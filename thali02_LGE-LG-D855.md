#### Test 8362733795b1a33_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 16:10:00.100  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 16:10:13.697  6721  6721 D AndroidRuntime: 
09-13 16:10:13.697  6721  6721 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 16:10:13.704  6721  6721 D AndroidRuntime: CheckJNI is OFF
09-13 16:10:13.905  6721  6721 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 16:10:13.916  1037  2016 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 16:10:13.932  1969  3999 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 16:10:13.939  1037  2016 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 16:10:13.941  1037  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{22023ae7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 16:10:13.941  1037  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{22023ae7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 16:10:13.942  1037  2016 D WindowStateEx: AppWindowTokenEx init.. 
09-13 16:10:13.943   341   358 E GBMv2   : DFP En is all cleared set to be enabled
09-13 16:10:13.971  1037  2016 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6736 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 16:10:13.974  6721  6721 D AndroidRuntime: Shutting down VM
09-13 16:10:14.028  1969  1986 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 16:10:14.028  1969  1986 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16c269d2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 16:10:14.029  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 16:10:14.029  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17713aa3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 16:10:14.097  6736  6736 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-13 16:10:14.202  6736  6736 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 16:10:14.213  6736  6736 I LibraryLoader: Loading: webviewchromium
,09-13 16:10:14.216  6736  6736 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7303-7308)
,09-13 16:10:14.216  6736  6736 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:10:14.234  6736  6736 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33272950}
,09-13 16:10:14.235  6736  6736 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:10:14.236  6736  6736 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 16:10:14.245  6736  6736 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 16:10:14.246  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:10:14.264  6736  6736 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 16:10:14.264  6736  6736 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 16:10:14.265  6736  6736 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 16:10:14.271   317  4021 V AudioPolicyService: registerClient() client 0xb14268e0, uid 10118
09-13 16:10:14.276  1037  1099 D BluetoothManagerService: Message: 20
09-13 16:10:14.276  1037  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bd2e839:true
,09-13 16:10:14.307  6736  6736 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:10:14.307  6736  6736 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:10:14.307  6736  6736 I Adreno-EGL: Build Date: 12/12/14 금
09-13 16:10:14.307  6736  6736 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 16:10:14.307  6736  6736 I Adreno-EGL: Remote Branch: 
09-13 16:10:14.307  6736  6736 I Adreno-EGL: Local Patches: 
09-13 16:10:14.307  6736  6736 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:10:14.412  6736  6783 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 16:10:14.420  6736  6736 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-13 16:10:14.436  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:10:14.441  6736  6736 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:10:14.444  6736  6736 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 16:10:14.446  6736  6736 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 16:10:14.446  6736  6736 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 16:10:14.460  6736  6736 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 16:10:14.467  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:10:14.467  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:10:14.517  6736  6798 D OpenGLRenderer: Render dirty regions requested: true
09-13 16:10:14.517  6736  6798 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 16:10:14.524  6736  6798 D OpenGLRenderer: Enabling debug mode 0
,09-13 16:10:14.528  1037  1095 W ActivityManager: Activity pause timeout for ActivityRecord{1e8fa694 u0 com.test.thalitest/.MainActivity t6}
09-13 16:10:14.548  6736  6736 D Atlas   : Validating map...
,09-13 16:10:14.562  1037  1595 D SplitWindow: check instance of lgWin Window{1bc3f8eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:10:14.588  6736  6796 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:14.589  6736  6796 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 16:10:14.672  1037  1100 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +645ms (total +728ms)
,09-13 16:10:14.674  6736  6736 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3834405f time:167766
09-13 16:10:14.675  1037  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e8fa694 u0 com.test.thalitest/.MainActivity t6} time:167767
09-13 16:10:14.801  6736  6736 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 16:10:14.801  6736  6736 I chromium: 
,09-13 16:10:14.826  6736  6736 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:10:14.966  6736  6811 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,09-13 16:10:14.981  6736  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:10:14.981  6736  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:10:14.981  6736  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:10:14.981  6736  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:10:14.981  6736  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 16:10:14.981  6736  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abe6f3 added. We now have 1 listener(s)
,09-13 16:10:14.990  1037  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:14.995  6736  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 16:10:14.997  6736  6811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:10:14.999  6736  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:10:14.999  6736  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:10:15.010  6736  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccfe5ae added. We now have 1 listener(s)
09-13 16:10:15.011  6736  6811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:10:15.016  1037  1546 D WifiService: New client listening to asynchronous messages
09-13 16:10:15.020  6736  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:10:15.020  6736  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:10:15.021  6736  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:10:15.021  6736  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:10:15.021  6736  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 16:10:15.024  6736  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:10:15.026  1037  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 16:10:15.027  6736  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 16:10:15.036  6736  6811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:15.037  6736  6811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:15.037  6736  6811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 16:10:15.037  6736  6811 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:10:15.040  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:15.042  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:15.045  6736  6811 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:10:15.091  6736  6796 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 16:10:15.091  6736  6796 I chromium: 
,09-13 16:10:15.161  6736  6736 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:10:15.870   341   360 E GBMv2   : DFP En is all cleared set to be enabled
09-13 16:10:15.870   341   360 E GBMv2   : Set value is all cleared set the max
09-13 16:10:15.870   341   360 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 16:10:15.909  6736  6814 W jxcore-log: Initializing JXcore engine
09-13 16:10:15.910  6736  6814 W jxcore-log: JXcore engine is ready
,09-13 16:10:16.016  6814  6814 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7482]" dev="sockfs" ino=7482 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 16:10:16.016  6814  6814 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-13 16:10:16.016  6814  6814 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7721]" dev="sockfs" ino=7721 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 16:10:16.016  6814  6814 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 16:10:16.016  6814  6814 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31863]" dev="sockfs" ino=31863 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-13 16:10:16.040  6736  6814 W jxcore-log: Starting JXcore engine
,09-13 16:10:16.200  6736  6814 W jxcore-log: Platform android
09-13 16:10:16.200  6736  6814 W jxcore-log: 
09-13 16:10:16.200  6736  6814 W jxcore-log: Process ARCH arm
09-13 16:10:16.200  6736  6814 W jxcore-log: 
,09-13 16:10:16.610  6736  6814 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:10:16.610  6736  6814 I jxcore-log: 
09-13 16:10:16.611  6736  6814 W jxcore-log: JXcore engine is started
,09-13 16:10:16.619  6736  6811 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 16:10:16.622  6736  6736 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:10:32.533  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:10:32.533  6736  6814 I jxcore-log: 
,09-13 16:10:32.535  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:10:32.535  6736  6814 I jxcore-log: 
,09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:32.539  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:32.541  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:32.544  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:10:32.544  6736  6814 I jxcore-log: 
09-13 16:10:32.545  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:10:32.545  6736  6814 I jxcore-log: 
09-13 16:10:33.054  6736  6814 I jxcore-log: Unit Test app is loaded
09-13 16:10:33.054  6736  6814 I jxcore-log: 
,09-13 16:10:33.063  6736  6736 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 16:10:33.073  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:33.073  6736  6814 I jxcore-log: 
,09-13 16:10:33.084  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:10:33.084  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@defc16f added. We now have 2 listener(s)
,09-13 16:10:33.085  1037  1710 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:33.087  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:10:33.087  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:10:33.087  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:10:33.088  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:10:33.088  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6df5e7c added. We now have 2 listener(s)
09-13 16:10:33.088  6736  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:10:33.088  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:10:33.090  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:33.092  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:33.093  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:33.093  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:10:33.094  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:33.095  6736  6814 D ExecuteNativeTests: Running unit tests
09-13 16:10:33.095  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:33.096  6736  6814 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 16:10:33.097  1037  2064 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:33.097  1037  2064 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:33.097  1037  2064 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:33.099  6736  6814 I System.out: Running UT
09-13 16:10:43.259  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:10:43.259  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a added. We now have 3 listener(s)
,09-13 16:10:43.263  1037  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:43.265  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:10:43.266  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:10:43.266  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:10:43.266  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:10:43.266  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b added. We now have 3 listener(s)
09-13 16:10:43.266  6736  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:10:43.266  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:10:43.270  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:43.273  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:10:43.277  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.277  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:10:43.279  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.281  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.288  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:10:43.293  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.293  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.293  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.297  6736  6814 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 16:10:43.298  6736  6814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:10:43.298  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:10:43.298  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.298  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.298  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.299  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.299  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.300  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.300  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:10:43.300  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a removed from the list
09-13 16:10:43.300  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.300  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b removed from the list
09-13 16:10:43.300  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.300  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:10:43.309  6736  6814 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 16:10:43.310  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.310  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.310  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.310  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.310  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.310  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.310  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.310  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.310  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:10:43.317  6736  6814 D io.jxcore.node.ConnectionMode,l: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:10:43.319  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.319  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.319  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:10:43.319  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.319  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.319  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.319  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.319  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:10:43.319  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.320  6736  6814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 16:10:43.330  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:43.333  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:10:43.336  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.337  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:10:43.339  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.340  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.341  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:10:43.342  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:10:43.342  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:10:43.342  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.342  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:10:43.346  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:10:43.349  1037  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:43.355  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:10:43.362  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:10:43.366  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 16:10:43.368  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:10:43.369  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.371  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:10:43.372  6736  6814 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:10:43.374  6736  6814 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 16:10:43.375  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:10:43.375  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 16:10:43.379  6736  6814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:10:43.379  6736  6814 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:10:43.379  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:10:43.379  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:10:43.379  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:10:43.379  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.379  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:10:43.384  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:10:43.385  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.386  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 16:10:43.388  6736  6814 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:10:43.389  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.389  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.389  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.389  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.389  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.389  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.389  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.389  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.391  6736  6814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:10:43.393  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:43.397  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:43.398  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.399  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:10:43.403  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.405  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.405  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:10:43.405  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:10:43.405  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:10:43.405  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.405  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:10:43.410  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:10:43.412  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.414  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:10:43.414  6736  6814 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:10:43.415  6736  6814 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 16:10:43.415  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:10:43.415  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 16:10:43.417  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.417  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.417  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.417  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.417  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.418  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.418  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.418  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.419  6736  6814 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 16:10:43.420  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.420  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.420  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.420  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.420  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.420  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.420  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.420  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.420  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.421  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:10:43.421  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.421  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.421  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.421  6736  6814 E org.thaliproject.p2p.btconnectorl,ib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.421  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.421  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.421  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.422  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.422  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.422  6736  6814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:10:43.422  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.423  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.423  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.423  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.423  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.423  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.423  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.423  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.423  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.424  6736  6814 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:10:43.424  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.424  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.424  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.424  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.424  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.424  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.424  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.424  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.424  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.425  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:10:43.428  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.428  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.428  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:10:43.429  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.429  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.429  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:10:43.429  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.429  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:10:43.429  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.429  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.429  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.429  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.429  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.429  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.429  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.429  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.429  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.430  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:10:43.430  6736  6814 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:10:43.442  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:10:43.446  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:10:43.447  6736  6814 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:10:43.450  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:10:43.451  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:10:43.451  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:10:43.451  6736  6814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:10:43.453  6736  6814 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:10:43.453  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:10:43.453  6736  6814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:10:43.455  6736  6814 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:10:43.455  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:10:43.455  6736  6814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:10:43.455  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:10:43.462  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 16:10:43.465  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:10:43.465  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 16:10:43.467  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:10:43.467  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:10:43.467  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:10:43.479  6736  6814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:10:43.479  6736  6814 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:10:43.479  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.479  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.479  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.479  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 16:10:43.480  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.480  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.480  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.480  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.480  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.480  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.481  6736  6814 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:10:43.482  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.482  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.482  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.482  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.482  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.482  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.482  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.482  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.482  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.483  6736  6814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:10:43.483  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.484  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.484  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.484  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.484  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.484  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.484  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.484  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.484  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.485  6736  6814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:10:43.485  6736  6814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:10:43.485  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:10:43.485  6736  6814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:10:43.485  6736  6814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:10:43.485  6736  6814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:10:43.485  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:10:43.485  6736  6814 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:10:43.486  6736  6814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:10:43.486  6736  6814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:10:43.486  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:10:43.486  6736  6814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:10:43.486  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.486  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.486  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.486  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.486  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.486  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.486  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.486  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.486  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.487  6736  6814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:10:43.489  6736  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 875
09-13 16:10:43.490  6736  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 875)
09-13 16:10:43.490  6736  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 875)
09-13 16:10:43.492  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:43.497  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:43.499  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.499  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:10:43.499  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:10:43.499  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:10:43.499  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:10:43.499  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.499  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:10:43.502  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.504  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:43.507  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:10:43.507  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.510  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:10:43.511  6736  6814 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:10:43.511  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.511  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.511  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:43.511  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.511  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.511  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.511  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.511  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.513  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.513  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.513  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.513  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.513  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.513  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.513  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.513  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.514  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.516  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:10:43.516  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:43.517  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:10:43.518  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:10:43.518  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:10:43.519  6736  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:10:43.519  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:10:43.519  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:10:43.520  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.521  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:10:43.521  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:10:43.521  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:10:43.521  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.521  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:10:43.521  6736  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:10:43.522  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.522  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.522  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:10:43.522  6736  6814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:10:43.522  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:10:43.523  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:10:43.525  6736  6814 D BluetoothLeScanner: could not find callback wrapper
09-13 16:10:43.525  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:10:43.525  6736  6814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:10:43.525  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.525  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.527  6736  6851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:10:43.527  6736  6851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:10:43.529  6736  6814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:10:43.529  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:10:43.529  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.529  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.529  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.529  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:10:43.529  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.530  6736  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:10:43.530  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:10:43.531  6736  6814 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 16:10:43.531  6736  6814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:10:43.531  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:10:43.533  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.534  6736  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:10:43.534  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.534  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.534  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.534  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.534  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.534  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.534  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.534  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.534  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.537  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:43.538  1037  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:43.539  1037  2064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:43.539  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:10:43.540  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.540  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.540  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.540  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.540  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.540  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.540  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.540  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.541  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:43.541  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.541  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.541  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b630a not in the list
09-13 16:10:43.541  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:43.541  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2902677b not in the list
09-13 16:10:43.541  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:43.541  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:43.541  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:43.543  6736  6814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:10:43.543  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:10:43.544  6736  6814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 16:10:43.544  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:10:43.544  6736  6814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:10:43.544  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:10:43.546  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:10:43.546  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 16:10:43.547  6736  6814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 16:10:43.547  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:10:43.547  6736  6814 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an in,coming connection thread with ID 1
09-13 16:10:43.548  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:10:43.548  6736  6814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:10:43.548  6736  6814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:10:43.551  6736  6814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 16:10:43.551  6736  6814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 16:10:43.552  6736  6814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:10:43.552  6736  6814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:10:43.552  6736  6814 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:10:43.552  6736  6814 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 16:10:43.553  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:10:43.554  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b970229 added. We now have 3 listener(s)
09-13 16:10:43.554  1037  2096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:43.556  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:10:43.556  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:10:43.556  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:10:43.557  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:10:43.557  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16aa99ae added. We now have 3 listener(s)
09-13 16:10:43.557  6736  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:10:43.557  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:10:43.561  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:43.567  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:43.569  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:43.569  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:10:43.573  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.575  6736  6814 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:10:43.576  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:43.577  1037  1710 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:43.578  1037  1710 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:43.578  1037  1710 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:43.596  1037  1779 D WifiServiceImplEx: setWifiEnabled: false pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:43.596  1037  1779 D WifiService: setWifiEnabled: false pid=6736, uid=10118
09-13 16:10:43.596  1037  1779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:10:43.614  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:43.615  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:43.615  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-13 16:10:43.615  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:43.617  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:43.618  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:43.619  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:43.620  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:43.620  1037  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 16:10:43.621  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:10:43.621  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 16:10:43.622  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 16:10:43.622  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 16:10:43.632  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 16:10:43.633  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.633  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.633  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 16:10:43.634  2715  2715 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 16:10:43.634  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 16:10:43.634  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:43.635  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
,09-13 16:10:43.636  1037  2861 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.648   313   897 D CommandListener: Clearing all IP addresses on wlan0
,09-13 16:10:43.700  1037  1979 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-13 16:10:43.701  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 16:10:43.702  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
09-13 16:10:43.702  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-13 16:10:43.705  1037  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.705  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.705  1037  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@376d4e6e
09-13 16:10:43.706  1037  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 16:10:43.707  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:43.707  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:43.707  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.707  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-13 16:10:43.707  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.711  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 16:10:43.711  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.712  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-13 16:10:43.714  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:43.720  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 16:10:43.723  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.723  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.724  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-13 16:10:43.732  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-13 16:10:43.733  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.733  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.733  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:10:43.734  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 16:10:43.734  1037  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.734  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-13 16:10:43.735  1037  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.740  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:43.740  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 16:10:43.741  1037  1539 D LGWifiP2pService: P2pDisablingState
09-13 16:10:43.741  1037  1539 D LGWifiP2pService: P2pDisablingState{ when=-36ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.742  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:43.744  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 16:10:43.744  1969  1969 D WfdsService: WifiP2pState is changed : false
09-13 16:10:43.744  1969  2310 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 16:10:43.744  1969  2310 D WfdsService: Set the WFDS Monitor: false
09-13 16:10:43.745  1969  2310 D WfdsMonitor: WFDS Monitor is stopped
09-13 16:10:43.745  1969  2310 D WfdsService: STATE : WfdsDisabledState - enter
09-13 16:10:43.746  1969  2772 D CtrlSupplicant: Received on exit socket, terminate
09-13 16:10:43.746  1969  2772 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 16:10:43.746  1969  2772 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 16:10:43.746  1969  2772 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 16:10:43.747  1969  2310 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 16:10:43.747  1969  2313 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 16:10:43.748  1037  1539 D LGWifiP2pService: p2p socket connection lost
09-13 16:10:43.749  1037  1539 D LGWifiP2pService: P2pDisabledState
09-13 16:10:43.749  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 16:10:43.750  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 16:10:43.750  2715  2715 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 16:10:43.750  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.750  1037  1539 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.750  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 16:10:43.750  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:43.751  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:43.757  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:43.779   313   897 D CommandListener: Clearing all IP addresses on wlan0
,09-13 16:10:43.780   313  6862 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 16:10:43.780  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 16:10:43.781  1037  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 16:10:43.781  1037  1547 D DSQN    : disableDataServiceNotify
09-13 16:10:43.781  1037  1547 D DSQN    : stop dsqn bin
,09-13 16:10:43.782  1037  1097 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 16:10:43.786  1037  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 16:10:43.786  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:43.786  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:43.786  1037  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:43.786  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 16:10:43.787  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.787  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 16:10:43.787  1037  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 16:10:43.787  1037  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 16:10:43.787  1037  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 16:10:43.787  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:10:43.788  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-13 16:10:43.800  1037  1950 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6863 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 16:10:43.802  1037  1540 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 16:10:43.803  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 16:10:43.803  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:43.804  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-13 16:10:43.804  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:43.806  1037  1540 D WifiNative-p2p0: TERMINATE: returned true
09-13 16:10:43.806  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:43.806  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:43.806  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:43.807  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.807  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.807  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:10:43.807  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:43.807  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:10:43.809  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 16:10:43.809  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 16:10:43.809  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 16:10:43.809  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 16:10:43.809  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 16:10:43.809  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:43.810  1037  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:43.810  1037  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:43.810  1037  1547 D NetworkManagementService: Removing idletimer
09-13 16:10:43.810  1037  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:43.813  1037  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:43.813  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 16:10:43.814  1880  1880 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:43.814  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 16:10:43.815  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 16:10:43.816  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 16:10:43.817  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 16:10:43.817  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 16:10:43.817  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 16:10:43.820  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 16:10:43.825  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,09-13 16:10:43.825  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:43.826  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:43.832  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:43.837  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:43.841  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:10:43.844  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:43.847  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:43.849  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:43.856  1037  2861 D DhcpStateMachine: StoppedState
,09-13 16:10:43.856  1037  2861 D DhcpStateMachine: StoppedState{ when=-105ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:43.857  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 16:10:43.858  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:43.859  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:43.860  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:43.860  1037  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-13 16:10:43.910  2715  2715 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-13 16:10:43.910  2715  2715 I wpa_supplicant: monitor socket send errors count : 1
09-13 16:10:43.910  2715  2715 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
09-13 16:10:43.912  1037  2771 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 16:10:43.912  1037  2771 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 16:10:43.950  2715  2715 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 16:10:43.951  1037  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 16:10:43.952  2715  2715 W wpa_supplicant: USIM:  scard_deinit function
09-13 16:10:43.952  1037  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 16:10:43.952  1037  2771 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 16:10:43.952  1037  2771 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 16:10:43.953  1037  1099 D Tethering: InitialState.processMessage what=4
09-13 16:10:43.954  1037  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197033
09-13 16:10:43.955  1037  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197034
09-13 16:10:43.953  1037  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:43.956  1037  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:43.959  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=197037  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 16:10:43.961  1037  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=197039  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 16:10:43.982  1037  1720 I art     : Explicit concurrent mark sweep GC freed 54508(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.979ms total 112.756ms
,09-13 16:10:43.987  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 16:10:43.989  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:43.990  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 16:10:44.013  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:44.014  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:44.014  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:44.014  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:44.030  6736  6736 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:10:44.069  2715  2715 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 16:10:44.069  1037  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 16:10:44.069  1037  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 16:10:44.069  1037  2771 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-13 16:10:44.070  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-13 16:10:44.085  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-13 16:10:44.090  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:44.090  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:44.121  6736  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:44.142  1037  2087 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6891 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 16:10:44.144  1037  2087 I ActivityManager: Killing 6285:com.android.calendar/u0a13 (adj 15): empty #17
,09-13 16:10:44.210  1037  1979 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:44.211  1037  1595 W libprocessgroup: failed to open /acct/uid_10013/pid_6285/cgroup.procs: No such file or directory
09-13 16:10:44.212  1037  1979 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:44.212  1037  1979 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:10:44.224  1037  1540 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 16:10:44.224  1969  1969 D WfdsService: Supplicant Connection state is changed : false
09-13 16:10:44.224  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:44.224  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:44.224  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:44.224  1969  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 16:10:44.224  1969  2310 D WfdsService: Set the WFDS Monitor: false
09-13 16:10:44.224  1969  2310 D WfdsMonitor: WFDS Monitor is stopped
,09-13 16:10:44.230  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 16:10:44.231  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:44.238  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:44.239  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:44.240  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 16:10:44.241  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:44.242  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:44.242  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-13 16:10:44.242  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 16:10:44.242  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 16:10:44.243  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:44.244  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:44.250  6891  6891 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:10:44.251  6891  6891 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 16:10:44.251  6891  6891 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:10:44.251  6891  6891 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 16:10:44.253  6891  6891 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 16:10:44.254  6891  6891 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 16:10:44.403  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:44.427  1037  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 16:10:44.427  1037  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-13 16:10:44.435  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 16:10:44.435  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 16:10:44.435  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 16:10:44.435  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 16:10:44.435  1037  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 16:10:44.435  1037  1540 E WifiHW  : unknown target_country: EU , set to default
09-13 16:10:44.435  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 16:10:44.435  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 16:10:44.435  1037  1540 I WifiUtil: gEnableBmps=1
09-13 16:10:44.445  6891  6891 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:44.445  6891  6891 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 16:10:44.456  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:44.557  1037  2016 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6913 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 16:10:44.559  1037  2016 I ActivityManager: Killing 6239:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 16:10:44.577   349   349 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 27.173ms
,09-13 16:10:44.598   349   349 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 19.120ms
,09-13 16:10:44.616   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 16.746ms
,09-13 16:10:44.622  1037  2096 W libprocessgroup: failed to open /acct/uid_10014/pid_6239/cgroup.procs: No such file or directory
09-13 16:10:44.646  6913  6913 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 16:10:44.685  6913  6913 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 16:10:44.738  6913  6913 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-13 16:10:44.738  6913  6913 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 16:10:44.739  6913  6913 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 16:10:44.739  6913  6913 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 16:10:44.740  6913  6913 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 16:10:44.742  6913  6913 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 16:10:44.745  1037  1934 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:44.747  1037  1934 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:44.747  1037  1934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:44.748  6913  6913 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-13 16:10:44.749  1037  1546 D WifiController: Mismatch in the state 1
09-13 16:10:44.756  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 16:10:44.762  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 16:10:44.792  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:44.797  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:44.797  6913  6913 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 16:10:44.803  6913  6913 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 16:10:44.804  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 16:10:44.804  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:44.804  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:44.811  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:44.821  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:44.829  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 16:10:44.829  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:44.832  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:44.835  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:44.839  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 16:10:44.839  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:44.839  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:44.844  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:44.855  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:44.866  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:44.866  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:44.868  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 16:10:44.928  1037  1993 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6933 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 16:10:45.069  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 16:10:45.074  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 16:10:45.081  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:45.110  6933  6958 W FormManager: Network not available. Please check & try again.
09-13 16:10:45.111  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:45.112  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:45.112  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:45.112  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:45.113  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-13 16:10:45.126  6933  6959 V FormManager: Network unavailable.
,09-13 16:10:45.129  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 16:10:45.129  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 16:10:45.130  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 16:10:45.130  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:45.130  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:45.130  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:45.135  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:45.135  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:45.136  6933  6959 V FormManager: Network unavailable.
09-13 16:10:45.138  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:45.140  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:45.149  6863  6863 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 16:10:45.149  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:45.149  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:45.152  4333  6963 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:45.152  4333  6963 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:45.153  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 16:10:45.156  4333  6962 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 16:10:45.168  6933  6964 W FormManager: Network not available. Please check & try again.
09-13 16:10:45.169  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 16:10:45.169  1037  1099 D Tethering: InitialState.processMessage what=4
09-13 16:10:45.170  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 16:10:45.176   313   897 D SoftapController: Softap fwReload - Ok
09-13 16:10:45.178  1037  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (733ms)
,09-13 16:10:45.181   313   897 D CommandListener: Setting iface cfg
09-13 16:10:45.181   313   897 D CommandListener: Trying to bring down wlan0
09-13 16:10:45.181   313   897 D CommandListener: Clearing all IP addresses on wlan0
09-13 16:10:45.183  1037  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 16:10:45.184  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:45.196  6967  6967 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:45.196  6967  6967 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:45.203  6913  6913 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 16:10:45.204  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 16:10:45.204  6913  6913 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 16:10:45.209  6933  6965 V FormManager: Network unavailable.
09-13 16:10:45.211  6933  6965 V FormManager: Network unavailable.
09-13 16:10:45.220  1037  2087 I ActivityManager: Killing 6358:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 16:10:45.223  6967  6967 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 16:10:45.259  6913  6913 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:45.260  6913  6913 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 16:10:45.264  6967  6967 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 16:10:45.265  6967  6967 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 16:10:45.267  6913  6913 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 16:10:45.268  6913  6913 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 16:10:45.268  6913  6913 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
09-13 16:10:45.268  6913  6913 V SoundPool: doLoad: loading sample sampleID=1
09-13 16:10:45.269  6913  6913 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 16:10:45.270  6913  6975 V SoundPool: Start decode
09-13 16:10:45.270  6913  6975 V MediaPlayer[Native]: decode(32, 10857164, 17813)
09-13 16:10:45.270   317  1387 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 16:10:45.270   317  1387 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 16:10:45.270   317  1387 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 16:10:45.270   317  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 16:10:45.270   317  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 16:10:45.270   317  1387 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 16:10:45.270   317  1387 V MediaPlayerService: player type = 3
09-13 16:10:45.270   317  1387 V AwesomePlayer: AwesomePlayer create()
09-13 16:10:45.271   317  1387 V AwesomePlayer: reset_l() 
09-13 16:10:45.271   317  1387 V AwesomePlayer: cancelPlayerEvents
09-13 16:10:45.271   317  1387 V AwesomePlayer: setAudioSink() 
09-13 16:10:45.271   317  1387 V AwesomePlayer: reset_l() 
09-13 16:10:45.271   317  1387 V AudioCache: notify(0xb57bf0c0, 8, 0, 0)
09-13 16:10:45.271   317  1387 V AudioCache: ignored
09-13 16:10:45.271   317  1387 V AwesomePlayer: cancelPlayerEvents
09-13 16:10:45.271   317  1387 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 16:10:45.271   317  1387 V AwesomePlayer: setDataSource_l dataSource
09-13 16:10:45.271   317  1387 V LGParserOSAL: SniffLGParser start
09-13 16:10:45.271   317  1387 V LGParserOSAL: MainType:5, SubType=0
09-13 16:10:45.271   317  1387 V LGParserOSAL: #### check Mime : application/ogg
09-13 16:10:45.271   317  1387 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 16:10:45.271   317  1387 E MediaExtractor: Use LGExtractor :application/ogg 
,09-13 16:10:45.286  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:45.286  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:45.286  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:45.308  1037  1595 W libprocessgroup: failed to open /acct/uid_10004/pid_6358/cgroup.procs: No such file or directory
,09-13 16:10:45.311  1037  2096 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:45.311  1037  2096 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:45.311  1037  2096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:45.312   317  1387 V LGParserOSAL: supported mime: application/ogg
09-13 16:10:45.312   317  1387 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 16:10:45.312   317  1387 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 16:10:45.312   317  1387 V AwesomePlayer: mBitrate = -1 bits/sec
,09-13 16:10:45.312   317  1387 V AwesomePlayer: AudioTrack Setting
09-13 16:10:45.312   317  1387 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 16:10:45.312   317  1387 V AwesomePlayer: setAudioSource() 
09-13 16:10:45.312   317  1387 V MediaPlayerService: prepare
09-13 16:10:45.312   317  1387 V AwesomePlayer: prepareAsync_l() 
09-13 16:10:45.313   317  1387 V MediaPlayerService: wait for prepare
09-13 16:10:45.313   317  6976 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 16:10:45.313   317  6976 V AwesomePlayer: initAudioDecoder() 
09-13 16:10:45.313   317  6976 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 16:10:45.313   317  6976 V AudioSystem: isOffloadSupported()
,09-13 16:10:45.313   317  6976 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 16:10:45.313   317  6976 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 16:10:45.314   317  6976 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 16:10:45.314   317  6976 V AwesomePlayer: getUseOffload() = 0 
09-13 16:10:45.314   317  6976 V OMXCodec: OMXCodec::Create
09-13 16:10:45.314   317  6976 V OMXCodec: findMatchingCodecs()
09-13 16:10:45.314   317  6976 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 16:10:45.314   317  6976 V OMXCodec: matchingCodecs.size()=1
09-13 16:10:45.314   317  6976 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 16:10:45.320   317  6976 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 16:10:45.320   317  6976 V LGCodecAdapter: LG Codec Adapter start
09-13 16:10:45.320   317  6976 V OMXCodec: OMXCodec Createtor
09-13 16:10:45.320   317  6976 V OMXCodec: setComponentRole
09-13 16:10:45.320   317  6976 V OMXCodec: configureCodec protected=0
09-13 16:10:45.320   317  6976 V LGCodecAdapter: called getLGCodecSpecificData
09-13 16:10:45.320   317  6976 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 16:10:45.320   317  6976 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 16:10:45.320   317  6976 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 16:10:45.321   317  6976 V LGCodecOSAL: Not support LGCodec
09-13 16:10:45.321   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 16:10:45.321   317  6976 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 16:10:45.321   317  6976 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 16:10:45.321   317  6976 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 16:10:45.321   317  6976 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 16:10:45.321   317  6976 V AudioSystem: isOffloadSupported()
,09-13 16:10:45.321   317  6976 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 16:10:45.321   317  6976 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 16:10:45.321   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 16:10:45.321   317  6976 V OMXCodec: init()
09-13 16:10:45.321   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 16:10:45.321   317  6976 V OMXCodec: allocateBuffers
09-13 16:10:45.322   317  6976 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 16:10:45.322   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 16:10:45.322   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1436150 on input port
09-13 16:10:45.322   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14361f0 on input port
09-13 16:10:45.322   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1436240 on input port
09-13 16:10:45.322   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14362e0 on input port
09-13 16:10:45.322   317  6976 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 16:10:45.323   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 16:10:45.323   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15430b0 on output port
09-13 16:10:45.323   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543790 on output port
09-13 16:10:45.323   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15437e0 on output port
09-13 16:10:45.323   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15438d0 on output port
09-13 16:10:45.323   317  6976 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 16:10:45.323   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 16:10:45.323   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 16:10:45.323   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 16:10:45.323   317  6976 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 16:10:45.323   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 16:10:45.323   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 16:10:45.323   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 16:10:45.323   317  6976 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 16:10:45.323   317  6976 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 16:10:45.324   317  6976 V AudioCache: notify(0xb57bf0c0, 5, 0, 0)
09-13 16:10:45.324   317  6976 V AudioCache: ignored
09-13 16:10:45.324   317  6976 V AudioCache: notify(0xb57bf0c0, 1, 0, 0)
09-13 16:10:45.324   317  6976 V AudioCache: prepared
09-13 16:10:45.324   317  1387 V AudioCache: wait - success
09-13 16:10:45.324   317  1387 V MediaPlayerService: start
09-13 16:10:45.324   317  1387 V AwesomePlayer: play_l() 
09-13 16:10:45.324   317  1387 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 16:10:45.324   317  1387 V AwesomePlayer: createAudioPlayer_l
09-13 16:10:45.324   317  1387 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 16:10:45.324   317  1387 V AwesomePlayer: startAudioPlayer_l() 
09-13 16:10:45.324   317  1387 D AudioPlayer: start of Playback, useOffload 0
09-13 16:10:45.324   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 16:10:45.324   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.v,orbis.decoder] setState mState=4 , newState=7
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975084720
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975086480
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975086560
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975086800
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 16:10:45.326   317  6978 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15437e0 on output port
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1543790 on output port
09-13 16:10:45.326   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15430b0 on output port
09-13 16:10:45.327   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on output port
09-13 16:10:45.327   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 16:10:45.327   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 16:10:45.327   317  1387 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 16:10:45.327   317  1387 V AudioCache: notify(0xb57bf0c0, 6, 0, 0)
09-13 16:10:45.327   317  1387 V AudioCache: ignored
09-13 16:10:45.327   317  1387 V MediaPlayerService: wait for playback complete
09-13 16:10:45.328   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.328   317  6979 V AudioCache: memcpy(0xac100000, 0xb57ff000, 4096)
09-13 16:10:45.329   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.329   317  6979 V AudioCache: memcpy(0xac101000, 0xb57ff000, 4096)
09-13 16:10:45.329   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.329   317  6979 V AudioCache: memcpy(0xac102000, 0xb57ff000, 4096)
09-13 16:10:45.330   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.330   317  6979 V AudioCache: memcpy(0xac103000, 0xb57ff000, 4096)
09-13 16:10:45.330   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.330   317  6979 V AudioCache: memcpy(0xac104000, 0xb57ff000, 4096)
09-13 16:10:45.330   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.330   317  6979 V AudioCache: memcpy(0xac105000, 0xb57ff000, 4096)
09-13 16:10:45.331   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.331   317  6979 V AudioCache: memcpy(0xac106000, 0xb57ff000, 4096)
09-13 16:10:45.331   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.331   317  6979 V AudioCache: memcpy(0xac107000, 0xb57ff000, 409,6)
09-13 16:10:45.332   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.332   317  6979 V AudioCache: memcpy(0xac108000, 0xb57ff000, 4096)
09-13 16:10:45.332   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.332   317  6979 V AudioCache: memcpy(0xac109000, 0xb57ff000, 4096)
09-13 16:10:45.333   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.333   317  6979 V AudioCache: memcpy(0xac10a000, 0xb57ff000, 4096)
09-13 16:10:45.333   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.333   317  6979 V AudioCache: memcpy(0xac10b000, 0xb57ff000, 4096)
09-13 16:10:45.334   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.334   317  6979 V AudioCache: memcpy(0xac10c000, 0xb57ff000, 4096)
09-13 16:10:45.334   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.334   317  6979 V AudioCache: memcpy(0xac10d000, 0xb57ff000, 4096)
09-13 16:10:45.334   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.334   317  6979 V AudioCache: memcpy(0xac10e000, 0xb57ff000, 4096)
09-13 16:10:45.335   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.335   317  6979 V AudioCache: memcpy(0xac10f000, 0xb57ff000, 4096)
09-13 16:10:45.335   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.335   317  6979 V AudioCache: memcpy(0xac110000, 0xb57ff000, 4096)
09-13 16:10:45.336   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.336   317  6979 V AudioCache: memcpy(0xac111000, 0xb57ff000, 4096)
09-13 16:10:45.336   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.336   317  6979 V AudioCache: memcpy(0xac112000, 0xb57ff000, 4096)
09-13 16:10:45.336   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.336   317  6979 V AudioCache: memcpy(0xac113000, 0xb57ff000, 4096)
09-13 16:10:45.337   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.337   317  6979 V AudioCache: memcpy(0xac114000, 0xb57ff000, 4096)
09-13 16:10:45.337   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.337   317  6979 V AudioCache: memcpy(0xac115000, 0xb57ff000, 4096)
09-13 16:10:45.343   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.343   317  6979 V AudioCache: memcpy(0xac116000, 0xb57ff000, 4096)
09-13 16:10:45.343   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.343   317  6979 V AudioCache: memcpy(0xac117000, 0xb57ff000, 4096)
09-13 16:10:45.344   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.344   317  6979 V AudioCache: memcpy(0xac118000, 0xb57ff000, 4096)
09-13 16:10:45.344   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.344   317  6979 V AudioCache: memcpy(0xac119000, 0xb57ff000, 4096)
09-13 16:10:45.344   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.344   317  6979 V AudioCache: memcpy(0xac11a000, 0xb57ff000, 4096)
09-13 16:10:45.346   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.346   317  6979 V AudioCache: memcpy(0xac11b000, 0xb57ff000, 4096)
09-13 16:10:45.347  6967  6967 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 16:10:45.348   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.348   317  6979 V AudioCache: memcpy(0xac11c000, 0xb57ff000, 4096)
09-13 16:10:45.352   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: memcpy(0xac11d000, 0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: memcpy(0xac11e000, 0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: memcpy(0xac11f000, 0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.353   317  6979 V AudioCache: memcpy(0xac120000, 0xb57ff000, 4096)
09-13 16:10:45.355   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.355   317  6979 V AudioCache: memcpy(0xac121000, 0xb57ff000, 4096)
09-13 16:10:45.356   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.356   317  6979 V AudioCache: memcpy(0xac122000, 0xb57ff000, 4096)
09-13 16:10:45.357   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.357   317  6979 V AudioCache: memcpy(0xac123000, 0xb57ff000, 4096)
09-13 16:10:45.358   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.358   317  6979 V AudioCache: memcpy(0xac124000, 0xb57ff000, 4096)
09-13 16:10:45.359   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.359   317  6979 V AudioCache: memcpy(0xac125000, 0xb57ff000, 4096)
09-13 16:10:45.359   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.359   317  6979 V AudioCache: memcpy(0xac126000, 0xb57ff000, 4096)
09-13 16:10:45.359   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.359   317  6979 V AudioCache: memcpy(0xac127000, 0xb57ff000, 4096)
09-13 16:10:45.360   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.360   317  6979 V AudioCache: memcpy(0xac128000, 0xb57ff000, 4096)
09-13 16:10:45.360   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.360   317  6979 V AudioCache: memcpy(0xac129000, 0xb57ff000, 4096)
09-13 16:10:45.360   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.360   317  6979 V AudioCache: memcpy(0xac12a000, 0xb57ff000, 4096)
09-13 16:10:45.361   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.361   317  6979 V AudioCache: memcpy(0xac12b000, 0xb57ff000, 4096)
09-13 16:10:45.361   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.361   317  6979 V AudioCache: memcpy(0xac12c000, 0xb57ff000, 4096)
09-13 16:10:45.362   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.362   317  6979 V AudioCache: memcpy(0xac12d000, 0xb57ff000, 4096)
09-13 16:10:45.363   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.363   317  6979 V AudioCache: memcpy(0xac12e000, 0xb57ff000, 4096)
09-13 16:10:45.363   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.363   317  6979 V AudioCache: memcpy(0xac12f000, 0xb57ff000, 4096)
09-13 16:10:45.364   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.364   317  6979 V AudioCache: memcpy(0xac130000, 0xb57ff000, 4096)
09-13 16:10:45.364   317  6979 V AudioCache: write(0xb57ff000, 4096)
09-13 16:10:45.364   317  6979 V AudioCache: memcpy(0xac131000, 0xb57ff000, 4096)
09-13 16:10:45.365   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 16:10:45.365   317  6979 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 16:10:45.365   317  6979 V AwesomePlayer: postAudioEOS() 
09-13 16:10:45.365   317  6979 V AudioCache: write(0xb57ff000, 280)
09-13 16:10:45.365   317  6979 V AudioCache: memcpy(0xac132000, 0xb57ff000, 280)
09-13 16:10:45.365  1037  1710 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6980 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 16:10:45.366  1037  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 16:10:45.366  1037  1540 D WifiMonitor: connecting to supplicant
09-13 16:10:45.366   317  6976 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 16:10:45.366   317  6976 V AwesomePlayer: onStreamDone
09-13 16:10:45.366   317  6976 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 16:10:45.366   317  6976 V AudioCache: notify(0xb57bf0c0, 2, 0, 0)
09-13 16:10:45.366   317  6976 V AudioCache: playback complete
09-13 16:10:45.366   317  6976 V AwesomePlayer: pause_l() 
09-13 16:10:45.366   317  6976 V AudioCache: notify(0xb57bf0c0, 7, 0, 0)
09-13 16:10:45.366   317  6976 V AudioCache: ignored
09-13 16:10:45.366   317  6976 V AwesomePlayer: cancelPlayerEvents
09-13 16:10:45.366   317  1387 V AudioCache: wait - success
09-13 16:10:45.366   317  1387 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 16:10:45.367   317  6976 D AudioPlayer: Pause Playback at 1068125
09-13 16:10:45.367   317  1387 V AwesomePlayer: reset_l() 
09-13 16:10:45.367   317  1387 V AudioCache: notify(0xb57bf0c0, 8, 0, 0)
09-13 16:10:45.367   317  1387 V AudioCache: ignored
09-13 16:10:45.367   317  1387 V AwesomePlayer: cancelPlayerEvents
09-13 16:10:45.367   317  1387 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 16:10:45.367   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 16:10:45.367   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 16:10:45.367   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 16:10:45.367   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 16:10:45.368  6913  6913 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14362e0 on port 0
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1436240 on port 0
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14361f0 on port 0
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1436150 on port 0
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 1
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15430b0 on port 1
09-13 16:10:45.368   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1543790 on port 1
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15437e0 on port 1
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 16:10:45.369   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 16:10:45.369   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 16:10:45.369   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 16:10:45.369   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 16:10:45.369   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 16:10:45.369   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 16:10:45.370   317  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 16:10:45.370   317  1387 D AudioPlayer: AudioPlayer releasing audio source
09-13 16:10:45.370   317  1387 D AudioPlayer: AudioPlayer done releasing audio source
09-13 16:10:45.370   317  1387 V AwesomePlayer: reset_l() 
09-13 16:10:45.370   317  1387 V AwesomePlayer: cancelPlayerEvents
09-13 16:10:45.370   317  1387 V AwesomePlayer: ~AwesomePlayer call
09-13 16:10:45.370  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:45.370  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 16:10:45.370   317  1387 V AwesomePlayer: reset_l() 
09-13 16:10:45.370   317  1387 V AwesomePlayer: cancelPlayerEvents
09-13 16:10:45.371  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 16:10:45.371  6913  6975 V SoundPool: close(32)
09-13 16:10:45.371  6913  6975 V SoundPool: pointer = 0xa0033000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 16:10:45.374  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:45.376  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:45.376  6913  6913 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 16:10:45.376  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 16:10:45.377  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:45.389  6913  6913 V LGMDMManager: Create singleton instance
,09-13 16:10:45.409  6967  6967 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-13 16:10:45.413  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-13 16:10:45.414  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 16:10:45.414  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 16:10:45.414  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 16:10:45.414  1037  6997 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 16:10:45.414  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,09-13 16:10:45.414  1037  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 16:10:45.415  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 16:10:45.415  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:45.415  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:45.416  1037  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 16:10:45.416  1037  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 16:10:45.416  1037  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 16:10:45.416  1037  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 16:10:45.416  1037  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 16:10:45.417  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:45.417  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:45.417  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:45.417  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.417  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.417  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.417  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.417  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:10:45.420  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 16:10:45.420  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 16:10:45.420  6967  6967 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 16:10:45.420  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,09-13 16:10:45.420  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 16:10:45.420  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 16:10:45.420  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 16:10:45.420  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 16:10:45.421  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 16:10:45.421  1969  1969 D WfdService: Waiting for WifiP2p enabling
09-13 16:10:45.421  1037  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 16:10:45.421  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:45.421  1037  1540 D WifiNative-wlan0: SET update_config 1: returned true
09-13 16:10:45.421  1037  1540 D WifiConfigStore: Loading config and enabling all networks 
09-13 16:10:45.421  1037  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 16:10:45.422  1037  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:45.424  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:45.425  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:45.428  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:45.430  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:45.433  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:45.434  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:45.434  1037  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 16:10:45.437  6980  6980 D UEI.SmartControl: Quickset Services start...
09-13 16:10:45.438  6980  6980 I UEI.SmartControl: Manufacture = LGE
09-13 16:10:45.438  6980  6980 D UEI.SmartControl: Id = LGNevo
09-13 16:10:45.439  6980  6980 D UEI.SmartControl: File observer start...
09-13 16:10:45.439  6980  6980 E UEI.SmartControl: IR Port is disabled: false
09-13 16:10:45.439  6980  6980 D UEI.SmartControl: Starting file observer...
09-13 16:10:45.440  6980  6980 D UEI.SmartControl: Extracting JNI libs...
09-13 16:10:45.440  6980  6980 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-13 16:10:45.440  1037  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 16:10:45.441  1037  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 16:10:45.442  1037  1540 D WifiStateMachine: enableVerboseLogging : level 2
09-13 16:10:45.442  1037  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 16:10:45.442  1037  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 16:10:45.442  1037  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 16:10:45.442  1037  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 16:10:45.442  1037  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 16:10:45.443  1037  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 16:10:45.444  1037  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 16:10:45.444  1037  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 16:10:45.445  1969  1969 D WfdsService: Supplicant Connection state is changed : true
09-13 16:10:45.445  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 16:10:45.445  1037  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 16:10:45.445  1969  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 16:10:45.445  1969  2310 D WfdsService: Set the WFDS Monitor: true
09-13 16:10:45.445  1969  2310 D WfdsMonitor: WfdsMonitorThread create
09-13 16:10:45.445  1969  2310 D WfdsMonitor: WFDS Monitor is created and started
09-13 16:10:45.445  1969,  2310 D WfdsService: WiFi: Supplicant connection re-established
09-13 16:10:45.445  1037  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 16:10:45.445  1037  1540 D WifiNative-HAL: Setting external_sim to 1
09-13 16:10:45.445  1037  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 16:10:45.445  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 16:10:45.445  1037  1540 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 16:10:45.445  1037  1540 I WifiNative-HAL: startHal
09-13 16:10:45.445  1037  1540 D wifi    : setting scan oui 0xaf6af140
09-13 16:10:45.445  1969  6999 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 16:10:45.446  1969  6999 E CtrlSupplicant: Succeed to open control connection
09-13 16:10:45.446  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 16:10:45.446  1037  1540 I WifiNative-HAL: startHal
09-13 16:10:45.446  1037  1540 D wifi    : setting scan oui 0xaf6af140
09-13 16:10:45.446  1969  6999 E CtrlSupplicant: Succeed to open monitor connection
09-13 16:10:45.446  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 16:10:45.446  1969  6999 D WfdsMonitor: Supplicant connection established
09-13 16:10:45.446  1037  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 16:10:45.446  1969  2310 D WfdsService: Connected to the supplicant for wfds
09-13 16:10:45.446  1037  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 16:10:45.446  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 16:10:45.446  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 16:10:45.447  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 16:10:45.447  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 16:10:45.447  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 16:10:45.447  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 16:10:45.447  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 16:10:45.447  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 16:10:45.447  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 16:10:45.447  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,09-13 16:10:45.447  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2793
09-13 16:10:45.447  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 16:10:45.448  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 16:10:45.448  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 16:10:45.448  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 16:10:45.448  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 16:10:45.448  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 16:10:45.448  6967  6967 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 16:10:45.448  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 16:10:45.448  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 16:10:45.448  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 16:10:45.449  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 16:10:45.449  1037  1540 E WifiNative: : [198,528,022 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 16:10:45.449  1037  1540 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 16:10:45.450  1037  1540 D WifiNative-wlan0: RECONNECT: returned true
09-13 16:10:45.450  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-13 16:10:45.450  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 16:10:45.450  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 16:10:45.450  1037  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 16:10:45.450  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:45.450  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:45.451  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.452  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:45.452   313   897 D CommandListener: Setting iface cfg
09-13 16:10:45.452  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:45.452  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:45.452   313   897 D CommandListener: Trying to bring up p2p0
09-13 16:10:45.452  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:45.452  1037  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 16:10:45.452  1037  1539 D LGWifiP2pService: P2pEnablingState
09-13 16:10:45.452  1037  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.452  1037  1539 D LGWifiP2pService: P2p socket connection successful
09-13 16:10:45.452  1037  1539 D LGWifiP2pService: P2pEnabledState
09-13 16:10:45.453  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 16:10:45.453  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-13 16:10:45.454  1037  1539 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 16:10:45.454  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 16:10:45.454  1037  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 16:10:45.454  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 16:10:45.454  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 16:10:45.454  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 16:10:45.454  6891  6891 D UsbSetting,sReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 16:10:45.454  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:45.454  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:45.454  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:45.455  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 16:10:45.455  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 16:10:45.455  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 16:10:45.455  1969  1969 D WfdsService: WifiP2pState is changed : true
09-13 16:10:45.455  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 16:10:45.456  1969  2310 D WfdsService: Receive the WFDS_ENABLE Method
09-13 16:10:45.456  1969  2310 D WfdsService: Set the WFDS Monitor: true
09-13 16:10:45.456  1969  2310 D WfdsService: Connected to the supplicant for wfds
09-13 16:10:45.456  1969  2310 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 16:10:45.456  6967  6967 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 16:10:45.456  1969  2310 D WfdsService: selectPreferredScanChannel [36]
09-13 16:10:45.456  1969  2310 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 16:10:45.456  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 16:10:45.456  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 16:10:45.456  1037  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 16:10:45.456  1969  1969 D WfdsService: isConnected: false
09-13 16:10:45.456  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 16:10:45.456  1037  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 16:10:45.457  1037  1539 D WifiNative-p2p0: SET device_name G3: returned true
09-13 16:10:45.457  1037  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 16:10:45.457  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 16:10:45.457  1037  1539 D LGWifiP2pService: before postfix = G3
09-13 16:10:45.457  1037  1539 D WifiServerServiceExt: postfix byte check : 2
09-13 16:10:45.457  1037  1539 D LGWifiP2pService: after postfix = G3
09-13 16:10:45.457  1037  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 16:10:45.457  1037  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 16:10:45.457  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 16:10:45.457  1037  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 16:10:45.457  1037  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 16:10:45.457  1037  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 16:10:45.457  1037  1540 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 16:10:45.458  1037  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 16:10:45.458  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 16:10:45.458  1037  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 16:10:45.458  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress
09-13 16:10:45.459  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 16:10:45.459  1037  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 16:10:45.459  1037  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 16:10:45.459  1037  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 16:10:45.459  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=198538  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:45.459  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 16:10:45.459  1969  1969 I WfdStateTrack,er: handleP2pThisDeviceChanged
09-13 16:10:45.459  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 16:10:45.459  1037  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 16:10:45.460  1037  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 16:10:45.460  1969  1969 D WfdsService: Update P2p Interface State: 3
09-13 16:10:45.460  1037  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 16:10:45.460  1037  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 16:10:45.460  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=198539  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:45.461  1037  1558 D WifiScanningService: DefaultState got{ when=-8ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.461  1037  1558 I WifiNative-HAL: startHal
09-13 16:10:45.461  1037  1559 D RttService: DefaultState got{ when=-8ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.461  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.461  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.461  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 16:10:45.461  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:45.461  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:45.462  1037  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 16:10:45.462  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:45.462  1037  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 16:10:45.463  1037  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 16:10:45.463  1037  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 16:10:45.465  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:45.467  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 16:10:45.471  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:45.474  6933  7001 W FormManager: Network not available. Please check & try again.
09-13 16:10:45.474  6967  6967 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 16:10:45.475  1037  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 16:10:45.475  1037  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 16:10:45.475  1037  1539 D LGWifiP2pService: InactiveState
09-13 16:10:45.475  1037  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 16:10:45.475  1037  1539 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.475  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.475  1037  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 16:10:45.475  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 16:10:45.476  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.476  1037  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 16:10:45.476  1969  6999 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 16:10:45.476  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 16:10:45.476  1037  6997 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.476  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.476  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.476  6967  6967 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 16:10:45.476  1037  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 16:10:45.476  1037  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 16:10:45.476  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.476  1969  6999 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.476  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.476  1037  6997 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.476  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.476  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.476  6967  6967 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 16:10:45.477  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.477  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 16:10:45.477  1969  6999 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.477  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.477  1037  6997 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.477  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.477  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.477  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 16:10:45.477  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 16:10:45.477  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 16:10:45.478  1037  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.478  1037  1539 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.479  6967  6967 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.479  1037  1037 E WifiServerServiceExt: No p2p device connected
09-13 16:10:45.479  6967  6967 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 16:10:45.479  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.479  1969  6999 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.479  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 16:10:45.479  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.479  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.479  1969  2310 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 16:10:45.479  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:45.480  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.480  1037  6997 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.480  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.480  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.480  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.480  1037  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 16:10:45.480  1037  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf6af140
09-13 16:10:45.480  1037  1558 D wifi    : failed to get capabilities : -3
09-13 16:10:45.480  1037  1558 E WifiScanningService: could not get scan capabilities
09-13 16:10:45.480  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.480  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:45.481  6933  7002 V FormManager: Network unavailable.
09-13 16:10:45.481  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 16:10:45.482  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 16:10:45.482  1969  6999 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.482  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:45.482  1037  6997 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.482  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.482  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:45.482  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 16:10:45.482  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 16:10:45.483  6933  7002 V FormManager: Network unavailable.
09-13 16:10:45.483  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 16:10:45.483  6967  6967 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:45.483  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 16:10:45.483  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:45.484  1037  6997 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:45.484  1037  6997 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:45.485  1037  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 16:10:45.485  1037  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 16:10:45.485  1037  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 16:10:45.485  1037  1540 D WifiNative-wlan0: doBoolean: SCAN
09-13 16:10:45.486  1037  1540 D WifiNative-wlan0: SCAN: returned false
09-13 16:10:45.486  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=198565  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:45.487  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:45.488  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=198567  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:45.488  1037  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:45.489  1037  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:45.489  1037  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:45.489  1037  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:45.489  1037  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-13 16:10:45.491  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.491  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:45.491  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 16:10:45.491  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:45.491  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 16:10:45.492  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:45.492  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:45.493  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:45.495  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 16:10:45.496  6933  7003 W FormManager: Network not available. Please check & try again.
09-13 16:10:45.498  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:45.503  6933  7004 V FormManager: Network unavailable.
09-13 16:10:45.509  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:45.510  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:45.511  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:45.511  6933  7004 V FormManager: Network unavailable.
09-13 16:10:45.512  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:45.516  6648  6648 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 16:10:45.516  6648  6648 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 16:10:45.518  4333  7005 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:45.522  6648  6648 V [BNRBootReceiver]: Boot Receiver Return
09-13 16:10:45.522  4333  7006 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:45.522  4333  7006 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:45.525  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:45.528  6980  6980 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 16:10:45.528  6980  6980 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 16:10:45.528  6980  6980 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-13 16:10:45.530  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:45.533  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:45.538  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:45.538  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:45.539  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 16:10:45.541  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:45.544  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:45.548  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:45.549  6980  6980 I UEI.SmartControl: --- Selecting new region: 6
09-13 16:10:45.550  6980  6980 I UEI.SmartControl: Model = LG-D855
,09-13 16:10:45.551  6980  6980 D UEI.SmartControl: QS Service created
09-13 16:10:45.552  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:45.552  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:45.553  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:45.560  6980  6980 I UEI.SmartControl: Service initServices...
09-13 16:10:45.562  6980  6980 D UEI.SmartControl: QS start get config
,09-13 16:10:45.600  6980  6980 D UEI.SmartControl: Loading JNI Libs...
,09-13 16:10:45.815  6736  6890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:45.826  1037  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:45.827  1037  1993 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:45.852  1037  1099 D BluetoothManagerService: Message: 2
09-13 16:10:45.854  1037  1099 D BluetoothManagerService: Sending off request.
09-13 16:10:45.855  3900  3918 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 16:10:45.855  3900  3987 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 16:10:45.856  3900  3987 D BluetoothAdapterProperties: Setting state to 13
09-13 16:10:45.856  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 16:10:45.856  3900  3987 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 16:10:45.856  3900  3987 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 16:10:45.858  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:45.858  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 16:10:45.858  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-13 16:10:45.862  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:45.862  3900  3900 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:45.862  3900  3900 D BluetoothMapService: STATE_TURNING_OFF
09-13 16:10:45.863  3900  3900 V BtOppService: Receiver DISABLED_ACTION 
09-13 16:10:45.863  3900  3900 V BluetoothMapService: Handler(): got msg=4
09-13 16:10:45.863  3900  3900 D BluetoothMapService: MAP Service closeService in
09-13 16:10:45.863  3900  3900 D BluetoothMapMasInstance: MAP Service shutdown
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 16:10:45.864  3900  4222 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 16:10:45.864  3900  3900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 16:10:45.864  3900  3900 V BluetoothMapService: MAP Service closeService out
09-13 16:10:45.865  3900  3900 I BtOppRfcommListener: stopping Accept Thread
09-13 16:10:45.865  3900  3900 V BtOppRfcommListener: close mBtServerSocket
09-13 16:10:45.866  3900  4277 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:45.866  3900  3900 V BtOppRfcommListener: waiting for thread to terminate
09-13 16:10:45.866  3900  4277 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 16:10:45.866  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:45.867  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:45.868  3900  3900 V BtOppRfcommListener: done waiting for thread to terminate
,09-13 16:10:45.870  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:45.871  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:45.871  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-13 16:10:45.874  3900  3900 V BtOppService: onDestroy
09-13 16:10:45.875  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:45.875  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:45.876  3900  3991 D BluetoothAdapterProperties: Scan Mode:20
09-13 16:10:45.876  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:45.876  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 16:10:45.877  3900  4227 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:45.877  3900  3987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 16:10:45.877  3900  4278 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:45.877  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:45.877  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:45.878  3900  4281 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:45.878  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:45.878  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 16:10:45.878  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:45.880  3900  4092 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 16:10:45.882  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to act,ive network: false
09-13 16:10:45.883  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:45.883  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:45.883  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:45.883  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 16:10:45.884  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 16:10:45.884  3900  4092 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 16:10:45.885  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:45.887  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:45.889  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:45.890  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 16:10:45.929  1037  1095 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7013 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 16:10:45.930  3900  3900 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-13 16:10:45.935  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:45.935  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:45.935  3900  3900 V BluetoothPbapReceiver: ***********state = 13
09-13 16:10:45.936  3900  3900 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 16:10:45.939  3900  3900 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:45.939  3900  3900 V BluetoothPbapService: state: 13
09-13 16:10:45.939  3900  3900 V BluetoothPbapService: Pbap Service closeService in
09-13 16:10:45.940  3900  3900 V BluetoothPbapService: successfully stopped pbap service
09-13 16:10:45.940  3900  3900 V BluetoothPbapService: Pbap Service closeService out
09-13 16:10:45.941  3900  3900 V BluetoothPbapService: Pbap Service onDestroy
09-13 16:10:45.941  3900  3900 V BluetoothPbapService: Pbap Service closeService in
09-13 16:10:45.941  3900  3900 V BluetoothPbapService: Pbap Service closeService out
09-13 16:10:45.941  3900  3900 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 16:10:45.941  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:10:45.948  1037  1099 D BluetoothManagerService: Message: 20
,09-13 16:10:45.948  1037  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35a0dcc6:true
09-13 16:10:45.956  1037  1099 D BluetoothManagerService: Message: 30
09-13 16:10:45.959  1037  1099 D BluetoothManagerService: Message: 30
,09-13 16:10:45.965  6891  6891 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 16:10:45.967  6891  6891 D BluetoothMap: Create BluetoothMap proxy object
09-13 16:10:45.967  1037  1099 D BluetoothManagerService: Message: 30
09-13 16:10:45.971  1037  1099 D BluetoothManagerService: Message: 30
,09-13 16:10:45.974  6891  6891 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 16:10:45.976  6891  6891 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-13 16:10:45.995  6891  6891 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-13 16:10:45.997  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 16:10:46.003  6891  6891 D DockEventReceiver: finishStartingService: stopping service
09-13 16:10:46.004  6891  6891 D BluetoothInputDevice: Proxy object connected
09-13 16:10:46.005  6891  6891 D HidProfile: Bluetooth service connected
09-13 16:10:46.005  6891  6891 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 16:10:46.006  6891  6891 D PanProfile: Bluetooth service connected
09-13 16:10:46.006  6891  6891 D BluetoothMap: Proxy object connected
09-13 16:10:46.007  6891  6891 D MapProfile: Bluetooth service connected
09-13 16:10:46.007  6891  6891 D BluetoothMap: getConnectedDevices()
09-13 16:10:46.007  6891  6891 D BluetoothMap: Bluetooth is Not enabled
09-13 16:10:46.008  6891  6891 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-13 16:10:46.028  6980  6980 I UEI.SmartControl: Supports setup maps: true
,09-13 16:10:46.028  7013  7013 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 16:10:46.029  7013  7013 W LG Account v2.2: No ProfileInfo entries
09-13 16:10:46.029  7013  7013 I LG Account v2.2: isEnabled: false
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Country: EU
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Operator: OPEN
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Ranking support: false
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Comfort support: false
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Accessory: true
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Health device: true
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Extra Pedometer: false
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Blood glucose device: false
09-13 16:10:46.029  7013  7013 I Feature : [Lifetracker]Device Number: 3
09-13 16:10:46.031  6980  6980 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 16:10:46.031  6980  6980 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 16:10:46.031  6980  6980 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 16:10:46.031  6980  6980 I UEI.SmartControl: ### init IR Blaster...
09-13 16:10:46.035  6980  6980 D serial_port: Configuring serial port
09-13 16:10:46.037  6891  6891 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 16:10:46.038  6980  6980 E UEI.SmartControl: UEIBLaster setting for 616
09-13 16:10:46.038  6980  6980 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 16:10:46.038  6980  6980 I UEI.SmartControl: configuring settings for MAXQ616
09-13 16:10:46.039  6980  6980 I UEI.SmartControl: Get version...
09-13 16:10:46.041  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:46.042  6891  6891 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 16:10:46.048  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 16:10:46.049  1037  1934 I ActivityManager: Killing 6516:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-13 16:10:46.055  6980  7043 D UEI.SmartControl: serial port data available: 21
,09-13 16:10:46.069  3900  3900 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 16:10:46.069  3900  3900 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-13 16:10:46.069  3900  3900 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 16:10:46.069  1037  1720 W libprocessgroup: failed to open /acct/uid_10008/pid_6516/cgroup.procs: No such file or directory
09-13 16:10:46.073  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:46.073  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 16:10:46.073  3900  3900 V BluetoothFtpService: Ftp Service onStartCommand
09-13 16:10:46.073  3900  3900 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:46.074  3900  3900 V BluetoothFtpService: Ftp Service closeService
09-13 16:10:46.074  3900  3900 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 16:10:46.075  3900  3900 V BluetoothFtpService: successfully stopped ftp service
09-13 16:10:46.075  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:46.075  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:46.075  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:46.076  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:46.076  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 16:10:46.076  3900  3900 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 16:10:46.076  3900  3900 V BluetoothFtpService: Ftp Service onDestroy
09-13 16:10:46.076  3900  3900 V BluetoothFtpService: Ftp Service closeService
09-13 16:10:46.083  6980  6980 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 16:10:46.083  6980  6980 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 16:10:46.083  6980  6980 I UEI.SmartControl: QS saving settings...
09-13 16:10:46.085  6980  6980 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 16:10:46.092  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 16:10:46.092  1037  6997 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 16:10:46.093  6967  6967 E wpa_supplicant: USIM:  scard_init function
09-13 16:10:46.094  1037  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 16:10:46.094  6967  6967 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 16:10:46.094  1037  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 16:10:46.095  1037  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 16:10:46.096  1037  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 16:10:46.096  1037  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 16:10:46.097  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 16:10:46.097  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-13 16:10:46.097  1037  6997 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 16:10:46.097  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 16:10:46.097  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-13 16:10:46.103  6980  7043 D UEI.SmartControl: serial port data available: 4
09-13 16:10:46.137  6980  7048 I UEI.SmartControl: Device manager: loading config....
,09-13 16:10:46.141  6980  7048 D UEI.SmartControl: ----------- loading internal config...
09-13 16:10:46.143  6980  6980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 16:10:46.146  1037  2016 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7049 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 16:10:46.149  3900  3900 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:46.149  3900  3900 V BluetoothSapService: state: 13
09-13 16:10:46.150  3900  3900 V BluetoothSapService: Stopping SAP server process
09-13 16:10:46.150  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=199228  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 16:10:46.152  3900  3900 V BluetoothSapService: Sap Service closeSapService in
09-13 16:10:46.152  3900  3900 V BluetoothSapService: Close listen Socket : 
09-13 16:10:46.153  3900  3900 V BluetoothSapService: Close rfcomm Socket : 
09-13 16:10:46.153  3900  3900 V BluetoothSapService: Close sapd  Socket : 
09-13 16:10:46.154  6980  6980 E UEI.SmartControl: Services init done
09-13 16:10:46.154  6980  6980 D UEI.SmartControl: QS Service init finished
09-13 16:10:46.155  6980  6980 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 16:10:46.155  6980  6980 D UEI.SmartControl: QS Service version code: 201091
09-13 16:10:46.156  6980  6980 D UEI.SmartControl: Service requested: Control
09-13 16:10:46.156  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=199235  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 16:10:46.159  3900  3900 V BluetoothSapService: Sap Service closeSapService out
09-13 16:10:46.160  3900  3900 V BluetoothSapService: Sap Service onDestroy
09-13 16:10:46.160  3900  3900 V BluetoothSapService: Sap Service closeSapService in
09-13 16:10:46.160  3900  3900 V BluetoothSapService: Close listen Socket : 
09-13 16:10:46.160  3900  3900 V BluetoothSapService: Close rfcomm Socket : 
09-13 16:10:46.160  3900  3900 V BluetoothSapService: Close sapd  Socket : 
09-13 16:10:46.163  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.163  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:46.164  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.164  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.164  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 16:10:46.165  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:46.165  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 16:10:46.167  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.168  3900  3900 V BluetoothSapService: Sap Service closeSapService out
,09-13 16:10:46.172  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 16:10:46.180  6891  6891 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 16:10:46.184  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:46.187  6980  7048 E UEI.SmartControl: Loading SETTINGS...
09-13 16:10:46.188  6980  6980 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 16:10:46.190  6980  6980 D UEI.SmartControl: Internal service binding...
09-13 16:10:46.191  6913  6913 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 16:10:46.192  6980  6996 I UEI.SmartControl: ------ IControl API: 11
09-13 16:10:46.193  6980  6996 I UEI.SmartControl: Registering callback...
09-13 16:10:46.194  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:46.195  6980  6995 I UEI.SmartControl: ------ IControl API: 19
09-13 16:10:46.196  6980  6995 I UEI.SmartControl: Registering Services Ready callback...
,09-13 16:10:46.199  6980  7048 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 16:10:46.206  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:46.212  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.212  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.212  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 16:10:46.215  6980  7047 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 16:10:46.216  6913  6929 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 16:10:46.216  6980  7047 D UEI.SmartControl: -----service ready thread exits
09-13 16:10:46.216  6913  6973 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 16:10:46.216  6913  6973 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 16:10:46.217  6913  6913 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 16:10:46.218  6913  6913 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 16:10:46.218  6980  6996 I UEI.SmartControl: ------ IControl API: 8
09-13 16:10:46.219  6913  6913 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 16:10:46.220  6913  6913 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 16:10:46.220  6913  6913 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 16:10:46.221  6913  6913 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 16:10:46.221  6913  6913 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 16:10:46.222  6913  6913 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 16:10:46.222  7049  7049 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:10:46.223  6913  6913 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 16:10:46.225  6913  6913 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 16:10:46.225  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 16:10:46.227  6913  6913 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 16:10:46.227  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 16:10:46.228  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 16:10:46.229  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 16:10:46.230  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 16:10:46.231  6913  6913 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473775846230]
09-13 16:10:46.232  6913  6913 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 16:10:46.233  1037  1934 I ActivityManager: Killing 6050:com.android.contacts/u0a19 (adj 15): empty #17
09-13 16:10:46.244  6967  6967 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 16:10:46.247  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 16:10:46.247  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 16:10:46.247  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,09-13 16:10:46.247  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 16:10:46.248  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:46.248  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:46.248  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=199327  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 16:10:46.249  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=199328  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 16:10:46.250  1037  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199328
09-13 16:10:46.250  1037  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199329
09-13 16:10:46.250  1037  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199329
09-13 16:10:46.251  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199330
09-13 16:10:46.251  1037  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199330
09-13 16:10:46.252  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=199331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 16:10:46.253  6967  6967 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 16:10:46.253  6967  6967 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 16:10:46.253  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:46.253  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:46.253  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 16:10:46.253  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 16:10:46.253  1037  6997 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 16:10:46.253  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 16:10:46.253  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 16:10:46.254  1037  6997 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 16:10:46.254  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:46.254  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:46.257  6913  7067 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
09-13 16:10:46.269  1037  1934 I ActivityManager: Killing 6026:com.lge.appbox.client/u0a11 (adj 15): empty #18
,09-13 16:10:46.299  1037  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 16:10:46.299  1037  1979 W libprocessgroup: failed to open /acct/uid_10019/pid_6050/cgroup.procs: No such file or directory
09-13 16:10:46.307  1037  1053 W libprocessgroup: failed to open /acct/uid_10011/pid_6026/cgroup.procs: No such file or directory
09-13 16:10:46.317  1037  1934 I ActivityManager: Killing 6561:com.lge.email/u0a23 (adj 15): empty #17
,09-13 16:10:46.356  6736  7011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:46.383  1037  1720 W libprocessgroup: failed to open /acct/uid_10023/pid_6561/cgroup.procs: No such file or directory
,09-13 16:10:46.384  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=199463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 16:10:46.390  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:46.391  1037  1054 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:46.393  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.393  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 16:10:46.397  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.398  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.398  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.399  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 16:10:46.404  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.404  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.404  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 16:10:46.410  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:46.410  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:46.410  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-13 16:10:46.411  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:46.411  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
09-13 16:10:46.413  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=199492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 16:10:46.414  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:46.414  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 16:10:46.415  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=199494  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 16:10:46.416  1037  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199495
09-13 16:10:46.416  1037  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199495
09-13 16:10:46.417  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-13 16:10:46.417  3900  3918 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 16:10:46.418  1037  1099 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 16:10:46.418  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:46.418  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:46.414  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:46.419  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:46.419  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:46.419  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:46.420  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 16:10:46.421  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 16:10:46.421  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 16:10:46.421  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 16:10:46.421  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:46.421  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:46.421  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 16:10:46.421  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:46.423  1037  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 16:10:46.425  1037  1540 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 16:10:46.425  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.425  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 16:10:46.428  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:46.429  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.434  1037  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 16:10:46.434  1037  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 16:10:46.440  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.440  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.440  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 16:10:46.443  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:46.447  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.447  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.447  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 16:10:46.450  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.450  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 16:10:46.456  1037  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 16:10:46.456  1037  1547 D ConnectivityService: Got NetworkAgent Messenger
09-13 16:10:46.456  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:10:46.456  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 16:10:46.457  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 16:10:46.457  1037  1547 D ConnectivityService: NetworkAgent connected
09-13 16:10:46.457  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 16:10:46.457  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 16:10:46.457  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.460  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.460  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:46.460  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:46.461  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.462  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 16:10:46.462  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:10:46.462  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 16:10:46.463  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 16:10:46.463  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 16:10:46.468  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 16:10:46.468  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.468  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.469  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:46.469   313   897 D CommandListener: Setting iface cfg
09-13 16:10:46.471  6913  6913 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-13 16:10:46.472  1037  1540 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 16:10:46.472  6913  6913 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 16:10:46.472  1037  7071 D DhcpStateMachine: StoppedState
09-13 16:10:46.473  1037  7071 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.473  1037  7071 D DhcpStateMachine: WaitBeforeStartState
09-13 16:10:46.473  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=199551  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:46.473  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 16:10:46.473  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 16:10:46.473  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=199552  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:46.473  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-13 16:10:46.474  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=199552  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:46.474  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 16:10:46.474  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 16:10:46.475  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:46.475  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 16:10:46.478  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:46.478  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:46.479  1037  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:46.479  1037  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:46.480  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:46.480  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:46.481  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:46.481  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=199560  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:46.481  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 16:10:46.481  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=199560  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:46.482  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=199561  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:46.483  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:154029] from screen [on:0 period:602063955] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:46.484  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:602063956] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:46.484  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 16:10:46.486  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-13 16:10:46.488  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.489  1037  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 16:10:46.489  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.489  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.490  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.490  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:46.490  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.491  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.491  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.491  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 16:10:46.492  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=160,0,0
09-13 16:10:46.492  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=160,0,0
09-13 16:10:46.492  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 16:10:46.493  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 16:10:46.493  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 16:10:46.493  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 16:10:46.495  1037  1540 D WifiNative-wlan0: SET ps 0: returned true
09-13 16:10:46.495  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 16:10:46.495  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 16:10:46.496  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 16:10:46.496  1037  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 16:10:46.496  1037  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 16:10:46.496  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d637ab0 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.496  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d637ab0 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.496  1037  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 16:10:46.496  1037  7071 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.496  1037  7071 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 16:10:46.497   313   897 D CommandListener: Setting iface cfg
09-13 16:10:46.498   313   897 D CommandListener: Trying to bring up wlan0
,09-13 16:10:46.500  1037  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 16:10:46.500  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:46.500  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 16:10:46.502  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.502  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.503  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-13 16:10:46.503  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 16:10:46.503  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.503  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.503  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:46.504  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.504  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:46.505  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 16:10:46.505  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 16:10:46.505  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 16:10:46.506  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 16:10:46.506  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.506  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.506  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 16:10:46.507  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 16:10:46.507  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 16:10:46.507  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 16:10:46.508  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 16:10:46.508  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:46.509  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 16:10:46.516  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.516  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.517  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:46.521  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:46.523  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:46.524  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 16:10:46.524  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 16:10:46.525  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 16:10:46.525  1037  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 16:10:46.526  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
09-13 16:10:46.530  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 16:10:46.531  1037  1547 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 16:10:46.535  1037  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 16:10:46.536  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.536  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:46.537  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.537  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.537  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 16:10:46.538  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.541  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.541  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:46.543  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.544  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.544  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.544  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 16:10:46.544  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 16:10:46.547  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-13 16:10:46.552  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.552  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.552  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 16:10:46.552  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 16:10:46.557  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 16:10:46.557  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 16:10:46.557  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.560  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.560  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:46.560  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 16:10:46.561  1037  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 16:10:46.562  1037  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 16:10:46.563  1037  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 16:10:46.563   313   897 E Netd    : netlink response contains error (File exists)
09-13 16:10:46.564  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.564  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 16:10:46.564  1037  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 16:10:46.564  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.564  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:46.565  1037  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 16:10:46.565  1037  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 16:10:46.565  1037  1547 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 16:10:46.566  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 16:10:46.566  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.566  1037  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.568  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.568  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 16:10:46.568  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:46.568  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 16:10:46.570  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.570  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:46.570  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:46.570  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 16:10:46.570  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.570  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 16:10:46.570  1037  1547 D ConnectivityService,: currentScore = 0, newScore = 20
09-13 16:10:46.570  1037  1547 D ConnectivityService:    accepting network in place of null
09-13 16:10:46.570  1037  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.571  1037  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.571  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:46.571  1880  1880 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.572  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 16:10:46.572  1037  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 16:10:46.572   313  7075 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 16:10:46.572  1037  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 16:10:46.572  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:10:46.572  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:46.573  1037  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,09-13 16:10:46.575  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 16:10:46.576  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 16:10:46.576  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 16:10:46.577  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 16:10:46.580  1037  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 16:10:46.581  1037  1547 D ConnectivityService: validation of new default Network = false
09-13 16:10:46.581  1037  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 16:10:46.581  1037  1547 D DSQN    : enableDataServiceNotify 
09-13 16:10:46.581  1037  1547 D DSQN    : start dsqn bin
09-13 16:10:46.582  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 16:10:46.588  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.588  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.588  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:46.588  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:46.589  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 16:10:46.586  7076  7076 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:46.586  7076  7076 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:46.593  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.594  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.594  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:46.604  7076  7076 E DSQN    : DSQN ssw
,09-13 16:10:46.607  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:46.615  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:46.618  1037  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 16:10:46.620  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:46.626  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.626  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.627  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 16:10:46.629  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:46.630  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.631   313  7075 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 16:10:46.631  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.632  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:46.640  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:46.645  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:46.650  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.650  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 16:10:46.655  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:46.659  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:46.667   313  7075 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 16:10:46.670  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:46.678  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:46.688  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 16:10:46.688  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.690  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:46.694   313   896 D LGDataListener: argv[0]=dsqncommand
09-13 16:10:46.694   313   896 D LGDataListener: argv[1]=wlan0
09-13 16:10:46.694   313   896 D LGDataListener: argv[2]=1
09-13 16:10:46.694   313   896 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 16:10:46.695  1037  1097 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 16:10:46.695  1037  1097 D DSQN    : start to monitor internet connection
09-13 16:10:46.697  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:46.698  1037  7071 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 16:10:46.699  1037  7071 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 16:10:46.699  1037  7071 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 16:10:46.696  7082  7082 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:46.696  7082  7082 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:46.708  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 16:10:46.714  7082  7082 I dhcpcd  : version 5.5.6 starting
09-13 16:10:46.716  7082  7082 E dhcpcd  : get_duid: m
09-13 16:10:46.716  7082  7082 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 16:10:46.716  7082  7082 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 16:10:46.717  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:46.722  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:46.723  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 14:10:46 GMT], X-Android-Received-Millis=[1473775846722], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473775846693]}
09-13 16:10:46.723  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 16:10:46.723  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 16:10:46.723  1037  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.723  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.723  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:46.723  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:46.723  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 16:10:46.723  1037  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 16:10:46.724  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 16:10:46.724  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.724  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:46.724  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:46.724  1037  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.725  1037  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.725  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 16:10:46.725  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:46.725  1880  1880 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:46.726  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 16:10:46.726  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 16:10:46.732  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 16:10:46.744  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.744  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 16:10:46.745  6913  6913 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 16:10:46.746  6913  6913 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 16:10:46.747  6913  6913 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 16:10:46.761  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:46.769  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 16:10:46.769  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:46.775  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:46.780  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:46.782  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.782  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:46.783  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:46.788  7082  7082 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 16:10:46.788  7082  7082 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 16:10:46.789  7082  7082 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 16:10:46.789  7082  7082 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-13 16:10:46.789  7082  7082 D dhcpcd  : wlan0: sending REQUEST (xid 0x108c97a6), next in 4.35 seconds
,09-13 16:10:46.790  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:46.791  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:46.792  6913  6913 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 16:10:46.793  6913  6913 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 16:10:46.793  6913  6913 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 16:10:46.807  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:46.811  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:46.811  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-13 16:10:46.811  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:46.811  7082  7082 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-13 16:10:46.816  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 16:10:46.820  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.820  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 16:10:46.822  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:46.822  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:46.825  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-13 16:10:46.827  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:46.828  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:46.828  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:46.833  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:46.833  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:46.834  6466  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 16:10:46.834  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:46.834  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:10:46.839  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:46.839  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:46.841  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:46.841  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:46.842  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 16:10:46.843  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:46.845  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:46.844  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:46.848  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:46.853  7082  7082 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 16:10:46.853  7082  7082 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 16:10:46.853  7082  7082 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 16:10:46.854  7082  7082 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 16:10:46.854  7082  7082 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 16:10:46.854  7082  7082 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 16:10:46.854  7082  7082 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 16:10:46.854  7082  7082 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 16:10:46.865  2276  2276 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:46.872   313  7096 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 16:10:46.872   313  7096 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 16:10:46.886  3900  3991 D bt_hci_bdroid: cleanup
,09-13 16:10:46.886  3900  4094 I bt_lpm  : LPM is already off!!!
,09-13 16:10:46.886  3900  4217 I bt_userial_mct: exiting userial_read_thread
09-13 16:10:46.887  3900  4217 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 16:10:46.887  3900  3991 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 16:10:46.887  3900  4092 W bt-btif : ag scb idx 1 not allocated
09-13 16:10:46.887  3900  4092 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:46.887  3900  4092 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:46.887  3900  4092 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 16:10:46.887  3900  4094 I bt_vendor: hw_epilog_process
09-13 16:10:46.888  3900  3991 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 16:10:46.888  3900  3991 D bt_userial_mct: userial_close
09-13 16:10:46.888  3900  3991 E bt_userial_mct: pthread_join() FAILED result:3
09-13 16:10:46.888  3900  3991 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 16:10:46.905   313  7096 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-13 16:10:46.930  1037  1720 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7102 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-13 16:10:46.931  1037  2087 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:46.931  1037  2087 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:46.932  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:46.932  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
,09-13 16:10:46.934  3900  3919 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 16:10:46.935  1037  1099 E BluetoothManagerService: IBluetooth.enable() returned false
,09-13 16:10:47.011  7102  7102 I AppUp4:AppBoxCP: onCreate
,09-13 16:10:47.011  7102  7102 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-13 16:10:47.023  7102  7102 I AppUp4:DB:  setFingerPrint start
09-13 16:10:47.023  7102  7102 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-13 16:10:47.032  3900  3991 D bt_hci_bdroid: set_power 0
09-13 16:10:47.032  3900  3991 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 16:10:47.032  3900  3991 I bt_vendor: bluetooth satus is on
09-13 16:10:47.032  3900  3991 I bt_vendor: bt-vendor : resetting BT status
09-13 16:10:47.032  3900  3991 I bt_vendor: Starting hciattach daemon
09-13 16:10:47.032  3900  3991 I bt_vendor: try to set false
09-13 16:10:47.032  3900  3991 I bt_vendor: Starting hciattach daemon
09-13 16:10:47.032  3900  3991 I bt_vendor: try to set false
09-13 16:10:47.033  3900  3991 I bt_vendor: cleanup
09-13 16:10:47.034  3900  4092 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 16:10:47.034  3900  3991 I GKI_LINUX: GKI_exit_task 0 done
09-13 16:10:47.034  3900  3991 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 16:10:47.035  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 16:10:47.037  3900  3900 D HeadsetService: Received stop request...Stopping profile...
,09-13 16:10:47.038  3900  3900 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 16:10:47.038  3900  3900 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:10:47.038  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.039  3900  4015 D HeadsetStateMachine: Exit Disconnected: -1
09-13 16:10:47.040  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:47.040  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 16:10:47.040  1880  1880 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:47.041  1880  1880 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:47.041  7102  7102 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-13 16:10:47.041  7102  7102 I AppUp4:DB:  SDK version = 21
,09-13 16:10:47.041  7102  7102 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 16:10:47.041  1880  1880 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:47.043  3900  3900 D A2dpService: Received stop request...Stopping profile...
09-13 16:10:47.043  3900  4071 D A2dpStateMachine: Exit Disconnected: -1
09-13 16:10:47.044  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 16:10:47.044  7102  7102 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-13 16:10:47.046  3900  3987 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 16:10:47.046  3900  3900 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 16:10:47.046  3900  3900 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:10:47.045  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 16:10:47.046  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.046  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:47.047  1037  1037 D BluetoothA2dp: Proxy object disconnected
,09-13 16:10:47.047  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 16:10:47.048  3900  3900 D HidService: Received stop request...Stopping profile...
09-13 16:10:47.048  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.049  3900  3900 D HeadsetStateMachine: Unbinding service...
09-13 16:10:47.049  6891  6891 D BluetoothInputDevice: Proxy object disconnected
09-13 16:10:47.049  6891  6891 D HidProfile: Bluetooth service disconnected
09-13 16:10:47.049  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 16:10:47.050  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 16:10:47.050  3900  3900 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 16:10:47.050  3900  3900 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-13 16:10:47.050  3900  3900 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 16:10:47.050  3900  3900 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 16:10:47.050  3900  3900 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 16:10:47.050  3900  3900 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:10:47.050  3900  3900 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 16:10:47.051  3900  3900 D HealthService: Received stop request...Stopping profile...
09-13 16:10:47.051  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.054  3900  3900 D PanService: Received stop request...Stopping profile...
09-13 16:10:47.055  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.056  3900  3900 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 16:10:47.056  3900  3900 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 16:10:47.056  3900  3900 D BtGatt.GattService: stop()
09-13 16:10:47.056  3900  3900 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 16:10:47.057  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.058  6891  6891 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 16:10:47.058  6891  6891 D PanProfile: Bluetooth service disconnected
09-13 16:10:47.058  3900  3900 D BluetoothMapService: Received stop request...Stopping profile...
09-13 16:10:47.058  3900  3900 D BluetoothMapService: stop()
09-13 16:10:47.058  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
09-13 16:10:47.059  3900  3900 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 16:10:47.059  3900  3900 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 16:10:47.059  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.060  6891  6891 D BluetoothMap: Proxy object disconnected
09-13 16:10:47.060  6891  6891 D MapProfile: Bluetooth service disconnected
09-13 16:10:47.060  3900  3900 I BluetoothA2dpServiceJni: cleanupNative
09-13 16:10:47.060  3900  4076 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 16:10:47.061  3900  3900 I GKI_LINUX: GKI_exit_task 2 done
09-13 16:10:47.061  3900  3900 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 16:10:47.061  3900  3900 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 16:10:47.061  3900  3900 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 16:10:47.061  3900  3900 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 16:10:47.061  3900  3900 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 16:10:47.061  3900  3900 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 16:10:47.062  3900  3900 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 16:10:47.062  3900  3900 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 16:10:47.062  3900  3900 V BluetoothMapService: Handler(): got msg=4
,09-13 16:10:47.062  3900  3900 D BluetoothMapService: MAP Service closeService in
09-13 16:10:47.063  3900  3900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 16:10:47.063  3900  3900 V BluetoothMapService: MAP Service closeService out
09-13 16:10:47.063  3900  3900 D BluetoothMapService: cleanup()
09-13 16:10:47.063  3900  3900 D BluetoothMapService: MAP Service closeService in
09-13 16:10:47.063  3900  3900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 16:10:47.063  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 16:10:47.063  3900  3900 V BluetoothMapService: MAP Service closeService out
09-13 16:10:47.063  3900  3987 D BluetoothAdapterProperties: Setting state to 10
09-13 16:10:47.063  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 16:10:47.064  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:47.064  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 16:10:47.064  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 16:10:47.064  3900  3987 I BluetoothAdapterState: Entering OffState
09-13 16:10:47.064  6891  6906 D BluetoothPan: onBluetoothStateChange on: false
09-13 16:10:47.065  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:47.066  6891  6907 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 16:10:47.066  1880  1896 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:47.067  6891  6906 D BluetoothMap: onBluetoothStateChange: up=false
09-13 16:10:47.067  1880  2597 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:47.068  6891  6907 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 16:10:47.069  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:47.069  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:10:47.069  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 16:10:47.072  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.072  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:47.072  1969  2173 D LGBluetoothAPIService: Message: 2
09-13 16:10:47.072  1969  2173 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3825d1a0 mBinding = false
09-13 16:10:47.072  1969  2173 D LGBluetoothAPIService: Sending unbind request.
09-13 16:10:47.075  6891  6891 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 16:10:47.075  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 16:10:47.075  6891  6891 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 16:10:47.077  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:47.080  3900  3900 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 16:10:47.080  3900  3900 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-13 16:10:47.080  3900  3900 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 16:10:47.082  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 16:10:47.083  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:47.085  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:47.085  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:47.086  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.086  3900  3900 V BluetoothPbapReceiver: ***********state = 10
09-13 16:10:47.086  6891  6891 D DockEventReceiver: finishStartingService: stopping service
09-13 16:10:47.090  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:10:47.098  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:47.100  6891  6891 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 16:10:47.100  6891  6891 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 16:10:47.103  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 16:10:47.105  1037  7071 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 16:10:47.106  1037  7071 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 16:10:47.106  1037  7071 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 16:10:47.106  1037  7071 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,09-13 16:10:47.107  1037  7071 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 16:10:47.107  1037  7071 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 16:10:47.107  1037  7071 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 16:10:47.107  1037  7071 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 16:10:47.107  1037  7071 D DhcpStateMachine: RunningState
09-13 16:10:47.107  7102  7102 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:47.108  7102  7102 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 16:10:47.109  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.111  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:47.111  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:47.111  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:47.111  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.111  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 16:10:47.114  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:47.114  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:47.114  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:47.115  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:47.115  7102  7102 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 16:10:47.115  7102  7102 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 16:10:47.116  7049  7049 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 16:10:47.116  7102  7132 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 16:10:47.116  7102  7132 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 16:10:47.116  7102  7132 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-13 16:10:47.119  1037  1710 I ActivityManager: Killing 6077:com.android.gallery3d/u0a27 (adj 15): empty #17
09-13 16:10:47.160  2276  7129 D GCM     : Connected
,09-13 16:10:47.183  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:47.184  1037  2064 W libprocessgroup: failed to open /acct/uid_10027/pid_6077/cgroup.procs: No such file or directory
09-13 16:10:47.185  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 16:10:47.191  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:47.200  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:47.211  3525  3525 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:47.211  4333  7139 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:47.213  2276  7129 D GCM     : Message class com.google.e.a.a.q
09-13 16:10:47.218  3525  3525 V DownloadManager: DownloadService onCreate
09-13 16:10:47.219  4333  7140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:47.220  4333  7140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 16:10:47.221  4333  7139 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 16:10:47.222  3525  7141 I DownloadManager: in removeSpuriousFiles
09-13 16:10:47.223  3525  7141 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 16:10:47.230  3525  7141 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@237a4574 on behalf of 3525
09-13 16:10:47.233  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 16:10:47.233  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 16:10:47.234  3525  7141 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 16:10:47.236  3525  7141 I DownloadManager: in trimDatabase
09-13 16:10:47.236  3525  7141 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 16:10:47.238  3525  7141 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@a325b12 on behalf of 3525
,09-13 16:10:47.269  1037  2096 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7144 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 16:10:47.272  3525  3525 V DownloadManager: DownloadService onStartCommand
09-13 16:10:47.274  3525  7142 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 16:10:47.275  3525  7142 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@12b044e0 on behalf of 3525
09-13 16:10:47.276  4333  7139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 16:10:47.278  3525  7142 V DownloadManager: processing inserted download 1
09-13 16:10:47.279  3525  7142 V DownloadManager: processing inserted download 4
09-13 16:10:47.280  4333  4333 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 16:10:47.281  3525  7142 V DownloadManager: processing inserted download 7
09-13 16:10:47.281  4333  4333 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 16:10:47.282  3525  7142 V DownloadManager: processing inserted download 8
09-13 16:10:47.284  3525  7142 V DownloadManager: processing inserted download 9
09-13 16:10:47.285  3525  7142 V DownloadManager: processing inserted download 10
09-13 16:10:47.286  3525  7142 V DownloadManager: processing inserted download 11
09-13 16:10:47.286  4333  4333 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-13 16:10:47.287  3525  7142 V DownloadManager: processing inserted download 12
09-13 16:10:47.289  4333  4333 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 16:10:47.289  3525  7142 V DownloadManager: processing inserted download 13
09-13 16:10:47.290  3525  7142 V DownloadManager: processing inserted download 14
09-13 16:10:47.291  3525  7142 V DownloadManager: processing inserted download 16
09-13 16:10:47.294  4333  4333 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 16:10:47.295  3525  3525 V DownloadManager: DownloadService onDestroy
,09-13 16:10:47.334  7144  7144 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:10:47.334  7144  7144 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 16:10:47.336  7144  7144 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 16:10:47.336  7144  7144 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 16:10:47.432  7144  7144 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-13 16:10:47.434  1037  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 16:10:47.434  1037  1934 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:47.434  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:47.434  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
09-13 16:10:47.436  3900  3987 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 16:10:47.436  3900  3987 D BluetoothAdapterProperties: Setting state to 11
09-13 16:10:47.436  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 16:10:47.437  1037  1099 D BluetoothManagerService: Message: 60
,09-13 16:10:47.437  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 16:10:47.437  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 16:10:47.437  3900  3987 D BluetoothBondStateMachine: make
09-13 16:10:47.439  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.439  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:47.441  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 16:10:47.442  3900  7161 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 16:10:47.442  3900  3987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.442  3900  3987 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 16:10:47.442  3900  3987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.442  3900  3987 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 16:10:47.443  3900  3987 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 16:10:47.447  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:47.447  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.447  3900  3900 V BluetoothPbapReceiver: ***********state = 11
09-13 16:10:47.449  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:47.451  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
09-13 16:10:47.452  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:10:47.456  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:47.460  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:47.464  3900  3900 D HeadsetService: Received start request. Starting profile...
09-13 16:10:47.465  3900  3900 D HeadsetStateMachine: make
09-13 16:10:47.466  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:47.471  3900  3900 D HeadsetStateMachine: max_hf_connections = 1
09-13 16:10:47.471  3900  3900 I bluedroid-qcom: get_profile_interface handsfree
09-13 16:10:47.471  3900  3900 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 16:10:47.471  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.472  3900  7162 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 16:10:47.472  3900  7162 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 16:10:47.472  3900  7162 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 16:10:47.472  3900  7162 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 16:10:47.472   317  4021 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3900
09-13 16:10:47.472  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
09-13 16:10:47.472   317  4021 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 16:10:47.473  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:47.473   317  4021 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 16:10:47.473   317  4021 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 16:10:47.473   317  4021 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 16:10:47.473   317  4021 V voice   : voice_set_parameters: exit with code(0)
,09-13 16:10:47.473   317  4021 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 16:10:47.473   317  4021 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 16:10:47.473   317  4021 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 16:10:47.473   317  4021 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 16:10:47.473   317  4021 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 16:10:47.474   317  4021 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 16:10:47.475  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.475  3900  3900 D A2dpService: Received start request. Starting profile...
09-13 16:10:47.475  3900  3900 V Avrcp   : make
09-13 16:10:47.475  3900  3900 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 16:10:47.475  3900  3900 I bluedroid-qcom: get_profile_interface avrcp
09-13 16:10:47.475  7144  7144 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-13 16:10:47.478  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 16:10:47.479  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:47.485  3900  3900 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 16:10:47.487  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
09-13 16:10:47.487  3900  3900 E AudioManager: No RCC entry present to update
09-13 16:10:47.487  3900  3900 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 16:10:47.488  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 16:10:47.488  3900  3900 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 16:10:47.495  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 16:10:47.496  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:47.532  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:47.536  3900  3987 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 16:10:47.550  7144  7144 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 16:10:47.581  1037  2064 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:10:47.581  1037  2064 V SIM_STK : Menu title from STK is T-Mobile
,09-13 16:10:47.589  1037  1547 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-13 16:10:47.590  7144  7144 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:47.591  7144  7144 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 16:10:47.642  1037  1979 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:10:47.644  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 16:10:47.644  3900  3900 D A2dpStateMachine: make
09-13 16:10:47.645  3900  3900 I bluedroid-qcom: get_profile_interface a2dp
09-13 16:10:47.646  3900  7170 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 16:10:47.646  3900  3900 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 16:10:47.646  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.646  3900  7169 D A2dpStateMachine: Enter Disconnected: -2
09-13 16:10:47.647  3900  3900 D HeadsetStateMachine: Proxy object connected
09-13 16:10:47.647  3900  3900 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 16:10:47.647  3900  3900 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-13 16:10:47.654  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:47.654  3900  7162 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 16:10:47.654  3900  7162 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 16:10:47.654  3900  7162 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 16:10:47.655  3900  3900 D HidService: Received start request. Starting profile...
09-13 16:10:47.655  3900  3900 I bluedroid-qcom: get_profile_interface hidhost
09-13 16:10:47.655  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.656  3900  3900 D HealthService: Received start request. Starting profile...
09-13 16:10:47.657  3900  3900 I bluedroid-qcom: get_profile_interface health
09-13 16:10:47.657  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.659  3900  3900 D PanService: Received start request. Starting profile...
09-13 16:10:47.659  3900  3900 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 16:10:47.659  3900  3900 I bluedroid-qcom: get_profile_interface pan
09-13 16:10:47.660  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.661  3900  3900 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 16:10:47.662  3900  3900 D BtGatt.GattService: Received start request. Starting profile...
09-13 16:10:47.662  3900  3900 D BtGatt.GattService: start()
09-13 16:10:47.662  3900  3900 D BtGatt.AdvertiseManager: advertise manager created
,09-13 16:10:47.667  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.668  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.668  3900  3900 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 16:10:47.668  3900  3900 V BluetoothMapService: BluetoothMapBinder()
09-13 16:10:47.668  3900  3900 D BluetoothMapService: Received start request. Starting profile...
09-13 16:10:47.669  3900  3900 D BluetoothMapService: start()
09-13 16:10:47.671  3900  3900 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 16:10:47.671  3900  3900 D BluetoothMapEmailAppObserver: createReceiver()
09-13 16:10:47.672  3900  3900 D BluetoothMapEmailAppObserver: initObservers()
09-13 16:10:47.672  3900  3900 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 16:10:47.672  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:47.680  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 16:10:47.685  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:47.690  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:47.693  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:47.693  3900  3900 V PanService: [BTUI] SIM Extra State :ABSENT
,09-13 16:10:47.695  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.699  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 16:10:47.699  3900  3900 V BluetoothMapService: Handler(): got msg=1
09-13 16:10:47.700  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 16:10:47.700  3900  3987 I bluedroid-qcom: enable
09-13 16:10:47.700  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:47.700  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:47.700  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:47.700  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:47.700  3900  3987 I bt_hci_bdroid: init
09-13 16:10:47.700  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 16:10:47.701  3900  7176 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 16:10:47.701  3900  7176 I bt-btu  : btu_task pending for preload complete event
09-13 16:10:47.703  3900  3987 I bt_vendor: bt-vendor : init
09-13 16:10:47.703  3900  3987 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 16:10:47.703  3900  3987 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 16:10:47.703  3900  3987 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 16:10:47.703  3900  3987 D bt_userial_mct: userial_init
09-13 16:10:47.704  3900  3987 D bt_hci_bdroid: set_power 1
09-13 16:10:47.704  3900  3987 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 16:10:47.706  7179  7179 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:47.706  7179  7179 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 16:10:47.705  3900  3987 I bt_vendor: try to set true
09-13 16:10:47.727  7180  7180 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 16:10:47.751  7144  7144 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 16:10:47.774  7144  7144 I HubEmail: JNI_OnLoad()
,09-13 16:10:47.774  7144  7144 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 16:10:47.774  7144  7144 I HubEmail: registerNatives()
09-13 16:10:47.774  7144  7144 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 16:10:47.774  7144  7144 I HubEmail: registerNativeMethods()
09-13 16:10:47.774  7144  7144 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 16:10:47.775  7144  7144 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-13 16:10:47.782  7144  7185 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:47.789  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 16:10:47.789  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:47.789  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 16:10:47.809  7191  7191 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 16:10:47.815   313  7194 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 16:10:47.816   313  7194 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-13 16:10:47.817  7192  7192 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 16:10:47.834  7196  7196 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 16:10:47.841  7197  7197 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 16:10:47.848  7198  7198 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 16:10:47.856  7199  7199 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 16:10:47.869  1037  2096 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7201 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-13 16:10:47.876  7203  7203 I libmdmdetect: ESOC framework not supported
09-13 16:10:47.876  7203  7203 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-13 16:10:47.888  7203  7203 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 16:10:47.888  7203  7203 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 16:10:47.888  7203  7203 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,09-13 16:10:47.888  7203  7203 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 16:10:47.888  7203  7203 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 16:10:47.888  7203  7203 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 16:10:47.888  7203  7203 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-13 16:10:47.928  7203  7218 E QC-QMI  : qmi_client [7203] 14: failed to locate client data
,09-13 16:10:47.929   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-13 16:10:47.929   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 16:10:47.937  1037  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:47.937  1037  1993 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:47.937  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:47.938  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
09-13 16:10:47.941  3900  4033 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 16:10:47.941  1037  1099 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 16:10:47.943   313  7194 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-13 16:10:47.987  7201  7201 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:47.987  7201  7201 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 16:10:47.990  7201  7201 D PhoneMonitor: Register our PhoneStateListener
,09-13 16:10:48.000  7220  7220 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 16:10:48.003  6933  7187 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 16:10:48.011  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 16:10:48.012  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 16:10:48.016  7221  7221 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 16:10:48.019  6933  7187 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-13 16:10:48.031  7201  7201 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-13 16:10:48.031  7201  7201 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 16:10:48.032  7201  7201 D TelephonyAutoProfiling: [parse] Load xml
,09-13 16:10:48.038  7201  7201 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 16:10:48.038  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-13 16:10:48.038  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 16:10:48.038  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 16:10:48.038  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 16:10:48.038  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 16:10:48.038  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 16:10:48.039  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 16:10:48.039  7201  7201 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-13 16:10:48.049  7201  7201 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-13 16:10:48.058  3900  3987 I bt_vendor: bluetooth satus is on
09-13 16:10:48.058  3900  3987 D bt_hci_bdroid: preload
,09-13 16:10:48.058  3900  7178 D bt_userial_mct: userial_open(port:0)
09-13 16:10:48.058  3900  7178 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 16:10:48.059  3900  7178 I bt_vendor: Done intiailizing UART
09-13 16:10:48.059  3900  7178 I bt_vendor: Done intiailizing UART
09-13 16:10:48.059  3900  7178 I bt_userial_mct: CMD=82, EVT=82, ACL_Out=83, ACL_In=83
09-13 16:10:48.059  3900  7178 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 16:10:48.059  3900  7176 I bt-btu  : btu_task received preload complete event
09-13 16:10:48.059  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 16:10:48.059  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 16:10:48.059  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 16:10:48.060  1037  1710 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7225 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 16:10:48.062  1037  1710 I ActivityManager: Killing 6137:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 16:10:48.062  3900  7176 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 16:10:48.063  3900  7176 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 16:10:48.063  3900  7176 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 16:10:48.063  3900  7229 D bt_userial_mct: Entering userial_read_thread()
09-13 16:10:48.097  3900  7176 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 16:10:48.097  3900  7176 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0241061 
,09-13 16:10:48.097  3900  7176 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0241061 
,09-13 16:10:48.103  3900  3991 E bt-btif : Calling BTA_HhEnable
09-13 16:10:48.103  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 16:10:48.103  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 16:10:48.103  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 16:10:48.103  3900  3991 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 16:10:48.103  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 16:10:48.103  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 16:10:48.103  3900  3991 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 16:10:48.106  1037  1595 W libprocessgroup: failed to open /acct/uid_10080/pid_6137/cgroup.procs: No such file or directory
09-13 16:10:48.109  3900  7176 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 16:10:48.109  3900  7176 W bt-smp  : Plain text(LSB ~ MSB) = b3 6f 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 16:10:48.109  3900  7176 W bt-smp  : Encrypted text(LSB ~ MSB) = bf 93 1f c0 37 e8 ea f3 d0 8c 28 a7 55 44 d2 ee 
09-13 16:10:48.110  3900  7176 W bt-btm  : Stopping oneshot timer
09-13 16:10:48.112  3900  3991 D BluetoothAdapterProperties: Name is: G3
09-13 16:10:48.116  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-13 16:10:48.116  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 16:10:48.118  3900  3991 D BluetoothAdapterProperties: Scan Mode:20
09-13 16:10:48.118  3900  3991 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:10:48.118  3900  3991 D bt_hci_bdroid: postload
09-13 16:10:48.119  3900  3991 D bte_conf: Device ID record 1 : primary
09-13 16:10:48.119  3900  3991 D bte_conf:   vendorId            = 00c4
09-13 16:10:48.119  3900  3991 D bte_conf:   vendorIdSource      = 0001
09-13 16:10:48.119  3900  3991 D bte_conf:   product             = 13a1
09-13 16:10:48.119  3900  7176 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 16:10:48.119  3900  3991 D bte_conf:   version             = 1000
09-13 16:10:48.119  3900  3991 D bte_conf:   clientExecutableURL = 
09-13 16:10:48.119  3900  3991 D bte_conf:   serviceDescription  = 
09-13 16:10:48.119  3900  3991 D bte_conf:   documentationURL    = 
09-13 16:10:48.119  3900  3991 D bte_conf: bte_load_did_conf no section named DID2.
09-13 16:10:48.119  3900  7178 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:48.119  3900  7178 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:48.119  3900  7178 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:48.120  3900  7178 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:48.120  3900  7229 E bt_mct  : hci lib postload completed
09-13 16:10:48.121  3900  3991 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 16:10:48.121  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 16:10:48.121  3900  3987 D BluetoothAdapterProperties: ScanMode =  20
09-13 16:10:48.121  3900  3987 D BluetoothAdapterProperties: State =  11
09-13 16:10:48.121  3900  3987 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 16:10:48.121  3900  3987 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 16:10:48.121  3900  3987 D BluetoothAdapterProperties: Setting state to 12
09-13 16:10:48.121  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 16:10:48.122  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:48.122  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 16:10:48.123  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 16:10:48.116  7244  7244 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:48.123  3900  3987 I BluetoothAdapterState: Entering On State
09-13 16:10:48.116  7244  7244 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:48.124  3900  3987 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 16:10:48.124  3900  3987 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 16:10:48.124  3900  3987 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 16:10:48.124  3900  3991 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 16:10:48.127  3900  3987 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 16:10:48.127  6891  6906 D BluetoothPan: onBluetoothStateChange on: true
09-13 16:10:48.127  6891  6906 D BluetoothPan: onBluetoothStateChange call bindService
,09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:48.134  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:48.135  1880  2597 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:48.139  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.140  6891  6906 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 16:10:48.141  6891  6891 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 16:10:48.141  6891  6891 D PanProfile: Bluetooth service connected
,09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:48.145  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:48.147  1880  1880 D BluetoothHeadset: Proxy object connected
09-13 16:10:48.148  1880  2562 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:48.149  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.151  1880  1880 D BluetoothHeadset: Proxy object connected
09-13 16:10:48.152  6891  6907 D BluetoothMap: onBluetoothStateChange: up=true
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:48.155  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:10:48.157  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.160  6891  6891 D BluetoothMap: Proxy object connected
09-13 16:10:48.161  6891  6891 D MapProfile: Bluetooth service connected
09-13 16:10:48.161  6891  6891 D BluetoothMap: getConnectedDevices()
09-13 16:10:48.161  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:48.163  1880  1880 D BluetoothHeadset: Proxy object connected
09-13 16:10:48.163  6891  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 16:10:48.164  3900  4033 V BluetoothMapService: getConnectedDevices()
09-13 16:10:48.166  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:48.167  6891  6891 D BluetoothInputDevice: Proxy object connected
09-13 16:10:48.167  6891  6891 D HidProfile: Bluetooth service connected
09-13 16:10:48.167  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 16:10:48.167  1037  1037 D BluetoothHeadset: Proxy object connected
09-13 16:10:48.168  1037  1099 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 16:10:48.168  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-13 16:10:48.171  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:48.173  3900  3987 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 16:10:48.174  3900  3991 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:10:48.174  3900  3991 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 16:10:48.174  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.174  1969  2173 D LGBluetoothAPIService: Message: 1
09-13 16:10:48.174  1969  2173 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 16:10:48.183  1037  1037 D BluetoothA2dp: Proxy object connected
09-13 16:10:48.183  1842  7245 I CheckinService: active receiver: enabled
09-13 16:10:48.184  7251  7251 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 16:10:48.184  1969  2173 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-13 16:10:48.197  6736  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 16:10:48.200  3900  3900 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.200  3900  3900 D BluetoothMapService: STATE_ON
09-13 16:10:48.200  3900  3900 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 16:10:48.200  3900  3900 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 16:10:48.201  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.201  1842  7245 I CheckinService: Preparing to send checkin request
09-13 16:10:48.201  1842  7245 I EventLogService: Accumulating logs since 1473775705285
09-13 16:10:48.202  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:48.202  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 16:10:48.202  3900  3900 V BluetoothPbapService: Pbap Service onCreate
09-13 16:10:48.202  3900  3900 V BluetoothPbapService: Starting PBAP service
09-13 16:10:48.202  1969  2173 D LGBluetoothAPIService: Message: 100
09-13 16:10:48.202  1969  2173 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 16:10:48.203  3900  3900 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 16:10:48.203  3900  3900 V BluetoothMapService: Handler(): got msg=1
09-13 16:10:48.203  3900  3900 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 16:10:48.203  3900  3900 V BluetoothPbapService: Pbap Service onBind
09-13 16:10:48.204  3900  7255 D BluetoothMapMasInstance: MAS initSocket()
09-13 16:10:48.204  3900  7255 D BluetoothMapMasInstance:   masId = 00
09-13 16:10:48.204  3900  7255 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 16:10:48.204  3900  7255 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 16:10:48.204  3900  7255 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 16:10:48.204  3900  3900 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.204  3900  3900 V BluetoothPbapService: state: 12
09-13 16:10:48.204  3900  3900 V BluetoothPbapService: Handler(): got msg=1
09-13 16:10:48.205  3900  3900 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 16:10:48.206  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.206  3900  7256 V BluetoothPbapService: Pbap Service initSocket
09-13 16:10:48.206  1037  2096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:48.206  1037  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:48.208  3900  7255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:48.209  6891  6891 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 16:10:48.210  3900  7256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:48.211  3900  7256 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=82
09-13 16:10:48.211  3900  7255 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=89 mFd=87
09-13 16:10:48.212  3900  7255 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 16:10:48.212  3900  7255 D BluetoothMapMasInstance: Accepting socket connection...
09-13 16:10:48.212  3900  7256 V BluetoothPbapService: Succeed to create listening socket 
09-13 16:10:48.212  3900  7256 V BluetoothPbapService: Accepting socket connection...
09-13 16:10:48.212  3900  3991 D BluetoothAdapterProperties: Scan Mode:21
09-13 16:10:48.212  3900  3991 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 16:10:48.213  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.213  1037  1099 D BluetoothManagerService: Message: 30
,09-13 16:10:48.216  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.217  6891  6891 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 16:10:48.220  1037  1099 D BluetoothManagerService: Message: 30
09-13 16:10:48.220  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.222  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.224  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 16:10:48.242  1842  7245 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 16:10:48.319  1037  1595 I art     : Explicit concurrent mark sweep GC freed 91524(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.301ms total 93.384ms
09-13 16:10:48.320  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 16:10:48.350  1037  2096 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7259 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 16:10:48.352  1037  2096 I ActivityManager: Killing 6597:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-13 16:10:48.369  1037  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 16:10:48.370  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 16:10:48.370  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:48.371  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:48.371  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:48.372  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:48.372  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-13 16:10:48.372  1037  1547 D ConnectivityService: identical MTU - not setting
09-13 16:10:48.372  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 16:10:48.372  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 16:10:48.372  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:48.372  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:48.373  1037  1547 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:48.373  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 16:10:48.390  6891  6891 D BluetoothPbap: Proxy object connected
09-13 16:10:48.391  6891  6891 D PbapServerProfile: Bluetooth service connected
09-13 16:10:48.391  6891  6891 D BluetoothA2dp: Proxy object connected
09-13 16:10:48.391  6891  6891 D A2dpProfile: Bluetooth service connected
,09-13 16:10:48.434  1037  1720 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7276 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-13 16:10:48.435  1037  1054 W libprocessgroup: failed to open /acct/uid_10061/pid_6597/cgroup.procs: No such file or directory
,09-13 16:10:48.444  6736  7068 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.448  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:48.449  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:10:48.454  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:48.454  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.455  3900  3900 V BluetoothPbapReceiver: ***********state = 12
09-13 16:10:48.460  6891  6891 D BluetoothHeadset: Proxy object connected
09-13 16:10:48.461  6891  6891 D HeadsetProfile: Bluetooth service connected
09-13 16:10:48.461  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:10:48.462  2276  2276 D c       : Getting all permits...
09-13 16:10:48.462  2276  2276 D a       : Opening database...
09-13 16:10:48.465  1037  1595 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:48.465  1037  1595 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
,09-13 16:10:48.467  6891  6891 D DockEventReceiver: finishStartingService: stopping service
09-13 16:10:48.473  2276  2276 D a       : Opening database auth.proximity.permit_store...
09-13 16:10:48.474  2276  2276 D a       : Closing database...
09-13 16:10:48.475  1037  1950 I ActivityManager: Killing 6167:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-13 16:10:48.478  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:48.479  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:48.479  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-13 16:10:48.479  1037  1099 D BluetoothManagerService: Message: 2
,09-13 16:10:48.480  1037  1099 D BluetoothManagerService: Sending off request.
09-13 16:10:48.480  3900  7253 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 16:10:48.481  3900  3987 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 16:10:48.481  3900  3987 D BluetoothAdapterProperties: Setting state to 13
09-13 16:10:48.481  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 16:10:48.481  3900  3987 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 16:10:48.482  3900  3987 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 16:10:48.482  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:48.482  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 16:10:48.482  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 16:10:48.530  3900  3991 D BluetoothAdapterProperties: Scan Mode:20
,09-13 16:10:48.530  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 16:10:48.530  3900  7256 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:48.531  3900  3987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 16:10:48.531  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 16:10:48.531  3900  7176 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 16:10:48.533  3900  7255 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 16:10:48.535  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 16:10:48.535  3900  7176 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 16:10:48.536  1037  1993 W libprocessgroup: failed to open /acct/uid_10097/pid_6167/cgroup.procs: No such file or directory
09-13 16:10:48.543  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.543  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 16:10:48.552  3900  3900 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.552  3900  3900 D BluetoothMapService: STATE_TURNING_OFF
09-13 16:10:48.552  3900  3900 V BluetoothMapService: Handler(): got msg=4
09-13 16:10:48.552  3900  3900 D BluetoothMapService: MAP Service closeService in
09-13 16:10:48.552  3900  3900 D BluetoothMapMasInstance: MAP Service shutdown
09-13 16:10:48.553  3900  3900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 16:10:48.553  3900  3900 V BluetoothMapService: MAP Service closeService out
,09-13 16:10:48.553  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-13 16:10:48.556  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:48.556  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:48.557  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:48.557  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.560  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:48.561  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:48.562  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:48.562  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.565  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:48.570  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:48.576  7276  7276 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 16:10:48.576  7276  7276 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 16:10:48.607  7276  7276 I MultiDex: VM with version 2.1.0 has multidex support
09-13 16:10:48.607  7276  7276 I MultiDex: install
,09-13 16:10:48.607  7276  7276 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 16:10:48.613  1037  1950 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7296 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 16:10:48.635   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 385us total 22.514ms
,09-13 16:10:48.637  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:48.639  7276  7276 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 16:10:48.641  6891  6891 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 16:10:48.645  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 16:10:48.648  1037  1720 I ActivityManager: Killing 6631:com.lge.eula/1000 (adj 15): empty #17
,09-13 16:10:48.653   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 337us total 16.884ms
,09-13 16:10:48.668   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 14.087ms
,09-13 16:10:48.690  3900  3900 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-13 16:10:48.693  3900  3900 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-13 16:10:48.703  1037  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_6631/cgroup.procs: No such file or directory
,09-13 16:10:48.714  3900  3900 V BtOppService: onCreate
09-13 16:10:48.714  3900  3900 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 16:10:48.716  3900  3900 V BluetoothOppNotification: send message
09-13 16:10:48.719  3900  3900 D BluetoothOppPreference: Dumping Names:  
09-13 16:10:48.719  3900  3900 D BluetoothOppPreference: {}
09-13 16:10:48.719  3900  3900 D BluetoothOppPreference: Dumping Channels:  
09-13 16:10:48.719  3900  3900 D BluetoothOppPreference: {}
09-13 16:10:48.719  3900  3900 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 16:10:48.719  3900  3900 V BtOppService: onStartCommand
,09-13 16:10:48.723  3900  3900 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 16:10:48.724  3900  7314 V BtOppService: Deleted complete outbound shares, number =  0
09-13 16:10:48.725  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.725  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 16:10:48.726  3900  7314 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 16:10:48.726  3900  7314 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 16:10:48.728  3900  7314 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20815b1b on behalf of 
09-13 16:10:48.730  3900  3900 V BluetoothOppNotification: previous thread is not finished yet
09-13 16:10:48.730  3900  3900 V BtOppService: ContentObserver received notification
09-13 16:10:48.730  3900  3900 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 16:10:48.730  3900  3900 V BtOppService: ContentObserver received notification
09-13 16:10:48.730  3900  3900 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 16:10:48.731  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:48.731  3900  3900 V BluetoothFtpService: Ftp Service onCreate
09-13 16:10:48.731  3900  3900 I BluetoothFtpService: Ftp Service onCreate
09-13 16:10:48.731  3900  3900 V BluetoothFtpService: Ftp Service onStartCommand
09-13 16:10:48.731  3900  3900 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.731  3900  3900 V BluetoothFtpService: Starting Listening on sockets
09-13 16:10:48.736  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:48.737  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:48.737  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
,09-13 16:10:48.737  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.737  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 16:10:48.737  3900  3900 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 16:10:48.739  3900  3900 V BluetoothFtpService: Handler(): got msg=1
09-13 16:10:48.740  3900  3900 V BluetoothFtpService: Ftp Service closeService
09-13 16:10:48.744  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:48.744  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:48.744  1037  1539 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:48.747  7296  7296 I art     : Almond Protected OAT
09-13 16:10:48.747  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 16:10:48.748  3900  3900 V BluetoothFtpService: successfully stopped ftp service
09-13 16:10:48.748  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:48.748  3900  3900 V BluetoothSapService: Sap Service onCreate
,09-13 16:10:48.751  3900  3900 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.751  3900  3900 V BluetoothSapService: state: 12
09-13 16:10:48.751  3900  3900 V BluetoothSapService: Starting SAP server process
09-13 16:10:48.752  3900  3900 V BluetoothFtpService: Ftp Service onDestroy
09-13 16:10:48.752  3900  3900 V BluetoothFtpService: Ftp Service closeService
09-13 16:10:48.746  7316  7316 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 16:10:48.746  7316  7316 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:48.759  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:48.759  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 16:10:48.759  3900  3900 V BluetoothPbapReceiver: ***********state = 13
09-13 16:10:48.760  6891  6891 D DockEventReceiver: finishStartingService: stopping service
09-13 16:10:48.764  7316  7316 V BT_SAP  : Event pipe created
09-13 16:10:48.764  7316  7316 V BT_SAP  : create_server_socket qcom.sap.server
09-13 16:10:48.764  7316  7316 V BT_SAP  : created socket fd 6
09-13 16:10:48.769  3900  3900 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 16:10:48.773  3900  3900 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 16:10:48.773  3900  3900 V BluetoothPbapService: state: 13
09-13 16:10:48.773  3900  3900 V BluetoothPbapService: Pbap Service closeService in
09-13 16:10:48.775  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:10:48.776  3900  3900 V BluetoothPbapService: successfully stopped pbap service
09-13 16:10:48.776  3900  3900 V BluetoothPbapService: Pbap Service closeService out
09-13 16:10:48.776  3900  3900 V BluetoothPbapService: Pbap Service onDestroy
09-13 16:10:48.776  3900  3900 V BluetoothPbapService: Pbap Service closeService in
09-13 16:10:48.776  3900  3900 V BluetoothPbapService: Pbap Service closeService out
09-13 16:10:48.776  3900  3900 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 16:10:48.777  6891  6891 D BluetoothPbap: Proxy object disconnected
09-13 16:10:48.777  6891  6891 D PbapServerProfile: Bluetooth service disconnected
09-13 16:10:48.785  6891  6891 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 16:10:48.789  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:48.789  6891  6891 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 16:10:48.794  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 16:10:48.797  3900  3900 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-13 16:10:48.797  3900  3900 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 16:10:48.798  3900  3900 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 16:10:48.801  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.801  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 16:10:48.803  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:48.804  3900  3900 V BluetoothFtpService: Ftp Service onCreate
09-13 16:10:48.804  3900  3900 I BluetoothFtpService: Ftp Service onCreate
09-13 16:10:48.804  3900  3900 V BluetoothFtpService: Ftp Service onStartCommand
09-13 16:10:48.804  3900  3900 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.804  3900  3900 V BluetoothFtpService: Ftp Service closeService
09-13 16:10:48.804  3900  3900 V BluetoothFtpService: successfully stopped ftp service
09-13 16:10:48.805  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:48.805  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:48.805  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:48.805  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:48.805  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 16:10:48.805  3900  3900 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 16:10:48.806  3900  3900 V BluetoothFtpService: Ftp Service onDestroy
09-13 16:10:48.806  3900  3900 V BluetoothFtpService: Ftp Service closeService
09-13 16:10:48.807  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 16:10:48.808  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 16:10:48.808  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 16:10:48.809  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 16:10:48.809  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 16:10:48.809  1037  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 16:10:48.811  3900  3900 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 16:10:48.811  3900  3900 V BluetoothSapService: state: 13
09-13 16:10:48.811  3900  3900 V BluetoothSapService: Stopping SAP server process
09-13 16:10:48.812  3900  3900 V BluetoothSapService: Sap Service closeSapService in
09-13 16:10:48.812  3900  3900 V BluetoothSapService: Close listen Socket : 
09-13 16:10:48.812  3900  3900 V BluetoothSapService: Close rfcomm Socket : 
09-13 16:10:48.812  3900  3900 V BluetoothSapService: Close sapd  Socket : 
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Sap Service closeSapService out
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Sap Service onDestroy
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Sap Service closeSapService in
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Close listen Socket : 
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Close rfcomm Socket : 
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Close sapd  Socket : 
09-13 16:10:48.815  3900  3900 V BluetoothSapService: Sap Service closeSapService out
09-13 16:10:48.832  7296  7296 D WeatherApplication: removeAccount
,09-13 16:10:48.834  7296  7296 D WeatherApplication: Account.length = 0
,09-13 16:10:48.834  7296  7296 E WeatherApplication: OPERATOR:OPEN
09-13 16:10:48.838  7296  7296 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:48
09-13 16:10:48.840  7296  7296 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 16:10:48.840  7296  7296 D Weather.Utils: 2 : All the weather widget is gone.
09-13 16:10:48.841  7296  7296 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 16:10:48.843  7296  7296 D WeatherAncestor: connectivity changed - connection : true
09-13 16:10:48.844  7296  7296 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-13 16:10:48.850  7296  7296 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-13 16:10:48.851  7296  7296 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 16:10:48.851  7296  7296 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-13 16:10:48.869  7296  7296 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 16:10:48.869  7296  7296 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:48
,09-13 16:10:48.899  1037  2087 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7318 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 16:10:48.900  1037  2087 I ActivityManager: Killing 2202:com.lge.music/u0a34 (adj 15): empty #17
,09-13 16:10:48.942   317  1386 V AudioFlinger: 2202 died, releasing its sessions
09-13 16:10:48.942   317  1386 V AudioFlinger:  pid 1880 @ 0
,09-13 16:10:48.942   317  1386 V AudioFlinger:  pid 3468 @ 1
,09-13 16:10:48.942   317  1386 V AudioFlinger:  pid 3468 @ 2
09-13 16:10:48.975  7276  7293 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:10:48.975  7276  7293 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 16:10:48.981  1037  2016 W libprocessgroup: failed to open /acct/uid_10034/pid_2202/cgroup.procs: No such file or directory
09-13 16:10:48.987  6736  7290 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:48.987  6736  7290 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:48.988  6736  7290 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:10:48.988  6736  7290 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:48.994  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:49.007  1037  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:49.007  1037  1934 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
,09-13 16:10:49.017  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:49.018  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
09-13 16:10:49.018  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:49.018  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:49.018  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-13 16:10:49.021  3900  7253 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 16:10:49.021  1037  1099 E BluetoothManagerService: IBluetooth.enable() returned false
,09-13 16:10:49.085   280   380 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 16:10:49.085   280   380 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 16:10:49.085   280   380 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 16:10:49.086  7318  7338 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 16:10:49.089   280   380 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 16:10:49.089   280   380 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 16:10:49.089   280   380 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 16:10:49.091  7318  7338 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 16:10:49.110   280   380 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 16:10:49.110   280   380 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 16:10:49.110   280   380 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 16:10:49.111  7318  7342 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 16:10:49.112   280   380 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 16:10:49.112   280   380 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 16:10:49.113   280   380 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 16:10:49.113  7318  7342 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-13 16:10:49.190  7344  7344 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 16:10:49.249  7344  7344 I dex2oat : dex2oat took 58.776ms (threads: 4)
,09-13 16:10:49.261  7276  7293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:10:49.261  7276  7293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:10:49.261  7276  7293 I Adreno-EGL: Build Date: 12/12/14 금
09-13 16:10:49.261  7276  7293 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 16:10:49.261  7276  7293 I Adreno-EGL: Remote Branch: 
09-13 16:10:49.261  7276  7293 I Adreno-EGL: Local Patches: 
09-13 16:10:49.261  7276  7293 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:10:49.328  7318  7318 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 16:10:49.338  7318  7318 I LibraryLoader: Loading: webviewchromium
09-13 16:10:49.342  7318  7318 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2430-2434)
09-13 16:10:49.342  7318  7318 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:10:49.351  7318  7318 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1206837b}
,09-13 16:10:49.355  7318  7318 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:10:49.356  7318  7318 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 16:10:49.358  7276  7293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:10:49.358  7276  7293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:10:49.358  7276  7293 I Adreno-EGL: Build Date: 12/12/14 금
09-13 16:10:49.358  7276  7293 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 16:10:49.358  7276  7293 I Adreno-EGL: Remote Branch: 
09-13 16:10:49.358  7276  7293 I Adreno-EGL: Local Patches: 
09-13 16:10:49.358  7276  7293 I Adreno-EGL: Reconstruct Branch: 
09-13 16:10:49.376  7318  7318 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 16:10:49.377  7318  7318 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:10:49.400   317   317 V AudioPolicyService: registerClient() client 0xb558a300, uid 10093
,09-13 16:10:49.403  7318  7369 W AudioManagerAndroid: Requires BLUETOOTH permission
09-13 16:10:49.403  7318  7318 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 16:10:49.405  7318  7318 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 16:10:49.405  7318  7318 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-13 16:10:49.424  7318  7318 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:10:49.424  7318  7318 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:10:49.424  7318  7318 I Adreno-EGL: Build Date: 12/12/14 금
09-13 16:10:49.424  7318  7318 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 16:10:49.424  7318  7318 I Adreno-EGL: Remote Branch: 
09-13 16:10:49.424  7318  7318 I Adreno-EGL: Local Patches: 
09-13 16:10:49.424  7318  7318 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:10:49.492  1037  1540 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=82.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:602066964] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:49.494  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=82.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:602066966] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:49.494  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 16:10:49.516  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:49.520  7318  7318 I NSApplication: Starting up...
09-13 16:10:49.521  1037  2064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:49.521  1037  2064 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:49.521  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:49.522  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
09-13 16:10:49.524  3900  7253 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
,09-13 16:10:49.524  1037  1099 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 16:10:49.540  3900  3991 D bt_hci_bdroid: cleanup
09-13 16:10:49.540  3900  7178 I bt_lpm  : LPM is already off!!!
09-13 16:10:49.541  3900  7176 W bt-btif : ag scb idx 1 not allocated
09-13 16:10:49.541  3900  7176 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 16:10:49.541  3900  7176 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 16:10:49.541  3900  7176 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 16:10:49.547  1037  1542 V WifiInternetCheck: Single check msg out of sync, ignoring.
09-13 16:10:49.548  3900  7229 I bt_userial_mct: exiting userial_read_thread
09-13 16:10:49.548  3900  7229 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 16:10:49.548  3900  3991 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 16:10:49.549  3900  7178 I bt_vendor: hw_epilog_process
09-13 16:10:49.549  3900  3991 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 16:10:49.549  3900  3991 D bt_userial_mct: userial_close
09-13 16:10:49.549  3900  3991 E bt_userial_mct: pthread_join() FAILED result:3
09-13 16:10:49.549  3900  3991 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-13 16:10:49.561  7276  7293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:10:49.561  7276  7293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:10:49.561  7276  7293 I Adreno-EGL: Build Date: 12/12/14 금
09-13 16:10:49.561  7276  7293 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 16:10:49.561  7276  7293 I Adreno-EGL: Remote Branch: 
09-13 16:10:49.561  7276  7293 I Adreno-EGL: Local Patches: 
09-13 16:10:49.561  7276  7293 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:10:49.575  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:49.592  1037  2016 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7383 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 16:10:49.593  1037  2016 I ActivityManager: Killing 6099:com.android.vending/u0a44 (adj 15): empty #17
09-13 16:10:49.722  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:49.722  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 16:10:49.723  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-13 16:10:49.728  3900  3991 D bt_hci_bdroid: set_power 0
09-13 16:10:49.728  3900  3991 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 16:10:49.728  3900  3991 I bt_vendor: bluetooth satus is on
09-13 16:10:49.728  3900  3991 I bt_vendor: bt-vendor : resetting BT status
09-13 16:10:49.728  3900  3991 I bt_vendor: Starting hciattach daemon
09-13 16:10:49.728  3900  3991 I bt_vendor: try to set false
09-13 16:10:49.729  3900  3991 I bt_vendor: Starting hciattach daemon
09-13 16:10:49.729  3900  3991 I bt_vendor: try to set false
09-13 16:10:49.730  3900  3991 I bt_vendor: cleanup
09-13 16:10:49.731  3900  7176 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 16:10:49.732  3900  3900 V BluetoothOppNotification: previous thread is not finished yet
09-13 16:10:49.732  3900  3991 I GKI_LINUX: GKI_exit_task 0 done
09-13 16:10:49.732  3900  3991 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 16:10:49.733  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-13 16:10:49.738  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 16:10:49.739  1037  2087 W libprocessgroup: failed to open /acct/uid_10044/pid_6099/cgroup.procs: No such file or directory
,09-13 16:10:49.743  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:49.745  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:49.764  3900  3900 D HeadsetService: Received stop request...Stopping profile...
,09-13 16:10:49.764  3900  3900 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 16:10:49.764  3900  3900 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:10:49.764  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.765  3900  7162 D HeadsetStateMachine: Exit Disconnected: -1
09-13 16:10:49.766  1880  1880 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:49.766  1880  1880 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:49.767  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:49.768  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 16:10:49.768  1880  1880 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:49.768  3900  3900 D A2dpService: Received stop request...Stopping profile...
09-13 16:10:49.768  3900  7169 D A2dpStateMachine: Exit Disconnected: -1
09-13 16:10:49.769  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 16:10:49.769  6891  6891 D BluetoothHeadset: Proxy object disconnected
09-13 16:10:49.769  6891  6891 D HeadsetProfile: Bluetooth service disconnected
09-13 16:10:49.771  3900  3900 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 16:10:49.771  3900  3900 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:10:49.771  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.771  3900  3987 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 16:10:49.772  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-13 16:10:49.772  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 16:10:49.772  6891  6891 D BluetoothA2dp: Proxy object disconnected
09-13 16:10:49.772  6891  6891 D A2dpProfile: Bluetooth service disconnected
09-13 16:10:49.773  3900  3900 D HidService: Received stop request...Stopping profile...
09-13 16:10:49.773  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.774  3900  3900 D HeadsetStateMachine: Unbinding service...
09-13 16:10:49.777  6891  6891 D BluetoothInputDevice: Proxy object disconnected
09-13 16:10:49.777  6891  6891 D HidProfile: Bluetooth service disconnected
09-13 16:10:49.779  3900  3900 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 16:10:49.779  3900  3900 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 16:10:49.779  3900  3900 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 16:10:49.779  3900  3900 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 16:10:49.779  3900  3900 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 16:10:49.780  3900  3900 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:10:49.780  3900  3900 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-13 16:10:49.783  3900  3900 D HealthService: Received stop request...Stopping profile...
09-13 16:10:49.783  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.784  3900  3900 D PanService: Received stop request...Stopping profile...
09-13 16:10:49.785  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.786  3900  3900 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 16:10:49.786  3900  3900 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 16:10:49.786  3900  3900 D BtGatt.GattService: stop()
09-13 16:10:49.786  3900  3900 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 16:10:49.787  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.788  6891  6891 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 16:10:49.788  6891  6891 D PanProfile: Bluetooth service disconnected
09-13 16:10:49.788  3900  3900 D BluetoothMapService: Received stop request...Stopping profile...
09-13 16:10:49.788  3900  3900 D BluetoothMapService: stop()
09-13 16:10:49.789  3900  3900 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 16:10:49.789  3900  3900 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 16:10:49.789  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:49.790  6891  6891 D BluetoothMap: Proxy object disconnected
09-13 16:10:49.790  6891  6891 D MapProfile: Bluetooth service disconnected
09-13 16:10:49.790  3900  3900 I BluetoothA2dpServiceJni: cleanupNative
09-13 16:10:49.790  3900  7170 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 16:10:49.791  3900  3900 I GKI_LINUX: GKI_exit_task 2 done
09-13 16:10:49.791  3900  3900 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 16:10:49.791  3900  3900 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 16:10:49.791  3900  3900 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 16:10:49.791  3900  3900 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 16:10:49.791  3900  3900 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 16:10:49.791  3900  3900 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 16:10:49.792  3900  3900 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 16:10:49.792  3900  3900 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 16:10:49.792  3900  3900 V BluetoothMapService: Handler(): got msg=4
09-13 16:10:49.792  3900  3900 D BluetoothMapService: MAP Service closeService in
09-13 16:10:49.792  3900  3900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 16:10:49.792  3900  3900 V BluetoothMapService: MAP Service closeService out
09-13 16:10:49.793  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 16:10:49.793  3900  3987 D BluetoothAdapterProperties: Setting state to 10
09-13 16:10:49.793  3900  3900 D BluetoothMapService: cleanup()
09-13 16:10:49.793  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 16:10:49.793  3900  3900 D BluetoothMapService: MAP Service closeService in
09-13 16:10:49.793  3900  3900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 16:10:49.793  3900  3900 V BluetoothMapService: MAP Service closeService out
09-13 16:10:49.793  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:49.793  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,09-13 16:10:49.793  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 16:10:49.794  3900  3987 I BluetoothAdapterState: Entering OffState
09-13 16:10:49.794  6891  6906 D BluetoothPan: onBluetoothStateChange on: false
09-13 16:10:49.795  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:49.795   313  7401 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 16:10:49.795   313  7401 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-13 16:10:49.795  6891  6907 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 16:10:49.796  7383  7383 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:10:49.796  6891  7249 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:49.797  6891  6906 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:10:49.797  1880  2597 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:49.798  6891  6907 D BluetoothMap: onBluetoothStateChange: up=false
09-13 16:10:49.799  1880  1896 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:49.800  6891  7249 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 16:10:49.800  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:10:49.800  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:10:49.800  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 16:10:49.802  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:49.802  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:49.802  1969  2173 D LGBluetoothAPIService: Message: 2
09-13 16:10:49.802  1969  2173 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2fb93159 mBinding = false
09-13 16:10:49.802  1969  2173 D LGBluetoothAPIService: Sending unbind request.
09-13 16:10:49.806  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 16:10:49.806  6891  6891 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 16:10:49.807  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:49.807  3900  3900 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 16:10:49.807  3900  3900 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-13 16:10:49.808  3900  3900 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 16:10:49.808  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 16:10:49.819  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:49.821  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:49.821  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:49.821  3900  3900 V BluetoothPbapReceiver: ***********state = 10
,09-13 16:10:49.824  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:10:49.829  6891  6891 D DockEventReceiver: finishStartingService: stopping service
09-13 16:10:49.840  6891  6891 D BluetoothPermissionRequest: onReceive
,09-13 16:10:49.840   313  7401 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-13 16:10:49.842  6891  6891 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 16:10:49.842  6891  6891 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 16:10:49.845  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 16:10:49.852  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 16:10:49.854  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:49.854  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:49.854  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:49.854  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:49.854  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 16:10:49.856  7049  7049 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 16:10:49.937  1842  7245 I CheckinTask: Sending checkin request (7838 bytes)
,09-13 16:10:50.031  1037  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:50.031  1037  1934 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:50.032  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:50.032  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
,09-13 16:10:50.038  3900  3987 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 16:10:50.038  3900  3987 D BluetoothAdapterProperties: Setting state to 11
09-13 16:10:50.038  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 16:10:50.039  3900  3987 D BluetoothBondStateMachine: make
09-13 16:10:50.040  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:50.040  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,09-13 16:10:50.040  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 16:10:50.041  3900  3987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.041  3900  3987 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 16:10:50.042  3900  3987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.042  3900  3987 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 16:10:50.042  3900  3987 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 16:10:50.043  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.043  3900  7406 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 16:10:50.044  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:50.047  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 16:10:50.052  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:50.057  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:50.058  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.058  3900  3900 V BluetoothPbapReceiver: ***********state = 11
09-13 16:10:50.058  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:50.061  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:10:50.061  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:50.067  3900  3900 D HeadsetService: Received start request. Starting profile...
09-13 16:10:50.067  3900  3900 D HeadsetStateMachine: make
09-13 16:10:50.075  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:50.078  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:50.079  3900  3900 D HeadsetStateMachine: max_hf_connections = 1
09-13 16:10:50.079  3900  3900 I bluedroid-qcom: get_profile_interface handsfree
09-13 16:10:50.079  3900  3900 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 16:10:50.079  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.080  3900  7407 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 16:10:50.080  3900  7407 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 16:10:50.080  3900  7407 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 16:10:50.080  3900  7407 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 16:10:50.081   317  1386 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3900
09-13 16:10:50.081  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.081   317  1386 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 16:10:50.081   317  1386 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 16:10:50.081   317  1386 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 16:10:50.081   317  1386 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 16:10:50.081   317  1386 V voice   : voice_set_parameters: exit with code(0)
09-13 16:10:50.081   317  1386 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 16:10:50.081   317  1386 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 16:10:50.081  3900  3900 D HeadsetStateMachine: Proxy object connected
09-13 16:10:50.081  3900  3900 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 16:10:50.081  3900  3900 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 16:10:50.081   317  1386 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 16:10:50.081   317  1386 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,09-13 16:10:50.081   317  1386 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 16:10:50.081   317  1386 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 16:10:50.086  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:50.086  3900  7407 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 16:10:50.087  3900  3900 D A2dpService: Received start request. Starting profile...
09-13 16:10:50.087  3900  3900 V Avrcp   : make
09-13 16:10:50.087  3900  3900 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 16:10:50.087  3900  3900 I bluedroid-qcom: get_profile_interface avrcp
09-13 16:10:50.087  3900  7407 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 16:10:50.087  3900  7407 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 16:10:50.089  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
09-13 16:10:50.089  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 16:10:50.093  3900  3900 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 16:10:50.094  3900  3900 E AudioManager: No RCC entry present to update
09-13 16:10:50.094  3900  3900 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 16:10:50.094  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 16:10:50.094  3900  3900 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 16:10:50.098  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 16:10:50.109  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:50.139  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:50.145  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 16:10:50.150  3900  3987 E BluetoothAdapterService: File transfer profiles supported!!
09-13 16:10:50.154  3900  3987 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 16:10:50.172  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 16:10:50.175  6466  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 16:10:50.183  1037  2064 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:10:50.183  1037  2064 V SIM_STK : Menu title from STK is T-Mobile
,09-13 16:10:50.193  2276  2276 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:50.202  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 16:10:50.202  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.202  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 16:10:50.202  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 16:10:50.204  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
09-13 16:10:50.206  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:50.206  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:50.207  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:50.207  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:50.207  7102  7102 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 16:10:50.210  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:50.211  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:50.212  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:50.213  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:50.217  3525  3525 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.218  4333  7416 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:50.219  3525  3525 V DownloadManager: DownloadService onCreate
09-13 16:10:50.220  4333  7416 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 16:10:50.222  3525  7418 I DownloadManager: in removeSpuriousFiles
09-13 16:10:50.222  3525  7418 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 16:10:50.224  3525  7418 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1d57165e on behalf of 3525
09-13 16:10:50.224  4333  7417 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.224  4333  7417 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:50.224  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 16:10:50.225  3525  7418 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-13 16:10:50.230  3525  3525 V DownloadManager: DownloadService onStartCommand
09-13 16:10:50.230  1037  1993 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 16:10:50.231  3525  7419 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:10:50.231  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 16:10:50.231  3900  3900 D A2dpStateMachine: make
09-13 16:10:50.232  3900  3900 I bluedroid-qcom: get_profile_interface a2dp
09-13 16:10:50.232  3900  7423 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 16:10:50.233  3525  7418 I DownloadManager: in trimDatabase
09-13 16:10:50.233  3525  7418 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 16:10:50.238  3900  3900 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 16:10:50.238  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.239  3900  7422 D A2dpStateMachine: Enter Disconnected: -2
,09-13 16:10:50.241  3525  7418 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@5ea0055 on behalf of 3525
09-13 16:10:50.242  3525  7419 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@277a3a6a on behalf of 3525
09-13 16:10:50.243  3900  3900 D HidService: Received start request. Starting profile...
09-13 16:10:50.243  3900  3900 I bluedroid-qcom: get_profile_interface hidhost
09-13 16:10:50.243  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.244  3900  3900 D HealthService: Received start request. Starting profile...
09-13 16:10:50.244  7144  7421 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:50.245  3900  3900 I bluedroid-qcom: get_profile_interface health
09-13 16:10:50.245  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.246  3900  3900 D PanService: Received start request. Starting profile...
09-13 16:10:50.246  3900  3900 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 16:10:50.246  3900  3900 I bluedroid-qcom: get_profile_interface pan
09-13 16:10:50.247  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.247  3900  3900 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 16:10:50.247  3900  3900 D BtGatt.GattService: Received start request. Starting profile...
09-13 16:10:50.247  3900  3900 D BtGatt.GattService: start()
09-13 16:10:50.247  3900  3900 D BtGatt.AdvertiseManager: advertise manager created
09-13 16:10:50.248  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 16:10:50.248  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.250  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 16:10:50.251  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.251  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.251  3900  3900 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 16:10:50.251  3900  3900 V BluetoothMapService: BluetoothMapBinder()
09-13 16:10:50.252  3900  3900 D BluetoothMapService: Received start request. Starting profile...
09-13 16:10:50.252  3900  3900 D BluetoothMapService: start()
09-13 16:10:50.253  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 16:10:50.255  3900  3900 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 16:10:50.255  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 16:10:50.255  3900  3900 D BluetoothMapEmailAppObserver: createReceiver()
09-13 16:10:50.256  4333  7416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 16:10:50.257  3525  7419 V DownloadManager: processing inserted download 1
09-13 16:10:50.257  3525  7419 V DownloadManager: processing inserted download 4
09-13 16:10:50.258  3525  7419 V DownloadManager: processing inserted download 7
09-13 16:10:50.259  3525  7419 V DownloadManager: processing inserted download 8
09-13 16:10:50.259  3525  7419 V DownloadManager: processing inserted download 9
09-13 16:10:50.260  3525  7419 V DownloadManager: processing inserted download 10
09-13 16:10:50.261  3525  7419 V DownloadManager: processing inserted download 11
09-13 16:10:50.261  3525  7419 V DownloadManager: processing inserted download 12
09-13 16:10:50.262  3525  7419 V DownloadManager: processing inserted download 13
09-13 16:10:50.262  3525  7419 V DownloadManager: processing inserted download 14
09-13 16:10:50.263  4333  4333 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 16:10:50.263  3525  7419 V DownloadManager: processing inserted download 16
09-13 16:10:50.263  4333  4333 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,09-13 16:10:50.263  4333  4333 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 16:10:50.264  4333  4333 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 16:10:50.266  3900  3900 D BluetoothMapEmailAppObserver: initObservers()
09-13 16:10:50.266  3900  3900 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 16:10:50.266  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.266  4333  4333 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 16:10:50.270  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:50.273  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:50.275  7296  7296 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:50
09-13 16:10:50.276  3525  3525 V DownloadManager: DownloadService onDestroy
,09-13 16:10:50.277  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.278  7296  7296 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 16:10:50.278  7296  7296 D Weather.Utils: 2 : All the weather widget is gone.
09-13 16:10:50.279  7296  7296 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 16:10:50.279  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 16:10:50.279  7296  7296 D WeatherAncestor: connectivity changed - connection : true
09-13 16:10:50.279  7296  7296 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2266284e
09-13 16:10:50.280  7296  7296 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 16:10:50.280  7296  7296 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 16:10:50.280  7296  7296 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 16:10:50.280  7296  7296 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 16:10:50.280  7296  7296 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:50
09-13 16:10:50.281  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 16:10:50.281  3900  3900 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 16:10:50.284  3900  3900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 16:10:50.284  3900  3900 V BluetoothMapService: Handler(): got msg=1
09-13 16:10:50.285  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 16:10:50.285  3900  3987 I bluedroid-qcom: enable
09-13 16:10:50.285  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:50.285  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:50.285  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:50.285  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.285  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 16:10:50.285  3900  7436 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 16:10:50.285  3900  7436 I bt-btu  : btu_task pending for preload complete event
09-13 16:10:50.285  3900  3987 I bt_hci_bdroid: init
09-13 16:10:50.286  3900  3987 I bt_vendor: bt-vendor : init
09-13 16:10:50.286  3900  3987 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 16:10:50.286  3900  3987 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 16:10:50.286  3900  3987 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 16:10:50.286  3900  3987 D bt_userial_mct: userial_init
09-13 16:10:50.286  3900  3987 D bt_hci_bdroid: set_power 1
09-13 16:10:50.286  3900  3987 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 16:10:50.286  3900  3987 I bt_vendor: Starting hciattach daemon
09-13 16:10:50.286  3900  3987 I bt_vendor: try to set true
09-13 16:10:50.286  7439  7439 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:50.286  7439  7439 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:50.303  7440  7440 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 16:10:50.309  1842  7245 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-13 16:10:50.317  6933  7429 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 16:10:50.318  2276  2276 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-13 16:10:50.321  6933  7429 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 16:10:50.321  1842  7245 I CheckinService: active receiver: disabled
,09-13 16:10:50.333  2276  2276 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-13 16:10:50.333  2276  2276 D c       : Getting all permits...
09-13 16:10:50.334  2276  2276 D a       : Opening database...
09-13 16:10:50.336  2276  2276 D a       : Opening database auth.proximity.permit_store...
09-13 16:10:50.336  2276  2276 D a       : Closing database...
09-13 16:10:50.344  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 16:10:50.345  6466  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 16:10:50.348  7447  7447 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
09-13 16:10:50.353  7449  7449 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 16:10:50.363  2276  2276 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.366  7452  7452 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 16:10:50.368  1842  7451 I CheckinService: active receiver: disabled
09-13 16:10:50.371  7453  7453 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 16:10:50.373  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 16:10:50.373  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.373  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 16:10:50.373  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 16:10:50.376  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 16:10:50.378  7454  7454 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 16:10:50.380  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:50.380  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:50.380  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:50.380  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:50.380  7102  7102 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 16:10:50.382  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.383  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:50.383  7455  7455 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 16:10:50.384  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:50.385  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:50.389  3525  3525 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:50.391  3525  3525 V DownloadManager: DownloadService onCreate
09-13 16:10:50.391  7457  7457 I libmdmdetect: ESOC framework not supported
09-13 16:10:50.392  7457  7457 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-13 16:10:50.393  3525  7459 I DownloadManager: in removeSpuriousFiles
09-13 16:10:50.393  3525  7459 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 16:10:50.394  3525  7459 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1735cff8 on behalf of 3525
09-13 16:10:50.395  7457  7457 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 16:10:50.395  7457  7457 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 16:10:50.395  7457  7457 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 16:10:50.395  7457  7457 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 16:10:50.395  7457  7457 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 16:10:50.395  7457  7457 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 16:10:50.395  7457  7457 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 16:10:50.397  4333  7463 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:50.397  4333  7458 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:50.397  4333  7463 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 16:10:50.397  3525  7459 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 16:10:50.399  3525  3525 V DownloadManager: DownloadService onStartCommand
09-13 16:10:50.399  3525  7460 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 16:10:50.400  3525  7459 I DownloadManager: in trimDatabase
09-13 16:10:50.400  3525  7459 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 16:10:50.400  4333  7458 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 16:10:50.400  3525  7459 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20e25237 on behalf of 3525
09-13 16:10:50.400  3525  7460 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f3f3a4 on behalf of 3525
,09-13 16:10:50.403  3525  7460 V DownloadManager: processing inserted download 1
09-13 16:10:50.404  3525  7460 V DownloadManager: processing inserted download 4
09-13 16:10:50.404  3525  7460 V DownloadManager: processing inserted download 7
09-13 16:10:50.405  7144  7464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:50.406  3525  7460 V DownloadManager: processing inserted download 8
09-13 16:10:50.407  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 16:10:50.407  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:50.407  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 16:10:50.407  3468  3468 D PhoneState: setPdpRejectCasuse : false
09-13 16:10:50.408  3525  7460 V DownloadManager: processing inserted download 9
09-13 16:10:50.409  3525  7460 V DownloadManager: processing inserted download 10
09-13 16:10:50.409  4333  7458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 16:10:50.410  3525  7460 V DownloadManager: processing inserted download 11
09-13 16:10:50.410  3525  7460 V DownloadManager: processing inserted download 12
09-13 16:10:50.411  3525  7460 V DownloadManager: processing inserted download 13
09-13 16:10:50.411  3525  7460 V DownloadManager: processing inserted download 14
09-13 16:10:50.412  3525  7460 V DownloadManager: processing inserted download 16
09-13 16:10:50.413  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 16:10:50.413  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 16:10:50.416  4333  4333 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 16:10:50.417  4333  4333 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 16:10:50.417  4333  4333 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 16:10:50.418  4333  4333 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 16:10:50.421  7296  7296 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:50
09-13 16:10:50.422  4333  4333 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 16:10:50.422  3525  3525 V DownloadManager: DownloadService onDestroy
09-13 16:10:50.422  7296  7296 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 16:10:50.422  7296  7296 D Weather.Utils: 2 : All the weather widget is gone.
09-13 16:10:50.423  7296  7296 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 16:10:50.423  7296  7296 D WeatherAncestor: connectivity changed - connection : true
09-13 16:10:50.423  7296  7296 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2266284e
09-13 16:10:50.423  7296  7296 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 16:10:50.423  7296  7296 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 16:10:50.423  7296  7296 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 16:10:50.423  7296  7296 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 16:10:50.423  7296  7296 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:50
09-13 16:10:50.426  7457  7461 E QC-QMI  : qmi_client [7457] 15: failed to locate client data
,09-13 16:10:50.427   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-13 16:10:50.427   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-13 16:10:50.438  2276  2276 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 16:10:50.445  2276  2276 I GCM     : GCM config loaded
09-13 16:10:50.447  1037  1390 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1035118318, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
09-13 16:10:50.452  6933  7468 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 16:10:50.453  6933  7468 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 16:10:50.456  7201  7201 V SetupWizard: Connected to Gservices successfully
09-13 16:10:50.459  2276  2276 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-13 16:10:50.466  6913  6913 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-13 16:10:50.468  6913  6913 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2793
09-13 16:10:50.472  2599  2599 D [Concierge]Service: onStartCommand(). Type : 9
09-13 16:10:50.485  7471  7471 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 16:10:50.492  7472  7472 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 16:10:50.500  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1035118318 [*alarm*], flags=0x0
,09-13 16:10:50.534  1037  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:50.534  1037  1054 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@281208ab mBinding = false
09-13 16:10:50.534  1037  1099 D BluetoothManagerService: Message: 1
09-13 16:10:50.534  1037  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@281208ab
,09-13 16:10:50.537  3900  3987 I bt_vendor: bluetooth satus is on
09-13 16:10:50.537  3900  3987 D bt_hci_bdroid: preload
09-13 16:10:50.537  3900  7438 D bt_userial_mct: userial_open(port:0)
09-13 16:10:50.537  3900  7438 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 16:10:50.537  3900  7252 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 16:10:50.538  3900  7438 I bt_vendor: Done intiailizing UART
09-13 16:10:50.538  3900  7438 I bt_vendor: Done intiailizing UART
09-13 16:10:50.538  3900  7438 I bt_userial_mct: CMD=94, EVT=94, ACL_Out=96, ACL_In=96
09-13 16:10:50.538  1037  1099 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 16:10:50.539  3900  7438 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 16:10:50.539  3900  7436 I bt-btu  : btu_task received preload complete event
09-13 16:10:50.539  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 16:10:50.539  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 16:10:50.540  3900  7474 D bt_userial_mct: Entering userial_read_thread()
09-13 16:10:50.541  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 16:10:50.546  3900  7436 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 16:10:50.592  3900  7436 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-13 16:10:50.592  3900  7436 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0241061 
09-13 16:10:50.592  3900  7436 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0241061 
,09-13 16:10:50.603  3900  3991 E bt-btif : Calling BTA_HhEnable
,09-13 16:10:50.603  3900  3991 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 16:10:50.603  3900  3991 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 16:10:50.604  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-13 16:10:50.604  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 16:10:50.604  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 16:10:50.604  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 16:10:50.604  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 16:10:50.605  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 16:10:50.606  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 16:10:50.606  3900  3991 D BluetoothAdapterProperties: Name is: G3
,09-13 16:10:50.608  3900  3991 D BluetoothAdapterProperties: Scan Mode:20
09-13 16:10:50.608  3900  3991 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:10:50.608  3900  3991 D bt_hci_bdroid: postload
09-13 16:10:50.609  3900  7438 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:50.609  3900  7436 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 16:10:50.610  3900  3991 D bte_conf: Device ID record 1 : primary
09-13 16:10:50.610  3900  3991 D bte_conf:   vendorId            = 00c4
09-13 16:10:50.610  3900  3991 D bte_conf:   vendorIdSource      = 0001
09-13 16:10:50.610  3900  3991 D bte_conf:   product             = 13a1
09-13 16:10:50.610  3900  3991 D bte_conf:   version             = 1000
09-13 16:10:50.610  3900  3991 D bte_conf:   clientExecutableURL = 
09-13 16:10:50.610  3900  3991 D bte_conf:   serviceDescription  = 
09-13 16:10:50.610  3900  3991 D bte_conf:   documentationURL    = 
09-13 16:10:50.610  3900  3991 D bte_conf: bte_load_did_conf no section named DID2.
09-13 16:10:50.612  3900  7436 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 16:10:50.612  3900  7436 W bt-smp  : Plain text(LSB ~ MSB) = 96 d6 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 16:10:50.612  3900  7436 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 4d 0d d8 a9 55 8e e4 87 a2 e8 ad 6d 3f 0c f2 
09-13 16:10:50.612  3900  7436 W bt-btm  : Stopping oneshot timer
09-13 16:10:50.613  3900  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 16:10:50.613  3900  3987 D BluetoothAdapterProperties: ScanMode =  20
,09-13 16:10:50.613  3900  3987 D BluetoothAdapterProperties: State =  11
09-13 16:10:50.613  3900  3987 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,09-13 16:10:50.613  3900  3987 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 16:10:50.613  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:50.613  3900  3987 D BluetoothAdapterProperties: Setting state to 12
09-13 16:10:50.613  3900  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 16:10:50.613  3900  3991 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 16:10:50.613  3900  7438 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 16:10:50.613  3900  7438 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:50.613  3900  7438 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:50.614  3900  3991 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 16:10:50.614  3900  7438 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:50.614  3900  7438 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 16:10:50.614  3900  7474 E bt_mct  : hci lib postload completed
09-13 16:10:50.606  7476  7476 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 16:10:50.606  7476  7476 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:50.617  3900  3987 I BluetoothAdapterState: Entering On State
09-13 16:10:50.618  3900  3987 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 16:10:50.618  3900  3987 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 16:10:50.618  3900  3987 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 16:10:50.619  3900  3987 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-13 16:10:50.621  1037  1099 D BluetoothManagerService: Message: 60
09-13 16:10:50.621  1037  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 16:10:50.621  1037  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 16:10:50.621  6891  6907 D BluetoothPan: onBluetoothStateChange on: true
09-13 16:10:50.621  6891  6907 D BluetoothPan: onBluetoothStateChange call bindService
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:50.624  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:50.626  3900  7436 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 16:10:50.626  3900  7436 W bt-smp  : Plain text(LSB ~ MSB) = b6 e1 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 16:10:50.627  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:50.626  3900  7436 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 1e 35 ed 1f 87 cc 70 98 9f 99 36 0c d8 f0 da 
09-13 16:10:50.627  3900  7436 W bt-btm  : Stopping oneshot timer
,09-13 16:10:50.632  6891  6891 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 16:10:50.632  6891  6891 D PanProfile: Bluetooth service connected
09-13 16:10:50.633  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:50.636  6891  6906 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 16:10:50.637  1880  1880 D BluetoothHeadset: Proxy object connected
09-13 16:10:50.639  3900  7436 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 16:10:50.639  3900  7436 W bt-smp  : Plain text(LSB ~ MSB) = a3 be 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 16:10:50.639  3900  7436 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 b1 4b ca f1 4f 5a 79 ec 18 a1 ed a1 4c 27 c0 
09-13 16:10:50.639  6891  6907 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:10:50.639  3900  7436 W bt-btm  : Stopping oneshot timer
09-13 16:10:50.641  6891  6891 D BluetoothHeadset: Proxy object connected
09-13 16:10:50.641  6891  6891 D HeadsetProfile: Bluetooth service connected
09-13 16:10:50.642  6891  6906 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 16:10:50.644  3900  3991 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:10:50.644  3900  3991 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 16:10:50.645  1880  2597 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:50.648  3900  7436 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 16:10:50.648  3900  7436 W bt-smp  : Plain text(LSB ~ MSB) = 25 36 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 16:10:50.648  3900  7436 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 29 43 6b b3 b7 ce 0c 8e e4 8a 60 e9 8a 17 02 
09-13 16:10:50.648  3900  7436 W bt-btm  : Stopping oneshot timer
09-13 16:10:50.657  3900  7436 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 16:10:50.657  3900  7436 W bt-smp  : Plain text(LSB ~ MSB) = 77 20 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 16:10:50.657  3900  7436 W bt-smp  : Encrypted text(LSB ~ MSB) = 1d 18 b7 77 cd 17 c0 51 0f ce 6d c4 1d 0a b0 e7 
09-13 16:10:50.657  3900  7436 W bt-btm  : Stopping oneshot timer
,09-13 16:10:50.667  3900  3987 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 16:10:50.683  7481  7481 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-13 16:10:50.754  1037  1710 I art     : Explicit concurrent mark sweep GC freed 36839(1788KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.531ms total 107.846ms
,09-13 16:10:50.755  3900  3900 V BluetoothOppNotification: new notify threadi!
09-13 16:10:50.755  3900  3900 V BluetoothOppNotification: send delay message
09-13 16:10:50.756  1880  1880 D BluetoothHeadset: Proxy object connected
09-13 16:10:50.758  6891  6891 D BluetoothA2dp: Proxy object connected
09-13 16:10:50.758  6891  6891 D A2dpProfile: Bluetooth service connected
09-13 16:10:50.759   313  7483 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 16:10:50.759  6891  6907 D BluetoothMap: onBluetoothStateChange: up=true
09-13 16:10:50.759   313  7483 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-13 16:10:50.763  3900  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-13 16:10:50.766  6891  6891 D BluetoothMap: Proxy object connected
09-13 16:10:50.766  6891  6891 D MapProfile: Bluetooth service connected
09-13 16:10:50.766  6891  6891 D BluetoothMap: getConnectedDevices()
09-13 16:10:50.766  3900  3919 V BluetoothMapService: getConnectedDevices()
09-13 16:10:50.767  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:10:50.771  3900  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@74620eb on behalf of 
09-13 16:10:50.772  3900  7482 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 16:10:50.773  3900  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 16:10:50.773  1880  1880 D BluetoothHeadset: Proxy object connected
09-13 16:10:50.776  6891  7249 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 16:10:50.778  3900  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17a5ce48 on behalf of 
09-13 16:10:50.778  3900  7482 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 16:10:50.780  3900  7482 V BluetoothOppNotification: outbound notification was removed.
09-13 16:10:50.780  3900  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-13 16:10:50.781  1037  1099 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:10:50.782  1037  1099 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 16:10:50.783  1037  1037 D BluetoothHeadset: Proxy object connected
09-13 16:10:50.783  1037  1099 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 16:10:50.783  1037  1099 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 16:10:50.783  6891  6891 D BluetoothInputDevice: Proxy object connected
09-13 16:10:50.783  6891  6891 D HidProfile: Bluetooth service connected
09-13 16:10:50.783  3900  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a22f4e1 on behalf of 
09-13 16:10:50.784  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.784  1969  2173 D LGBluetoothAPIService: Message: 1
09-13 16:10:50.784  1969  2173 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 16:10:50.785  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 16:10:50.789  3900  7482 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 16:10:50.790   313  7483 D libc-netbsd: res_queryN name = www.google.com succeed
09-13 16:10:50.793   313  7485 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 16:10:50.793   313  7485 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 16:10:50.793   313  7485 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:50.799  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:50.799  3900  3900 V BtOppService: Receiver BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 16:10:50.799  3900  3900 V BtOppService: start RfcommListener
09-13 16:10:50.799  3900  3900 V BtOppService: RfcommListener started
09-13 16:10:50.799  3900  3900 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.799  3900  3900 D BluetoothMapService: STATE_ON
09-13 16:10:50.799  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.800  3900  3900 V BluetoothPbapService: Pbap Service onCreate
09-13 16:10:50.800  3900  3900 V BluetoothPbapService: Starting PBAP service
09-13 16:10:50.800  3900  7486 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 16:10:50.800  3900  3900 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 16:10:50.800  3900  3900 V BluetoothPbapService: Pbap Service onBind
09-13 16:10:50.802  1037  2087 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:50.803  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:50.803  3900  3900 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.803  3900  3900 V BluetoothPbapService: state: 12
09-13 16:10:50.803  3900  3900 V BluetoothMapService: Handler(): got msg=1
09-13 16:10:50.804  3900  3900 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 16:10:50.804  3900  7486 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:50.804  1037  1037 D BluetoothA2dp: Proxy object connected
09-13 16:10:50.804  3900  3900 V BluetoothPbapService: Handler(): got msg=1
09-13 16:10:50.805  3900  3900 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 16:10:50.805  3900  7487 D BluetoothMapMasInstance: MAS initSocket()
09-13 16:10:50.805  3900  7482 V BluetoothOppNotification: inbound notification was removed.
09-13 16:10:50.805  3900  7487 D BluetoothMapMasInstance:   masId = 00
09-13 16:10:50.805  3900  7487 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 16:10:50.805  3900  7487 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 16:10:50.805  3900  7487 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 16:10:50.805  3900  3900 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 16:10:50.805  1037  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:50.805  3900  3900 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 16:10:50.806  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 16:10:50.806  3900  7488 V BluetoothPbapService: Pbap Service initSocket
09-13 16:10:50.806  1969  2173 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 16:10:50.807  1969  2173 D LGBluetoothAPIService: Message: 100
09-13 16:10:50.807  1969  2173 D LGBluetoothAPIService: ,MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 16:10:50.807  3900  7482 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 16:10:50.807  3900  7487 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:50.807  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:50.808  3900  7486 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=99 mFd=89
09-13 16:10:50.808  1037  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 16:10:50.809  3900  7486 V BtOppRfcommListener: Started RFCOMM listener....
09-13 16:10:50.809  3900  7486 I BtOppRfcommListener: Accept thread started.
09-13 16:10:50.809  3900  7486 V BtOppRfcommListener: Accepting connection...
09-13 16:10:50.811  3900  3991 D BluetoothAdapterProperties: Scan Mode:21
09-13 16:10:50.811  3900  3991 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 16:10:50.812  3900  7488 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:50.813  3900  7487 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=101 mFd=99
09-13 16:10:50.813  3900  7482 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6d86f4 on behalf of 
09-13 16:10:50.813  3900  7487 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 16:10:50.813  3900  7487 D BluetoothMapMasInstance: Accepting socket connection...
09-13 16:10:50.816  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:50.817  3900  7488 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=104 mFd=101
09-13 16:10:50.817  3900  7488 V BluetoothPbapService: Succeed to create listening socket 
09-13 16:10:50.817  3900  7488 V BluetoothPbapService: Accepting socket connection...
09-13 16:10:50.818  6891  6891 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 16:10:50.819  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:50.819  6891  6891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 16:10:50.822  6891  6891 D BluetoothPbap: Proxy object connected
09-13 16:10:50.822  6891  6891 D PbapServerProfile: Bluetooth service connected
09-13 16:10:50.824  3900  3900 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 16:10:50.824  3900  3900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.824  3900  3900 V BluetoothPbapReceiver: ***********state = 12
09-13 16:10:50.828  2276  2276 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:10:50.828  2276  2276 D c       : Getting all permits...
09-13 16:10:50.828  2276  2276 D a       : Opening database...
09-13 16:10:50.829  6891  6891 D DockEventReceiver: finishStartingService: stopping service
09-13 16:10:50.831  2276  2276 D a       : Opening database auth.proximity.permit_store...
09-13 16:10:50.831  2276  2276 D a       : Closing database...
,09-13 16:10:50.840  1037  1543 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-13 16:10:50.842  6891  6891 D BluetoothPermissionRequest: onReceive
09-13 16:10:50.843  6891  6891 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-13 16:10:50.845  6891  6891 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 16:10:50.848  3900  3900 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 16:10:50.849  3900  3900 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 16:10:50.850  3900  3900 V BtOppService: onStartCommand
09-13 16:10:50.851  3900  3900 V BtOppService: Starting RfcommListener
09-13 16:10:50.853  3900  7490 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 16:10:50.853  3900  7490 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 16:10:50.854  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.854  3900  3900 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 16:10:50.856  3900  3900 V BtOppService: start RfcommListener
09-13 16:10:50.856  3900  3900 V BtOppService: RfcommListener started
,09-13 16:10:50.857  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.857  3900  3900 V BluetoothFtpService: Ftp Service onCreate
09-13 16:10:50.857  3900  3900 I BluetoothFtpService: Ftp Service onCreate
09-13 16:10:50.857  3900  3900 V BluetoothFtpService: Ftp Service onStartCommand
09-13 16:10:50.855  3900  7490 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2578fe1d on behalf of 
09-13 16:10:50.857  3900  3900 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.857  3900  3900 V BluetoothFtpService: Starting Listening on sockets
09-13 16:10:50.857  3900  3900 V BluetoothFtpService: Handler(): got msg=1
09-13 16:10:50.859  3900  3900 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,09-13 16:10:50.859  3900  3900 V BluetoothFtpService: Ftp Service initSocket
09-13 16:10:50.859  1037  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:50.860  3900  7490 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 16:10:50.861  3900  3900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:50.862  3900  3900 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=105 mFd=104
09-13 16:10:50.862  3900  3900 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 16:10:50.863  3900  3900 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 16:10:50.863  3900  3900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 16:10:50.863  3900  3900 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 16:10:50.863  3900  3900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.863  3900  3900 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 16:10:50.863  3900  3900 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 16:10:50.866  3900  3900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a232749
09-13 16:10:50.866  3900  3900 V BluetoothSapService: Sap Service onCreate
09-13 16:10:50.867  3900  7491 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 16:10:50.872  3900  3900 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:10:50.872  3900  3900 V BluetoothSapService: state: 12
09-13 16:10:50.872  3900  3900 V BluetoothSapService: Starting SAP server process
,09-13 16:10:50.866  7492  7492 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:50.866  7492  7492 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:50.874  3900  3900 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 16:10:50.879  3900  7493 V BluetoothSapService: Sap Service initRfcommSocket
09-13 16:10:50.880  1037  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:50.881  3900  7493 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:50.883  3900  7493 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=107 mFd=105
09-13 16:10:50.883  3900  7493 V BluetoothSapService: Succeed to create listening socket 
09-13 16:10:50.883  3900  7493 V BluetoothSapService: Accepting socket connection...
09-13 16:10:50.893  7492  7492 V BT_SAP  : Event pipe created
09-13 16:10:50.893  7492  7492 V BT_SAP  : create_server_socket qcom.sap.server
09-13 16:10:50.893  7492  7492 V BT_SAP  : created socket fd 6
,09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:51.047  6736  7335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:10:51.051  6736  7335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:51.060  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:51.064  1037  2064 D WifiServiceImplEx: setWifiEnabled: false pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 16:10:51.065  1037  2064 D WifiService: setWifiEnabled: false pid=6736, uid=10118
,09-13 16:10:51.065  1037  2064 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:10:51.088  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-13 16:10:51.089  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:51.089  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-13 16:10:51.090  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:51.092  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:51.093  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,09-13 16:10:51.095  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:51.096  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 16:10:51.096  1037  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 16:10:51.097  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 16:10:51.097  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 16:10:51.099  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 16:10:51.099  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 16:10:51.100  1037  1054 D WifiServiceImplEx: setWifiEnabled: false pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 16:10:51.101  1037  1054 D WifiService: setWifiEnabled: false pid=6736, uid=10118
09-13 16:10:51.101  1037  1054 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:51.110  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 16:10:51.111  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 16:10:51.112  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-13 16:10:51.112  1037  1539 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.112  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.113  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 16:10:51.114  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
,09-13 16:10:51.115  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:51.116  1037  7071 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.119   313   897 D CommandListener: Clearing all IP addresses on wlan0
09-13 16:10:51.121   313   890 E Netd    : ifc_reset_connections failed on iface wlan0 for address 192.168.1.108/24 (Unknown error -1)
09-13 16:10:51.132  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 16:10:51.132  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
09-13 16:10:51.132  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-13 16:10:51.141  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-13 16:10:51.142  6980  7046 D serial_port: close(fd = 25)
09-13 16:10:51.145  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 16:10:51.145  6980  7051 D UEI.SmartControl: Internal timer expired: 1
09-13 16:10:51.145  6980  7051 D UEI.SmartControl: unbind internal service
09-13 16:10:51.146  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:51.146  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:51.148  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.151  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.151  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 16:10:51.151  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:10:51.156  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:51.156  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:51.157  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:51.158  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.158  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.158  1037  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@376d4e6e
09-13 16:10:51.159  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-13 16:10:51.159  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:51.160  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:51.160  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:51.162  1037  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 16:10:51.163  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.163  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.163  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:10:51.164  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 16:10:51.164  1037  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.165  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-13 16:10:51.165  1037  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.165  1037  1539 D LGWifiP2pService: P2pDisablingState
09-13 16:10:51.166  1037  1539 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.166  1037  1539 D LGWifiP2pService: p2p socket connection lost
09-13 16:10:51.166  1037  1539 D LGWifiP2pService: P2pDisabledState
09-13 16:10:51.166  1037  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 16:10:51.166  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 16:10:51.167  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.167  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.167  6967  6967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 16:10:51.167  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 16:10:51.167  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:51.167  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:51.169  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 16:10:51.170  1969  1969 D WfdsService: WifiP2pState is changed : false
09-13 16:10:51.170  1969  2310 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 16:10:51.170  1969  2310 D WfdsService: Set the WFDS Monitor: false
09-13 16:10:51.171  1969  2310 D WfdsMonitor: WFDS Monitor is stopped
09-13 16:10:51.171  1969  2310 D WfdsService: STATE : WfdsDisabledState - enter
09-13 16:10:51.171  1969  6999 D CtrlSupplicant: Received on exit socket, terminate
09-13 16:10:51.171  1969  6999 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 16:10:51.171  1969  6999 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 16:10:51.171  1969  2313 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 16:10:51.171  1969  6999 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 16:10:51.171  1969  2310 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 16:10:51.172  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:51.173  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:51.173  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:51.175  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:51.177  6980  7046 I UEI.SmartControl: Serial port is closed.
09-13 16:10:51.180  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 16:10:51.180  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:51.180  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:51.183  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:51.188  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 16:10:51.195  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:51.196  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:51.198  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:51.202  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:51.205  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 16:10:51.206  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:51.206  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:51.211  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:51.217  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 16:10:51.223   313   897 D CommandListener: Clearing all IP addresses on wlan0
09-13 16:10:51.224  1037  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 16:10:51.224  1037  1547 D DSQN    : disableDataServiceNotify
09-13 16:10:51.224  1037  1547 D DSQN    : stop dsqn bin
09-13 16:10:51.226  1037  1540 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 16:10:51.227  1037  1540 D WifiNative-p2p0: TERMINATE: returned true
09-13 16:10:51.227  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:51.227  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:51.227  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:51.228  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-13 16:10:51.230  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.230  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.230  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 16:10:51.230  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:51.230  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:10:51.231  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 16:10:51.232  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 16:10:51.233  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:51.233  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 16:10:51.233  1037  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 16:10:51.233  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:51.233  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:51.234  1037  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:51.234  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 16:10:51.234  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.234  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.234  1037  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 16:10:51.235  1037  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 16:10:51.235  1037  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101], isDefaultNetwork=true
09-13 16:10:51.235  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:51.235  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:10:51.235  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:51.235  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:51.235  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:10:51.236  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 16:10:51.238  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 16:10:51.238  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 16:10:51.238  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 16:10:51.238  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 16:10:51.238  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 16:10:51.238  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:51.238  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 16:10:51.238  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 16:10:51.238  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 16:10:51.238  1037  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:51.238  1037  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:51.238  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 16:10:51.238  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 16:10:51.239  1037  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:51.239  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:51.241  1037  1547 D NetworkManagementService: Removing idletimer
09-13 16:10:51.241  1037  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.242  1880  1880 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:51.242  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-13 16:10:51.245  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.245  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:51.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:51.249  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.251  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:51.251  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:51.255  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 16:10:51.255  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:51.255  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:51.259  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:51.262  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:51.265  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:51.281  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:51.289  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:51.289  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:51.291  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:51.300  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 16:10:51.301  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 16:10:51.302  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 16:10:51.302  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.303  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.307  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:51.309  6967  6967 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 16:10:51.309  6967  6967 I wpa_supplicant: monitor socket send errors count : 1
09-13 16:10:51.309  6967  6967 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-4\x00 that cannot receive messages
09-13 16:10:51.310  1037  6997 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 16:10:51.310  1037  6997 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 16:10:51.317  6933  7509 W FormManager: Network not available. Please check & try again.
,09-13 16:10:51.324  6933  7510 V FormManager: Network unavailable.
09-13 16:10:51.331  6933  7510 V FormManager: Network unavailable.
,09-13 16:10:51.342  6967  6967 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 16:10:51.343  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 16:10:51.343  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 16:10:51.343  1037  6997 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 16:10:51.343  1037  6997 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 16:10:51.343  6967  6967 W wpa_supplicant: USIM:  scard_deinit function
09-13 16:10:51.343  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:51.343  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:51.344  1037  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=204423
,09-13 16:10:51.345  1037  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=204424
09-13 16:10:51.347  1037  1099 D Tethering: InitialState.processMessage what=4
09-13 16:10:51.347  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=204426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 16:10:51.348  1037  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=204427  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 16:10:51.348  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 16:10:51.350  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:51.351  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:51.351  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:51.352  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:51.352  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:51.352  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:51.352  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 16:10:51.353  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 16:10:51.354  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 16:10:51.354  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 16:10:51.354  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:51.354  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:51.354  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:51.354  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:51.355  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.356  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.370  1037  7071 D DhcpStateMachine: StoppedState
09-13 16:10:51.370  1037  7071 D DhcpStateMachine: StoppedState{ when=-203ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:51.371  1037  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 16:10:51.372  1037  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-13 16:10:51.472  6967  6967 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 16:10:51.472  1037  6997 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,09-13 16:10:51.472  1037  6997 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 16:10:51.473  1037  6997 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 16:10:51.474  1037  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
09-13 16:10:51.579  1969  1969 D WfdsService: Supplicant Connection state is changed : false
,09-13 16:10:51.579  1969  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 16:10:51.579  1969  2310 D WfdsService: Set the WFDS Monitor: false
09-13 16:10:51.579  1969  2310 D WfdsMonitor: WFDS Monitor is stopped
09-13 16:10:51.586  1037  1540 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 16:10:51.586  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:51.586  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:51.586  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:51.587  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:51.592  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 16:10:51.597  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 16:10:51.599  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:51.601  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:51.602  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:51.610  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 16:10:51.610  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 16:10:51.610  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:51.615  6736  7495 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:51.617  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:51.620  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:51.621  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:51.621  6736  7495 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:51.624  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:51.626  1037  1979 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:51.626  1037  1979 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:51.626  1037  1979 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:51.630  4333  7515 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 16:10:51.633  6863  6863 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 16:10:51.633  6863  6863 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 16:10:51.633  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:51.636  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 16:10:51.637  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 16:10:51.637  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 16:10:51.637  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-13 16:10:51.639  4333  7516 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:51.639  4333  7516 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:51.640  1037  2064 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:51.641  1037  2064 D WifiService: setWifiEnabled: true pid=6736, uid=10118
,09-13 16:10:51.641  1037  2064 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:51.642  1037  1546 D WifiController: Mismatch in the state 1
,09-13 16:10:51.646  6933  7520 W FormManager: Network not available. Please check & try again.
09-13 16:10:51.649  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:51.653  6933  7521 V FormManager: Network unavailable.
09-13 16:10:51.656  6933  7521 V FormManager: Network unavailable.
,09-13 16:10:51.757  3900  3900 V BluetoothOppNotification: new notify threadi!
,09-13 16:10:51.757  3900  3900 V BluetoothOppNotification: send delay message
09-13 16:10:51.761  3900  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 16:10:51.764  3900  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32344bde on behalf of 
09-13 16:10:51.766  3900  7522 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 16:10:51.769  3900  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 16:10:51.772  3900  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b1621bf on behalf of 
09-13 16:10:51.773  3900  7522 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-13 16:10:51.775  3900  7522 V BluetoothOppNotification: outbound notification was removed.
,09-13 16:10:51.775  3900  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-13 16:10:51.776  3900  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f6ec08c on behalf of 
09-13 16:10:51.777  3900  7522 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 16:10:51.779  3900  7522 V BluetoothOppNotification: inbound notification was removed.
09-13 16:10:51.779  3900  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 16:10:51.781  3900  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@191ad3d5 on behalf of 
09-13 16:10:51.790  1037  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 16:10:51.790  1037  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-13 16:10:51.795  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-13 16:10:51.795  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-13 16:10:51.795  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-13 16:10:51.795  1037  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-13 16:10:51.795  1037  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 16:10:51.795  1037  1540 E WifiHW  : unknown target_country: EU , set to default
09-13 16:10:51.795  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 16:10:51.796  1037  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-13 16:10:51.796  1037  1540 I WifiUtil: gEnableBmps=1
09-13 16:10:52.145  1037  2096 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:52.147  1037  2096 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:52.147  1037  2096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,09-13 16:10:52.163  1037  1546 D WifiController: Mismatch in the state 1
09-13 16:10:52.377   313   897 D SoftapController: Softap fwReload - Ok
,09-13 16:10:52.415  1037  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 16:10:52.415  1037  1540 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (614ms)
,09-13 16:10:52.438   313   897 D CommandListener: Setting iface cfg
09-13 16:10:52.438   313   897 D CommandListener: Trying to bring down wlan0
,09-13 16:10:52.441   313   897 D CommandListener: Clearing all IP addresses on wlan0
09-13 16:10:52.443  1037  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 16:10:52.446  7536  7536 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 16:10:52.455  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:52.455  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:52.455  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:52.446  7536  7536 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:52.489  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:52.493  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 16:10:52.504  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-13 16:10:52.505  1037  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 16:10:52.506  1037  1540 D WifiMonitor: connecting to supplicant
09-13 16:10:52.508  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:52.508  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:52.508  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:52.509  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:52.509  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:52.510  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 16:10:52.520  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:52.520  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-13 16:10:52.521  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 16:10:52.521  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 16:10:52.521  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:52.521  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:52.521  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 16:10:52.521  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:52.522  7536  7536 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 16:10:52.532  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:52.535  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 16:10:52.543  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:52.559  7536  7536 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 16:10:52.559  7536  7536 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 16:10:52.560  6933  7555 W FormManager: Network not available. Please check & try again.
09-13 16:10:52.562  1037  1099 D Tethering: InitialState.processMessage what=4
09-13 16:10:52.562  6933  7556 V FormManager: Network unavailable.
09-13 16:10:52.563  1037  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 16:10:52.565  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:52.565  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:52.565  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:52.565  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:52.567  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 16:10:52.567  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 16:10:52.567  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 16:10:52.567  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,09-13 16:10:52.567  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:52.567  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:52.568  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:52.569  6933  7556 V FormManager: Network unavailable.
09-13 16:10:52.666  1037  1934 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:52.667  1037  1934 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:52.667  1037  1934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:52.671  7536  7536 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 16:10:52.682  7536  7536 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-13 16:10:52.689  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-13 16:10:52.689  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 16:10:52.690  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 16:10:52.690  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 16:10:52.690  7536  7536 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 16:10:52.690  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 16:10:52.690  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 16:10:52.690  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 16:10:52.690  1037  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 16:10:52.690  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 16:10:52.690  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 16:10:52.691  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.691  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.692  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-13 16:10:52.692  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:52.693  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3178] from screen [on:0 period:602070165] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 16:10:52.694  1037  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:602070166] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:52.695  1037  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:52.695  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:52.696  1037  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 16:10:52.696  1037  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,09-13 16:10:52.698  1037  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 16:10:52.699  1037  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 16:10:52.699  1037  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 16:10:52.702  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.702  1037  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 16:10:52.702  1037  1540 E WifiStateMachine: useWiFiOffloading() : false
09-13 16:10:52.702  1037  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 16:10:52.702  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.702  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.702  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.703  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-13 16:10:52.706  1037  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 16:10:52.706  1037  1540 D WifiNative-wlan0: SET update_config 1: returned true
09-13 16:10:52.706  1037  1540 D WifiConfigStore: Loading config and enabling all networks 
09-13 16:10:52.706  1037  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 16:10:52.707  1037  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 16:10:52.709  1969  1969 D WfdService: Waiting for WifiP2p enabling
09-13 16:10:52.709  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:52.713  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 16:10:52.713  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 16:10:52.714  1037  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:52.719  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:52.723  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:10:52.726  1037  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 16:10:52.726  1037  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 16:10:52.728  1037  1540 D WifiStateMachine: enableVerboseLogging : level 2
09-13 16:10:52.728  1037  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 16:10:52.728  1037  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 16:10:52.729  1037  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 16:10:52.729  1037  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 16:10:52.729  1037  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 16:10:52.729  1037  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:52.729  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:10:52.729  1037  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 16:10:52.730  1037  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 16:10:52.730  1037  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,09-13 16:10:52.730  1037  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 16:10:52.730  1037  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 16:10:52.731  1037  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 16:10:52.731  1037  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 16:10:52.731  1037  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 16:10:52.732  1969  1969 D WfdsService: Supplicant Connection state is changed : true
09-13 16:10:52.732  1969  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 16:10:52.733  1969  2310 D WfdsService: Set the WFDS Monitor: true
09-13 16:10:52.733  1969  2310 D WfdsMonitor: WfdsMonitorThread create
09-13 16:10:52.733  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 16:10:52.733  1037  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 16:10:52.733  1969  2310 D WfdsMonitor: WFDS Monitor is created and started
09-13 16:10:52.733  1969  2310 D WfdsService: WiFi: Supplicant connection re-established
09-13 16:10:52.733  1037  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 16:10:52.733  1037  1540 D WifiNative-HAL: Setting external_sim to 1
09-13 16:10:52.733  1037  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 16:10:52.734  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:52.734  1969  7558 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 16:10:52.734  1037  1540 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 16:10:52.734  1037  1540 I WifiNative-HAL: startHal
09-13 16:10:52.734  1037  1540 D wifi    : setting scan oui 0xaf6af140
09-13 16:10:52.734  1969  7558 E CtrlSupplicant: Succeed to open control connection
09-13 16:10:52.734  1037  1540 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 16:10:52.734  1037  1540 I WifiNative-HAL: startHal
09-13 16:10:52.734  1037  1540 D wifi    : setting scan oui 0xaf6af140
09-13 16:10:52.734  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:52.734  1969  7558 E CtrlSupplicant: Succeed to open monitor connection
09-13 16:10:52.735  1037  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 16:10:52.735  1969  7558 D WfdsMonitor: Supplicant connection established
09-13 16:10:52.735  1037  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 16:10:52.735  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 16:10:52.735  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 16:10:52.736  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 16:10:52.736  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 16:10:52.736  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 16:10:52.736  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 16:10:52.736  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 16:10:52.737  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 16:10:52.737  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 16:10:52.737  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 16:10:52.737  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 16:10:52.737  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 16:10:52.737  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 16:10:52.738  1969  2310 D WfdsService: Connected to the supplicant for wfds
,09-13 16:10:52.738  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 16:10:52.738  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 16:10:52.738  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 16:10:52.739  7536  7536 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 16:10:52.739  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 16:10:52.739  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 16:10:52.739  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-13 16:10:52.739  1037  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 16:10:52.740  1037  1540 E WifiNative: : [205,818,843 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 16:10:52.740  1037  1540 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 16:10:52.741  1037  1540 D WifiNative-wlan0: RECONNECT: returned true
09-13 16:10:52.741  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-13 16:10:52.741  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 16:10:52.741  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 16:10:52.741  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 16:10:52.742  1037  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 16:10:52.742  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:52.743  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:52.743  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.745  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 16:10:52.745  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-13 16:10:52.745  1037  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.745  1037  1558 I WifiNative-HAL: startHal
09-13 16:10:52.745  1037  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.745  1037  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf6af140
09-13 16:10:52.745  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 16:10:52.745  1037  1558 D wifi    : failed to get capabilities : -3
09-13 16:10:52.745  1037  1558 E WifiScanningService: could not get scan capabilities
09-13 16:10:52.745   313   897 D CommandListener: Setting iface cfg
09-13 16:10:52.746   313   897 D CommandListener: Trying to bring up p2p0
09-13 16:10:52.746  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
,09-13 16:10:52.746  1037  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 16:10:52.746  1037  1539 D LGWifiP2pService: P2pEnablingState
09-13 16:10:52.746  1037  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.746  1037  1539 D LGWifiP2pService: P2p socket connection successful
09-13 16:10:52.746  1037  1539 D LGWifiP2pService: P2pEnabledState
09-13 16:10:52.746  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 16:10:52.746  1037  1539 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 16:10:52.747  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 16:10:52.747  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.747  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 16:10:52.747  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.747  1969  1969 D WfdsService: WifiP2pState is changed : true
09-13 16:10:52.748  1969  2310 D WfdsService: Receive the WFDS_ENABLE Method
09-13 16:10:52.748  1969  2310 D WfdsService: Set the WFDS Monitor: true
09-13 16:10:52.748  1969  2310 D WfdsService: Connected to the supplicant for wfds
,09-13 16:10:52.748  1969  2310 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 16:10:52.748  7536  7536 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 16:10:52.748  1969  2310 D WfdsService: selectPreferredScanChannel [36]
09-13 16:10:52.748  1969  2310 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-13 16:10:52.748  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.749  1037  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 16:10:52.750  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.750  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:52.750  1037  1540 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.750  1037  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 16:10:52.750  1037  1540 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.750  1037  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
,09-13 16:10:52.751  1037  1540 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.751  1037  1539 D WifiNative-p2p0: SET device_name G3: returned true
09-13 16:10:52.751  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 16:10:52.751  1037  1540 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.751  1037  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 16:10:52.751  1037  1539 D LGWifiP2pService: before postfix = G3
09-13 16:10:52.751  1037  1539 D WifiServerServiceExt: postfix byte check : 2
09-13 16:10:52.751  1037  1539 D LGWifiP2pService: after postfix = G3
09-13 16:10:52.751  1037  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 16:10:52.751  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.751  1969  1969 D WfdsService: isConnected: false
09-13 16:10:52.751  1037  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 16:10:52.752  1037  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 16:10:52.752  1037  1540 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 16:10:52.752  6933  7561 W FormManager: Network not available. Please check & try again.
09-13 16:10:52.752  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=205831  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:52.752  1037  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 16:10:52.752  1037  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 16:10:52.753  1037  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 16:10:52.753  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 16:10:52.754  1037  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 16:10:52.754  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress
09-13 16:10:52.754  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 16:10:52.754  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=205833  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:52.755  1037  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 16:10:52.755  1037  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 16:10:52.755  1037  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
,09-13 16:10:52.755  1037  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 16:10:52.755  7536  7536 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 16:10:52.756  1037  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 16:10:52.756  1037  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,09-13 16:10:52.757  1037  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 16:10:52.757  1037  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 16:10:52.757  7536  7536 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 16:10:52.758  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 16:10:52.758  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 16:10:52.759  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
,09-13 16:10:52.759  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 16:10:52.759  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:52.759  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:52.759  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 16:10:52.760  7536  7536 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.760  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:52.760  7536  7536 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 16:10:52.761  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.761  1969  7558 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.761  1037  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 16:10:52.761  1037  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 16:10:52.761  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.761  1969  7558 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.761  1037  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 16:10:52.762  1037  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 16:10:52.762  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 16:10:52.762  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 16:10:52.762  7536  7536 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:52.764  1037  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 16:10:52.764  1037  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 16:10:52.764  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 16:10:52.764  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.764  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.764  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.764  1037  7557 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.764  1037  7557 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.764  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.764  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.764  1037  7557 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.764  1037  7557 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.764  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.764  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.765  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 16:10:52.765  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:52.765  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:52.765  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 16:10:,52.765  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 16:10:52.765  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 16:10:52.765  1969  1969 D WfdsService: Update P2p Interface State: 3
09-13 16:10:52.766  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.766  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.766  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 16:10:52.767  1037  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 16:10:52.767  1037  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 16:10:52.767  1037  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 16:10:52.767  1037  1540 D WifiNative-wlan0: doBoolean: SCAN
09-13 16:10:52.768  1037  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 16:10:52.768  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 16:10:52.768  1037  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 16:10:52.768  1037  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 16:10:52.769  1037  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 16:10:52.769  1037  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-13 16:10:52.778  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:52.778  1037  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 16:10:52.778  1037  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 16:10:52.779  1037  1539 D LGWifiP2pService: InactiveState
09-13 16:10:52.779  1037  1539 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.779  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.779  1037  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 16:10:52.779  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 16:10:52.780  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-13 16:10:52.780  1969  7558 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 16:10:52.780  1037  7557 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 16:10:52.780  1037  7557 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.780  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.780  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 16:10:52.780  7536  7536 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 16:10:52.780  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  1969  7558 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.781  1037  7557 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.781  1037  7557 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  1969  7558 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.781  1037  7557 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 16:10:52.781  1037  7557 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  1037  7557 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.781  1037  7557 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:10:52.784  6933  7562 V FormManager: Network unavailable.
09-13 16:10:52.784  1037  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 16:10:52.784  1037  1539 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.784  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.784  1037  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.784  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.784  1037  1540 D WifiNative-wlan0: SCAN: returned false
09-13 16:10:52.784  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=205864  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: Defaul,tState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1969  2310 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.785  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:52.786  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:52.786  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=205865  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 16:10:52.786  1037  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:52.786  1037  1037 E WifiServerServiceExt: No p2p device connected
09-13 16:10:52.786  6933  7562 V FormManager: Network unavailable.
09-13 16:10:52.786  1037  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:52.787  1037  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:52.787  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:52.787  1037  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:52.788  1037  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 16:10:52.788  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:52.788  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:52.789  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.789  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:52.789  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 16:10:52.789  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:52.791  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:52.791  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 16:10:52.792  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:52.795  6648  6648 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 16:10:52.795  6648  6648 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 16:10:52.795  6648  6648 V [BNRBootReceiver]: Boot Receiver Return
09-13 16:10:52.798  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:52.804  4333  7563 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:52.805  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:52.808  4333  7564 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 16:10:52.808  4333  7564 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:52.811  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:52.816  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 16:10:52.816  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:52.817  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:52.820  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:52.825  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:52.829  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:52.834  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:52.834  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:52.835  6913  6913 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:10:53.182  6736  7519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:10:53.186  6736  7519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:10:53.189  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:53.189  6736  6814 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 16:10:53.190  1037  2096 D WifiServiceImplEx: setWifiEnabled: true pid=6736, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:10:53.191  1037  2096 D WifiService: setWifiEnabled: true pid=6736, uid=10118
09-13 16:10:53.191  1037  2096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:10:53.201  6736  7574 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 16:10:53.201  6736  7574 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:10:53.393  7536  7536 E wpa_supplicant: USIM:  scard_init function
,09-13 16:10:53.395  7536  7536 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-13 16:10:53.409  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 16:10:53.409  1037  7557 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 16:10:53.409  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 16:10:53.409  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
09-13 16:10:53.410  1037  7557 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 16:10:53.410  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 16:10:53.410  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 16:10:53.411  1037  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 16:10:53.412  1037  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 16:10:53.412  1037  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 16:10:53.412  1037  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 16:10:53.412  1037  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 16:10:53.432  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=206511  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 16:10:53.439  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=206518  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 16:10:53.443  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.444  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:53.445  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.445  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.445  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 16:10:53.448  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:53.451  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:53.451  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 16:10:53.464  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-13 16:10:53.473  6891  6891 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 16:10:53.492  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:53.503  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:53.511  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.519  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.519  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.519  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 16:10:53.527  7536  7536 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 16:10:53.532  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 16:10:53.532  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 16:10:53.532  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 16:10:53.532  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 16:10:53.532  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:53.533  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 16:10:53.537  7536  7536 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 16:10:53.537  7536  7536 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 16:10:53.541  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=206620  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 16:10:53.542  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=206620  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 16:10:53.542  1037  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206621
09-13 16:10:53.543  1037  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206621
09-13 16:10:53.543  1037  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206622
09-13 16:10:53.547  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:53.547  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 16:10:53.552  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 16:10:53.552  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 16:10:53.552  1037  7557 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 16:10:53.552  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 16:10:53.552  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 16:10:53.553  1037  7557 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 16:10:53.553  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:53.553  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:53.554  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206622
,09-13 16:10:53.554  1037  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206633
09-13 16:10:53.555  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206634  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 16:10:53.560  1037  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 16:10:53.572  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 16:10:53.572  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.572  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 16:10:53.573  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.573  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:53.575  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206653  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 16:10:53.575  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.576  1037  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=206654  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,09-13 16:10:53.576  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=206655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 16:10:53.577  1037  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206656
09-13 16:10:53.577  1037  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206656
09-13 16:10:53.581  1037  1540 D WifiNative-wlan0: doString: [STATUS]
09-13 16:10:53.581  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 16:10:53.581  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 16:10:53.581  6891  6891 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 16:10:53.581  6891  6891 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 16:10:53.581  1037  7557 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 16:10:53.581  1037  7557 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 16:10:53.584  1037  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 16:10:53.584  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.584  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.584  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 16:10:53.584  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:53.584  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 16:10:53.585  1037  1540 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 16:10:53.586  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 16:10:53.587  6891  6891 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 16:10:53.587  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 16:10:53.587  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 16:10:53.587  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 16:10:53.587  6891  6891 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 16:10:53.587  6891  6891 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 16:10:53.587  6891  6891 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 16:10:53.591  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:53.592  1037  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 16:10:53.592  1037  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 16:10:53.597  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.597  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:53.599  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.601  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.601  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.602  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 16:10:53.603  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.603  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.603  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-13 16:10:53.609  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:53.611  1037  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 16:10:53.611  1037  1547 D ConnectivityService: Got NetworkAgent Messenger
09-13 16:10:53.611  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 16:10:53.611  1037  1547 D ConnectivityService: NetworkAgent connected
09-13 16:10:53.612  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:10:53.612  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 16:10:53.612  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 16:10:53.612  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 16:10:53.616  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 16:10:53.617  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 16:10:53.617  1037  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:10:53.617  1037  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 16:10:53.617  1037  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-13 16:10:53.617  1037  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 16:10:53.621  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.621  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:53.622  1037  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 16:10:53.623  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.624   313   897 D CommandListener: Setting iface cfg
09-13 16:10:53.624  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.624  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:53.625  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.630  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.630  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.630  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:53.631  1037  1540 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 16:10:53.631  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=206710  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:53.632  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=206711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:53.632  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=206711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:53.633  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:53.633  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:53.634  1037  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:53.634  1037  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:53.635  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:53.635  1037  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 16:10:53.635  1037  7594 D DhcpStateMachine: StoppedState
09-13 16:10:53.635  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:53.636  1037  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=206715  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:53.637  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:53.637  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,09-13 16:10:53.638  1037  7594 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.638  1037  7594 D DhcpStateMachine: WaitBeforeStartState
09-13 16:10:53.639  1037  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=206718  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:53.640  1037  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=206718  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 16:10:53.641  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:947] from screen [on:0 period:602071113] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:53.642  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:602071114] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:53.642  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 16:10:53.645  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:53.648  1037  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-13 16:10:53.648  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:53.648  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.648  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 16:10:53.649  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:53.649  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:53.649  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:53.650  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 16:10:53.650  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 16:10:53.651  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:53.651  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=208,0,0
09-13 16:10:53.651  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 16:10:53.651  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=208,0,0
09-13 16:10:53.651  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 16:10:53.652  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 16:10:53.653  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 16:10:53.653  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 16:10:53.653  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.653  1037  1540 D WifiNative-wlan0: SET ps 0: returned true
09-13 16:10:53.653  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 16:10:53.653  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 16:10:53.654  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 16:10:53.654  1037  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 16:10:53.654  1037  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 16:10:53.654  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d0af1a4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.654  1037  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 16:10:53.654  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d0af1a4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.654  1037  7594 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.654  1037  7594 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 16:10:53.655   313   897 D CommandListener: Setting iface cfg
09-13 16:10:53.655   313   897 D CommandListener: Trying to bring up wlan0
09-13 16:10:53.656  1037  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 16:10:53.657  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:10:53.657  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 16:10:53.657  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 16:10:53.657  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 16:10:53.657  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 16:10:53.658  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 16:10:53.658  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.658  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.658  1037  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 16:10:53.658  1037  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUS,PENDMODE 1
09-13 16:10:53.658  7536  7536 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 16:10:53.659  1037  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 16:10:53.659  1037  1540 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 16:10:53.660  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 16:10:53.660  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.661  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:53.664  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:53.670  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:53.675  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.679  1037  1540 D WifiNative-wlan0: SET ps 1: returned true
09-13 16:10:53.680  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 16:10:53.680  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:53.681  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:53.681  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.681  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:53.681  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.681  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:53.681  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:53.682  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:53.682  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:53.683  1037  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 16:10:53.683  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 16:10:53.683  1037  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 16:10:53.684  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 16:10:53.684  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
09-13 16:10:53.685  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:53.687  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.687  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 16:10:53.688  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 16:10:53.689  1037  1547 D ConnectivityService: Adding iface wlan0 to network 102
09-13 16:10:53.690  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.690  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.690  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 16:10:53.690  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.697  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.697  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.697  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-13 16:10:53.703  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 16:10:53.705  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 16:10:53.706  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.706  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.706  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 16:10:53.706  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 16:10:53.709  1037  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 16:10:53.711  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.711  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:53.711  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 16:10:53.714  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:53.717  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:53.717  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:10:53.719  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.719  1037  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 16:10:53.719  1037  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 16:10:53.720  1037  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 16:10:53.721   313   897 E Netd    : netlink response contains error (File exists)
09-13 16:10:53.721  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.721  1037  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 16:10:53.722  1037  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 16:10:53.722  1037  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 16:10:53.722  1037  1547 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 16:10:53.723  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 16:10:53.723  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.723  1037  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.723  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.724  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 16:10:53.724  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:53.724  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 16:10:53.724  6736  7597 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 16:10:53.724  6736  7597 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:10:53.724  6736  7574 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:10:53.724  6736  7574 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:10:53.724  6736  7574 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:10:53.725  6736  7574 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:10:53.725  6736  7574 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:10:53.723  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.725  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:53.725  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:53.725  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 16:10:53.725  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.725  1037  1547 D ConnectivityService:     satisfied: NetworkReq,uest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 16:10:53.725  1037  1547 D ConnectivityService: currentScore = 0, newScore = 20
09-13 16:10:53.725  1037  1547 D ConnectivityService:    accepting network in place of null
09-13 16:10:53.726  1037  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.726  6736  7597 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:10:53.726  6736  7597 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:10:53.726  6736  7597 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:10:53.727  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 16:10:53.727  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 16:10:53.728   313  7604 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 16:10:53.728  1037  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.728  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:53.729  1880  1880 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.729  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.729  1037  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 16:10:53.729  1037  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 16:10:53.729  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 16:10:53.729  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:10:53.729  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:53.729  1037  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 16:10:53.730  6736  7603 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 937, name: OutgoingSocketThread/Receiver)
09-13 16:10:53.730  1037  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-13 16:10:53.730  1037  1547 D ConnectivityService: validation of new default Network = false
09-13 16:10:53.730  1037  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 16:10:53.730  1037  1547 D DSQN    : enableDataServiceNotify 
09-13 16:10:53.730  1037  1547 D DSQN    : start dsqn bin
09-13 16:10:53.733  6736  7602 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 936, name: OutgoingSocketThread/Sender)
09-13 16:10:53.733  6736  7603 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 937, thread name: OutgoingSocketThread/Receiver)
09-13 16:10:53.733  6736  7606 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 939, name: IncomingSocketThread/Receiver)
09-13 16:10:53.734  6736  7606 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 939, thread name: IncomingSocketThread/Receiver)
09-13 16:10:53.734  6736  7603 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:10:53.734  6736  7606 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:10:53.734  6736  7605 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 938, name: IncomingSocketThread/Sender)
09-13 16:10:53.734  6736  7603 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 937, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:10:53.735  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 16:10:53.735  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 16:10:53.735  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 16:10:53.735  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 16:10:53.736  6736  7606 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 939, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:10:53.739  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 16:10:53.739  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 16:10:53.740  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.743  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.743  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.743  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:53.744  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:53.736  7607  7607 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:53.736  7607  7607 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:53.748  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 16:10:53.748  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.748  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.749  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:53.755  1037  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-13 16:10:53.757  7607  7607 E DSQN    : DSQN ssw
09-13 16:10:53.758  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:53.766  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:53.771  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.777   313  7604 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 16:10:53.777  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 16:10:53.778  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.778  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:53.781  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 16:10:53.785  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:53.785  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.786  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.786  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:53.790  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.794  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.795  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.795  6913  6913 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 16:10:53.797  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:53.801  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 16:10:53.801  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 16:10:53.803  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 16:10:53.806  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.811  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.811  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.812  6913  6913 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-13 16:10:53.812  6913  6913 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 16:10:53.813  6913  6913 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 16:10:53.817  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 16:10:53.817   313  7604 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 16:10:53.820  6863  6863 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 16:10:53.820  6863  6863 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 16:10:53.824  6891  6891 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 16:10:53.828  6891  6891 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 16:10:53.833  6913  6913 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 16:10:53.833  6913  6913 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 16:10:53.834  6913  6913 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 16:10:53.835  6913  6913 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 16:10:53.835  6913  6913 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-13 16:10:53.842   313   896 D LGDataListener: argv[0]=dsqncommand
09-13 16:10:53.842   313   896 D LGDataListener: argv[1]=wlan0
09-13 16:10:53.842   313   896 D LGDataListener: argv[2]=1
09-13 16:10:53.842   313   896 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 16:10:53.842  1037  1097 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 16:10:53.842  1037  1097 D DSQN    : start to monitor internet connection
09-13 16:10:53.858  1037  7594 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 16:10:53.859  1037  7594 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 16:10:53.859  1037  7594 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-13 16:10:53.856  7613  7613 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:53.856  7613  7613 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 16:10:53.869  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 14:10:53 GMT], X-Android-Received-Millis=[1473775853869], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473775853842]}
09-13 16:10:53.870  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 16:10:53.870  1037  7593 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 16:10:53.870  1037  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.870  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.870  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:53.871  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:53.871  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 16:10:53.871  1037  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 16:10:53.871  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 16:10:53.871  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.871  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:53.872  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:53.873  1037  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.873  1037  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:53.873  1037  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 16:10:53.874  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 16:10:53.875  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 16:10:53.876  1880  1880 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:10:53.877  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 16:10:53.885  7613  7613 I dhcpcd  : version 5.5.6 starting
09-13 16:10:53.888  7613  7613 E dhcpcd  : get_duid: m
09-13 16:10:53.888  7613  7613 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
,09-13 16:10:53.888  7613  7613 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 16:10:53.911  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:10:53.912  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 16:10:53.913  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:53.977  7613  7613 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 16:10:53.978  7613  7613 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 16:10:53.978  7613  7613 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 16:10:53.979  7613  7613 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 16:10:53.979  7613  7613 D dhcpcd  : wlan0: sending REQUEST (xid 0xd63d789a), next in 3.28 seconds
09-13 16:10:54.047  7613  7613 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 16:10:54.049  7613  7613 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 16:10:54.049  7613  7613 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-13 16:10:54.050  7613  7613 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 16:10:54.051  7613  7613 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 16:10:54.051  7613  7613 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 16:10:54.052  7613  7613 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 16:10:54.052  7613  7613 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 16:10:54.052  7613  7613 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 16:10:54.102  7318  7340 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-13 16:10:54.234  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 16:10:54.236  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 16:10:54.236  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.241  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.241  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.247  1037  1099 D Tethering: MasterInitialState.processMessage what=3
,09-13 16:10:54.249  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-13 16:10:54.254  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1e531bb2 Bundle[{}]
09-13 16:10:54.255  6736  6814 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:10:54.255  6736  6814 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 16:10:54.255  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 16:10:54.256  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 16:10:54.257  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 16:10:54.258  6736  6814 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 16:10:54.264  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.264  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:54.264  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 16:10:54.267  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 16:10:54.276  6466  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:54.280  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:10:54.282  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:54.282  6736  7638 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 16:10:54.282  6736  7638 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 16:10:54.283  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:54.291  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:10:54.296  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:10:54.299  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:54.302  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:54.309  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 16:10:54.329  2276  2276 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:54.340  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 16:10:54.340  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.341  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 16:10:54.341  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 16:10:54.347  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 16:10:54.352  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:54.352  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:54.352  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:54.353  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:54.353  7102  7102 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 16:10:54.357  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.357  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:54.359  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:54.362  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:54.367  3525  3525 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.369  4333  7652 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:54.371  4333  7654 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.371  3525  3525 V DownloadManager: DownloadService onCreate
09-13 16:10:54.371  4333  7654 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:54.372  4333  7652 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 16:10:54.374  3525  7655 I DownloadManager: in removeSpuriousFiles
09-13 16:10:54.375  3525  7655 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 16:10:54.376  3525  7655 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@43acc2 on behalf of 3525
,09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 16:10:54.377  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 16:10:54.380  3525  7655 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 16:10:54.382  4333  7652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 16:10:54.383  3525  7655 I DownloadManager: in trimDatabase
09-13 16:10:54.384  3525  7655 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 16:10:54.385  3525  7655 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b7fdad3 on behalf of 3525
09-13 16:10:54.389  4333  4333 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,09-13 16:10:54.389  4333  4333 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 16:10:54.390  4333  4333 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 16:10:54.391  4333  4333 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 16:10:54.394  3525  3525 V DownloadManager: DownloadService onStartCommand
09-13 16:10:54.395  7144  7658 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:54.394  3525  7656 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 16:10:54.396  3525  7656 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1623d30e on behalf of 3525
09-13 16:10:54.400  4333  4333 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 16:10:54.405  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 16:10:54.405  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.406  3525  7656 V DownloadManager: processing inserted download 1
09-13 16:10:54.406  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 16:10:54.407  3525  7656 V DownloadManager: processing inserted download 4
09-13 16:10:54.408  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 16:10:54.409  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 16:10:54.409  3525  7656 V DownloadManager: processing inserted download 7
,09-13 16:10:54.410  3525  7656 V DownloadManager: processing inserted download 8
09-13 16:10:54.411  3525  7656 V DownloadManager: processing inserted download 9
09-13 16:10:54.414  3525  7656 V DownloadManager: processing inserted download 10
09-13 16:10:54.415  3525  7656 V DownloadManager: processing inserted download 11
09-13 16:10:54.418  3525  7656 V DownloadManager: processing inserted download 12
09-13 16:10:54.420  3525  7656 V DownloadManager: processing inserted download 13
09-13 16:10:54.421  7296  7296 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:54
09-13 16:10:54.421  3525  7656 V DownloadManager: processing inserted download 14
,09-13 16:10:54.423  7296  7296 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 16:10:54.423  3525  7656 V DownloadManager: processing inserted download 16
09-13 16:10:54.423  7296  7296 D Weather.Utils: 2 : All the weather widget is gone.
09-13 16:10:54.423  7296  7296 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 16:10:54.423  7296  7296 D WeatherAncestor: connectivity changed - connection : true
09-13 16:10:54.424  7296  7296 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2266284e
09-13 16:10:54.425  7296  7296 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 16:10:54.425  7296  7296 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 16:10:54.425  7296  7296 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 16:10:54.425  7296  7296 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 16:10:54.425   313  7664 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 16:10:54.426   313  7664 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-13 16:10:54.426  7296  7296 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:54
09-13 16:10:54.428  3525  3525 V DownloadManager: DownloadService onDestroy
09-13 16:10:54.447  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 16:10:54.448  6466  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 16:10:54.463  1037  7594 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 16:10:54.464  2276  2276 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.465  1037  7594 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 16:10:54.465  1037  7594 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 16:10:54.465  1037  7594 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 16:10:54.465  1037  7594 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 16:10:54.465  1037  7594 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 16:10:54.465  1037  7594 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 16:10:54.465  1037  7594 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 16:10:54.466  1037  7594 D DhcpStateMachine: RunningState
,09-13 16:10:54.468   313  7664 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-13 16:10:54.475  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 16:10:54.475  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.475  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 16:10:54.475  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 16:10:54.477  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 16:10:54.483  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:54.483  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:54.483  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:54.483  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:54.484  7102  7102 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 16:10:54.489  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.489  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:54.493  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:54.498  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:54.505  3525  3525 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:54.509  4333  7665 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 16:10:54.513  6933  7661 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 16:10:54.514  3525  3525 V DownloadManager: DownloadService onCreate
09-13 16:10:54.516  6933  7661 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 16:10:54.517  4333  7665 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 16:10:54.518  4333  7666 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.519  4333  7666 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:54.530  3525  7667 I DownloadManager: in removeSpuriousFiles
09-13 16:10:54.531  3525  7667 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 16:10:54.534  4333  7665 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 16:10:54.534  3525  7667 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2060133c on behalf of 3525
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 16:10:54.535  3525  7667 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 16:10:54.539  3525  7667 I DownloadManager: in trimDatabase
09-13 16:10:54.540  3525  7667 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 16:10:54.542  4333  4333 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 16:10:54.543  4333  4333 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 16:10:54.543  4333  4333 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-13 16:10:54.545  4333  4333 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 16:10:54.545  3525  7667 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ace121a on behalf of 3525
09-13 16:10:54.547  3525  3525 V DownloadManager: DownloadService onStartCommand
09-13 16:10:54.548  3525  7668 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 16:10:54.549  7144  7669 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:54.550  3525  7668 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@21b92728 on behalf of 3525
09-13 16:10:54.553  4333  4333 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 16:10:54.554  3525  7668 V DownloadManager: processing inserted download 1
09-13 16:10:54.555  3525  7668 V DownloadManager: processing inserted download 4
09-13 16:10:54.557  3525  7668 V DownloadManager: processing inserted download 7
09-13 16:10:54.557  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 16:10:54.557  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:54.557  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 16:10:54.560  3525  7668 V DownloadManager: processing inserted download 8
09-13 16:10:54.561  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 16:10:54.561  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 16:10:54.567  3525  7668 V DownloadManager: processing inserted download 9
09-13 16:10:54.569  3525  7668 V DownloadManager: processing inserted download 10
09-13 16:10:54.570  3525  7668 V DownloadManager: processing inserted download 11
09-13 16:10:54.571  7296  7296 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:54
,09-13 16:10:54.573  3525  7668 V DownloadManager: processing inserted download 12
09-13 16:10:54.574  3525  7668 V DownloadManager: processing inserted download 13
09-13 16:10:54.575  3525  7668 V DownloadManager: processing inserted download 14
09-13 16:10:54.575  7296  7296 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 16:10:54.575  7296  7296 D Weather.Utils: 2 : All the weather widget is gone.
09-13 16:10:54.576  7296  7296 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 16:10:54.576  7296  7296 D WeatherAncestor: connectivity changed - connection : true
09-13 16:10:54.576  7296  7296 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2266284e
09-13 16:10:54.577  7296  7296 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 16:10:54.577  7296  7296 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 16:10:54.577  7296  7296 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 16:10:54.577  3525  7668 V DownloadManager: processing inserted download 16
09-13 16:10:54.577  7296  7296 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 16:10:54.577  7296  7296 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:54
09-13 16:10:54.583  3525  3525 V DownloadManager: DownloadService onDestroy
,09-13 16:10:54.597  6933  7673 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 16:10:54.599  6933  7673 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 16:10:54.744  1037  1547 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 16:10:54.770  1037  1054 I ActivityManager: Killing 7013:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-13 16:10:54.785  6736  7638 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 16:10:54.786  6736  7638 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:10:54.786  6736  7638 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:10:54.786  6736  7638 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:10:54.788  6736  7638 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:10:54.789  6736  7677 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 950, name: OutgoingSocketThread/Sender)
09-13 16:10:54.789  6736  7674 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 16:10:54.789  6736  7674 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:10:54.789  6736  7674 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:10:54.790  6736  7674 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:10:54.801  6736  7678 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 951, name: OutgoingSocketThread/Receiver)
09-13 16:10:54.801  6736  7674 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:10:54.803  6736  7678 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 951, thread name: OutgoingSocketThread/Receiver)
09-13 16:10:54.803  6736  7678 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:10:54.803  6736  7678 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 951, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:10:54.803  6736  7679 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 952, name: IncomingSocketThread/Sender)
,09-13 16:10:54.808  6736  7680 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 953, name: IncomingSocketThread/Receiver)
09-13 16:10:54.810  6736  7680 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 953, thread name: IncomingSocketThread/Receiver)
09-13 16:10:54.810  6736  7680 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:10:54.810  6736  7680 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 953, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:10:54.870  1037  1993 W libprocessgroup: failed to open /acct/uid_10037/pid_7013/cgroup.procs: No such file or directory
,09-13 16:10:55.168  1037  1934 I ActivityManager: Killing 7049:com.lge.settings.easy/1000 (adj 15): empty #17
,09-13 16:10:55.199  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_7049/cgroup.procs: No such file or directory
,09-13 16:10:55.293  6736  6814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 962)
09-13 16:10:55.294  6736  6814 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 16:10:55.294  6736  6814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 963)
09-13 16:10:55.297  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:10:55.297  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c63cadc added. We now have 4 listener(s)
,09-13 16:10:55.300  1037  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:55.303  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:10:55.303  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:10:55.303  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:10:55.303  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:10:55.303  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7497e5 added. We now have 4 listener(s)
09-13 16:10:55.304  6736  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:10:55.304  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:10:55.309  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:10:55.312  6736  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:10:55.318  6736  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:10:55.318  6736  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:10:55.320  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:55.322  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:55.326  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:55.326  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:55.326  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:55.326  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:10:55.326  6736  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c63cadc removed from the list
09-13 16:10:55.326  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:55.326  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7497e5 removed from the list
09-13 16:10:55.326  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:55.326  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:10:55.334  1037  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:55.334  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:55.335  1037  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:55.335  1037  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:55.336  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:55.336  1037  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 16:10:55.337  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 16:10:55.337  1037  1547 D ConnectivityService: identical MTU - not setting
09-13 16:10:55.337  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 16:10:55.338  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 16:10:55.338  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:10:55.338  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:55.338  1037  1547 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:10:55.340  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 16:10:55.344  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:10:55.344  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:10:55.344  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:10:55.344  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:55.344  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:10:55.350  6736  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:10:55.351  1037  2087 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:55.356  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:10:55.357  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:10:55.360  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:10:55.361  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:55.363  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:10:56.169  1037  1539 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:56.169  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:10:56.170  1037  1539 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 16:10:56.230  1037  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 16:10:56.231  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 16:10:56.232  1037  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 16:10:56.233  1037  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 16:10:56.234  1037  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 16:10:56.236  1037  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 16:10:56.651  1037  1540 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=104.0, 0.0, 0.0  rx=100.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:602074123] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:56.654  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=104.0, 0.0, 0.0  rx=100.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:602074126] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:56.655  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 16:10:56.672  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 16:10:56.707  1037  1542 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 16:10:56.730  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:56.745  1037  1099 D Tethering: MasterInitialState.processMessage what=3
09-13 16:10:56.766  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:10:56.773  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:10:56.776  1037  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:56.782  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 16:10:56.786  6466  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 16:10:56.797  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 16:10:56.817  2276  2276 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:10:56.832  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 16:10:56.832  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:56.832  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 16:10:56.832  7102  7102 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 16:10:56.836  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
09-13 16:10:56.840  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:56.840  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:56.840  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:56.841  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:56.841  7102  7102 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 16:10:56.846  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:56.846  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 16:10:56.847  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 16:10:56.853  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 16:10:56.858  3525  3525 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:56.867  3525  3525 V DownloadManager: DownloadService onCreate
,09-13 16:10:56.884  3525  7690 I DownloadManager: in removeSpuriousFiles
09-13 16:10:56.885  3525  7690 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 16:10:56.893  3525  7690 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@21ab35e6 on behalf of 3525
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 16:10:56.894  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 16:10:56.895  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 16:10:56.895  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 16:10:56.895  3525  7690 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-13 16:10:56.917  4333  7694 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 16:10:56.921  3525  7690 I DownloadManager: in trimDatabase
09-13 16:10:56.921  3525  7690 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 16:10:56.922  1037  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 16:10:56.925  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 16:10:56.925  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:56.925  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 16:10:56.925  3525  7690 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16363727 on behalf of 3525
,09-13 16:10:56.925  3468  3468 D PhoneState: setPdpRejectCasuse : false
09-13 16:10:56.926  7144  7693 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:56.930  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 16:10:56.931  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 16:10:56.932  4333  7694 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 16:10:56.937  4333  7698 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 16:10:56.937  4333  7698 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 16:10:56.942  7296  7296 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:56
09-13 16:10:56.944  3525  3525 V DownloadManager: DownloadService onStartCommand
09-13 16:10:56.945  3525  7691 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-13 16:10:56.947  3525  7691 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@19e4ca72 on behalf of 3525
09-13 16:10:56.948  4333  7694 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 16:10:56.949  7296  7296 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 16:10:56.949  7296  7296 D Weather.Utils: 2 : All the weather widget is gone.
09-13 16:10:56.949  7296  7296 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 16:10:56.949  7296  7296 D WeatherAncestor: connectivity changed - connection : true
09-13 16:10:56.949  7296  7296 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2266284e
09-13 16:10:56.951  4333  4333 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 16:10:56.951  7296  7296 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 16:10:56.951  7296  7296 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 16:10:56.951  7296  7296 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 16:10:56.951  7296  7296 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 16:10:56.951  7296  7296 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:10:56
09-13 16:10:56.954  4333  4333 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 16:10:56.954  4333  4333 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 16:10:56.956  4333  4333 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 16:10:56.959  4333  4333 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-13 16:10:56.963  3525  7691 V DownloadManager: processing inserted download 1
09-13 16:10:56.968  3525  7691 V DownloadManager: processing inserted download 4
,09-13 16:10:56.970  3525  7691 V DownloadManager: processing inserted download 7
09-13 16:10:56.971  3525  7691 V DownloadManager: processing inserted download 8
09-13 16:10:56.972  3525  7691 V DownloadManager: processing inserted download 9
09-13 16:10:56.973  3525  7691 V DownloadManager: processing inserted download 10
09-13 16:10:56.975  3525  7691 V DownloadManager: processing inserted download 11
09-13 16:10:56.977  3525  7691 V DownloadManager: processing inserted download 12
09-13 16:10:56.978  3525  7691 V DownloadManager: processing inserted download 13
09-13 16:10:56.979  3525  7691 V DownloadManager: processing inserted download 14
09-13 16:10:56.981  3525  7691 V DownloadManager: processing inserted download 16
09-13 16:10:56.983  3525  3525 V DownloadManager: DownloadService onDestroy
09-13 16:10:56.997  6933  7696 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 16:10:57.000  6933  7696 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-13 16:10:57.926   313  7726 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 16:10:57.936   313  7726 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-13 16:10:57.969   313  7726 D libc-netbsd: res_queryN name = www.google.com succeed
,09-13 16:10:57.977   313  7728 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 16:10:57.977   313  7728 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 16:10:57.977   313  7728 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 16:10:58.045  1037  1543 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-13 16:10:58.268  1037  1450 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:10:58.277  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 16:10:58.363  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:10:58.363  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 16:10:58.375  1037  1037 D administrator: Handling package changes for user 0
09-13 16:10:58.392  1037  1095 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7730 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 16:10:58.401  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 16:10:58.405  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 16:10:58.414  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 16:10:58.425  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:58.425  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:58.425  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:58.425  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c63cadc not in the list
09-13 16:10:58.425  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:58.425  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7497e5 not in the list
09-13 16:10:58.425  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:58.425  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:58.425  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:58.427  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:10:58.427  6736  6814 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:10:58.428  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 16:10:58.431  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:10:58.431  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:10:58.431  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:10:58.431  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:58.433  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:10:58.433  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:10:58.433  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:10:58.433  6736  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:10:58.435  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:10:58.435  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:10:58.435  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:58.435  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:10:58.440  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:10:58.441  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:10:58.442  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:10:58.443  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:10:58.443  6736  6814 I org.thaliproject.p2p.btconnec,torlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:10:58.443  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:10:58.443  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:10:58.443  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:58.443  6736  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:10:58.443  6736  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:10:58.443  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c63cadc not in the list
09-13 16:10:58.443  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:10:58.443  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7497e5 not in the list
09-13 16:10:58.443  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:10:58.443  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:10:58.443  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:58.444  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:10:58.444  6736  6814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:10:58.444  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:10:58.444  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:10:58.444  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:10:58.450  6736  6814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:10:58.451  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:10:58.452  6736  6814 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 16:10:58.453  1037  2087 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:10:58.454  6736  7755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:10:58.455  3900  4033 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=109 mFd=107
09-13 16:10:58.462  6736  7755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:10:58.462  6736  7755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:10:58.462  6736  7755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:10:58.462  6736  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:10:58.472  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:10:58.494  7730  7730 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 16:10:58.536  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-13 16:10:58.536  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 16:10:58.575  1037  1094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 16:10:58.579  1037  1094 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 16:10:58.585  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 16:10:58.587  2478  2478 V GmsNetworkLocationProvi: DISABLE
09-13 16:10:58.597  7730  7730 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 16:10:58.598  7730  7730 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 16:10:58.613  1037  1094 D LocationProviderProxy: applying state to connected service
,09-13 16:10:58.615  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-13 16:10:58.716  7730  7775 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 16:10:58.716  7730  7775 I Babel   : MmsConfig.loadMmsSettings
09-13 16:10:58.722  7730  7775 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 16:10:58.722  7730  7775 I Babel   : MmsConfig.loadFromDatabase
09-13 16:10:58.762  7730  7774 W AudioCapabilities: Unsupported mime audio/evrc
09-13 16:10:58.763  7730  7774 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 16:10:58.766  7730  7774 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 16:10:58.774  7730  7775 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 16:10:58.778  7730  7775 I Babel   : MmsConfig.loadFromResources
09-13 16:10:58.779  7730  7775 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 16:10:58.780  7730  7775 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-13 16:10:58.787  7730  7774 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 16:10:58.788  7730  7774 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 16:10:58.798  7730  7774 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 16:10:58.802  7730  7730 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:10:58.815  7730  7774 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 16:10:58.817  7730  7774 W VideoCapabilities: Unsupported mime video/divx
09-13 16:10:58.821  7730  7774 W VideoCapabilities: Unsupported mime video/divx311
09-13 16:10:58.823  7730  7774 W VideoCapabilities: Unsupported mime video/divx4
09-13 16:10:58.830  1842  7779 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 16:10:58.830  1842  7779 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-13 16:10:58.835  7730  7774 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-13 16:10:58.836  7102  7102 I AppUp4:CustModeStarterReceiver: onReceive
09-13 16:10:58.840  7102  7102 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33272950
09-13 16:10:58.840  7102  7102 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 16:10:58.840  7102  7102 D AppUp4:CustFacade: isPhone : true
09-13 16:10:58.841  7102  7102 D AppUp4:CustModeStarterReceiver: begin check event
09-13 16:10:58.841  7102  7102 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-13 16:10:58.845  1842  4793 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-13 16:10:58.857  7730  7774 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 16:10:58.861  7730  7774 W AudioCapabilities: Unsupported mime audio/eac3
09-13 16:10:58.861  7730  7774 W AudioCapabilities: Unsupported mime audio/ac3
09-13 16:10:58.862  7730  7774 W AudioCapabilities: Unsupported mime audio/g726
09-13 16:10:58.863  7730  7774 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 16:10:58.864  7730  7774 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 16:10:58.865  7730  7774 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 16:10:58.866  7730  7774 W VideoCapabilities: Unsupported mime video/theora
09-13 16:10:58.868  7730  7774 W VideoCapabilities: Unsupported mime video/mjpg
09-13 16:10:58.883  1037  1979 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7782 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-13 16:10:58.918  1037  1720 I ActivityManager: Killing 6648:com.lge.bnr/1000 (adj 15): empty #17
,09-13 16:10:58.919  7782  7782 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:10:58.919  7782  7782 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:10:58.920  7782  7782 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 16:10:58.920  7782  7782 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 16:10:58.921  7782  7782 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 16:10:59.111  1037  1779 W libprocessgroup: failed to open /acct/uid_1000/pid_6648/cgroup.procs: No such file or directory
,09-13 16:10:59.164  7782  7782 I SystemConfig: BUILD Country: EU
,09-13 16:10:59.165  7782  7782 I SystemConfig: BUILD Operator: OPEN
,09-13 16:10:59.242  1037  2016 I ActivityManager: Killing 6863:com.lge.sync/1000 (adj 15): empty #17
,09-13 16:10:59.363  1037  2016 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7805 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-13 16:10:59.364  1037  1595 W libprocessgroup: failed to open /acct/uid_1000/pid_6863/cgroup.procs: No such file or directory
,09-13 16:10:59.378  7782  7803 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 16:10:59.378  7782  7803 I SystemConfig: existFile = false
,09-13 16:10:59.378  7782  7803 I SystemConfig: canReadFile = false
09-13 16:10:59.379  7782  7803 I SystemConfig: systemFeature RCS result false
09-13 16:10:59.379  7782  7803 D SystemConfig: refreshRcsSupport() :false
,09-13 16:10:59.431  7805  7805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:10:59.431  7805  7805 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 16:10:59.432  7805  7805 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 16:10:59.432  7805  7805 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 16:10:59.561  7805  7805 I AppConfig: Total System Memory = 2995761152
,09-13 16:10:59.573  7805  7805 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-13 16:10:59.679  1037  1540 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=60.0, 0.0, 0.0  rx=55.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:602077151] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 16:10:59.682  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=60.0, 0.0, 0.0  rx=55.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:602077152] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:10:59.682  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 16:10:59.684  1037  2096 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7827 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 16:10:59.687  1037  2096 I ActivityManager: Killing 6980:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-13 16:10:59.710  6913  6913 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 16:10:59.715  6913  6913 W System.err: android.os.DeadObjectException
09-13 16:10:59.716  6913  6913 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 16:10:59.716  6913  6913 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 16:10:59.716  6913  6913 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 16:10:59.716  6913  6913 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 16:10:59.716  6913  6913 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:10:59.716  6913  6913 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:10:59.716  6913  6913 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 16:10:59.716  6913  6913 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 16:10:59.717  6913  6913 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 16:10:59.717  6913  6913 W System.err: android.os.DeadObjectException
09-13 16:10:59.717  6913  6913 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 16:10:59.717  6913  6913 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 16:10:59.717  6913  6913 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 16:10:59.717  6913  6913 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 16:10:59.717  6913  6913 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 16:10:59.717  6913  6913 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 16:10:59.717  6913  6913 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,09-13 16:10:59.717  6913  6913 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:10:59.722  6913  6913 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 16:10:59.722  6913  6913 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 16:10:59.722  6913  6913 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:10:59.722  6913  6913 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:10:59.722  6913  6913 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 16:10:59.722  6913  6913 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 16:10:59.722  6913  6913 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 16:10:59.724  6913  6913 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 16:10:59.820  1037  2087 W libprocessgroup: failed to open /acct/uid_1000/pid_6980/cgroup.procs: No such file or directory
09-13 16:10:59.820  1037  2087 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-13 16:10:59.829  6913  6913 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 16:10:59.829  6913  6913 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 16:10:59.885  1037  1779 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7844 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 16:10:59.893  6913  6913 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 16:10:59.972  7844  7844 D UEI.SmartControl: Quickset Services start...
09-13 16:10:59.974  7844  7844 I UEI.SmartControl: Manufacture = LGE
09-13 16:10:59.974  7844  7844 D UEI.SmartControl: Id = LGNevo
09-13 16:10:59.975  7844  7844 D UEI.SmartControl: File observer start...
09-13 16:10:59.976  7844  7844 E UEI.SmartControl: IR Port is disabled: false
09-13 16:10:59.976  7844  7844 D UEI.SmartControl: Starting file observer...
09-13 16:10:59.976  7844  7844 D UEI.SmartControl: Extracting JNI libs...
09-13 16:10:59.976  7844  7844 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-13 16:11:00.007  7827  7827 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 16:11:00.050  7844  7844 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 16:11:00.050  7844  7844 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 16:11:00.050  7844  7844 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-13 16:11:00.050  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 16:11:00.050  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 16:11:00.050  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 16:11:00.051  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
09-13 16:11:00.051  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 16:11:00.051  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
09-13 16:11:00.052  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
09-13 16:11:00.052  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 16:11:00.075  7844  7844 I UEI.SmartControl: --- Selecting new region: 6
09-13 16:11:00.075  7827  7827 D LgDataFeature: LgDataFeature() Constructor: none
09-13 16:11:00.075  7827  7827 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 16:11:00.077  7844  7844 I UEI.SmartControl: Model = LG-D855
,09-13 16:11:00.078  7844  7844 D UEI.SmartControl: QS Service created
09-13 16:11:00.089  7844  7844 I UEI.SmartControl: Service initServices...
09-13 16:11:00.092  7844  7844 D UEI.SmartControl: QS start get config
,09-13 16:11:00.130  7844  7844 D UEI.SmartControl: Loading JNI Libs...
,09-13 16:11:00.135  7827  7827 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 16:11:00.167  7827  7827 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 16:11:00.168  7827  7827 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 16:11:00.184  7827  7827 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 16:11:00.184  7827  7827 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 16:11:00.198  1037  1979 I ActivityManager: Killing 6891:com.android.settings/1000 (adj 15): empty #17
,09-13 16:11:00.280  1037  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6891/cgroup.procs: No such file or directory
,09-13 16:11:00.291  3525  3955 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-13 16:11:00.294  3525  3955 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@149fb340 on behalf of 7827
,09-13 16:11:00.301  4620  7897 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-13 16:11:00.346  1037  1054 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7898 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 16:11:00.364  7844  7844 I UEI.SmartControl: Supports setup maps: true
,09-13 16:11:00.367  7844  7844 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 16:11:00.367  7844  7844 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 16:11:00.367  7844  7844 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 16:11:00.367  7844  7844 I UEI.SmartControl: ### init IR Blaster...
09-13 16:11:00.373  7844  7844 D serial_port: Configuring serial port
09-13 16:11:00.375  7844  7844 E UEI.SmartControl: UEIBLaster setting for 616
09-13 16:11:00.375  7844  7844 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 16:11:00.375  7844  7844 I UEI.SmartControl: configuring settings for MAXQ616
09-13 16:11:00.375  7844  7844 I UEI.SmartControl: Get version...
,09-13 16:11:00.383  7827  7827 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 16:11:00.395  7844  7915 D UEI.SmartControl: serial port data available: 21
09-13 16:11:00.412  7827  7827 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 16:11:00.422  7844  7844 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 16:11:00.422  7844  7844 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 16:11:00.422  7844  7844 I UEI.SmartControl: QS saving settings...
09-13 16:11:00.423  7844  7844 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 16:11:00.439  7844  7915 D UEI.SmartControl: serial port data available: 4
,09-13 16:11:00.470  7844  7926 I UEI.SmartControl: Device manager: loading config....
09-13 16:11:00.471  7844  7926 D UEI.SmartControl: ----------- loading internal config...
09-13 16:11:00.471  7844  7844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 16:11:00.477  1037  2016 I art     : Explicit concurrent mark sweep GC freed 143585(6MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.823ms total 79.594ms
09-13 16:11:00.478  7844  7844 E UEI.SmartControl: Services init done
09-13 16:11:00.479  7844  7844 D UEI.SmartControl: QS Service init finished
09-13 16:11:00.479  7844  7844 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 16:11:00.479  7844  7844 D UEI.SmartControl: QS Service version code: 201091
09-13 16:11:00.486  7844  7844 D UEI.SmartControl: Service requested: Control
09-13 16:11:00.486  7844  7926 E UEI.SmartControl: Loading SETTINGS...
,09-13 16:11:00.488  6913  6913 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 16:11:00.489  1037  1053 I ActivityManager: Killing 6913:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 16:11:00.491  7844  7859 I UEI.SmartControl: ------ IControl API: 11
09-13 16:11:00.492  7844  7859 I UEI.SmartControl: Registering callback...
09-13 16:11:00.497  7898  7898 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-13 16:11:00.514  7844  7926 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 16:11:00.530  7844  7925 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 16:11:00.530  7844  7925 D UEI.SmartControl: -----service ready thread exits
,09-13 16:11:00.548  1037  2087 W libprocessgroup: failed to open /acct/uid_10112/pid_6913/cgroup.procs: No such file or directory
09-13 16:11:00.548  7844  7844 D UEI.SmartControl: Internal service binding...
,09-13 16:11:00.561  7898  7898 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-13 16:11:00.562  7898  7898 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 16:11:00.562  7898  7898 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 16:11:00.562  7898  7898 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 16:11:00.562  7898  7898 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 16:11:00.562  7898  7898 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-13 16:11:00.579  1037  1779 I ActivityManager: Killing 7276:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-13 16:11:00.637  1037  1934 W libprocessgroup: failed to open /acct/uid_10005/pid_7276/cgroup.procs: No such file or directory
,09-13 16:11:00.856  1037  1979 V SIM_STK : Menu title from STK is T-Mobile
,09-13 16:11:00.881  4620  7897 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 578 ms] updated apps [took 577 ms] 
,09-13 16:11:01.453  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:11:01.454  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:11:01.454  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:11:01.454  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c63cadc not in the list
09-13 16:11:01.454  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:11:01.454  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7497e5 not in the list,
09-13 16:11:01.454  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:11:01.454  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:11:01.454  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:11:01.470  6736  6814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:11:01.470  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:11:01.471  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:11:01.471  6736  6814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c63cadc not in the list
09-13 16:11:01.471  6736  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:11:01.471  6736  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7497e5 not in the list
09-13 16:11:01.471  6736  6814 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:11:01.471  6736  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:11:01.472  6736  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:11:01.473  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:11:01.473  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:11:01.473  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 16:11:01.473  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:11:01.474  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:11:01.474  6736  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 16:11:01.486  6736  7940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 982, name: My test thread name)
,09-13 16:11:02.695  1037  1540 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=35.0, 0.0, 0.0  rx=30.9 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:602080167] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 16:11:02.705  1037  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=35.0, 0.0, 0.0  rx=30.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:602080177] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 16:11:02.705  1037  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 16:11:03.485  6736  6814 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 982
09-13 16:11:03.485  6736  6814 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 982, name: My test thread name)
,09-13 16:11:03.499  6736  7941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 983, name: My test thread name)
09-13 16:11:03.499  6736  7941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 983, thread name: My test thread name)
09-13 16:11:03.499  6736  7941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 983, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 16:11:03.501  6736  6814 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:11:03.506  6736  7942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 987, name: My test thread name)
09-13 16:11:03.507  6736  7942 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 987, thread name: My test thread name): Test exception.
09-13 16:11:03.507  6736  7942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 987, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 16:11:03.512  6736  6814 I jxcore-log: Total number of executed tests:  82
09-13 16:11:03.512  6736  6814 I jxcore-log: 
09-13 16:11:03.512  6736  6814 I jxcore-log: Number of passed tests:  82
09-13 16:11:03.512  6736  6814 I jxcore-log: 
09-13 16:11:03.513  6736  6814 I jxcore-log: Number of failed tests:  0
09-13 16:11:03.513  6736  6814 I jxcore-log: 
09-13 16:11:03.513  6736  6814 I jxcore-log: Number of ignored tests:  0
09-13 16:11:03.513  6736  6814 I jxcore-log: 
09-13 16:11:03.513  6736  6814 I jxcore-log: Total duration:  20255
09-13 16:11:03.513  6736  6814 I jxcore-log: 
09-13 16:11:03.515  6736  6814 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:11:03.515  6736  6814 I jxcore-log: 
09-13 16:11:03.516  6736  6814 I jxcore-log: My device name is: LGE-LG-D855
09-13 16:11:03.516  6736  6814 I jxcore-log: 
09-13 16:11:03.531  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.531  6736  6814 I jxcore-log: 
09-13 16:11:03.532  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.532  6736  6814 I jxcore-log: 
09-13 16:11:03.533  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.533  6736  6814 I jxcore-log: 
09-13 16:11:03.535  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.535  6736  6814 I jxcore-log: 
09-13 16:11:03.536  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.536  6736  6814 I jxcore-log: 
,09-13 16:11:03.549  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.549  6736  6814 I jxcore-log: 
09-13 16:11:03.551  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:11:03.551  6736  6814 I jxcore-log: 
09-13 16:11:03.552  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:11:03.552  6736  6814 I jxcore-log: 
09-13 16:11:03.553  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:11:03.553  6736  6814 I jxcore-log: 
09-13 16:11:03.554  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:11:03.554  6736  6814 I jxcore-log: 
09-13 16:11:03.555  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.555  6736  6814 I jxcore-log: 
09-13 16:11:03.556  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.556  6736  6814 I jxcore-log: 
09-13 16:11:03.557  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.557  6736  6814 I jxcore-log: 
09-13 16:11:03.559  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.559  6736  6814 I jxcore-log: 
09-13 16:11:03.559  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.559  6736  6814 I jxcore-log: 
09-13 16:11:03.560  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.560  6736  6814 I jxcore-log: 
09-13 16:11:03.561  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.561  6736  6814 I jxcore-log: 
09-13 16:11:03.562  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.562  6736  6814 I jxcore-log: 
09-13 16:11:03.563  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.563  6736  6814 I jxcore-log: 
,09-13 16:11:03.568  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.568  6736  6814 I jxcore-log: 
09-13 16:11:03.569  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.569  6736  6814 I jxcore-log: 
09-13 16:11:03.570  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.570  6736  6814 I jxcore-log: 
09-13 16:11:03.570  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.570  6736  6814 I jxcore-log: 
09-13 16:11:03.571  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.571  6736  6814 I jxcore-log: 
09-13 16:11:03.572  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.572  6736  6814 I jxcore-log: 
09-13 16:11:03.573  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.573  6736  6814 I jxcore-log: 
09-13 16:11:03.573  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.573  6736  6814 I jxcore-log: 
09-13 16:11:03.574  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.574  6736  6814 I jxcore-log: 
09-13 16:11:03.575  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:11:03.575  6736  6814 I jxcore-log: 
09-13 16:11:03.576  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:11:03.576  6736  6814 I jxcore-log: 
09-13 16:11:03.577  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:11:03.577  6736  6814 I jxcore-log: 
09-13 16:11:03.577  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.577  6736  6814 I jxcore-log: 
09-13 16:11:03.579  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.579  6736  6814 I jxcore-log: 
09-13 16:11:03.580  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:11:03.580  6736  6814 I jxcore-log: 
09-13 16:11:03.581  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.581  6736  6814 I jxcore-log: 
09-13 16:11:03.581  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on",,"cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.581  6736  6814 I jxcore-log: 
09-13 16:11:03.582  6736  6814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:11:03.582  6736  6814 I jxcore-log: 
,09-13 16:11:03.698  6736  7940 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 982, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-13 16:11:03.881  7943  7943 D AndroidRuntime: 
09-13 16:11:03.881  7943  7943 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 16:11:03.891  7943  7943 D AndroidRuntime: CheckJNI is OFF
09-13 16:11:04.052  7943  7943 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:11:04.073  1037  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-13 16:11:04.075  1037  1095 I ActivityManager: Killing 6736:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 16:11:04.117  1037  1934 I WindowState: WIN DEATH: Window{1bc3f8eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 16:11:04.117  1037  1546 D WifiService: Client connection lost with reason: 4
09-13 16:11:04.135  1037  1934 D InputDispatcher: Window went away: Window{1bc3f8eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:11:04.254  1037  1095 I ActivityManager:   Force finishing activity ActivityRecord{1e8fa694 u0 com.test.thalitest/.MainActivity t6}
,09-13 16:11:04.294   341   358 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 16:11:04.299  1037  1053 W ActivityManager: Spurious death for ProcessRecord{d208920 6736:com.test.thalitest/u0a118}, curProc for 6736: null
09-13 16:11:04.300  1037  1120 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 16:11:04.303  1037  1120 I ActivityManager:   Force finishing activity ActivityRecord{1e8fa694 u0 com.test.thalitest/.MainActivity t6 f}
09-13 16:11:04.303  1037  1120 W ActivityManager: Duplicate finish request for ActivityRecord{1e8fa694 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 16:11:04.332  2097  2097 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 16:11:04.334  1969  3999 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,09-13 16:11:04.335  1969  3999 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3da667cc co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 16:11:04.336  2097  2097 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 16:11:04.344  1969  1986 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,09-13 16:11:04.345  1969  1986 D SplitWindowPolicy: topRunningActivity=ActivityInfo{7428a15 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 16:11:04.346  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,09-13 16:11:04.347  2097  2200 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
09-13 16:11:04.355  1931  1931 D ActionManagerService: notifyUserLog: 1000003
09-13 16:11:04.355  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 16:11:04.356  3839  4510 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 16:11:04.360  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 16:11:04.371  4522  4522 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 16:11:04.372  4522  4522 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 16:11:04.372  4522  4522 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 16:11:04.372  4522  4522 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 16:11:04.372  4522  4522 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:11:04.372  4522  4522 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:11:04.372  2041  2041 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 16:11:04.372  4522  4522 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 16:11:04.372  4522  4522 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 16:11:04.372  4522  4522 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:11:04.372  4522  4522 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:11:04.372  4522  4522 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 16:11:04.373  4522  4522 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 16:11:04.373  3839  3839 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-13 16:11:04.374  3900  3900 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 16:11:04.374  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 16:11:04.377  1037  1450 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:11:04.385  2478  2619 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 16:11:04.429  1037  1993 V SIM_STK : Menu title from STK is T-Mobile
,09-13 16:11:04.433  4620  4620 I art     : Explicit concurrent mark sweep GC freed 8188(469KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 677us total 122.982ms
09-13 16:11:04.437  6466  6466 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 16:11:04.437  2097  2097 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 16:11:04.450  1037  1037 D administrator: Handling package changes for user 0
,09-13 16:11:04.459  1605  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 16:11:04.459  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.460  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-13 16:11:04.461  2097  2097 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 16:11:04.464  2097  2097 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-13 16:11:04.478  1605  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,09-13 16:11:04.478  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.478  1842  1842 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 16:11:04.487  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 16:11:04.487  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:11:04.487  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 16:11:04.491  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 16:11:04.495  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:11:04.495  1605  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 16:11:04.499  1605  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 16:11:04.499  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.500  1897  1897 D SplitUIManager: split_name #11 / not available #0
09-13 16:11:04.501  1897  1897 D SplitUIService: removed split : 
09-13 16:11:04.504  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 16:11:04.504  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:11:04.506  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:11:04.507  1605  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-13 16:11:04.508  1605  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 16:11:04.508  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.510  1931  1931 D ActionManagerService: notifyUserLog: 1000004
09-13 16:11:04.511  3839  4510 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 16:11:04.511  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 16:11:04.514  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:11:04.514  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 16:11:04.514  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 16:11:04.514  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 16:11:04.516  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:11:04.516  1605  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 16:11:04.520  3839  4505 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-13 16:11:04.536  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-13 16:11:04.536  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 16:11:04.538  1605  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 16:11:04.538  1605  1653 D KeyguardModel: createShortcutInfo...
,09-13 16:11:04.541  1037  1054 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:11:04.541  1037  1054 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:11:04.544  1897  1897 D SplitUIManager: split_name #11 / not available #0
09-13 16:11:04.544  1897  1897 I SplitUIService: split app #11
09-13 16:11:04.548  1037  1094 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 16:11:04.558  2276  2276 I ConfigService: onCreate
09-13 16:11:04.558  2276  2276 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 16:11:04.561  1605  1605 D KeyguardModel: handleShortcutListChanged...
09-13 16:11:04.561  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , expire_time: 0
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , display: false
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , animation: false }
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , expire_time: 0
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , display: false
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , animation: false }
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , expire_time: 0
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , display: false
09-13 16:11:04.561  2097  2097 I GBoardWebViewUtils: , animation: false }
,09-13 16:11:04.566  1842  1842 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 16:11:04.578  1605  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 16:11:04.578  1605  1653 D KeyguardModel: createShortcutInfo...
,09-13 16:11:04.583  1605  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 16:11:04.583  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.584  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:11:04.584  1605  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 16:11:04.585  1605  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 16:11:04.585  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.586  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:11:04.586  1605  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 16:11:04.586  2097  7978 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 16:11:04.589  1037  2016 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:11:04.594  1037  1053 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 16:11:04.594  2276  2276 I ConfigService: onBind returning update interface
09-13 16:11:04.594  1605  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 16:11:04.594  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:11:04.595  3900  3900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 16:11:04.596  2276  2276 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 16:11:04.596  2276  2276 I ConfigService: onBind returning config service
,09-13 16:11:04.598  2276  2276 I ConfigService: onDestroy
09-13 16:11:04.600  1842  7980 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 16:11:04.600  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:11:04.600  1605  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 16:11:04.604  1605  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 16:11:04.604  1605  1653 D KeyguardModel: createShortcutInfo...
09-13 16:11:04.606  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-13 16:11:04.624  1605  1605 D KeyguardModel: handleShortcutListChanged...
09-13 16:11:04.624  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-13 16:11:04.656  5957  7985 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-13 16:11:04.663  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 16:11:04.663  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:11:04.663  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:11:04.665  1037  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-13 16:11:04.681  1842  7987 I PeopleContactsSync: CP2 sync disabled
09-13 16:11:04.684  1842  4793 I Icing   : doRemovePackageData com.test.thalitest
,09-13 16:11:04.708  2276  2367 I art     : Explicit concurrent mark sweep GC freed 9299(575KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.129ms total 37.188ms
,09-13 16:11:04.719  1842  7986 W GmsApplication: Using Auth Proxy for data requests.
09-13 16:11:04.726  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-13 16:11:04.728  1842  7986 W GmsApplication: Using Auth Proxy for data requests.
09-13 16:11:04.731  2097  2097 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 16:11:04.738  7102  7102 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-13 16:11:04.753  7144  7144 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 16:11:04.756  1037  1120 I art     : Explicit concurrent mark sweep GC freed 25268(1772KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.092ms total 424.662ms
09-13 16:11:04.759  2221  7990 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 16:11:04.776  2041  2041 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 16:11:04.776  2041  2041 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,09-13 16:11:04.778  2041  2041 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-13 16:11:04.781  6466  6466 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 16:11:04.827  1037  1053 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7993 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 16:11:04.829  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-13 16:11:04.831  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.833  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 16:11:04.834  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 16:11:04.835  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 16:11:04.836  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 16:11:04.839  7943  7943 D AndroidRuntime: Shutting down VM
,09-13 16:11:04.862  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 16:11:04.862  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.868  2097  2298 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 16:11:04.868  2097  2298 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-13 16:11:04.872  1037  1120 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8011 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 16:11:04.873  1037  1094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:11:04.874  1037  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{217c28cf u0 com.lge.launcher2/.Launcher t5} time:217966
09-13 16:11:04.879  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 16:11:04.879  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 16:11:04.879  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.884  1037  1094 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 16:11:04.887  2097  2097 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-13 16:11:04.889  2599  2599 D [Concierge]Service: onStartCommand(). Type : 8
09-13 16:11:04.889  2599  2599 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 16:11:04.890  2599  2599 D [Concierge]Service: Update widget ID : 11
09-13 16:11:04.891  2097  2097 D [Concierge]WidgetView: change position of spinner
09-13 16:11:04.892  2097  2097 I [Concierge]WidgetView: initWebView(). Time : 1473775864892
09-13 16:11:04.892  2599  2599 D [Concierge]Service: onStartCommand(). Type : 0
09-13 16:11:04.911  2097  2097 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 284312951
09-13 16:11:04.912  2097  2097 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 16:11:04.912  2097  2097 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-13 16:11:04.915  2097  2097 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@397d47b8
09-13 16:11:04.915  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 16:11:04.917  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 16:11:04.917  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.919  1037  1720 I ActivityManager: Killing 6933:com.lge.formmanager/u0a26 (adj 15): empty #17
09-13 16:11:04.922  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 16:11:04.922  2097  2097 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 16:11:04.922  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 16:11:04.923  2097  2097 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 16:11:04.958  1037  1053 W libprocessgroup: failed to open /acct/uid_10026/pid_6933/cgroup.procs: No such file or directory
09-13 16:11:04.958  2097  2097 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473775675632, New one : 1473775864892
09-13 16:11:04.959  2097  2097 D [Concierge]WidgetView: Unregister all receivers
,09-13 16:11:04.959  2097  2097 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 16:11:04.960  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.962  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 16:11:04.962  7993  7993 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 16:11:04.962  7993  7993 W LG Account v2.2: No ProfileInfo entries
09-13 16:11:04.963  7993  7993 I LG Account v2.2: isEnabled: false
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Country: EU
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Operator: OPEN
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Ranking support: false
09-13 16:11:04.963  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Comfort support: false
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Accessory: true
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Health device: true
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Extra Pedometer: false
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Blood glucose device: false
09-13 16:11:04.963  7993  7993 I Feature : [Lifetracker]Device Number: 3
09-13 16:11:04.963  7993  7993 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-13 16:11:04.964  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 16:11:04.965  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 16:11:04.966  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-13 16:11:04.966  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.966  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:04.996  1037  1054 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8032 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 16:11:04.999  1037  1054 I ActivityManager: Killing 7201:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-13 16:11:05.008   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 14.332ms
09-13 16:11:05.020   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.673ms
,09-13 16:11:05.021  2097  2097 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 16:11:05.032   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 222us total 11.250ms
,09-13 16:11:05.039  2097  2097 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-13 16:11:05.039  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 16:11:05.040  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:11:05.063  2097  2097 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@149fb340 time:218155
,09-13 16:11:05.069  1037  1595 W libprocessgroup: failed to open /acct/uid_10046/pid_7201/cgroup.procs: No such file or directory
09-13 16:11:05.086  8032  8032 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:11:05.086  8032  8032 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 16:11:05.087  8032  8032 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:11:05.087  8032  8032 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 16:11:05.088  8032  8032 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 16:11:05.088  8032  8032 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 16:11:05.168  8032  8032 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-13 16:11:05.174  8032  8032 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-13 16:11:05.174  8032  8032 D HideNavigationAppsReceiver: replacing : false
09-13 16:11:05.177  8032  8032 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-13 16:11:05.179  8032  8032 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-13 16:11:05.179  8032  8032 D ButtonCombinationReceiver: replacing : false

```
