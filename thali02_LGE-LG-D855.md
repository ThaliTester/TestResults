#### Test 846186378976bee_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 13:53:00.073  1564  1564 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 13:53:17.243  6771  6771 D AndroidRuntime: 
09-13 13:53:17.243  6771  6771 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 13:53:17.248  6771  6771 D AndroidRuntime: CheckJNI is OFF
09-13 13:53:17.370  6771  6771 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 13:53:17.375  1035  2017 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 13:53:17.384  1926  3944 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 13:53:17.389  1035  2017 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 13:53:17.389  1035  2017 D ActivityManager: setTaskToReturnTo : TaskRecord{2c2019dc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 13:53:17.389  1035  2017 D ActivityManager: setTaskToReturnTo : TaskRecord{2c2019dc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 13:53:17.391  1035  2017 D WindowStateEx: AppWindowTokenEx init.. 
09-13 13:53:17.392   336   354 E GBMv2   : DFP En is all cleared set to be enabled
09-13 13:53:17.428  1035  2017 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6786 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 13:53:17.429  6771  6771 D AndroidRuntime: Shutting down VM
09-13 13:53:17.475  1926  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 13:53:17.475  1926  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{391a2267 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 13:53:17.476  1926  3946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 13:53:17.476  1926  3946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9463814 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 13:53:17.525  6786  6786 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 13:53:17.591  6786  6786 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 13:53:17.597  6786  6786 I LibraryLoader: Loading: webviewchromium
09-13 13:53:17.599  6786  6786 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8032-8034)
09-13 13:53:17.599  6786  6786 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:53:17.614  6786  6786 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c76b7ad}
,09-13 13:53:17.615  6786  6786 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:53:17.615  6786  6786 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 13:53:17.623  6786  6786 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 13:53:17.624  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 13:53:17.642  6786  6786 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 13:53:17.642  6786  6786 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 13:53:17.643  6786  6786 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 13:53:17.650   319  2172 V AudioPolicyService: registerClient() client 0xb57d7e80, uid 10118
09-13 13:53:17.654  6786  6786 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:53:17.654  6786  6786 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:53:17.654  6786  6786 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:53:17.654  6786  6786 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:53:17.654  6786  6786 I Adreno-EGL: Remote Branch: 
09-13 13:53:17.654  6786  6786 I Adreno-EGL: Local Patches: 
09-13 13:53:17.654  6786  6786 I Adreno-EGL: Reconstruct Branch: 
09-13 13:53:17.659  1035  1117 D BluetoothManagerService: Message: 20
09-13 13:53:17.659  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23320786:true
,09-13 13:53:17.738  6786  6831 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 13:53:17.740  6786  6786 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 13:53:17.756  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 13:53:17.767  6786  6786 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 13:53:17.774  6786  6786 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 13:53:17.777  6786  6786 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 13:53:17.778  6786  6786 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 13:53:17.793  6786  6786 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 13:53:17.800  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 13:53:17.800  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 13:53:17.837  6786  6847 D OpenGLRenderer: Render dirty regions requested: true
09-13 13:53:17.837  6786  6847 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 13:53:17.854  6786  6847 D OpenGLRenderer: Enabling debug mode 0
,09-13 13:53:17.862  6786  6786 D Atlas   : Validating map...
09-13 13:53:17.867  1035  1558 D SplitWindow: check instance of lgWin Window{17b01910 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 13:53:17.921  6786  6845 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:53:17.922  6786  6845 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:53:18.048  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +574ms (total +656ms)
09-13 13:53:18.049  6786  6786 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10e22660 time:308484
,09-13 13:53:18.050  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2db43ae5 u0 com.test.thalitest/.MainActivity t6} time:308486
,09-13 13:53:18.241  6786  6786 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 13:53:18.325  6786  6845 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 13:53:18.325  6786  6845 I chromium: 
,09-13 13:53:18.492  6786  6861 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,09-13 13:53:18.498  6786  6786 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 13:53:18.498  6786  6786 I chromium: 
09-13 13:53:18.511  6786  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 13:53:18.511  6786  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 13:53:18.511  6786  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 13:53:18.511  6786  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 13:53:18.511  6786  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 13:53:18.511  6786  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31481d24 added. We now have 1 listener(s)
09-13 13:53:18.518  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:18.522  6786  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 13:53:18.525  6786  6861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 13:53:18.526  6786  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:53:18.526  6786  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 13:53:18.534  6786  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efb3253 added. We now have 1 listener(s)
09-13 13:53:18.535  6786  6861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:53:18.542  1035  1527 D WifiService: New client listening to asynchronous messages
,09-13 13:53:18.548  6786  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:53:18.548  6786  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 13:53:18.549  6786  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 13:53:18.549  6786  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 13:53:18.549  6786  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 13:53:18.553  6786  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:53:18.556  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:18.559  6786  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 13:53:18.574  6786  6861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:18.577  6786  6861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:53:18.577  6786  6861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 13:53:18.578  6786  6861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:53:18.580  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:18.582  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:18.582  6786  6861 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 13:53:18.628  6786  6786 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 13:53:19.344   336   356 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 13:53:19.344   336   356 E GBMv2   : Set value is all cleared set the max
09-13 13:53:19.344   336   356 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 13:53:19.610  6786  6864 W jxcore-log: Initializing JXcore engine
09-13 13:53:19.610  6786  6864 W jxcore-log: JXcore engine is ready
,09-13 13:53:19.646  6864  6864 W Thread-772: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10422]" dev="sockfs" ino=10422 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 13:53:19.646  6864  6864 W Thread-772: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-13 13:53:19.646  6864  6864 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10561]" dev="sockfs" ino=10561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 13:53:19.646  6864  6864 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 13:53:19.646  6864  6864 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32949]" dev="sockfs" ino=32949 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-13 13:53:19.669  6786  6864 W jxcore-log: Starting JXcore engine
09-13 13:53:19.747  6786  6864 W jxcore-log: Platform android
09-13 13:53:19.747  6786  6864 W jxcore-log: 
09-13 13:53:19.748  6786  6864 W jxcore-log: Process ARCH arm
09-13 13:53:19.748  6786  6864 W jxcore-log: 
,09-13 13:53:19.945  6786  6864 I jxcore-log: JXcore Cordova bridge is ready!
09-13 13:53:19.945  6786  6864 I jxcore-log: 
09-13 13:53:19.945  6786  6864 W jxcore-log: JXcore engine is started
,09-13 13:53:19.959  6786  6861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 13:53:19.964  6786  6786 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 13:53:33.475  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 13:53:33.475  6786  6864 I jxcore-log: 
,09-13 13:53:33.478  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 13:53:33.478  6786  6864 I jxcore-log: 
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:33.482  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:53:33.485  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:53:33.488  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 13:53:33.488  6786  6864 I jxcore-log: 
,09-13 13:53:33.490  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 13:53:33.490  6786  6864 I jxcore-log: 
09-13 13:53:33.832  6786  6864 I jxcore-log: Running unit tests
09-13 13:53:33.832  6786  6864 I jxcore-log: 
09-13 13:53:33.833  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:53:33.833  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@226d55a4 added. We now have 2 listener(s)
09-13 13:53:33.834  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:33.835  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 13:53:33.835  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:53:33.835  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:53:33.835  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:53:33.835  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197d9f0d added. We now have 2 listener(s)
09-13 13:53:33.835  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:53:33.836  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:53:33.838  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:33.840  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:53:33.841  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.841  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:53:33.841  6786  6864 D executeNativeTests: Running unit tests
09-13 13:53:33.845  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:33.849  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:53:33.921  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:53:33.921  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 added. We now have 3 listener(s),
09-13 13:53:33.922  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 13:53:33.923  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 13:53:33.923  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:53:33.923  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:53:33.923  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:53:33.923  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 added. We now have 3 listener(s)
09-13 13:53:33.923  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:53:33.924  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:53:33.927  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:33.931  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:53:33.933  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.933  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:53:33.938  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:33.939  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:33.940  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:53:33.941  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:33.941  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:33.941  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:33.944  6786  6864 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 13:53:33.944  6786  6864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 13:53:33.944  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 13:53:33.944  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:33.944  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:33.945  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:33.945  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:33.946  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:33.946  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:33.946  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:33.946  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:33.946  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:33.947  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:53:33.947  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 removed from the list
09-13 13:53:33.947  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:33.947  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 removed from the list
09-13 13:53:33.947  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:33.947  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.948  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:33.948  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.948  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:33.948  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:33.948  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:33.949  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:33.950  6786  6864 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 13:53:33.951  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:33.951  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:33.951  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:33.951  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:33.951  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:33.951  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.952  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:33.952  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:33.952  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:33.952  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:33.952  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:33.952  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09,-13 13:53:33.952  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:33.952  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.954  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:33.954  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:33.954  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:33.954  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 13:53:33.960  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 13:53:33.961  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 13:53:33.961  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:33.961  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:53:33.961  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:33.962  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:33.962  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:53:33.962  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.962  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:33.962  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 13:53:33.962  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:33.962  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:53:33.962  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:33.962  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.962  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:53:33.962  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:33.962  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:33.962  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:53:33.962  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:33.962  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:33.963  6786  6864 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 13:53:33.964  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:33.966  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:53:33.967  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:33.967  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:53:33.968  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:33.969  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:33.969  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:53:33.969  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:53:33.969  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:53:33.969  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:33.969  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:53:33.972  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:53:33.972  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:33.976  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 13:53:33.980  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:53:33.981  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 13:53:33.983  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:53:33.983  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:33.985  6786  6864 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 13:53:33.985  6786  6864 I io.jxcore.node.ConnectionHelper: start: OK
09-13 13:53:38.997  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:38.997  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:38.997  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:39.006  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:39.006  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:39.006  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:39.006  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:39.006  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:39.006  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:39.006  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 13:53:39.007  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:53:44.008  6786  6864 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 13:53:44.025  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:44.031  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:53:44.033  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:44.033  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:53:44.035  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:44.037  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:53:44.039  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:53:44.039  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:53:44.039  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:53:44.039  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:44.039  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:53:44.044  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:53:44.045  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:44.047  6786  6864 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 13:53:44.047  6786  6864 I io.jxcore.node.ConnectionHelper: start: OK
09-13 13:53:44.049  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:44.049  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:44.049  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:44.052  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:44.052  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:44.052  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:44.052  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:44.052  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:44.052  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:44.052  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:44.052  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:44.053  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:44.053  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:44.054  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:44.054  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:44.056  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:44.056  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:44.057  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:44.057  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:44.058  6786  6864 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 13:53:44.060  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:53:44.065  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:53:44.069  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:53:44.070  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:53:44.072  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:44.075  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:53:44.075  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:53:44.075  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:53:44.075  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:53:44.075  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:44.075  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:53:44.081  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 13:53:44.083  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:44.085  6786  6864 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 13:53:44.086  6786  6864 I io.jxcore.node.ConnectionHelper: start: OK
09-13 13:53:44.647  1035  3505 I LocationManagerService: remove 373f03a
09-13 13:53:44.648  1035  3505 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-13 13:53:44.648  1035  3505 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:53:44.649  1035  3505 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-13 13:53:44.650  1035  3505 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
09-13 13:53:44.651  1035  3505 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,09-13 13:53:49.086  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:49.086  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:49.086  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:54.096  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.097  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.097  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:54.103  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.103  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.103  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:53:54.103  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.103  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.104  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.104  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.104  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.107  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.107  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.108  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.108  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.109  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.109  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.109  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.109  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.110  6786  6864 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 13:53:54.111  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.111  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.111  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:54.111  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.111  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.111  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.112  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.112  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.112  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.112  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.112  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.112  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: 2 listener(s) left
09-13 13:53:54.112  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.112  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:53:54.117  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.117  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.118  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.118  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.118  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.118  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.120  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 13:53:54.120  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.120  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.120  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:54.121  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.121  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.121  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.121  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.121  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.121  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.121  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.121  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.121  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.121  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.121  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.122  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.122  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.123  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.123  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.123  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.123  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.124  6786  6864 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 13:53:54.125  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.125  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.125  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:54.129  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.129  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.129  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.129  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
,09-13 13:53:54.129  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.129  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.129  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:53:54.130  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.130  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.130  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.130  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.131  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.131  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.132  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.132  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.132  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.132  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.133  6786  6864 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 13:53:54.133  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.133  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.133  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:54.134  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.134  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.134  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.134  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.134  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.134  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.134  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.134  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.134  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.134  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.134  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.136  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.136  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.136  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.136  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.137  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.137  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.137  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:53:54.141  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:54.141  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:54.141  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 13:53:54.148  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:54.148  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:54.148  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:53:54.149  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:54.149  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:53:54.149  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.149  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.149  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:54.151  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.151  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.151  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.151  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.152  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.152  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.152  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.152  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.152  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.152  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.152  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.156  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.156  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:53:54.162  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.162  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.162  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.162  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.166  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:53:54.166  6786  6864 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 13:53:54.166  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 13:53:54.169  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:53:54.169  6786  6864 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:,1810:1810:1810]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 13:53:54.170  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 13:53:54.171  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 13:53:54.171  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 13:53:54.171  6786  6864 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:53:54.171  6786  6864 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 13:53:54.171  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-13 13:53:54.171  6786  6864 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:53:54.172  6786  6864 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 13:53:54.172  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:53:54.172  6786  6864 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:53:54.172  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 13:53:54.175  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 13:53:54.177  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 13:53:54.177  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 13:53:54.178  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 13:53:54.178  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-13 13:53:54.178  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 13:53:54.178  6786  6864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:53:54.178  6786  6864 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 13:53:54.179  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.179  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:53:54.179  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:54.190  6786  6869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
09-13 13:53:54.195  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.195  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.195  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.195  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 13:53:54.196  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.196  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.196  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.196  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.196  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.196  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.196  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.196  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:53:54.201  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.201  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.201  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.201  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.201  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.202  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.204  6786  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
09-13 13:53:54.204  6786  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
09-13 13:53:54.205  6786  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
09-13 13:53:54.205  6786  6864 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 13:53:54.205  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.205  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.206  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:54.206  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.206  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.206  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.206  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.206  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.206  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.206  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.206  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.206  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.206  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.206  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.207  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.207  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.208  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.208  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.208  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.208  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSett,ings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.209  6786  6864 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 13:53:54.210  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.210  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.210  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:54.216  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.216  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.216  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.216  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.216  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.216  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.216  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.216  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.216  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.216  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.216  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.217  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.218  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.218  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.218  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.218  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.218  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.224  6786  6864 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 13:53:54.224  6786  6864 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 13:53:54.225  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:53:54.225  6786  6864 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 13:53:54.225  6786  6864 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 13:53:54.225  6786  6864 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 13:53:54.225  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:53:54.225  6786  6864 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 13:53:54.225  6786  6864 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 13:53:54.225  6786  6864 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 13:53:54.225  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:53:54.225  6786  6864 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 13:53:54.225  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:54.225  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:54.225  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:54.229  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.229  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.230  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.230  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.230  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.230  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.230  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.230  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.230  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.230  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.230  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.231  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:54.231  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:54.232  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:54.232  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:54.232  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.232  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.233  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:54.233  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.233  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.233  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:54.233  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:54.233  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:54.233  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:54.233  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:54.233  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:54.318  6786  6869 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-13 13:53:54.319  6786  6869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
,09-13 13:53:59.235  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.235  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.236  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.236  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.236  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.236  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.236  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:59.236  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:59.237  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:53:59.246  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.246  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.246  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.246  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.246  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.246  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.246  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:59.246  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.246  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.247  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.247  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.248  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:59.248  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:59.249  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:59.249  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:59.249  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.249  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.252  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 13:53:59.252  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:53:59.253  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 13:53:59.254  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 13:53:59.254  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 13:53:59.258  6786  6786 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 13:53:59.258  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 13:53:59.261  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:53:59.262  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.262  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 13:53:59.262  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 13:53:59.262  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 13:53:59.262  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.262  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 13:53:59.263  1035  1617 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:59.264  6786  6887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:53:59.265  6786  6786 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 13:53:59.266  3856  3873 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-13 13:53:59.267  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.267  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.268  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:53:59.268  6786  6864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:53:59.268  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:53:59.272  6786  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 13:53:59.272  6786  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 13:53:59.272  6786  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 13:53:59.273  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:53:59.275  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:53:59.275  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:53:59.275  6786  6864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:53:59.275  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.275  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.276  6786  6864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:53:59.277  6786  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:53:59.278  6786  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:53:59.278  6786  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 13:53:59.278  6786  6786 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:53:59.279  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.279  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:59.279  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:59.279  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:59.280  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.280  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.280  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.280  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.280  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.280  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.280  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:59.280  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.280  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.280  6786  6864 W, org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.280  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:53:59.285  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:59.285  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:59.285  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.285  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.286  6786  6864 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 13:53:59.287  6786  6864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 13:53:59.287  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 13:53:59.289  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:59.289  6786  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:53:59.289  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:59.289  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:59.289  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:59.292  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.292  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.292  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:53:59.294  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.294  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.294  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.294  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:59.294  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.294  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.294  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.294  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.298  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:59.298  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:59.298  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.298  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.301  1035  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:59.302  1035  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:53:59.303  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 13:53:59.306  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:59.306  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:59.306  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:59.307  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.307  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.307  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.307  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.307  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.307  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.307  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:59.307  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.307  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.307  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.307  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.308  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:59.309  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:59.309  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.309  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.310  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:53:59.310  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:53:59.310  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:53:59.311  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:53:59.311  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.311  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.311  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535e8c3 not in the list
09-13 13:53:59.311  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.311  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.311  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:53:59.311  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.311  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.311  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:53:59.311  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:53:59.312  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:53:59.312  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:53:59.312  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:53:59.312  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb1b540 not in the list
09-13 13:53:59.314  6786  6864 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 13:53:59.314  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:53:59.315  6786  6864 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 13:53:59.315  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:53:59.315  6786  6864 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 13:53:59.315  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:53:59.317  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 13:53:59.317  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 13:53:59.318  6786  6864 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 13:53:59.318  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 13:53:59.319  6786  6864 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 13:53:59.319  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 13:53:59.319  6786  6864 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 13:53:59.319  6786  6864 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 13:53:59.320  6786  6864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 13:53:59.320  6786  6864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed,
09-13 13:53:59.321  6786  6864 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 13:53:59.321  6786  6864 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 13:53:59.321  6786  6864 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 13:53:59.321  6786  6864 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 13:53:59.322  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:53:59.322  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@287fa1b1 added. We now have 3 listener(s)
09-13 13:53:59.322  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:53:59.326  6786  6864 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 13:53:59.334  1035  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6786, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 13:53:59.335  1035  1051 D WifiService: setWifiEnabled: true pid=6786, uid=10118
09-13 13:53:59.335  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 13:53:59.779  6786  6786 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:54:00.094  1564  1564 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 13:54:00.094  1564  1564 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 13:54:00.095  1564  1564 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 13:54:00.095  1564  1564 I [SystemUI]Clock: called onTimeUpdated()
,09-13 13:54:00.106  1564  1564 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 13:54:00.106  1564  1564 I [SystemUI]DateView: called onTimeUpdated()
09-13 13:54:00.107  1564  1564 I [SystemUI]DateView: called onTimeUpdated()
09-13 13:54:00.108  1564  1564 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 13:54:04.343  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:54:04.343  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2181f696 added. We now have 4 listener(s)
09-13 13:54:04.343  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:54:04.363  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:54:04.363  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2181f696 removed from the list
09-13 13:54:04.363  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:04.363  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:54:04.363  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:54:04.366  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:54:04.366  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b7be217 added. We now have 4 listener(s)
09-13 13:54:04.366  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:54:04.368  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:54:04.368  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b7be217 removed from the list
09-13 13:54:04.368  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:04.368  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:54:04.368  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:54:04.369  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:54:04.369  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@376c7604 added. We now have 4 listener(s)
09-13 13:54:04.369  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:54:04.372  1035  1943 D WifiServiceImplEx: setWifiEnabled: false pid=6786, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 13:54:04.372  1035  1943 D WifiService: setWifiEnabled: false pid=6786, uid=10118
09-13 13:54:04.372  1035  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:54:04.391  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:04.392  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:04.392  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 13:54:04.394  1035  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:04.395  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:04.395  1035  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:04.396  1035  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:04.396  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:04.396  1035  1521 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 13:54:04.396  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:54:04.396  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 13:54:04.397  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 13:54:04.397  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 13:54:04.400  1035  1618 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:04.400  1035  1618 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@7d19b6e mBinding = false
,09-13 13:54:04.406  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 13:54:04.406  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.406  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.407  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 13:54:04.408  2656  2656 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 13:54:04.408  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 13:54:04.408  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:04.409  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:04.410  1035  2825 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.415   314   893 D CommandListener: Clearing all IP addresses on wlan0
,09-13 13:54:04.429  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:04.429  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:04.429  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 13:54:04.434  1035  1117 D BluetoothManagerService: Message: 2
09-13 13:54:04.435  1035  1117 D BluetoothManagerService: Sending off request.
,09-13 13:54:04.437  3856  3872 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 13:54:04.443  3856  3936 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 13:54:04.444  3856  3936 D BluetoothAdapterProperties: Setting state to 13
09-13 13:54:04.444  3856  3936 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 13:54:04.445  3856  3936 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 13:54:04.445  3856  3936 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 13:54:04.457  3856  3939 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:54:04.460  3856  3936 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 13:54:04.461  3856  3936 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 13:54:04.463  3856  4226 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 13:54:04.464  3856  4227 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:04.464  3856  4282 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:04.467  3856  4283 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:04.468  3856  4289 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:04.473  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,09-13 13:54:04.475  3856  4035 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 13:54:04.478  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 13:54:04.478  3856  4035 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 13:54:04.484  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:04.485  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:54:04.488  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.488  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:04.502  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:04.502  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:54:04.525  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.525  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:04.528  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 13:54:04.529  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-13 13:54:04.534  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:04.534  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 13:54:04.534  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 13:54:04.553  1035  2036 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-13 13:54:04.554  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.554  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.554  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 13:54:04.554  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.554  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-13 13:54:04.562  1035  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6910 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 13:54:04.566  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=669963053, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-13 13:54:04.567  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.568  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.568  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.569  1035  1520 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.569  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.569  1035  1520 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@38ca9013
09-13 13:54:04.570  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.570  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.570  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.571  1035  1521 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 13:54:04.571  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.571  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.572  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:04.573  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 13:54:04.573  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:04.574  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:04.576  1035  1520 D LGWifiP2pService: P2pDisablingState
09-13 13:54:04.576  1035  1520 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.576  1035  1520 D LGWifiP2pService: p2p socket connection lost
09-13 13:54:04.576  1035  1520 D LGWifiP2pService: P2pDisabledState
09-13 13:54:04.576  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.576  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 13:54:04.577  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 13:54:04.577  2656  2656 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 13:54:04.577  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.577  1035  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.577  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 13:54:04.577  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:04.578  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
,09-13 13:54:04.580  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:04.581  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 13:54:04.581  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.581  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.581  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:04.581  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 13:54:04.582  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.582  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.582  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:04.582  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 13:54:04.583  1035  1539 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.583  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 13:54:04.583  1035  1540 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.583   314   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:54:04.584   314  6923 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 13:54:04.584  3856  3856 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:04.584  3856  3856 D BluetoothMapService: STATE_TURNING_OFF
09-13 13:54:04.584  1035  1528 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 13:54:04.584  1035  1528 D DSQN    : disableDataServiceNotify
09-13 13:54:04.585  3856  3856 V BtOppService: Receiver DISABLED_ACTION 
09-13 13:54:04.585  1035  1528 D DSQN    : stop dsqn bin
09-13 13:54:04.585  3856  3856 V BluetoothMapService: Handler(): got msg=4
,09-13 13:54:04.585  3856  3856 D BluetoothMapService: MAP Service closeService in
09-13 13:54:04.585  3856  3856 D BluetoothMapMasInstance: MAP Service shutdown
09-13 13:54:04.585  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 13:54:04.585  3856  3856 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 13:54:04.585  3856  3856 V BluetoothMapService: MAP Service closeService out
,09-13 13:54:04.585  3856  3856 I BtOppRfcommListener: stopping Accept Thread
09-13 13:54:04.585  3856  3856 V BtOppRfcommListener: close mBtServerSocket
09-13 13:54:04.585  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 13:54:04.585  3856  3856 V BtOppRfcommListener: waiting for thread to terminate
09-13 13:54:04.586  3856  4282 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 13:54:04.586  3856  3856 V BtOppRfcommListener: done waiting for thread to terminate
09-13 13:54:04.588  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:04.588  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:04.588  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.588  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:04.588  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 13:54:04.589  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:04.589  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:04.589  1926  1926 D WfdsService: WifiP2pState is changed : false
09-13 13:54:04.589  1926  2251 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 13:54:04.589  1926  2251 D WfdsService: Set the WFDS Monitor: false
09-13 13:54:04.590  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:04.590  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:04.591  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return ,stored value
09-13 13:54:04.591  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:04.591  1926  2251 D WfdsMonitor: WFDS Monitor is stopped
09-13 13:54:04.591  1926  2251 D WfdsService: STATE : WfdsDisabledState - enter
09-13 13:54:04.591  1926  2252 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 13:54:04.591  1926  2728 D CtrlSupplicant: Received on exit socket, terminate
09-13 13:54:04.591  1926  2728 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 13:54:04.591  1926  2728 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 13:54:04.591  1926  2728 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,09-13 13:54:04.592  1926  2251 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 13:54:04.592  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 13:54:04.592  3856  3856 V BtOppService: onDestroy
09-13 13:54:04.593  1035  1528 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 13:54:04.593  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:04.593  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:04.593  1035  1528 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:04.593  1035  1528 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 13:54:04.593  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 13:54:04.594  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.594  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.595  1035  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 13:54:04.596  1035  1528 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 13:54:04.596  1035  1528 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 13:54:04.596  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 13:54:04.596  1035  1521 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 13:54:04.597  1035  1521 D WifiNative-p2p0: TERMINATE: returned true
09-13 13:54:04.597  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:04.597  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:04.597  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 13:54:04.598  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 13:54:04.599  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 13:54:04.599  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.599  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.599  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:04.599  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 13:54:04.599  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 13:54:04.599  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 13:54:04.599  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 13:54:04.601  1926  1926 V WfdStateTracker: WfdStateTracker handleDi,rectStateChangedEvent: 6
09-13 13:54:04.601  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:04.602  1035  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:04.602  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 13:54:04.602  1035  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:04.603  1035  1528 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:04.603  1035  1528 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:04.603  1035  1528 D NetworkManagementService: Removing idletimer
09-13 13:54:04.603  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:04.603  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:04.603  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 13:54:04.603  1035  1528 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.603  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:04.603  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 13:54:04.604  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 13:54:04.604  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:04.604  1035  1521 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:04.604  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:04.605  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.605  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:04.606  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 13:54:04.606  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will re,turn stored value
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:04.606  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:04.607  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.607  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:04.607  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 13:54:04.608  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 13:54:04.608  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 13:54:04.608  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 13:54:04.608  1035  1528 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 13:54:04.645  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 13:54:04.645  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 13:54:04.647  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 13:54:04.670  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:04.671  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.671  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.672  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.688  1035  1962 I art     : Explicit concurrent mark sweep GC freed 53407(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.366ms total 174.090ms
,09-13 13:54:04.688  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:54:04.689  3856  3856 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 13:54:04.692  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:04.692  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:04.692  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.692  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:04.692  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:54:04.693  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:04.694  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:04.697  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:04.697  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.698  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.705  2661  2661 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 13:54:04.745  2656  2656 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 13:54:04.745  2656  2656 I wpa_supplicant: monitor socket send errors count : 1
09-13 13:54:04.745  2656  2656 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-2\x00 that cannot receive messages
09-13 13:54:04.746  1035  2722 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 13:54:04.746  1035  2722 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-13 13:54:04.748  1035  2825 D DhcpStateMachine: StoppedState
09-13 13:54:04.748  1035  2825 D DhcpStateMachine: StoppedState{ when=-171ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:04.763  1035  1748 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6935 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 13:54:04.765  1035  1521 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 13:54:04.766  1035  1521 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 13:54:04.775  6910  6910 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 13:54:04.775  6910  6910 W LG Account v2.2: No ProfileInfo entries
09-13 13:54:04.775  6910  6910 I LG Account v2.2: isEnabled: false
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Country: EU
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Operator: OPEN
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Ranking support: false
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Comfort support: false
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Accessory: true
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Health device: true
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Extra Pedometer: false
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Blood glucose device: false
09-13 13:54:04.775  6910  6910 I Feature : [Lifetracker]Device Number: 3
,09-13 13:54:04.783  2656  2656 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:54:04.783  1035  2722 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 13:54:04.783  1035  2722 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:54:04.783  1035  2722 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:54:04.784  2656  2656 W wpa_supplicant: USIM:  scard_deinit function
09-13 13:54:04.785  1035  2722 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 13:54:04.785  1035  2722 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:04.785  1035  2722 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:04.785  1035  1521 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=355207
09-13 13:54:04.785  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 13:54:04.786  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 13:54:04.787  1035  1521 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=355208
09-13 13:54:04.787  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:04.787  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=355208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 13:54:04.788  1035  1521 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=355209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 13:54:04.788  1035  1521 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:04.788  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 13:54:04.803  6935  6935 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:54:04.803  6935  6935 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,09-13 13:54:04.803  6935  6935 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:04.804  6935  6935 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 13:54:04.805  6935  6935 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 13:54:04.806  6935  6935 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 13:54:04.808  1035  2036 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6953 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 13:54:04.810  1035  2036 I ActivityManager: Killing 6252:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 13:54:04.839  1035  1558 W libprocessgroup: failed to open /acct/uid_10014/pid_6252/cgroup.procs: No such file or directory
,09-13 13:54:04.845  2656  2656 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 13:54:04.850  1035  2722 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 13:54:04.850  1035  2722 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 13:54:04.851  1035  2722 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-13 13:54:04.852  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-13 13:54:04.853  1926  1926 D WfdsService: Supplicant Connection state is changed : false
09-13 13:54:04.853  1035  1521 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 13:54:04.854  1926  2251 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 13:54:04.854  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:04.854  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:04.854  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 13:54:04.854  1926  2251 D WfdsService: Set the WFDS Monitor: false
09-13 13:54:04.854  1926  2251 D WfdsMonitor: WFDS Monitor is stopped
09-13 13:54:04.855  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 13:54:04.855  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 13:54:04.856  1035  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 13:54:04.856  1035  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 13:54:04.857  2487  2487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:04.857  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:04.859  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:04.859  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:04.860  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:04.861  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:04.882  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-13 13:54:04.889  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:04.889  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 13:54:04.889  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:04.892  1035  1998 I ActivityManager: Killing 2154:com.lge.music/u0a34 (adj 15): empty #17
09-13 13:54:04.894  1035  1117 D BluetoothManagerService: Message: 20
09-13 13:54:04.894  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22f01621:true
,09-13 13:54:04.906   319  1369 V AudioFlinger: 2154 died, releasing its sessions
09-13 13:54:04.907   319  1369 V AudioFlinger:  pid 1837 @ 0
09-13 13:54:04.907   319  1369 V AudioFlinger:  pid 3423 @ 1
09-13 13:54:04.907   319  1369 V AudioFlinger:  pid 3423 @ 2
,09-13 13:54:04.927  1035  1943 W libprocessgroup: failed to open /acct/uid_10034/pid_2154/cgroup.procs: No such file or directory
,09-13 13:54:04.931  1035  1117 D BluetoothManagerService: Message: 30
09-13 13:54:04.934  3856  3856 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 13:54:04.934  3856  3856 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:04.934  3856  3856 V BluetoothPbapReceiver: ***********state = 13
09-13 13:54:04.936  3856  3856 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 13:54:04.937  3856  3856 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:04.937  3856  3856 V BluetoothPbapService: state: 13
09-13 13:54:04.937  3856  3856 V BluetoothPbapService: Pbap Service closeService in
09-13 13:54:04.941  3856  3856 V BluetoothPbapService: successfully stopped pbap service
,09-13 13:54:04.941  3856  3856 V BluetoothPbapService: Pbap Service closeService out
09-13 13:54:04.941  3856  3856 V BluetoothPbapService: Pbap Service onDestroy
,09-13 13:54:04.941  3856  3856 V BluetoothPbapService: Pbap Service closeService in
09-13 13:54:04.941  3856  3856 V BluetoothPbapService: Pbap Service closeService out
09-13 13:54:04.941  3856  3856 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 13:54:04.942  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:54:04.942  1035  1117 D BluetoothManagerService: Message: 30
09-13 13:54:04.949  6935  6935 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 13:54:04.951  6935  6935 D BluetoothMap: Create BluetoothMap proxy object
09-13 13:54:04.951  1035  1117 D BluetoothManagerService: Message: 30
09-13 13:54:04.958  1035  1117 D BluetoothManagerService: Message: 30
09-13 13:54:04.959  6935  6935 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 13:54:04.960  6935  6935 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-13 13:54:04.973  6935  6935 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-13 13:54:04.980  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 13:54:04.994  6935  6935 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:54:05.020  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:05.072  6935  6935 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:05.072  6935  6935 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:05.084  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:05.085  6935  6935 D BluetoothInputDevice: Proxy object connected
09-13 13:54:05.086  6935  6935 D HidProfile: Bluetooth service connected
,09-13 13:54:05.089  6935  6935 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:54:05.090  6935  6935 D PanProfile: Bluetooth service connected
09-13 13:54:05.091  6935  6935 D BluetoothMap: Proxy object connected
09-13 13:54:05.091  6935  6935 D MapProfile: Bluetooth service connected
09-13 13:54:05.091  6935  6935 D BluetoothMap: getConnectedDevices()
09-13 13:54:05.092  6935  6935 D BluetoothMap: Bluetooth is Not enabled
,09-13 13:54:05.102  6935  6935 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-13 13:54:05.108  6935  6935 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 13:54:05.114  6935  6935 D BluetoothPermissionRequest: onReceive
09-13 13:54:05.120  6935  6935 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 13:54:05.137  1035  1558 I ActivityManager: Killing 6417:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-13 13:54:05.140  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 13:54:05.178  3856  3856 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-13 13:54:05.178  3856  3856 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 13:54:05.180  3856  3856 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 13:54:05.182  1035  1907 W libprocessgroup: failed to open /acct/uid_10004/pid_6417/cgroup.procs: No such file or directory
09-13 13:54:05.305  1035  1906 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6988 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 13:54:05.311  3856  3856 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:05.311  3856  3856 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 13:54:05.314  3856  3856 V BluetoothFtpService: Ftp Service onStartCommand
09-13 13:54:05.315  3856  3856 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:05.315  3856  3856 V BluetoothFtpService: Ftp Service closeService
09-13 13:54:05.315  3856  3856 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 13:54:05.316  3856  3856 V BluetoothFtpService: successfully stopped ftp service
09-13 13:54:05.316  3856  3856 V BluetoothFtpService: Ftp Service onDestroy
09-13 13:54:05.316  3856  3856 V BluetoothFtpService: Ftp Service closeService
09-13 13:54:05.319   340   340 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 460us total 24.597ms
,09-13 13:54:05.325  3856  3856 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:05.325  3856  3856 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:05.325  3856  3856 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:05.325  3856  3856 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:05.325  3856  3856 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 13:54:05.325  3856  3856 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 13:54:05.327  3856  3856 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:05.327  3856  3856 V BluetoothSapService: state: 13
09-13 13:54:05.327  3856  3856 V BluetoothSapService: Stopping SAP server process
09-13 13:54:05.330  3856  3856 V BluetoothSapService: Sap Service closeSapService in
09-13 13:54:05.330  3856  3856 V BluetoothSapService: Close listen Socket : 
09-13 13:54:05.330  3856  3856 V BluetoothSapService: Close rfcomm Socket : 
09-13 13:54:05.330  3856  3856 V BluetoothSapService: Close sapd  Socket : 
09-13 13:54:05.333  3856  3856 V BluetoothSapService: Sap Service closeSapService out
09-13 13:54:05.334  3856  3856 V BluetoothSapService: Sap Service onDestroy
09-13 13:54:05.334  3856  3856 V BluetoothSapService: Sap Service closeSapService in
09-13 13:54:05.334  3856  3856 V BluetoothSapService: Close listen Socket : 
09-13 13:54:05.334  3856  3856 V BluetoothSapService: Close rfcomm Socket : 
09-13 13:54:05.334  3856  3856 V BluetoothSapService: Close sapd  Socket : 
,09-13 13:54:05.344   340   340 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 23.653ms
09-13 13:54:05.366   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 19.330ms
,09-13 13:54:05.419  1035  1906 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7013 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 13:54:05.420  3856  3856 V BluetoothSapService: Sap Service closeSapService out
,09-13 13:54:05.445  6988  6988 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 13:54:05.465  6988  6988 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 13:54:05.479  3856  3939 D bt_hci_bdroid: cleanup
09-13 13:54:05.479  3856  4037 I bt_lpm  : LPM is already off!!!
09-13 13:54:05.479  3856  4212 I bt_userial_mct: exiting userial_read_thread
09-13 13:54:05.479  3856  4212 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 13:54:05.479  3856  4035 W bt-btif : ag scb idx 1 not allocated
09-13 13:54:05.479  3856  4035 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:05.479  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:05.480  3856  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:05.480  3856  4035 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 13:54:05.480  3856  3939 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 13:54:05.480  3856  4037 I bt_vendor: hw_epilog_process
09-13 13:54:05.480  3856  3939 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 13:54:05.480  3856  3939 D bt_userial_mct: userial_close
09-13 13:54:05.480  3856  3939 E bt_userial_mct: pthread_join() FAILED result:3
09-13 13:54:05.480  3856  3939 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-13 13:54:05.491  7013  7013 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:05.499  6988  6988 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 13:54:05.499  6988  6988 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 13:54:05.500  6988  6988 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 13:54:05.500  6988  6988 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 13:54:05.500  6988  6988 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 13:54:05.502  6988  6988 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-13 13:54:05.506  6988  6988 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 13:54:05.508  1035  1980 I ActivityManager: Killing 6527:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-13 13:54:05.537  1035  1050 W libprocessgroup: failed to open /acct/uid_10008/pid_6527/cgroup.procs: No such file or directory
,09-13 13:54:05.542  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:05.546  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:05.554  3856  3939 D bt_hci_bdroid: set_power 0
09-13 13:54:05.554  3856  3939 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 13:54:05.554  3856  3939 I bt_vendor: bluetooth satus is on
09-13 13:54:05.554  3856  3939 I bt_vendor: bt-vendor : resetting BT status
09-13 13:54:05.554  3856  3939 I bt_vendor: Starting hciattach daemon
09-13 13:54:05.555  3856  3939 I bt_vendor: try to set false
,09-13 13:54:05.556  3856  3939 I bt_vendor: Starting hciattach daemon
09-13 13:54:05.556  3856  3939 I bt_vendor: try to set false
09-13 13:54:05.556  3856  3939 I bt_vendor: cleanup
09-13 13:54:05.558  3856  4035 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 13:54:05.558  3856  3939 I GKI_LINUX: GKI_exit_task 0 done
09-13 13:54:05.558  3856  3939 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 13:54:05.560  3856  3936 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 13:54:05.562  3856  3856 D HeadsetService: Received stop request...Stopping profile...
09-13 13:54:05.564  3856  3856 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-13 13:54:05.564  3856  3856 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:54:05.564  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.565  3856  3963 D HeadsetStateMachine: Exit Disconnected: -1
09-13 13:54:05.566  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:05.566  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 13:54:05.566  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:05.566  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:05.567  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:05.569  3856  3856 D A2dpService: Received stop request...Stopping profile...
09-13 13:54:05.570  3856  3999 D A2dpStateMachine: Exit Disconnected: -1
09-13 13:54:05.571  3856  3856 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-13 13:54:05.574  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:05.575  3856  3856 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 13:54:05.575  3856  3856 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:54:05.575  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.578  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 13:54:05.578  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 13:54:05.579  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:05.580  3856  3936 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 13:54:05.580  3856  3856 D HidService: Received stop request...Stopping profile...
09-13 13:54:05.580  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.582  3856  3856 D HeadsetStateMachine: Unbinding service...
09-13 13:54:05.582  6935  6935 D BluetoothInputDevice: Proxy object disconnected
09-13 13:54:05.582  6935  6935 D HidProfile: Bluetooth service disconnected
09-13 13:54:05.584  6988  6988 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-13 13:54:05.585  3856  3856 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 13:54:05.585  3856  3856 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 13:54:05.585  3856  3856 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 13:54:05.585  3856  3856 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 13:54:05.585  3856  3856 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 13:54:05.585  3856  3856 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:54:05.585  3856  3856 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 13:54:05.586  3856  3856 D HealthService: Received stop request...Stopping profile...
09-13 13:54:05.586  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.589  6988  6988 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-13 13:54:05.591  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 13:54:05.591  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:05.591  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:05.592  3856  3856 D PanService: Received stop request...Stopping profile...
09-13 13:54:05.593  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.598  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:05.600  3856  3856 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 13:54:05.601  3856  3856 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 13:54:05.601  3856  3856 D BtGatt.GattService: stop()
09-13 13:54:05.601  3856  3856 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 13:54:05.602  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.603  3856  3856 I BluetoothA2dpServiceJni: cleanupNative
09-13 13:54:05.603  3856  4000 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 13:54:05.604  3856  3856 I GKI_LINUX: GKI_exit_task 2 done
09-13 13:54:05.604  3856  3856 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 13:54:05.605  3856  3856 D BluetoothMapService: Received stop request...Stopping profile...
09-13 13:54:05.605  3856  3856 D BluetoothMapService: stop()
09-13 13:54:05.606  3856  3856 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 13:54:05.606  3856  3856 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 13:54:05.606  3856  3856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37511ae2
09-13 13:54:05.607  3856  3856 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 13:54:05.607  3856  3856 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 13:54:05.608  3856  3856 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 13:54:05.608  3856  3856 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:54:05.608  3856  3856 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:54:05.608  3856  3856 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 13:54:05.608  3856  3856 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 13:54:05.609  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:05.609  3856  3856 V BluetoothMapService: Handler(): got msg=4
09-13 13:54:05.609  3856  3856 D BluetoothMapService: MAP Service closeService in
09-13 13:54:05.609  3856  3856 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 13:54:05.609  3856  3856 V BluetoothMapService: MAP Service closeService out
09-13 13:54:05.609  6935  6935 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:54:05.609  6935  6935 D PanProfile: Bluetooth service disconnected
09-13 13:54:05.610  6935  6935 D BluetoothMap: Proxy object disconnected
09-13 13:54:05.610  6935  6935 D MapProfile: Bluetooth service disconnected
09-13 13:54:05.610  3856  3936 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 13:54:05.610  3856  3936 D BluetoothAdapterProperties: Setting state to 10
09-13 13:54:05.610  3856  3936 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 13:54:05.610  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:05.610  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 13:54:05.610  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 13:54:05.610  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:54:05.611  3856  3936 I BluetoothAdapterState: Entering OffState
09-13 13:54:05.611  3856  3856 D BluetoothMapService: cleanup()
09-13 13:54:05.611  3856  3856 D BluetoothMapService: MAP Service closeService in
09-13 13:54:05.611  3856  3856 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 13:54:05.611  3856  3856 V BluetoothMapService: MAP Service closeService out
09-13 13:54:05.612  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:05.613  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 13:54:05.614  6935  6951 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:54:05.615  6935  6950 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 13:54:05.616  6935  6973 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:54:05.617  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:05.618  6935  6951 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:54:05.623  1837  2430 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:05.624  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:05.624  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:05.625  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 13:54:05.625  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-13 13:54:05.626  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:05.629  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 13:54:05.629  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 13:54:05.629  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@7d19b6e mBinding = false
09-13 13:54:05.630  1035  1117 D BluetoothManagerService: Sending unbind request.
09-13 13:54:05.630  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=669963053 [*alarm*], flags=0x0
09-13 13:54:05.633  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:05.637  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-13 13:54:05.638  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 13:54:05.638  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:05.638  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:05.645  3856  3939 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-13 13:54:05.646  3856  3856 I GKI_LINUX: GKI_exit_task 1 done
,09-13 13:54:05.646  3856  3856 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 13:54:05.647  3856  3856 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 13:54:05.647  3856  3856 I art     : --- WEIRD: removing null entry 246
09-13 13:54:05.647  3856  3856 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-13 13:54:05.647  3856  3856 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 13:54:05.652  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:05.653  3856  3856 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 13:54:05.655  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:05.656  1926  2087 D LGBluetoothAPIService: Message: 2
09-13 13:54:05.656  1926  2087 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@b7428bd mBinding = false
09-13 13:54:05.657  1926  2087 D LGBluetoothAPIService: Sending unbind request.
09-13 13:54:05.657  3856  3856 I art     : System.exit called, status: 0
09-13 13:54:05.657  3856  3856 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 13:54:05.663  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:05.664  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:05.665  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:05.666  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:05.670  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:05.671  6935  6935 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 13:54:05.672  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 13:54:05.672  6935  6935 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 13:54:05.673  1564  1564 D BluetoothAdapter: 420809189: getState() :  mService = null. Returning STATE_OFF
09-13 13:54:05.673  1564  1564 D BluetoothAdapter: 420809189: getState() :  mService = null. Returning STATE_OFF
09-13 13:54:05.674  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 13:54:05.679   319   319 V AudioFlinger: 3856 died, releasing its sessions
09-13 13:54:05.679   319   319 V AudioFlinger:  pid 1837 @ 0
09-13 13:54:05.679   319   319 V AudioFlinger:  pid 3423 @ 1
09-13 13:54:05.679   319   319 V AudioFlinger:  pid 3423 @ 2
,09-13 13:54:05.682  6935  6935 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 13:54:05.704  1035  1925 I ActivityManager: Process com.android.bluetooth (pid 3856) has died
09-13 13:54:05.705  1035  1925 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-13 13:54:05.711  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:54:05.711  6935  6935 D DockEventReceiver: finishStartingService: stopping service
09-13 13:54:05.717  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:05.717  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:05.721  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:05.760  1035  1051 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7041 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 13:54:05.763  6935  6935 D BluetoothPermissionRequest: onReceive
09-13 13:54:05.765  6935  6935 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 13:54:05.766  6935  6935 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 13:54:05.768  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 13:54:05.833  1035  1748 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7058 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 13:54:05.869  7058  7058 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-13 13:54:05.869  7058  7058 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:05.869  7058  7058 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-13 13:54:05.870  7058  7058 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 13:54:05.872  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:05.874  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 13:54:05.877  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:05.887  7041  7077 W FormManager: Network not available. Please check & try again.
,09-13 13:54:05.888  7058  7058 D BluetoothAdapterApp: Loading JNI Library
09-13 13:54:05.891  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 13:54:05.891  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 13:54:05.891  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 13:54:05.891  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 13:54:05.892  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:05.897  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:05.897  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 13:54:05.897  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:05.897  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:05.898  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:05.898  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 13:54:05.899  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-13 13:54:05.899  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 13:54:05.900  7041  7078 V FormManager: Network unavailable.
09-13 13:54:05.903  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:05.906  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:05.907  7041  7078 V FormManager: Network unavailable.
09-13 13:54:05.911  4291  7081 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 13:54:05.913  4291  7082 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-13 13:54:05.913  4291  7082 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:05.915  7058  7058 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2272aafb Instance Count = 1
09-13 13:54:05.918  7058  7058 D BluetoothAdapterApp: onCreate
09-13 13:54:05.922  7041  7083 W FormManager: Network not available. Please check & try again.
09-13 13:54:05.923  7041  7084 V FormManager: Network unavailable.
,09-13 13:54:05.925  7041  7084 V FormManager: Network unavailable.
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: Adding HeadsetService
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: Adding A2dpService
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: Adding HidService
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 13:54:05.933  7058  7058 D ProfileConfigQcom: Adding HealthService
09-13 13:54:05.934  7058  7058 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 13:54:05.934  7058  7058 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 13:54:05.934  7058  7058 D ProfileConfigQcom: Adding PanService
09-13 13:54:05.934  7058  7058 D ProfileConfigQcom: [BTUI] GattService is supported
,09-13 13:54:05.934  7058  7058 D ProfileConfigQcom: Adding GattService
09-13 13:54:05.935  7058  7058 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-13 13:54:05.935  7058  7058 D ProfileConfigQcom: Adding BluetoothMapService
09-13 13:54:05.935  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 13:54:05.936  7058  7058 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 13:54:05.939  6935  6935 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 13:54:05.940  7058  7058 V LGMDMManagerInternal: Create singleton instance
09-13 13:54:05.961  6953  6953 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 13:54:05.961  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:05.961  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:05.963  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 13:54:05.968  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:05.970  1035  1617 I ActivityManager: Killing 6065:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-13 13:54:05.996  1035  1944 W libprocessgroup: failed to open /acct/uid_10011/pid_6065/cgroup.procs: No such file or directory
,09-13 13:54:05.998  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:06.001  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:06.001  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:06.001  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:06.002  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:06.002  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 13:54:06.009  7013  7013 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 13:54:06.011  1035  1962 I ActivityManager: Killing 6086:com.android.contacts/u0a19 (adj 15): empty #17
09-13 13:54:06.080  1035  1748 W libprocessgroup: failed to open /acct/uid_10019/pid_6086/cgroup.procs: No such file or directory
,09-13 13:54:06.095  6988  6988 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 13:54:06.098  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 13:54:06.099  6988  6988 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 13:54:06.147  6988  6988 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:06.147  6988  6988 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:06.155  6988  6988 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 13:54:06.157  6988  6988 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 13:54:06.157  6988  6988 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 13:54:06.157  6988  6988 V SoundPool: doLoad: loading sample sampleID=1
09-13 13:54:06.157  6988  6988 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 13:54:06.164  6988  7091 V SoundPool: Start decode
09-13 13:54:06.164  6988  7091 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-13 13:54:06.165  6988  6988 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 13:54:06.166  6677  6677 D UEI.SmartControl: QS Service created
09-13 13:54:06.167   319  2171 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 13:54:06.167   319  2171 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 13:54:06.167   319  2171 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 13:54:06.167   319  2171 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 13:54:06.167   319  2171 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 13:54:06.167   319  2171 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 13:54:06.167   319  2171 V MediaPlayerService: player type = 3
09-13 13:54:06.167   319  2171 V AwesomePlayer: AwesomePlayer create()
09-13 13:54:06.168   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:06.168   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:06.168   319  2171 V AwesomePlayer: setAudioSink() 
09-13 13:54:06.169   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:06.169   319  2171 V AudioCache: notify(0xb5474a00, 8, 0, 0)
09-13 13:54:06.169   319  2171 V AudioCache: ignored
,09-13 13:54:06.169   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:06.169   319  2171 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 13:54:06.169   319  2171 V AwesomePlayer: setDataSource_l dataSource
09-13 13:54:06.169   319  2171 V LGParserOSAL: SniffLGParser start
09-13 13:54:06.169   319  2171 V LGParserOSAL: MainType:5, SubType=0
09-13 13:54:06.170   319  2171 V LGParserOSAL: #### check Mime : application/ogg
09-13 13:54:06.170   319  2171 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 13:54:06.170   319  2171 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 13:54:06.176  6988  6988 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 13:54:06.176  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 13:54:06.182  6988  6988 V LGMDMManager: Create singleton instance
09-13 13:54:06.193  6677  6677 I UEI.SmartControl: Service initServices...
09-13 13:54:06.194  6677  6677 D UEI.SmartControl: QS start get config
,09-13 13:54:06.220  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-13 13:54:06.221  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-13 13:54:06.221   319  2171 V LGParserOSAL: supported mime: application/ogg
09-13 13:54:06.221   319  2171 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 13:54:06.221   319  2171 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 13:54:06.221   319  2171 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 13:54:06.221   319  2171 V AwesomePlayer: AudioTrack Setting
09-13 13:54:06.221   319  2171 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 13:54:06.221   319  2171 V AwesomePlayer: setAudioSource() 
09-13 13:54:06.221   319  2171 V MediaPlayerService: prepare
09-13 13:54:06.221   319  2171 V AwesomePlayer: prepareAsync_l() 
09-13 13:54:06.221   319  2171 V MediaPlayerService: wait for prepare
09-13 13:54:06.222   319  7096 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 13:54:06.222   319  7096 V AwesomePlayer: initAudioDecoder() 
09-13 13:54:06.222   319  7096 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,09-13 13:54:06.222   319  7096 V AudioSystem: isOffloadSupported()
09-13 13:54:06.222   319  7096 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 13:54:06.222   319  7096 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 13:54:06.222   319  7096 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 13:54:06.222   319  7096 V AwesomePlayer: getUseOffload() = 0 
09-13 13:54:06.222   319  7096 V OMXCodec: OMXCodec::Create
09-13 13:54:06.222   319  7096 V OMXCodec: findMatchingCodecs()
09-13 13:54:06.222   319  7096 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 13:54:06.222   319  7096 V OMXCodec: matchingCodecs.size()=1
09-13 13:54:06.222   319  7096 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 13:54:06.223   319  7096 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 13:54:06.223   319  7096 V LGCodecAdapter: LG Codec Adapter start
09-13 13:54:06.223   319  7096 V OMXCodec: OMXCodec Createtor
09-13 13:54:06.223   319  7096 V OMXCodec: setComponentRole
,09-13 13:54:06.223   319  7096 V OMXCodec: configureCodec protected=0
09-13 13:54:06.223   319  7096 V LGCodecAdapter: called getLGCodecSpecificData
09-13 13:54:06.223   319  7096 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 13:54:06.223   319  7096 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 13:54:06.223   319  7096 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 13:54:06.223   319  7096 V LGCodecOSAL: Not support LGCodec
09-13 13:54:06.223   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 13:54:06.223   319  7096 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 13:54:06.223   319  7096 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 13:54:06.224   319  7096 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 13:54:06.224   319  7096 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 13:54:06.224   319  7096 V AudioSystem: isOffloadSupported()
09-13 13:54:06.224   319  7096 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 13:54:06.224   319  7096 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 13:54:06.224   319  7096 V OMXCodec: init()
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 13:54:06.224   319  7096 V OMXCodec: allocateBuffers
09-13 13:54:06.224   319  7096 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010380 on input port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010600 on input port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010650 on input port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010740 on input port
09-13 13:54:06.224   319  7096 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010790 on output port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010b50 on output port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010c90 on output port
09-13 13:54:06.224   319  7096 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010d30 on output port
09-13 13:54:06.224   319  7096 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 13:54:06.224   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 13:54:06.224   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 13:54:06.224   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 13:54:06.224   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 13:54:06.224   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 13:54:06.224   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 13:54:06.224   319  7096 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 13:54:06.224   319  7096 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 13:54:06.224   319  7096 V AudioCache: notify(0xb5474a00, 5, 0, 0)
09-13 13:54:06.224   319  7096 V AudioCache: ignored
09-13 13:54:06.22,4   319  7096 V AudioCache: notify(0xb5474a00, 1, 0, 0)
09-13 13:54:06.224   319  7096 V AudioCache: prepared
09-13 13:54:06.224   319  2171 V AudioCache: wait - success
09-13 13:54:06.224   319  2171 V MediaPlayerService: start
09-13 13:54:06.224   319  2171 V AwesomePlayer: play_l() 
09-13 13:54:06.224   319  2171 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 13:54:06.224   319  2171 V AwesomePlayer: createAudioPlayer_l
09-13 13:54:06.224   319  2171 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 13:54:06.225   319  2171 V AwesomePlayer: startAudioPlayer_l() 
09-13 13:54:06.225   319  2171 D AudioPlayer: start of Playback, useOffload 0
09-13 13:54:06.225   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 13:54:06.225   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969634704
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969635664
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969635984
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969636144
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 13:54:06.226   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 13:54:06.227   319  7098 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010c90 on output port
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010b50 on output port
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010790 on output port
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 13:54:06.227   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 13:54:06.228   319  2171 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 13:54:06.228   319  2171 V AudioCache: notify(0xb5474a00, 6, 0, 0)
09-13 13:54:06.228   319  2171 V AudioCache: ignored
09-13 13:54:06.228   319  2171 V MediaPlayerService: wait for playback complete
09-13 13:54:06.228  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6161
09-13 13:54:06.229   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.229   319  7100 V AudioCache: memcpy(0xac300000, 0xb16a5000, 4096)
09-13 13:54:06.233   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.233   319  7100 V AudioCache: memcpy(0xac301000, 0xb16a5000, 4096)
09-13 13:54:06.233   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.233   319  7100 V AudioCache: memcpy(0xac302000, 0xb16a5000, 4096)
09-13 13:54:06.234   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.234   319  7100 V AudioCache: memcpy(0xac303000, 0xb16a5000, 4096)
09-13 13:54:06.235   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.235   319  7100 V AudioCache: memcpy(0xac304000, 0xb16a5000, 4096)
09-13 13:54:06.235   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.235   319  7100 V AudioCache: memcpy(0xac305000, 0xb16a5000, 4096)
09-13 13:54:06.236   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.236   319  7100 V AudioCache: memcpy(0xac306000, 0xb16a5000, 4096)
09-13 13:54:06.236   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.236   319  7100 V AudioCache: memcpy(0xac307000, 0xb16a5000, 4096)
09-13 13:54:06.237   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.237   319  7100 V AudioCache: memcpy(0xac308000, 0xb16a5000, 4096)
09-13 13:54:06.237   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.237   319  7100 V AudioCache: memcpy(0xac309000, 0xb16a5000, 4096)
09-13 13:54:06.237   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.237   319  7100 V AudioCache: memcpy(0xac30a000, 0xb16a5000, 4096)
09-13 13:54:06.238   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.238   319  7100 V AudioCache: memcpy(0xac30b000, 0xb16a5000, 4096)
09-13 13:54:06.238   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.238   319  7100 V AudioCache: memcpy(0xac30c000, 0xb16a5000, 4096)
09-13 13:54:06.238   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.238   319  7100 V AudioCache: memcpy(0xac30d000, 0xb16a5000, 4096)
09-13 13:54:06.239   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.239   319  7100 V AudioCache: memcpy(0xac30e000, 0xb16a5000, 4096)
09-13 13:54:06.239   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.239   319  7100 V AudioCache: memcpy(0xac30f000, 0xb16a5000, 4096)
09-13 13:54:06.240   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.240   319  7100 V AudioCache: memcpy(0xac310000, 0xb16a5000, 4096)
09-13 13:54:06.240   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.240   319  7100 V AudioCache: memcpy(0xac311000, 0xb16a5000, 4096)
09-13 13:54:06.241   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.241   319  7100 V AudioCache: memcpy(0xac312000, 0xb16a5000, 4096)
09-13 13:54:06.241   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.241   319  7100 V AudioCache: memcpy(0xac313000, 0xb16a5000, 4096)
09-13 13:54:06.242   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.242   319  7100 V AudioCache: memcpy(0xac314000, 0xb16a5000, 4096)
09-13 13:54:06.242   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.242   319  7100 V AudioCache: memcpy(0xac315000, 0xb16a5000, 4096)
09-13 13:54:06.243   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.243   319  7100 V AudioCache: memcpy(0xac316000, 0xb16a5000, 4096)
09-13 13:54:06.243   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.243   319  7100 V AudioCache: memcpy(0xac317000, 0xb16a5000, 4096)
09-13 13:54:06.244   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.244   319  7100 V AudioCache: memcpy(0xac318000, 0xb16a5000, 4096)
09-13 13:54:06.244   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.244   319  7100 V AudioCache: memcpy(0xac319000, 0xb16a5000, 4096)
09-13 13:54:06.245   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.245   319  7100 V AudioCache: memcpy(0xac31a000, 0xb16a5000, 4096)
09-13 13:54:06.246   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.246   319  7100 V AudioCache: memcpy(0xac31b000, 0xb16a5000, 4096)
09-13 13:54:06.246   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.246   319  7100 V AudioCache: memcpy(0xac31c000, 0xb16a5000, 4096)
09-13 13:54:06.246   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.246   319  7100 V AudioCache: memcpy(0xac31d000, 0xb16a5000, 4096)
09-13 13:54:06.247   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.247   319  7100 V AudioCache: memcpy(0xac31e000, 0xb16a5000, 4096)
09-13 13:54:06.247   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.247   319  7100 V AudioCache: memcpy(0xac31f000, 0xb16a5000, 4096)
09-13 13:54:06.248   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.248   319  7100 V AudioCache: memcpy(0xac320000, 0xb16a5000, 4096)
09-13 13:54:06.248   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.248   319  7100 V AudioCache: memcpy(0xac321000, 0xb16a5000, 4096)
09-13 13:54:06.249   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.249   319  7100 V AudioCache: memcpy(0xac322000, 0xb16a5000, 4096)
09-13 13:54:06.249   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.249   319  7100 V AudioCache: memcpy(0xac323000, 0xb16a5000, 4096)
09-13 13:54:06.250   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.250   319  7100 V AudioCache: memcpy(0xac324000, 0xb16a5000, 4096)
09-13 13:54:06.251   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.251   319  7100 V AudioCache: memcpy(0xac325000, 0xb16a5000, 4096)
09-13 13:54:06.251   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.251   319  7100 V AudioCache: memcpy(0xac326000, 0xb16a5000, 4096)
09-13 13:54:06.252   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.252   319  7100 V AudioCache: memcpy(0xac327000, 0xb16a5000, 4096)
09-13 13:54:06.252   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.252   319  7100 V AudioCache: memcpy(0xac328000, 0xb16a5000, 4096)
09-13 13:54:06.252   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.252   319  7100 V AudioCache: memcpy(0xac329000, 0xb16a5000, 4096)
09-13 13:54:06.253   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.253   319  7100 V AudioCache: memcpy(0xac32a000, 0xb16a5000, 4096)
09-13 13:54:06.253   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.253   319  7100 V AudioCache: memcpy(0xac32b000, 0xb16a5000, 4096)
09-13 13:54:06.254   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.254   319  7100 V AudioCache: memcpy(0xac32c000, 0xb16a5000, 4096)
09-13 13:54:06.254   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.254   319  7100 V AudioCache: memcpy(0xac32d000, 0xb16a5000, 4096)
09-13 13:54:06.254   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.254   319  7100 V AudioCache: memcpy(0xac32e000, 0xb16a5000, 4096)
09-13 13:54:06.254   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 13:54:06.255   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.255   319  7100 V AudioCache: memcpy(0xac32f000, 0xb16a5000, 4096)
09-13 13:54:06.255   319  7100 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 13:54:06.255   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.255   319  7100 V AudioCache: memcpy(0xac330000, 0xb16a5000, 4096)
09-13 13:54:06.255   319  7100 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 13:54:06.255   319  7100 V AudioCache: write(0xb16a5000, 4096)
09-13 13:54:06.255   319  7100 V AudioCache: memcpy(0xac331000, 0xb16a5000, 4096)
09-13 13:54:06.255   319  7100 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 13:54:06.255   319  7100 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 13:54:06.255   319  7100 V AwesomePlayer: postAudioEOS() 
09-13 13:54:06.255   319  7100 V AudioCache: write(0xb16a5000, 280)
09-13 13:54:06.255   319  7100 V AudioCache: memcpy(0xac332000, 0xb16a5000, 280)
09-13 13:54:06.256   319  7096 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 13:54:06.256   319  7096 V AwesomePlayer: onStreamDone
09-13 13:54:06.256   319  7096 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 13:54:06.256   319  7096 V AudioCache: notify(0xb5474a00, 2, 0, 0)
09-13 13:54:06.256   319  7096 V AudioCache: playback complete
09-13 13:54:06.256   319  7096 V AwesomePlayer: pause_l() 
09-13 13:54:06.256   319  7096 V AudioCache: notify(0xb5474a00, 7, 0, 0)
09-13 13:54:06.256   319  2171 V AudioCache: wait - success
09-13 13:54:06.256   319  7096 V AudioCache: ignored
09-13 13:54:06.256   319  7096 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:06.256   319  2171 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 13:54:06.257   319  7096 D AudioPlayer: Pause Playback at 1068125
09-13 13:54:06.258   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:06.258   319  2171 V AudioCache: notify(0xb5474a00, 8, 0, 0)
09-13 13:54:06.258   319  2171 V AudioCache: ignored
09-13 13:54:06.258   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:06.258   319  2171 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 13:54:06.258   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 13:54:06.258   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 13:54:06.258   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 13:54:06.258   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010740 on port 0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010650 on port 0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010600 on port 0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010380 on port 0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010790 on port 1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010b50 on port 1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010c90 on port 1
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:06.258   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 13:54:06.259   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 13:54:06.259   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 13:54:06.259   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 13:54:06.259   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 13:54:06.259   319  7098 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 13:54:06.259   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 13:54:06.259   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 13:54:06.259   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 13:54:06.260   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 13:54:06.260   319  2171 D AudioPlayer: AudioPlayer releasing audio source
09-13 13:54:06.260   319  2171 D AudioPlayer: AudioPlayer done releasing audio source
09-13 13:54:06.260   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:06.260   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:06.260   319  2171 V AwesomePlayer: ~AwesomePlayer call
09-13 13:54:06.260   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:06.260   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:06.261  6988  7091 V SoundPool: close(31)
09-13 13:54:06.261  6988  7091 V SoundPool: pointer = 0x9fe54000, size = 205080, sampleRate = 48000, numChannels = 2
,09-13 13:54:06.542  6677  6677 I UEI.SmartControl: Supports setup maps: true
09-13 13:54:06.545  6677  6677 D UEI.SmartControl: QS start statue = true Error code = 0
,09-13 13:54:06.545  6677  6677 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 13:54:06.545  6677  6677 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 13:54:06.545  6677  6677 I UEI.SmartControl: ### init IR Blaster...
09-13 13:54:06.548  6677  6677 D serial_port: Configuring serial port
09-13 13:54:06.549  6677  6677 E UEI.SmartControl: UEIBLaster setting for 616
09-13 13:54:06.549  6677  6677 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 13:54:06.549  6677  6677 I UEI.SmartControl: configuring settings for MAXQ616
09-13 13:54:06.549  6677  6677 I UEI.SmartControl: Get version...
,09-13 13:54:06.568  6677  7108 D UEI.SmartControl: serial port data available: 21
,09-13 13:54:06.597  6677  6677 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 13:54:06.597  6677  6677 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 13:54:06.597  6677  6677 I UEI.SmartControl: QS saving settings...
,09-13 13:54:06.599  6677  6677 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 13:54:06.621  6677  7108 D UEI.SmartControl: serial port data available: 4
,09-13 13:54:06.661  6677  6677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 13:54:06.669  6677  7114 I UEI.SmartControl: Device manager: loading config....
09-13 13:54:06.669  6677  7114 D UEI.SmartControl: ----------- loading internal config...
09-13 13:54:06.673  6677  6677 E UEI.SmartControl: Services init done
09-13 13:54:06.673  6677  6677 D UEI.SmartControl: QS Service init finished
09-13 13:54:06.674  6677  6677 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 13:54:06.674  6677  6677 D UEI.SmartControl: QS Service version code: 201091
09-13 13:54:06.675  6677  6677 D UEI.SmartControl: Service requested: Control
09-13 13:54:06.677  6677  7114 E UEI.SmartControl: Loading SETTINGS...
,09-13 13:54:06.682  6677  6677 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 13:54:06.686  6988  6988 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 13:54:06.687  6677  6677 D UEI.SmartControl: Internal service binding...
09-13 13:54:06.688  6677  6693 I UEI.SmartControl: ------ IControl API: 11
09-13 13:54:06.688  6677  6693 D UEI.SmartControl: File observer start...
09-13 13:54:06.688  6677  6693 E UEI.SmartControl: IR Port is disabled: false
09-13 13:54:06.689  6677  6693 D UEI.SmartControl: Starting file observer...
09-13 13:54:06.689  6677  6693 I UEI.SmartControl: Registering callback...
09-13 13:54:06.689  6677  6692 I UEI.SmartControl: ------ IControl API: 19
09-13 13:54:06.690  6677  6692 I UEI.SmartControl: Registering Services Ready callback...
09-13 13:54:06.694  6677  7114 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 13:54:06.712  6677  7113 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 13:54:06.714  6988  7003 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 13:54:06.715  6988  7089 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 13:54:06.715  6988  7089 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 13:54:06.716  6988  6988 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 13:54:06.716  6988  6988 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 13:54:06.717  6677  6693 I UEI.SmartControl: ------ IControl API: 8
09-13 13:54:06.717  6677  7113 D UEI.SmartControl: -----service ready thread exits
09-13 13:54:06.719  6988  6988 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 13:54:06.719  6988  6988 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 13:54:06.719  6988  6988 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 13:54:06.720  6988  6988 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 13:54:06.720  6988  6988 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 13:54:06.721  6988  6988 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 13:54:06.724  6988  6988 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-13 13:54:06.729  6988  6988 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 13:54:06.730  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 13:54:06.731  6988  6988 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 13:54:06.731  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 13:54:06.732  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 13:54:06.733  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 13:54:06.734  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 13:54:06.735  6988  6988 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473767646734]
09-13 13:54:06.738  6988  6988 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-13 13:54:06.743  1035  1618 I ActivityManager: Killing 6578:com.lge.email/u0a23 (adj 15): empty #17
09-13 13:54:06.781  6988  7119 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 13:54:06.788  1035  2036 W libprocessgroup: failed to open /acct/uid_10023/pid_6578/cgroup.procs: No such file or directory
09-13 13:54:06.796  6988  6988 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-13 13:54:06.799  6988  6988 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 13:54:06.799  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 13:54:06.800  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 13:54:06.800  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-13 13:54:06.800  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 13:54:06.801  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 13:54:06.821  6988  6988 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 13:54:07.606  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:07.622  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 13:54:07.638  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:07.643  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:07.645  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:07.646  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:07.649  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 13:54:07.653  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 13:54:07.657  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:07.659  6477  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 13:54:07.667  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:07.670  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:07.671  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:07.680  5814  5814 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 13:54:07.689  5814  5814 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 13:54:07.708  2125  2125 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:07.776  1035  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7128 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-13 13:54:07.779  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:07.787  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:07.787  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 13:54:07.856  7128  7128 I AppUp4:AppBoxCP: onCreate
09-13 13:54:07.857  7128  7128 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-13 13:54:07.867  7128  7128 I AppUp4:DB:  setFingerPrint start
09-13 13:54:07.867  7128  7128 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-13 13:54:07.876  7128  7128 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-13 13:54:07.876  7128  7128 I AppUp4:DB:  SDK version = 21
09-13 13:54:07.876  7128  7128 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 13:54:07.878  7128  7128 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-13 13:54:07.879  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-13 13:54:07.879  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:07.882  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 13:54:07.882  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 13:54:07.889  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 13:54:07.932  7128  7128 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 13:54:07.933  7128  7128 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:07.941  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
,09-13 13:54:07.941  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-13 13:54:07.941  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:07.942  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:07.942  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,09-13 13:54:07.943  7128  7128 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 13:54:07.943  7128  7161 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 13:54:07.944  7128  7161 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 13:54:07.944  7128  7161 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-13 13:54:07.949  1035  1051 I ActivityManager: Killing 6113:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-13 13:54:08.009  1035  1925 W libprocessgroup: failed to open /acct/uid_10027/pid_6113/cgroup.procs: No such file or directory
,09-13 13:54:08.010  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:08.010  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:08.013  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:08.023  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:08.036  4291  7164 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:08.039  4291  7165 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:08.039  4291  7165 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 13:54:08.128  1035  1907 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7169 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 13:54:08.241  7169  7169 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:54:08.242  7169  7169 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:08.243  7169  7169 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 13:54:08.244  7169  7169 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 13:54:08.342  7169  7169 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 13:54:08.360  7169  7169 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 13:54:08.422  7169  7169 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 13:54:08.479  7169  7169 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:08.479  7169  7169 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:08.609  7169  7169 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 13:54:08.650  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 13:54:08.650  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:08.651  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 13:54:08.665  7169  7169 I HubEmail: JNI_OnLoad()
09-13 13:54:08.665  7169  7169 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 13:54:08.665  7169  7169 I HubEmail: registerNatives()
09-13 13:54:08.665  7169  7169 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 13:54:08.665  7169  7169 I HubEmail: registerNativeMethods()
09-13 13:54:08.665  7169  7169 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 13:54:08.665  7169  7169 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-13 13:54:08.702  1035  1925 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7198 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-13 13:54:08.713  7041  7195 W FormManager: Network not available. Please check & try again.
09-13 13:54:08.714  7041  7196 V FormManager: Network unavailable.
09-13 13:54:08.716  7169  7197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:08.729  7041  7196 V FormManager: Network unavailable.
,09-13 13:54:08.737  1035  1998 I ActivityManager: Killing 6612:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-13 13:54:08.805  1035  1944 W libprocessgroup: failed to open /acct/uid_10061/pid_6612/cgroup.procs: No such file or directory
,09-13 13:54:08.907  7198  7198 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:08.907  7198  7198 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 13:54:08.911  7198  7198 D PhoneMonitor: Register our PhoneStateListener
,09-13 13:54:08.937  7198  7198 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 13:54:08.940  7198  7198 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 13:54:08.960  7198  7198 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-13 13:54:08.961  7198  7198 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 13:54:08.962  7198  7198 D TelephonyAutoProfiling: [parse] Load xml
09-13 13:54:08.968  7198  7198 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 13:54:08.968  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 13:54:08.969  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 13:54:08.969  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 13:54:08.969  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 13:54:08.969  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 13:54:08.969  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 13:54:08.969  7198  7198 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 13:54:08.969  7198  7198 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-13 13:54:08.980  7198  7198 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-13 13:54:09.003  1035  1906 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7230 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 13:54:09.005  1035  1906 I ActivityManager: Killing 6173:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-13 13:54:09.045  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{171d09f4 type 2 when 359369 com.google.android.gms} when 359369
,09-13 13:54:09.046  1035  1618 W libprocessgroup: failed to open /acct/uid_10080/pid_6173/cgroup.procs: No such file or directory
,09-13 13:54:09.282  1035  1980 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7249 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 13:54:09.283  1035  1980 I ActivityManager: Killing 6199:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-13 13:54:09.346  1035  1925 W libprocessgroup: failed to open /acct/uid_10097/pid_6199/cgroup.procs: No such file or directory
,09-13 13:54:09.502  1035  1748 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7266 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 13:54:09.502  1035  1748 I ActivityManager: Killing 6642:com.lge.eula/1000 (adj 15): empty #17
,09-13 13:54:09.545  1035  1617 W libprocessgroup: failed to open /acct/uid_1000/pid_6642/cgroup.procs: No such file or directory
,09-13 13:54:09.577  7266  7266 I art     : Almond Protected OAT
,09-13 13:54:09.580  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:09.580  1035  1520 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:09.598  1035  1521 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 13:54:09.599  1035  1521 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 13:54:09.637  7266  7266 D WeatherApplication: removeAccount
,09-13 13:54:09.639  7266  7266 D WeatherApplication: Account.length = 0
,09-13 13:54:09.640  7266  7266 E WeatherApplication: OPERATOR:OPEN
09-13 13:54:09.652  7266  7266 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:9
,09-13 13:54:09.658  7266  7266 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-13 13:54:09.658  7266  7266 D Weather.Utils: 2 : All the weather widget is gone.
09-13 13:54:09.663  7266  7266 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 13:54:09.670  7266  7266 D WeatherAncestor: connectivity changed - connection : true
,09-13 13:54:09.673  7266  7266 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-13 13:54:09.685  7266  7266 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-13 13:54:09.685  7266  7266 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 13:54:09.686  7266  7266 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-13 13:54:09.704  1035  1944 D WifiServiceImplEx: setWifiEnabled: true pid=6786, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 13:54:09.705  1035  1944 D WifiService: setWifiEnabled: true pid=6786, uid=10118
,09-13 13:54:09.705  1035  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 13:54:09.717  7266  7266 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 13:54:09.717  7266  7266 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:9
,09-13 13:54:09.720  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:09.720  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:09.720  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 13:54:09.723  1035  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 13:54:09.723  1035  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 13:54:09.725  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 13:54:09.725  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 13:54:09.725  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-13 13:54:09.725  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 13:54:09.726  1035  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 13:54:09.726  1035  1521 E WifiHW  : unknown target_country: EU , set to default
09-13 13:54:09.726  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 13:54:09.726  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 13:54:09.726  1035  1521 I WifiUtil: gEnableBmps=1
09-13 13:54:09.759  1035  1980 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7285 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 13:54:09.760  1035  1980 I ActivityManager: Killing 6659:com.lge.bnr/1000 (adj 15): empty #17
,09-13 13:54:09.815  1035  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_6659/cgroup.procs: No such file or directory
,09-13 13:54:09.946   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:09.946   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 13:54:09.946   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 13:54:09.947  7285  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 13:54:09.950   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-13 13:54:09.950   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 13:54:09.950   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 13:54:09.951  7285  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 13:54:09.962   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:09.962   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-13 13:54:09.962   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 13:54:09.962  7285  7307 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 13:54:09.967   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:09.967   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 13:54:09.967   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 13:54:09.968  7285  7307 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 13:54:10.230  7285  7285 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 13:54:10.241  7285  7285 I LibraryLoader: Loading: webviewchromium
,09-13 13:54:10.245  7285  7285 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 676-681)
,09-13 13:54:10.246  7285  7285 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 13:54:10.256  7285  7285 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {147393de}
09-13 13:54:10.258  7285  7285 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:54:10.259  7285  7285 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 13:54:10.279  7285  7285 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 13:54:10.283  7285  7285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 13:54:10.301  7285  7285 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 13:54:10.302  7285  7285 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 13:54:10.302  7285  7285 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-13 13:54:10.310   319  1369 V AudioPolicyService: registerClient() client 0xb57f92c0, uid 10093
09-13 13:54:10.312  7285  7332 W AudioManagerAndroid: Requires BLUETOOTH permission
09-13 13:54:10.323  7285  7285 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:10.323  7285  7285 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:10.323  7285  7285 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:10.323  7285  7285 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:10.323  7285  7285 I Adreno-EGL: Remote Branch: 
09-13 13:54:10.323  7285  7285 I Adreno-EGL: Local Patches: 
09-13 13:54:10.323  7285  7285 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:10.415  7285  7285 I NSApplication: Starting up...
,09-13 13:54:10.468   314   893 D SoftapController: Softap fwReload - Ok
09-13 13:54:10.470  1035  1521 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (737ms)
09-13 13:54:10.471   314   893 D CommandListener: Setting iface cfg
09-13 13:54:10.471   314   893 D CommandListener: Trying to bring down wlan0
,09-13 13:54:10.472   314   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:54:10.474  1035  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 13:54:10.477  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:10.477  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:10.477  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 13:54:10.476  7347  7347 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:10.476  7347  7347 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 13:54:10.506  1035  1618 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7348 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 13:54:10.507  1035  1618 I ActivityManager: Killing 6135:com.android.vending/u0a44 (adj 15): empty #17
09-13 13:54:10.519  7347  7347 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 13:54:10.540   340   340 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.510ms total 23.771ms
09-13 13:54:10.556  7347  7347 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 13:54:10.556  7347  7347 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 13:54:10.572   340   340 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 31.645ms
,09-13 13:54:10.594   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 20.548ms
,09-13 13:54:10.646  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 13:54:10.646  1035  1117 D Tethering: InitialState.processMessage what=4
,09-13 13:54:10.647  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 13:54:10.658  1035  1962 W libprocessgroup: failed to open /acct/uid_10044/pid_6135/cgroup.procs: No such file or directory
09-13 13:54:10.669  1035  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 13:54:10.669  1035  1521 D WifiMonitor: connecting to supplicant
,09-13 13:54:10.671  7347  7347 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 13:54:10.672  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:10.673  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 13:54:10.675  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 13:54:10.675  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:10.677  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:10.677  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:10.697  7348  7348 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 13:54:10.783  7347  7347 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 13:54:10.797  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-13 13:54:10.798  7347  7347 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 13:54:10.799  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 13:54:10.799  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 13:54:10.800  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 13:54:10.800  1035  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 13:54:10.801  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-13 13:54:10.801  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 13:54:10.801  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 13:54:10.801  1035  7372 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 13:54:10.802  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 13:54:10.802  1035  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 13:54:10.802  1035  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 13:54:10.802  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 13:54:10.802  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 13:54:10.802  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 13:54:10.803  1035  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 13:54:10.803  1035  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 13:54:10.803  1035  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 13:54:10.804  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:10.804  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:10.804  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:10.804  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 13:54:10.804  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:10.804  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:10.804  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:10.804  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:10.806  1926  1926 D WfdService: Waiting for WifiP2p enabling
09-13 13:54:10.807  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 13:54:10.808  1035  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 13:54:10.809  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:10.809  1035  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
,09-13 13:54:10.811  1035  1521 D WifiNative-wlan0: SET update_config 1: returned true
09-13 13:54:10.811  1035  1521 D WifiConfigStore: Loading config and enabling all networks 
09-13 13:54:10.811  1035  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 13:54:10.811  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:10.811  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:10.811  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:10.811  1035  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 13:54:10.811  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:10.814  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:10.815  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:54:10.815  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:10.815  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:10.816  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:10.816  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:54:10.816  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:10.816  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:54:10.818  1035  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 13:54:10.826  1035  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 13:54:10.827  1035  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 13:54:10.828  1035  1521 D WifiStateMachine: enableVerboseLogging : level 2
09-13 13:54:10.828  1035  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 13:54:10.828  1035  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 13:54:10.828  1035  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 13:54:10.829  1035  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 13:54:10.829  1035  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 13:54:10.829  1035  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 13:54:10.829  1035  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 13:54:10.830  1035  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 13:54:10.830  1035  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 13:54:10.830  1035  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 13:54:10.830  1035  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 13:54:10.831  1035  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 13:54:10.831  1035  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 13:54:10.831  1035  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 13:54:10.832  1926  1926 D WfdsService: Supplicant Connection state is changed : true
09-13 13:54:10.832  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 13:54:10.832  1926  2251 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 13:54:10.832  1926  2251 D WfdsService: Set the WFDS Monitor: true
,09-13 13:54:10.832  1035  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 13:54:10.832  1926  2251 D WfdsMonitor: WfdsMonitorThread create
09-13 13:54:10.832  1926  2251 D WfdsMonitor: WFDS Monitor is created and started
09-13 13:54:10.832  1926  2251 D WfdsService: WiFi: Supplicant connection re-established
09-13 13:54:10.833  1035  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 13:54:10.833  1035  1521 D WifiNative-HAL: Setting external_sim to 1
09-13 13:54:10.833  1035  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 13:54:10.834  1035  1521 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 13:54:10.834  1035  1521 I WifiNative-HAL: startHal
09-13 13:54:10.834  1035  1521 D wifi    : setting scan oui 0xaf6e8660
09-13 13:54:10.834  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 13:54:10.834  1035  1521 I WifiNative-HAL: startHal
09-13 13:54:10.834  1035  1521 D wifi    : setting scan oui 0xaf6e8660
09-13 13:54:10.835  1035  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 13:54:10.835  1926  7373 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 13:54:10.835  1035  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 13:54:10.835  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 13:54:10.835  1926  7373 E CtrlSupplicant: Succeed to open control connection
09-13 13:54:10.835  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 13:54:10.835  1926  7373 E CtrlSupplicant: Succeed to open monitor connection
09-13 13:54:10.835  1926  7373 D WfdsMonitor: Supplicant connection established
09-13 13:54:10.836  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 13:54:10.836  1926  2251 D WfdsService: Connected to the supplicant for wfds
09-13 13:54:10.836  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 13:54:10.836  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 13:54:10.836  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 13:54:10.836  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 13:54:10.836  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 13:54:10.837  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 13:54:10.837  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 13:54:10.838  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 13:54:10.838  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 13:54:10.838  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 13:54:10.838  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 13:54:10.839  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 13:54:10.839  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 13:54:10.839  7347  7347 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-13 13:54:10.839  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true,
,09-13 13:54:10.839  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 13:54:10.839  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 13:54:10.840  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 13:54:10.840  1035  1521 E WifiNative: : [361,261,600 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 13:54:10.840  1035  1521 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 13:54:10.841  1035  1521 D WifiNative-wlan0: RECONNECT: returned true
09-13 13:54:10.841  1035  1521 D WifiNative-wlan0: doString: [STATUS]
,09-13 13:54:10.841  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 13:54:10.841  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 13:54:10.842  1035  1521 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 13:54:10.842  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:10.842  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:10.842  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.843  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
,09-13 13:54:10.843  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 13:54:10.843  1035  1539 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.843  1035  1539 I WifiNative-HAL: startHal
09-13 13:54:10.843  1035  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf6e8660
09-13 13:54:10.843  1035  1539 D wifi    : failed to get capabilities : -3
09-13 13:54:10.843  1035  1539 E WifiScanningService: could not get scan capabilities
09-13 13:54:10.843  1035  1540 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 13:54:10.843  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 13:54:10.844  1035  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 13:54:10.844   314   893 D CommandListener: Setting iface cfg
09-13 13:54:10.844   314   893 D CommandListener: Trying to bring up p2p0
09-13 13:54:10.844  1035  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 13:54:10.844  1035  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 13:54:10.844  1035  1520 D LGWifiP2pService: P2pEnablingState
,09-13 13:54:10.844  1035  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.845  1035  1520 D LGWifiP2pService: P2p socket connection successful
09-13 13:54:10.845  1035  1520 D LGWifiP2pService: P2pEnabledState
09-13 13:54:10.845  1035  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 13:54:10.845  1035  1520 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 13:54:10.845  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 13:54:10.845  1926  1926 D WfdsService: WifiP2pState is changed : true
09-13 13:54:10.846  1035  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
,09-13 13:54:10.846  1926  2251 D WfdsService: Receive the WFDS_ENABLE Method
09-13 13:54:10.846  1926  2251 D WfdsService: Set the WFDS Monitor: true
09-13 13:54:10.846  1926  2251 D WfdsService: Connected to the supplicant for wfds
09-13 13:54:10.846  1926  2251 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 13:54:10.846  7347  7347 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 13:54:10.846  1926  2251 D WfdsService: selectPreferredScanChannel [36]
09-13 13:54:10.846  1926  2251 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-13 13:54:10.846  1035  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 13:54:10.846  1035  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 13:54:10.846  1035  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 13:54:10.847  7347  7347 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 13:54:10.847  1035  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,09-13 13:54:10.847  1035  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 13:54:10.848  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 13:54:10.848  1035  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 13:54:10.848  1035  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 13:54:10.848  7347  7347 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-13 13:54:10.848  1926  1926 D WfdsService: isConnected: false
09-13 13:54:10.848  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 13:54:10.849  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 13:54:10.849  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 13:54:10.849  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 13:54:10.850  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 13:54:10.850  1035  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,09-13 13:54:10.851  7347  7347 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-13 13:54:10.851  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 13:54:10.851  7347  7347 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 13:54:10.851  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.851  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:10.851  1926  7373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.852  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:10.852  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-13 13:54:10.852  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.852  1035  7372 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.852  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.852  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.852  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.852  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.852  1035  7372 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.852  1926  7373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.852  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 13:54:10.852  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.853  1035  1521 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 13:54:10.854  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 13:54:10.854  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 13:54:10.855  1035  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 13:54:10.855  1035  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 13:54:10.855  1035  1520 D WifiNative-p2p0: SET device_name G3: returned true
09-13 13:54:10.855  1035  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 13:54:10.855  1035  1520 D LGWifiP2pService: before postfix = G3
09-13 13:54:10.855  1035  1520 D WifiServerServiceExt: postfix byte check : 2
09-13 13:54:10.855  1035  1520 D LGWifiP2pService: after postfix = G3
09-13 13:54:10.855  1035  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 13:54:10.856  1035  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 13:54:10.856  1035  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,09-13 13:54:10.857  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 13:54:10.857  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 13:54:10.857  1035  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 13:54:10.857  1035  1520 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 13:54:10.858  1035  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 13:54:10.858  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 13:54:10.858  1035  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 13:54:10.858  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress
09-13 13:54:10.858  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 13:54:10.858  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 13:54:10.858  7347  7347 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:10.859  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 13:54:10.859  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-13 13:54:10.859  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:10.859  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:10.860  1035  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 13:54:10.860  1035  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 13:54:10.861  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 13:54:10.861  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 13:54:10.861  1035  1521 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,09-13 13:54:10.861  1926  1926 D WfdsService: Update P2p Interface State: 3
09-13 13:54:10.861  1035  1521 D WifiNative-wlan0: doBoolean: SCAN
09-13 13:54:10.861  1035  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 13:54:10.861  1035  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 13:54:10.861  1035  1521 D WifiNative-wlan0: SCAN: returned false
09-13 13:54:10.861  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=361283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 13:54:10.862  1035  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 13:54:10.862  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 13:54:10.863  1035  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 13:54:10.863  1035  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,09-13 13:54:10.863  1035  1520 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 13:54:10.863  1035  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 13:54:10.865  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:10.865  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:10.865  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 13:54:10.866  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=361287  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 13:54:10.866  1035  1521 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:10.867  1035  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:10.867  1035  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:10.867  1035  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:10.868  1035  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:10.868  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:10.868  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:10.871  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:10.871  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:10.871  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 13:54:10.879  1035  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 13:54:10.879  1035  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-13 13:54:10.879  1035  1520 D LGWifiP2pService: InactiveState
09-13 13:54:10.879  1035  1520 D LGWifiP2pService: InactiveState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.879  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.879  1035  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 13:54:10.879  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 13:54:10.880  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:10.880  1926  7373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 13:54:10.880  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 13:54:10.880  1035  7372 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:10.880  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:10.880  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:10.880  7347  7347 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 13:54:10.880  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.880  1926  7373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.881  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.881  1035  7372 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  1926  7373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.881  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:10.881  1035  7372 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  1035  7372 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  1035  7372 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:10.881  1035  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10,.882  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1926  2251 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:10.882  1035  1035 E WifiServerServiceExt: No p2p device connected
,09-13 13:54:10.968  1035  1980 I art     : Explicit concurrent mark sweep GC freed 48358(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.376ms total 67.802ms
,09-13 13:54:11.038  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 13:54:11.043  6477  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 13:54:11.063  2125  2125 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:11.076  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 13:54:11.076  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:11.077  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 13:54:11.077  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 13:54:11.080  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
09-13 13:54:11.084  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:54:11.084  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:54:11.084  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:11.085  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:11.085  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 13:54:11.089  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:11.089  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:11.091  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:11.093  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:11.105  7169  7169 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 13:54:11.108  4291  7384 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:11.113  4291  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:11.113  4291  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:11.132  7169  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:11.135  7041  7390 W FormManager: Network not available. Please check & try again.
09-13 13:54:11.139  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 13:54:11.139  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:11.139  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 13:54:11.145  7198  7198 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 13:54:11.145  7198  7198 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 13:54:11.147  7041  7391 V FormManager: Network unavailable.
09-13 13:54:11.158  7266  7266 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:11
,09-13 13:54:11.160  7041  7391 V FormManager: Network unavailable.
09-13 13:54:11.162  7266  7266 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 13:54:11.162  7266  7266 D Weather.Utils: 2 : All the weather widget is gone.
09-13 13:54:11.163  7266  7266 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 13:54:11.163  7266  7266 D WeatherAncestor: connectivity changed - connection : true
09-13 13:54:11.163  7266  7266 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30857e73
09-13 13:54:11.164  7266  7266 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 13:54:11.164  7266  7266 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 13:54:11.164  7266  7266 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 13:54:11.164  7266  7266 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 13:54:11.165  7266  7266 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:11
09-13 13:54:11.198   314  7394 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-13 13:54:11.199  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 13:54:11.204  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 13:54:11.204  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 13:54:11.205  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 13:54:11.205  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 13:54:11.206  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:11.208  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:11.209  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 13:54:11.209  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:11.209  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:11.209  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:11.209  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 13:54:11.218  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:11.224  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 13:54:11.226  7041  7396 W FormManager: Network not available. Please check & try again.
09-13 13:54:11.231  7041  7397 V FormManager: Network unavailable.
09-13 13:54:11.231  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 13:54:11.239  7041  7397 V FormManager: Network unavailable.
09-13 13:54:11.255  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:11.259  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 13:54:11.261  7041  7399 W FormManager: Network not available. Please check & try again.
09-13 13:54:11.265  7041  7400 V FormManager: Network unavailable.
09-13 13:54:11.265  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.272  7041  7400 V FormManager: Network unavailable.
,09-13 13:54:11.284  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 13:54:11.285  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:11.286  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:11.289  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:11.294  4291  7401 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:11.299  4291  7402 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 13:54:11.299  4291  7402 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 13:54:11.354  1035  1944 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7403 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 13:54:11.460  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 13:54:11.460  1035  7372 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-13 13:54:11.460  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 13:54:11.461  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-13 13:54:11.461  7347  7347 E wpa_supplicant: USIM:  scard_init function
09-13 13:54:11.461  1035  7372 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 13:54:11.462  7347  7347 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 13:54:11.462  1035  1521 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 13:54:11.463  1035  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 13:54:11.465  1035  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 13:54:11.466  1035  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 13:54:11.466  1035  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 13:54:11.466  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 13:54:11.467  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 13:54:11.478  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=361900  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 13:54:11.483  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=361904  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 13:54:11.486  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.486  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.486  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-13 13:54:11.487  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:11.487  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.487  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 13:54:11.488  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:11.488  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 13:54:11.490  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.490  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.491  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.493  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 13:54:11.493  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.494  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.496  7403  7403 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 13:54:11.497  7403  7403 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 13:54:11.503  7403  7403 V [BNRBootReceiver]: Boot Receiver Return
09-13 13:54:11.503  7403  7403 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-13 13:54:11.506  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
,09-13 13:54:11.516  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.524  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.535  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 13:54:11.535  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.537  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:11.540  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 13:54:11.543  6935  6935 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 13:54:11.549  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:11.557  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.563  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 13:54:11.572  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.573  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:11.576  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:11.583  7347  7347 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 13:54:11.584  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 13:54:11.584  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 13:54:11.585  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 13:54:11.585  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,09-13 13:54:11.586  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:11.586  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=362007  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 13:54:11.586  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:11.587  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=362008  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 13:54:11.588  1035  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=362009
09-13 13:54:11.588  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:11.589  1035  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=362010
09-13 13:54:11.589  1035  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=362011
09-13 13:54:11.590  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=362011
09-13 13:54:11.591  1035  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=362012
09-13 13:54:11.592  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=362013  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 13:54:11.594  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 13:54:11.598  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.598  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 13:54:11.598  7347  7347 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:54:11.599  7347  7347 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 13:54:11.600  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:11.600  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:11.600  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 13:54:11.600  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:54:11.600  1035  7372 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:54:11.600  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 13:54:11.600  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 13:54:11.600  1035  7372 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 13:54:11.601  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:11.601  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:11.601  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.602  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.602  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 13:54:11.602  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.605  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=362026  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 13:54:11.607  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.607  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.607  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 13:54:11.611  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.612  1035  1521 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:11.613  1035  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:11.613  1035  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:11.614  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:11.615  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:11.615  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 13:54:11.615  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:11.616  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=362037  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 13:54:11.616  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=362038  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 13:54:11.617  1035  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=362038
09-13 13:54:11.617  1035  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=362039
09-13 13:54:11.618  1035  1521 D WifiNative-wlan0: doString: [STATUS]
09-13 13:54:11.618  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:11.618  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:11.619  1035  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 13:54:11.620  1035  1521 I WifiServiceExtension: setVHTCapabilityType  : false
,09-13 13:54:11.626  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.628  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.628  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.629  1035  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 13:54:11.629  1035  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 13:54:11.630  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.634  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:11.634  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.634  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 13:54:11.634  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.635  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.635  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 13:54:11.639  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.640  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.640  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 13:54:11.644  1035  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 13:54:11.644  1035  1528 D ConnectivityService: Got NetworkAgent Messenger
09-13 13:54:11.644  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:54:11.644  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 13:54:11.644  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 13:54:11.644  1035  1528 D ConnectivityService: NetworkAgent connected
09-13 13:54:11.644  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 13:54:11.644  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 13:54:11.646  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 13:54:11.646  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 13:54:11.646  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 13:54:11.646  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 13:54:11.646  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:11.647  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:11.647  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 13:54:11.647  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:11.647  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:11.647  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:11.647  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 13:54:11.648  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 13:54:11.650  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.650  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.651  6677  7118 D UEI.SmartControl: Internal timer expired: 2
09-13 13:54:11.651  6677  7118 D UEI.SmartControl: unbind internal service
09-13 13:54:11.651  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.652  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:11.653  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.653  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.654  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.658  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 13:54:11.658  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:54:11.658  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 13:54:11.659  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 13:54:11.659  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 13:54:11.661  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.667  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.667  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 13:54:11.668   314   893 D CommandListener: Setting iface cfg
09-13 13:54:11.674  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.674  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.675  1035  1521 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 13:54:11.675  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:11.675  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=362096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:11.676  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=362097  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 13:54:11.676  1035  7422 D DhcpStateMachine: StoppedState
09-13 13:54:11.676  1035  7422 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.676  1035  7422 D DhcpStateMachine: WaitBeforeStartState
09-13 13:54:11.676  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=362097  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:11.679  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:11.680  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:11.680  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 13:54:11.680  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=362102  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:11.681  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=362102  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:11.681  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=362103  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:11.683  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:316071] from screen [on:0 period:593869155] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:11.684  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:593869155] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:11.684  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:54:11.688  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:11.689  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.690  1035  1528 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 13:54:11.690  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 13:54:11.691  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:11.691  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:11.692  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:11.692  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:11.693  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 13:54:11.693  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 13:54:11.693  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=126,0,0
,09-13 13:54:11.694  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=126,0,0
09-13 13:54:11.694  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 13:54:11.694  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.694  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 13:54:11.695  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 13:54:11.695  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 13:54:11.695  1035  1521 D WifiNative-wlan0: SET ps 0: returned true
09-13 13:54:11.695  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 13:54:11.695  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 13:54:11.696  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 13:54:11.696  1035  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 13:54:11.696  1035  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 13:54:11.696  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3af11676 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.696  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3af11676 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.696  1035  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 13:54:11.696  1035  7422 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.696  1035  7422 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 13:54:11.697   314   893 D CommandListener: Setting iface cfg
09-13 13:54:11.697   314   893 D CommandListener: Trying to bring up wlan0
09-13 13:54:11.698  1035  1521 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 13:54:11.699  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:11.699  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 13:54:11.703  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.703  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:11.703  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 13:54:11.704  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 13:54:11.704  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.704  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:11.705  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
,09-13 13:54:11.705  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 13:54:11.705  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.705  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 13:54:11.706  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 13:54:11.706  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 13:54:11.706  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 13:54:11.707  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 13:54:11.707  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 13:54:11.707  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:11.708  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:11.717  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.723  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:11.724  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 13:54:11.725  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:11.725  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.725  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 13:54:11.726  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:11.726  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:11.727  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:11.727  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:11.728  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 13:54:11.728  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 13:54:11.729  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 13:54:11.729  1035  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 13:54:11.729  1035  1528 D ConnectivityService: ignoring duplicate network state non-change
09-13 13:54:11.732  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.732  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.733  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:11.734  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 13:54:11.736  1035  1528 D ConnectivityService: Adding iface wlan0 to network 101
09-13 13:54:11.737  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.737  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.738  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.739  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.739  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:11.739  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 13:54:11.745  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.745  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.745  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 13:54:11.751  1035  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 13:54:11.752  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:11.756  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 13:54:11.761  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.761  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:11.762  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 13:54:11.762  1035  1528 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 13:54:11.762  1035  1528 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 13:54:11.763  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.764  1035  1528 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 13:54:11.764  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.764  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.764  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 13:54:11.765   314   893 E Netd    : netlink response contains error (File exists)
09-13 13:54:11.765  1035  1528 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 13:54:11.766  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 13:54:11.767  1035  1528 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 13:54:11.767  1035  1528 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 13:54:11.767  1035  1528 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 13:54:11.767  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.767  1564  1564 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 13:54:11.767  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.770  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.770  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:11.770  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 13:54:11.775  1035  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 13:54:11.775  1035  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 13:54:11.775  1035  1528 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 13:54:11.775  1035  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,09-13 13:54:11.775  1035  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:11.775  1035  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:11.775  1035  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 13:54:11.775  1035  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.775  1035  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 13:54:11.775  1035  1528 D ConnectivityService: currentScore = 0, newScore = 20
09-13 13:54:11.775  1035  1528 D ConnectivityService:    accepting network in place of null
09-13 13:54:11.775  1035  1528 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.776  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.776  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 13:54:11.776  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:11.776  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 13:54:11.776  1035  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.777  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:11.778  1035  1528 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 13:54:11.778  1035  1528 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 13:54:11.778  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 13:54:11.779   314  7426 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 13:54:11.780  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.780  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 13:54:11.781  1035  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:11.781  1035  1528 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 13:54:11.781  1035  1528 D ConnectivityService: Switc,hing to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 13:54:11.782  1035  1528 D ConnectivityService: validation of new default Network = false
09-13 13:54:11.782  1035  1528 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 13:54:11.783  1035  1528 D DSQN    : enableDataServiceNotify 
09-13 13:54:11.783  1035  1528 D DSQN    : start dsqn bin
09-13 13:54:11.784  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 13:54:11.784  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 13:54:11.784  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 13:54:11.784  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-13 13:54:11.787  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:11.789  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:11.789  1564  1564 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 13:54:11.789  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.790  1035  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 13:54:11.790  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.790  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:11.790  1035  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:11.791  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 13:54:11.776  7427  7427 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:11.776  7427  7427 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:11.795  6677  7112 D serial_port: close(fd = 24)
09-13 13:54:11.798  6677  7112 I UEI.SmartControl: Serial port is closed.
,09-13 13:54:11.802  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.804  7427  7427 E DSQN    : DSQN ssw
09-13 13:54:11.806  1035  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 13:54:11.809  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.811  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:11.811  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:11.818  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:11.830  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:11.831  1802  7431 I CheckinService: active receiver: enabled
09-13 13:54:11.832   314  7426 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 13:54:11.835  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 13:54:11.842  1802  7431 I CheckinService: Preparing to send checkin request
09-13 13:54:11.842  1802  7431 I EventLogService: Accumulating logs since 1473767347236
09-13 13:54:11.846  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.846  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:11.849  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:11.850  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:11.851  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.851  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.852  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:11.858  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.863  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.866   314  7426 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 13:54:11.867  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.868  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.868  6988  6988 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:11.871  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:11.876  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 13:54:11.877  1802  7431 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-13 13:54:11.879  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:11.882  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:11.888  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.889   314   892 D LGDataListener: argv[0]=dsqncommand
09-13 13:54:11.889   314   892 D LGDataListener: argv[1]=wlan0
09-13 13:54:11.889   314   892 D LGDataListener: argv[2]=1
09-13 13:54:11.889   314   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 13:54:11.890  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 13:54:11.890  1035  1115 D DSQN    : start to monitor internet connection
09-13 13:54:11.895  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.895  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:11.896  6988  6988 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 13:54:11.897  6988  6988 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 13:54:11.897  6988  6988 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-13 13:54:11.899  1035  7422 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 13:54:11.899  1035  7422 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 13:54:11.899  1035  7422 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 13:54:11.886  7435  7435 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:11.886  7435  7435 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:11.902  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:11.905  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 13:54:11.906  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:11.908  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:11.909  7435  7435 I dhcpcd  : version 5.5.6 starting
,09-13 13:54:11.911  7435  7435 E dhcpcd  : get_duid: m
09-13 13:54:11.911  7435  7435 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 13:54:11.911  7435  7435 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 13:54:11.913  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:11.920  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:11.920  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:11.920  6988  6988 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 13:54:11.921  6988  6988 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 13:54:11.921  6988  6988 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 13:54:11.921  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 11:54:11 GMT], X-Android-Received-Millis=[1473767651921], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473767651889]}
09-13 13:54:11.921  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 13:54:11.922  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 13:54:11.922  1035  1528 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 13:54:11.922  1035  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 13:54:11.922  1035  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:11.922  1035  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:11.922  1035  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 13:54:11.922  1035  1528 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 13:54:11.922  1035  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 13:54:11.922  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.922  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:11.923  1035  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 13:54:11.923  1035  1528 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.923  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 13:54:11.923  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 13:54:11.923  1035  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.923  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:11.924  1035  1906 I ActivityManager: Killing 6910:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-13 13:54:11.925  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:11.925  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-13 13:54:11.968  7435  7435 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 13:54:11.968  7435  7435 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 13:54:11.969  7435  7435 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 13:54:11.969  7435  7435 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 13:54:11.970  7435  7435 D dhcpcd  : wlan0: sending REQUEST (xid 0xfeec2b9f), next in 3.81 seconds
09-13 13:54:11.979  1035  1618 W libprocessgroup: failed to open /acct/uid_10037/pid_6910/cgroup.procs: No such file or directory
,09-13 13:54:11.995  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:11.996  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:11.996  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:12.003  7435  7435 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-13 13:54:12.049  7435  7435 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 13:54:12.049  7435  7435 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 13:54:12.049  7435  7435 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 13:54:12.049  7435  7435 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 13:54:12.050  7435  7435 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-13 13:54:12.050  7435  7435 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 13:54:12.051  7435  7435 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 13:54:12.051  7435  7435 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 13:54:12.056  1035  1943 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7442 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-13 13:54:12.139  7442  7442 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 13:54:12.140  7442  7442 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 13:54:12.171  7442  7442 I MultiDex: VM with version 2.1.0 has multidex support
09-13 13:54:12.171  7442  7442 I MultiDex: install
09-13 13:54:12.171  7442  7442 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 13:54:12.183  7442  7442 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 13:54:12.190  2125  2125 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-13 13:54:12.203  2125  2125 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-13 13:54:12.203  2125  2125 D c       : Getting all permits...
09-13 13:54:12.203  2125  2125 D a       : Opening database...
09-13 13:54:12.210  2125  2125 D a       : Opening database auth.proximity.permit_store...
09-13 13:54:12.211  2125  2125 D a       : Closing database...
09-13 13:54:12.300  1035  7422 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 13:54:12.303  1035  7422 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 13:54:12.303  1035  7422 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 13:54:12.303  1035  7422 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 13:54:12.303  1035  7422 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 13:54:12.303  1035  7422 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 13:54:12.303  1035  7422 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 13:54:12.303  1035  7422 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 13:54:12.303  1035  7422 D DhcpStateMachine: RunningState
,09-13 13:54:12.514  7442  7461 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 13:54:12.514  7442  7461 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:12.663  7488  7488 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 13:54:12.755  7488  7488 I dex2oat : dex2oat took 91.880ms (threads: 4)
,09-13 13:54:12.766  7442  7461 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:12.766  7442  7461 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:12.766  7442  7461 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:12.766  7442  7461 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:12.766  7442  7461 I Adreno-EGL: Remote Branch: 
09-13 13:54:12.766  7442  7461 I Adreno-EGL: Local Patches: 
09-13 13:54:12.766  7442  7461 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:12.791  1035  1528 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 13:54:12.837  1035  1521 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:12.837  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 13:54:12.837  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:12.837  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:12.838  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:12.838  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:12.838  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-13 13:54:12.838  1035  1528 D ConnectivityService: identical MTU - not setting
09-13 13:54:12.838  1035  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 13:54:12.838  1035  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 13:54:12.839  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:12.839  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:12.839  1035  1528 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:12.843  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 13:54:12.856  7442  7461 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:12.856  7442  7461 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:12.856  7442  7461 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:12.856  7442  7461 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:12.856  7442  7461 I Adreno-EGL: Remote Branch: 
09-13 13:54:12.856  7442  7461 I Adreno-EGL: Local Patches: 
09-13 13:54:12.856  7442  7461 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:12.985  7442  7461 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:12.985  7442  7461 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:12.985  7442  7461 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:12.985  7442  7461 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:12.985  7442  7461 I Adreno-EGL: Remote Branch: 
09-13 13:54:12.985  7442  7461 I Adreno-EGL: Local Patches: 
09-13 13:54:12.985  7442  7461 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:13.093   314  7496 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 13:54:13.093   314  7496 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,09-13 13:54:13.144   314  7496 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-13 13:54:13.236  1802  7431 I CheckinTask: Sending checkin request (7837 bytes)
,09-13 13:54:13.500  1802  7431 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-13 13:54:13.511  1802  7431 I CheckinService: active receiver: disabled
,09-13 13:54:13.547  2125  2125 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 13:54:13.561  2125  2125 I GCM     : GCM config loaded
,09-13 13:54:13.579   314  7502 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 13:54:13.581   314  7502 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 13:54:13.586  7198  7198 V SetupWizard: Connected to Gservices successfully
09-13 13:54:13.614   314  7502 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-13 13:54:13.934  2125  7505 D GCM     : Connected
,09-13 13:54:13.977  2125  7505 D GCM     : Message class com.google.e.a.a.q
,09-13 13:54:14.695  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=63.0, 0.0, 0.0  rx=71.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:593872167] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:14.698  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=63.0, 0.0, 0.0  rx=71.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593872170] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:14.698  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:54:14.716  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:14.723  1035  1617 D WifiServiceImplEx: setWifiEnabled: false pid=6786, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 13:54:14.723  1035  1617 D WifiService: setWifiEnabled: false pid=6786, uid=10118
09-13 13:54:14.723  1035  1617 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:54:14.753  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:14.753  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:14.753  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 13:54:14.755  1035  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:14.755  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:14.756  1035  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:14.756  1035  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:14.756  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 13:54:14.756  1035  1521 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 13:54:14.757  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:54:14.757  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 13:54:14.758  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 13:54:14.758  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 13:54:14.759  1035  1523 V WifiInternetCheck: Single check msg out of sync, ignoring.
09-13 13:54:14.772  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 13:54:14.777  1035  1520 D LGWifiP2pService: InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.778  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.778  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 13:54:14.778  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 13:54:14.779  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 13:54:14.779  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:14.779  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:14.780  1035  7422 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.781  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.785  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.794  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:54:14.801  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:14.801  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:14.801  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.801  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:14.803  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:14.803  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:14.803  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.803  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:14.804  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active net,work: true
09-13 13:54:14.805  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:14.805  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.805  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:14.811   314   893 D CommandListener: Clearing all IP addresses on wlan0
,09-13 13:54:14.851  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 13:54:14.856  6477  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 13:54:14.906  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:14.908  1035  1944 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,09-13 13:54:14.909  5814  5814 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 13:54:14.914  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:14.914  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:14.914  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-7ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.914  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:14.914  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.914  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 13:54:14.914  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.914  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 13:54:14.915  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 13:54:14.915  1035  1528 D ConnectivityService: ignoring duplicate network state non-change
09-13 13:54:14.915  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-13 13:54:14.915  1035  1520 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.915  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.916  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 13:54:14.915  1035  1520 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@38ca9013
09-13 13:54:14.917  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:14.917  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:14.918  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 13:54:14.918  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:14.918  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.918  1035  1521 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 13:54:14.918  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.918  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:14.918  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 13:54:14.920  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:14.920  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 13:54:14.922  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:14.925  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:14.925  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:14.926  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.926  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.927  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:14.927  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 13:54:14.927  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 13:54:14.927  1035  1539 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.928  1035  1540 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.928  1035  1520 D LGWifiP2pService: P2pDisablingState
09-13 13:54:14.928  1035  1520 D LGWifiP2pService: P2pDisablingState{ when=-11ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.928  1035  1520 D LGWifiP2pService: p2p socket connection lost
09-13 13:54:14.928  1035  1520 D LGWifiP2pService: P2pDisabledState
09-13 13:54:14.928  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 13:54:14.929  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.929  1035  1520 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.929  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 13:54:14.929  7347  7347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 13:54:14.929  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:14.930  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 13:54:14.930  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:14.930  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:14.932  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 13:54:14.933  1926  1926 D WfdsService: WifiP2pState is changed : false
,09-13 13:54:14.944  1926  2251 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 13:54:14.944  1926  2251 D WfdsService: Set the WFDS Monitor: false
09-13 13:54:14.945  1926  2251 D WfdsMonitor: WFDS Monitor is stopped
09-13 13:54:14.945  1926  2251 D WfdsService: STATE : WfdsDisabledState - enter
09-13 13:54:14.945  1926  7373 D CtrlSupplicant: Received on exit socket, terminate
09-13 13:54:14.945  1926  7373 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 13:54:14.945  1926  2252 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 13:54:14.945  1926  7373 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 13:54:14.945  1926  7373 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,09-13 13:54:14.949  2125  2125 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.950  2125  2125 W GCM     : ACTIVE NETWORK NOT CONNECTED
09-13 13:54:14.954  1926  2251 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 13:54:14.956  1035  1944 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-13 13:54:14.961  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 13:54:14.961  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.961  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 13:54:14.961  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 13:54:14.963  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
09-13 13:54:14.966  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:54:14.967  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:54:14.967  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:14.969  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:14.969  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 13:54:14.972  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.972  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:14.974  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:14.976  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:14.977   314   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:54:14.977  1035  1528 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 13:54:14.977  1035  1528 D DSQN    : disableDataServiceNotify
09-13 13:54:14.977  1035  1528 D DSQN    : stop dsqn bin
09-13 13:54:14.978   314  7530 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 13:54:14.978  1035  1521 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 13:54:14.979  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 13:54:14.979  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-23ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.979  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 13:54:14.979  1035  1521 D WifiNative-p2p0: TERMINATE: returned true
09-13 13:54:14.979  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:14.979  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:14.979  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 13:54:14.980  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 13:54:14.980  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 13:54:14.980  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:14.980  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.980  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.980  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:14.981  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:14.983  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 13:54:14.985  4291  7531 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:14.986  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:14.986  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network ,type is Wi-Fi: true
09-13 13:54:14.986  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.986  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:54:14.987  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:14.987  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:14.987  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.987  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:14.988  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:14.988  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:14.988  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:14.988  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:14.989  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 13:54:14.989  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:14.989  1035  1528 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 13:54:14.989  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 13:54:14.989  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:14.989  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:14.990  4291  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.990  1035  1528 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:14.990  4291  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : Connectivi,tyManager is not null
09-13 13:54:14.990  1035  1528 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 13:54:14.990  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.990  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:14.990  1035  7421 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 13:54:14.990  1035  1528 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 13:54:14.990  1035  1528 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 13:54:14.990  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 13:54:14.991  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 13:54:14.991  1035  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.991  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 13:54:14.991  1035  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:14.991  1035  1528 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:14.991  1035  1528 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:14.992  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 13:54:14.992  1035  1528 D NetworkManagementService: Removing idletimer
09-13 13:54:14.992  1035  1521 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:14.992  1035  1528 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:14.992  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:14.992  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:14.993  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 13:54:14.993  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 13:54:14.993  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 13:54:14.993  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCO,NNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 13:54:14.993  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 13:54:14.993  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 13:54:14.993  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 13:54:14.994  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 13:54:14.994  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 13:54:14.994  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 13:54:14.996  7169  7169 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 13:54:14.999  7285  7305 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-13 13:54:15.000  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:15.021  7169  7535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:15.024  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 13:54:15.024  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:15.025  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 13:54:15.025  3423  3423 D PhoneState: setPdpRejectCasuse : false
09-13 13:54:15.026  7041  7537 W FormManager: Network not available. Please check & try again.
09-13 13:54:15.029  7198  7198 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 13:54:15.029  7198  7198 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 13:54:15.035  7347  7347 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 13:54:15.035  7347  7347 I wpa_supplicant: monitor socket send errors count : 1
09-13 13:54:15.035  7347  7347 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-4\x00 that cannot receive messages
,09-13 13:54:15.036  1035  7372 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 13:54:15.036  1035  7372 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 13:54:15.040  7266  7266 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:15
09-13 13:54:15.041  7041  7538 V FormManager: Network unavailable.
09-13 13:54:15.041  7266  7266 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 13:54:15.041  7266  7266 D Weather.Utils: 2 : All the weather widget is gone.
09-13 13:54:15.042  7266  7266 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 13:54:15.042  7266  7266 D WeatherAncestor: connectivity changed - connection : true
09-13 13:54:15.042  7266  7266 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30857e73
09-13 13:54:15.042  7266  7266 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 13:54:15.042  7266  7266 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 13:54:15.042  7266  7266 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 13:54:15.042  7266  7266 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 13:54:15.043  7266  7266 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:15
09-13 13:54:15.044  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:15.046  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:15.047  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 13:54:15.049  7041  7538 V FormManager: Network unavailable.
09-13 13:54:15.050  1035  7422 D DhcpStateMachine: StoppedState
09-13 13:54:15.050  1035  7422 D DhcpStateMachine: StoppedState{ when=-120ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:15.051  1035  1521 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 13:54:15.053  1035  1521 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 13:54:15.060  7347  7347 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:54:15.061  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 13:54:15.061  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:54:15.061  1035  7372 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 13:54:15.061  1035  7372 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 13:54:15.061  1035  1521 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=365483
,09-13 13:54:15.061  7347  7347 W wpa_supplicant: USIM:  scard_deinit function
09-13 13:54:15.061  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:15.061  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:15.062  1035  1521 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=365483
09-13 13:54:15.062  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=365483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 13:54:15.062  1035  1521 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=365484  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 13:54:15.064  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 13:54:15.067  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 13:54:15.068  1035  1521 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:15.068  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:15.070  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:15.073  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 13:54:15.073  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:15.073  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:15.076  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:15.080  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 13:54:15.081  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:15.081  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:15.081  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:15.085  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:15.085  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:15.087  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 13:54:15.090  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:15.092  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 13:54:15.093  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:15.093  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:15.096  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:15.101  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:15.106  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:15.107  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:15.108  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:15.111  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:15.114  6953  6953 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 13:54:15.114  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:15.114  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:15.117  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:15.121  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:15.125  6988  6988 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 13:54:15.125  6988  6988 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:15.126  7347  7347 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 13:54:15.126  1035  7372 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 13:54:15.126  1035  7372 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 13:54:15.126  1035  7372 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 13:54:15.127  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-13 13:54:15.127  6988  6988 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:15.134  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:15.140  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 13:54:15.144  7041  7543 W FormManager: Network not available. Please check & try again.
09-13 13:54:15.146  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 13:54:15.153  7041  7544 V FormManager: Network unavailable.
09-13 13:54:15.159  7041  7544 V FormManager: Network unavailable.
09-13 13:54:15.161  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 13:54:15.161  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 13:54:15.161  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-13 13:54:15.161  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 13:54:15.162  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:15.162  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:15.162  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 13:54:15.162  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:15.162  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:15.162  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:15.163  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 13:54:15.228  1035  1521 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 13:54:15.228  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:15.228  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:15.228  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 13:54:15.228  1926  1926 D WfdsService: Supplicant Connection state is changed : false
09-13 13:54:15.228  1926  2251 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-13 13:54:15.228  1926  2251 D WfdsService: Set the WFDS Monitor: false
09-13 13:54:15.228  1926  2251 D WfdsMonitor: WFDS Monitor is stopped
09-13 13:54:15.233  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 13:54:15.233  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:15.234  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:15.236  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 13:54:15.237  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:15.239  2487  2487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:15.241  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:15.241  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:54:15.241  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 13:54:15.242  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:15.242  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:15.243  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:15.243  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:15.244  1035  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 13:54:15.244  1035  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 13:54:15.246  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:15.255  4291  7545 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:15.258  6953  6953 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 13:54:15.258  6953  6953 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 13:54:15.258  6953  6953 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:15.266  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 13:54:15.266  4291  7546 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 13:54:15.266  4291  7546 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:15.274  7041  7548 W FormManager: Network not available. Please check & try again.
,09-13 13:54:15.276  7041  7549 V FormManager: Network unavailable.
09-13 13:54:15.278  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:15.287  7041  7549 V FormManager: Network unavailable.
,09-13 13:54:15.717  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7512
09-13 13:54:15.717  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7513
09-13 13:54:15.718  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7522
09-13 13:54:15.719  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7541
09-13 13:54:15.719  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7553
,09-13 13:54:16.040  1035  1748 I ActivityManager: Killing 7013:com.lge.settings.easy/1000 (adj 15): empty #17
,09-13 13:54:16.072  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7013/cgroup.procs: No such file or directory
,09-13 13:54:17.722  1035  1521 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:593875194] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 13:54:17.731  1035  1521 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:593875203] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:17.993  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:18.006  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 13:54:18.016  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:18.020  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:18.021  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:18.026  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.030  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:54:18.041  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.043  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:18.046  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:18.048  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:18.051  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 13:54:18.052  6477  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 13:54:18.054  5814  5814 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 13:54:18.071  5814  5814 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 13:54:18.095  2125  2125 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:18.113  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 13:54:18.113  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.114  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 13:54:18.114  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 13:54:18.118  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
09-13 13:54:18.122  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:54:18.122  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:54:18.122  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:18.122  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:18.122  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 13:54:18.127  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.127  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:18.129  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:18.134  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:18.141  7169  7169 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 13:54:18.157  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:18.161  4291  7572 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.161  4291  7572 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:18.161  4291  7571 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:18.162  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:18.162  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:18.174  7169  7573 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:18.182  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 13:54:18.182  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.182  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 13:54:18.187  7198  7198 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 13:54:18.187  7198  7198 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 13:54:18.190  7041  7578 W FormManager: Network not available. Please check & try again.
09-13 13:54:18.197  7041  7579 V FormManager: Network unavailable.
09-13 13:54:18.204  7266  7266 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:18
,09-13 13:54:18.207  7266  7266 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 13:54:18.207  7266  7266 D Weather.Utils: 2 : All the weather widget is gone.
09-13 13:54:18.208  7266  7266 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 13:54:18.208  7266  7266 D WeatherAncestor: connectivity changed - connection : true
09-13 13:54:18.208  7266  7266 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30857e73
09-13 13:54:18.209  7266  7266 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 13:54:18.209  7266  7266 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 13:54:18.209  7266  7266 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 13:54:18.209  7266  7266 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 13:54:18.210  7266  7266 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:18
09-13 13:54:18.211  7041  7579 V FormManager: Network unavailable.
09-13 13:54:18.229  1035  1558 I ActivityManager: Killing 7403:com.lge.bnr/1000 (adj 15): empty #17
,09-13 13:54:18.318  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_7403/cgroup.procs: No such file or directory
,09-13 13:54:18.357  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 13:54:18.364  6477  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 13:54:18.395  2125  2125 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:18.412  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 13:54:18.412  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.412  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-13 13:54:18.412  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 13:54:18.415  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
09-13 13:54:18.420  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:54:18.420  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:54:18.420  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:18.420  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:18.421  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 13:54:18.427  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.427  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 13:54:18.429  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:18.434  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:18.443  4291  7583 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 13:54:18.453  4291  7584 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.453  7169  7169 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 13:54:18.454  4291  7584 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:18.483  7169  7585 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:18.490  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 13:54:18.490  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:18.490  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 13:54:18.497  7198  7198 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 13:54:18.497  7198  7198 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 13:54:18.500  7041  7587 W FormManager: Network not available. Please check & try again.
09-13 13:54:18.515  7266  7266 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:18
,09-13 13:54:18.519  7266  7266 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 13:54:18.519  7266  7266 D Weather.Utils: 2 : All the weather widget is gone.
09-13 13:54:18.520  7266  7266 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 13:54:18.520  7041  7589 V FormManager: Network unavailable.
09-13 13:54:18.520  7266  7266 D WeatherAncestor: connectivity changed - connection : true
09-13 13:54:18.520  7266  7266 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30857e73
09-13 13:54:18.522  7266  7266 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 13:54:18.522  7266  7266 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 13:54:18.522  7266  7266 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 13:54:18.522  7266  7266 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 13:54:18.522  7266  7266 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:18
09-13 13:54:18.529  7041  7589 V FormManager: Network unavailable.
,09-13 13:54:19.760  1035  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:19.761  1035  1558 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-13 13:54:19.785  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:19.785  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:19.785  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 13:54:19.786  1035  1117 D BluetoothManagerService: Message: 1
09-13 13:54:19.786  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-13 13:54:19.812  1035  1117 D BluetoothManagerService: Message: 20
09-13 13:54:19.812  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a8921e5:true
,09-13 13:54:19.817  7058  7058 D BluetoothAdapterState: make
09-13 13:54:19.822  7058  7058 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 13:54:19.822  7058  7058 I bluedroid-qcom: init
09-13 13:54:19.823  7058  7601 I BluetoothAdapterState: Entering OffState
09-13 13:54:19.824  7058  7058 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 13:54:19.824  7058  7058 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 13:54:19.824  7058  7058 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 13:54:19.824  7058  7058 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 13:54:19.824  7058  7058 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 13:54:19.826  7058  7058 I bluedroid-qcom: get_profile_interface socket
09-13 13:54:19.826  7058  7058 I bluedroid-qcom: get_profile_interface map_client
,09-13 13:54:19.830  7058  7605 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 13:54:19.816  7604  7604 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:19.826  7604  7604 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:19.836  7058  7605 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 13:54:19.845  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 13:54:19.846  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 13:54:19.851  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-13 13:54:19.851  1035  1117 D BluetoothManagerService: Message: 40
09-13 13:54:19.851  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 13:54:19.852  7058  7073 I bluedroid-qcom: config_hci_snoop_log
09-13 13:54:19.853  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 13:54:19.853  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 13:54:19.854  7604  7604 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 13:54:19.854  7604  7604 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 13:54:19.854  7604  7604 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-13 13:54:19.857  7604  7604 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 13:54:19.864  7604  7604 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 13:54:19.864  7604  7604 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-13 13:54:19.868  7058  7601 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 13:54:19.869  7058  7605 D BluetoothAdapterProperties: Name is: G3
09-13 13:54:19.869  7058  7601 D BluetoothAdapterProperties: Setting state to 11
09-13 13:54:19.869  7058  7601 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 13:54:19.870  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:19.870  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 13:54:19.870  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 13:54:19.873  7058  7601 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 13:54:19.878  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 13:54:19.880  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:19.883  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:19.887  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 13:54:19.888  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:19.895  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:19.902  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 13:54:19.903  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:19.903  7058  7058 V BluetoothPbapReceiver: ***********state = 11
09-13 13:54:19.908  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:54:19.933  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:19.933  1035  1520 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 13:54:19.974  1035  1748 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7621 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 13:54:19.978  7058  7601 D BluetoothBondStateMachine: make
09-13 13:54:19.984  1035  1521 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 13:54:19.985  1035  1521 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 13:54:19.989  7058  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:19.989  7058  7601 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 13:54:19.989  7058  7637 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 13:54:19.989  7058  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:19.989  7058  7601 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 13:54:19.990  7058  7601 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-13 13:54:19.993  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 13:54:20.004  7058  7058 D HeadsetService: Received start request. Starting profile...
09-13 13:54:20.005  7058  7058 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:54:20.005  7058  7058 D LGBluetoothHfpAdapter: Version 1.6
,09-13 13:54:20.007  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 13:54:20.008  7058  7058 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:54:20.008  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:20.008  7058  7058 D HeadsetStateMachine: make
09-13 13:54:20.019  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 13:54:20.025  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:20.030  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:20.035  7058  7058 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:20.036  7058  7058 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 13:54:20.037  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 13:54:20.040  7058  7058 D HeadsetStateMachine: max_hf_connections = 1
09-13 13:54:20.040  7058  7058 I bluedroid-qcom: get_profile_interface handsfree
09-13 13:54:20.042  7058  7058 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-13 13:54:20.043   319  1368 V AudioPolicyService: registerClient() client 0xb57d7d00, uid 1002
09-13 13:54:20.044   319  1368 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 13:54:20.044   319  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 13:54:20.044   319  1368 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 13:54:20.044  7058  7058 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 13:54:20.045   319  1369 V AudioFlinger: registerClient() client 0xb5581970, pid 7058
09-13 13:54:20.045   319  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:20.045   319  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:20.045  1564  1579 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:20.045  1564  1579 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:20.045  7058  7058 V ToneGenerator: Create Track: 0xb4928a80
09-13 13:54:20.045  7058  7058 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 13:54:20.045  7058  7058 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 13:54:20.045  7058  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:20.046  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:20.046  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:20.046  7058  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 13:54:20.046  1035  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:20.046  3423  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:20.046  1035  1617 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:20.046  3423  3439 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:20.046   319  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:20.046   319  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:20.046   319  2171 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 13:54:20.046   319  2171 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 13:54:20.046  1564  2088 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:20.046  7058  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:20.046   319  2171 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 13:54:20.046  1564  2088 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:20.046   319  2171 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 13:54:20.046  7058  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 13:54:20.047  1035  1944 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:20.047  1035  1944 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:20.047   319  1368 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 13:54:20.047  1837  2430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:20.047  1837  2430 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:20.047  3423  3438 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:20.047  3423  3438 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 ,13:54:20.048   319  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 13:54:20.048   319  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 13:54:20.048   319  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 13:54:20.048   319  1369 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 13:54:20.048  7058  7058 V AudioSystem: getLatency() output 2, latency 50
09-13 13:54:20.048  7058  7058 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 13:54:20.048  7058  7058 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 13:54:20.048   319  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 13:54:20.048   319  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 13:54:20.048   319  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 13:54:20.048   319  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 13:54:20.048   319  2172 V AudioFlinger: createTrack() lSessionId: 22
,09-13 13:54:20.055  7058  7058 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 13:54:20.056   319  2172 V AudioFlinger: acquiring 22 from 7058, for 7058
09-13 13:54:20.056   319  2172 V AudioFlinger:  added new entry for 22
09-13 13:54:20.056  7058  7058 V ToneGenerator: ToneGenerator INIT OK, time: 370491
09-13 13:54:20.056  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.057  7058  7641 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 13:54:20.057  7058  7641 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 13:54:20.057  7058  7641 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 13:54:20.057  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.057  7058  7641 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 13:54:20.060  7058  7058 D A2dpService: Received start request. Starting profile...
09-13 13:54:20.060  7058  7601 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:20.061  7058  7058 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 13:54:20.063   319  2171 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7058
09-13 13:54:20.063  7058  7058 V Avrcp   : make
09-13 13:54:20.063   319  2171 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 13:54:20.063   319  2171 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 13:54:20.063   319  2171 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 13:54:20.063   319  2171 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 13:54:20.063   319  2171 V voice   : voice_set_parameters: exit with code(0)
09-13 13:54:20.063   319  2171 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 13:54:20.063   319  2171 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,09-13 13:54:20.063   319  2171 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 13:54:20.063   319  2171 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 13:54:20.063   319  2171 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 13:54:20.063   319  2171 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 13:54:20.064  7058  7641 V ToneGenerator: ToneGenerator destructor
09-13 13:54:20.064  7058  7641 V ToneGenerator: stopTone
09-13 13:54:20.064  7058  7641 V ToneGenerator: Delete Track: 0xb4928a80
09-13 13:54:20.064  7058  7641 V AudioTrack: ~AudioTrack, releasing session id from 7058 on behalf of 7058
09-13 13:54:20.064   319   319 V AudioFlinger: releasing 22 from 7058 for 7058
09-13 13:54:20.064   319   319 V AudioFlinger:  decremented refcount to 0
09-13 13:54:20.064   319   319 V AudioFlinger: purging stale effects
09-13 13:54:20.064   319  1368 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 13:54:20.064   319  1368 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 13:54:20.064   319  1271 V AudioPolicyService: AudioCommandThread() waking up
09-13 13:54:20.064   319  1368 V AudioFlinger: PlaybackThread::Track destructor
09-13 13:54:20.064   319  1271 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 13:54:20.064   319  1271 V AudioPolicyManager: releaseOutput() 2
09-13 13:54:20.064   319  1271 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 13:54:20.064   319  1368 V AudioFlinger: removeClient_l() pid 7058, calling pid 319
09-13 13:54:20.065  7058  7058 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 13:54:20.065  7058  7058 I bluedroid-qcom: get_profile_interface avrcp
,09-13 13:54:20.074  7058  7058 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 13:54:20.076  7058  7058 E AudioManager: No RCC entry present to update
09-13 13:54:20.076  7058  7058 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 13:54:20.079  7058  7058 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 13:54:20.080  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 13:54:20.080  7058  7058 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-13 13:54:20.083  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 13:54:20.085  7621  7621 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 13:54:20.085  7621  7621 W LG Account v2.2: No ProfileInfo entries
09-13 13:54:20.085  7621  7621 I LG Account v2.2: isEnabled: false
,09-13 13:54:20.085  7621  7621 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 13:54:20.085  7621  7621 I Feature : [Lifetracker]Country: EU
09-13 13:54:20.085  7621  7621 I Feature : [Lifetracker]Operator: OPEN
09-13 13:54:20.085  7621  7621 I Feature : [Lifetracker]Ranking support: false
09-13 13:54:20.085  7621  7621 I Feature : [Lifetracker]Comfort support: false
09-13 13:54:20.086  7621  7621 I Feature : [Lifetracker]Accessory: true
09-13 13:54:20.086  7621  7621 I Feature : [Lifetracker]Health device: true
09-13 13:54:20.086  7621  7621 I Feature : [Lifetracker]Extra Pedometer: false
09-13 13:54:20.086  7621  7621 I Feature : [Lifetracker]Blood glucose device: false
09-13 13:54:20.086  7621  7621 I Feature : [Lifetracker]Device Number: 3
09-13 13:54:20.086  7058  7601 V LGMDMManager: Create singleton instance
09-13 13:54:20.088  7058  7601 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 13:54:20.131  6935  6935 D BluetoothPermissionRequest: onReceive
,09-13 13:54:20.136  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 13:54:20.189  1035  1617 V SIM_STK : Menu title from STK is T-Mobile
09-13 13:54:20.189  1035  1617 V SIM_STK : Menu title from STK is T-Mobile
,09-13 13:54:20.261  1035  1925 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 13:54:20.270  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 13:54:20.274  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 13:54:20.274  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 13:54:20.274  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 13:54:20.274  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 13:54:20.275  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 13:54:20.275  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 13:54:20.275  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 13:54:20.275  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 13:54:20.275  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 13:54:20.275  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 13:54:20.275  7058  7058 I BluetoothA2dpServiceJni: classInitNative
09-13 13:54:20.275  7058  7058 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:54:20.275  7058  7058 D A2dpStateMachine: make
09-13 13:54:20.278  7058  7058 I bluedroid-qcom: get_profile_interface a2dp
09-13 13:54:20.278  7058  7649 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-13 13:54:20.285  7058  7058 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:54:20.285  7058  7058 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 13:54:20.288  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.289  7058  7648 D A2dpStateMachine: Enter Disconnected: -2
09-13 13:54:20.291  7058  7058 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 13:54:20.295  7058  7058 D HidService: Received start request. Starting profile...
09-13 13:54:20.295  7058  7058 I bluedroid-qcom: get_profile_interface hidhost
09-13 13:54:20.295  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.296  7058  7058 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:54:20.298  7058  7058 D HealthService: Received start request. Starting profile...
09-13 13:54:20.300  7058  7058 I bluedroid-qcom: get_profile_interface health
09-13 13:54:20.300  7058  7058 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:54:20.300  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.301  7058  7058 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 13:54:20.302  7058  7058 D PanService: Received start request. Starting profile...
09-13 13:54:20.302  7058  7058 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 13:54:20.302  7058  7058 I bluedroid-qcom: get_profile_interface pan
,09-13 13:54:20.309  7058  7058 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 13:54:20.309  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.309  7058  7058 D HeadsetStateMachine: Proxy object connected
09-13 13:54:20.310  7058  7058 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 13:54:20.310  7058  7058 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 13:54:20.311  7058  7058 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 13:54:20.315  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 13:54:20.315  7058  7058 D BtGatt.GattService: Received start request. Starting profile...
09-13 13:54:20.315  7058  7058 D BtGatt.GattService: start()
09-13 13:54:20.315  7058  7058 I bluedroid-qcom: get_profile_interface gatt
09-13 13:54:20.316  7058  7058 D BtGatt.AdvertiseManager: advertise manager created
,09-13 13:54:20.329  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
,09-13 13:54:20.336  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:20.337  7058  7641 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 13:54:20.337  7058  7641 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 13:54:20.338  7058  7641 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 13:54:20.340  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.340  7058  7058 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,09-13 13:54:20.343  7058  7058 V BluetoothMapService: BluetoothMapBinder()
09-13 13:54:20.345  7058  7058 D BluetoothMapService: Received start request. Starting profile...
09-13 13:54:20.345  7058  7058 D BluetoothMapService: start()
09-13 13:54:20.351  7058  7058 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 13:54:20.352  7058  7058 D BluetoothMapEmailAppObserver: createReceiver()
,09-13 13:54:20.354  7058  7058 D BluetoothMapEmailAppObserver: initObservers()
09-13 13:54:20.355  7058  7058 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-13 13:54:20.371  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:20.381  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 13:54:20.388  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:20.395  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:20.395  7058  7058 V PanService: [BTUI] SIM Extra State :ABSENT
,09-13 13:54:20.405  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:20.412  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 13:54:20.412  7058  7058 V BluetoothMapService: Handler(): got msg=1
,09-13 13:54:20.415  7058  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 13:54:20.415  7058  7601 I bluedroid-qcom: enable
09-13 13:54:20.415  7058  7601 I bt_hci_bdroid: init
09-13 13:54:20.416  7058  7601 I bt_vendor: bt-vendor : init
09-13 13:54:20.416  7058  7601 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 13:54:20.417  7058  7601 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 13:54:20.417  7058  7601 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 13:54:20.417  7058  7601 D bt_userial_mct: userial_init
09-13 13:54:20.418  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:20.418  7058  7601 D bt_hci_bdroid: set_power 1
09-13 13:54:20.418  7058  7601 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 13:54:20.418  7058  7601 I bt_vendor: Starting hciattach daemon
09-13 13:54:20.418  7058  7601 I bt_vendor: try to set true
09-13 13:54:20.420  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:20.420  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:20.420  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:20.420  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:20.420  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-13 13:54:20.421  7058  7662 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 13:54:20.421  7058  7662 I bt-btu  : btu_task pending for preload complete event
09-13 13:54:20.406  7665  7665 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 13:54:20.416  7665  7665 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:20.455  7666  7666 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 13:54:20.479  1035  2036 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7668 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 13:54:20.514  7698  7698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 13:54:20.524  7700  7700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 13:54:20.535  7668  7668 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 13:54:20.537  7702  7702 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 13:54:20.547  7703  7703 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 13:54:20.550  1035  1998 I ActivityManager: Killing 6677:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-13 13:54:20.556  7704  7704 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 13:54:20.562  6988  6988 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 13:54:20.562  6988  6988 W System.err: android.os.DeadObjectException
,09-13 13:54:20.562  6988  6988 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 13:54:20.562  6988  6988 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 13:54:20.562  6988  6988 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:54:20.562  6988  6988 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:54:20.563  6988  6988 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:54:20.563  6988  6988 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:54:20.563  6988  6988 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:54:20.563  6988  6988 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 13:54:20.563  6988  6988 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 13:54:20.563  6988  6988 W System.err: android.os.DeadObjectException
09-13 13:54:20.563  6988  6988 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 13:54:20.563  6988  6988 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 13:54:20.563  6988  6988 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 13:54:20.563  6988  6988 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 13:54:20.563  6988  6988 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 13:54:20.563  6988  6988 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 13:54:20.563  6988  6988 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 13:54:20.563  6988  6988 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 13:54:20.564  6988  6988 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:54:20.564  6988  6988 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:54:20.564  6988  6988 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:54:20.564  6988  6988 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:54:20.564  6988  6988 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:54:20.564  6988  6988 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 13:54:20.564  6988  6988 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 13:54:20.564  6988  6988 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 13:54:20.565  7705  7705 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 13:54:20.583  7707  7707 I libmdmdetect: ESOC framework not supported
09-13 13:54:20.584  7707  7707 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 13:54:20.591  7707  7707 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 13:54:20.591  7707  7707 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 13:54:20.591  7707  7707 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 13:54:20.591  7707  7707 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 13:54:20.591  7707  7707 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 13:54:20.591  7707  7707 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 13:54:20.591  7707  7707 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 13:54:20.629  7707  7710 E QC-QMI  : qmi_client [7707] 14: failed to locate client data
,09-13 13:54:20.630   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-13 13:54:20.631   461   461 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 13:54:20.676  7711  7711 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 13:54:20.682  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6677/cgroup.procs: No such file or directory
,09-13 13:54:20.682  1035  1051 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-13 13:54:20.687  6988  6988 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 13:54:20.687  6988  6988 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 13:54:20.700  7712  7712 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 13:54:20.729  7058  7601 I bt_vendor: bluetooth satus is on
09-13 13:54:20.729  7058  7601 D bt_hci_bdroid: preload
09-13 13:54:20.729  7058  7664 D bt_userial_mct: userial_open(port:0)
09-13 13:54:20.729  7058  7664 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 13:54:20.733  7058  7664 I bt_vendor: Done intiailizing UART
09-13 13:54:20.733  7058  7664 I bt_vendor: Done intiailizing UART
09-13 13:54:20.734  7058  7664 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 13:54:20.734  7058  7664 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 13:54:20.734  7058  7714 D bt_userial_mct: Entering userial_read_thread()
09-13 13:54:20.734  7058  7662 I bt-btu  : btu_task received preload complete event
09-13 13:54:20.735  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 13:54:20.735  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 13:54:20.740  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 13:54:20.745  7058  7662 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 13:54:20.757  1035  1558 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7715 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 13:54:20.758  6988  6988 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 13:54:20.801  7058  7662 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 13:54:20.801  7058  7662 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0160061 
09-13 13:54:20.801  7058  7662 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0160061 
,09-13 13:54:20.822  7058  7605 E bt-btif : Calling BTA_HhEnable
,09-13 13:54:20.822  7058  7605 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 13:54:20.822  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 13:54:20.822  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 13:54:20.822  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 13:54:20.822  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 13:54:20.822  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 13:54:20.822  7058  7605 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-13 13:54:20.824  7058  7605 D BluetoothAdapterProperties: Name is: G3
09-13 13:54:20.825  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 13:54:20.825  7058  7605 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:54:20.825  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 13:54:20.825  7058  7605 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:54:20.826  7058  7605 D bt_hci_bdroid: postload
09-13 13:54:20.826  7058  7664 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:20.826  7058  7662 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 13:54:20.827  7058  7664 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:20.827  7058  7605 D bte_conf: Device ID record 1 : primary
09-13 13:54:20.827  7058  7605 D bte_conf:   vendorId            = 00c4
09-13 13:54:20.827  7058  7605 D bte_conf:   vendorIdSource      = 0001
09-13 13:54:20.827  7058  7605 D bte_conf:   product             = 13a1
09-13 13:54:20.827  7058  7605 D bte_conf:   version             = 1000
09-13 13:54:20.827  7058  7605 D bte_conf:   clientExecutableURL = 
09-13 13:54:20.827  7058  7605 D bte_conf:   serviceDescription  = 
09-13 13:54:20.827  7058  7605 D bte_conf:   documentationURL    = 
09-13 13:54:20.827  7058  7605 D bte_conf: bte_load_did_conf no section named DID2.
09-13 13:54:20.830  7058  7605 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 13:54:20.830  7058  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 13:54:20.830  7058  7601 D BluetoothAdapterProperties: ScanMode =  20
09-13 13:54:20.830  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:20.831  7058  7601 D BluetoothAdapterProperties: State =  11
09-13 13:54:20.831  7058  7601 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 13:54:20.831  7058  7601 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 13:54:20.831  7058  7601 D BluetoothAdapterProperties: Setting state to 12
09-13 13:54:20.831  7058  7601 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 13:54:20.832  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:20.832  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 13:54:20.832  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 13:54:20.832  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:54:20.832  7058  7664 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:20.832  7058  7664 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:20.816  7736  7736 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:20.816  7736  7736 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:20.834  7058  7605 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 13:54:20.835  7058  7601 I BluetoothAdapterState: Entering On State
09-13 13:54:20.836  7058  7664 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 13:54:20.839  7058  7714 E bt_mct  : hci lib postload completed
09-13 13:54:20.847  7058  7601 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 13:54:20.847  7058  7601 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 13:54:20.847  7058  7601 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 13:54:20.848  7058  7601 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 13:54:20.848  7058  7662 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:20.848  7058  7662 W bt-smp  : Plain text(LSB ~ MSB) = 7c 06 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:20.848  7058  7662 W bt-smp  : Encrypted text(LSB ~ MSB) = 93 36 59 de f7 ae 9a b9 be fc 00 31 e4 5b 09 21 
09-13 13:54:20.848  7058  7662 W bt-btm  : Stopping oneshot timer
09-13 13:54:20.850  7058  7605 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:54:20.850  7058  7605 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-13 13:54:20.852  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:20.853  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:20.856  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:20.860  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:20.860  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 13:54:20.863  6935  6951 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:20.865  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:20.866  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 13:54:20.867  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 13:54:20.868  6935  6950 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 13:54:20.870  6935  6951 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 13:54:20.871  6935  6935 D BluetoothMap: Proxy object connected
09-13 13:54:20.871  6935  6935 D MapProfile: Bluetooth service connected
09-13 13:54:20.871  6935  6935 D BluetoothMap: getConnectedDevices()
09-13 13:54:20.872  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:20.873  7058  7740 V BluetoothMapService: getConnectedDevices()
09-13 13:54:20.876  1837  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:54:20.878  6935  6935 D BluetoothInputDevice: Proxy object connected
09-13 13:54:20.878  6935  6935 D HidProfile: Bluetooth service connected
09-13 13:54:20.880  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 13:54:20.881  6935  6950 D BluetoothPan: onBluetoothStateChange on: true
09-13 13:54:20.881  6935  6950 D BluetoothPan: onBluetoothStateChange call bindService
09-13 13:54:20.883  7058  7601 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 13:54:20.885  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:20.887  7058  7662 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:20.887  7058  7662 W bt-smp  : Plain text(LSB ~ MSB) = 2e c3 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:20.887  7058  7662 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 c6 45 af a5 80 2d 7f ae 63 f7 73 41 7e 8f cb 
09-13 13:54:20.887  7058  7662 W bt-btm  : Stopping oneshot timer
09-13 13:54:20.889  6935  6935 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:54:20.889  6935  6935 D PanProfile: Bluetooth service connected
,09-13 13:54:20.892  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 13:54:20.896  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 13:54:20.897  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 13:54:20.897  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 13:54:20.900  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:20.900  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:20.901  7747  7747 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 13:54:20.902  1926  2087 D LGBluetoothAPIService: Message: 1
,09-13 13:54:20.902  1926  2087 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 13:54:20.903  7058  7662 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:20.903  7058  7662 W bt-smp  : Plain text(LSB ~ MSB) = 9e 00 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:20.903  7058  7662 W bt-smp  : Encrypted text(LSB ~ MSB) = b3 da 31 79 16 77 73 43 2f d0 73 f5 56 d0 83 c5 
09-13 13:54:20.903  7058  7662 W bt-btm  : Stopping oneshot timer
09-13 13:54:20.906  1035  1117 D BluetoothManagerService: Message: 40
09-13 13:54:20.906  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-13 13:54:20.908  7715  7715 D UEI.SmartControl: Quickset Services start...
09-13 13:54:20.911  7715  7715 I UEI.SmartControl: Manufacture = LGE
09-13 13:54:20.911  7715  7715 D UEI.SmartControl: Id = LGNevo
09-13 13:54:20.912  7715  7715 D UEI.SmartControl: File observer start...
09-13 13:54:20.914  1926  2087 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 13:54:20.915  6935  6935 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 13:54:20.916  7058  7662 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:20.916  7058  7662 W bt-smp  : Plain text(LSB ~ MSB) = e2 73 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:20.916  7058  7662 W bt-smp  : Encrypted text(LSB ~ MSB) = 8f 80 b5 f0 96 c9 8c b4 d5 e9 f5 cb c7 80 4f 4d 
09-13 13:54:20.916  7058  7662 W bt-btm  : Stopping oneshot timer
09-13 13:54:20.920  7715  7715 E UEI.SmartControl: IR Port is disabled: false
09-13 13:54:20.920  7715  7715 D UEI.SmartControl: Starting file observer...
09-13 13:54:20.920  7715  7715 D UEI.SmartControl: Extracting JNI libs...
09-13 13:54:20.921  7715  7715 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-13 13:54:20.925  6786  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 13:54:20.926  1035  1117 D BluetoothManagerService: Message: 30
09-13 13:54:20.926  7058  7662 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:20.926  7058  7662 W bt-smp  : Plain text(LSB ~ MSB) = 10 52 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:20.926  7058  7662 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 4c 62 b8 ce 34 e8 e0 4e 6c 8d 5b a4 f3 38 7e 
09-13 13:54:20.926  7058  7662 W bt-btm  : Stopping oneshot timer
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:20.930  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:54:20.933  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:20.935  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:20.936  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:21.013  7715  7715 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 13:54:21.013  7715  7715 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 13:54:21.013  7715  7715 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-13 13:54:21.040  7715  7715 I UEI.SmartControl: --- Selecting new region: 6
,09-13 13:54:21.041  7715  7715 I UEI.SmartControl: Model = LG-D855
09-13 13:54:21.042  7715  7715 D UEI.SmartControl: QS Service created
09-13 13:54:21.049  1035  1618 I art     : Explicit concurrent mark sweep GC freed 129578(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.680ms total 133.640ms
09-13 13:54:21.049  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.050  7058  7058 D BluetoothMapService: STATE_ON
09-13 13:54:21.050  6935  6935 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 13:54:21.051  7058  7058 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 13:54:21.051  7058  7058 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 13:54:21.051  7058  7058 V BluetoothMapService: Handler(): got msg=1
,09-13 13:54:21.052  7058  7058 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 13:54:21.053  7058  7751 D BluetoothMapMasInstance: MAS initSocket()
09-13 13:54:21.053  7058  7751 D BluetoothMapMasInstance:   masId = 00
09-13 13:54:21.053  7058  7751 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 13:54:21.053  7058  7751 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 13:54:21.053  7058  7751 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 13:54:21.054  1035  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:21.054  7058  7751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:21.055  7058  7751 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 13:54:21.056  7058  7751 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 13:54:21.056  7058  7751 D BluetoothMapMasInstance: Accepting socket connection...
,09-13 13:54:21.060  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 13:54:21.060  1926  2087 D LGBluetoothAPIService: Message: 100
09-13 13:54:21.060  7058  7605 D BluetoothAdapterProperties: Scan Mode:21
09-13 13:54:21.061  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:21.061  7058  7605 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 13:54:21.061  7058  7058 V BluetoothPbapService: Pbap Service onCreate
09-13 13:54:21.061  1926  2087 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 13:54:21.061  7058  7058 V BluetoothPbapService: Starting PBAP service
09-13 13:54:21.062  7058  7058 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 13:54:21.062  7058  7058 V BluetoothPbapService: Pbap Service onBind
09-13 13:54:21.064  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.064  7058  7058 V BluetoothPbapService: state: 12
09-13 13:54:21.064  1035  1117 D BluetoothManagerService: Message: 30
,09-13 13:54:21.064  7058  7058 V BluetoothPbapService: Handler(): got msg=1
09-13 13:54:21.064  7058  7058 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 13:54:21.064  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:21.065  7058  7752 V BluetoothPbapService: Pbap Service initSocket
09-13 13:54:21.066  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:21.067  7058  7752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:21.067  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:21.068  7058  7752 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 13:54:21.068  7058  7752 V BluetoothPbapService: Succeed to create listening socket 
09-13 13:54:21.068  7058  7752 V BluetoothPbapService: Accepting socket connection...
09-13 13:54:21.069  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:21.071  7715  7715 I UEI.SmartControl: Service initServices...
,09-13 13:54:21.073  7715  7715 D UEI.SmartControl: QS start get config
09-13 13:54:21.076  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 13:54:21.078  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 13:54:21.080  6935  6935 D BluetoothA2dp: Proxy object connected
09-13 13:54:21.080  6935  6935 D A2dpProfile: Bluetooth service connected
09-13 13:54:21.082  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 13:54:21.082  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.082  7058  7058 V BluetoothPbapReceiver: ***********state = 12
09-13 13:54:21.084  6935  6935 D BluetoothPbap: Proxy object connected
,09-13 13:54:21.086  6935  6935 D PbapServerProfile: Bluetooth service connected
09-13 13:54:21.086  6935  6935 D BluetoothHeadset: Proxy object connected
09-13 13:54:21.087  6935  6935 D HeadsetProfile: Bluetooth service connected
09-13 13:54:21.088  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:54:21.088  2125  2125 D c       : Getting all permits...
09-13 13:54:21.088  2125  2125 D a       : Opening database...
09-13 13:54:21.091  2125  2125 D a       : Opening database auth.proximity.permit_store...
09-13 13:54:21.091  2125  2125 D a       : Closing database...
09-13 13:54:21.094  6935  6935 D DockEventReceiver: finishStartingService: stopping service
09-13 13:54:21.114  6935  6935 D BluetoothPermissionRequest: onReceive
09-13 13:54:21.115  7715  7715 D UEI.SmartControl: Loading JNI Libs...
09-13 13:54:21.115  6935  6935 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 13:54:21.116  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 13:54:21.118  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 13:54:21.119  7058  7058 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 13:54:21.124  7058  7058 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-13 13:54:21.145  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 13:54:21.145  7058  7058 V BtOppService: onCreate
,09-13 13:54:21.149  7058  7058 V BluetoothOppNotification: send message
09-13 13:54:21.152  7058  7058 V BtOppService: Starting RfcommListener
09-13 13:54:21.156  7058  7058 D BluetoothOppPreference: Dumping Names:  
09-13 13:54:21.156  7058  7058 D BluetoothOppPreference: {}
09-13 13:54:21.156  7058  7058 D BluetoothOppPreference: Dumping Channels:  
09-13 13:54:21.157  7058  7058 D BluetoothOppPreference: {}
09-13 13:54:21.157  7058  7058 V BtOppService: onStartCommand
09-13 13:54:21.158  7058  7759 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 13:54:21.162  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.162  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-13 13:54:21.165  7058  7058 V BluetoothOppNotification: new notify threadi!
09-13 13:54:21.166  7058  7058 V BluetoothOppNotification: send delay message
09-13 13:54:21.167  7058  7058 V BtOppService: start RfcommListener
09-13 13:54:21.172  7058  7058 V BtOppService: RfcommListener started
09-13 13:54:21.172  7058  7756 V BtOppService: Deleted complete outbound shares, number =  0
09-13 13:54:21.174  7058  7760 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 13:54:21.174  7058  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-13 13:54:21.175  7058  7761 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 13:54:21.176  7058  7756 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 13:54:21.176  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:21.176  7058  7756 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 13:54:21.177  7058  7761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:21.179  7058  7761 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-13 13:54:21.179  7058  7761 V BtOppRfcommListener: Started RFCOMM listener....
09-13 13:54:21.179  7058  7761 I BtOppRfcommListener: Accept thread started.
09-13 13:54:21.179  7058  7761 V BtOppRfcommListener: Accepting connection...
09-13 13:54:21.180  7058  7760 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1955fcec on behalf of 
09-13 13:54:21.180  7058  7756 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@734c8b5 on behalf of 
09-13 13:54:21.181  7058  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@179ecb4a on behalf of 
09-13 13:54:21.183  7058  7759 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 13:54:21.184  7058  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 13:54:21.184  7058  7760 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-13 13:54:21.184  7058  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35c94abb on behalf of 
09-13 13:54:21.185  7058  7759 V BluetoothOppNotification: update too frequent, put in queue
09-13 13:54:21.186  7058  7759 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 13:54:21.189  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:21.189  7058  7058 V BluetoothFtpService: Ftp Service onCreate
09-13 13:54:21.189  7058  7058 I BluetoothFtpService: Ftp Service onCreate
09-13 13:54:21.189  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
09-13 13:54:21.189  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.189  7058  7058 V BluetoothFtpService: Starting Listening on sockets
09-13 13:54:21.190  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:21.190  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:21.190  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:21.190  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.190  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 13:54:21.190  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 13:54:21.190  7058  7760 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 13:54:21.192  7058  7760 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ab63b31 on behalf of 
09-13 13:54:21.192  7058  7058 V BtOppService: ContentObserver received notification
09-13 13:54:21.193  7058  7058 V BtOppService: ContentObserver received notification
09-13 13:54:21.193  7058  7760 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 13:54:21.193  7058  7058 V BluetoothFtpService: Handler(): got msg=1
09-13 13:54:21.193  7058  7762 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 13:54:21.193  7058  7058 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 13:54:21.193  7058  7058 V BluetoothFtpService: Ftp Service initSocket
09-13 13:54:21.193  7058  7762 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 13:54:21.194  7058  7762 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e865216 on behalf of 
09-13 13:54:21.195  7058  7762 V BluetoothOppNotification: update too frequent, put in queue
09-13 13:54:21.195  7058  7762 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 13:54:21.196  7058  7760 V BluetoothOppNotification: outbound notification was removed.
09-13 13:54:21.196  7058  7760 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 13:54:21.197  7058  7760 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f37d797 on behalf of 
09-13 13:54:21.197  7058  7760 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 13:54:21.198  1035  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:21.198  7058  7058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:54:21.199  7058  7058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-13 13:54:21.199  7058  7058 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 13:54:21.200  7058  7763 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 13:54:21.201  7058  7760 V BluetoothOppNotification: inbound notification was removed.
09-13 13:54:21.201  7058  7760 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 13:54:21.202  7058  7760 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2440fd84 on behalf of 
09-13 13:54:21.210  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
,09-13 13:54:21.210  7058  7058 V BluetoothSapService: Sap Service onCreate
,09-13 13:54:21.212  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:21.212  7058  7058 V BluetoothSapService: state: 12
09-13 13:54:21.212  7058  7058 V BluetoothSapService: Starting SAP server process
09-13 13:54:21.213  7058  7058 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 13:54:21.196  7764  7764 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:21.196  7764  7764 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:21.215  7058  7765 V BluetoothSapService: Sap Service initRfcommSocket
09-13 13:54:21.215  1035  1748 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:21.216  7058  7765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:21.216  7058  7765 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-13 13:54:21.216  7058  7765 V BluetoothSapService: Succeed to create listening socket 
09-13 13:54:21.216  7058  7765 V BluetoothSapService: Accepting socket connection...
09-13 13:54:21.223  7764  7764 V BT_SAP  : Event pipe created
09-13 13:54:21.223  7764  7764 V BT_SAP  : create_server_socket qcom.sap.server
09-13 13:54:21.223  7764  7764 V BT_SAP  : created socket fd 6
,09-13 13:54:21.394  7715  7715 I UEI.SmartControl: Supports setup maps: true
,09-13 13:54:21.397  7715  7715 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 13:54:21.397  7715  7715 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 13:54:21.397  7715  7715 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 13:54:21.397  7715  7715 I UEI.SmartControl: ### init IR Blaster...
,09-13 13:54:21.403  7715  7715 D serial_port: Configuring serial port
09-13 13:54:21.407  7715  7715 E UEI.SmartControl: UEIBLaster setting for 616
09-13 13:54:21.407  7715  7715 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 13:54:21.407  7715  7715 I UEI.SmartControl: configuring settings for MAXQ616
09-13 13:54:21.408  7715  7715 I UEI.SmartControl: Get version...
,09-13 13:54:21.425  7715  7766 D UEI.SmartControl: serial port data available: 21
,09-13 13:54:21.454  7715  7715 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 13:54:21.454  7715  7715 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 13:54:21.455  7715  7715 I UEI.SmartControl: QS saving settings...
09-13 13:54:21.457  7715  7715 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 13:54:21.474  7715  7766 D UEI.SmartControl: serial port data available: 4
,09-13 13:54:21.518  7715  7772 I UEI.SmartControl: Device manager: loading config....
09-13 13:54:21.519  7715  7715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 13:54:21.519  7715  7772 D UEI.SmartControl: ----------- loading internal config...
09-13 13:54:21.521  7715  7715 E UEI.SmartControl: Services init done
09-13 13:54:21.521  7715  7715 D UEI.SmartControl: QS Service init finished
09-13 13:54:21.525  7715  7715 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 13:54:21.526  7715  7715 D UEI.SmartControl: QS Service version code: 201091
09-13 13:54:21.527  7715  7715 D UEI.SmartControl: Service requested: Control
09-13 13:54:21.533  7715  7715 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-13 13:54:21.537  6988  6988 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 13:54:21.537  7715  7730 I UEI.SmartControl: ------ IControl API: 11
09-13 13:54:21.539  7715  7730 I UEI.SmartControl: Registering callback...
09-13 13:54:21.539  1035  1051 I ActivityManager: Killing 6988:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 13:54:21.541  7715  7772 E UEI.SmartControl: Loading SETTINGS...
09-13 13:54:21.552  7715  7772 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 13:54:21.570  1035  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_6988/cgroup.procs: No such file or directory
09-13 13:54:21.571  7715  7715 D UEI.SmartControl: Internal service binding...
,09-13 13:54:21.575  7715  7771 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 13:54:21.575  7715  7771 D UEI.SmartControl: -----service ready thread exits
09-13 13:54:21.890  1564  1564 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 13:54:21.995  1035  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7780 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 13:54:22.002  1564  1564 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 13:54:22.003  1564  1564 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 13:54:22.033  1035  1035 D administrator: Handling package changes for user 0
,09-13 13:54:22.036  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 13:54:22.047  1035  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 13:54:22.084  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 13:54:22.090  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 13:54:22.136  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-13 13:54:22.137  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 13:54:22.168  7058  7058 V BluetoothOppNotification: new notify threadi!
09-13 13:54:22.168  7058  7058 V BluetoothOppNotification: send delay message
,09-13 13:54:22.170  7058  7812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 13:54:22.173  7780  7780 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:22.173  7780  7780 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 13:54:22.174  7058  7812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25926df0 on behalf of 
09-13 13:54:22.175  7058  7812 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 13:54:22.175  7058  7812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 13:54:22.176  7058  7812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14781f69 on behalf of 
09-13 13:54:22.176  7058  7812 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 13:54:22.177  7058  7812 V BluetoothOppNotification: outbound notification was removed.
09-13 13:54:22.177  7058  7812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 13:54:22.178  7058  7812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4ed8dee on behalf of 
09-13 13:54:22.178  7058  7812 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 13:54:22.179  7058  7812 V BluetoothOppNotification: inbound notification was removed.
09-13 13:54:22.179  7058  7812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-13 13:54:22.182  7058  7812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e78228f on behalf of 
09-13 13:54:22.200  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 13:54:22.208  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 13:54:22.215  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 13:54:22.217  2487  2487 V GmsNetworkLocationProvi: DISABLE
,09-13 13:54:22.237  2487  2487 E GCoreFlp: Bound FusedProviderService with LocationManager
09-13 13:54:22.238  1035  1097 D LocationProviderProxy: applying state to connected service
,09-13 13:54:22.277  7780  7825 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 13:54:22.277  7780  7825 I Babel   : MmsConfig.loadMmsSettings
09-13 13:54:22.282  7780  7825 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 13:54:22.282  7780  7825 I Babel   : MmsConfig.loadFromDatabase
,09-13 13:54:22.301  7780  7825 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 13:54:22.301  7780  7825 I Babel   : MmsConfig.loadFromResources
09-13 13:54:22.303  7780  7825 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 13:54:22.303  7780  7825 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 13:54:22.306  7780  7780 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:54:22.338  1802  7826 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 13:54:22.338  1802  7826 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-13 13:54:22.341  7780  7823 W AudioCapabilities: Unsupported mime audio/evrc
09-13 13:54:22.343  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
09-13 13:54:22.344  7780  7823 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 13:54:22.347  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:54:22.348  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:54:22.348  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:22.348  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:22.349  7128  7128 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 13:54:22.350  1802  4747 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-13 13:54:22.354  7780  7823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 13:54:22.368  7780  7823 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 13:54:22.369  7780  7823 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 13:54:22.371  7780  7823 W AudioCapabilities: Unsupported mime audio/evrc
09-13 13:54:22.382  7780  7823 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 13:54:22.386  7780  7823 W VideoCapabilities: Unsupported mime video/divx
09-13 13:54:22.389  7780  7823 W VideoCapabilities: Unsupported mime video/divx311
09-13 13:54:22.392  7780  7823 W VideoCapabilities: Unsupported mime video/divx4
09-13 13:54:22.395  1035  1998 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7831 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-13 13:54:22.399  7780  7823 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-13 13:54:22.400  1035  1998 I ActivityManager: Killing 6953:com.lge.sync/1000 (adj 15): empty #17
09-13 13:54:22.414  7780  7823 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 13:54:22.417  7780  7823 W AudioCapabilities: Unsupported mime audio/eac3
09-13 13:54:22.418  7780  7823 W AudioCapabilities: Unsupported mime audio/ac3
,09-13 13:54:22.419  7780  7823 W AudioCapabilities: Unsupported mime audio/g726
09-13 13:54:22.419  7780  7823 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 13:54:22.420  7780  7823 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 13:54:22.421  7780  7823 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 13:54:22.422  7780  7823 W VideoCapabilities: Unsupported mime video/theora
09-13 13:54:22.425  7780  7823 W VideoCapabilities: Unsupported mime video/mjpg
09-13 13:54:22.455  1035  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_6953/cgroup.procs: No such file or directory
,09-13 13:54:22.475  7831  7831 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:54:22.475  7831  7831 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:22.476  7831  7831 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-13 13:54:22.477  7831  7831 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 13:54:22.477  7831  7831 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 13:54:22.526  7831  7831 I SystemConfig: BUILD Country: EU
09-13 13:54:22.526  7831  7831 I SystemConfig: BUILD Operator: OPEN
,09-13 13:54:22.562  1035  1962 I ActivityManager: Killing 7442:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-13 13:54:22.662  1035  1051 W libprocessgroup: failed to open /acct/uid_10005/pid_7442/cgroup.procs: No such file or directory
,09-13 13:54:22.727  1035  1962 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7855 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 13:54:22.736  7831  7850 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 13:54:22.737  7831  7850 I SystemConfig: existFile = false
09-13 13:54:22.737  7831  7850 I SystemConfig: canReadFile = false
09-13 13:54:22.737  7831  7850 I SystemConfig: systemFeature RCS result false
09-13 13:54:22.737  7831  7850 D SystemConfig: refreshRcsSupport() :false
,09-13 13:54:22.792  7855  7855 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:54:22.792  7855  7855 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 13:54:22.792  7855  7855 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 13:54:22.792  7855  7855 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 13:54:22.895  7855  7855 I AppConfig: Total System Memory = 2995761152
,09-13 13:54:22.905  7855  7855 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-13 13:54:22.989  1035  1925 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7874 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 13:54:22.991  1035  1925 I ActivityManager: Killing 7169:com.lge.email/u0a23 (adj 15): empty #17
,09-13 13:54:23.047  1035  1980 W libprocessgroup: failed to open /acct/uid_10023/pid_7169/cgroup.procs: No such file or directory
,09-13 13:54:23.244  7874  7874 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 13:54:23.352  7874  7874 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 13:54:23.352  7874  7874 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:23.407  7874  7874 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 13:54:23.428  7874  7874 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 13:54:23.429  7874  7874 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 13:54:23.457  7874  7874 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 13:54:23.457  7874  7874 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 13:54:23.478  1035  1907 I ActivityManager: Killing 7041:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-13 13:54:23.517  1035  1962 W libprocessgroup: failed to open /acct/uid_10026/pid_7041/cgroup.procs: No such file or directory
,09-13 13:54:23.522  2830  2845 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-13 13:54:23.523  2830  2845 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3fd6dfc1 on behalf of 7874
09-13 13:54:23.540  4555  7914 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-13 13:54:23.547  7874  7874 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-13 13:54:23.604  1035  1906 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7916 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 13:54:23.667  7874  7874 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 13:54:23.694  7916  7916 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 13:54:23.729  7916  7916 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 13:54:23.729  7916  7916 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 13:54:23.729  7916  7916 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 13:54:23.729  7916  7916 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 13:54:23.729  7916  7916 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 13:54:23.729  7916  7916 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-13 13:54:23.751  1035  1980 I ActivityManager: Killing 6477:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-13 13:54:23.781  1035  1962 W libprocessgroup: failed to open /acct/uid_1000/pid_6477/cgroup.procs: No such file or directory
,09-13 13:54:23.954  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-13 13:54:23.983  4555  7914 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 443 ms] updated apps [took 443 ms] 
,09-13 13:54:24.798  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 13:54:24.798  1035  1906 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1959bad9 mBinding = false
,09-13 13:54:24.828  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:24.828  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:24.828  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 13:54:24.831  1035  1117 D BluetoothManagerService: Message: 2
09-13 13:54:24.832  1035  1117 D BluetoothManagerService: Sending off request.
09-13 13:54:24.833  7058  7740 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 13:54:24.834  7058  7601 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 13:54:24.834  7058  7601 D BluetoothAdapterProperties: Setting state to 13
09-13 13:54:24.834  7058  7601 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 13:54:24.835  7058  7601 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 13:54:24.835  7058  7601 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 13:54:24.837  7058  7605 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:54:24.838  7058  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 13:54:24.840  7058  7751 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-13 13:54:24.845  7058  7761 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:24.845  7058  7763 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:24.846  7058  7765 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:24.846  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 13:54:24.847  7058  7662 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 13:54:24.848  7058  7752 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:54:24.849  7058  7601 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 13:54:24.852  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:24.852  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:24.852  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 13:54:24.853  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
,09-13 13:54:24.859  7058  7662 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 13:54:24.862  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:24.863  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:24.872  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:24.872  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:54:24.878  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:24.878  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:24.879  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:24.880  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:24.881  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:24.881  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:24.883  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:54:24.883  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:24.884  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:24.884  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 13:54:24.884  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-13 13:54:24.890  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:24.891  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:24.896  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:24.899  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:24.901  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:24.903  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:24.903  7058  7058 D BluetoothMapService: STATE_TURNING_OFF
09-13 13:54:24.904  7058  7058 V BluetoothMapService: Handler(): got msg=4
09-13 13:54:24.904  7058  7058 D BluetoothMapService: MAP Service closeService in
09-13 13:54:24.904  7058  7058 D BluetoothMapMasInstance: MAP Service shutdown
09-13 13:54:24.904  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 13:54:24.905  7058  7058 V BluetoothMapService: MAP Service closeService out
09-13 13:54:24.905  7058  7058 V BtOppService: Receiver DISABLED_ACTION 
09-13 13:54:24.906  7058  7058 I BtOppRfcommListener: stopping Accept Thread
09-13 13:54:24.906  7058  7058 V BtOppRfcommListener: close mBtServerSocket
09-13 13:54:24.906  7058  7761 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 13:54:24.907  7058  7058 V BtOppRfcommListener: waiting for thread to terminate
09-13 13:54:24.907  7058  7058 V BtOppRfcommListener: done waiting for thread to terminate
09-13 13:54:24.917  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-13 13:54:24.927  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 13:54:24.930  7058  7058 V BtOppService: onDestroy
,09-13 13:54:24.934  7058  7058 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 13:54:24.937  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 13:54:24.937  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:24.937  7058  7058 V BluetoothPbapReceiver: ***********state = 13
09-13 13:54:24.939  7058  7058 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 13:54:24.942  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:54:24.945  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:24.945  7058  7058 V BluetoothPbapService: state: 13
09-13 13:54:24.945  7058  7058 V BluetoothPbapService: Pbap Service closeService in
09-13 13:54:24.952  7058  7058 V BluetoothPbapService: successfully stopped pbap service
09-13 13:54:24.952  7058  7058 V BluetoothPbapService: Pbap Service closeService out
09-13 13:54:24.953  7058  7058 V BluetoothPbapService: Pbap Service onDestroy
09-13 13:54:24.953  7058  7058 V BluetoothPbapService: Pbap Service closeService in
09-13 13:54:24.953  7058  7058 V BluetoothPbapService: Pbap Service closeService out
09-13 13:54:24.953  7058  7058 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 13:54:24.969  6935  6935 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:54:24.972  6935  6935 D BluetoothPbap: Proxy object disconnected
09-13 13:54:24.972  6935  6935 D PbapServerProfile: Bluetooth service disconnected
09-13 13:54:24.992  6935  6935 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 13:54:24.995  1035  1528 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
09-13 13:54:24.999  6935  6935 D BluetoothPermissionRequest: onReceive
09-13 13:54:24.999  6935  6935 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 13:54:25.004  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 13:54:25.009  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 13:54:25.009  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 13:54:25.010  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 13:54:25.015  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:25.015  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 13:54:25.016  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
09-13 13:54:25.016  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:25.016  7058  7058 V BluetoothFtpService: Ftp Service closeService
09-13 13:54:25.016  7058  7058 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 13:54:25.019  7058  7058 V BluetoothFtpService: successfully stopped ftp service
09-13 13:54:25.019  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:25.019  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:25.019  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:25.019  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:25.020  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 13:54:25.020  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 13:54:25.021  7058  7058 V BluetoothFtpService: Ftp Service onDestroy
09-13 13:54:25.021  7058  7058 V BluetoothFtpService: Ftp Service closeService
,09-13 13:54:25.026  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 13:54:25.026  7058  7058 V BluetoothSapService: state: 13
09-13 13:54:25.026  7058  7058 V BluetoothSapService: Stopping SAP server process
09-13 13:54:25.027  7058  7058 V BluetoothSapService: Sap Service closeSapService in
09-13 13:54:25.027  7058  7058 V BluetoothSapService: Close listen Socket : 
09-13 13:54:25.027  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
09-13 13:54:25.027  7058  7058 V BluetoothSapService: Close sapd  Socket : 
09-13 13:54:25.030  7058  7058 V BluetoothSapService: Sap Service closeSapService out
09-13 13:54:25.030  7058  7058 V BluetoothSapService: Sap Service onDestroy
09-13 13:54:25.030  7058  7058 V BluetoothSapService: Sap Service closeSapService in
09-13 13:54:25.031  7058  7058 V BluetoothSapService: Close listen Socket : 
09-13 13:54:25.031  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
09-13 13:54:25.031  7058  7058 V BluetoothSapService: Close sapd  Socket : 
09-13 13:54:25.031  7058  7058 V BluetoothSapService: Sap Service closeSapService out
,09-13 13:54:25.752  7058  7605 D bt_hci_bdroid: cleanup
,09-13 13:54:25.765  7058  7664 I bt_lpm  : LPM is already off!!!
09-13 13:54:25.766  7058  7714 I bt_userial_mct: exiting userial_read_thread
09-13 13:54:25.766  7058  7714 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 13:54:25.766  7058  7662 W bt-btif : ag scb idx 1 not allocated
09-13 13:54:25.766  7058  7662 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 13:54:25.766  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:25.766  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:25.766  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:25.766  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 13:54:25.767  7058  7662 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 13:54:25.767  7058  7662 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 13:54:25.768  7058  7605 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 13:54:25.769  7058  7664 I bt_vendor: hw_epilog_process
09-13 13:54:25.769  7058  7605 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 13:54:25.769  7058  7605 D bt_userial_mct: userial_close
,09-13 13:54:25.770  7058  7605 E bt_userial_mct: pthread_join() FAILED result:3
09-13 13:54:25.770  7058  7605 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 13:54:25.775  7058  7605 D bt_hci_bdroid: set_power 0
09-13 13:54:25.775  7058  7605 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 13:54:25.775  7058  7605 I bt_vendor: bluetooth satus is on
09-13 13:54:25.775  7058  7605 I bt_vendor: bt-vendor : resetting BT status
09-13 13:54:25.775  7058  7605 I bt_vendor: Starting hciattach daemon
09-13 13:54:25.775  7058  7605 I bt_vendor: try to set false
09-13 13:54:25.777  7058  7605 I bt_vendor: Starting hciattach daemon
09-13 13:54:25.777  7058  7605 I bt_vendor: try to set false
,09-13 13:54:25.785  7058  7605 I bt_vendor: cleanup
09-13 13:54:25.786  7058  7662 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 13:54:25.787  7058  7605 I GKI_LINUX: GKI_exit_task 0 done
09-13 13:54:25.787  7058  7605 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 13:54:25.788  7058  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 13:54:25.793  7058  7058 D HeadsetService: Received stop request...Stopping profile...
,09-13 13:54:25.797  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 13:54:25.797  7058  7058 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:54:25.797  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:25.800  7058  7641 D HeadsetStateMachine: Exit Disconnected: -1
09-13 13:54:25.802  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:25.802  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:25.802  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:25.802  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 13:54:25.803  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 13:54:25.804  7058  7058 D A2dpService: Received stop request...Stopping profile...
,09-13 13:54:25.807  7058  7648 D A2dpStateMachine: Exit Disconnected: -1
09-13 13:54:25.811  7058  7601 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 13:54:25.813  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 13:54:25.814  7058  7058 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 13:54:25.814  7058  7058 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:54:25.814  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:25.816  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 13:54:25.816  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 13:54:25.816  7058  7058 D HidService: Received stop request...Stopping profile...
09-13 13:54:25.817  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
,09-13 13:54:25.821  7058  7058 D HealthService: Received stop request...Stopping profile...
09-13 13:54:25.821  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:25.822  7058  7058 D HeadsetStateMachine: Unbinding service...
09-13 13:54:25.824  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 13:54:25.824  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 13:54:25.825  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 13:54:25.825  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 13:54:25.825  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 13:54:25.825  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:54:25.825  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 13:54:25.827  7058  7058 D PanService: Received stop request...Stopping profile...
09-13 13:54:25.827  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:25.828  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:54:25.831  7058  7058 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 13:54:25.831  7058  7058 D BtGatt.GattService: stop()
09-13 13:54:25.831  7058  7058 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 13:54:25.832  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:25.833  7058  7058 D BluetoothMapService: Received stop request...Stopping profile...
09-13 13:54:25.833  7058  7058 D BluetoothMapService: stop()
09-13 13:54:25.834  7058  7058 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 13:54:25.834  7058  7058 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 13:54:25.835  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30857e73
09-13 13:54:25.836  7058  7058 I BluetoothA2dpServiceJni: cleanupNative
09-13 13:54:25.836  7058  7649 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 13:54:25.837  7058  7058 I GKI_LINUX: GKI_exit_task 2 done
09-13 13:54:25.837  7058  7058 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 13:54:25.837  7058  7058 V BluetoothMapService: Handler(): got msg=4
09-13 13:54:25.837  7058  7058 D BluetoothMapService: MAP Service closeService in
09-13 13:54:25.837  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 13:54:25.837  7058  7058 V BluetoothMapService: MAP Service closeService out
09-13 13:54:25.839  7058  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 13:54:25.839  7058  7601 D BluetoothAdapterProperties: Setting state to 10
09-13 13:54:25.839  7058  7601 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 13:54:25.840  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:25.840  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 13:54:25.840  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,09-13 13:54:25.844  7058  7601 I BluetoothAdapterState: Entering OffState
09-13 13:54:25.845  6935  6951 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:25.846  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:54:25.846  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:25.846  1837  2430 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:25.847  6935  6951 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:54:25.847  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 13:54:25.847  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 13:54:25.848  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 13:54:25.849  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:54:25.849  7058  7058 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:54:25.853  6935  6951 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 13:54:25.856  6935  6951 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:54:25.857  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 13:54:25.857  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 13:54:25.859  7058  7058 D BluetoothMapService: cleanup()
09-13 13:54:25.859  7058  7058 D BluetoothMapService: MAP Service closeService in
09-13 13:54:25.859  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 13:54:25.859  7058  7058 V BluetoothMapService: MAP Service closeService out
09-13 13:54:25.860  6935  6951 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:54:25.861  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:25.863  6935  6951 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:54:25.863  1837  2424 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:54:25.864  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 13:54:25.864  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-13 13:54:25.868  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 13:54:25.868  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 13:54:25.868  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1959bad9 mBinding = false
09-13 13:54:25.869  1035  1117 D BluetoothManagerService: Sending unbind request.
09-13 13:54:25.873  7058  7605 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-13 13:54:25.875  7058  7058 I GKI_LINUX: GKI_exit_task 1 done
09-13 13:54:25.875  7058  7058 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 13:54:25.875  7058  7058 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 13:54:25.875  7058  7058 I art     : --- WEIRD: removing null entry 248
09-13 13:54:25.876  7058  7058 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-13 13:54:25.876  7058  7058 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 13:54:25.877  7058  7058 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,09-13 13:54:25.880  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 13:54:25.881  7058  7058 I art     : System.exit called, status: 0
09-13 13:54:25.881  7058  7058 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 13:54:25.901   319  2172 V AudioFlinger: 7058 died, releasing its sessions
09-13 13:54:25.901   319  2172 V AudioFlinger:  pid 1837 @ 0
09-13 13:54:25.901   319  2172 V AudioFlinger:  pid 3423 @ 1
09-13 13:54:25.901   319  2172 V AudioFlinger:  pid 3423 @ 2
,09-13 13:54:25.910  6935  6935 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-13 13:54:25.911  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-13 13:54:25.911  1926  2087 D LGBluetoothAPIService: Message: 101
09-13 13:54:25.915  1926  2087 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-13 13:54:25.915  1926  2087 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-13 13:54:25.915  1926  2087 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,09-13 13:54:25.965  1035  1906 I ActivityManager: Process com.android.bluetooth (pid 7058) has died
,09-13 13:54:25.965  1035  1906 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-13 13:54:25.965  1035  1906 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
09-13 13:54:25.973  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:25.976  1926  2087 D LGBluetoothAPIService: Message: 2
09-13 13:54:25.978  1926  2087 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-13 13:54:25.982  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 13:54:25.985  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:25.986  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 13:54:25.986  6935  6935 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 13:54:25.987  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:25.988  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:25.989  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 13:54:25.993  1564  1564 D BluetoothAdapter: 420809189: getState() :  mService = null. Returning STATE_OFF
09-13 13:54:25.993  1564  1564 D BluetoothAdapter: 420809189: getState() :  mService = null. Returning STATE_OFF
09-13 13:54:26.043  1035  1051 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7995 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 13:54:26.052  6935  6935 D DockEventReceiver: finishStartingService: stopping service
09-13 13:54:26.068   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 571us total 25.354ms
,09-13 13:54:26.091   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 471us total 21.937ms
,09-13 13:54:26.112  7995  7995 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-13 13:54:26.113  7995  7995 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:26.113  7995  7995 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-13 13:54:26.114   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 21.646ms
,09-13 13:54:26.114  7995  7995 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 13:54:26.132  7995  7995 D BluetoothAdapterApp: Loading JNI Library
,09-13 13:54:26.163  7995  7995 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2272aafb Instance Count = 1
,09-13 13:54:26.168  7995  7995 D BluetoothAdapterApp: onCreate
09-13 13:54:26.187  7995  7995 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 13:54:26.187  7995  7995 D ProfileConfigQcom: Adding HeadsetService
,09-13 13:54:26.188  7995  7995 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-13 13:54:26.188  7995  7995 D ProfileConfigQcom: Adding A2dpService
09-13 13:54:26.188  7995  7995 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 13:54:26.188  7995  7995 D ProfileConfigQcom: Adding HidService
09-13 13:54:26.188  7995  7995 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 13:54:26.188  7995  7995 D ProfileConfigQcom: Adding HealthService
09-13 13:54:26.188  7995  7995 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 13:54:26.189  7995  7995 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 13:54:26.189  7995  7995 D ProfileConfigQcom: Adding PanService
09-13 13:54:26.190  7995  7995 D ProfileConfigQcom: [BTUI] GattService is supported
09-13 13:54:26.190  7995  7995 D ProfileConfigQcom: Adding GattService
09-13 13:54:26.190  7995  7995 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-13 13:54:26.190  7995  7995 D ProfileConfigQcom: Adding BluetoothMapService
09-13 13:54:26.190  7995  7995 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 13:54:26.191  7995  7995 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 13:54:26.191  7995  7995 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:26.192  7995  7995 V BluetoothPbapReceiver: ***********state = 10
09-13 13:54:26.193  7995  7995 V LGMDMManagerInternal: Create singleton instance
09-13 13:54:26.249  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:54:26.249  6935  6935 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 13:54:26.250  7995  7995 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-13 13:54:26.250  7995  7995 D LGBluetoothAPIServer: [BTUI] onBind()
,09-13 13:54:26.257  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 13:54:26.257  1926  2087 D LGBluetoothAPIService: Message: 100
09-13 13:54:26.258  1926  2087 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 13:54:26.267  6935  6935 D BluetoothPermissionRequest: onReceive
,09-13 13:54:26.271  6935  6935 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 13:54:26.271  6935  6935 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 13:54:26.274  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 13:54:26.277  7995  7995 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 13:54:26.281  7995  7995 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 13:54:26.285  7995  7995 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-13 13:54:26.286  7995  7995 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:26.286  7995  7995 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:26.287  7995  7995 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:26.287  7995  7995 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 13:54:26.300  7668  7668 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 13:54:26.518  7715  7773 D UEI.SmartControl: Internal timer expired: 1
09-13 13:54:26.519  7715  7773 D UEI.SmartControl: unbind internal service
,09-13 13:54:26.532  7715  7715 D UEI.SmartControl: Service.onUnbind: IControl
09-13 13:54:26.535  7715  7715 D UEI.SmartControl: Service.onDestroy
09-13 13:54:26.536  7715  7715 D UEI.SmartControl: Lock is in USE false
09-13 13:54:26.536  7715  7715 D UEI.SmartControl: unbind internal service
09-13 13:54:26.536  7715  7715 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@337421a9
09-13 13:54:26.537  7715  7715 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-13 13:54:26.537  7715  7715 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-13 13:54:26.537  7715  7715 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-13 13:54:26.537  7715  7715 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-13 13:54:26.537  7715  7715 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-13 13:54:26.537  7715  7715 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-13 13:54:26.537  7715  7715 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-13 13:54:26.537  7715  7715 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-13 13:54:26.537  7715  7715 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:54:26.538  7715  7715 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:54:26.538  7715  7715 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:54:26.538  7715  7715 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:54:26.538  7715  7715 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:54:26.538  7715  7715 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:54:26.538  7715  7715 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 13:54:26.538  7715  7715 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@337421a9
,09-13 13:54:26.548  7715  7715 D serial_port: close(fd = 25)
09-13 13:54:26.553  7715  7715 I UEI.SmartControl: Serial port is closed.
09-13 13:54:26.553  7715  7715 I UEI.SmartControl: Serial port is closed.
09-13 13:54:26.554  7715  7715 D UEI.SmartControl: Blaster closed
09-13 13:54:26.554  7715  7715 D UEI.SmartControl: Shut down QS...
,09-13 13:54:26.556  7715  7715 D UEI.SmartControl: Stopping QS lib
09-13 13:54:26.557  7715  7715 D UEI.SmartControl: QS lib stop result = true
09-13 13:54:26.557  7715  7715 D UEI.SmartControl: Stopped QS lib
09-13 13:54:26.557  7715  7715 D UEI.SmartControl: Stopped file observer...
09-13 13:54:26.557  7715  7715 D UEI.SmartControl: QS shutdown complete
09-13 13:54:29.903  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:29.903  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:54:29.917  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:54:29.917  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@376c7604 removed from the list
09-13 13:54:29.917  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:29.917  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:54:29.917  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:54:29.920  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:54:29.920  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4dee622 added. We now have 4 listener(s)
09-13 13:54:29.921  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:54:29.923  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:54:29.923  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4dee622 removed from the list
09-13 13:54:29.923  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:29.923  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:54:29.923  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:54:29.925  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:54:29.925  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d5288b3 added. We now have 4 listener(s)
09-13 13:54:29.925  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:54:29.925  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:29.925  1035  1943 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-13 13:54:29.926  1035  1117 D BluetoothManagerService: Message: 2
09-13 13:54:34.933  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:34.946  1035  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:34.946  1035  1558 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-13 13:54:34.964  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-13 13:54:34.967  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:34.967  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 13:54:34.968  1035  1117 D BluetoothManagerService: Message: 1
09-13 13:54:34.968  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-13 13:54:34.994  1035  1117 D BluetoothManagerService: Message: 20
09-13 13:54:34.995  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26ef6438:true
,09-13 13:54:34.998  7995  7995 D BluetoothAdapterState: make
09-13 13:54:35.003  7995  7995 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 13:54:35.003  7995  7995 I bluedroid-qcom: init
09-13 13:54:35.004  7995  8029 I BluetoothAdapterState: Entering OffState
09-13 13:54:35.005  7995  7995 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 13:54:35.005  7995  7995 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 13:54:35.006  7995  7995 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 13:54:35.006  7995  7995 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 13:54:35.006  7995  7995 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 13:54:35.008  7995  7995 I bluedroid-qcom: get_profile_interface socket
09-13 13:54:35.008  7995  7995 I bluedroid-qcom: get_profile_interface map_client
,09-13 13:54:35.012  7995  8033 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 13:54:35.007  8032  8032 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:35.007  8032  8032 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:35.017  7995  8033 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 13:54:35.026  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 13:54:35.026  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 13:54:35.031  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-13 13:54:35.032  1035  1117 D BluetoothManagerService: Message: 40
09-13 13:54:35.032  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 13:54:35.032  7995  8012 I bluedroid-qcom: config_hci_snoop_log
09-13 13:54:35.035  8032  8032 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 13:54:35.035  8032  8032 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 13:54:35.035  8032  8032 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-13 13:54:35.036  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 13:54:35.036  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 13:54:35.037  7995  8033 D BluetoothAdapterProperties: Name is: G3
09-13 13:54:35.038  8032  8032 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 13:54:35.043  8032  8032 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 13:54:35.043  8032  8032 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-13 13:54:35.049  7995  8029 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 13:54:35.050  7995  8029 D BluetoothAdapterProperties: Setting state to 11
09-13 13:54:35.050  7995  8029 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 13:54:35.052  7995  8029 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 13:54:35.054  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:35.054  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 13:54:35.055  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 13:54:35.058  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 13:54:35.061  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:35.063  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:35.068  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:35.071  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-13 13:54:35.078  7995  7995 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-13 13:54:35.079  7995  7995 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:35.079  7995  7995 V BluetoothPbapReceiver: ***********state = 11
09-13 13:54:35.090  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:54:35.099  7995  8029 D BluetoothBondStateMachine: make
09-13 13:54:35.102  7995  8029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.103  7995  8029 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 13:54:35.103  7995  8047 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 13:54:35.103  7995  8029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.104  7995  8029 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 13:54:35.105  7995  8029 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-13 13:54:35.110  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:35.116  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 13:54:35.119  7995  7995 D HeadsetService: Received start request. Starting profile...
09-13 13:54:35.120  7995  7995 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:54:35.120  7995  7995 D LGBluetoothHfpAdapter: Version 1.6
09-13 13:54:35.123  7995  7995 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 13:54:35.124  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:35.124  7995  7995 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:54:35.125  7995  7995 D HeadsetStateMachine: make
09-13 13:54:35.125  6935  6935 D BluetoothPermissionRequest: onReceive
09-13 13:54:35.131  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 13:54:35.132  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 13:54:35.139  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:35.145  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
09-13 13:54:35.149  7995  8029 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 13:54:35.157  7995  7995 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:35.157  7995  7995 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 13:54:35.160  7995  7995 D HeadsetStateMachine: max_hf_connections = 1
09-13 13:54:35.160  7995  7995 I bluedroid-qcom: get_profile_interface handsfree
,09-13 13:54:35.162  7995  7995 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-13 13:54:35.162   319   319 V AudioPolicyService: registerClient() client 0xb558a260, uid 1002
09-13 13:54:35.163   319  2172 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 13:54:35.163   319  2172 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 13:54:35.163   319  2172 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 13:54:35.163  7995  7995 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 13:54:35.163   319  1369 V AudioFlinger: registerClient() client 0xb55816e8, pid 7995
09-13 13:54:35.164   319  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:35.164   319  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:35.164  7995  7995 V ToneGenerator: Create Track: 0xb4928080
09-13 13:54:35.164  7995  7995 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 13:54:35.164  7995  7995 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 13:54:35.164   319  2171 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 13:54:35.164  1035  1980 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:35.164   319  2171 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 13:54:35.164  1035  1980 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:35.164   319  2171 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 13:54:35.164   319  2171 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 13:54:35.165  7995  7995 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 13:54:35.165  1564  2088 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:35.165  1564  2088 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:35.165  3423  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:35.165   319  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:35.165  3423  3439 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:35.165   319  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:35.165  7995  8012 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:35.165   319  1369 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 13:54:35.165  1035  2036 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:35.165  1035  2036 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:35.165  7995  8012 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 13:54:35.165  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 13:54:35.166  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 13:54:35.166  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:35.166  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:35.166   319  2172 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 13:54:35.166   319  2172 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 13:54:35.166   319  2172 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 13:54:35.166   319  2172 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 13:54:35.166  7995  7995 V AudioSystem: getLatency() output 2, latency 50
09-13 13:54:35.166  7995  7995 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 13:54:35.166  7995  7995 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 13:54:35.166   319  2171 V AudioFlinger: [MABL_AudioFlinger] PlaybackT,hread::setMABLEnable(), enable = 0 
09-13 13:54:35.166   319  2171 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 13:54:35.166   319  2171 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 13:54:35.166   319  2171 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 13:54:35.166   319  2171 V AudioFlinger: createTrack() lSessionId: 23
09-13 13:54:35.166  1564  2523 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:35.166  1564  2523 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:35.166  3423  3438 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:35.166  3423  3438 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 13:54:35.167  7995  7995 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 13:54:35.167  7995  8012 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 13:54:35.167  7995  8012 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 13:54:35.167   319  2171 V AudioFlinger: acquiring 23 from 7995, for 7995
09-13 13:54:35.167   319  2171 V AudioFlinger:  added new entry for 23
09-13 13:54:35.167  7995  7995 V ToneGenerator: ToneGenerator INIT OK, time: 385603
09-13 13:54:35.167  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.168  7995  8052 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 13:54:35.168  7995  8052 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 13:54:35.168  7995  8052 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 13:54:35.168  7995  8052 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 13:54:35.168   319   319 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7995
09-13 13:54:35.169   319   319 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 13:54:35.169   319   319 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 13:54:35.169   319   319 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 13:54:35.169   319   319 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 13:54:35.169   319   319 V voice   : voice_set_parameters: exit with code(0)
09-13 13:54:35.169   319   319 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 13:54:35.169   319   319 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 13:54:35.169   319   319 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 13:54:35.169   319   319 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 13:54:35.169   319   319 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 13:54:35.169   319   319 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 13:54:35.169  7995  8052 V ToneGenerator: ToneGenerator destructor
09-13 13:54:35.169  7995  8052 V ToneGenerator: stopTone
09-13 13:54:35.169  7995  8052 V ToneGenerator: Delete Track: 0xb4928080
09-13 13:54:35.170  7995  8029 V LGMDMManager: Create singleton instance
09-13 13:54:35.170  7995  8052 V AudioTrack: ~AudioTrack, releasing session id from 7995 on behalf of 7995
09-13 13:54:35.170   319  1368 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 13:54:35.170   319  1368 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 13:54:35.170   319  1368 V AudioFlinger: PlaybackThread::Track destructor
09-13 13:54:35.170   319  2172 V AudioFlinger: releasing 23 from 7995 for 7995
09-13 13:54:35.170   319  1368 V AudioFlinger: removeClient_l() pid 7995, calling pid 319
09-13 13:54:35.170   319  2172 V AudioFlinger:  decremented refcount to 0
09-13 13:54:35.170   319  2172 V AudioFlinger: purging stale effects
09-13 13:54:35.170  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.171  7995  8029 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 13:54:35.173   319  1271 V AudioPolicyService: AudioCommandThread() waking up
09-13 13:54:35.173   319  1271 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 13:54:35.173   319  1271 V AudioPolicyManager: releaseOutput() 2
09-13 13:54:35.173   319  1271 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 13:54:35.174  7995  7995 D A2dpService: Received start request. Starting profile...
09-13 13:54:35.175  7995  7995 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 13:54:35.177  1035  1618 W Process : Unable to open /proc/8053/status
09-13 13:54:35.177  7995  7995 V Avrcp   : make
09-13 13:54:35.178  7995  7995 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 13:54:35.178  7995  7995 I bluedroid-qcom: get_profile_interface avrcp
09-13 13:54:35.189  7995  7995 V AudioManager: registerRemoteController: size of Media player list: 0
,09-13 13:54:35.191  7995  7995 E AudioManager: No RCC entry present to update
,09-13 13:54:35.191  7995  7995 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 13:54:35.194  7995  7995 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 13:54:35.195  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 13:54:35.195  7995  7995 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 13:54:35.198  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 13:54:35.300  1035  2017 V SIM_STK : Menu title from STK is T-Mobile
09-13 13:54:35.300  1035  2017 V SIM_STK : Menu title from STK is T-Mobile
,09-13 13:54:35.420  1035  1618 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 13:54:35.430  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 13:54:35.435  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 13:54:35.437  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 13:54:35.438  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 13:54:35.438  7995  7995 I BluetoothA2dpServiceJni: classInitNative
09-13 13:54:35.443  7995  7995 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:54:35.443  7995  7995 D A2dpStateMachine: make
09-13 13:54:35.448  7995  7995 I bluedroid-qcom: get_profile_interface a2dp
,09-13 13:54:35.449  7995  8060 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 13:54:35.459  7995  7995 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,09-13 13:54:35.459  7995  7995 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 13:54:35.463  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
,09-13 13:54:35.468  7995  7995 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 13:54:35.469  7995  8059 D A2dpStateMachine: Enter Disconnected: -2
09-13 13:54:35.475  7995  7995 D HidService: Received start request. Starting profile...
,09-13 13:54:35.476  7995  7995 I bluedroid-qcom: get_profile_interface hidhost
09-13 13:54:35.476  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.478  7995  7995 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:54:35.483  7995  7995 D HealthService: Received start request. Starting profile...
,09-13 13:54:35.485  7995  7995 I bluedroid-qcom: get_profile_interface health
09-13 13:54:35.486  7995  7995 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:54:35.486  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.488  7995  7995 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 13:54:35.490  7995  7995 D PanService: Received start request. Starting profile...
09-13 13:54:35.490  7995  7995 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 13:54:35.491  7995  7995 I bluedroid-qcom: get_profile_interface pan
09-13 13:54:35.500  7995  7995 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 13:54:35.500  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
,09-13 13:54:35.502  7995  7995 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!,
09-13 13:54:35.509  7995  7995 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 13:54:35.509  7995  7995 D BtGatt.GattService: Received start request. Starting profile...
,09-13 13:54:35.509  7995  7995 D BtGatt.GattService: start(),
09-13 13:54:35.509  7995  7995 I bluedroid-qcom: get_profile_interface gatt,
09-13 13:54:35.510  7995  7995 D BtGatt.AdvertiseManager: advertise manager created
,09-13 13:54:35.519  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
,09-13 13:54:35.521  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:35.522  7995  7995 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 13:54:35.523  7995  7995 V BluetoothMapService: BluetoothMapBinder()
,09-13 13:54:35.524  7995  7995 D BluetoothMapService: Received start request. Starting profile...
09-13 13:54:35.524  7995  7995 D BluetoothMapService: start()
09-13 13:54:35.529  7995  7995 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 13:54:35.529  7995  7995 D BluetoothMapEmailAppObserver: createReceiver()
09-13 13:54:35.531  7995  7995 D BluetoothMapEmailAppObserver: initObservers()
09-13 13:54:35.531  7995  7995 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 13:54:35.541  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
,09-13 13:54:35.541  7995  7995 D HeadsetStateMachine: Proxy object connected
,09-13 13:54:35.542  7995  7995 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 13:54:35.543  7995  7995 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 13:54:35.545  7995  8052 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 13:54:35.546  7995  8052 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 13:54:35.546  7995  8052 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 13:54:35.552  7995  7995 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:35.556  7995  7995 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 13:54:35.560  7995  7995 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:35.562  7995  7995 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:35.565  7995  7995 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:35.569  7995  7995 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 13:54:35.569  7995  7995 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 13:54:35.573  7995  7995 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 13:54:35.573  7995  7995 V BluetoothMapService: Handler(): got msg=1
,09-13 13:54:35.575  7995  8029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 13:54:35.575  7995  8029 I bluedroid-qcom: enable
09-13 13:54:35.575  7995  7995 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:35.575  7995  7995 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:35.575  7995  7995 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:35.576  7995  7995 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:35.576  7995  7995 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 13:54:35.577  7995  8029 I bt_hci_bdroid: init
09-13 13:54:35.580  7995  8067 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 13:54:35.580  7995  8067 I bt-btu  : btu_task pending for preload complete event
09-13 13:54:35.582  7995  8029 I bt_vendor: bt-vendor : init
09-13 13:54:35.582  7995  8029 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 13:54:35.582  7995  8029 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 13:54:35.582  7995  8029 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 13:54:35.582  7995  8029 D bt_userial_mct: userial_init
09-13 13:54:35.583  7995  8029 D bt_hci_bdroid: set_power 1
09-13 13:54:35.583  7995  8029 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 13:54:35.583  7995  8029 I bt_vendor: Starting hciattach daemon
09-13 13:54:35.583  7995  8029 I bt_vendor: try to set true
,09-13 13:54:35.576  8070  8070 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:35.576  8070  8070 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:35.624  8071  8071 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 13:54:35.746  8077  8077 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 13:54:35.767  8078  8078 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 13:54:35.793  8080  8080 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 13:54:35.812  8081  8081 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 13:54:35.828  8085  8085 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 13:54:35.840  8086  8086 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 13:54:35.862  8088  8088 I libmdmdetect: ESOC framework not supported
09-13 13:54:35.863  8088  8088 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 13:54:35.874  8088  8088 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-13 13:54:35.874  8088  8088 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 13:54:35.874  8088  8088 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 13:54:35.874  8088  8088 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,09-13 13:54:35.874  8088  8088 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 13:54:35.874  8088  8088 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 13:54:35.874  8088  8088 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-13 13:54:35.918  8088  8089 E QC-QMI  : qmi_client [8088] 15: failed to locate client data
09-13 13:54:35.919   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 13:54:35.919   461   461 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-13 13:54:35.986  8090  8090 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 13:54:36.002  8094  8094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 13:54:36.057  7995  8029 I bt_vendor: bluetooth satus is on
,09-13 13:54:36.057  7995  8029 D bt_hci_bdroid: preload
,09-13 13:54:36.064  7995  8069 D bt_userial_mct: userial_open(port:0)
,09-13 13:54:36.064  7995  8069 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 13:54:36.070  7995  8069 I bt_vendor: Done intiailizing UART
09-13 13:54:36.073  7995  8069 I bt_vendor: Done intiailizing UART
09-13 13:54:36.073  7995  8069 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 13:54:36.074  7995  8069 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-13 13:54:36.082  7995  8067 I bt-btu  : btu_task received preload complete event
,09-13 13:54:36.083  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,09-13 13:54:36.083  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-13 13:54:36.090  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-13 13:54:36.104  7995  8096 D bt_userial_mct: Entering userial_read_thread()
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 13:54:36.109  7995  8067 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 13:54:36.165  7995  8067 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 13:54:36.165  7995  8067 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0160061 
09-13 13:54:36.165  7995  8067 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0160061 
,09-13 13:54:36.190  7995  8033 E bt-btif : Calling BTA_HhEnable
09-13 13:54:36.190  7995  8033 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 13:54:36.191  7995  8033 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-13 13:54:36.195  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 13:54:36.195  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 13:54:36.195  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 13:54:36.195  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 13:54:36.195  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 13:54:36.197  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 13:54:36.198  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 13:54:36.198  7995  8033 D BluetoothAdapterProperties: Name is: G3
09-13 13:54:36.201  7995  8033 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:54:36.201  7995  8033 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:54:36.201  7995  8033 D bt_hci_bdroid: postload
09-13 13:54:36.202  7995  8069 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:36.203  7995  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 13:54:36.205  7995  8033 D bte_conf: Device ID record 1 : primary
09-13 13:54:36.205  7995  8033 D bte_conf:   vendorId            = 00c4
09-13 13:54:36.205  7995  8033 D bte_conf:   vendorIdSource      = 0001
09-13 13:54:36.205  7995  8033 D bte_conf:   product             = 13a1
09-13 13:54:36.205  7995  8033 D bte_conf:   version             = 1000
09-13 13:54:36.205  7995  8033 D bte_conf:   clientExecutableURL = 
09-13 13:54:36.205  7995  8033 D bte_conf:   serviceDescription  = 
09-13 13:54:36.205  7995  8033 D bte_conf:   documentationURL    = 
09-13 13:54:36.205  7995  8033 D bte_conf: bte_load_did_conf no section named DID2.
,09-13 13:54:36.211  7995  8069 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:36.216  7995  8069 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:36.219  7995  8029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 13:54:36.219  7995  8029 D BluetoothAdapterProperties: ScanMode =  20
09-13 13:54:36.219  7995  8029 D BluetoothAdapterProperties: State =  11
09-13 13:54:36.219  7995  8029 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 13:54:36.220  7995  8029 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 13:54:36.220  7995  8029 D BluetoothAdapterProperties: Setting state to 12
09-13 13:54:36.220  7995  8029 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 13:54:36.216  8098  8098 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:36.216  8098  8098 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:36.235  7995  8033 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 13:54:36.235  7995  8033 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 13:54:36.241  1035  1117 D BluetoothManagerService: Message: 60
09-13 13:54:36.241  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 13:54:36.241  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 13:54:36.242  7995  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:36.242  7995  8067 W bt-smp  : Plain text(LSB ~ MSB) = 2d 3d 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:36.242  7995  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = ab 4c e9 30 11 28 d0 b8 59 2f a5 b6 e1 4a 07 51 
09-13 13:54:36.242  7995  8069 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 13:54:36.242  7995  8067 W bt-btm  : Stopping oneshot timer
09-13 13:54:36.245  7995  8096 E bt_mct  : hci lib postload completed
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:36.261  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:54:36.272  7995  8029 I BluetoothAdapterState: Entering On State
09-13 13:54:36.276  7995  8033 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:54:36.277  7995  8033 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-13 13:54:36.279  7995  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:36.279  7995  8067 W bt-smp  : Plain text(LSB ~ MSB) = f1 46 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:36.279  7995  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = be 3b 38 3a f4 38 12 d0 cd 5c b9 a2 6e b5 29 30 
09-13 13:54:36.282  7995  8067 W bt-btm  : Stopping oneshot timer
09-13 13:54:36.292  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:36.301  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:36.303  7995  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:36.303  7995  8067 W bt-smp  : Plain text(LSB ~ MSB) = 36 91 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:36.303  7995  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = aa 60 01 3d c7 7e fa 3f fb 83 63 dc 0f ea 1e 68 
09-13 13:54:36.303  7995  8067 W bt-btm  : Stopping oneshot timer
09-13 13:54:36.319  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:54:36.330  7995  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:36.330  7995  8067 W bt-smp  : Plain text(LSB ~ MSB) = 76 0e 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:36.330  7995  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = a0 d6 b3 6f ef d9 5f 7d 16 00 a6 cc c4 3f dc 34 
09-13 13:54:36.330  7995  8067 W bt-btm  : Stopping oneshot timer
09-13 13:54:36.336  7995  8029 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 13:54:36.336  7995  8029 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 13:54:36.336  7995  8029 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-13 13:54:36.339  7995  8029 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 13:54:36.339  7995  8029 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 13:54:36.340  6935  6973 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:36.348  8103  8103 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-13 13:54:36.356  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:54:36.357  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 13:54:36.359  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:36.361  7995  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 13:54:36.361  7995  8067 W bt-smp  : Plain text(LSB ~ MSB) = 0e 73 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 13:54:36.361  7995  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d e6 d8 a9 56 c3 24 18 6f 38 81 99 1c ae 04 a2 
09-13 13:54:36.361  7995  8067 W bt-btm  : Stopping oneshot timer
09-13 13:54:36.373  6935  6935 D BluetoothHeadset: Proxy object connected
09-13 13:54:36.373  6935  6935 D HeadsetProfile: Bluetooth service connected
,09-13 13:54:36.381  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:36.386  6935  6973 D BluetoothMap: onBluetoothStateChange: up=true
09-13 13:54:36.386  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 13:54:36.388  6935  6950 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 13:54:36.390  6935  6935 D BluetoothMap: Proxy object connected
09-13 13:54:36.390  6935  6935 D MapProfile: Bluetooth service connected
09-13 13:54:36.390  6935  6935 D BluetoothMap: getConnectedDevices()
09-13 13:54:36.391  6935  6973 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:54:36.392  6935  6950 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:54:36.394  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:54:36.395  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 13:54:36.396  6935  6950 D BluetoothPan: onBluetoothStateChange on: true
09-13 13:54:36.396  6935  6950 D BluetoothPan: onBluetoothStateChange call bindService
09-13 13:54:36.397  7995  8012 V BluetoothMapService: getConnectedDevices()
09-13 13:54:36.397  6935  6935 D BluetoothA2dp: Proxy object connected
09-13 13:54:36.397  6935  6935 D A2dpProfile: Bluetooth service connected
09-13 13:54:36.400  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:54:36.401  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 13:54:36.402  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 13:54:36.402  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 13:54:36.403  6935  6935 D BluetoothInputDevice: Proxy object connected
09-13 13:54:36.403  6935  6935 D HidProfile: Bluetooth service connected
09-13 13:54:36.405  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:36.406  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.407  1564  1564 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 13:54:36.410  1926  2087 D LGBluetoothAPIService: Message: 1
09-13 13:54:36.410  1926  2087 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 13:54:36.410  1926  2087 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-13 13:54:36.410  1926  2087 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-13 13:54:36.413  7995  7995 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.413  7995  7995 D BluetoothMapService: STATE_ON
09-13 13:54:36.413  7995  7995 V BluetoothMapService: Handler(): got msg=1
09-13 13:54:36.414  7995  7995 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,09-13 13:54:36.415  7995  8119 D BluetoothMapMasInstance: MAS initSocket()
09-13 13:54:36.416  7995  8119 D BluetoothMapMasInstance:   masId = 00
09-13 13:54:36.416  7995  8119 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 13:54:36.416  7995  8119 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 13:54:36.416  7995  8119 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 13:54:36.417  1035  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:36.418  7995  8119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:36.420  7995  8119 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 13:54:36.420  7995  8119 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 13:54:36.421  7995  8119 D BluetoothMapMasInstance: Accepting socket connection...
09-13 13:54:36.421  7995  8033 D BluetoothAdapterProperties: Scan Mode:21
09-13 13:54:36.421  7995  8033 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 13:54:36.421  6935  6935 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:54:36.422  6935  6935 D PanProfile: Bluetooth service connected
09-13 13:54:36.425  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:36.425  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:36.425  7995  7995 V BluetoothPbapService: Pbap Service onCreate
09-13 13:54:36.425  7995  7995 V BluetoothPbapService: Starting PBAP service
,09-13 13:54:36.426  7995  7995 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 13:54:36.426  7995  7995 V BluetoothPbapService: Handler(): got msg=1
09-13 13:54:36.426  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:36.427  7995  7995 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 13:54:36.427  7995  7995 V BluetoothPbapService: Pbap Service onBind
09-13 13:54:36.427  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:36.430  7995  7995 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.430  7995  7995 V BluetoothPbapService: state: 12
09-13 13:54:36.430  7995  8120 V BluetoothPbapService: Pbap Service initSocket
09-13 13:54:36.431  1035  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:36.432  7995  8120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:36.432  7995  8120 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 13:54:36.432  7995  8120 V BluetoothPbapService: Succeed to create listening socket 
09-13 13:54:36.432  7995  8120 V BluetoothPbapService: Accepting socket connection...
09-13 13:54:36.433  6935  6935 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 13:54:36.434  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 13:54:36.436  6935  6935 D BluetoothPbap: Proxy object connected
09-13 13:54:36.436  6935  6935 D PbapServerProfile: Bluetooth service connected
09-13 13:54:36.437  7995  7995 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 13:54:36.438  7995  7995 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.438  7995  7995 V BluetoothPbapReceiver: ***********state = 12
,09-13 13:54:36.440  6935  6935 D DockEventReceiver: finishStartingService: stopping service
09-13 13:54:36.441  2125  2125 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:54:36.442  2125  2125 D c       : Getting all permits...
09-13 13:54:36.442  2125  2125 D a       : Opening database...
09-13 13:54:36.446  2125  2125 D a       : Opening database auth.proximity.permit_store...
09-13 13:54:36.446  2125  2125 D a       : Closing database...
09-13 13:54:36.453  6935  6935 D BluetoothPermissionRequest: onReceive
,09-13 13:54:36.455  6935  6935 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 13:54:36.456  6935  6935 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 13:54:36.458  7995  7995 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 13:54:36.459  7995  7995 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 13:54:36.464  7995  7995 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-13 13:54:36.479  7995  7995 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 13:54:36.480  7995  7995 V BtOppService: onCreate
,09-13 13:54:36.484  7995  7995 V BluetoothOppNotification: send message
09-13 13:54:36.486  7995  7995 V BtOppService: Starting RfcommListener
09-13 13:54:36.492  7995  8127 V BtOppService: Deleted complete outbound shares, number =  0
,09-13 13:54:36.494  7995  8127 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 13:54:36.497  7995  7995 D BluetoothOppPreference: Dumping Names:  
09-13 13:54:36.497  7995  7995 D BluetoothOppPreference: {}
09-13 13:54:36.497  7995  7995 D BluetoothOppPreference: Dumping Channels:  
09-13 13:54:36.497  7995  7995 D BluetoothOppPreference: {}
09-13 13:54:36.498  7995  8127 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 13:54:36.499  7995  7995 V BtOppService: onStartCommand
09-13 13:54:36.500  7995  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1955fcec on behalf of 
09-13 13:54:36.501  7995  8131 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 13:54:36.501  7995  8131 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 13:54:36.502  7995  8131 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@734c8b5 on behalf of 
09-13 13:54:36.503  7995  8131 V BluetoothOppNotification: update too frequent, put in queue
09-13 13:54:36.503  7995  8131 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 13:54:36.504  7995  7995 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.504  7995  7995 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-13 13:54:36.506  7995  7995 V BluetoothOppNotification: new notify threadi!
09-13 13:54:36.507  7995  7995 V BluetoothOppNotification: send delay message
09-13 13:54:36.508  7995  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 13:54:36.508  7995  7995 V BtOppService: start RfcommListener
09-13 13:54:36.509  7995  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@179ecb4a on behalf of 
09-13 13:54:36.510  7995  8132 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 13:54:36.511  7995  7995 V BtOppService: RfcommListener started
09-13 13:54:36.511  7995  7995 V BtOppService: ContentObserver received notification
09-13 13:54:36.511  7995  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 13:54:36.512  7995  7995 V BtOppService: ContentObserver received notification
09-13 13:54:36.512  7995  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35c94abb on behalf of 
09-13 13:54:36.513  7995  8134 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 13:54:36.513  7995  8134 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 13:54:36.513  7995  8132 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 13:54:36.514  7995  8134 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31bfbd8 on behalf of 
09-13 13:54:36.515  7995  8132 V BluetoothOppNotification: outbound notification was removed.
09-13 13:54:36.515  1035  1035 I art     : Explicit concurrent mark sweep GC freed 29155(1427KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.647ms total 153.965ms
09-13 13:54:36.515  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 13:54:36.515  7995  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 13:54:36.516  7995  8133 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 13:54:36.516  1035  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 13:54:36.517  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 13:54:36.518  1035  1117 D BluetoothManagerService: Message: 40
09-13 13:54:36.518  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,09-13 13:54:36.518  7995  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ab63b31 on behalf of 
09-13 13:54:36.519  7995  8132 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 13:54:36.522  7995  8132 V BluetoothOppNotification: inbound notification was removed.
09-13 13:54:36.523  7995  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-13 13:54:36.523  7995  8133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:36.523  7995  8134 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 13:54:36.525  7995  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e865216 on behalf of 
09-13 13:54:36.526  7995  8133 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-13 13:54:36.527  7995  8133 V BtOppRfcommListener: Started RFCOMM listener....
09-13 13:54:36.527  7995  8133 I BtOppRfcommListener: Accept thread started.
09-13 13:54:36.527  7995  8133 V BtOppRfcommListener: Accepting connection...
09-13 13:54:36.528  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
09-13 13:54:36.528  7995  7995 V BluetoothFtpService: Ftp Service onCreate
09-13 13:54:36.528  7995  7995 I BluetoothFtpService: Ftp Service onCreate
09-13 13:54:36.528  7995  7995 V BluetoothFtpService: Ftp Service onStartCommand
09-13 13:54:36.529  7995  7995 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.529  7995  7995 V BluetoothFtpService: Starting Listening on sockets
09-13 13:54:36.529  7995  7995 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 13:54:36.529  7995  7995 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 13:54:36.529  7995  7995 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 13:54:36.529  7995  7995 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.529  7995  7995 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 13:54:36.529  7995  7995 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-13 13:54:36.531  7995  7995 V BluetoothFtpService: Handler(): got msg=1
09-13 13:54:36.532  7995  7995 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 13:54:36.532  7995  7995 V BluetoothFtpService: Ftp Service initSocket
09-13 13:54:36.534  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:36.536  7995  7995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:36.539  7995  7995 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-13 13:54:36.539  7995  7995 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 13:54:36.540  7995  8135 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 13:54:36.548  7995  7995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15501130
,09-13 13:54:36.548  7995  7995 V BluetoothSapService: Sap Service onCreate
09-13 13:54:36.550  7995  7995 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:54:36.550  7995  7995 V BluetoothSapService: state: 12
09-13 13:54:36.550  7995  7995 V BluetoothSapService: Starting SAP server process
09-13 13:54:36.551  7995  7995 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-13 13:54:36.536  8137  8137 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:36.536  8137  8137 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:36.552  7995  8138 V BluetoothSapService: Sap Service initRfcommSocket
09-13 13:54:36.552  1035  1748 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:54:36.553  7995  8138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:54:36.553  7995  8138 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-13 13:54:36.553  7995  8138 V BluetoothSapService: Succeed to create listening socket 
09-13 13:54:36.554  7995  8138 V BluetoothSapService: Accepting socket connection...
09-13 13:54:36.560  8137  8137 V BT_SAP  : Event pipe created
09-13 13:54:36.560  8137  8137 V BT_SAP  : create_server_socket qcom.sap.server
09-13 13:54:36.560  8137  8137 V BT_SAP  : created socket fd 6
,09-13 13:54:37.509  7995  7995 V BluetoothOppNotification: new notify threadi!
,09-13 13:54:37.509  7995  7995 V BluetoothOppNotification: send delay message
,09-13 13:54:37.522  7995  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 13:54:37.526  7995  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c985633 on behalf of 
09-13 13:54:37.527  7995  8148 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 13:54:37.529  7995  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-13 13:54:37.532  7995  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25926df0 on behalf of 
09-13 13:54:37.533  7995  8148 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 13:54:37.535  7995  8148 V BluetoothOppNotification: outbound notification was removed.
09-13 13:54:37.535  7995  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-13 13:54:37.536  7995  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14781f69 on behalf of 
09-13 13:54:37.536  7995  8148 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 13:54:37.538  7995  8148 V BluetoothOppNotification: inbound notification was removed.
09-13 13:54:37.538  7995  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 13:54:37.539  7995  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4ed8dee on behalf of 
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:40.000  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:54:40.010  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:54:40.010  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:54:40.010  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d5288b3 removed from the list
09-13 13:54:40.011  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:40.011  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:54:40.011  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:54:40.012  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:54:40.012  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3cee70 added. We now have 4 listener(s)
09-13 13:54:40.012  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:54:40.014  1035  1944 D WifiServiceImplEx: setWifiEnabled: false pid=6786, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 13:54:40.014  1035  1944 D WifiService: setWifiEnabled: false pid=6786, uid=10118
09-13 13:54:40.014  1035  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 13:54:45.025  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:54:45.038  1035  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6786, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 13:54:45.038  1035  1051 D WifiService: setWifiEnabled: true pid=6786, uid=10118
09-13 13:54:45.039  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 13:54:45.055  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 13:54:45.056  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 13:54:45.056  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 13:54:45.059  1035  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 13:54:45.060  1035  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 13:54:45.062  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 13:54:45.062  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 13:54:45.062  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 13:54:45.062  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 13:54:45.062  1035  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 13:54:45.063  1035  1521 E WifiHW  : unknown target_country: EU , set to default
09-13 13:54:45.063  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 13:54:45.063  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 13:54:45.063  1035  1521 I WifiUtil: gEnableBmps=1
09-13 13:54:45.635   314   893 D SoftapController: Softap fwReload - Ok
,09-13 13:54:45.646  1035  1521 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (581ms)
09-13 13:54:45.649   314   893 D CommandListener: Setting iface cfg
09-13 13:54:45.649   314   893 D CommandListener: Trying to bring down wlan0
,09-13 13:54:45.666  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 13:54:45.666  1035  1117 D Tethering: InitialState.processMessage what=4
,09-13 13:54:45.674   314   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:54:45.677  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 13:54:45.694  1035  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-13 13:54:45.686  8159  8159 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:45.696  8159  8159 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:45.707  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:45.707  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:45.707  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 13:54:45.710  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 13:54:45.735  1035  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 13:54:45.735  1035  1521 D WifiMonitor: connecting to supplicant
09-13 13:54:45.744  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-13 13:54:45.754  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:45.755  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 13:54:45.760  8159  8159 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 13:54:45.773  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:45.775  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-13 13:54:45.775  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-13 13:54:45.775  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-13 13:54:45.779  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:54:45.779  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:45.781  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:45.781  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 13:54:45.781  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:45.781  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:45.781  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:45.782  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 13:54:45.786  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 13:54:45.786  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 13:54:45.786  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 13:54:45.786  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 13:54:45.787  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:45.787  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:45.788  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 13:54:45.788  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:45.788  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:45.788  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:45.788  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 13:54:45.831  1035  1943 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8176 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 13:54:45.837  8159  8159 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 13:54:45.837  8159  8159 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 13:54:45.936  8159  8159 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 13:54:45.951  1035  1944 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8199 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 13:54:45.960  8176  8197 W FormManager: Network not available. Please check & try again.
09-13 13:54:45.965  8176  8198 V FormManager: Network unavailable.
,09-13 13:54:45.968  8159  8159 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-13 13:54:45.975  8176  8198 V FormManager: Network unavailable.
09-13 13:54:45.977  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 13:54:45.978  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 13:54:45.978  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 13:54:45.979  1035  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 13:54:45.979  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:45.980  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:45.980  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:45.981  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:45.981  8159  8159 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 13:54:45.982  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 13:54:45.982  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 13:54:45.982  1035  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 13:54:45.982  1035  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 13:54:45.982  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 13:54:45.982  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 13:54:45.982  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 13:54:45.982  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 13:54:45.982  1035  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 13:54:45.983  1035  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 13:54:45.983  1035  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 13:54:45.983  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 13:54:45.983  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
09-13 13:54:45.983  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 13:54:45.983  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:45.983  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:45.984  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:45.984  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:45.984  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 13:54:45.986  1926  1926 D WfdService: Waiting for WifiP2p enabling
09-13 13:54:45.987  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:45.992  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 13:54:45.993  1035  2036 I ActivityManager: Killing 7198:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-13 13:54:45.994  1035  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:45.996  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:45.998  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:45.999  1035  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 13:54:45.999  1035  1521 D WifiNative-wlan0: SET update_config 1: returned true
09-13 13:54:45.999  1035  1521 D WifiConfigStore: Loading config and enabling all networks 
09-13 13:54:45.999  1035  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 13:54:46.000  1035  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:54:46.001  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:54:46.002  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:54:46.006  1035  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-13 13:54:46.015  1035  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 13:54:46.016  1035  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 13:54:46.026  1035  1558 W libprocessgroup: failed to open /acct/uid_10046/pid_7198/cgroup.procs: No such file or directory
09-13 13:54:46.029  1035  1521 D WifiStateMachine: enableVerboseLogging : level 2
09-13 13:54:46.029  1035  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 13:54:46.029  1035  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 13:54:46.029  1035  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 13:54:46.030  1035  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 13:54:46.030  1035  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,09-13 13:54:46.030  1035  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 13:54:46.030  1035  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 13:54:46.031  1035  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 13:54:46.031  1035  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 13:54:46.031  1035  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 13:54:46.031  1035  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 13:54:46.032  1035  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 13:54:46.032  1035  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 13:54:46.032  1035  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 13:54:46.033  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 13:54:46.033  1035  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 13:54:46.033  1035  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 13:54:46.033  1035  1521 D WifiNative-HAL: Setting external_sim to 1
09-13 13:54:46.033  1035  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 13:54:46.033  1926  1926 D WfdsService: Supplicant Connection state is changed : true
09-13 13:54:46.034  1926  2251 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 13:54:46.034  1926  2251 D WfdsService: Set the WFDS Monitor: true
09-13 13:54:46.034  1926  2251 D WfdsMonitor: WfdsMonitorThread create
09-13 13:54:46.034  1926  2251 D WfdsMonitor: WFDS Monitor is created and started
09-13 13:54:46.034  1926  2251 D WfdsService: WiFi: Supplicant connection re-established
09-13 13:54:46.034  7780  7780 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.034  1035  1521 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 13:54:46.034  1035  1521 I WifiNative-HAL: startHal
09-13 13:54:46.034  1035  1521 D wifi    : setting scan oui 0xaf6e8660
09-13 13:54:46.035  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 13:54:46.035  1035  1521 I WifiNative-HAL: startHal
09-13 13:54:46.035  1035  1521 D wifi    : setting scan oui 0xaf6e8660
09-13 13:54:46.035  1926  8218 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 13:54:46.035  1035  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 13:54:46.035  1926  8218 E CtrlSupplicant: Succeed to open control connection
09-13 13:54:46.035  1035  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 13:54:46.035  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 13:54:46.035  1926  8218 E CtrlSupplicant: Succeed to open monitor connection
09-13 13:54:46.035  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 13:54:46.035  1926  8218 D WfdsMonitor: Supplicant connection established
09-13 13:54:46.036  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 13:54:46.036  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 13:54:46.036  1926  2251 D WfdsService: Connected to the supplicant for wfds
09-13 13:54:46.036  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 13:54:46.036  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 13:54:46.036  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 13:54:46.036  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-13 13:54:46.037  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 13:54:46.037  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 13:54:46.037  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 13:54:46.037  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 13:54:46.037  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 13:54:46.037  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 13:54:46.038  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 13:54:46.038  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 13:54:46.038  8159  8159 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-13 13:54:46.038  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 13:54:46.038  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 13:54:46.039  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 13:54:46.039  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 13:54:46.040  1035  1521 E WifiNative: : [396,460,917 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 13:54:46.040  1035  1521 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 13:54:46.040  1035  1521 D WifiNative-wlan0: RECONNECT: returned true
09-13 13:54:46.040  1035  1521 D WifiNative-wlan0: doString: [STATUS]
09-13 13:54:46.041  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 13:54:46.041  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 13:54:46.041  1035  1521 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 13:54:46.041  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 13:54:46.042  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:46.042  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.043   314   893 D CommandListener: Setting iface cfg
09-13 13:54:46.043   314   893 D CommandListener: Trying to bring up p2p0
09-13 13:54:46.044  1035  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 13:54:46.044  1035  1520 D LGWifiP2pService: P2pEnablingState
09-13 13:54:46.044  1035  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.044  1035  1520 D LGWifiP2pService: P2p socket connection successful
09-13 13:54:46.044  1035  1520 D LGWifiP2pService: P2pEnabledState
09-13 13:54:46.045  1035  1520 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 13:54:46.045  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 13:54:46.045  1926  1926 D WfdsService: WifiP2pState is changed : true
09-13 13:54:46.045  1926  2251 D WfdsService: Receive the WFDS_ENABLE Method
09-13 13:54:46.045  1035  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 13:54:46.045  1926  2251 D WfdsService: Set the WFDS Monitor: true
09-13 13:54:46.046  1926  2251 D WfdsService: Connected to the supplicant for wfds
09-13 13:54:46.046  1926  2251 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 13:54:46.046  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 13:54:46.046  8159  8159 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 13:54:46.046  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 13:54:46.046  1035  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.046  1035  1539 I WifiNative-HAL: startHal
09-13 13:54:46.046  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 13:54:46.046  1035  1540 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.046  1926  1926 D WfdsService: isConnected: false
,09-13 13:54:46.046  1926  2251 D WfdsService: selectPreferredScanChannel [36]
09-13 13:54:46.046  1926  2251 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-13 13:54:46.047  1035  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 13:54:46.047  1035  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 13:54:46.047  1035  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf6e8660
09-13 13:54:46.047  1035  1539 D wifi    : failed to get capabilities : -3
09-13 13:54:46.047  1035  1539 E WifiScanningService: could not get scan capabilities
09-13 13:54:46.047  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 13:54:46.047  1035  1520 D WifiNative-p2p0: SET device_name G3: returned true
09-13 13:54:46.047  1035  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 13:54:46.047  1035  1520 D LGWifiP2pService: before postfix = G3
09-13 13:54:46.047  1035  1520 D WifiServerServiceExt: postfix byte check : 2
09-13 13:54:46.048  1035  1520 D LGWifiP2pService: after postfix = G3
09-13 13:54:46.048  1035  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 13:54:46.048  1035  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 13:54:46.048  1035  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
,09-13 13:54:46.048  1035  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 13:54:46.048  1035  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 13:54:46.048  1035  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 13:54:46.048  1035  1520 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 13:54:46.048  1035  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 13:54:46.049  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=396470  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 13:54:46.049  1035  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 13:54:46.049  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 13:54:46.050  1035  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 13:54:46.050  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress
09-13 13:54:46.050  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=396471  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 13:54:46.050  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 13:54:46.050  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.050  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.051  1035  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 13:54:46.051  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.051  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.051  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 13:54:46.052  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.052  1035  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 13:54:46.052  1035  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 13:54:46.052  1035  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 13:54:46.052  8159  8159 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 13:54:46.053  1035  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 13:54:46.054  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 13:54:46.054  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 13:54:46.054  1926  1926 D WfdsService: Update P2p Interface State: 3
09-13 13:54:46.054  1035  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 13:54:46.054  1035  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 13:54:46.054  1035  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 13:54:46.054  1035  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 13:54:46.054  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 13:54:46.054  1035  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 13:54:46.054  1035  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 13:54:46.055  1035  1520 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 13:54:46.055  1035  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 13:54:46.055  1035  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 13:54:46.055  1035  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,09-13 13:54:46.060  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:46.062  8159  8159 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 13:54:46.062  1035  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 13:54:46.062  1035  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-13 13:54:46.062  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 13:54:46.062  1035  1520 D LGWifiP2pService: InactiveState
09-13 13:54:46.062  1035  1520 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.062  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.062  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 13:54:46.062  1035  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 13:54:46.063  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 13:54:46.063  8159  8159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.063  1035  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 13:54:46.063  1035  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.063  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.064  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.064  8159  8159 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 13:54:46.064  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 13:54:46.064  1926  8218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 13:54:46.064  1035  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 13:54:46.064  8159  8159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.064  1035  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-13 13:54:46.064  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 13:54:46.064  1035  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.064  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 13:54:46.065  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.065  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.065  8159  8159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.065  1035  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.065  1035  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.065  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.065  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.065  1926  8218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.065  1926  8218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.065  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.065  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.065  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.066  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 13:54:46.066  8159  8159 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.066  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 13:54:46.066  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.066  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.066  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 13:54:46.066  8159  8159 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 13:54:46.066  8159  8159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  8159  8159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 13:54:46.067  1035  1520 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1521 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.067  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:46.067  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 13:54:46.068  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 13:54:46.068  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 13:54:46.068  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 13:54:46.068  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 13:54:46.068  8159  8159 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:46.068  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 13:54:46.068  1035  1906 I ActivityManager: Killing 7230:com.android.chrome/u0a57 (adj 15): empty #17
09-13 13:54:46.068  1926  8218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.068  1926  8218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.068  1035  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.068  1035  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.068  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.068  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.068  1926  2251 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 13:54:46.069  1035  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 13:54:46.069  1035  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.069  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.069  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 13:54:46.069  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 13:54:46.069  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:46.069  1035  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:46.069  1035  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 13:54:46.070  1035  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 13:54:46.070  1035  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 13:54:46.071  1035  1521 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 13:54:46.071  1035  1521 D WifiNative-wlan0: doBoolean: SCAN
09-13 13:54:46.071  1035  1521 D WifiNative-wlan0: SCAN: returned false
09-13 13:54:46.071  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=396493  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 13:54:46.086  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE,_CHANGE_EVENT 46 0 rt=396508  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 13:54:46.087  1035  1521 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:46.087  1035  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:46.087  1035  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:46.087  1035  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 13:54:46.087  1035  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-13 13:54:46.089  1035  1962 W libprocessgroup: failed to open /acct/uid_10057/pid_7230/cgroup.procs: No such file or directory
09-13 13:54:46.089  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.089  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.089  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 13:54:46.089  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.089  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.091  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.093  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.093  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 13:54:46.102  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:46.107  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 13:54:46.110  1564  1564 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 13:54:46.110  1564  1564 I [SystemUI]LGPowerUI: On Skip Timer : true
09-13 13:54:46.110  8176  8222 W FormManager: Network not available. Please check & try again.
09-13 13:54:46.112  1035  1527 D WifiController: battery changed pluggedType: 2
09-13 13:54:46.113  1564  1564 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
09-13 13:54:46.113  1564  1564 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 13:54:46.114  1926  2081 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 13:54:46.114  1926  2081 D LEDHandler: Battery Level Remaining: 100%
09-13 13:54:46.114  1926  2081 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
09-13 13:54:46.114  1564  1564 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-13 13:54:46.115  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.115  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.115  7995  8052 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 13:54:46.116  8176  8223 V FormManager: Network unavailable.
09-13 13:54:46.117  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:46.125  8176  8223 V FormManager: Network unavailable.
09-13 13:54:46.126  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 13:54:46.127  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:46.128  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:46.129  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:46.135  4291  8224 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:46.136  4291  8225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 13:54:46.136  4291  8225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:46.161  1035  1944 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 13:54:46.247  8226  8226 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 13:54:46.247  8226  8226 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 13:54:46.258  8226  8226 V [BNRBootReceiver]: Boot Receiver Return
09-13 13:54:46.259  8226  8226 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 13:54:46.325  1035  1051 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8244 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 13:54:46.327  1035  1051 I ActivityManager: Killing 7249:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-13 13:54:46.387  1035  1050 W libprocessgroup: failed to open /acct/uid_10062/pid_7249/cgroup.procs: No such file or directory
,09-13 13:54:46.429  8244  8244 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 13:54:46.471  8244  8244 D PluginManager: init()
,09-13 13:54:46.551  8159  8159 E wpa_supplicant: USIM:  scard_init function
,09-13 13:54:46.551  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 13:54:46.551  1035  8217 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 13:54:46.552  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 13:54:46.552  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-13 13:54:46.552  1035  8217 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 13:54:46.552  8159  8159 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-13 13:54:46.555  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 13:54:46.555  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 13:54:46.558  1035  1521 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-13 13:54:46.561  1035  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-13 13:54:46.563  1035  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-13 13:54:46.564  1035  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-13 13:54:46.564  1035  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 13:54:46.578  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=397000  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 13:54:46.584  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=397006  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 13:54:46.585  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.585  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.586  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.586  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.587  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 13:54:46.588  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.588  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 13:54:46.588  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.678  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 13:54:46.678  8159  8159 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 13:54:46.678  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 13:54:46.678  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 13:54:46.678  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,09-13 13:54:46.683  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:46.683  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:46.683  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=397104  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 13:54:46.684  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=397105  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 13:54:46.685  1035  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397106
09-13 13:54:46.685  1035  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397106
09-13 13:54:46.685  1035  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397107
09-13 13:54:46.686  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397107
09-13 13:54:46.686  1035  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=397107
09-13 13:54:46.686  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=397108  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 13:54:46.689  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.689  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.689  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.689  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.689  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 13:54:46.690  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 13:54:46.690  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.692  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=397113  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 13:54:46.697  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:46.697  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:46.697  8159  8159 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:54:46.697  8159  8159 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 13:54:46.698  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 13:54:46.698  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:54:46.698  1035  8217 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 13:54:46.698  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 13:54:46.698  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 13:54:46.698  1035  8217 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 13:54:46.698  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:46.698  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:46.702  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.702  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.703  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 13:54:46.704  1035  1521 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:46.704  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.704  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 13:54:46.705  1035  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,09-13 13:54:46.705  1035  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:46.706  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:46.706  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 13:54:46.707  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.707  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 13:54:46.708  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=397128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 13:54:46.708  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=397129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 13:54:46.709  1035  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=397130
09-13 13:54:46.709  1035  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=397130
09-13 13:54:46.710  1035  1521 D WifiNative-wlan0: doString: [STATUS]
09-13 13:54:46.710  1035  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 13:54:46.710  1035  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 13:54:46.710  1035  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 13:54:46.710  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.710  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.711  1035  1521 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 13:54:46.713  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.716  1035  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 13:54:46.716  1035  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 13:54:46.720  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.720  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.720  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 13:54:46.722  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.722  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.722  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 13:54:46.729  1035  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 13:54:46.729  1035  1528 D ConnectivityService: Got NetworkAgent Messenger
09-13 13:54:46.729  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 13:54:46.730  1035  1528 D ConnectivityService: NetworkAgent connected
09-13 13:54:46.730  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:54:46.730  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-13 13:54:46.730  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 13:54:46.730  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 13:54:46.734  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.734  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.735  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.737  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.737  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.737  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 13:54:46.737  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:54:46.737  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 13:54:46.738  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.739  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 13:54:46.739  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 13:54:46.743  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 13:54:46.745   314   893 D CommandListener: Setting iface cfg
,09-13 13:54:46.748  1035  1521 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 13:54:46.748  1035  8265 D DhcpStateMachine: StoppedState
09-13 13:54:46.748  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=397169  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:46.748  1035  8265 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.748  1035  8265 D DhcpStateMachine: WaitBeforeStartState
09-13 13:54:46.748  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=397170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:46.749  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=397170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:46.749  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.749  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 13:54:46.750  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=397171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:46.750  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=397172  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:46.751  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=397172  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 13:54:46.751  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29019] from screen [on:0 period:593904223] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:46.752  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:593904224] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:46.752  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:54:46.755  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.756  1035  1528 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-13 13:54:46.756  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:46.756  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:46.757  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:46.757  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:46.757  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:46.757  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 13:54:46.757  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 13:54:46.758  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
09-13 13:54:46.758  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
09-13 13:54:46.758  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 13:54:46.758  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 13:54:46.759  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 13:54:46.759  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 13:54:46.759  1035  1521 D WifiNative-wlan0: SET ps 0: returned true
09-13 13:54:46.759  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 13:54:46.759  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 13:54:46.764  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 13:54:46.764  1035  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 13:54:46.764  1035  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 13:54:46.764  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@124ed659 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.764  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@124ed659 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.764  1035  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 13:54:46.765  1035  8265 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.765  1035  8265 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 13:54:46.765   314   893 D CommandListener: Setting iface cfg
09-13 13:54:46.766   314   893 D CommandListener: Trying to bring up wlan0
09-13 13:54:46.766  1035  1521 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 13:54:46.767  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.767  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 13:54:46.767  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 13:54:46.768  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 13:54:46.768  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 13:54:46.768  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 13:54:46.768  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.768  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.768  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 13:54:46.768  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 13:54:46.768  1035  1521 D WifiNativ,e-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 13:54:46.768  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 13:54:46.769  8159  8159 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 13:54:46.769  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 13:54:46.769  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
,09-13 13:54:46.785  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
09-13 13:54:46.786  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 13:54:46.786  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:46.787  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:46.787  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:46.787  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:46.788  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:46.788  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 13:54:46.789  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 13:54:46.789  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 13:54:46.789  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 13:54:46.789  1035  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 13:54:46.790  1035  1528 D ConnectivityService: ignoring duplicate network state non-change
09-13 13:54:46.792  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.792  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.793  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.794  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.794  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 13:54:46.796  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.796  1035  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 13:54:46.798  1035  1528 D ConnectivityService: Adding iface wlan0 to network 102
09-13 13:54:46.800  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.800  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.800  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 13:54:46.801  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 13:54:46.805  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-13 13:54:46.807  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.807  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.807  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 13:54:46.809  1035  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 13:54:46.815  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 13:54:46.816  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.816  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:46.816  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 13:54:46.818  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.818  1564  1564 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 13:54:46.820  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 13:54:46.826  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.826  1564  1564 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 13:54:46.826  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.826  1035  1528 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 13:54:46.826  1035  1528 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 13:54:46.828  1035  1528 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 13:54:46.828   314   893 E Netd    : netlink response contains error (File exists)
09-13 13:54:46.829  1035  1528 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 13:54:46.829  1564  1564 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:46.829  1564  1564 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 13:54:46.829  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.830  1035  1528 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 13:54:46.830  1035  1528 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 13:54:46.830  1035  1528 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 13:54:46.831  1035  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 13:54:46.832  1035  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 13:54:46.832  1035  1528 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-13 13:54:46.836  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.836  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 13:54:46.836  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 13:54:46.836  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 13:54:46.837  1035  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 13:54:46.837  1035  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 13:54:46.837  1035  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:46.837  1035  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 13:54:46.837  1035  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.837  1035  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 13:54:46.838  1035  1528 D ConnectivityService: currentScore = 0, newScore = 20
09-13 13:54:46.838  1035  1528 D ConnectivityService:    accepting network in place of null
09-13 13:54:46.838  1035  1528 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.839   314  8269 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 13:54:46.844  1035  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.845  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.845  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 13:54:46.845  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:46.845  1035  1528 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 13:54:46.845  1035  1528 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 13:54:46.845  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 13:54:46.849  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 13:54:46.849  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 13:54:46.849  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 13:54:46.849  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 13:54:46.850  1035  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:46.850  1035  1528 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,09-13 13:54:46.853  1035  1528 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 13:54:46.854  1035  1528 D ConnectivityService: validation of new default Network = false
09-13 13:54:46.854  1035  1528 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 13:54:46.854  1035  1528 D DSQN    : enableDataServiceNotify 
09-13 13:54:46.854  1035  1528 D DSQN    : start dsqn bin
09-13 13:54:46.861  1035  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 13:54:46.869  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.869  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:46.870  1035  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:46.846  8270  8270 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:46.846  8270  8270 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 13:54:46.870  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 13:54:46.874  1035  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 13:54:46.885  8270  8270 E DSQN    : DSQN ssw
09-13 13:54:46.885   314  8269 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 13:54:46.888  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:46.889  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.890  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.918   314  8269 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 13:54:46.943   314   892 D LGDataListener: argv[0]=dsqncommand
,09-13 13:54:46.943   314   892 D LGDataListener: argv[1]=wlan0
09-13 13:54:46.943   314   892 D LGDataListener: argv[2]=1
09-13 13:54:46.943   314   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 13:54:46.943  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 13:54:46.943  1035  1115 D DSQN    : start to monitor internet connection
,09-13 13:54:46.966  1035  8265 D DhcpStateMachine: DHCPV4 request on wlan0
,09-13 13:54:46.967  1035  8265 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 13:54:46.967  1035  8265 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-13 13:54:46.971  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 11:54:46 GMT], X-Android-Received-Millis=[1473767686970], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473767686943]}
09-13 13:54:46.971  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 13:54:46.972  1035  8264 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 13:54:46.972  1035  1528 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 13:54:46.972  1035  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 13:54:46.972  1035  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:46.972  1035  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:46.972  1035  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 13:54:46.972  1035  1528 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 13:54:46.973  1035  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 13:54:46.973  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.973  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:46.973  1035  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:46.973  1035  1528 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.974  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 13:54:46.956  8281  8281 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:46.956  8281  8281 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 13:54:46.975  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 13:54:46.975  1035  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.975  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:46.975  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 13:54:46.976  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 13:54:46.976  8244  8244 W ExternalStrings: load override strings
09-13 13:54:46.976  8244  8244 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-13 13:54:46.976  8244  8244 W ,ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:54:46.976  8244  8244 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 13:54:46.976  8281  8281 I dhcpcd  : version 5.5.6 starting
09-13 13:54:46.977  8281  8281 E dhcpcd  : get_duid: m
09-13 13:54:46.977  8281  8281 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 13:54:46.977  8281  8281 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 13:54:46.980  8244  8244 D StatusProvider: onCreate
,09-13 13:54:46.997  1564  1564 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 13:54:46.998  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:46.999  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 13:54:47.042  8281  8281 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 13:54:47.042  8281  8281 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-13 13:54:47.043  8281  8281 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 13:54:47.043  8281  8281 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 13:54:47.043  8281  8281 D dhcpcd  : wlan0: sending REQUEST (xid 0x21e53190), next in 4.66 seconds
09-13 13:54:47.060  8244  8244 V Signer  : override build config not found
09-13 13:54:47.060  8244  8244 D Signer  : value of property debug is false
,09-13 13:54:47.080  8281  8281 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 13:54:47.092  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-13 13:54:47.093  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,09-13 13:54:47.093  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-13 13:54:47.093  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-13 13:54:47.093  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-13 13:54:47.093  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,09-13 13:54:47.094  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-13 13:54:47.094  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-13 13:54:47.094  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,09-13 13:54:47.094  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-13 13:54:47.094  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-13 13:54:47.095  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-13 13:54:47.095  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-13 13:54:47.103  8244  8244 V LGMDMManager: Create singleton instance,
,09-13 13:54:47.114  8281  8281 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-13 13:54:47.114  8281  8281 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 13:54:47.115  8281  8281 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 13:54:47.115  8281  8281 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 13:54:47.116  8281  8281 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-13 13:54:47.116  8281  8281 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 13:54:47.117  8281  8281 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 13:54:47.117  8281  8281 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-13 13:54:47.144  8244  8244 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-13 13:54:47.226  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.228  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 13:54:47.240  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.244  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.280  1035  1962 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8308 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-13 13:54:47.280  1035  1962 I ActivityManager: Killing 7266:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-13 13:54:47.362  8244  8297 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 13:54:47.370  1035  8265 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 13:54:47.372  1035  8265 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 13:54:47.373  1035  8265 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 13:54:47.373  1035  8265 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 13:54:47.373  1035  8265 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 13:54:47.373  1035  8265 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 13:54:47.373  1035  8265 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 13:54:47.374  1035  8265 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 13:54:47.375  1035  8265 D DhcpStateMachine: RunningState
,09-13 13:54:47.379  1035  1907 W libprocessgroup: failed to open /acct/uid_10085/pid_7266/cgroup.procs: No such file or directory
09-13 13:54:47.431  8308  8308 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 13:54:47.457  8308  8308 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-13 13:54:47.517  8308  8308 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-13 13:54:47.518  8308  8308 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 13:54:47.518  8308  8308 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 13:54:47.518  8308  8308 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 13:54:47.519  8308  8308 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 13:54:47.522  8308  8308 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 13:54:47.528  8308  8308 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 13:54:47.534  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 13:54:47.539  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.546  8244  8297 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:47.547  8244  8297 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:47.559  8308  8308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:47.562  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.563  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 13:54:47.563  8308  8308 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-13 13:54:47.567  8308  8308 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 13:54:47.571  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:47.577  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 13:54:47.584  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.585  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.587  8308  8308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 13:54:47.589  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-13 13:54:47.593  6935  6935 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 13:54:47.596  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.597  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.603  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.616  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.623  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.624  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.625  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:47.628  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 13:54:47.628  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-13 13:54:47.628  6935  6935 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 13:54:47.628  6935  6935 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 13:54:47.629  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 13:54:47.630  6935  6935 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 13:54:47.630  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,09-13 13:54:47.630  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 13:54:47.630  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 13:54:47.630  6935  6935 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 13:54:47.630  6935  6935 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 13:54:47.630  6935  6935 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 13:54:47.635  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.634  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.644  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.656  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.663  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.664  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:47.665  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:47.668  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.668  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.673  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.682  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.689  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.689  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.690  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 13:54:47.694  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.695  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.704  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.714  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 13:54:47.715  8244  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-13 13:54:47.724  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.724  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.725  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 13:54:47.729  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.729  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.738  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 13:54:47.739  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-13 13:54:47.748  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.751  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-13 13:54:47.751  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 13:54:47.752  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,09-13 13:54:47.753  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-13 13:54:47.754  8244  8297 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-13 13:54:47.758  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-13 13:54:47.760  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.760  8244  8297 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-13 13:54:47.761  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.761  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 13:54:47.774  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.774  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.789  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.800  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.809  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 13:54:47.810  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 13:54:47.823  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 13:54:47.829  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.829  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.840  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.852  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.860  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.860  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:47.861  8308  8308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 13:54:47.867  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.869  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 13:54:47.873  8199  8199 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 13:54:47.879  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 13:54:47.884  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.895  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.903  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.903  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:47.905  8308  8308 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-13 13:54:47.906  8308  8308 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 13:54:47.906  8308  8308 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 13:54:47.912  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:47.955  8199  8199 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 13:54:47.956  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 13:54:47.962  6935  6935 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 13:54:47.969  6935  6935 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 13:54:47.980  8308  8308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 13:54:47.981  8308  8308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 13:54:47.983  8308  8308 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 13:54:47.985  8308  8308 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 13:54:47.986  8308  8308 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 13:54:47.992  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.001  8308  8308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 13:54:48.002  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 13:54:48.002  8308  8308 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-13 13:54:48.053  8308  8308 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 13:54:48.053  8308  8308 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:48.062  8308  8308 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 13:54:48.063  8308  8308 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 13:54:48.063  8308  8308 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 13:54:48.063  8308  8308 V SoundPool: doLoad: loading sample sampleID=1
09-13 13:54:48.064  8308  8308 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 13:54:48.075  7715  7715 D UEI.SmartControl: QS Service created
09-13 13:54:48.076  8308  8353 V SoundPool: Start decode
,09-13 13:54:48.076  8308  8353 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 13:54:48.079   319  2171 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 13:54:48.079   319  2171 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,09-13 13:54:48.079   319  2171 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 13:54:48.079   319  2171 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 13:54:48.079   319  2171 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 13:54:48.079   319  2171 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 13:54:48.079   319  2171 V MediaPlayerService: player type = 3
09-13 13:54:48.079   319  2171 V AwesomePlayer: AwesomePlayer create()
09-13 13:54:48.080   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:48.080   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:48.080   319  2171 V AwesomePlayer: setAudioSink() 
09-13 13:54:48.080   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:48.080   319  2171 V AudioCache: notify(0xb5474900, 8, 0, 0)
09-13 13:54:48.080   319  2171 V AudioCache: ignored
09-13 13:54:48.080   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:48.080   319  2171 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 13:54:48.080   319  2171 V AwesomePlayer: setDataSource_l dataSource
09-13 13:54:48.080   319  2171 V LGParserOSAL: SniffLGParser start
09-13 13:54:48.080   319  2171 V LGParserOSAL: MainType:5, SubType=0
09-13 13:54:48.080   319  2171 V LGParserOSAL: #### check Mime : application/ogg
09-13 13:54:48.080   319  2171 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 13:54:48.080   319  2171 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 13:54:48.085  8308  8308 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 13:54:48.091  8308  8308 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 13:54:48.092  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-13 13:54:48.104  7715  7715 I UEI.SmartControl: Service initServices...
,09-13 13:54:48.104  7715  7715 D UEI.SmartControl: QS start get config
09-13 13:54:48.119   319  2171 V LGParserOSAL: supported mime: application/ogg
09-13 13:54:48.119   319  2171 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 13:54:48.119   319  2171 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 13:54:48.119   319  2171 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 13:54:48.119   319  2171 V AwesomePlayer: AudioTrack Setting
09-13 13:54:48.119   319  2171 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 13:54:48.119   319  2171 V AwesomePlayer: setAudioSource() 
09-13 13:54:48.119   319  2171 V MediaPlayerService: prepare
09-13 13:54:48.120   319  2171 V AwesomePlayer: prepareAsync_l() 
09-13 13:54:48.120   319  2171 V MediaPlayerService: wait for prepare
09-13 13:54:48.120   319  8354 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 13:54:48.120   319  8354 V AwesomePlayer: initAudioDecoder() 
09-13 13:54:48.120   319  8354 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 13:54:48.120   319  8354 V AudioSystem: isOffloadSupported()
09-13 13:54:48.120   319  8354 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 13:54:48.120   319  8354 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 13:54:48.120   319  8354 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 13:54:48.120   319  8354 V AwesomePlayer: getUseOffload() = 0 
09-13 13:54:48.120   319  8354 V OMXCodec: OMXCodec::Create
09-13 13:54:48.120   319  8354 V OMXCodec: findMatchingCodecs()
09-13 13:54:48.120   319  8354 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 13:54:48.120   319  8354 V OMXCodec: matchingCodecs.size()=1
09-13 13:54:48.120   319  8354 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 13:54:48.122   319  8354 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,09-13 13:54:48.122   319  8354 V LGCodecAdapter: LG Codec Adapter start
09-13 13:54:48.122   319  8354 V OMXCodec: OMXCodec Createtor
09-13 13:54:48.122   319  8354 V OMXCodec: setComponentRole
09-13 13:54:48.122   319  8354 V OMXCodec: configureCodec protected=0
09-13 13:54:48.122   319  8354 V LGCodecAdapter: called getLGCodecSpecificData
09-13 13:54:48.122   319  8354 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 13:54:48.122   319  8354 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 13:54:48.123   319  8354 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 13:54:48.123   319  8354 V LGCodecOSAL: Not support LGCodec
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 13:54:48.123  8308  8308 V LGMDMManager: Create singleton instance
09-13 13:54:48.123   319  8354 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 13:54:48.123   319  8354 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 13:54:48.123   319  8354 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 13:54:48.123   319  8354 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 13:54:48.123   319  8354 V AudioSystem: isOffloadSupported()
09-13 13:54:48.123   319  8354 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 13:54:48.123   319  8354 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 13:54:48.123   319  8354 V OMXCodec: init()
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 13:54:48.123   319  8354 V OMXCodec: allocateBuffers
09-13 13:54:48.123   319  8354 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010470 on input port
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010600 on input port
09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010650 on input port
,09-13 13:54:48.123   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010740 on input port
09-13 13:54:48.124   319  8354 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 13:54:48.124   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 13:54:48.124   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010790 on output port
,09-13 13:54:48.124   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010a10 on output port
09-13 13:54:48.124   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010b50 on output port
09-13 13:54:48.124   319  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010c90 on output port
09-13 13:54:48.124   319  8354 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 13:54:48.124   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,09-13 13:54:48.124   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 13:54:48.124   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 13:54:48.124   319  8354 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 13:54:48.125   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 13:54:48.125   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 13:54:48.125   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 13:54:48.125   319  8354 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 13:54:48.125   319  8354 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 13:54:48.125   319  8354 V AudioCache: notify(0xb5474900, 5, 0, 0)
09-13 13:54:48.125   319  8354 V AudioCache: ignored
09-13 13:54:48.125   319  8354 V AudioCache: notify(0xb5474900, 1, 0, 0)
09-13 13:54:48.125   319  8354 V AudioCache: prepared
09-13 13:54:48.125   319  2171 V AudioCache: wait - success
09-13 13:54:48.125   319  2171 V MediaPlayerService: start
09-13 13:54:48.125   319  2171 V AwesomePlayer: play_l() 
09-13 13:54:48.125   319  2171 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 13:54:48.125   319  2171 V AwesomePlayer: createAudioPlayer_l
09-13 13:54:48.125   319  2171 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 13:54:48.125   319  2171 V AwesomePlayer: startAudioPlayer_l() 
09-13 13:54:48.125   319  2171 D AudioPlayer: start of Playback, useOffload 0
09-13 13:54:48.125   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 13:54:48.125   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969634704
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969635344
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969635664
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969635984
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 13:54:48.127   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 13:54:48.128   319  8356 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 13:54:48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 13:54:48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010b50 on output port
09-13 13:54:,48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010a10 on output port
09-13 13:54:48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010790 on output port
09-13 13:54:48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1010e70 on output port
09-13 13:54:48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 13:54:48.128   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 13:54:48.129   319  2171 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 13:54:48.129   319  2171 V AudioCache: notify(0xb5474900, 6, 0, 0)
09-13 13:54:48.129   319  2171 V AudioCache: ignored
09-13 13:54:48.129   319  2171 V MediaPlayerService: wait for playback complete
09-13 13:54:48.129   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.129   319  8357 V AudioCache: memcpy(0xabe08000, 0xb16dc000, 4096)
09-13 13:54:48.130   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.130   319  8357 V AudioCache: memcpy(0xabe09000, 0xb16dc000, 4096)
09-13 13:54:48.131   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.131   319  8357 V AudioCache: memcpy(0xabe0a000, 0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: memcpy(0xabe0b000, 0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: memcpy(0xabe0c000, 0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: memcpy(0xabe0d000, 0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.132   319  8357 V AudioCache: memcpy(0xabe0e000, 0xb16dc000, 4096)
09-13 13:54:48.134   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.134   319  8357 V AudioCache: memcpy(0xabe0f000, 0xb16dc000, 4096)
09-13 13:54:48.135   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.135   319  8357 V AudioCache: memcpy(0xabe10000, 0xb16dc000, 4096)
09-13 13:54:48.136   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.136   319  8357 V AudioCache: memcpy(0xabe11000, 0xb16dc000, 4096)
09-13 13:54:48.136   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.136   319  8357 V AudioCache: memcpy(0xabe12000, 0xb16dc000, 4096)
09-13 13:54:48.137   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.137   319  8357 V AudioCache: memcpy(0xabe13000, 0xb16dc000, 4096)
09-13 13:54:48.137   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.137   319  8357 V AudioCache: memcpy(0xabe14000, 0xb16dc000, 4096)
09-13 13:54:48.138   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.138   319  8357 V AudioCache: memcpy(0xabe15000, 0xb16dc000, 4096)
09-13 13:54:48.138   319  8357 V AudioCache: write(0xb16dc000, 4096)
,09-13 13:54:48.138   319  8357 V AudioCache: memcpy(0xabe16000, 0xb16dc000, 4096)
09-13 13:54:48.139   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.139   319  8357 V AudioCache: memcpy(0xabe17000, 0xb16dc000, 4096)
09-13 13:54:48.139   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.139   319  8357 V AudioCache: memcpy(0xabe18000, 0xb16dc000, 4096)
09-13 13:54:48.140   319  8357 V AudioCache: write(0xb16dc000, 4096)
,09-13 13:54:48.140   319  8357 V AudioCache: memcpy(0xabe19000, 0xb16dc000, 4096)
09-13 13:54:48.140   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.140   319  8357 V AudioCache: memcpy(0xabe1a000, 0xb16dc000, 4096)
,09-13 13:54:48.148   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.149   319  8357 V AudioCache: memcpy(0xabe1b000, 0xb16dc000, 4096)
09-13 13:54:48.151   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.151   319  8357 V AudioCache: memcpy(0xabe1c000, 0xb16dc000, 4096)
09-13 13:54:48.151   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.151   319  8357 V AudioCache: memcpy(0xabe1d000, 0xb16dc000, 4096)
09-13 13:54:48.152   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.152   319  8357 V AudioCache: memcpy(0xabe1e000, 0xb16dc000, 4096)
09-13 13:54:48.152   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.152   319  8357 V AudioCache: memcpy(0xabe1f000, 0xb16dc000, 4096)
09-13 13:54:48.153   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.153   319  8357 V AudioCache: memcpy(0xabe20000, 0xb16dc000, 4096)
09-13 13:54:48.153   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.153   319  8357 V AudioCache: memcpy(0xabe21000, 0xb16dc000, 4096)
09-13 13:54:48.154   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.154   319  8357 V AudioCache: memcpy(0xabe22000, 0xb16dc000, 4096)
09-13 13:54:48.154   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.155   319  8357 V AudioCache: memcpy(0xabe23000, 0xb16dc000, 4096)
,09-13 13:54:48.155   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.155   319  8357 V AudioCache: memcpy(0xabe24000, 0xb16dc000, 4096)
09-13 13:54:48.156   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.156   319  8357 V AudioCache: memcpy(0xabe25000, 0xb16dc000, 4096)
09-13 13:54:48.156   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.156   319  8357 V AudioCache: memcpy(0xabe26000, 0xb16dc000, 4096)
09-13 13:54:48.157   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.157   319  8357 V AudioCache: memcpy(0xabe27000, 0xb16dc000, 4096)
09-13 13:54:48.157   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.157   319  8357 V AudioCache: memcpy(0xabe28000, 0xb16dc000, 4096)
09-13 13:54:48.158   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.158   319  8357 V AudioCache: memcpy(0xabe29000, 0xb16dc000, 4096)
09-13 13:54:48.158   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.158   319  8357 V AudioCache: memcpy(0xabe2a000, 0xb16dc000, 4096)
09-13 13:54:48.159   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.159   319  8357 V AudioCache: memcpy(0xabe2b000, 0xb16dc000, 4096)
09-13 13:54:48.159   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.159   319  8357 V AudioCache: memcpy(0xabe2c000, 0xb16dc000, 4096)
09-13 13:54:48.160   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.160   319  8357 V AudioCache: memcpy(0xabe2d000, 0xb16dc000, 4096)
09-13 13:54:48.161   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.161   319  8357 V AudioCache: memcpy(0xabe2e000, 0xb16dc000, 4096)
09-13 13:54:48.163   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.163   319  8357 V AudioCache: memcpy(0xabe2f000, 0xb16dc000, 4096)
09-13 13:54:48.164   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.164   319  8357 V AudioCache: memcpy(0xabe30000, 0xb16dc000, 4096)
09-13 13:54:48.164   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.164   319  8357 V AudioCache: memcpy(0xabe31000, 0xb16dc000, 4096)
09-13 13:54:48.165   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.165   319  8357 V AudioCache: memcpy(0xabe32000, 0xb16dc000, 4096)
09-13 13:54:48.165   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.165   319  8357 V AudioCache: memcpy(0xabe33000, 0xb16dc000, 4096)
09-13 13:54:48.166   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.166   319  8357 V AudioCache: memcpy(0xabe34000, 0xb16dc000, 4096)
09-13 13:54:48.166   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.166   319  8357 V AudioCache: memcpy(0xabe35000, 0xb16dc000, 4096)
09-13 13:54:48.167   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.167   319  8357 V AudioCache: memcpy(0xabe36000, 0xb16dc000, 4096)
09-13 13:54:48.167   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.167   319  8357 V AudioCache: memcpy(0xabe37000, 0xb16dc000, 4096)
09-13 13:54:48.168   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.168   319  8357 V AudioCache: memcpy(0xabe38000, 0xb16dc000, 4096)
09-13 13:54:48.168   319  8357 V AudioCache: write(0xb16dc000, 4096)
09-13 13:54:48.168   319  8357 V AudioCache: memcpy(0xabe39000, 0xb16dc000, 4096)
,09-13 13:54:48.168   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,09-13 13:54:48.168   319  8357 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,09-13 13:54:48.168   319  8357 V AwesomePlayer: postAudioEOS() 
09-13 13:54:48.168   319  8357 V AudioCache: write(0xb16dc000, 280)
09-13 13:54:48.168   319  8357 V AudioCache: memcpy(0xabe3a000, 0xb16dc000, 280)
09-13 13:54:48.174   319  8354 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 13:54:48.174   319  8354 V AwesomePlayer: onStreamDone
09-13 13:54:48.174   319  8354 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 13:54:48.174   319  8354 V AudioCache: notify(0xb5474900, 2, 0, 0)
09-13 13:54:48.174   319  8354 V AudioCache: playback complete
09-13 13:54:48.174   319  8354 V AwesomePlayer: pause_l() 
09-13 13:54:48.174   319  8354 V AudioCache: notify(0xb5474900, 7, 0, 0)
09-13 13:54:48.174   319  8354 V AudioCache: ignored
09-13 13:54:48.174   319  8354 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:48.174   319  2171 V AudioCache: wait - success
09-13 13:54:48.174   319  2171 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 13:54:48.174   319  8354 D AudioPlayer: Pause Playback at 1068125
09-13 13:54:48.175   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:48.175   319  2171 V AudioCache: notify(0xb5474900, 8, 0, 0)
09-13 13:54:48.175   319  2171 V AudioCache: ignored
09-13 13:54:48.175   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:48.175   319  2171 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 13:54:48.175   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 13:54:48.175   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 13:54:48.175   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 13:54:48.175   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 13:54:48.175   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 13:54:48.175   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010740 on port 0
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010650 on port 0
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010600 on port 0
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010470 on port 0
09-13 13:54:48.176   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010e70 on port 1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010790 on port 1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010a10 on port 1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1010b50 on port 1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 13:54:48.177   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 13:54:48.177   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 13:54:48.177   319  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 13:54:48.177   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 13:54:48.177   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 13:54:48.177   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 13:54:48.178   319  2171 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 13:54:48.178   319  2171 D AudioPlayer: AudioPlayer releasing audio source
09-13 13:54:48.178   319  2171 D AudioPlayer: AudioPlayer done releasing audio source
09-13 13:54:48.178   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:48.178   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:48.178   319  2171 V AwesomePlayer: ~AwesomePlayer call
09-13 13:54:48.179   319  2171 V AwesomePlayer: reset_l() 
09-13 13:54:48.179   319  2171 V AwesomePlayer: cancelPlayerEvents
09-13 13:54:48.179  8308  8353 V SoundPool: close(31)
09-13 13:54:48.179  8308  8353 V SoundPool: pointer = 0x9fe54000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 13:54:48.192  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 13:54:48.193  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 13:54:48.198  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4782
,09-13 13:54:48.201  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.204  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.206  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.208  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.210  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 13:54:48.212  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.214  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.216  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.218  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 13:54:48.266  1035  1521 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 13:54:48.268  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:48.270  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:48.271  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:48.272  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:48.274  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 13:54:48.275  1035  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 13:54:48.275  1035  1528 D ConnectivityService: identical MTU - not setting
09-13 13:54:48.275  1035  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 13:54:48.276  1035  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 13:54:48.276  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 13:54:48.276  1035  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:48.278  1035  1528 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 13:54:48.279  1564  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-13 13:54:48.472  7715  7715 I UEI.SmartControl: Supports setup maps: true
,09-13 13:54:48.478  7715  7715 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 13:54:48.478  7715  7715 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 13:54:48.478  7715  7715 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 13:54:48.478  7715  7715 I UEI.SmartControl: ### init IR Blaster...
09-13 13:54:48.483  7715  7715 D serial_port: Configuring serial port
09-13 13:54:48.484  7715  7715 E UEI.SmartControl: UEIBLaster setting for 616
09-13 13:54:48.484  7715  7715 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 13:54:48.484  7715  7715 I UEI.SmartControl: configuring settings for MAXQ616
09-13 13:54:48.484  7715  7715 I UEI.SmartControl: Get version...
09-13 13:54:48.501  7715  8366 D UEI.SmartControl: serial port data available: 21
,09-13 13:54:48.527  7715  7715 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 13:54:48.530  7715  7715 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 13:54:48.530  7715  7715 I UEI.SmartControl: QS saving settings...
09-13 13:54:48.532  7715  7715 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 13:54:48.551  7715  8366 D UEI.SmartControl: serial port data available: 4
,09-13 13:54:48.588  7715  7715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 13:54:48.606  7715  7715 E UEI.SmartControl: Services init done
09-13 13:54:48.606  7715  7715 D UEI.SmartControl: QS Service init finished
,09-13 13:54:48.609  7715  7715 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 13:54:48.609  7715  7715 D UEI.SmartControl: QS Service version code: 201091
09-13 13:54:48.610  7715  7715 D UEI.SmartControl: Service requested: Control
09-13 13:54:48.613  8308  8308 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 13:54:48.614  7715  7730 I UEI.SmartControl: ------ IControl API: 11
09-13 13:54:48.614  7715  7730 D UEI.SmartControl: File observer start...
09-13 13:54:48.615  7715  7730 E UEI.SmartControl: IR Port is disabled: false
09-13 13:54:48.615  7715  7730 D UEI.SmartControl: Starting file observer...
09-13 13:54:48.615  7715  7730 I UEI.SmartControl: Registering callback...
09-13 13:54:48.615  7715  7731 I UEI.SmartControl: ------ IControl API: 19
09-13 13:54:48.616  7715  7731 I UEI.SmartControl: Registering Services Ready callback...
09-13 13:54:48.617  7715  7715 D UEI.SmartControl: Internal service binding...
09-13 13:54:48.617  7715  8375 I UEI.SmartControl: Device manager: loading config....
09-13 13:54:48.617  7715  8375 D UEI.SmartControl: ----------- loading internal config...
09-13 13:54:48.622  7715  8375 E UEI.SmartControl: Loading SETTINGS...
,09-13 13:54:48.631  7715  8375 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 13:54:48.647  7715  8374 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 13:54:48.651  8308  8323 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 13:54:48.651  8308  8351 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 13:54:48.652  8308  8351 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 13:54:48.652  8308  8308 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 13:54:48.652  8308  8308 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 13:54:48.653  7715  7730 I UEI.SmartControl: ------ IControl API: 8
09-13 13:54:48.654  7715  8374 D UEI.SmartControl: -----service ready thread exits
09-13 13:54:48.656  8308  8308 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 13:54:48.656  8308  8308 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 13:54:48.656  8308  8308 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 13:54:48.656  8308  8308 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 13:54:48.657  8308  8308 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 13:54:48.658  8308  8308 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 13:54:48.661  8308  8308 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-13 13:54:48.667  8308  8308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 13:54:48.668  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 13:54:48.669  8308  8308 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 13:54:48.669  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 13:54:48.670  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 13:54:48.671  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 13:54:48.671  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 13:54:48.672  8308  8308 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473767688672]
09-13 13:54:48.676  8308  8308 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-13 13:54:48.683  1035  1617 I ActivityManager: Killing 7285:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-13 13:54:48.732  8308  8377 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 13:54:48.765  1035  1943 W libprocessgroup: failed to open /acct/uid_10093/pid_7285/cgroup.procs: No such file or directory
,09-13 13:54:48.776  8308  8308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-13 13:54:48.777  8308  8308 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 13:54:48.778  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,09-13 13:54:48.779  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 13:54:48.780  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-13 13:54:48.780  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 13:54:48.781  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 13:54:48.800  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 13:54:49.760  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=79.5, 0.0, 0.0  rx=83.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:593907232] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 13:54:49.763  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=79.5, 0.0, 0.0  rx=83.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593907235] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:49.764  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:54:49.791  1564  1564 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 13:54:49.805  1035  1523 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 13:54:49.853  1035  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:49.871  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:49.884  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:54:49.888  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:49.896  6786  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:54:49.901  6786  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:49.905  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:49.907  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 13:54:49.912  8244  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 13:54:49.925  5814  5814 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 13:54:49.943  2125  2125 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:54:49.957  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 13:54:49.957  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:49.957  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 13:54:49.957  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 13:54:49.963  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
09-13 13:54:49.967  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:54:49.967  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:54:49.967  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:54:49.967  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:54:49.967  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 13:54:49.972  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:49.972  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 13:54:49.973  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 13:54:49.979  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 13:54:49.985  2830  2830 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:50.000  2830  2830 V DownloadManager: DownloadService onCreate
,09-13 13:54:50.005  4291  8409 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 13:54:50.010  4291  8409 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 13:54:50.014  4291  8410 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:50.014  4291  8410 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 13:54:50.015   314  8414 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 13:54:50.015   314  8414 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 13:54:50.016  2830  8407 I DownloadManager: in removeSpuriousFiles
09-13 13:54:50.016  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 13:54:50.016  2830  8407 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 13:54:50.019  2830  8407 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@36f04366 on behalf of 2830
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 13:54:50.020  2830  8407 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 13:54:50.022  2830  8407 I DownloadManager: in trimDatabase
09-13 13:54:50.022  2830  8407 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 13:54:50.022  2830  8407 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@177f1754 on behalf of 2830
09-13 13:54:50.027  1035  2036 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8416 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-13 13:54:50.029  2830  2830 V DownloadManager: DownloadService onStartCommand
,09-13 13:54:50.031  4291  8409 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 13:54:50.032  2830  8408 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 13:54:50.033  2830  8408 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@162d2ff2 on behalf of 2830
09-13 13:54:50.034  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 13:54:50.035  2830  8408 V DownloadManager: processing inserted download 1
09-13 13:54:50.036  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 13:54:50.036  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 13:54:50.036  2830  8408 V DownloadManager: processing inserted download 4
09-13 13:54:50.037  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 13:54:50.039  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 13:54:50.042  2830  8408 V DownloadManager: processing inserted download 7
,09-13 13:54:50.043  2830  8408 V DownloadManager: processing inserted download 8
09-13 13:54:50.046  2830  8408 V DownloadManager: processing inserted download 9
09-13 13:54:50.047  2830  8408 V DownloadManager: processing inserted download 10
09-13 13:54:50.048  2830  8408 V DownloadManager: processing inserted download 11
09-13 13:54:50.049  2830  8408 V DownloadManager: processing inserted download 12
09-13 13:54:50.050  2830  8408 V DownloadManager: processing inserted download 13
09-13 13:54:50.051  2830  8408 V DownloadManager: processing inserted download 14
09-13 13:54:50.052  2830  8408 V DownloadManager: processing inserted download 16
09-13 13:54:50.055   314  8414 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-13 13:54:50.060  2830  2830 V DownloadManager: DownloadService onDestroy
,09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:54:50.071  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:54:50.072  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:54:50.072  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:54:50.072  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3cee70 removed from the list
09-13 13:54:50.072  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:54:50.072  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:54:50.072  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:54:50.076  6786  8435 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 13:54:50.076  6786  8435 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 13:54:50.077  8416  8416 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:54:50.077  8416  8416 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:54:50.078  8416  8416 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 13:54:50.079  8416  8416 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 13:54:50.134  8416  8416 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 13:54:50.142  8416  8416 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 13:54:50.178  8416  8416 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 13:54:50.218  8416  8416 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 13:54:50.219  8416  8416 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:50.309  2125  8439 D GCM     : Connected
,09-13 13:54:50.338  2125  8439 D GCM     : Message class com.google.e.a.a.q
,09-13 13:54:50.381  8416  8416 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 13:54:50.433  8416  8416 I HubEmail: JNI_OnLoad()
09-13 13:54:50.433  8416  8416 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 13:54:50.433  8416  8416 I HubEmail: registerNatives()
09-13 13:54:50.433  8416  8416 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 13:54:50.433  8416  8416 I HubEmail: registerNativeMethods()
09-13 13:54:50.433  8416  8416 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 13:54:50.435  8416  8416 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-13 13:54:50.444  8416  8449 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 13:54:50.452  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 13:54:50.452  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 13:54:50.452  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 13:54:50.452  3423  3423 D PhoneState: setPdpRejectCasuse : false
,09-13 13:54:50.471   314  8452 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 13:54:50.471   314  8452 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-13 13:54:50.495  1035  1962 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8453 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-13 13:54:50.513   314  8452 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-13 13:54:50.554  8176  8448 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 13:54:50.561  8176  8448 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-13 13:54:50.592  1035  1980 I ActivityManager: Killing 7780:com.google.android.talk/u0a72 (adj 15): empty #17
,09-13 13:54:50.643  8453  8453 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:50.644  8453  8453 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:50.648  8453  8453 D PhoneMonitor: Register our PhoneStateListener
09-13 13:54:50.656  1035  2036 W libprocessgroup: failed to open /acct/uid_10072/pid_7780/cgroup.procs: No such file or directory
,09-13 13:54:50.678  8453  8453 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 13:54:50.682  8453  8453 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 13:54:50.703  8453  8453 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-13 13:54:50.704  8453  8453 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 13:54:50.706  8453  8453 D TelephonyAutoProfiling: [parse] Load xml
09-13 13:54:50.712  8453  8453 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 13:54:50.712  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 13:54:50.713  8453  8453 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 13:54:50.714  8453  8453 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-13 13:54:50.722  8453  8453 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-13 13:54:50.743  1035  1944 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8472 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 13:54:50.745  1035  1944 I ActivityManager: Killing 7831:com.android.contacts/u0a19 (adj 15): empty #17
,09-13 13:54:50.805  1035  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_7831/cgroup.procs: No such file or directory
,09-13 13:54:50.833  1802  8489 I CheckinService: active receiver: enabled
,09-13 13:54:50.847  1802  8489 I CheckinService: Preparing to send checkin request
09-13 13:54:50.847  1802  8489 I EventLogService: Accumulating logs since 1473767651843
09-13 13:54:50.915  1802  8489 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 13:54:51.027   314  8492 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 13:54:51.027   314  8492 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-13 13:54:51.069   314  8492 D libc-netbsd: res_queryN name = www.google.com succeed
,09-13 13:54:51.074   314  8495 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 13:54:51.074   314  8495 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 13:54:51.075   314  8495 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 13:54:51.082  1035  1944 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8493 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-13 13:54:51.123  1035  1524 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-13 13:54:51.138  1035  1618 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8512 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 13:54:51.143  1035  1618 I ActivityManager: Killing 7855:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-13 13:54:51.212  1035  1906 W libprocessgroup: failed to open /acct/uid_10027/pid_7855/cgroup.procs: No such file or directory
09-13 13:54:51.239  8493  8493 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 13:54:51.239  8493  8493 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 13:54:51.276  8493  8493 I MultiDex: VM with version 2.1.0 has multidex support
09-13 13:54:51.276  8493  8493 I MultiDex: install
09-13 13:54:51.277  8493  8493 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 13:54:51.341  1035  2017 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8530 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 13:54:51.345  1035  2017 I ActivityManager: Killing 7874:com.android.vending/u0a44 (adj 15): empty #17
09-13 13:54:51.371   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 28.135ms
,09-13 13:54:51.394   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 21.492ms
,09-13 13:54:51.417   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 521us total 22.366ms
,09-13 13:54:51.467  1035  1998 W libprocessgroup: failed to open /acct/uid_10044/pid_7874/cgroup.procs: No such file or directory
,09-13 13:54:51.478  8493  8493 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 13:54:51.503  8530  8530 I art     : Almond Protected OAT
,09-13 13:54:51.566  8530  8530 D WeatherApplication: removeAccount
,09-13 13:54:51.568  8530  8530 D WeatherApplication: Account.length = 0
09-13 13:54:51.568  8530  8530 E WeatherApplication: OPERATOR:OPEN
09-13 13:54:51.573  8530  8530 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:51
09-13 13:54:51.579  8530  8530 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 13:54:51.579  8530  8530 D Weather.Utils: 2 : All the weather widget is gone.
,09-13 13:54:51.581  8530  8530 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 13:54:51.583  8530  8530 D WeatherAncestor: connectivity changed - connection : true
09-13 13:54:51.592  8530  8530 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 13:54:51.608  8530  8530 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 13:54:51.608  8530  8530 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 13:54:51.608  8530  8530 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-13 13:54:51.648  8530  8530 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 13:54:51.648  8530  8530 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:54:51
,09-13 13:54:51.677  1035  1521 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,09-13 13:54:51.677  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
09-13 13:54:51.677  1035  1521 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
09-13 13:54:51.677  1035  1521 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
09-13 13:54:51.678  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
09-13 13:54:51.678  1035  1521 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
09-13 13:54:51.720  1035  2017 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8550 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 13:54:51.721  1035  2017 I ActivityManager: Killing 7916:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-13 13:54:51.827  8493  8510 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:54:51.827  8493  8510 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:54:51.846  1035  1558 W libprocessgroup: failed to open /acct/uid_10080/pid_7916/cgroup.procs: No such file or directory
,09-13 13:54:51.967   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:51.967   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 13:54:51.967   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 13:54:51.968  8550  8568 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 13:54:51.969   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:51.969   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 13:54:51.969   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 13:54:51.973  8550  8568 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 13:54:51.988   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:51.988   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 13:54:51.988   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 13:54:51.991  8550  8570 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 13:54:51.993   280   357 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 13:54:51.993   280   357 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 13:54:51.994   280   357 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 13:54:51.994  8550  8570 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 13:54:52.039  8574  8574 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 13:54:52.079  8574  8574 I dex2oat : dex2oat took 40.833ms (threads: 4)
,09-13 13:54:52.095  8493  8510 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:52.095  8493  8510 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:52.095  8493  8510 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:52.095  8493  8510 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:52.095  8493  8510 I Adreno-EGL: Remote Branch: 
09-13 13:54:52.095  8493  8510 I Adreno-EGL: Local Patches: 
09-13 13:54:52.095  8493  8510 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:52.220  8493  8510 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:52.220  8493  8510 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:52.220  8493  8510 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:52.220  8493  8510 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:52.220  8493  8510 I Adreno-EGL: Remote Branch: 
09-13 13:54:52.220  8493  8510 I Adreno-EGL: Local Patches: 
09-13 13:54:52.220  8493  8510 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:52.227  8550  8550 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 13:54:52.310  1035  1906 I art     : Explicit concurrent mark sweep GC freed 81229(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.198ms total 146.278ms
,09-13 13:54:52.317  8550  8550 I LibraryLoader: Loading: webviewchromium
09-13 13:54:52.319  8550  8550 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2752-2755)
09-13 13:54:52.320  8550  8550 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:54:52.325  8550  8550 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cb3488c}
09-13 13:54:52.326  8550  8550 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:54:52.326  8550  8550 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 13:54:52.334  8550  8550 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 13:54:52.335  8550  8550 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 13:54:52.346  8550  8550 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 13:54:52.347  8550  8550 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 13:54:52.348  8550  8550 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-13 13:54:52.353   319  2171 V AudioPolicyService: registerClient() client 0xb57f81a0, uid 10093
09-13 13:54:52.354  8550  8604 W AudioManagerAndroid: Requires BLUETOOTH permission
09-13 13:54:52.362  8550  8550 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:52.362  8550  8550 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:52.362  8550  8550 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:52.362  8550  8550 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:52.362  8550  8550 I Adreno-EGL: Remote Branch: 
09-13 13:54:52.362  8550  8550 I Adreno-EGL: Local Patches: 
09-13 13:54:52.362  8550  8550 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:52.429  8493  8510 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 13:54:52.429  8493  8510 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 13:54:52.429  8493  8510 I Adreno-EGL: Build Date: 12/12/14 금
09-13 13:54:52.429  8493  8510 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 13:54:52.429  8493  8510 I Adreno-EGL: Remote Branch: 
09-13 13:54:52.429  8493  8510 I Adreno-EGL: Local Patches: 
09-13 13:54:52.429  8493  8510 I Adreno-EGL: Reconstruct Branch: 
,09-13 13:54:52.436  8550  8550 I NSApplication: Starting up...
09-13 13:54:52.472  1035  1925 I ActivityManager: Killing 7621:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-13 13:54:52.532  1035  1907 W libprocessgroup: failed to open /acct/uid_10037/pid_7621/cgroup.procs: No such file or directory
,09-13 13:54:52.571   314  8619 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 13:54:52.571   314  8619 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,09-13 13:54:52.574  2125  2125 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-13 13:54:52.589  2125  2125 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-13 13:54:52.590  2125  2125 D c       : Getting all permits...
09-13 13:54:52.590  2125  2125 D a       : Opening database...
,09-13 13:54:52.598  2125  2125 D a       : Opening database auth.proximity.permit_store...
09-13 13:54:52.599  2125  2125 D a       : Closing database...
09-13 13:54:52.608   314  8619 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-13 13:54:52.745  1802  8489 I CheckinTask: Sending checkin request (7835 bytes)
,09-13 13:54:52.790  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=44.8, 0.0, 0.0  rx=44.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:593910262] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 13:54:52.794  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=44.8, 0.0, 0.0  rx=44.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:593910266] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 13:54:52.794  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:54:53.000  2125  2313 I art     : Explicit concurrent mark sweep GC freed 7685(482KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.838ms total 37.667ms
,09-13 13:54:53.017  1802  8489 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-13 13:54:53.031  1802  8489 I CheckinService: active receiver: disabled
,09-13 13:54:53.053  2125  2125 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 13:54:53.070  2125  2125 I GCM     : GCM config loaded
,09-13 13:54:53.085  6786  8435 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 13:54:53.085  6786  8435 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:54:53.086  6786  8435 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:53.086  6786  8435 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:53.086  6786  8435 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 13:54:53.089  6786  8633 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 13:54:53.089  6786  8633 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:54:53.089  6786  8633 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:53.089  6786  8633 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:53.089  6786  8633 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 13:54:53.092  6786  8638 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: IncomingSocketThread/Sender)
09-13 13:54:53.093  6786  8637 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: OutgoingSocketThread/Receiver)
09-13 13:54:53.093  6786  8637 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: OutgoingSocketThread/Receiver)
09-13 13:54:53.094  6786  8637 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 13:54:53.094  6786  8637 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 13:54:53.095  6786  8639 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: IncomingSocketThread/Receiver)
09-13 13:54:53.095  6786  8639 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: IncomingSocketThread/Receiver)
09-13 13:54:53.095  6786  8639 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 13:54:53.095  6786  8639 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 13:54:53.096  6786  8636 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: OutgoingSocketThread/Sender)
09-13 13:54:53.101  8453  8453 V SetupWizard: Connected to Gservices successfully
,09-13 13:54:53.213  8308  8308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-13 13:54:53.218  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4782
,09-13 13:54:53.222  8308  8308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-13 13:54:53.222  8308  8308 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4782
09-13 13:54:53.584  7715  8376 D UEI.SmartControl: Internal timer expired: 2
,09-13 13:54:53.584  7715  8376 D UEI.SmartControl: unbind internal service
,09-13 13:54:53.677  7715  8370 D serial_port: close(fd = 24)
,09-13 13:54:53.689  7715  8370 I UEI.SmartControl: Serial port is closed.
,09-13 13:54:55.810  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=39.4, 0.0, 0.0  rx=34.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:593913282] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 13:54:55.826  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=39.4, 0.0, 0.0  rx=34.9 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:593913298] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:55.826  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:54:56.091  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 13:54:56.093  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 13:54:56.102  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3d888c7 Bundle[{}]
09-13 13:54:56.102  6786  6864 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 13:54:56.103  6786  6864 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 13:54:56.103  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 13:54:56.104  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 13:54:56.105  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 13:54:56.106  6786  6864 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 13:54:56.112  6786  6864 I System.out: Running OutgoingSocketThread
09-13 13:54:56.115  6786  8640 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 13:54:56.115  6786  8640 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 13:54:57.021  8550  8571 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-13 13:54:57.533  1035  1962 I ActivityManager: Killing 7668:com.lge.settings.easy/1000 (adj 15): empty #17
,09-13 13:54:57.567  1035  1748 W libprocessgroup: failed to open /acct/uid_1000/pid_7668/cgroup.procs: No such file or directory
,09-13 13:54:58.847  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=20.2, 0.0, 0.0  rx=18.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:593916318] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:58.850  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=20.2, 0.0, 0.0  rx=18.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593916321] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:54:58.850  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:54:59.126  6786  8640 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 13:54:59.126  6786  8640 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:54:59.127  6786  8640 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:59.127  6786  8640 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:59.127  6786  8640 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 13:54:59.132  6786  8643 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 13:54:59.132  6786  8643 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:54:59.132  6786  8643 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:59.132  6786  8643 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:54:59.132  6786  8643 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 13:54:59.135  6786  8646 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: OutgoingSocketThread/Receiver)
09-13 13:54:59.135  6786  8646 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: OutgoingSocketThread/Receiver)
09-13 13:54:59.135  6786  8646 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 13:54:59.135  6786  8646 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 13:54:59.137  6786  8645 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: OutgoingSocketThread/Sender)
09-13 13:54:59.139  6786  8648 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: IncomingSocketThread/Receiver)
09-13 13:54:59.139  6786  8648 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: IncomingSocketThread/Receiver)
09-13 13:54:59.139  6786  8648 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 13:54:59.139  6786  8648 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 13:54:59.141  6786  8647 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: IncomingSocketThread/Sender)
,09-13 13:55:00.056  1564  1564 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-13 13:55:00.062  1564  1564 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 13:55:00.065  1564  1564 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 13:55:00.065  1564  1564 I [SystemUI]Clock: called onTimeUpdated()
09-13 13:55:00.072  1564  1564 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 13:55:00.072  1564  1564 I [SystemUI]DateView: called onTimeUpdated()
09-13 13:55:00.077  1564  1564 I [SystemUI]DateView: called onTimeUpdated()
09-13 13:55:00.078  1564  1564 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 13:55:00.908  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 13:55:00.917  1564  1564 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 13:55:00.948  1035  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 13:55:01.026  1035  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8649 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 13:55:01.032  1564  1564 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 13:55:01.032  1564  1564 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 13:55:01.040  1035  1035 D administrator: Handling package changes for user 0
,09-13 13:55:01.073  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 13:55:01.101  8649  8649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 13:55:01.147  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-13 13:55:01.147  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 13:55:01.179  8649  8649 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:55:01.179  8649  8649 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:55:01.213  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 13:55:01.220  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 13:55:01.227  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 13:55:01.228  2487  2487 V GmsNetworkLocationProvi: DISABLE
,09-13 13:55:01.251  1035  1097 D LocationProviderProxy: applying state to connected service
09-13 13:55:01.255  2487  2487 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-13 13:55:01.275  8649  8693 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 13:55:01.275  8649  8693 I Babel   : MmsConfig.loadMmsSettings
09-13 13:55:01.278  8649  8693 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 13:55:01.278  8649  8693 I Babel   : MmsConfig.loadFromDatabase
,09-13 13:55:01.295  8649  8693 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 13:55:01.295  8649  8693 I Babel   : MmsConfig.loadFromResources
09-13 13:55:01.298  8649  8693 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 13:55:01.298  8649  8693 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 13:55:01.310  8649  8649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:55:01.314  8649  8692 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 13:55:01.315  8649  8692 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 13:55:01.317  8649  8692 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-13 13:55:01.323  8649  8692 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 13:55:01.324  8649  8692 W AudioCapabilities: Unsupported mime audio/qcelp
,09-13 13:55:01.325  8649  8692 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 13:55:01.332  8649  8692 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-13 13:55:01.334  8649  8692 W VideoCapabilities: Unsupported mime video/divx
09-13 13:55:01.336  8649  8692 W VideoCapabilities: Unsupported mime video/divx311
09-13 13:55:01.338  8649  8692 W VideoCapabilities: Unsupported mime video/divx4
,09-13 13:55:01.346  1802  8696 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 13:55:01.346  1802  8696 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-13 13:55:01.360  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 13:55:01.362  8649  8692 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-13 13:55:01.365  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c76b7ad
09-13 13:55:01.365  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 13:55:01.365  7128  7128 D AppUp4:CustFacade: isPhone : true
09-13 13:55:01.365  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
09-13 13:55:01.365  7128  7128 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 13:55:01.366  1802  4747 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-13 13:55:01.399  8649  8692 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 13:55:01.406  8649  8692 W AudioCapabilities: Unsupported mime audio/eac3
09-13 13:55:01.408  1035  2036 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8700 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-13 13:55:01.411  1035  1618 I ActivityManager: Killing 8226:com.lge.bnr/1000 (adj 15): empty #17
09-13 13:55:01.421  8649  8692 W AudioCapabilities: Unsupported mime audio/ac3
09-13 13:55:01.422  8649  8692 W AudioCapabilities: Unsupported mime audio/g726
09-13 13:55:01.422  8649  8692 W AudioCapabilities: Unsupported mime audio/wma-voice
,09-13 13:55:01.423  8649  8692 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 13:55:01.423  8649  8692 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 13:55:01.435  8649  8692 W VideoCapabilities: Unsupported mime video/theora
09-13 13:55:01.438  8649  8692 W VideoCapabilities: Unsupported mime video/mjpg
,09-13 13:55:01.528  1035  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_8226/cgroup.procs: No such file or directory
,09-13 13:55:01.549  8700  8700 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:55:01.550  8700  8700 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:55:01.550  8700  8700 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 13:55:01.551  8700  8700 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 13:55:01.552  8700  8700 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-13 13:55:01.600  8700  8700 I SystemConfig: BUILD Country: EU
09-13 13:55:01.600  8700  8700 I SystemConfig: BUILD Operator: OPEN
,09-13 13:55:01.635  1035  1998 I ActivityManager: Killing 8199:com.lge.sync/1000 (adj 15): empty #17,
,09-13 13:55:01.738  1035  1558 W libprocessgroup: failed to open /acct/uid_1000/pid_8199/cgroup.procs: No such file or directory
,09-13 13:55:01.802  1035  1907 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8723 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 13:55:01.811  8700  8718 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 13:55:01.811  8700  8718 I SystemConfig: existFile = false
09-13 13:55:01.811  8700  8718 I SystemConfig: canReadFile = false
09-13 13:55:01.811  8700  8718 I SystemConfig: systemFeature RCS result false
09-13 13:55:01.811  8700  8718 D SystemConfig: refreshRcsSupport() :false
,09-13 13:55:01.864  8723  8723 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:55:01.864  8723  8723 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 13:55:01.864  8723  8723 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-13 13:55:01.865  8723  8723 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 13:55:01.872  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=10.6, 0.0, 0.0  rx=9.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:593919344] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:55:01.875  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=10.6, 0.0, 0.0  rx=9.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:593919346] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:55:01.875  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:55:01.960  8723  8723 I AppConfig: Total System Memory = 2995761152
,09-13 13:55:01.976  8723  8723 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-13 13:55:02.068  1035  1748 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8742 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 13:55:02.070  1035  1748 I ActivityManager: Killing 6935:com.android.settings/1000 (adj 15): empty #17
,09-13 13:55:02.122  6786  6864 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 891)
09-13 13:55:02.123  6786  6864 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 13:55:02.123  6786  6864 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
09-13 13:55:02.127  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:55:02.127  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2837d5e9 added. We now have 3 listener(s)
09-13 13:55:02.135  1035  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_6935/cgroup.procs: No such file or directory
,09-13 13:55:02.143  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:02.148  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 13:55:02.148  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:55:02.148  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:55:02.148  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:55:02.148  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e29426e added. We now have 4 listener(s)
09-13 13:55:02.148  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:55:02.149  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:55:02.152  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:55:02.158  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:55:02.160  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:02.160  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:55:02.161  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:55:02.161  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:02.161  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:55:02.161  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:02.161  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:02.161  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:02.161  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:55:02.161  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2837d5e9 removed from the list
09-13 13:55:02.161  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:02.162  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e29426e removed from the list
09-13 13:55:02.163  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:02.163  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:55:02.163  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:02.163  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:02.164  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:02.165  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:02.165  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:02.165  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:02.165  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e29426e not in the list
09-13 13:55:02.165  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:02.165  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:02.167  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:02.167  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:02.167  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:02.167  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:02.167  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e29426e not in the list
09-13 13:55:02.167  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:02.167  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:02.167  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:02.167  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2837d5e9 not in the list
09-13 13:55:02.168  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:55:02.168  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5a819c added. We now have 3 listener(s)
09-13 13:55:02.169  1035  1617 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:02.172  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 13:55:02.172  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:55:02.172  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:55:02.172  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:55:02.173  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16aee7a5 added. We now have 4 listener(s)
09-13 13:55:02.173  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:55:02.173  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:55:02.177  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:55:02.182  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:55:02.183  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:02.184  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:55:02.185  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 13:55:02.185  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:55:02.185  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:55:02.185  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:02.185  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:55:02.186  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:02.189  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:55:02.189  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:02.189  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:02.193  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 13:55:02.196  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:55:02.197  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:55:02.198  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:55:02.199  6786  6864 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 13:55:02.200  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:02.200  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:55:02.354  8742  8742 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 13:55:02.448  8742  8742 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 13:55:02.448  8742  8742 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:55:02.503  8742  8742 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 13:55:02.528  8742  8742 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 13:55:02.529  8742  8742 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 13:55:02.546  8742  8742 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 13:55:02.547  8742  8742 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 13:55:02.567  1035  1925 I ActivityManager: Killing 8416:com.lge.email/u0a23 (adj 15): empty #17
09-13 13:55:02.628  1035  1962 W libprocessgroup: failed to open /acct/uid_10023/pid_8416/cgroup.procs: No such file or directory
,09-13 13:55:02.637  2830  5813 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-13 13:55:02.638  2830  5813 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@166054c0 on behalf of 8742
09-13 13:55:02.640  4555  8779 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-13 13:55:02.678  1035  1944 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8780 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 13:55:02.696  8742  8742 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 13:55:02.718  8742  8742 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 13:55:02.765  8780  8780 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 13:55:02.786  8780  8780 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 13:55:02.786  8780  8780 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 13:55:02.786  8780  8780 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 13:55:02.786  8780  8780 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 13:55:02.786  8780  8780 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 13:55:02.786  8780  8780 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-13 13:55:02.800  1035  2017 I ActivityManager: Killing 8176:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-13 13:55:02.838  1035  2036 W libprocessgroup: failed to open /acct/uid_10026/pid_8176/cgroup.procs: No such file or directory
,09-13 13:55:03.024  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-13 13:55:03.037  4555  8779 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 396 ms] updated apps [took 396 ms] 
,09-13 13:55:04.896  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:593922368] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:55:04.899  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593922371] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 13:55:04.899  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:05.201  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:55:05.201  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:05.201  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:55:05.210  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:05.211  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:05.211  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:05.211  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:55:05.211  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5a819c removed from the list
09-13 13:55:05.211  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:05.211  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16aee7a5 removed from the list
09-13 13:55:05.211  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:55:05.212  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:05.215  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:05.215  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:05.216  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:05.216  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:05.217  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:55:05.217  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:55:05.217  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:05.217  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16aee7a5 not in the list
09-13 13:55:05.217  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:05.217  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:05.219  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:55:05.223  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:55:05.223  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:55:05.223  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:05.223  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:05.223  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16aee7a5 not in the list
09-13 13:55:05.223  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:05.223  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:05.223  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:05.223  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5a819c not in the list
09-13 13:55:05.226  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:55:05.226  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30cb5921 added. We now have 3 listener(s)
09-13 13:55:05.226  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:05.229  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 13:55:05.229  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:55:05.229  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:55:05.229  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:55:05.229  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c433146 added. We now have 4 listener(s)
09-13 13:55:05.229  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:55:05.230  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:55:05.234  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:55:05.241  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:55:05.244  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:05.244  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:55:05.246  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:55:05.250  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:05.251  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 13:55:05.251  6786  6864 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 13:55:05.252  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 13:55:05.255  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 13:55:05.255  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 13:55:05.255  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 13:55:05.255  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:05.258  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 13:55:05.261  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 13:55:05.261  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 13:55:05.261  6786  6786 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 13:55:05.263  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 13:55:05.263  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 13:55:05.263  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:05.263  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:55:05.267  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:55:05.269  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:05.274  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:55:05.277  1035  1617 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:05.279  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:55:05.280  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:55:05.282  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:55:05.283  6786  8807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:55:05.284  6786  6864 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 13:55:05.285  7995  8117 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-13 13:55:05.286  6786  8807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 13:55:07.926  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:593925397] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:07.929  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593925400] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:07.929  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:08.290  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:55:08.291  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:08.291  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:55:08.291  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 13:55:08.292  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 13:55:08.292  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 13:55:08.304  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:08.305  6786  8807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 13:55:08.305  6786  8807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 13:55:08.305  6786  8807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 13:55:08.306  6786  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 13:55:08.307  6786  6864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 13:55:08.307  6786  6786 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 13:55:08.309  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:55:08.309  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:08.309  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:08.311  6786  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:08.311  6786  6786 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:55:08.313  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:08.313  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:08.313  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:08.313  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:55:08.314  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30cb5921 removed from the list
09-13 13:55:08.314  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:08.314  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c433146 removed from the list
09-13 13:55:08.314  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:55:08.314  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:08.315  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:08.315  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:08.316  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:08.316  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:08.317  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:55:08.317  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:55:08.317  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:08.317  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c433146 not in the list
09-13 13:55:08.317  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:08.317  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:08.318  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:08.319  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:55:08.319  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:55:08.319  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:08.319  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:08.319  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c433146 not in the list
09-13 13:55:08.319  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:08.319  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:08.319  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:08.319  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30cb5921 not in the list
09-13 13:55:08.320  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:55:08.320  6786  ,6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f11bd2 added. We now have 3 listener(s)
09-13 13:55:08.321  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:08.325  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 13:55:08.325  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:55:08.325  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:55:08.325  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:55:08.325  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f04a3 added. We now have 4 listener(s)
09-13 13:55:08.326  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:55:08.330  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:55:08.335  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:55:08.340  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:55:08.344  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:08.345  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:55:08.347  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:08.350  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:08.350  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:55:08.350  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:55:08.350  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:55:08.350  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:08.350  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:55:08.354  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:55:08.356  1035  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:08.361  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 13:55:08.362  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:55:08.364  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:55:08.365  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:08.366  6786  6864 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 13:55:10.955  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:593928426] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:10.958  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:593928430] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:10.958  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:11.375  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:55:11.382  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:11.382  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:55:11.384  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:11.384  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.384  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:11.384  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:55:11.384  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f11bd2 removed from the list
09-13 13:55:11.385  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:11.385  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f04a3 removed from the list
09-13 13:55:11.385  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:55:11.385  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:11.388  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.389  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:11.391  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:11.392  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:11.396  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:55:11.396  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:55:11.396  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:11.396  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f04a3 not in the list
09-13 13:55:11.396  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.396  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:55:11.400  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:11.401  6786  6864 D BluetoothLeScanner: could not find callback wrapper
09-13 13:55:11.401  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:55:11.401  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:11.401  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:11.401  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f04a3 not in the list
09-13 13:55:11.401  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:11.401  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.401  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:11.401  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f11bd2 not in the list
09-13 13:55:11.402  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:55:11.402  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370347ff added. We now have 3 listener(s)
09-13 13:55:11.403  1035  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 13:55:11.406  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 13:55:11.406  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:55:11.406  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:55:11.406  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:55:11.406  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8f89cc added. We now have 4 listener(s)
09-13 13:55:11.406  6786  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:55:11.408  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:55:11.415  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:55:11.419  6786  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:55:11.422  6786  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:55:11.422  6786  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:55:11.426  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:11.428  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:55:11.430  6786  6864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:55:11.430  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:11.430  6786  6864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:55:11.432  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:11.432  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.432  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:55:11.432  6786  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:55:11.433  6786  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370347ff removed from the list
09-13 13:55:11.433  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:11.433  6786  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8f89cc removed from the list
09-13 13:55:11.433  6786  6864 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:55:11.433  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:11.435  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.435  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:55:11.438  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:11.438  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:11.438  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:11.438  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8f89cc not in the list
09-13 13:55:11.438  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.438  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:11.439  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:55:11.439  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:55:11.440  6786  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:55:11.440  6786  6864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8f89cc not in the list
09-13 13:55:11.440  6786  6864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:55:11.440  6786  6864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:55:11.440  6786  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:55:11.440  6786  6864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370347ff not in the list
09-13 13:55:11.441  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 13:55:11.441  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 13:55:11.441  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 13:55:11.442  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:55:11.442  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 13:55:11.442  6786  6864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:55:13.463  6786  8808 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 901, name: My test thread name)
,09-13 13:55:13.984  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:593931455] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:13.993  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:593931465] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:13.993  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:55:15.461  6786  6864 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 901
09-13 13:55:15.461  6786  6864 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 901, name: My test thread name)
,09-13 13:55:15.477  6786  8809 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 902, name: My test thread name)
09-13 13:55:15.477  6786  8809 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 902, thread name: My test thread name)
09-13 13:55:15.477  6786  8809 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 902, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 13:55:15.479  6786  6864 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:55:15.483  6786  8810 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: My test thread name)
09-13 13:55:15.484  6786  8810 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 906, thread name: My test thread name): Test exception.
,09-13 13:55:15.486  6786  8810 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-13 13:55:15.489  6786  6864 I jxcore-log: Total number of executed tests:  82
09-13 13:55:15.489  6786  6864 I jxcore-log: 
09-13 13:55:15.490  6786  6864 I jxcore-log: Number of passed tests:  82
09-13 13:55:15.490  6786  6864 I jxcore-log: 
09-13 13:55:15.490  6786  6864 I jxcore-log: Number of failed tests:  0
09-13 13:55:15.490  6786  6864 I jxcore-log: 
09-13 13:55:15.490  6786  6864 I jxcore-log: Number of ignored tests:  0
09-13 13:55:15.490  6786  6864 I jxcore-log: 
09-13 13:55:15.490  6786  6864 I jxcore-log: Total duration:  101568
09-13 13:55:15.490  6786  6864 I jxcore-log: 
09-13 13:55:15.493  6786  6864 I jxcore-log: Unit Test app is loaded
09-13 13:55:15.493  6786  6864 I jxcore-log: 
09-13 13:55:15.510  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.510  6786  6864 I jxcore-log: 
,09-13 13:55:15.530  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.530  6786  6864 I jxcore-log: 
09-13 13:55:15.532  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.532  6786  6864 I jxcore-log: 
09-13 13:55:15.533  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.533  6786  6864 I jxcore-log: 
09-13 13:55:15.534  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.534  6786  6864 I jxcore-log: 
,09-13 13:55:15.537  6786  6786 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 13:55:15.540  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.540  6786  6864 I jxcore-log: 
09-13 13:55:15.543  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:55:15.543  6786  6864 I jxcore-log: 
09-13 13:55:15.545  6786  8808 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 901, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-13 13:55:15.546  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.546  6786  6864 I jxcore-log: 
09-13 13:55:15.547  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.547  6786  6864 I jxcore-log: 
09-13 13:55:15.548  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.548  6786  6864 I jxcore-log: 
09-13 13:55:15.549  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.549  6786  6864 I jxcore-log: 
09-13 13:55:15.551  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.551  6786  6864 I jxcore-log: 
09-13 13:55:15.552  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.552  6786  6864 I jxcore-log: 
09-13 13:55:15.553  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.553  6786  6864 I jxcore-log: 
09-13 13:55:15.554  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.554  6786  6864 I jxcore-log: 
,09-13 13:55:15.559  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.559  6786  6864 I jxcore-log: 
09-13 13:55:15.560  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.560  6786  6864 I jxcore-log: 
09-13 13:55:15.560  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.560  6786  6864 I jxcore-log: 
09-13 13:55:15.561  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.561  6786  6864 I jxcore-log: 
09-13 13:55:15.562  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.562  6786  6864 I jxcore-log: 
09-13 13:55:15.563  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.563  6786  6864 I jxcore-log: 
09-13 13:55:15.563  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.563  6786  6864 I jxcore-log: 
09-13 13:55:15.565  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.565  6786  6864 I jxcore-log: 
09-13 13:55:15.566  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.566  6786  6864 I jxcore-log: 
09-13 13:55:15.566  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.566  6786  6864 I jxcore-log: 
09-13 13:55:15.567  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.567  6786  6864 I jxcore-log: 
09-13 13:55:15.568  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.568  6786  6864 I jxcore-log: 
09-13 13:55:15.569  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.569  6786  6864 I jxcore-log: 
09-13 13:55:15.569  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.569  6786  6864 I jxcore-log: 
09-13 13:55:15.570  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.570  6786  6864 I jxcore-log: 
09-13 13:55:15.571  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.571  6786  6864 I jxcore-log: 
09-13 13:55:15.571  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:55:15.571  6786  6864 I jxcore-log: 
09-13 13:55:15.572  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth,":"on","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.572  6786  6864 I jxcore-log: 
09-13 13:55:15.573  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 13:55:15.573  6786  6864 I jxcore-log: 
09-13 13:55:15.574  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.574  6786  6864 I jxcore-log: 
09-13 13:55:15.575  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.575  6786  6864 I jxcore-log: 
09-13 13:55:15.576  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.576  6786  6864 I jxcore-log: 
09-13 13:55:15.577  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.577  6786  6864 I jxcore-log: 
09-13 13:55:15.578  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.578  6786  6864 I jxcore-log: 
09-13 13:55:15.578  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.578  6786  6864 I jxcore-log: 
09-13 13:55:15.579  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.579  6786  6864 I jxcore-log: 
09-13 13:55:15.580  6786  6864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:55:15.580  6786  6864 I jxcore-log: 
,09-13 13:55:15.591  6786  6864 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'notHere',
09-13 13:55:15.591  6786  6864 I jxcore-log:   bluetooth: 'on',
09-13 13:55:15.591  6786  6864 I jxcore-log:   wifi: 'on',
09-13 13:55:15.591  6786  6864 I jxcore-log:   cellular: 'doNotCare',
09-13 13:55:15.591  6786  6864 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 13:55:15.591  6786  6864 I jxcore-log: 
09-13 13:55:15.599  6786  6864 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'notHere',
09-13 13:55:15.599  6786  6864 I jxcore-log:   bluetooth: 'on',
09-13 13:55:15.599  6786  6864 I jxcore-log:   wifi: 'on',
09-13 13:55:15.599  6786  6864 I jxcore-log:   cellular: 'doNotCare',
09-13 13:55:15.599  6786  6864 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 13:55:15.599  6786  6864 I jxcore-log: 
09-13 13:55:15.600  6786  6864 I jxcore-log: My device name is: LGE-LG-D855
09-13 13:55:15.600  6786  6864 I jxcore-log: 
09-13 13:55:15.601  6786  6864 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 13:55:15.601  6786  6864 I jxcore-log: 
09-13 13:55:15.601  6786  6864 I jxcore-log: Running for WIFI network type
09-13 13:55:15.601  6786  6864 I jxcore-log: 
,09-13 13:55:17.015  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:593934487] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:17.017  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:593934489] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:17.017  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:18.245  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 13:55:18.245  6786  6864 I jxcore-log: 
,09-13 13:55:18.692  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 13:55:18.692  6786  6864 I jxcore-log: 
,09-13 13:55:18.717  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 13:55:18.717  6786  6864 I jxcore-log: 
,09-13 13:55:20.038  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:593937509] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:20.040  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593937512] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:20.040  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:20.064  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 13:55:20.064  6786  6864 I jxcore-log: 
,09-13 13:55:20.293  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 13:55:20.293  6786  6864 I jxcore-log: 
,09-13 13:55:20.299  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 13:55:20.299  6786  6864 I jxcore-log: 
,09-13 13:55:20.305  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 13:55:20.305  6786  6864 I jxcore-log: 
,09-13 13:55:20.382  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 13:55:20.382  6786  6864 I jxcore-log: 
,09-13 13:55:20.403  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 13:55:20.403  6786  6864 I jxcore-log: 
,09-13 13:55:20.409  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 13:55:20.409  6786  6864 I jxcore-log: 
09-13 13:55:21.311  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 13:55:21.311  6786  6864 I jxcore-log: 
,09-13 13:55:21.477  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 13:55:21.477  6786  6864 I jxcore-log: 
,09-13 13:55:21.807  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 13:55:21.807  6786  6864 I jxcore-log: 
,09-13 13:55:21.818  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 13:55:21.818  6786  6864 I jxcore-log: 
,09-13 13:55:21.825  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 13:55:21.825  6786  6864 I jxcore-log: 
,09-13 13:55:21.832  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 13:55:21.832  6786  6864 I jxcore-log: 
,09-13 13:55:21.869  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 13:55:21.869  6786  6864 I jxcore-log: 
,09-13 13:55:21.915  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 13:55:21.915  6786  6864 I jxcore-log: 
,09-13 13:55:21.921  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 13:55:21.921  6786  6864 I jxcore-log: 
09-13 13:55:21.928  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 13:55:21.928  6786  6864 I jxcore-log: 
09-13 13:55:21.947  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 13:55:21.947  6786  6864 I jxcore-log: 
,09-13 13:55:21.952  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 13:55:21.952  6786  6864 I jxcore-log: 
,09-13 13:55:21.957  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 13:55:21.957  6786  6864 I jxcore-log: 
09-13 13:55:21.972  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 13:55:21.972  6786  6864 I jxcore-log: 
,09-13 13:55:21.999  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 13:55:21.999  6786  6864 I jxcore-log: 
,09-13 13:55:22.012  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 13:55:22.012  6786  6864 I jxcore-log: 
,09-13 13:55:22.026  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 13:55:22.026  6786  6864 I jxcore-log: 
,09-13 13:55:22.039  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 13:55:22.039  6786  6864 I jxcore-log: 
,09-13 13:55:22.054  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 13:55:22.054  6786  6864 I jxcore-log: 
,09-13 13:55:22.064  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 13:55:22.064  6786  6864 I jxcore-log: 
,09-13 13:55:22.069  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 13:55:22.069  6786  6864 I jxcore-log: 
,09-13 13:55:22.097  6786  6864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 13:55:22.097  6786  6864 I jxcore-log: 
,09-13 13:55:22.107  6786  6864 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
09-13 13:55:22.108  6786  6864 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
09-13 13:55:22.108  6786  6864 I jxcore-log: 
09-13 13:55:22.110  6786  6864 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 13:55:22.110  6786  6864 I jxcore-log: 
09-13 13:55:22.110  6786  6864 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 13:55:22.110  6786  6864 I jxcore-log: 
09-13 13:55:22.115  6786  6864 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 13:55:22.115  6786  6864 I jxcore-log: 
,09-13 13:55:22.253  6786  6864 I jxcore-log: ThaliTape :: Connected to the test server
09-13 13:55:22.253  6786  6864 I jxcore-log: 
,09-13 13:55:23.065  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:593940537] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:23.068  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593940540] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:23.068  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:26.098  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:593943569] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:26.101  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:593943573] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:26.101  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:26.750  1035  1521 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,09-13 13:55:26.751  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
09-13 13:55:26.752  1035  1521 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
09-13 13:55:26.753  1035  1521 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,09-13 13:55:26.764  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,09-13 13:55:26.766  1035  1521 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
09-13 13:55:29.122  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:593946594] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:29.134  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:593946605] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:29.135  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:55:32.155  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:593949627] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:32.158  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:593949630] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:32.158  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 13:55:35.182  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:593952654] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 13:55:35.193  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:593952665] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:35.193  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:55:36.892  6786  6864 I jxcore-log: Device disqualified
09-13 13:55:36.892  6786  6864 I jxcore-log: 
09-13 13:55:36.893  6786  6864 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 13:55:36.893  6786  6864 I jxcore-log: 
,09-13 13:55:37.232  8828  8828 D AndroidRuntime: 
09-13 13:55:37.232  8828  8828 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 13:55:37.238  8828  8828 D AndroidRuntime: CheckJNI is OFF
09-13 13:55:37.386  8828  8828 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 13:55:37.403  1035  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 13:55:37.403  1035  1098 I ActivityManager: Killing 6786:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 13:55:37.468  1035  2017 I WindowState: WIN DEATH: Window{17b01910 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 13:55:37.469  1035  1527 D WifiService: Client connection lost with reason: 4
,09-13 13:55:37.475  1035  2017 D InputDispatcher: Window went away: Window{17b01910 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 13:55:37.622  1035  1098 I ActivityManager:   Force finishing activity ActivityRecord{2db43ae5 u0 com.test.thalitest/.MainActivity t6}
,09-13 13:55:37.663   336   354 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 13:55:37.668  1035  1962 W ActivityManager: Spurious death for ProcessRecord{18d12004 6786:com.test.thalitest/u0a118}, curProc for 6786: null
09-13 13:55:37.671  1926  3946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 13:55:37.672  1926  3946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{11aa73fe co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 13:55:37.673  1926  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 13:55:37.673  1926  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{295ef75f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-13 13:55:37.683  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-13 13:55:37.737  4555  4555 I art     : Explicit concurrent mark sweep GC freed 15443(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 514us total 46.635ms
,09-13 13:55:37.739  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 13:55:37.741  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 13:55:37.743  1035  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 13:55:37.746  1564  1564 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 13:55:37.747  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 13:55:37.748  3804  3804 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-13 13:55:37.751  7995  7995 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 13:55:37.751  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 13:55:37.756  2487  2588 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 13:55:37.768  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-13 13:55:37.771  4444  4444 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-13 13:55:37.772  4444  4444 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 13:55:37.772  4444  4444 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 13:55:37.772  4444  4444 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 13:55:37.772  4444  4444 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 13:55:37.772  4444  4444 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 13:55:37.772  4444  4444 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:55:37.772  4444  4444 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:55:37.772  4444  4444 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:55:37.772  4444  4444 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:55:37.772  4444  4444 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:55:37.772  4444  4444 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 13:55:37.790  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 13:55:37.790  1035  1618 V SIM_STK : Menu title from STK is T-Mobile
09-13 13:55:37.791  2018  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,09-13 13:55:37.811  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-13 13:55:37.813  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 13:55:37.814  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 13:55:37.815  1889  1889 D ActionManagerService: notifyUserLog: 1000003
09-13 13:55:37.816  3804  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 13:55:37.817  1564  1564 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-13 13:55:37.819  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 13:55:37.822  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-13 13:55:37.836  2125  2125 I ConfigService: onCreate
,09-13 13:55:37.840  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 13:55:37.842  1889  1889 D ActionManagerService: notifyUserLog: 1000004
09-13 13:55:37.843  3804  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 13:55:37.844  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 13:55:37.848  3804  3820 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 13:55:37.850  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-13 13:55:37.850  2125  2125 I ConfigService: onBind returning update interface
09-13 13:55:37.855  2125  2125 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 13:55:37.855  2125  2125 I ConfigService: onBind returning config service
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , display: false
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , animation: false }
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , display: false
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , animation: false }
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , display: false
09-13 13:55:37.855  2018  2018 I GBoardWebViewUtils: , animation: false }
09-13 13:55:37.855  1564  1564 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 13:55:37.856  1564  1564 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 13:55:37.861  1035  1998 V SIM_STK : Menu title from STK is T-Mobile
09-13 13:55:37.861  1035  1998 V SIM_STK : Menu title from STK is T-Mobile
,09-13 13:55:37.867  2018  8861 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 13:55:37.870  2125  2125 I ConfigService: onDestroy
09-13 13:55:37.882  1564  1636 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 13:55:37.883  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.887  1802  8862 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 13:55:37.893  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 13:55:37.894  1854  1854 D SplitUIService: removed split : 
,09-13 13:55:37.895  1564  1636 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 13:55:37.895  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.900  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 13:55:37.901  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 13:55:37.907  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 13:55:37.907  1564  1636 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:55:37.907  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 13:55:37.908  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 13:55:37.910  1564  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:37.910  1564  1636 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 13:55:37.911  1564  1636 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 13:55:37.911  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.918  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 13:55:37.918  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:55:37.920  1564  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:37.921  1564  1636 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-13 13:55:37.923  1564  1636 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 13:55:37.923  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.927  1564  1636 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:55:37.927  1564  1636 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 13:55:37.928  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 13:55:37.928  1564  1636 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 13:55:37.928  1564  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:37.928  1564  1636 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 13:55:37.929  1564  1636 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 13:55:37.929  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.932  1035  2017 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 13:55:37.932  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 13:55:37.932  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 13:55:37.933  7995  7995 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 13:55:37.935  1564  1564 D KeyguardModel: handleShortcutListChanged...
09-13 13:55:37.935  1564  1564 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 13:55:37.936  5984  8867 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-13 13:55:37.948  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 13:55:37.948  1854  1854 I SplitUIService: split app #11
09-13 13:55:37.950  1035  1035 I art     : Explicit concurrent mark sweep GC freed 48567(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 7.053ms total 249.654ms
,09-13 13:55:37.952  1035  1123 I art     : WaitForGcToComplete blocked for 81.414ms for cause Explicit
09-13 13:55:37.955  1564  1636 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 13:55:37.955  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.957  1564  1636 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 13:55:37.957  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.959  1564  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:37.959  1564  1636 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 13:55:37.961  1564  1636 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 13:55:37.961  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.964  1564  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:37.964  1564  1636 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 13:55:37.967  1564  1636 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 13:55:37.967  1564  1636 D KeyguardModel: createShortcutInfo...
,09-13 13:55:37.971  1564  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:37.971  1564  1636 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 13:55:37.976  1564  1636 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 13:55:37.976  1564  1636 D KeyguardModel: createShortcutInfo...
09-13 13:55:37.993  1035  1035 D administrator: Handling package changes for user 0
,09-13 13:55:37.994  1035  1980 V SIM_STK : Menu title from STK is T-Mobile
09-13 13:55:37.995  1802  8871 I PeopleContactsSync: CP2 sync disabled
09-13 13:55:37.998  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 13:55:37.999  1802  4747 I Icing   : doRemovePackageData com.test.thalitest
09-13 13:55:38.016  1564  1564 D KeyguardModel: handleShortcutListChanged...
09-13 13:55:38.016  1564  1564 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-13 13:55:38.025  1802  8870 W GmsApplication: Using Auth Proxy for data requests.
,09-13 13:55:38.031  1802  8870 W GmsApplication: Using Auth Proxy for data requests.
09-13 13:55:38.071   329   440 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 13:55:38.073  3173  8874 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,09-13 13:55:38.075  7128  7128 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-13 13:55:38.078  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 13:55:38.078  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 13:55:38.079  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 13:55:38.083  1035  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 13:55:38.087  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-13 13:55:38.093  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 13:55:38.094  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 13:55:38.095  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 13:55:38.096  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 13:55:38.097  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 13:55:38.119  2354  8875 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 13:55:38.120  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 13:55:38.120  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 13:55:38.125  2018  2216 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 13:55:38.125  2018  2216 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 13:55:38.125  1035  1944 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8877 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-13 13:55:38.127  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6f7036 u0 com.lge.launcher2/.Launcher t5} time:448562
09-13 13:55:38.135  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 13:55:38.136  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 13:55:38.137  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 13:55:38.145  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 13:55:38.148  2661  2661 D [Concierge]Service: onStartCommand(). Type : 8
09-13 13:55:38.148  2661  2661 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 13:55:38.149  2661  2661 D [Concierge]Service: Update widget ID : 11
09-13 13:55:38.150  2018  2018 D [Concierge]WidgetView: change position of spinner
,09-13 13:55:38.152  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1473767738152
09-13 13:55:38.153  2661  2661 D [Concierge]Service: onStartCommand(). Type : 0
09-13 13:55:38.167  8877  8877 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:55:38.167  8877  8877 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 13:55:38.168  8877  8877 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 13:55:38.168  8877  8877 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 13:55:38.173  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 234359320
09-13 13:55:38.173  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 13:55:38.173  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 13:55:38.176  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1919d975
09-13 13:55:38.176  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 13:55:38.177  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 13:55:38.177  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 13:55:38.182  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 13:55:38.183  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 13:55:38.183  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 13:55:38.184  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473767317345, New one : 1473767738152
09-13 13:55:38.184  2018  2018 D [Concierge]WidgetView: Unregister all receivers
09-13 13:55:38.184  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 13:55:38.185  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 13:55:38.186  1802  8895 I art     : Explicit concurrent mark sweep GC freed 37766(2MB) AllocSpace objects, 27(432KB) LOS objects, 51% free, 30MB/62MB, paused 744us total 25.655ms
09-13 13:55:38.186  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 13:55:38.187  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 13:55:38.188  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 13:55:38.188  1802  1814 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-13 13:55:38.189  1802  1814 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-13 13:55:38.189  1802  1814 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-13 13:55:38.189  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 13:55:38.190  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-13 13:55:38.195  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 13:55:38.195  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 13:55:38.207  1035  1123 I art     : Explicit concurrent mark sweep GC freed 11509(797KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.022ms total 225.651ms
,09-13 13:55:38.213  1035  1521 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:593955685] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:38.214  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:593955686] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 13:55:38.214  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 13:55:38.237  8877  8877 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 13:55:38.238  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 13:55:38.246  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 13:55:38.246  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 13:55:38.247  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 13:55:38.253  8877  8877 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 13:55:38.266  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@247977dd time:448702
09-13 13:55:38.271  8828  8828 D AndroidRuntime: Shutting down VM
,09-13 13:55:38.280  8877  8877 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 13:55:38.302  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8897 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 13:55:38.322  8877  8877 D LgDataFeature: LgDataFeature() Constructor: none
09-13 13:55:38.322  8877  8877 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 13:55:38.349  1035  2017 I ActivityManager: Killing 8472:com.android.chrome/u0a57 (adj 15): empty #17
,09-13 13:55:38.387  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-13 13:55:38.415  1035  1617 W libprocessgroup: failed to open /acct/uid_10057/pid_8472/cgroup.procs: No such file or directory
,09-13 13:55:38.422  2018  2915 I GBoardtInterface: onReloaded()
09-13 13:55:38.424  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 13:55:38.425  3804  3820 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 13:55:38.427  3804  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-13 13:55:38.432  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-13 13:55:38.433  3804  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 13:55:38.433  3804  4443 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 13:55:38.436  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-13 13:55:38.437  3804  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 13:55:38.437  3804  4443 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 13:55:38.437  3804  4443 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 13:55:38.437  3804  4443 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-13 13:55:38.438  3804  3820 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-13 13:55:38.440  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 13:55:38.440  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 13:55:38.441  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 13:55:38.442  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 13:55:38.443  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 13:55:38.443  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-13 13:55:38.463  8877  8877 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 13:55:38.471  1035  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 13:55:38.475  1035  2036 I ActivityManager: Killing 8512:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-13 13:55:38.525  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 13:55:38.525  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,09-13 13:55:38.526  1035  1962 W libprocessgroup: failed to open /acct/uid_10062/pid_8512/cgroup.procs: No such file or directory
09-13 13:55:38.528  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-13 13:55:38.530  8244  8244 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-13 13:55:38.566  1035  1748 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8920 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 13:55:38.610  8920  8920 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:55:38.610  8920  8920 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: Unable to open database for writing.
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 13:55:38.611  8920  8920 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 13:55:38.622  8920  8920 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-13 13:55:38.622  8920  8920 W LG Account v2.2: No ProfileInfo entries
09-13 13:55:38.622  8920  8920 I LG Account v2.2: isEnabled: false
09-13 13:55:38.622  8920  8920 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 13:55:38.622  8920  8920 I Feature : [Lifetracker]Country: EU
09-13 13:55:38.622  8920  8920 I Feature : [Lifetracker]Operator: OPEN
09-13 13:55:38.622  8920  8920 I Feature : [Lifetracker]Ranking support: false
09-13 13:55:38.622  8920  8920 I Feature : [Lifetracker]Comfort support: false
09-13 13:55:38.623  8920  8920 I Feature : [Lifetracker]Accessory: true
09-13 13:55:38.623  8920  8920 I Feature : [Lifetracker]Health device: true
09-13 13:55:38.623  8920  8920 I Feature : [Lifetracker]Extra Pedometer: false
09-13 13:55:38.623  8920  8920 I Feature : [Lifetracker]Blood glucose device: false
09-13 13:55:38.623  8920  8920 I Feature : [Lifetracker]Device Number: 3
09-13 13:55:38.624  8920  8920 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-13 13:55:38.633  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 13:55:38.639  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
