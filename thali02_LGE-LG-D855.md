#### Test 82914073f44248e_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-06 18:58:00.103  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,09-06 18:58:02.236  6850  6850 D AndroidRuntime: 
09-06 18:58:02.236  6850  6850 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 18:58:02.242  6850  6850 D AndroidRuntime: CheckJNI is OFF
09-06 18:58:02.363  6850  6850 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 18:58:02.368  1034  1952 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 18:58:02.377  1941  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-06 18:58:02.381  1034  1952 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-06 18:58:02.382  1034  1952 D ActivityManager: setTaskToReturnTo : TaskRecord{15ed4824 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 18:58:02.382  1034  1952 D ActivityManager: setTaskToReturnTo : TaskRecord{15ed4824 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 18:58:02.383  1034  1952 D WindowStateEx: AppWindowTokenEx init.. 
09-06 18:58:02.384   342   353 E GBMv2   : DFP En is all cleared set to be enabled
09-06 18:58:02.410  1034  1952 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6865 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 18:58:02.417  6850  6850 D AndroidRuntime: Shutting down VM
09-06 18:58:02.465  1941  3970 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-06 18:58:02.466  1941  3970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33f3e9e7 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 18:58:02.467  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-06 18:58:02.467  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3fc92994 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 18:58:02.514  6865  6865 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-06 18:58:02.576  6865  6865 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-06 18:58:02.583  6865  6865 I LibraryLoader: Loading: webviewchromium
09-06 18:58:02.585  6865  6865 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2734-2737)
09-06 18:58:02.585  6865  6865 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:58:02.600  6865  6865 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ee96b2d}
09-06 18:58:02.601  6865  6865 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:58:02.601  6865  6865 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 18:58:02.610  6865  6865 I BrowserStartupController: Initializing chromium process, renderers=0
09-06 18:58:02.611  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 18:58:02.631  6865  6865 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 18:58:02.631  6865  6865 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-06 18:58:02.632  6865  6865 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-06 18:58:02.659   316  2165 V AudioPolicyService: registerClient() client 0xb57ead40, uid 10118
,09-06 18:58:02.664  6865  6865 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 18:58:02.664  6865  6865 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 18:58:02.664  6865  6865 I Adreno-EGL: Build Date: 12/12/14 금
09-06 18:58:02.664  6865  6865 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 18:58:02.664  6865  6865 I Adreno-EGL: Remote Branch: 
09-06 18:58:02.664  6865  6865 I Adreno-EGL: Local Patches: 
09-06 18:58:02.664  6865  6865 I Adreno-EGL: Reconstruct Branch: 
09-06 18:58:02.669  1034  1096 D BluetoothManagerService: Message: 20
09-06 18:58:02.669  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@245e838e:true
09-06 18:58:02.770  6865  6910 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-06 18:58:02.773  6865  6865 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-06 18:58:02.794  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 18:58:02.799  6865  6865 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 18:58:02.803  6865  6865 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-06 18:58:02.807  6865  6865 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-06 18:58:02.807  6865  6865 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-06 18:58:02.823  6865  6865 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-06 18:58:02.831  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 18:58:02.831  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 18:58:02.879  6865  6923 D OpenGLRenderer: Render dirty regions requested: true
09-06 18:58:02.880  6865  6923 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 18:58:02.899  6865  6923 D OpenGLRenderer: Enabling debug mode 0
,09-06 18:58:02.909  6865  6865 D Atlas   : Validating map...
09-06 18:58:02.918  1034  1576 D SplitWindow: check instance of lgWin Window{2f0df6d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 18:58:02.939  6865  6921 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:02.939  6865  6921 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:03.053  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +588ms (total +668ms)
09-06 18:58:03.054  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11dadf8d u0 com.test.thalitest/.MainActivity t6} time:163206
,09-06 18:58:03.061  6865  6865 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9a6fe0 time:163213
09-06 18:58:03.176  6865  6865 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-06 18:58:03.176  6865  6865 I chromium: 
,09-06 18:58:03.206  6865  6865 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 18:58:03.299  6865  6921 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-06 18:58:03.299  6865  6921 I chromium: 
,09-06 18:58:03.441  6865  6940 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,09-06 18:58:03.456  6865  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 18:58:03.456  6865  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 18:58:03.456  6865  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 18:58:03.456  6865  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 18:58:03.456  6865  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 18:58:03.457  6865  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d62ea4 added. We now have 1 listener(s)
09-06 18:58:03.464  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:03.466  6865  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-06 18:58:03.468  6865  6940 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 18:58:03.470  6865  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:03.470  6865  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 18:58:03.479  6865  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c791d3 added. We now have 1 listener(s)
09-06 18:58:03.481  6865  6940 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:58:03.485  1034  1405 D WifiService: New client listening to asynchronous messages
09-06 18:58:03.490  6865  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:58:03.490  6865  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 18:58:03.492  6865  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 18:58:03.492  6865  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 18:58:03.492  6865  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 18:58:03.496  6865  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:58:03.501  1034  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:03.506  6865  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-06 18:58:03.519  6865  6940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:03.519  6865  6940 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:03.519  6865  6940 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 18:58:03.520  6865  6940 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:03.521  6865  6940 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 18:58:03.522  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:03.524  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:03.577  6865  6865 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 18:58:03.773   342   357 E GBMv2   : DFP En is all cleared set to be enabled
09-06 18:58:03.773   342   357 E GBMv2   : Set value is all cleared set the max
09-06 18:58:03.773   342   357 I GBMv2   : DFP Enabled. Ignore VFP set
,09-06 18:58:04.414  6865  6943 W jxcore-log: Initializing JXcore engine
09-06 18:58:04.414  6865  6943 W jxcore-log: JXcore engine is ready
,09-06 18:58:04.442  6943  6943 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8455]" dev="sockfs" ino=8455 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 18:58:04.442  6943  6943 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-06 18:58:04.442  6943  6943 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10075]" dev="sockfs" ino=10075 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 18:58:04.442  6943  6943 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,09-06 18:58:04.442  6943  6943 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33086]" dev="sockfs" ino=33086 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-06 18:58:04.466  6865  6943 W jxcore-log: Starting JXcore engine
09-06 18:58:04.566  6865  6943 W jxcore-log: Platform android
09-06 18:58:04.566  6865  6943 W jxcore-log: 
09-06 18:58:04.566  6865  6943 W jxcore-log: Process ARCH arm
09-06 18:58:04.566  6865  6943 W jxcore-log: 
,09-06 18:58:04.862  6865  6943 I jxcore-log: JXcore Cordova bridge is ready!
09-06 18:58:04.862  6865  6943 I jxcore-log: 
09-06 18:58:04.862  6865  6943 W jxcore-log: JXcore engine is started
,09-06 18:58:04.875  6865  6940 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 18:58:04.879  6865  6865 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 18:58:14.778  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 18:58:14.778  6865  6943 I jxcore-log: 
,09-06 18:58:14.781  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 18:58:14.781  6865  6943 I jxcore-log: 
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:14.784  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:14.786  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:14.788  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 18:58:14.788  6865  6943 I jxcore-log: 
09-06 18:58:14.790  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 18:58:14.790  6865  6943 I jxcore-log: 
09-06 18:58:15.296  6865  6943 D executeNativeTests: Running unit tests
,09-06 18:58:15.377  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:15.377  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 added. We now have 2 listener(s)
09-06 18:58:15.377  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 18:58:15.382  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 18:58:15.382  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:15.382  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:15.382  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:15.382  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d added. We now have 2 listener(s)
09-06 18:58:15.382  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:15.383  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:58:15.385  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:15.388  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.389  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.389  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:15.390  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:15.393  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.396  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:58:15.398  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:58:15.398  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:58:15.400  6865  6943 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 18:58:15.401  6865  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 18:58:15.401  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:58:15.401  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:58:15.401  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:58:15.402  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.402  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.402  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.402  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.403  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.403  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:15.403  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:15.403  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 removed from the list
09-06 18:58:15.403  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.403  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d removed from the list
09-06 18:58:15.403  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.403  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:58:15.405  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.405  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.406  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.406  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.406  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.406  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.407  6865  6943 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 18:58:15.408  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.408  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.408  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.408  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.408  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.408  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.408  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.408  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.408  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.408  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.408  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.408  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.408  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.408  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.410  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.410  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.411  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.411  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.427  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 18:58:15.427  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 18:58:15.427  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 18:58:15.428  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 18:58:15.429  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 18:58:15.429  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 18:58:15.429  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 18:58:15.430  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 18:58:15.430  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 18:58:15.430  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 18:58:15.430  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 18:58:15.430  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 18:58:15.430  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 18:58:15.431  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 18:58:15.431  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 18:58:15.431  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 18:58:15.431  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 18:58:15.431  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 18:58:15.431  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 18:58:15.432  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 18:58:15.432  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-06 18:58:15.432  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 18:58:15.432  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 18:58:15.432  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 18:58:15.432  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.432  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.432  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.433  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.433  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.433  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.433  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.434  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.434  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.434  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.434  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.434  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.434  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.434  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.435  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.435  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.435  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.435  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.438  6865  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:58:15.439  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:15.443  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.444  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.444  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:15.446  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.447  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:15.447  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.447  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:58:15.448  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:58:15.448  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.448  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:58:15.451  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:58:15.453  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:15.460  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:58:15.466  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 18:58:15.469  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 18:58:15.471  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:58:15.471  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:15.473  6865  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 18:58:15.474  6865  6943 I io.jxcore.node.ConnectionHelper: start: OK
09-06 18:58:15.478  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:58:15.478  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.478  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.478  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.478  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.478  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:15.478  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.478  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.478  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.478  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.478  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.479  6865  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:58:15.481  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:15.484  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.486  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.486  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:15.486  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:15.486  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:58:15.486  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:58:15.486  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.486  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:58:15.488  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.491  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18,:58:15.491  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.492  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:58:15.493  6865  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 18:58:15.493  6865  6943 I io.jxcore.node.ConnectionHelper: start: OK
09-06 18:58:15.495  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.495  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.495  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.496  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.496  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.496  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:15.496  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.496  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.496  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.496  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.496  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.496  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.497  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.497  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.498  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.500  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.500  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.500  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.500  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.501  6865  6943 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:58:15.502  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:15.505  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:58:15.506  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.507  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:15.508  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:15.508  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:58:15.508  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:58:15.508  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.509  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:58:15.509  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.511  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.513  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:58:15.514  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:15.515  6865  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 18:58:15.515  6865  6943 I io.jxcore.node.ConnectionHelper: start: OK
09-06 18:58:15.515  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.515  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.515  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.516  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.516  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.516  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.516  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.516  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.516  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:15.517  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.517  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.517  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.517  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.517  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.517  6865  6943 W org.thalipro,ject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:58:15.517  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.518  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.518  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.519  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.519  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.519  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.519  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.520  6865  6943 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 18:58:15.521  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.521  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.521  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.522  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.522  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.522  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.522  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.522  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.522  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.522  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.522  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.522  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.522  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.522  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.523  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.523  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.523  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.523  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.523  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.523  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.525  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 18:58:15.525  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing, connections
09-06 18:58:15.525  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.525  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.525  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.526  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.526  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.526  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.526  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.526  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.526  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.526  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.526  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.526  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.526  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.527  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.527  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.527  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.528  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.528  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.528  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.529  6865  6943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 18:58:15.529  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.529  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:58:15.529  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:58:15.530  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.530  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.530  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.530  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.530  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.530  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.530  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.530  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.530  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.531  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.531  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.532  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.532  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.533  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.533  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.533  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.533  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.534  6865  6943 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 18:58:15.534  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.534  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.534  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.535  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.535  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.535  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.535  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.535  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.535  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.535  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.535  6865  6,943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.535  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.535  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.535  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.536  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.536  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.537  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.537  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.537  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.537  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.538  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:58:15.538  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:58:15.538  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:58:15.538  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:58:15.538  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:58:15.538  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:58:15.538  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.539  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.539  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.539  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.539  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.539  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.539  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.539  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.539  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.539  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.539  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.539  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.539  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.539  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.540  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.540  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.540  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.540  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.540  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.540  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.542  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:58:15.542  6865  6943 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 18:58:15.542  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 18:58:15.551  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:58:15.551  6865  6943 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 18:58:15.552  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 18:58:15.553  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 18:58:15.554  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 18:58:15.554  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 18:58:15.554  6865  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:58:15.555  6865  6943 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 18:58:15.555  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:58:15.555  6865  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:58:15.555  6865  6943 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 18:58:15.555  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:58:15.555  6865  6943 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:58:15.555  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 18:58:15.557  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 18:58:15.559  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 18:58:15.559  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 18:58:15.560  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 18:58:15.560  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 18:58:15.560  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 18:58:15.560  6865  6943 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:58:15.560  6865  6943 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 18:58:15.561  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.561  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.561  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.562  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.562  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.562  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.562  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 18:58:15.563  6865  6953 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 846)
09-06 18:58:15.568  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.568  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.568  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.568  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.568  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.568  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.568  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.568  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.569  6865  6954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 846
09-06 18:58:15.569  6865  6954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 846)
09-06 18:58:15.569  6865  6954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 846)
09-06 18:58:15.569  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.569  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:58:15.570  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.570  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.570  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.570  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.572  6865  6943 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 18:58:15.572  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.572  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.572  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.573  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.573  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.573  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.573  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.573  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.573  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.573  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.573  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.573  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.573  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.573  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.574  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.574  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.575  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.575  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.575  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.575  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.576  6865  6943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 18:58:15.577  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.577  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.577  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.577  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.577  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.577  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.577  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.577  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.577  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.577  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.577  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.577  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.577  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.577  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.579  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.579  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.579  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.579  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.579  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.580  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.580  6865  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 18:58:15.580  6865  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 18:58:15.581  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:58:15.588  6865  6943 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 18:58:15.588  6865  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 18:58:15.588  6865  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 18:58:15.588  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:58:15.588  6865  6943 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 18:58:15.589  6865  6943 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 18:58:15.589  6865  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 18:58:15.589  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:58:15.589  6865  6943 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 18:58:15.589  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.589  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.589  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.598  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.598  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.598  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.599  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.599  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.599  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.599  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.599  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.599  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.599  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.599  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.600  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.600  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.601  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.601  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.601  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.601  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.602  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.602  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.602  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.602  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.602  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.602  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.602  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.602  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.602  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.603  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.603  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.603  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.603  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.603  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.603  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.603  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.603  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.603  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.606  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.606  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.606  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.607  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.607  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.607  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
,09-06 18:58:15.607  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.607  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.607  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.607  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.607  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.609  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.609  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.609  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.609  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.609  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.609  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.612  6865  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 18:58:15.612  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.615  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 18:58:15.615  6865  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 18:58:15.616  6865  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 18:58:15.617  6865  6865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 18:58:15.617  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 18:58:15.617  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:58:15.619  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.619  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 18:58:15.619  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 18:58:15.619  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 18:58:15.619  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.619  6865  6943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 18:58:15.619  6865  6865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 18:58:15.619  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.619  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.620  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:58:15.620  6865  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:58:15.620  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:58:15.621  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer,: stopScannerAndAdvertiser
09-06 18:58:15.621  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:15.622  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:15.622  6865  6959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:15.622  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:15.622  6865  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:58:15.622  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.622  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:58:15.624  3877  4069 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-06 18:58:15.625  6865  6959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 18:58:15.625  6865  6959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 18:58:15.625  6865  6959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 18:58:15.627  6865  6943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:58:15.629  6865  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:58:15.629  6865  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:58:15.629  6865  6865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 18:58:15.630  6865  6865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:58:15.630  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.630  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.630  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.630  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.630  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.631  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.631  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.631  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.631  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.631  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.631  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.631  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.631  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.631  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.631  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.632  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.632  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.632  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.632  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSet,tings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.633  6865  6943 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 18:58:15.634  6865  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 18:58:15.634  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 18:58:15.638  6865  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:58:15.638  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.638  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.638  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.639  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.639  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.639  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.639  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.639  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.639  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.639  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.639  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.639  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.639  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.639  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.641  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.641  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.641  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.641  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.642  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:15.643  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:15.644  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:15.644  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.644  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.644  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.645  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.645  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.645  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:58:15.645  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.645  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.645  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.645  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.645  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.645  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.645  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.645  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.646  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.646  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:15.646  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.646  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.647  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:15.648  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:15.648  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:15.649  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:15.649  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.649  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.649  6865  6943 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfa1474 not in the list
09-06 18:58:15.649  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.649  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.649  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:15.649  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.649  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.649  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:15.649  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:15.650  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:15.650  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscove,ry
09-06 18:58:15.650  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:15.650  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6e3d9d not in the list
09-06 18:58:15.652  6865  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 18:58:15.652  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:58:15.652  6865  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 18:58:15.652  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:58:15.652  6865  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 18:58:15.653  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:58:15.655  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 18:58:15.655  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 18:58:15.656  6865  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 18:58:15.656  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 18:58:15.656  6865  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 18:58:15.656  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 18:58:15.656  6865  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 18:58:15.656  6865  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 18:58:15.660  6865  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-06 18:58:15.660  6865  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 18:58:15.661  6865  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 18:58:15.661  6865  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 18:58:15.661  6865  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 18:58:15.661  6865  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 18:58:15.663  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:15.663  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee2016a added. We now have 2 listener(s)
09-06 18:58:15.663  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:15.673  6865  6943 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 18:58:15.674  1034  2033 D WifiServiceImplEx: setWifiEnabled: true pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 18:58:15.674  1034  2033 D WifiService: setWifiEnabled: true pid=6865, uid=10118
09-06 18:58:15.674  1034  2033 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 18:58:15.676  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:15.676  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34a5165b added. We now have 3 listener(s)
09-06 18:58:15.676  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:15.680  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:15.680  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c7c6ef8 added. We now have 4 listener(s)
09-06 18:58:15.680  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:15.683  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:15.683  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@169affd1 added. We now have 5 listener(s)
09-06 18:58:15.683  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:15.683  6865  6953 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-06 18:58:15.684  6865  6953 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 846)
,09-06 18:58:15.687  1034  1952 D WifiServiceImplEx: setWifiEnabled: false pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 18:58:15.687  1034  1952 D WifiService: setWifiEnabled: false pid=6865, uid=10118
09-06 18:58:15.687  1034  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:58:15.698  1034  1393 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:15.698  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:15.698  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:15.698  1034  1887 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@10fb499b mBinding = false
09-06 18:58:15.698  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:15.699  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:15.699  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:15.699  1034  1393 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:15.700  1034  1393 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:15.700  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:15.700  1034  1393 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 18:58:15.701  1034  1393 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:58:15.701  1034  1393 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-06 18:58:15.702  1034  1393 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 18:58:15.702  1034  1393 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 18:58:15.707  1034  1393 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 18:58:15.707  1034  1096 D BluetoothManagerService: Message: 2
09-06 18:58:15.707  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 18:58:15.707  2716  2716 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 18:58:15.708  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.708  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.709  1034  1096 D BluetoothManagerService: Sending off request.
09-06 18:58:15.709  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:15.709  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 18:58:15.709  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:15.709  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:15.710  3877  3903 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 18:58:15.710  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:15.710  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:15.711  3877  3983 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 18:58:15.711  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:15.711  3877  3983 D BluetoothAdapterProperties: Setting state to 13
,09-06 18:58:15.711  3877  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 18:58:15.711  1034  2863 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.711  3877  3983 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 18:58:15.711  3877  3983 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 18:58:15.713   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:58:15.716  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:15.716  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 18:58:15.716  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 18:58:15.717  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:15.717  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.718  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.718  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.718  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:15.719  3877  3988 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:58:15.719  3877  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 18:58:15.720  3877  4279 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:15.720  3877  3983 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 18:58:15.720  3877  4262 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:15.721  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 18:58:15.721  3877  4263 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:15.722  3877  4070 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 18:58:15.722  3877  4204 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: 	at android.bluetooth.Blueto,othSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 18:58:15.725  3877  4203 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 18:58:15.730  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 18:58:15.730  3877  4070 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 18:58:15.734  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.737  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:15.740  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:15.740  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:58:15.741  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.741  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:15.742  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:15.747  1034  2033 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-06 18:58:15.747  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.747  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.747  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 18:58:15.747  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.747  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 18:58:15.751   312  6971 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 18:58:15.751  1034  1094 D DSQN    : Dns fail occured do internet check.
09-06 18:58:15.752  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-06 18:58:15.752  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-06 18:58:15.752  1034  1034 D DSQN    : try Internet connection check
09-06 18:58:15.758  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 18:58:15.760  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-06 18:58:15.779  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6976 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 18:58:15.780  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.781  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.781  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.781  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 18:58:15.781  3877  3877 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:15.781  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.781  3877  3877 D BluetoothMapService: STATE_TURNING_OFF
09-06 18:58:15.782  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.782  3877  3877 V BtOppService: Receiver DISABLED_ACTION 
09-06 18:58:15.782  3877  3877 V BluetoothMapService: Handler(): got msg=4
09-06 18:58:15.782  3877  3877 D BluetoothMapService: MAP Service closeService in
09-06 18:58:15.782  3877  3877 D BluetoothMapMasInstance: MAP Service shutdown
09-06 18:58:15.782  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 18:58:15.782  1034  1393 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 18:58:15.782  3877  3877 V BluetoothMapService: MAP Service closeService out
09-06 18:58:15.782  3877  3877 I BtOppRfcommListener: stopping Accept Thread
09-06 18:58:15.782  3877  3877 V BtOppRfcommListener: close mBtServerSocket
09-06 18:58:15.782  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.782  3877  3877 V BtOppRfcommListener: waiting for thread to terminate
09-06 18:58:15.783  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:15.783  3877  4262 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 18:58:15.783  3877  3877 V BtOppRfcommListener: done waiting for thread to terminate
09-06 18:58:15.784  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:15.784  1034  1391 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.784  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.785  1034  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@346e6f93
09-06 18:58:15.785  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.785  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:15.787  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:15.787  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.789  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.789  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:15.791  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth ,is disabled - will return stored value
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:15.791  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.792  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.792  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:58:15.820  1034  1414 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 18:58:15.820  1034  1414 D DSQN    : disableDataServiceNotify
09-06 18:58:15.820  1034  1414 D DSQN    : stop dsqn bin
09-06 18:58:15.821   312  6996 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-06 18:58:15.822  1034  6973 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
09-06 18:58:15.822  1034  6972 D DSQN    : ThreadInternetCheck internet check NOK 
09-06 18:58:15.822  1034  6972 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
09-06 18:58:15.822  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 18:58:15.826  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6995 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 18:58:15.827  1034  1391 D LGWifiP2pService: P2pDisablingState
09-06 18:58:15.827  1034  1391 D LGWifiP2pService: P2pDisablingState{ when=-43ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.827  1034  1391 D LGWifiP2pService: p2p socket connection lost
09-06 18:58:15.827  3877  3877 V BtOppService: onDestroy
09-06 18:58:15.827  1034  1391 D LGWifiP2pService: P2pDisabledState
09-06 18:58:15.828  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 18:58:15.828  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 18:58:15.828  2716  2716 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 18:58:15.828  1034  1414 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 18:58:15.828  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:15.828  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:15.829  1034  1414 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:15.829  1034  1414 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 18:58:15.829  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 18:58:15.829  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:15.830  1034  1414 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 18:58:15.830  1034  1414 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 18:58:15.830  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.830  1034  1391 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.830  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:58:15.830  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:15.830   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:58:15.830  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.831  1034  2862 D NetworkMonitor Net,workAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.831  1034  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 18:58:15.832  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-06 18:58:15.833  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-06 18:58:15.833  3877  3877 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 18:58:15.836  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.836  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.837  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:15.837  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-06 18:58:15.837  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 18:58:15.837  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.837  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.837  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:15.837  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 18:58:15.837  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-06 18:58:15.838  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.838  1034  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.838   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 262us total 12.283ms
09-06 18:58:15.839  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 18:58:15.839  1941  1941 D WfdsService: WifiP2pState is changed : false
09-06 18:58:15.839  1034  1414 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:15.840  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:58:15.840  1034  1393 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 18:58:15.840  1034  1414 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:15.840  1034  1414 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:15.840  1034  1414 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:15.840  1034  1414 D NetworkManagementService: Removing idletimer
09-06 18:58:15.840  1034  1393 D WifiNative-p2p0: TERMINATE: returned true
09-06 18:58:15.840  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:15.840  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:15.840  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:15.841  1034  1414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.841  1034  1393 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:15.841  1034  1393 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:15.841  1941  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 18:58:15.841  1941  2345 D WfdsService: Set the WFDS Monitor: false
09-06 18:58,:15.841  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:15.842  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 18:58:15.842  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 18:58:15.842  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-06 18:58:15.842  1941  2345 D WfdsService: STATE : WfdsDisabledState - enter
09-06 18:58:15.842  1941  2766 D CtrlSupplicant: Received on exit socket, terminate
09-06 18:58:15.842  1941  2766 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 18:58:15.842  1941  2766 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 18:58:15.842  1941  2766 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 18:58:15.843  1941  2346 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 18:58:15.843  1941  2345 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 18:58:15.843  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 18:58:15.844  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-06 18:58:15.846  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:15.846  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:15.847  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.849   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 10.514ms
09-06 18:58:15.855  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 18:58:15.857  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:15.857  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:58:15.858  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.858  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:15.860   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 193us total 10.314ms
09-06 18:58:15.861  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:15.861  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:15.862  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:15.862  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:15.870  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:15.870  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 18:58:15.873  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.883  1034  1905 I art     : Explicit concurrent mark sweep GC freed 36433(1744KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.470ms total 159.710ms
,09-06 18:58:15.897  1034  1034 D WifiHS20: hidePasspointNotification off =false
,09-06 18:58:15.897  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.897  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:15.897  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:15.897  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 18:58:15.898  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 18:58:15.898  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:15.898  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 18:58:15.898  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 18:58:15.898  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 18:58:15.898  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 18:58:15.898  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 18:58:15.898  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 18:58:15.898  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 18:58:15.900  6995  6995 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:58:15.900  6995  6995 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-06 18:58:15.900  6995  6995 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:15.901  6995  6995 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-06 18:58:15.901  1034  1414 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 18:58:15.901  6995  6995 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 18:58:15.902  6995  6995 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 18:58:15.916  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:15.917  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.917  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.918  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 18:58:15.918  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:15.918  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:15.929  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:15.930  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.930  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.933  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:15.944  1034  2863 D DhcpStateMachine: StoppedState
09-06 18:58:15.944  1034  2863 D DhcpStateMachine: StoppedState{ when=-114ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:15.944  1034  1393 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,09-06 18:58:15.944  1034  1393 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 18:58:15.948  6976  6976 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 18:58:15.948  6976  6976 W LG Account v2.2: No ProfileInfo entries
09-06 18:58:15.948  6976  6976 I LG Account v2.2: isEnabled: false
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Country: EU
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Operator: OPEN
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Ranking support: false
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Comfort support: false
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Accessory: true
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Health device: true
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Extra Pedometer: false
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Blood glucose device: false
09-06 18:58:15.949  6976  6976 I Feature : [Lifetracker]Device Number: 3
09-06 18:58:15.954  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:15.968  2716  2716 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 18:58:15.969  2716  2716 I wpa_supplicant: monitor socket send errors count : 1
09-06 18:58:15.969  2716  2716 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,09-06 18:58:15.969  1034  2764 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 18:58:15.969  1034  2764 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 18:58:15.986  1034  1576 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7016 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 18:58:15.988  1034  1576 I ActivityManager: Killing 6339:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-06 18:58:16.001  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 18:58:16.008  2716  2716 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:58:16.008  1034  2764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 18:58:16.008  1034  2764 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:58:16.008  1034  2764 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:58:16.008  1034  2764 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 18:58:16.009  1034  1096 D Tethering: InitialState.processMessage what=4
09-06 18:58:16.009  1034  1393 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=176147
09-06 18:58:16.009  1034  1393 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=176148
09-06 18:58:16.010  1034  2764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:16.010  1034  2764 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:16.010  2716  2716 W wpa_supplicant: USIM:  scard_deinit function
09-06 18:58:16.011  1034  1393 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=176149  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 18:58:16.011  1034  1393 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=176149  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 18:58:16.028  1034  1787 W libprocessgroup: failed to open /acct/uid_10014/pid_6339/cgroup.procs: No such file or directory
,09-06 18:58:16.030  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 18:58:16.031  2716  2716 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 18:58:16.031  1034  2764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 18:58:16.031  1034  2764 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 18:58:16.031  1034  2764 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 18:58:16.032  1034  1393 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-06 18:58:16.037  3877  3877 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:16.037  3877  3877 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:16.037  3877  3877 V BluetoothPbapReceiver: ***********state = 13
09-06 18:58:16.037  1034  1096 D BluetoothManagerService: Message: 20
09-06 18:58:16.037  3877  3877 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 18:58:16.038  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@228a1402:true
09-06 18:58:16.038  3877  3877 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:16.038  3877  3877 V BluetoothPbapService: state: 13
09-06 18:58:16.038  3877  3877 V BluetoothPbapService: Pbap Service closeService in
09-06 18:58:16.040  3877  3877 V BluetoothPbapService: successfully stopped pbap service
09-06 18:58:16.040  3877  3877 V BluetoothPbapService: Pbap Service closeService out
09-06 18:58:16.040  3877  3877 V BluetoothPbapService: Pbap Service onDestroy
09-06 18:58:16.040  3877  3877 V BluetoothPbapService: Pbap Service closeService in
09-06 18:58:16.040  3877  3877 V BluetoothPbapService: Pbap Service closeService out
09-06 18:58:16.040  3877  3877 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 18:58:16.041  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:58:16.054  1034  1096 D BluetoothManagerService: Message: 30
09-06 18:58:16.059  1034  1096 D BluetoothManagerService: Message: 30
,09-06 18:58:16.060  6995  6995 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 18:58:16.061  6995  6995 D BluetoothMap: Create BluetoothMap proxy object
09-06 18:58:16.062  1034  1096 D BluetoothManagerService: Message: 30
09-06 18:58:16.064  1034  1096 D BluetoothManagerService: Message: 30
09-06 18:58:16.065  6995  6995 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 18:58:16.066  6995  6995 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-06 18:58:16.077  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-06 18:58:16.079  6995  6995 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-06 18:58:16.082  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:16.082  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:16.082  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-06 18:58:16.083  1034  1940 I ActivityManager: Killing 6458:com.android.defcontainer/u0a4 (adj 15): empty #17
09-06 18:58:16.100  1034  1051 W libprocessgroup: failed to open /acct/uid_10004/pid_6458/cgroup.procs: No such file or directory
,09-06 18:58:16.107  6995  6995 D DockEventReceiver: finishStartingService: stopping service
09-06 18:58:16.116  6995  6995 D BluetoothInputDevice: Proxy object connected
09-06 18:58:16.117  6995  6995 D HidProfile: Bluetooth service connected
,09-06 18:58:16.118  6995  6995 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:58:16.118  6995  6995 D PanProfile: Bluetooth service connected
09-06 18:58:16.119  6995  6995 D BluetoothMap: Proxy object connected
09-06 18:58:16.119  6995  6995 D MapProfile: Bluetooth service connected
09-06 18:58:16.119  6995  6995 D BluetoothMap: getConnectedDevices()
09-06 18:58:16.120  6995  6995 D BluetoothMap: Bluetooth is Not enabled
09-06 18:58:16.128  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 18:58:16.130  6865  6865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 18:58:16.134  1941  1941 D WfdsService: Supplicant Connection state is changed : false
,09-06 18:58:16.134  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 18:58:16.135  1941  2345 D WfdsService: Set the WFDS Monitor: false
09-06 18:58:16.135  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-06 18:58:16.135  1034  1393 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 18:58:16.135  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:16.135  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:16.135  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:16.137  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:16.138  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 18:58:16.139  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 18:58:16.140  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 18:58:16.140  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:16.140  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:16.140  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 18:58:16.142  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:16.142  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:16.142  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:16.161  6995  6995 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:16.161  6995  6995 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:16.169  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:16.169  6995  6995 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 18:58:16.171  6995  6995 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 18:58:16.175  6995  6995 D BluetoothPermissionRequest: onReceive
09-06 18:58:16.178  6995  6995 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 18:58:16.183  1034  1940 I ActivityManager: Killing 6604:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-06 18:58:16.186  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 18:58:16.223  3877  3877 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 18:58:16.223  3877  3877 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-06 18:58:16.224  3877  3877 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 18:58:16.225  1034  1051 W libprocessgroup: failed to open /acct/uid_10008/pid_6604/cgroup.procs: No such file or directory
09-06 18:58:16.245  3877  3877 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:58:16.245  3877  3877 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 18:58:16.247  3877  3877 V BluetoothFtpService: Ftp Service onStartCommand
09-06 18:58:16.247  3877  3877 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:16.249  3877  3877 V BluetoothFtpService: Ftp Service closeService
09-06 18:58:16.250  3877  3877 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 18:58:16.316  1034  1952 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7044 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 18:58:16.318  3877  3877 V BluetoothFtpService: successfully stopped ftp service
09-06 18:58:16.319  3877  3877 V BluetoothFtpService: Ftp Service onDestroy
09-06 18:58:16.319  3877  3877 V BluetoothFtpService: Ftp Service closeService
09-06 18:58:16.327  3877  3877 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:16.327  3877  3877 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:16.328  3877  3877 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:16.328  3877  3877 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:16.328  3877  3877 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 18:58:16.328  3877  3877 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 18:58:16.330  3877  3877 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:16.331  3877  3877 V BluetoothSapService: state: 13
09-06 18:58:16.331  3877  3877 V BluetoothSapService: Stopping SAP server process
,09-06 18:58:16.334  3877  3877 V BluetoothSapService: Sap Service closeSapService in
09-06 18:58:16.335  3877  3877 V BluetoothSapService: Close listen Socket : 
09-06 18:58:16.336  3877  3877 V BluetoothSapService: Close rfcomm Socket : 
09-06 18:58:16.336  3877  3877 V BluetoothSapService: Close sapd  Socket : 
09-06 18:58:16.339  1034  1393 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:16.340  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:16.374  1034  1952 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7064 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 18:58:16.375  3877  3877 V BluetoothSapService: Sap Service closeSapService out
09-06 18:58:16.375  3877  3877 V BluetoothSapService: Sap Service onDestroy
09-06 18:58:16.375  3877  3877 V BluetoothSapService: Sap Service closeSapService in
09-06 18:58:16.375  3877  3877 V BluetoothSapService: Close listen Socket : 
09-06 18:58:16.375  3877  3877 V BluetoothSapService: Close rfcomm Socket : 
09-06 18:58:16.375  3877  3877 V BluetoothSapService: Close sapd  Socket : 
09-06 18:58:16.382  3877  3877 V BluetoothSapService: Sap Service closeSapService out
,09-06 18:58:16.415  7044  7044 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:16.431  7064  7064 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 18:58:16.445  7044  7044 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-06 18:58:16.449  1034  1051 I ActivityManager: Killing 6121:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-06 18:58:16.485  1034  1959 W libprocessgroup: failed to open /acct/uid_10011/pid_6121/cgroup.procs: No such file or directory
,09-06 18:58:16.522  7044  7044 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-06 18:58:16.523  7044  7044 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 18:58:16.523  7044  7044 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 18:58:16.524  7044  7044 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 18:58:16.524  7044  7044 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 18:58:16.526  7044  7044 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-06 18:58:16.533  7044  7044 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 18:58:16.546  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 18:58:16.552  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:16.583  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 18:58:16.588  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:16.592  7044  7044 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 18:58:16.596  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 18:58:16.596  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:16.597  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:16.602  7044  7044 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 18:58:16.603  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:16.611  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:16.624  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:16.625  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:16.628  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 18:58:16.634  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:16.644  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 18:58:16.644  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-06 18:58:16.644  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:16.650  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 18:58:16.656  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:16.667  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:16.667  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:16.670  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 18:58:16.733  1034  1988 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7084 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 18:58:16.739  3877  3988 D bt_hci_bdroid: cleanup
09-06 18:58:16.739  3877  4073 I bt_lpm  : LPM is already off!!!
09-06 18:58:16.739  3877  4190 I bt_userial_mct: exiting userial_read_thread
09-06 18:58:16.739  3877  4070 W bt-btif : ag scb idx 1 not allocated
09-06 18:58:16.739  3877  4070 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 18:58:16.739  3877  4190 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 18:58:16.739  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:16.739  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:16.740  3877  4070 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:16.740  3877  4070 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 18:58:16.740  3877  3988 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 18:58:16.740  3877  4073 I bt_vendor: hw_epilog_process
09-06 18:58:16.741  3877  3988 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 18:58:16.741  3877  3988 D bt_userial_mct: userial_close
09-06 18:58:16.741  3877  3988 E bt_userial_mct: pthread_join() FAILED result:3
09-06 18:58:16.741  3877  3988 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 18:58:16.823  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,09-06 18:58:16.836  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:16.843  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:58:16.857  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:16.858  3877  3988 D bt_hci_bdroid: set_power 0
09-06 18:58:16.858  3877  3988 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 18:58:16.858  3877  3988 I bt_vendor: bluetooth satus is on
09-06 18:58:16.858  3877  3988 I bt_vendor: bt-vendor : resetting BT status
09-06 18:58:16.858  3877  3988 I bt_vendor: Starting hciattach daemon
09-06 18:58:16.858  3877  3988 I bt_vendor: try to set false
09-06 18:58:16.860  3877  3988 I bt_vendor: Starting hciattach daemon
09-06 18:58:16.860  3877  3988 I bt_vendor: try to set false
09-06 18:58:16.860  3877  3988 I bt_vendor: cleanup
09-06 18:58:16.861  3877  4070 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 18:58:16.862  3877  3988 I GKI_LINUX: GKI_exit_task 0 done
09-06 18:58:16.862  3877  3988 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 18:58:16.863  3877  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 18:58:16.870  3877  3877 D HeadsetService: Received stop request...Stopping profile...
,09-06 18:58:16.873  3877  3877 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 18:58:16.873  3877  3877 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:58:16.873  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.873  3877  4001 D HeadsetStateMachine: Exit Disconnected: -1
09-06 18:58:16.874  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:16.874  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 18:58:16.875  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:16.875  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:16.875  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:16.876  3877  3877 D A2dpService: Received stop request...Stopping profile...
09-06 18:58:16.876  3877  4053 D A2dpStateMachine: Exit Disconnected: -1
,09-06 18:58:16.877  3877  3877 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 18:58:16.880  3877  3983 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 18:58:16.881  3877  3877 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 18:58:16.881  3877  3877 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:58:16.881  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.881  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-06 18:58:16.881  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 18:58:16.882  3877  3877 D HidService: Received stop request...Stopping profile...
09-06 18:58:16.882  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.883  7084  7104 W FormManager: Network not available. Please check & try again.
,09-06 18:58:16.884  3877  3877 D HeadsetStateMachine: Unbinding service...
09-06 18:58:16.885  6995  6995 D BluetoothInputDevice: Proxy object disconnected
09-06 18:58:16.886  6995  6995 D HidProfile: Bluetooth service disconnected
09-06 18:58:16.886  3877  3877 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 18:58:16.886  3877  3877 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 18:58:16.886  3877  3877 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 18:58:16.886  3877  3877 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 18:58:16.886  3877  3877 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 18:58:16.886  3877  3877 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:58:16.886  3877  3877 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 18:58:16.887  3877  3877 D HealthService: Received stop request...Stopping profile...
09-06 18:58:16.887  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.889  3877  3877 D PanService: Received stop request...Stopping profile...
09-06 18:58:16.889  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.890  3877  3877 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:58:16.890  6995  6995 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 18:58:16.891  6995  6995 D PanProfile: Bluetooth service disconnected
09-06 18:58:16.891  3877  3877 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 18:58:16.891  3877  3877 D BtGatt.GattService: stop()
09-06 18:58:16.891  3877  3877 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 18:58:16.895  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.896  3877  3877 D BluetoothMapService: Received stop request...Stopping profile...
09-06 18:58:16.896  3877  3877 D BluetoothMapService: stop()
09-06 18:58:16.897  3877  3877 D BluetoothMapEmailAppObserver: deinitObservers()
,09-06 18:58:16.897  3877  3877 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 18:58:16.899  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 18:58:16.899  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 18:58:16.899  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29d88862
09-06 18:58:16.900  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 18:58:16.900  6995  6995 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 18:58:16.901  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 18:58:16.901  3877  3877 I BluetoothA2dpServiceJni: cleanupNative
09-06 18:58:16.901  3877  4055 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 18:58:16.901  3877  3877 I GKI_LINUX: GKI_exit_task 2 done
09-06 18:58:16.901  3877  3877 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 18:58:16.901  3877  3877 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 18:58:16.901  3877  3877 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 18:58:16.902  3877  3877 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 18:58:16.902  3877  3877 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 18:58:16.902  3877  3877 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 18:58:16.902  3877  3877 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 18:58:16.902  3877  3877 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 18:58:16.903  3877  3877 V BluetoothMapService: Handler(): got msg=4
09-06 18:58:16.903  3877  3877 D BluetoothMapService: MAP Service closeService in
09-06 18:58:16.903  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 18:58:16.903  3877  3877 V BluetoothMapService: MAP Service closeService out
09-06 18:58:16.904  3877  3877 D BluetoothMapService: cleanup()
09-06 18:58:16.904  3877  3877 D BluetoothMapService: MAP Service closeService in
09-06 18:58:16.904  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 18:58:16.904  3877  3877 V BluetoothMapService: MAP Service closeService out
09-06 18:58:16.904  3877  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 18:58:16.904  3877  3983 D BluetoothAdapterProperties: Setting state to 10
09-06 18:58:16.904  3877  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 18:58:16.904  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:16.904  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 18:58:16.904  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-06 18:58:16.905  3877  3983 I BluetoothAdapterState: Entering OffState
09-06 18:58:16.905  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:16.905  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:16.906  6995  7012 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 18:58:16.906  6995  7011 D BluetoothMap: onBluetoothStateChange: up=false
09-06 18:58:16.908  6995  7011 D BluetoothPan: onBluetoothStateChange on: false
,09-06 18:58:16.911  1853  2451 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:16.911  1853  4450 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:16.912  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:58:16.912  6995  7012 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 18:58:16.913  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 18:58:16.913  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 18:58:16.914  7084  7105 V FormManager: Network unavailable.
09-06 18:58:16.916  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 18:58:16.917  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 18:58:16.917  7084  7105 V FormManager: Network unavailable.
09-06 18:58:16.917  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@10fb499b mBinding = false
09-06 18:58:16.917  1034  1096 D BluetoothManagerService: Sending unbind request.
09-06 18:58:16.919  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 18:58:16.920  6995  6995 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 18:58:16.920  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 18:58:16.920  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 18:58:16.920  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 18:58:16.920  6995  6995 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 18:58:16.921  6995  6995 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 18:58:16.922  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:16.922  1941  2145 D LGBluetoothAPIService: Message: 2
,09-06 18:58:16.922  1941  2145 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2fc9fc3d mBinding = false
09-06 18:58:16.922  1941  2145 D LGBluetoothAPIService: Sending unbind request.
09-06 18:58:16.925  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:16.929  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:16.931  3877  3988 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 18:58:16.931  3877  3877 I GKI_LINUX: GKI_exit_task 1 done
09-06 18:58:16.931  3877  3877 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 18:58:16.931  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:16.933  3877  3877 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 18:58:16.934  3877  3877 I art     : --- WEIRD: removing null entry 246
09-06 18:58:16.934  3877  3877 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-06 18:58:16.934  3877  3877 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 18:58:16.935  3877  3877 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,09-06 18:58:16.938  6995  6995 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 18:58:16.939  3877  3877 I art     : System.exit called, status: 0
09-06 18:58:16.939  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 18:58:16.939  6995  6995 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 18:58:16.939  3877  3877 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 18:58:16.940  1604  1604 D BluetoothAdapter: 647474533: getState() :  mService = null. Returning STATE_OFF
09-06 18:58:16.940  1604  1604 D BluetoothAdapter: 647474533: getState() :  mService = null. Returning STATE_OFF
09-06 18:58:16.944  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 18:58:16.956  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:16.956  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:16.956  6995  6995 D DockEventReceiver: finishStartingService: stopping service
09-06 18:58:16.957  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:16.961  1034  1887 I ActivityManager: Killing 6147:com.android.contacts/u0a19 (adj 15): empty #17
09-06 18:58:16.963   316  2165 V AudioFlinger: 3877 died, releasing its sessions
09-06 18:58:16.963   316  2165 V AudioFlinger:  pid 1853 @ 0
09-06 18:58:16.963   316  2165 V AudioFlinger:  pid 3383 @ 1
09-06 18:58:16.963   316  2165 V AudioFlinger:  pid 3383 @ 2
09-06 18:58:16.963  6995  6995 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 18:58:17.006  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:17.059  1034  1758 I ActivityManager: Process com.android.bluetooth (pid 3877) has died
09-06 18:58:17.060  1034  1758 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-06 18:58:17.066  1034  2060 W libprocessgroup: failed to open /acct/uid_10019/pid_6147/cgroup.procs: No such file or directory
09-06 18:58:17.083  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:58:17.088  4343  7116 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 18:58:17.097  4343  7117 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:17.098  4343  7117 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 18:58:17.124  7016  7016 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,09-06 18:58:17.124  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:17.124  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:17.131  7084  7119 W FormManager: Network not available. Please check & try again.
09-06 18:58:17.148  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:58:17.161  7084  7120 V FormManager: Network unavailable.
09-06 18:58:17.167  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:17.169  6995  6995 D BluetoothPermissionRequest: onReceive
09-06 18:58:17.173  6995  6995 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-06 18:58:17.174  6995  6995 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 18:58:17.178  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 18:58:17.241  1034  1576 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7121 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 18:58:17.247  7084  7120 V FormManager: Network unavailable.
09-06 18:58:17.273  7044  7044 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 18:58:17.274  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-06 18:58:17.275  7044  7044 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-06 18:58:17.316  7044  7044 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:17.316  7044  7044 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:17.317  7121  7121 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 18:58:17.317  7121  7121 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:17.317  7121  7121 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 18:58:17.318  7121  7121 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 18:58:17.325  7044  7044 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 18:58:17.326  7044  7044 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 18:58:17.326  7044  7044 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 18:58:17.326  7044  7044 V SoundPool: doLoad: loading sample sampleID=1
,09-06 18:58:17.327  7044  7140 V SoundPool: Start decode
09-06 18:58:17.327  7044  7140 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 18:58:17.327   316  1404 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 18:58:17.327   316  1404 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 18:58:17.327   316  1404 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 18:58:17.328   316  1404 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 18:58:17.328  7044  7044 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 18:58:17.328   316  1404 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 18:58:17.328   316  1404 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 18:58:17.328   316  1404 V MediaPlayerService: player type = 3
09-06 18:58:17.328   316  1404 V AwesomePlayer: AwesomePlayer create()
09-06 18:58:17.328   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:17.328   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:17.328   316  1404 V AwesomePlayer: setAudioSink() 
09-06 18:58:17.328   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:17.328   316  1404 V AudioCache: notify(0xb0409680, 8, 0, 0)
09-06 18:58:17.328   316  1404 V AudioCache: ignored
09-06 18:58:17.328   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:17.328   316  1404 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 18:58:17.328   316  1404 V AwesomePlayer: setDataSource_l dataSource
09-06 18:58:17.328   316  1404 V LGParserOSAL: SniffLGParser start
09-06 18:58:17.328   316  1404 V LGParserOSAL: MainType:5, SubType=0
09-06 18:58:17.329   316  1404 V LGParserOSAL: #### check Mime : application/ogg
09-06 18:58:17.329   316  1404 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 18:58:17.329   316  1404 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 18:58:17.332  7044  7044 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 18:58:17.334  7044  7044 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 18:58:17.335  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 18:58:17.337  6774  6774 D UEI.SmartControl: QS Service created
09-06 18:58:17.351  6774  6774 I UEI.SmartControl: Service initServices...
09-06 18:58:17.352  6774  6774 D UEI.SmartControl: QS start get config
,09-06 18:58:17.352  7044  7044 V LGMDMManager: Create singleton instance
09-06 18:58:17.354  7121  7121 D BluetoothAdapterApp: Loading JNI Library
09-06 18:58:17.372   316  1404 V LGParserOSAL: supported mime: application/ogg
09-06 18:58:17.372   316  1404 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 18:58:17.372   316  1404 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,09-06 18:58:17.372   316  1404 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 18:58:17.372   316  1404 V AwesomePlayer: AudioTrack Setting
09-06 18:58:17.372   316  1404 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 18:58:17.372   316  1404 V AwesomePlayer: setAudioSource() 
09-06 18:58:17.372   316  1404 V MediaPlayerService: prepare
09-06 18:58:17.372   316  1404 V AwesomePlayer: prepareAsync_l() 
09-06 18:58:17.372   316  1404 V MediaPlayerService: wait for prepare
09-06 18:58:17.372   316  7141 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 18:58:17.372   316  7141 V AwesomePlayer: initAudioDecoder() 
09-06 18:58:17.372   316  7141 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 18:58:17.372   316  7141 V AudioSystem: isOffloadSupported()
09-06 18:58:17.373   316  7141 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 18:58:17.373   316  7141 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 18:58:17.373   316  7141 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 18:58:17.373   316  7141 V AwesomePlayer: getUseOffload() = 0 
09-06 18:58:17.373   316  7141 V OMXCodec: OMXCodec::Create
09-06 18:58:17.373   316  7141 V OMXCodec: findMatchingCodecs()
09-06 18:58:17.373   316  7141 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 18:58:17.373   316  7141 V OMXCodec: matchingCodecs.size()=1
09-06 18:58:17.373   316  7141 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 18:58:17.374   316  7141 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 18:58:17.375   316  7141 V LGCodecAdapter: LG Codec Adapter start
09-06 18:58:17.375   316  7141 V OMXCodec: OMXCodec Createtor
09-06 18:58:17.375   316  7141 V OMXCodec: setComponentRole
09-06 18:58:17.375   316  7141 V OMXCodec: configureCodec protected=0
09-06 18:58:17.375   316  7141 V LGCodecAdapter: called getLGCodecSpecificData
09-06 18:58:17.375   316  7141 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 18:58:17.375   316  7141 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 18:58:17.375   316  7141 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 18:58:17.375   316  7141 V LGCodecOSAL: Not support LGCodec
09-06 18:58:17.375   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 18:58:17.375   316  7141 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 18:58:17.375   316  7141 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 18:58:17.375   316  7141 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 18:58:17.375   316  7141 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 18:58:17.375   316  7141 V AudioSystem: isOffloadSupported()
09-06 18:58:17.375   316  7141 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 18:58:17.375   316  7141 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 18:58:17.375   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 18:58:17.375   316  7141 V OMXCodec: init()
09-06 18:58:17.375   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 18:58:17.375   316  7141 V OMXCodec: allocateBuffers
09-06 18:58:17.375   316  7141 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 18:58:17.375   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on, input port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-06 18:58:17.376   316  7141 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-06 18:58:17.376   316  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-06 18:58:17.376   316  7141 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 18:58:17.376   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 18:58:17.376   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 18:58:17.376   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 18:58:17.376   316  7141 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 18:58:17.376   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 18:58:17.376   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 18:58:17.376   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 18:58:17.376   316  7141 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 18:58:17.376   316  7141 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 18:58:17.376   316  7141 V AudioCache: notify(0xb0409680, 5, 0, 0)
09-06 18:58:17.376   316  7141 V AudioCache: ignored
09-06 18:58:17.376   316  7141 V AudioCache: notify(0xb0409680, 1, 0, 0)
09-06 18:58:17.376   316  7141 V AudioCache: prepared
09-06 18:58:17.376   316  1404 V AudioCache: wait - success
09-06 18:58:17.377   316  1404 V MediaPlayerService: start
09-06 18:58:17.377   316  1404 V AwesomePlayer: play_l() 
09-06 18:58:17.377   316  1404 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 18:58:17.377   316  1404 V AwesomePlayer: createAudioPlayer_l
09-06 18:58:17.377   316  1404 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 18:58:17.377   316  1404 V AwesomePlayer: startAudioPlayer_l() 
09-06 18:58:17.377   316  1404 D AudioPlayer: start of Playback, useOffload 0
,09-06 18:58:17.377   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 18:58:17.377   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-06 18:58:17.379   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 18:58:17.380   316  7143 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-06 18:58:17.380   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
,09-06 18:58:17.381   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
09-06 18:58:17.381   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 18:58:17.381   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 18:58:17.381   316  1404 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 18:58:17.382   316  1404 V AudioCache: notify(0xb0409680, 6, 0, 0)
09-06 18:58:17.382   316  1404 V AudioCache: ignored
09-06 18:58:17.382   316  1404 V MediaPlayerService: wait for playback complete
09-06 18:58:17.383   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.383   316  7144 V AudioCache: memcpy(0xaf004000, 0xb16b1000, 4096)
,09-06 18:58:17.384   316  7144 V AudioCache: write(0xb16b1000, 4096)
,09-06 18:58:17.384   316  7144 V AudioCache: memcpy(0xaf005000, 0xb16b1000, 4096)
09-06 18:58:17.384   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.384   316  7144 V AudioCache: memcpy(0xaf006000, 0xb16b1000, 4096)
09-06 18:58:17.385   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.385   316  7144 V AudioCache: memcpy(0xaf007000, 0xb16b1000, 4096)
09-06 18:58:17.386   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.386   316  7144 V AudioCache: memcpy(0xaf008000, 0xb16b1000, 4096)
09-06 18:58:17.386   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.386   316  7144 V AudioCache: memcpy(0xaf009000, 0xb16b1000, 4096)
09-06 18:58:17.387   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.387   316  7144 V AudioCache: memcpy(0xaf00a000, 0xb16b1000, 4096)
09-06 18:58:17.387   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.387   316  7144 V AudioCache: memcpy(0xaf00b000, 0xb16b1000, 4096)
09-06 18:58:17.388   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.388   316  7144 V AudioCache: memcpy(0xaf00c000, 0xb16b1000, 4096)
09-06 18:58:17.389   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.389   316  7144 V AudioCache: memcpy(0xaf00d000, 0xb16b1000, 4096)
09-06 18:58:17.389   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.389   316  7144 V AudioCache: memcpy(0xaf00e000, 0xb16b1000, 4096)
09-06 18:58:17.390   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.390   316  7144 V AudioCache: memcpy(0xaf00f000, 0xb16b1000, 4096)
09-06 18:58:17.390   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.390   316  7144 V AudioCache: memcpy(0xaf010000, 0xb16b1000, 4096)
09-06 18:58:17.391   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.391   316  7144 V AudioCache: memcpy(0xaf011000, 0xb16b1000, 4096)
09-06 18:58:17.391   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.392   316  7144 V AudioCache: memcpy(0xaf012000, 0xb16b1000, 4096)
09-06 18:58:17.392   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.392   316  7144 V AudioCache: memcpy(0xaf013000, 0xb16b1000, 4096)
09-06 18:58:17.392   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.392   316  7144 V AudioCache: memcpy(0xaf014000, 0xb16b1000, 4096)
09-06 18:58:17.393   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.393   316  7144 V AudioCache: memcpy(0xaf015000, 0xb16b1000, 4096)
09-06 18:58:17.393   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.393   316  7144 V AudioCache: memcpy(0xaf016000, 0xb16b1000, 4096)
09-06 18:58:17.394   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.394   316  7144 V AudioCache: memcpy(0xaf017000, 0xb16b1000, 4096)
09-06 18:58:17.395   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.395   316  7144 V AudioCache: memcpy(0xaf018000, 0xb16b1000, 4096)
09-06 18:58:17.395   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.395   316  7144 V AudioCache: memcpy(0xaf019000, 0xb16b1000, 4096)
09-06 18:58:17.396   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.396   316  7144 V AudioCache: memcpy(0xaf01a000, 0xb16b1000, 4096)
09-06 18:58:17.396   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.396   316  7144 V AudioCache: memcpy(0xaf01b000, 0xb16b1000, 4096)
09-06 18:58:17.396  7121  7121 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b92da7b Instance Count = 1
09-06 18:58:17.397   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.397   316  7144 V AudioCache: memcpy(0xaf01c000, 0xb16b1000, 4096)
09-06 18:58:17.397   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.397   316  7144 V AudioCache: memcpy(0xaf01d000, 0xb16b1000, 4096)
09-06 18:58:17.400   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.400   316  7144 V AudioCache: memcpy(0xaf01e000, 0xb16b1000, 4096)
09-06 18:58:17.400   316  7144 V AudioCa,che: write(0xb16b1000, 4096)
09-06 18:58:17.400   316  7144 V AudioCache: memcpy(0xaf01f000, 0xb16b1000, 4096)
09-06 18:58:17.401   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.401   316  7144 V AudioCache: memcpy(0xaf020000, 0xb16b1000, 4096)
09-06 18:58:17.401   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.401   316  7144 V AudioCache: memcpy(0xaf021000, 0xb16b1000, 4096)
,09-06 18:58:17.402  7121  7121 D BluetoothAdapterApp: onCreate
09-06 18:58:17.402   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.402   316  7144 V AudioCache: memcpy(0xaf022000, 0xb16b1000, 4096)
09-06 18:58:17.403   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.403   316  7144 V AudioCache: memcpy(0xaf023000, 0xb16b1000, 4096)
09-06 18:58:17.403   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.403   316  7144 V AudioCache: memcpy(0xaf024000, 0xb16b1000, 4096)
09-06 18:58:17.404   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.404   316  7144 V AudioCache: memcpy(0xaf025000, 0xb16b1000, 4096)
09-06 18:58:17.404   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.404   316  7144 V AudioCache: memcpy(0xaf026000, 0xb16b1000, 4096)
09-06 18:58:17.405   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.405   316  7144 V AudioCache: memcpy(0xaf027000, 0xb16b1000, 4096)
09-06 18:58:17.405   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.405   316  7144 V AudioCache: memcpy(0xaf028000, 0xb16b1000, 4096)
09-06 18:58:17.406   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.406   316  7144 V AudioCache: memcpy(0xaf029000, 0xb16b1000, 4096)
09-06 18:58:17.407   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.407   316  7144 V AudioCache: memcpy(0xaf02a000, 0xb16b1000, 4096)
09-06 18:58:17.407   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.407   316  7144 V AudioCache: memcpy(0xaf02b000, 0xb16b1000, 4096)
09-06 18:58:17.408   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.408   316  7144 V AudioCache: memcpy(0xaf02c000, 0xb16b1000, 4096)
09-06 18:58:17.408   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.408   316  7144 V AudioCache: memcpy(0xaf02d000, 0xb16b1000, 4096)
09-06 18:58:17.409   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.409   316  7144 V AudioCache: memcpy(0xaf02e000, 0xb16b1000, 4096)
09-06 18:58:17.409   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.409   316  7144 V AudioCache: memcpy(0xaf02f000, 0xb16b1000, 4096)
09-06 18:58:17.410   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.410   316  7144 V AudioCache: memcpy(0xaf030000, 0xb16b1000, 4096)
09-06 18:58:17.410   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.410   316  7144 V AudioCache: memcpy(0xaf031000, 0xb16b1000, 4096)
09-06 18:58:17.411   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.411   316  7144 V AudioCache: memcpy(0xaf032000, 0xb16b1000, 4096)
09-06 18:58:17.411   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.411   316  7144 V AudioCache: memcpy(0xaf033000, 0xb16b1000, 4096)
09-06 18:58:17.412   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.412   316  7144 V AudioCache: memcpy(0xaf034000, 0xb16b1000, 4096)
09-06 18:58:17.412   316  7144 V AudioCache: write(0xb16b1000, 4096)
09-06 18:58:17.412   316  7144 V AudioCache: memcpy(0xaf035000, 0xb16b1000, 4096)
09-06 18:58:17.412   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 18:58:17.412   316  7144 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 18:58:17.412   316  7144 V AwesomePlayer: postAudioEOS() 
09-06 18:58:17.412   316  7144 V AudioCache: write(0xb16b1000, 280)
09-06 18:58:17.412   316  7144 V AudioCache: memcpy(0xaf036000, 0xb16b1000, 280)
09-06 18:58:17.418   316  7141 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 18:58:17.418   316  7141 V AwesomePlayer: onStreamDone
09-06 18:58:17.418   316  7141 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 18:58:17.418   316  7141 V AudioCache: notify(0xb0409680, 2, 0, 0)
09-06 18:58:17.418   316  7141 V AudioCache: playback complete
09-06 18:58:17.418   316  7141 V AwesomePlayer: pause_l() 
09-06 18:58:17.418   316  7141 V AudioCache: notify(0xb0409680, 7, 0, 0)
09-06 18:58:17.418   316 , 7141 V AudioCache: ignored
09-06 18:58:17.418   316  7141 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:17.419   316  1404 V AudioCache: wait - success
09-06 18:58:17.419   316  1404 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 18:58:17.419   316  7141 D AudioPlayer: Pause Playback at 1068125
09-06 18:58:17.419   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:17.419   316  1404 V AudioCache: notify(0xb0409680, 8, 0, 0)
09-06 18:58:17.419   316  1404 V AudioCache: ignored
09-06 18:58:17.419   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:17.419   316  1404 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 18:58:17.419   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 18:58:17.419   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 18:58:17.419   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 18:58:17.419   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 18:58:17.419   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 18:58:17.419   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 18:58:17.419   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 18:58:17.419   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-06 18:58:17.419   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 18:58:17.420   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 18:58:17.420   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 18:58:17.420   316  7143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 18:58:17.420   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 18:58:17.420   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 18:58:17.420   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-06 18:58:17.421   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 18:58:17.421   316  1404 D AudioPlayer: AudioPlayer releasing audio source
09-06 18:58:17.421   316  1404 D AudioPlayer: AudioPlayer done releasing audio source
09-06 18:58:17.421   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:17.421   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:17.421   316  1404 V AwesomePlayer: ~AwesomePlayer call
09-06 18:58:17.421   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:17.421   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:17.421  7044  7140 V SoundPool: close(31)
09-06 18:58:17.421  7044  7140 V SoundPool: pointer = 0x9fe4a000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 18:58:17.422  7121  7121 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 18:58:17.422  7121  7121 D ProfileConfigQcom: Adding HeadsetService
09-06 18:58:17.422  7121  7121 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-06 18:58:17.422  7121  7121 D ProfileConfigQcom: Adding A2dpService
09-06 18:58:17.423  7121  7121 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 18:58:17.423  7121  7121 D ProfileConfigQcom: Adding HidService
09-06 18:58:17.423  7121  7121 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 18:58:17.423  7121  7121 D ProfileConfigQcom: Adding HealthService
09-06 18:58:17.423  7121  7121 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: Adding PanService
09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: Adding GattService
09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: Adding BluetoothMapService
,09-06 18:58:17.424  7121  7121 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 18:58:17.426  7121  7121 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 18:58:17.429  7121  7121 V LGMDMManagerInternal: Create singleton instance
,09-06 18:58:17.432  6995  6995 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 18:58:17.433  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 18:58:17.434  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 18:58:17.435  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1790
09-06 18:58:17.474  7121  7121 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:58:17.477  7121  7121 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-06 18:58:17.478  7121  7121 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-06 18:58:17.478  7121  7121 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:17.479  7121  7121 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:17.479  7121  7121 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 18:58:17.484  7064  7064 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-06 18:58:17.652  6774  6774 I UEI.SmartControl: Supports setup maps: true
09-06 18:58:17.655  6774  6774 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 18:58:17.655  6774  6774 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 18:58:17.655  6774  6774 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,09-06 18:58:17.655  6774  6774 I UEI.SmartControl: ### init IR Blaster...
09-06 18:58:17.659  6774  6774 D serial_port: Configuring serial port
09-06 18:58:17.659  6774  6774 E UEI.SmartControl: UEIBLaster setting for 616
09-06 18:58:17.659  6774  6774 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 18:58:17.659  6774  6774 I UEI.SmartControl: configuring settings for MAXQ616
09-06 18:58:17.659  6774  6774 I UEI.SmartControl: Get version...
09-06 18:58:17.678  6774  7147 D UEI.SmartControl: serial port data available: 21
,09-06 18:58:17.705  6774  6774 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 18:58:17.705  6774  6774 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 18:58:17.705  6774  6774 I UEI.SmartControl: QS saving settings...
,09-06 18:58:17.707  6774  6774 D UEI.SmartControl: IR Blaster version: 25672567
09-06 18:58:17.726  6774  7147 D UEI.SmartControl: serial port data available: 4
,09-06 18:58:17.754  6774  7156 I UEI.SmartControl: Device manager: loading config....
,09-06 18:58:17.757  6774  7156 D UEI.SmartControl: ----------- loading internal config...
,09-06 18:58:17.759  6774  6774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 18:58:17.764  6774  7156 E UEI.SmartControl: Loading SETTINGS...
09-06 18:58:17.765  6774  6774 E UEI.SmartControl: Services init done
09-06 18:58:17.765  6774  6774 D UEI.SmartControl: QS Service init finished
09-06 18:58:17.768  6774  6774 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 18:58:17.768  6774  6774 D UEI.SmartControl: QS Service version code: 201091
09-06 18:58:17.768  6774  6774 D UEI.SmartControl: Service requested: Control
,09-06 18:58:17.770  6774  7156 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 18:58:17.777  7044  7044 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 18:58:17.780  6774  6791 I UEI.SmartControl: ------ IControl API: 11
09-06 18:58:17.780  6774  6791 D UEI.SmartControl: File observer start...
,09-06 18:58:17.781  6774  6791 E UEI.SmartControl: IR Port is disabled: false
09-06 18:58:17.782  6774  6791 D UEI.SmartControl: Starting file observer...
09-06 18:58:17.782  6774  6791 I UEI.SmartControl: Registering callback...
,09-06 18:58:17.784  6774  6790 I UEI.SmartControl: ------ IControl API: 19
09-06 18:58:17.784  6774  6790 I UEI.SmartControl: Registering Services Ready callback...
09-06 18:58:17.785  6774  6790 I UEI.SmartControl: Notify client services are ready...
09-06 18:58:17.786  7044  7063 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 18:58:17.786  6774  6774 D UEI.SmartControl: Internal service binding...
09-06 18:58:17.787  7044  7138 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 18:58:17.787  7044  7138 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 18:58:17.787  7044  7044 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 18:58:17.787  7044  7044 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 18:58:17.788  6774  6790 I UEI.SmartControl: ------ IControl API: 8
09-06 18:58:17.790  7044  7044 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 18:58:17.790  7044  7044 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 18:58:17.790  7044  7044 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 18:58:17.791  7044  7044 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 18:58:17.791  7044  7044 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 18:58:17.792  7044  7044 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 18:58:17.793  7044  7044 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 18:58:17.793  6774  7155 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 18:58:17.793  6774  7155 D UEI.SmartControl: -----service ready thread exits
09-06 18:58:17.794  7044  7062 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 18:58:17.796  7044  7138 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 18:58:17.796  7044  7138 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 18:58:17.796  7044  7044 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 18:58:17.797  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-06 18:58:17.798  7044  7044 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 18:58:17.798  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 18:58:17.800  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 18:58:17.802  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 18:58:17.803  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 18:58:17.804  7044  7044 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473181097803]
09-06 18:58:17.807  7044  7044 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 18:58:17.807  7044  7044 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
,09-06 18:58:17.810  1034  1758 I ActivityManager: Killing 6176:com.android.gallery3d/u0a27 (adj 15): empty #17
09-06 18:58:17.828  7044  7158 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 18:58:17.848  1034  1758 I ActivityManager: Killing 6657:com.lge.email/u0a23 (adj 15): empty #18
,09-06 18:58:17.877  1034  2011 W libprocessgroup: failed to open /acct/uid_10027/pid_6176/cgroup.procs: No such file or directory
,09-06 18:58:17.882  1034  1988 W libprocessgroup: failed to open /acct/uid_10023/pid_6657/cgroup.procs: No such file or directory
09-06 18:58:17.892  7044  7044 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-06 18:58:17.895  7044  7044 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 18:58:17.896  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 18:58:17.897  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 18:58:17.898  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 18:58:17.899  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 18:58:17.900  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 18:58:17.915  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 18:58:18.723  1034  1576 D WifiServiceImplEx: setWifiEnabled: true pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 18:58:18.724  1034  1576 D WifiService: setWifiEnabled: true pid=6865, uid=10118
09-06 18:58:18.724  1034  1576 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:58:18.757  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:18.758  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:18.758  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:18.759  1034  1393 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 18:58:18.759  1034  1393 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 18:58:18.762  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 18:58:18.762  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 18:58:18.762  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 18:58:18.762  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 18:58:18.762  1034  1393 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 18:58:18.762  1034  1393 E WifiHW  : unknown target_country: EU , set to default
09-06 18:58:18.762  1034  1393 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 18:58:18.762  1034  1393 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 18:58:18.762  1034  1393 I WifiUtil: gEnableBmps=1
09-06 18:58:18.842  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:18.860  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-06 18:58:18.885  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:18.888  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:18.890  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:18.891  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:18.894  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-06 18:58:18.907  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:18.912  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:18.913  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 18:58:18.916  6568  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 18:58:18.928  5825  5825 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 18:58:18.937  5825  5825 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 18:58:18.973  2215  2215 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:19.009  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:19.050  1034  2011 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7175 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-06 18:58:19.051  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 18:58:19.052  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 18:58:19.125  7175  7175 I AppUp4:AppBoxCP: onCreate
,09-06 18:58:19.126  7175  7175 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-06 18:58:19.137  7175  7175 I AppUp4:DB:  setFingerPrint start
,09-06 18:58:19.137  7175  7175 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-06 18:58:19.145  7175  7175 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-06 18:58:19.145  7175  7175 I AppUp4:DB:  SDK version = 21
09-06 18:58:19.145  7175  7175 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-06 18:58:19.147  7175  7175 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-06 18:58:19.149  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 18:58:19.149  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:19.152  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 18:58:19.152  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 18:58:19.161  7175  7175 I AppUp4:CustModeStarterReceiver: onReceive
09-06 18:58:19.217  7175  7175 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:19.217  7175  7175 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:19.225  7175  7175 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ee96b2d
09-06 18:58:19.226  7175  7175 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 18:58:19.226  7175  7175 D AppUp4:CustFacade: isPhone : true
09-06 18:58:19.227  7175  7175 D AppUp4:CustModeStarterReceiver: begin check event
09-06 18:58:19.227  7175  7175 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-06 18:58:19.228  7175  7175 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-06 18:58:19.230  7175  7195 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-06 18:58:19.230  7175  7195 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-06 18:58:19.231  7175  7195 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-06 18:58:19.234  1034  2011 I ActivityManager: Killing 6251:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-06 18:58:19.291  1034  1988 W libprocessgroup: failed to open /acct/uid_10080/pid_6251/cgroup.procs: No such file or directory
,09-06 18:58:19.291  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:19.292  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:19.297  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:19.302  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:19.314  4343  7209 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 18:58:19.320  4343  7210 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:19.320  4343  7210 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 18:58:19.353  1034  2060 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7211 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 18:58:19.444  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 18:58:19.449  1034  1096 D Tethering: InitialState.processMessage what=4
09-06 18:58:19.450   312   894 D SoftapController: Softap fwReload - Ok
09-06 18:58:19.452  1034  1393 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (683ms)
09-06 18:58:19.453   312   894 D CommandListener: Setting iface cfg
09-06 18:58:19.453   312   894 D CommandListener: Trying to bring down wlan0
09-06 18:58:19.454   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:58:19.455  1034  1393 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 18:58:19.457  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:19.457  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:19.457  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:19.458  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 18:58:19.460  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-06 18:58:19.462  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 18:58:19.462  1034  1393 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 18:58:19.462  1034  1393 D WifiMonitor: connecting to supplicant
09-06 18:58:19.452  7229  7229 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:19.452  7229  7229 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:19.465  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:19.465  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:19.478  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:19.491  7229  7229 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 18:58:19.492  7211  7211 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:58:19.492  7211  7211 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:19.494  7211  7211 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 18:58:19.494  7211  7211 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 18:58:19.524  7229  7229 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 18:58:19.524  7229  7229 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-06 18:58:19.591  7211  7211 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 18:58:19.608  7211  7211 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 18:58:19.649  7211  7211 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 18:58:19.652  7229  7229 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 18:58:19.680  7211  7211 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:19.680  7211  7211 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:19.716  7229  7229 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 18:58:19.732  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-06 18:58:19.732  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 18:58:19.733  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 18:58:19.733  1034  1393 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 18:58:19.733  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 18:58:19.733  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:19.734  7229  7229 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 18:58:19.734  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:19.734  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:19.735  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:19.735  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-06 18:58:19.735  1034  7240 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 18:58:19.735  1034  1393 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 18:58:19.735  1034  1393 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 18:58:19.735  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 18:58:19.735  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 18:58:19.735  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 18:58:19.736  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 18:58:19.736  1034  1393 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 18:58:19.736  1034  1393 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 18:58:19.736  1034  1393 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 18:58:19.736  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:19.736  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:19.736  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:19.737  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.737  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.737  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.737  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.737  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:19.738  1034  1393 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 18:58:19.738  1034  1393 D WifiNative-wlan0: SET update_config 1: returned true
09-06 18:58:19.738  1034  1393 D WifiConfigStore: Loading config and enabling all networks 
09-06 18:58:19.739  1034  1393 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 18:58:19.739  1034  1393 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 18:58:19.739  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-06 18:58:19.740  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 18:58:19.740  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 18:58:19.742  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:19.743  1034  1393 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-06 18:58:19.745  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:19.746  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:19.746  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:19.746  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:19.747  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:19.747  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:19.747  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:19.747  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:19.752  1034  1393 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-06 18:58:19.752  1034  1393 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 18:58:19.753  1034  1393 D WifiStateMachine: enableVerboseLogging : level 2
09-06 18:58:19.754  1034  1393 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 18:58:19.754  1034  1393 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 18:58:19.754  1034  1393 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 18:58:19.755  1034  1393 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 18:58:19.755  1034  1393 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 18:58:19.755  1034  1393 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 18:58:19.755  1034  1393 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 18:58:19.755  1034  1393 D WifiNative-wl,an0: SET model_number LG-D855: returned true
09-06 18:58:19.755  1034  1393 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 18:58:19.756  1034  1393 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 18:58:19.756  1034  1393 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-06 18:58:19.757  1034  1393 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 18:58:19.757  1034  1393 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 18:58:19.758  1034  1393 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 18:58:19.758  1034  1393 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 18:58:19.758  1034  1393 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-06 18:58:19.759  1034  1393 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 18:58:19.759  1034  1393 D WifiNative-HAL: Setting external_sim to 1
09-06 18:58:19.759  1034  1393 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 18:58:19.759  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-06 18:58:19.759  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 18:58:19.759  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-06 18:58:19.759  1034  1393 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 18:58:19.759  1941  2345 D WfdsMonitor: WfdsMonitorThread create
09-06 18:58:19.759  1034  1393 I WifiNative-HAL: startHal
09-06 18:58:19.759  1034  1393 D wifi    : setting scan oui 0x953e4480
09-06 18:58:19.760  1941  2345 D WfdsMonitor: WFDS Monitor is created and started
09-06 18:58:19.760  1941  2345 D WfdsService: WiFi: Supplicant connection re-established
09-06 18:58:19.760  1034  1393 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 18:58:19.760  1034  1393 I WifiNative-HAL: startHal
09-06 18:58:19.760  1034  1393 D wifi    : setting scan oui 0x953e4480
09-06 18:58:19.760  1034  1393 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 18:58:19.760  1034  1393 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 18:58:19.760  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 18:58:19.761  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 18:58:19.761  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 18:58:19.761  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 18:58:19.761  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 18:58:19.761  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 18:58:19.761  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 18:58:19.761  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 18:58:19.761  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 18:58:19.761  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 18:58:19.762  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 18:58:19.762  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 18:58:19.762  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 18:58:19.762  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 18:58:19.763  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 18:58:19.763  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 18:58:19.763  7229  7229 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 18:58:19.763  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 18:58:19.763  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 18:58:19.763  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 18:58:19.763  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 18:58:19.764  1941  7241 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 18:58:19.764  1941  7241 E CtrlSupplicant: Succeed to open control connection
09-06 18:58:19.764  1034  1393 E WifiNative: : [179,902,461 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 18:58:19.764  1034  1393 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 18:58:19.764  1941  7241 E CtrlSupplicant: Succeed to open monitor connection
09-06 18:58:19.764  1941  7241 D WfdsMonitor: Supplicant connection established
09-06 18:58:19.765  1034  1393 D WifiNative-wlan0: RECONNECT: returned true
09-06 18:58:19.765  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-06 18:58:19.765  1034  1393 D WifiNative-wlan0: doString: [STATUS]
09-06 18:58:19.765  1034  7240 D WifiMonito,r: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 18:58:19.765  1034  1393 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 18:58:19.765  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 18:58:19.765  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:19.766  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:19.766  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.767   312   894 D CommandListener: Setting iface cfg
09-06 18:58:19.767   312   894 D CommandListener: Trying to bring up p2p0
09-06 18:58:19.767  1034  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 18:58:19.767  1034  1391 D LGWifiP2pService: P2pEnablingState
09-06 18:58:19.768  1034  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.768  1034  1391 D LGWifiP2pService: P2p socket connection successful
09-06 18:58:19.768  1034  1391 D LGWifiP2pService: P2pEnabledState
,09-06 18:58:19.769  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 18:58:19.769  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-06 18:58:19.769  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 18:58:19.769  1941  1941 D WfdsService: WifiP2pState is changed : true
09-06 18:58:19.770  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.770  1034  1556 I WifiNative-HAL: startHal
09-06 18:58:19.770  1941  2345 D WfdsService: Receive the WFDS_ENABLE Method
09-06 18:58:19.770  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-06 18:58:19.770  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0x953e4480
09-06 18:58:19.770  1034  1556 D wifi    : failed to get capabilities : -3
09-06 18:58:19.770  1034  1556 E WifiScanningService: could not get scan capabilities
09-06 18:58:19.770  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-06 18:58:19.770  1941  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-06 18:58:19.770  7229  7229 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 18:58:19.770  1034  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.770  1941  2345 D WfdsService: selectPreferredScanChannel [36]
09-06 18:58:19.770  1941  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 18:58:19.771  1034  1391 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 18:58:19.772  1034  1393 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 18:58:19.772  1034  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 18:58:19.774  1034  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 18:58:19.774  1034  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 18:58:19.774  1034  1391 D WifiNative-p2p0: SET device_name G3: returned true
09-06 18:58:19.774  1034  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 18:58:19.774  1034  1391 D LGWifiP2pService: before postfix = G3
09-06 18:58:19.774  1034  1391 D WifiServerServiceExt: postfix byte check : 2
09-06 18:58:19.774  1034  1391 D LGWifiP2pService: after postfix = G3
09-06 18:58:19.774  1034  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 18:58:19.774  1034  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 18:58:19.774  1034  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 18:58:19.775  1034  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 18:58:19.775  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 18:58:19.775  1034  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 18:58:19.775  1034  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 18:58:19.775  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 18:58:19.775  1941  1941 D WfdsService: isConnected: false
09-06 18:58:19.776  1034  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 18:58:19.776  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress
09-06 18:58:19.776  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 18:58:19.777  1034  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 18:58:19.777  1034  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 18:58:19.777  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 18:58:19.777  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 18:58:19.777  1941  1941 D WfdsService: Update P2p Interface State: 3
09-06 18:58:19.777  1034  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 18:58:19.777  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 18:58:19.778  1034  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 18:58:19.778  1034  1393 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 18:58:19.778  1034  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 18:58:19.778  1034  1393 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 18:58:19.778  1034  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 18:58:19.778  1034  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 18:58:19.779  1034  1393 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 18:58:19.779  1034  1393 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 18:58:19.780  1034  1393 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 18:58:19.780  1034  1393 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 18:58:19.780  1034  1393 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 18:58:19.788  7229  7229 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 18:58:19.789  1034  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 18:58:19.789  ,1034  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 18:58:19.789  1034  1391 D LGWifiP2pService: InactiveState
,09-06 18:58:19.789  1034  1391 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.789  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.789  1034  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 18:58:19.789  1034  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 18:58:19.789  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.789  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.789  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 18:58:19.789  1034  1391 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.790  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.790  7229  7229 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 18:58:19.791  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.791  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 18:58:19.792  1034  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.792  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.792  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.792  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.792  1034  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.792  1034  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.792  1941  7241 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 18:58:19.792  1941  7241 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.792  1941  7241 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.792  1034  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.792  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.792  1034  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.792  1034  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.792  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.792  1034  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2,=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.793  1941  2345 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 18:58:19.793  1034  1393 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 18:58:19.793  1034  1391 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.793  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.793  1034  1391 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.793  1034  1393 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 18:58:19.794  1034  1034 E WifiServerServiceExt: No p2p device connected
09-06 18:58:19.794  1034  1393 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 18:58:19.794  1034  1393 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 18:58:19.794  7229  7229 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 18:58:19.794  1034  1393 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 18:58:19.794  1034  1393 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 18:58:19.795  1034  1393 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 18:58:19.795  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 18:58:19.795  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 18:58:19.796  7229  7229 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.796  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 18:58:19.796  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.796  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.796  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:19.796  7229  7229 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 18:58:19.796  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.796  1034  1393 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 18:58:19.796  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.796  1034  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.796  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.796  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.796  1941  7241 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.797  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.797  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:19.797  1034  1393 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 18:58:19.797  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.797  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.797  1034  1393 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 18:58:19.797  1034  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.797  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.797  1034  7240 E, WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:19.797  1941  7241 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:19.797  1034  1393 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 18:58:19.797  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 18:58:19.798  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 18:58:19.798  7229  7229 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:19.798  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 18:58:19.798  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:19.798  1034  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:19.798  1034  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:19.799  1034  1393 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 18:58:19.799  1034  1393 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 18:58:19.799  1034  1393 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 18:58:19.799  1034  1393 D WifiNative-wlan0: doBoolean: SCAN
09-06 18:58:19.799  1034  1393 D WifiNative-wlan0: SCAN: returned false
09-06 18:58:19.800  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=179938  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 18:58:19.801  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:19.801  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:19.802  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.802  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.802  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 18:58:19.802  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=179940  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 18:58:19.802  1034  1393 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:19.803  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:19.803  1034  1393 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:19.803  1034  1393 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:19.804  1034  1393 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:19.804  1034  1393 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:19.805  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:19.805  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 18:58:19.814  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 18:58:19.842  7211  7211 I HubEmail: JNI_OnLoad()
09-06 18:58:19.842  7211  7211 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 18:58:19.842  7211  7211 I HubEmail: registerNatives()
09-06 18:58:19.842  7211  7211 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 18:58:19.842  7211  7211 I HubEmail: registerNativeMethods()
09-06 18:58:19.842  7211  7211 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 18:58:19.842  7211  7211 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-06 18:58:19.844  3383  3383 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 18:58:19.844  3383  3383 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:19.844  3383  3383 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 18:58:19.882  1034  1051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7247 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-06 18:58:19.891  7084  7245 V FormManager: Network unavailable.
09-06 18:58:19.891  7211  7246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:19.892  7084  7243 W FormManager: Network not available. Please check & try again.
09-06 18:58:19.895  7084  7245 V FormManager: Network unavailable.
09-06 18:58:19.900  1034  2030 I ActivityManager: Killing 6694:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-06 18:58:19.949  1034  1952 W libprocessgroup: failed to open /acct/uid_10061/pid_6694/cgroup.procs: No such file or directory
,09-06 18:58:20.034  7247  7247 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:20.034  7247  7247 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:20.037  7247  7247 D PhoneMonitor: Register our PhoneStateListener
,09-06 18:58:20.065  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-06 18:58:20.067  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 18:58:20.093  7247  7247 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-06 18:58:20.095  7247  7247 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-06 18:58:20.096  7247  7247 D TelephonyAutoProfiling: [parse] Load xml
,09-06 18:58:20.103  7247  7247 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-06 18:58:20.103  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-06 18:58:20.104  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-06 18:58:20.105  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-06 18:58:20.105  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-06 18:58:20.105  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-06 18:58:20.105  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-06 18:58:20.105  7247  7247 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-06 18:58:20.105  7247  7247 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-06 18:58:20.119  1034  1952 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7269 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 18:58:20.120  1034  1952 I ActivityManager: Killing 5602:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-06 18:58:20.130  7247  7247 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-06 18:58:20.192  1034  2033 W libprocessgroup: failed to open /acct/uid_10097/pid_5602/cgroup.procs: No such file or directory
,09-06 18:58:20.377  7229  7229 E wpa_supplicant: USIM:  scard_init function
09-06 18:58:20.379  7229  7229 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-06 18:58:20.384  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 18:58:20.384  1034  7240 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 18:58:20.385  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 18:58:20.385  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-06 18:58:20.385  1034  7240 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 18:58:20.385  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,09-06 18:58:20.385  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 18:58:20.387  1034  1393 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 18:58:20.388  1034  1393 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 18:58:20.389  1034  1393 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 18:58:20.390  1034  1393 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 18:58:20.391  1034  1393 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-06 18:58:20.400  1034  1952 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7287 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-06 18:58:20.401  1034  1952 I ActivityManager: Killing 6736:com.lge.eula/1000 (adj 15): empty #17
,09-06 18:58:20.450  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=180589  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-06 18:58:20.456  1034  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6736/cgroup.procs: No such file or directory
09-06 18:58:20.462  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.462  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 18:58:20.465  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.465  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=180604  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 18:58:20.466  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.466  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.466  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 18:58:20.471  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.472  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.472  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 18:58:20.473  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 18:58:20.473  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 18:58:20.488  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.488  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:20.491  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:20.493  7229  7229 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 18:58:20.493  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 18:58:20.493  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 18:58:20.493  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 18:58:20.493  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 18:58:20.494  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:20.494  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:20.495  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=180633  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 18:58:20.495  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=180634  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 18:58:20.496  1034  1393 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=180634
09-06 18:58:20.496  1034  1393 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=180635
09-06 18:58:20.498  1034  1393 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=180636
09-06 18:58:20.498  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=180637
09-06 18:58:20.499  1034  1393 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=180637
09-06 18:58:20.500  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=180638  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 18:58:20.503  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:20.503  7229  7229 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 18:58:20.503  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 18:58:20.503  7229  7229 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 18:58:20.503  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 18:58:20.503  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 18:58:20.503  1034  7240 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 18:58:20.503  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 18:58:20.503  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 18:58:20.503  1034  7240 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-06 18:58:20.508  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:20.508  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 18:58:20.511  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.511  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.511  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 18:58:20.511  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 18:58:20.512  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.512  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:20.513  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.515  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=180653  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 18:58:20.516  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=180654  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 18:58:20.516  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=180655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 18:58:20.517  1034  1393 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=180655
09-06 18:58:20.519  1034  1393 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=180657
09-06 18:58:20.520  1034  1393 D WifiNative-wlan0: doString: [STATUS]
09-06 18:58:20.520  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:20.520  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:20.521  1034  1393 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-06 18:58:20.524  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:58:20.524  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.524  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 18:58:20.525  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 18:58:20.525  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 18:58:20.525  1034  1393 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 18:58:20.534  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.534  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:20.536  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:20.579  1034  1952 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7308 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 18:58:20.581  1034  1952 I ActivityManager: Killing 6753:com.lge.bnr/1000 (adj 15): empty #17
09-06 18:58:20.617   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 38.461ms
,09-06 18:58:20.638   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 20.033ms
,09-06 18:58:20.657   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 378us total 18.270ms
,09-06 18:58:20.660  1034  1959 W libprocessgroup: failed to open /acct/uid_1000/pid_6753/cgroup.procs: No such file or directory
09-06 18:58:20.660  1034  1393 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-06 18:58:20.660  1034  1393 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 18:58:20.666  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.666  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:20.667  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.667  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.667  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.667  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-06 18:58:20.674  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:58:20.674  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.674  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 18:58:20.687  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.687  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 18:58:20.694  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.699  1034  1393 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 18:58:20.699  1034  1393 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:58:20.699  1034  1393 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 18:58:20.699  1034  1414 D ConnectivityService: Got NetworkAgent Messenger
09-06 18:58:20.699  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 18:58:20.699  1034  1414 D ConnectivityService: NetworkAgent connected
09-06 18:58:20.700  1034  1393 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 18:58:20.700  1034  1393 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 18:58:20.706  1034  1393 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 18:58:20.706  1034  1393 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:58:20.706  1034  1393 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 18:58:20.706  1034  1393 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 18:58:20.707  1034  1393 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 18:58:20.709  7308  7308 I art     : Almond Protected OAT
09-06 18:58:20.710  1034  1393 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 18:58:20.712   312   894 D CommandListener: Setting iface cfg
09-06 18:58:20.717  1034  1393 E WifiStateMachine: Start Dhcp Watchdog 2
09-06 18:58:20.717  1034  7328 D DhcpStateMachine: StoppedState
09-06 18:58:20.718  1034  7328 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.718  1034  7328 D DhcpStateMachine: WaitBeforeStartState
09-06 18:58:20.718  1034  1393 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=180856  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-06 18:58:20.718  1034  1393 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=180857  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-06 18:58:20.719  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=180857  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:20.720  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:20.720  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:20.721  1034  1393 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:20.721  1034  1393 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:20.722  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-06 18:58:20.722  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:20.723  1034  1393 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=180861  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:20.723  1034  1393 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=180861  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-06 18:58:20.724  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=180862  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:20.725  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:134373] from screen [on:0 period:7318197] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-06 18:58:20.726  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:7318198] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-06 18:58:20.726  1034  1393 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 18:58:20.731  1034  1414 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-06 18:58:20.731  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.732  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 18:58:20.732  1034  1393 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.732  1034  1393 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.733  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.735  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.735  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 18:58:20.736  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
09-06 18:58:20.736  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
09-06 18:58:20.736  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 18:58:20.737  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 18:58:20.737  1034  1393 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 18:58:20.737  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 18:58:20.737  1034  1393 D WifiNative-wlan0: SET ps 0: returned true
09-06 18:58:20.737  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 18:58:20.738  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 18:58:20.738  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 18:58:20.740  1034  1391 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@212a7f2b target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.741  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@212a7f2b target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.741  1034  1393 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,09-06 18:58:20.741  1034  1393 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 18:58:20.741  1034  1393 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 18:58:20.742   312   894 D CommandListener: Setting iface cfg
09-06 18:58:20.742   312   894 D CommandListener: Trying to bring up wlan0
09-06 18:58:20.743  1034  1393 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 18:58:20.744  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.745  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 18:58:20.745  1034  1393 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.745  1034  1393 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.746  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.746  1034  7328 D DhcpStateMachine: WaitBeforeStartState{ when=-5ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.746  1034  7328 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 18:58:20.746  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:20.747  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 18:58:20.748  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 18:58:20.748  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 18:58:20.749  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.749  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.749  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 18:58:20.750  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 18:58:20.750  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 18:58:20.750  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 18:58:20.750  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 18:58:20.751  1034  1393 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 18:58:20.751  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:20.755  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:20.755  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 18:58:20.756  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.761  7308  7308 D WeatherApplication: removeAccount
,09-06 18:58:20.761  7308  7308 D WeatherApplication: Account.length = 0
09-06 18:58:20.762  7308  7308 E WeatherApplication: OPERATOR:OPEN
09-06 18:58:20.766  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:20.767  7308  7308 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:20
09-06 18:58:20.767  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 18:58:20.768  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 18:58:20.768  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 18:58:20.769  1034  1393 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 18:58:20.769  1034  1414 D ConnectivityService: ignoring duplicate network state non-change
09-06 18:58:20.770  7308  7308 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 18:58:20.770  7308  7308 D Weather.Utils: 2 : All the weather widget is gone.
09-06 18:58:20.771  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.771  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 18:58:20.772  7308  7308 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 18:58:20.772  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.773  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.773  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.773  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 18:58:20.774  7308  7308 D WeatherAncestor: connectivity changed - connection : true
09-06 18:58:20.775  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.775  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.775  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 18:58:20.776  7308  7308 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-06 18:58:20.776  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 18:58:20.777  1034  1414 D ConnectivityService: Adding iface wlan0 to network 101
09-06 18:58:20.778  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 18:58:20.779  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 18:58:20.781  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.781  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.781  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 18:58:20.783  7308  7308 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-06 18:58:20.783  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 18:58:20.783  7308  7308 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 18:58:20.783  7308  7308 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-06 18:58:20.787  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.787  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:20.787  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 18:58:20.787  1034  1393 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 18:58:20.794  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.794  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:20.795  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.796  7308  7308 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 18:58:20.796  7308  7308 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:20
09-06 18:58:20.797  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.797  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 18:58:20.797  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.799  1034  1414 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 18:58:20.799  1034  1414 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-06 18:58:20.800  1034  1414 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 18:58:20.800  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:20.800  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 18:58:20.801  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:20.801   312   894 E Netd    : netlink response contains error (File exists)
,09-06 18:58:20.803  1034  1414 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-06 18:58:20.804  1034  1414 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 18:58:20.804  1034  1414 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-06 18:58:20.805  1034  1414 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-06 18:58:20.827  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.827  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.828  1034  1391 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.828  1034  1050 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7332 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 18:58:20.829  1034  1050 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
,09-06 18:58:20.840  1034  1393 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 18:58:20.841  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 18:58:20.841  1034  1393 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 18:58:20.841  1034  1393 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 18:58:20.841  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 18:58:20.842  1034  1393 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 18:58:20.843   316  2162 V AudioFlinger: 2127 died, releasing its sessions
,09-06 18:58:20.843   316  2162 V AudioFlinger:  pid 1853 @ 0
09-06 18:58:20.843   316  2162 V AudioFlinger:  pid 3383 @ 1
09-06 18:58:20.843   316  2162 V AudioFlinger:  pid 3383 @ 2
09-06 18:58:20.859  1034  1414 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-06 18:58:20.859  1034  1414 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 18:58:20.859  1034  1414 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 18:58:20.859  1034  1414 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 18:58:20.859  1034  1414 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:20.859  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.859  1034  1414 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:20.859  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 18:58:20.859  1034  1414 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 18:58:20.860  1034  1414 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:20.860  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:20.860  1034  1414 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 18:58:20.860  1034  1414 D ConnectivityService: currentScore = 0, newScore = 20
09-06 18:58:20.860  1034  1414 D ConnectivityService:    accepting network in place of null
09-06 18:58:20.860  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 18:58:20.860  1034  1414 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:20.860  1034  1393 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:20.860  1034  1393 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:20.860  1034  1988 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
09-06 18:58:20.861  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:20.861  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 18:58:20.862  1034  1414 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 18:58:20.862  1034  1414 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 18:58:20.862  1034  1414 D ConnectivityService: sendStickyBroadcast: acti,on=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:58:20.862   312  7350 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 18:58:20.867  1034  1414 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:20.867  1034  1414 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 18:58:20.867  1034  1414 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 18:58:20.868  1034  1414 D ConnectivityService: validation of new default Network = false
09-06 18:58:20.868  1034  1414 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 18:58:20.868  1034  1414 D DSQN    : enableDataServiceNotify 
09-06 18:58:20.868  1034  1414 D DSQN    : start dsqn bin
09-06 18:58:20.868  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 18:58:20.868  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 18:58:20.868  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 18:58:20.868  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 18:58:20.875  1034  1414 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 18:58:20.875  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:20.875  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:20.876  1034  1414 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:20.876  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 18:58:20.862  7351  7351 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:20.862  7351  7351 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:20.888  7351  7351 E DSQN    : DSQN ssw
,09-06 18:58:20.896  1034  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-06 18:58:20.904  1817  7355 I CheckinService: active receiver: enabled
,09-06 18:58:20.915   312  7350 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-06 18:58:20.916  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:20.917  1817  7355 I CheckinService: Preparing to send checkin request
09-06 18:58:20.917  1817  7355 I EventLogService: Accumulating logs since 1473180976986
09-06 18:58:20.917  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.918  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:20.922  1817  7355 W EventLogAggregator: Unknown tag: snet_gcore
09-06 18:58:20.922  1817  7355 W EventLogAggregator: Unknown tag: snet_launch_service
09-06 18:58:20.946   312  7350 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 18:58:20.949  1034  7328 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 18:58:20.950  1034  7328 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 18:58:20.950  1034  7328 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 18:58:20.942  7361  7361 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:20.942  7361  7361 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:20.960   281   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 18:58:20.960   281   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 18:58:20.960   281   372 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:58:20.961  7361  7361 I dhcpcd  : version 5.5.6 starting
09-06 18:58:20.962  7332  7358 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 18:58:20.963  7361  7361 E dhcpcd  : get_duid: m
09-06 18:58:20.963  7361  7361 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 18:58:20.963  7361  7361 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 18:58:20.966   281   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 18:58:20.966   281   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 18:58:20.966   281   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 18:58:20.966  7332  7358 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 18:58:20.969  1817  7355 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-06 18:58:20.977   281   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 18:58:20.977   281   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 18:58:20.977   281   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 18:58:20.979   312   893 D LGDataListener: argv[0]=dsqncommand
09-06 18:58:20.979   312   893 D LGDataListener: argv[1]=wlan0
09-06 18:58:20.979   312   893 D LGDataListener: argv[2]=1
09-06 18:58:20.979   312   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 18:58:20.979  7332  7364 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 18:58:20.979  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
09-06 18:58:20.979  1034  1094 D DSQN    : start to monitor internet connection
,09-06 18:58:20.987   281   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 18:58:20.987   281   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 18:58:20.987   281   372 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 18:58:20.989  7332  7364 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 18:58:21.011  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 16:58:20 GMT], X-Android-Received-Millis=[1473181101011], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181100978]}
09-06 18:58:21.011  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 18:58:21.011  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-06 18:58:21.012  1034  1414 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-06 18:58:21.012  1034  1414 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 18:58:21.012  1034  1414 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:21.012  1034  1414 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:21.012  1034  1414 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,09-06 18:58:21.012  1034  1414 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-06 18:58:21.013  1034  1414 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,09-06 18:58:21.013  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.013  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:21.013  1034  1414 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:21.013  7361  7361 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 18:58:21.013  7361  7361 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 18:58:21.013  7361  7361 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 18:58:21.013  1034  1414 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.013  7361  7361 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 18:58:21.014  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 18:58:21.014  7361  7361 D dhcpcd  : wlan0: sending REQUEST (xid 0x9fc70f0f), next in 3.74 seconds
09-06 18:58:21.014  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.014  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 18:58:21.015  1034  1393 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.015  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 18:58:21.015  1034  1393 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 18:58:21.027  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:21.028  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.029  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.038  7361  7361 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 18:58:21.065  1034  1887 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7373 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-06 18:58:21.068  7361  7361 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 18:58:21.068  7361  7361 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 18:58:21.068  7361  7361 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 18:58:21.068  7361  7361 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 18:58:21.068  7361  7361 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 18:58:21.069  7361  7361 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 18:58:21.069  7361  7361 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 18:58:21.069  7361  7361 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-06 18:58:21.124  7373  7373 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 18:58:21.124  7373  7373 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 18:58:21.154  7373  7373 I MultiDex: VM with version 2.1.0 has multidex support
09-06 18:58:21.154  7373  7373 I MultiDex: install
09-06 18:58:21.154  7373  7373 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 18:58:21.171  7373  7373 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-06 18:58:21.196  7332  7332 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 18:58:21.203  7332  7332 I LibraryLoader: Loading: webviewchromium
09-06 18:58:21.206  7332  7332 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1355-1358)
09-06 18:58:21.206  7332  7332 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 18:58:21.210  7332  7332 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d66aa0c}
09-06 18:58:21.211  7332  7332 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:58:21.211  7332  7332 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 18:58:21.221  7332  7332 I BrowserStartupController: Initializing chromium process, renderers=0
09-06 18:58:21.222  7332  7332 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 18:58:21.232   316  1403 V AudioPolicyService: registerClient() client 0xb558af20, uid 10093
,09-06 18:58:21.234  7332  7332 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 18:58:21.234  7332  7332 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-06 18:58:21.235  7332  7332 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-06 18:58:21.236  7332  7430 W AudioManagerAndroid: Requires BLUETOOTH permission
09-06 18:58:21.245  7332  7332 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 18:58:21.245  7332  7332 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 18:58:21.245  7332  7332 I Adreno-EGL: Build Date: 12/12/14 금
09-06 18:58:21.245  7332  7332 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 18:58:21.245  7332  7332 I Adreno-EGL: Remote Branch: 
09-06 18:58:21.245  7332  7332 I Adreno-EGL: Local Patches: 
09-06 18:58:21.245  7332  7332 I Adreno-EGL: Reconstruct Branch: 
,09-06 18:58:21.313  7332  7332 I NSApplication: Starting up...
,09-06 18:58:21.353  1034  7328 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-06 18:58:21.354  1034  7328 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 18:58:21.354  1034  7328 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 18:58:21.354  1034  7328 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 18:58:21.354  1034  7328 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 18:58:21.354  1034  7328 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 18:58:21.354  1034  7328 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 18:58:21.354  1034  7328 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 18:58:21.355  1034  7328 D DhcpStateMachine: RunningState
09-06 18:58:21.368  1034  1960 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7443 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 18:58:21.369  1034  1960 I ActivityManager: Killing 6195:com.android.vending/u0a44 (adj 15): empty #17
09-06 18:58:21.454  1034  1576 W libprocessgroup: failed to open /acct/uid_10044/pid_6195/cgroup.procs: No such file or directory
,09-06 18:58:21.499  7443  7443 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 18:58:21.502  7463  7463 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-06 18:58:21.541  7463  7463 I dex2oat : dex2oat took 39.334ms (threads: 4)
,09-06 18:58:21.558  7373  7392 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 18:58:21.558  7373  7392 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 18:58:21.558  7373  7392 I Adreno-EGL: Build Date: 12/12/14 금
09-06 18:58:21.558  7373  7392 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 18:58:21.558  7373  7392 I Adreno-EGL: Remote Branch: 
09-06 18:58:21.558  7373  7392 I Adreno-EGL: Local Patches: 
09-06 18:58:21.558  7373  7392 I Adreno-EGL: Reconstruct Branch: 
,09-06 18:58:21.654  1034  1959 I art     : Explicit concurrent mark sweep GC freed 97712(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.706ms total 77.474ms
,09-06 18:58:21.729  1034  1393 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:21.730  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:21.730  1034  1393 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:21.730  1034  1393 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:21.731  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:21.731  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:21.732  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-06 18:58:21.732  1034  1414 D ConnectivityService: identical MTU - not setting
09-06 18:58:21.732  1034  1414 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 18:58:21.732  1034  1414 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 18:58:21.732  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.732  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-06 18:58:21.733  1034  1414 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:21.733  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 18:58:21.762  1034  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 18:58:21.762  1034  1051 D WifiService: setWifiEnabled: false pid=6865, uid=10118
09-06 18:58:21.762  1034  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:58:21.773  1034  1393 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:21.774  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:21.774  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:21.774  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:21.774  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:21.775  1034  1393 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:21.775  1034  1393 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:21.776  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 18:58:21.776  1034  1393 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 18:58:21.776  1034  1393 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:58:21.777  1034  1393 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-06 18:58:21.777  1034  1393 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 18:58:21.777  1034  1393 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 18:58:21.784  1034  1393 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 18:58:21.784  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 18:58:21.784  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.784  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.785  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 18:58:21.785  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 18:58:21.785  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:21.787  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:21.787  1034  7328 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.787   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:58:21.839  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.839  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.839  1034  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@346e6f93
09-06 18:58:21.840  1034  1391 D LGWifiP2pService: P2pDisablingState
09-06 18:58:21.840  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:21.840  1034  1391 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.840  1034  1391 D LGWifiP2pService: p2p socket connection lost
09-06 18:58:21.840  1034  1391 D LGWifiP2pService: P2pDisabledState
09-06 18:58:21.840  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:21.840  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:21.841  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:21.841  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:21.842  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:21.842  1034  1393 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 18:58:21.842  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 18:58:21.842  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.842  1034  1391 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.842  7229  7229 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 18:58:21.843  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 18:58:21.843  1034  1414 D ConnectivityService: ignoring duplicate network state non-change
09-06 18:58:21.843  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-06 18:58:21.848  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-06 18:58:21.848  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:21.848  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:21.848  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:21.848  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 18:58:21.848  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-06 18:58:21.849  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:21.849  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:21.850  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 18:58:21.850  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:21.851  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:21.856  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:21.856  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:58:21.856  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:21.856  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 18:58:21.856  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-06 18:58:21.857  1034  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.857  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 18:58:21.857  1941  1941 D WfdsService: WifiP2pState is changed : false
09-06 18:58:21.858  1941  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 18:58:21.858  1941  2345 D WfdsService: Set the WFDS Monitor: false
,09-06 18:58:21.859  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.859  1034  1556 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.860  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-06 18:58:21.860  1941  2345 D WfdsService: STATE : WfdsDisabledState - enter
09-06 18:58:21.860  1941  7241 D CtrlSupplicant: Received on exit socket, terminate
09-06 18:58:21.860  1941  7241 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 18:58:21.860  1941  7241 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 18:58:21.860  1941  7241 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 18:58:21.861  1941  2346 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 18:58:21.862  1941  2345 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 18:58:21.862  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:21.863  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:21.868  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:21.896  7373  7392 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:21.896  7373  7392 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:21.899   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:58:21.899  1034  1414 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 18:58:21.899  1034  1414 D DSQN    : disableDataServiceNotify
09-06 18:58:21.899  1034  1414 D DSQN    : stop dsqn bin
09-06 18:58:21.901  1034  1393 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 18:58:21.901  1034  1393 D WifiNative-p2p0: TERMINATE: returned true
09-06 18:58:21.901  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:21.901  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:21.901  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:21.902  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-06 18:58:21.902  1034  1393 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 18:58:21.902  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:21.902  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:21.902  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:21.903  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 18:58:21.903  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:21.903  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 18:58:21.904  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.904  1034  1414 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 18:58:21.904  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.904  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:21.904  1034  1414 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:21.905  1034  1414 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 18:58:21.905  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.905  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:21.905  1034  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 18:58:21.905  1034  1414 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 18:58:21.905  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 18:58:21.905  1034  1414 D CSLegacyTypeTracker: S,ending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 18:58:21.905  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:58:21.906  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.908  1034  1414 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:21.908  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:58:21.909  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-06 18:58:21.914  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 18:58:21.914  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:21.914  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 18:58:21.914  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 18:58:21.914  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 18:58:21.914  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 18:58:21.914  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING,
09-06 18:58:21.915  1034  1414 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:21.915  1034  1414 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.915  1034  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 18:58:21.915  1034  1414 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.916  1034  1393 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.916  1034  1393 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:21.917  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 18:58:21.917  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 18:58:21.917  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 18:58:21.917  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 18:58:21.918  1034  1414 D NetworkManagementService: Removing idletimer
09-06 18:58:21.918  1034  1414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:21.918  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:21.918  1034  1414 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-06 18:58:21.918  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 18:58:21.919  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:21.919  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:21.919  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:58:21.919  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:21.919  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:21.920  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:21.920  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:21.937  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 18:58:21.938  6568  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-06 18:58:21.956  2215  2215 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:21.968  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-06 18:58:21.968  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:21.970  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:21.971  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.971  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.975  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 18:58:21.975  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 18:58:21.977  7175  7175 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 18:58:21.984  7175  7175 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ee96b2d
09-06 18:58:21.984  7175  7175 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 18:58:21.984  7175  7175 D AppUp4:CustFacade: isPhone : true
09-06 18:58:21.984  7175  7175 D AppUp4:CustModeStarterReceiver: begin check event
09-06 18:58:21.985  7175  7175 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 18:58:21.986  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:21.987  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.987  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:21.989  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:21.989  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:21.990  7229  7229 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 18:58:21.990  7229  7229 I wpa_supplicant: monitor socket send errors count : 1
09-06 18:58:21.990  7229  7229 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
09-06 18:58:21.991  1034  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 18:58:21.991  1034  7240 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 18:58:21.994  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:21.996  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:22.000  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 18:58:22.001  4343  7495 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 18:58:22.002  4343  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:22.002  4343  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 18:58:22.011  7229  7229 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:58:22.012  7229  7229 W wpa_supplicant: USIM:  scard_deinit function
09-06 18:58:22.012  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 18:58:22.012  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:58:22.013  1034  7240 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:58:22.013  1034  7240 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 18:58:22.013  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:22.013  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:22.013  1034  1393 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=182152
09-06 18:58:22.013  1034  1393 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=182152
09-06 18:58:22.014  1034  1096 D Tethering: InitialState.processMessage what=4
09-06 18:58:22.014  1034  1393 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=182152  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 18:58:22.014  1034  1393 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=182153  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 18:58:22.015  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 18:58:22.018  1034  7328 D DhcpStateMachine: StoppedState
09-06 18:58:22.019  1034  7328 D DhcpStateMachine: StoppedState{ when=-167ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:22.019  7211  7498 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:22.020  7084  7500 W FormManager: Network not available. Please check & try again.
09-06 18:58:22.020  1034  1393 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:22.021  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:22.021  1034  1393 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 18:58:22.021  1034  1393 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 18:58:22.022  3383  3383 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 18:58:22.022  3383  3383 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:22.022  3383  3383 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 18:58:22.025  7084  7501 V FormManager: Network unavailable.
09-06 18:58:22.027  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 18:58:22.027  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 18:58:22.035  7308  7308 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:22
09-06 18:58:22.035  7084  7501 V FormManager: Network unavailable.
09-06 18:58:22.038  7308  7308 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 18:58:22.038  7308  7308 D Weather.Utils: 2 : All the weather widget is gone.
,09-06 18:58:22.040  7308  7308 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 18:58:22.040  7308  7308 D WeatherAncestor: connectivity changed - connection : true
09-06 18:58:22.040  7308  7308 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@288c1df3
09-06 18:58:22.041  7308  7308 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 18:58:22.041  7308  7308 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 18:58:22.041  7308  7308 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 18:58:22.041  7308  7308 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 18:58:22.041  7308  7308 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:22
09-06 18:58:22.058  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 18:58:22.058  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 18:58:22.058  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 18:58:22.058  6995  6995 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 18:58:22.059  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 18:58:22.059  6995  6995 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 18:58:22.059  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 18:58:22.059  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 18:58:22.059  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 18:58:22.059  6995  6995 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 18:58:22.059  6995  6995 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 18:58:22.064  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:22.066  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 18:58:22.067  7084  7503 W FormManager: Network not available. Please check & try again.
,09-06 18:58:22.071  7084  7504 V FormManager: Network unavailable.
,09-06 18:58:22.073  7084  7504 V FormManager: Network unavailable.
09-06 18:58:22.076  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.090  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 18:58:22.092  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 18:58:22.096  7084  7506 W FormManager: Network not available. Please check & try again.
09-06 18:58:22.099  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.104  7084  7507 V FormManager: Network unavailable.
,09-06 18:58:22.107  7084  7507 V FormManager: Network unavailable.
09-06 18:58:22.113  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:22.113  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:22.114  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:22.116  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:22.122  4343  7508 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 18:58:22.125  4343  7509 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:22.125  4343  7509 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 18:58:22.139  7229  7229 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 18:58:22.139  1034  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 18:58:22.139  1034  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 18:58:22.139  1034  7240 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 18:58:22.140  1034  1393 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-06 18:58:22.174  1034  1952 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7510 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 18:58:22.193  7373  7392 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 18:58:22.193  7373  7392 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 18:58:22.193  7373  7392 I Adreno-EGL: Build Date: 12/12/14 금
09-06 18:58:22.193  7373  7392 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 18:58:22.193  7373  7392 I Adreno-EGL: Remote Branch: 
09-06 18:58:22.193  7373  7392 I Adreno-EGL: Local Patches: 
09-06 18:58:22.193  7373  7392 I Adreno-EGL: Reconstruct Branch: 
,09-06 18:58:22.249  1034  1393 D WifiOffDelayIfNotUsed: stopMonitoring
,09-06 18:58:22.250  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:22.250  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:22.250  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 18:58:22.252  1941  1941 D WfdsService: Supplicant Connection state is changed : false
09-06 18:58:22.252  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:22.252  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 18:58:22.252  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 18:58:22.252  1941  2345 D WfdsService: Set the WFDS Monitor: false
09-06 18:58:22.252  1941  2345 D WfdsMonitor: WFDS Monitor is stopped
09-06 18:58:22.255  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 18:58:22.255  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 18:58:22.255  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 18:58:22.256  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:22.256  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:22.257  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:22.260  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:22.303  7373  7392 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 18:58:22.303  7373  7392 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 18:58:22.303  7373  7392 I Adreno-EGL: Build Date: 12/12/14 금
09-06 18:58:22.303  7373  7392 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 18:58:22.303  7373  7392 I Adreno-EGL: Remote Branch: 
09-06 18:58:22.303  7373  7392 I Adreno-EGL: Local Patches: 
09-06 18:58:22.303  7373  7392 I Adreno-EGL: Reconstruct Branch: 
,09-06 18:58:22.326  7510  7510 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 18:58:22.327  7510  7510 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 18:58:22.331  7510  7510 V [BNRBootReceiver]: Boot Receiver Return
09-06 18:58:22.332  7510  7510 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 18:58:22.334  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.340  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.344  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.356  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.356  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.358  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 18:58:22.361  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 18:58:22.364  6995  6995 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 18:58:22.370  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:22.385  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.393  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:22.397   312  7529 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-06 18:58:22.398  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-06 18:58:22.398  1817  7355 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-06 18:58:22.400  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.401  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.402  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 18:58:22.405  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.410  1817  7355 I CheckinService: active receiver: disabled
,09-06 18:58:22.426  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.432  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:22.436  1034  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=550282974, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,09-06 18:58:22.443  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 18:58:22.444  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.444  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:22.448  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.469  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.476  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:22.483  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.483  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.484  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:22.485  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-06 18:58:22.490  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.501  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.517  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:22.527  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.528  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.528  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 18:58:22.536  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.550  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.557  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.565  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 18:58:22.565  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.566  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:22.570  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.579  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.585  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.592  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.593  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.594  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:22.604  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:22.624  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.633  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.645  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.645  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:22.653  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 18:58:22.662  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:22.673  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.683  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.696  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.696  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.698  7044  7044 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 18:58:22.708  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.715  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 18:58:22.735  1034  1405 D WifiService: New client listening to asynchronous messages
,09-06 18:58:22.736  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:22.747  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.755  6774  7157 D UEI.SmartControl: Internal timer expired: 2
09-06 18:58:22.755  6774  7157 D UEI.SmartControl: unbind internal service
09-06 18:58:22.760  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.779  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 18:58:22.780  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.783  7044  7044 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 18:58:22.785  7044  7044 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 18:58:22.786  7044  7044 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 18:58:22.793  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:22.799  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 18:58:22.801  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:22.806  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.816  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.825  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.826  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:22.828  7044  7044 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 18:58:22.830  7044  7044 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 18:58:22.831  7044  7044 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 18:58:22.836  1034  1576 I ActivityManager: Killing 6976:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-06 18:58:22.892  6774  7151 D serial_port: close(fd = 24)
,09-06 18:58:22.901  1034  1952 W libprocessgroup: failed to open /acct/uid_10037/pid_6976/cgroup.procs: No such file or directory
,09-06 18:58:22.901  6774  7151 I UEI.SmartControl: Serial port is closed.
09-06 18:58:22.908  2215  2215 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-06 18:58:22.926  2215  2215 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-06 18:58:22.926  2215  2215 D c       : Getting all permits...
09-06 18:58:22.926  2215  2215 D a       : Opening database...
09-06 18:58:22.931  2215  2215 D a       : Opening database auth.proximity.permit_store...
09-06 18:58:22.932  2215  2215 D a       : Closing database...
,09-06 18:58:22.946  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:22.951  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 18:58:22.952  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:22.952  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:22.955  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.964  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:22.971  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:22.972  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:22.974  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 18:58:22.977  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:22.981  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 18:58:22.981  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:22.981  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:22.985  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:22.993  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:23.001  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:23.002  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:23.004  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 18:58:23.009  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:23.014  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-06 18:58:23.014  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:23.014  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:23.020  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:23.029  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:23.041  7044  7044 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:23.041  7044  7044 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:23.043  7044  7044 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 18:58:23.054  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:23.060  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:58:23.062  7084  7537 W FormManager: Network not available. Please check & try again.
09-06 18:58:23.072  7084  7538 V FormManager: Network unavailable.
09-06 18:58:23.072  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:23.083  7084  7538 V FormManager: Network unavailable.
,09-06 18:58:23.100  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:23.100  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:23.103  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:23.106  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:23.119  7016  7016 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 18:58:23.119  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 18:58:23.119  4343  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:23.119  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 18:58:23.119  4343  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 18:58:23.121  4343  7539 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 18:58:23.127  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 18:58:23.134  7084  7542 W FormManager: Network not available. Please check & try again.
,09-06 18:58:23.143  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:23.144  7084  7543 V FormManager: Network unavailable.
09-06 18:58:23.154  7084  7543 V FormManager: Network unavailable.
,09-06 18:58:23.165  2215  2215 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-06 18:58:23.181  7044  7044 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-06 18:58:23.182  7044  7044 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1790
09-06 18:58:23.182  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=550282974 [*alarm*], flags=0x0
,09-06 18:58:23.733  1034  1393 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:7321205] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 18:58:23.736  1034  1393 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:7321207] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 18:58:23.869  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:23.890  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:23.893  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-06 18:58:23.899  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:23.901  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:23.906  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 18:58:23.913  6568  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 18:58:23.923  5825  5825 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 18:58:23.947  2215  2215 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:23.976  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 18:58:23.976  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:23.976  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 18:58:23.976  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 18:58:23.983  7175  7175 I AppUp4:CustModeStarterReceiver: onReceive
09-06 18:58:23.987  7175  7175 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ee96b2d
09-06 18:58:23.987  7175  7175 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 18:58:23.987  7175  7175 D AppUp4:CustFacade: isPhone : true
09-06 18:58:23.987  7175  7175 D AppUp4:CustModeStarterReceiver: begin check event
09-06 18:58:23.987  7175  7175 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 18:58:23.993  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:23.993  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:23.994  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:24.002  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:24.017  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 18:58:24.037  4343  7562 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 18:58:24.040  4343  7563 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:24.041  4343  7563 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 18:58:24.044  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:24.059  7084  7570 W FormManager: Network not available. Please check & try again.
,09-06 18:58:24.061  7211  7566 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:24.065  3383  3383 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 18:58:24.065  3383  3383 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:24.065  3383  3383 I LgeMiscReceiver: networkInfo.isConnected() = true
09-06 18:58:24.066  3383  3383 D PhoneState: setPdpRejectCasuse : false
09-06 18:58:24.066  7084  7571 V FormManager: Network unavailable.
09-06 18:58:24.068  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 18:58:24.068  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 18:58:24.073  7084  7571 V FormManager: Network unavailable.
,09-06 18:58:24.080  7308  7308 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:24
,09-06 18:58:24.083  7308  7308 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-06 18:58:24.083  7308  7308 D Weather.Utils: 2 : All the weather widget is gone.
09-06 18:58:24.083  7308  7308 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 18:58:24.084  7308  7308 D WeatherAncestor: connectivity changed - connection : true
09-06 18:58:24.084  7308  7308 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@288c1df3
09-06 18:58:24.084  7308  7308 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 18:58:24.085  7308  7308 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 18:58:24.085  7308  7308 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 18:58:24.085  7308  7308 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 18:58:24.085  7308  7308 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:24
09-06 18:58:24.775  1034  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:24.776  1034  1905 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 18:58:24.810  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:24.811  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:24.811  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:24.812  1034  1096 D BluetoothManagerService: Message: 1
09-06 18:58:24.812  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 18:58:24.839  1034  1096 D BluetoothManagerService: Message: 20
09-06 18:58:24.839  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ba36ec7:true
,09-06 18:58:24.844  7121  7121 D BluetoothAdapterState: make
09-06 18:58:24.850  7121  7121 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 18:58:24.850  7121  7121 I bluedroid-qcom: init
09-06 18:58:24.851  7121  7583 I BluetoothAdapterState: Entering OffState
09-06 18:58:24.851  7121  7121 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 18:58:24.852  7121  7121 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 18:58:24.852  7121  7121 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 18:58:24.852  7121  7121 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 18:58:24.852  7121  7121 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 18:58:24.856  7121  7121 I bluedroid-qcom: get_profile_interface socket
09-06 18:58:24.856  7121  7121 I bluedroid-qcom: get_profile_interface map_client
,09-06 18:58:24.860  7121  7587 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 18:58:24.852  7586  7586 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:24.865  7121  7587 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 18:58:24.862  7586  7586 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:24.876  7586  7586 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 18:58:24.876  7586  7586 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 18:58:24.876  7586  7586 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-06 18:58:24.880  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 18:58:24.880  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 18:58:24.884  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 18:58:24.884  1034  1096 D BluetoothManagerService: Message: 40
09-06 18:58:24.884  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 18:58:24.885  7121  7137 I bluedroid-qcom: config_hci_snoop_log
09-06 18:58:24.886  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 18:58:24.886  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 18:58:24.887  7586  7586 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-06 18:58:24.896  7586  7586 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 18:58:24.896  7586  7586 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 18:58:24.900  7121  7583 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-06 18:58:24.902  7121  7587 D BluetoothAdapterProperties: Name is: G3
09-06 18:58:24.902  7121  7583 D BluetoothAdapterProperties: Setting state to 11
09-06 18:58:24.903  7121  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 18:58:24.903  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:24.903  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 18:58:24.904  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 18:58:24.905  7121  7583 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 18:58:24.910  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:24.914  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:58:24.917  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:24.918  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:24.920  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:24.922  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 18:58:24.927  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:58:24.939  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:58:24.942  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:24.943  7121  7583 D BluetoothBondStateMachine: make
09-06 18:58:24.947  1034  1096 D Tethering: MasterInitialState.processMessage what=3
09-06 18:58:24.953  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:24.956  7121  7121 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:24.956  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 18:58:24.957  7121  7121 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:24.957  7121  7121 V BluetoothPbapReceiver: ***********state = 11
09-06 18:58:24.959  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:24.962  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 18:58:24.963  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:24.964  7121  7605 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 18:58:24.964  6568  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 18:58:24.965  7121  7583 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:24.965  7121  7583 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 18:58:24.965  7121  7583 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:24.965  7121  7583 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 18:58:24.966  7121  7583 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 18:58:24.968  5825  5825 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 18:58:24.968  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:24.972  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:25.001  1034  1887 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7607 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-06 18:58:25.009  5825  5825 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 18:58:25.012  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:25.015  7121  7121 D HeadsetService: Received start request. Starting profile...
09-06 18:58:25.016  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.016  7121  7121 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 18:58:25.017  7121  7121 D LGBluetoothHfpAdapter: Version 1.6
09-06 18:58:25.019  7121  7121 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 18:58:25.020  7121  7121 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 18:58:25.021  7121  7121 D HeadsetStateMachine: make
,09-06 18:58:25.024  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:25.025  2215  2215 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.031  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:25.039  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 18:58:25.041  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 18:58:25.042  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.042  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 18:58:25.042  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 18:58:25.045  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:25.050  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:25.051  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 18:58:25.051  7121  7121 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:25.051  7121  7121 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:25.051  7175  7175 I AppUp4:CustModeStarterReceiver: onReceive
09-06 18:58:25.054  7121  7121 D HeadsetStateMachine: max_hf_connections = 1
09-06 18:58:25.054  7121  7121 I bluedroid-qcom: get_profile_interface handsfree
09-06 18:58:25.055  7121  7583 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:25.055  7175  7175 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ee96b2d
09-06 18:58:25.055  7175  7175 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 18:58:25.055  7175  7175 D AppUp4:CustFacade: isPhone : true
09-06 18:58:25.056  7175  7175 D AppUp4:CustModeStarterReceiver: begin check event
09-06 18:58:25.056  7121  7121 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 18:58:25.056  7175  7175 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 18:58:25.056   316  1404 V AudioPolicyService: registerClient() client 0xb57eafe0, uid 1002
09-06 18:58:25.057   316  2162 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 18:58:25.057   316  2162 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 18:58:25.057   316  2162 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 18:58:25.057  7121  7121 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 18:58:25.057   316  1403 V AudioFlinger: registerClient() client 0xb1433088, pid 7121
09-06 18:58:25.058  7121  7121 V ToneGenerator: Create Track: 0xb4928a80
09-06 18:58:25.058  7121  7121 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 18:58:25.058  7121  7121 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 18:58:25.058   316  2165 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 18:58:25.058   316  2165 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 18:58:25.058   316  2165 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 18:58:25.058   316  2165 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 18:58:25.058   316  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:25.058   316  1398 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:25.058  7121  7121 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 18:58:25.058  1604  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:25.058  1604  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:25.058  3383  3398 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:25.058  3383  3398 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:25.058   316  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:25.058   316  1399 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:25.059  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:25.059  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:25.059  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:25.059  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:25.059  1604  2543 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:25.059  1604  2543 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:25.059  7121  7137 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:25.059  7121  7137 V AudioSystem: ioConfigChanged() new output samplingRate 4,8000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 18:58:25.059  3383  3399 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:25.059  3383  3399 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:25.059  7121  7137 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:25.059  7121  7137 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 18:58:25.059   316  1404 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 18:58:25.059  1034  1988 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:25.059   316  2165 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 18:58:25.059  1034  1988 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:25.059   316  2165 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 18:58:25.059   316  2165 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 18:58:25.059   316  2165 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 18:58:25.059  1034  1988 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:25.059  1034  1988 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:25.059  7121  7121 V AudioSystem: getLatency() output 2, latency 50
09-06 18:58:25.059  7121  7121 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 18:58:25.059  7121  7121 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 18:58:25.060   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 18:58:25.060   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 18:58:25.060   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 18:58:25.060   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 18:58:25.060   316  2162 V AudioFlinger: createTrack() lSessionId: 20
09-06 18:58:25.060  7121  7121 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 18:58:25.061   316  2162 V AudioFlinger: acquiring 20 from 7121, for 7121
09-06 18:58:25.061   316  2162 V AudioFlinger:  added new entry for 20
09-06 18:58:25.061  7121  7121 V ToneGenerator: ToneGenerator INIT OK, time: 185213
09-06 18:58:25.061  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.062  7121  7623 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 18:58:25.062  7121  7623 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 18:58:25.062  7121  7623 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 18:58:25.062  7121  7623 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 18:58:25.063   316  1403 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7121
09-06 18:58:25.063   316  1403 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 18:58:25.063   316  1403 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 18:58:25.063   316  1403 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 18:58:25.063   316  1403 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 18:58:25.063   316  1403 V voice   : voice_set_parameters: exit with code(0)
09-06 18:58:25.063   316  1403 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 18:58:25.063   316  1403 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 18:58:25.063   316  1403 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 18:58:25.063   316  1403 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 18:58:25.063   316  1403 V audio_hw_prima,ry: adev_set_parameters: exit with code(0)
09-06 18:58:25.063   316  1403 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 18:58:25.063  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.063  7121  7623 V ToneGenerator: ToneGenerator destructor
09-06 18:58:25.063  7121  7623 V ToneGenerator: stopTone
09-06 18:58:25.063  7121  7623 V ToneGenerator: Delete Track: 0xb4928a80
09-06 18:58:25.064  7121  7623 V AudioTrack: ~AudioTrack, releasing session id from 7121 on behalf of 7121
09-06 18:58:25.064   316   316 V AudioFlinger: releasing 20 from 7121 for 7121
09-06 18:58:25.064   316   316 V AudioFlinger:  decremented refcount to 0
09-06 18:58:25.064   316   316 V AudioFlinger: purging stale effects
09-06 18:58:25.064   316   316 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 18:58:25.064   316   316 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 18:58:25.064   316  1258 V AudioPolicyService: AudioCommandThread() waking up
09-06 18:58:25.064   316  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 18:58:25.064   316  1258 V AudioPolicyManager: releaseOutput() 2
09-06 18:58:25.064   316  1258 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 18:58:25.064   316   316 V AudioFlinger: PlaybackThread::Track destructor
09-06 18:58:25.064   316   316 V AudioFlinger: removeClient_l() pid 7121, calling pid 316
09-06 18:58:25.065  7121  7121 D A2dpService: Received start request. Starting profile...
09-06 18:58:25.065  7121  7121 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 18:58:25.066  7121  7121 V Avrcp   : make
09-06 18:58:25.067  7121  7121 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 18:58:25.067  7121  7121 I bluedroid-qcom: get_profile_interface avrcp
09-06 18:58:25.069  1034  1952 W Process : Unable to open /proc/7626/status
09-06 18:58:25.069  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.069  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:25.070  7121  7583 V LGMDMManager: Create singleton instance
09-06 18:58:25.070  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:25.072  7121  7583 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 18:58:25.072  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:25.074  7121  7121 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 18:58:25.075  7121  7121 E AudioManager: No RCC entry present to update
09-06 18:58:25.075  7121  7121 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 18:58:25.078  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 18:58:25.078  7121  7121 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 18:58:25.079  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 18:58:25.079  7121  7121 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 18:58:25.086  4343  7630 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.086  4343  7630 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 18:58:25.088  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 18:58:25.099  4343  7628 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 18:58:25.130  3383  3383 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 18:58:25.130  3383  3383 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.130  3383  3383 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 18:58:25.135  7211  7632 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:25.137  7084  7633 W FormManager: Network not available. Please check & try again.
09-06 18:58:25.137  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 18:58:25.137  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 18:58:25.139  7084  7634 V FormManager: Network unavailable.
09-06 18:58:25.146  7308  7308 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:25
09-06 18:58:25.146  7084  7634 V FormManager: Network unavailable.
09-06 18:58:25.147  7308  7308 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 18:58:25.147  7308  7308 D Weather.Utils: 2 : All the weather widget is gone.
09-06 18:58:25.147  7308  7308 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 18:58:25.147  7308  7308 D WeatherAncestor: connectivity changed - connection : true
09-06 18:58:25.147  7308  7308 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@288c1df3
09-06 18:58:25.148  7308  7308 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 18:58:25.148  7308  7308 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 18:58:25.148  7308  7308 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 18:58:25.148  7308  7308 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 18:58:25.149  7308  7308 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:25
,09-06 18:58:25.163  7607  7607 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 18:58:25.164  7607  7607 W LG Account v2.2: No ProfileInfo entries
09-06 18:58:25.164  7607  7607 I LG Account v2.2: isEnabled: false
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Country: EU
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Operator: OPEN
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Ranking support: false
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Comfort support: false
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Accessory: true
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Health device: true
09-06 18:58:25.164  7607  7607 I Feature : [Lifetracker]Extra Pedometer: false
09-06 18:58:25.165  7607  7607 I Feature : [Lifetracker]Blood glucose device: false
09-06 18:58:25.165  7607  7607 I Feature : [Lifetracker]Device Number: 3
09-06 18:58:25.165  6568  6568 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 18:58:25.168  6568  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 18:58:25.176  1034  1787 V SIM_STK : Menu title from STK is T-Mobile
09-06 18:58:25.176  1034  1787 V SIM_STK : Menu title from STK is T-Mobile
09-06 18:58:25.178  6995  6995 D BluetoothPermissionRequest: onReceive
,09-06 18:58:25.183  2215  2215 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.184  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 18:58:25.196  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 18:58:25.196  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.196  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 18:58:25.197  7175  7175 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 18:58:25.199  7175  7175 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 18:58:25.201  7175  7175 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ee96b2d
09-06 18:58:25.201  7175  7175 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 18:58:25.201  7175  7175 D AppUp4:CustFacade: isPhone : true
09-06 18:58:25.201  7175  7175 D AppUp4:CustModeStarterReceiver: begin check event
09-06 18:58:25.201  7175  7175 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 18:58:25.203  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.203  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:25.204  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:25.205  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:25.210  7211  7211 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 18:58:25.211  4343  7638 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 18:58:25.213  4343  7639 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.213  4343  7639 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 18:58:25.223  7211  7640 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:25.230  3383  3383 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 18:58:25.230  3383  3383 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:25.230  3383  3383 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 18:58:25.231  1034  1959 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 18:58:25.234  7247  7247 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 18:58:25.235  7247  7247 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 18:58:25.235  7084  7643 W FormManager: Network not available. Please check & try again.
09-06 18:58:25.236  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 18:58:25.239  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 18:58:25.240  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 18:58:25.240  7121  7121 I BluetoothA2dpServiceJni: classInitNative
09-06 18:58:25.240  7121  7121 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:58:25.240  7121  7121 D A2dpStateMachine: make
09-06 18:58:25.241  7121  7121 I bluedroid-qcom: get_profile_interface a2dp
09-06 18:58:25.241  7121  7646 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 18:58:25.243  7121  7121 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:58:25.243  7121  7121 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 18:58:25.243  7308  7308 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:25
09-06 18:58:25.244  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.244  7121  7121 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 18:58:25.244  7308  7308 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 18:58:25.244  7308  7308 D Weather.Utils: 2 : All the weather widget is gone.
09-06 18:58:25.244  7084  7644 V FormManager: Network unavailable.
09-06 18:58:25.245  7308  7308 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 18:58:25.245  7308  7308 D WeatherAncestor: connectivity changed - connection : true
09-06 18:58:25.245  7308  7308 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@288c1df3
09-06 18:58:25.245  7121  7645 D A2dpStateMachine: Enter Disconnected: -2
09-06 18:58:25.245  7121  7121 D HidService: Received start request. Starting profile...
09-06 18:58:25.245  7121  7121 I bluedroid-qcom: get_profile_interface hidhost
09-06 18:58:25.245  7308  7308 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 18:58:25.245  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.245  7308  7308 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 18:58:25.245  7308  7308 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 18:58:25.245  7308  7308 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 18:58:25.245  7308  7308 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:25
09-06 18:58:25.246  7121  7121 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 18:58:25.248  7121  7121 D HealthService: Received start request. Starting profile...
09-06 18:58:25.249  7121  7121 I bluedroid-qcom: get_profile_interface health
09-06 18:58:25.249  7121  7121 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 18:58:25.249  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.250  7121  7121 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 18:58:25.250  7084  7644 V FormManager: Network unavailable.
09-06 18:58:25.251  7121  7121 D PanService: Received start request. Starting profile...
09-06 18:58:25.251  7121  7121 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 18:58:25.251  7121  7121 I bluedroid-qcom: get_profile_interface pan
,09-06 18:58:25.256  7121  7121 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 18:58:25.256  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.257  7121  7121 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 18:58:25.261  7121  7121 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:58:25.261  7121  7121 D BtGatt.GattService: Received start request. Starting profile...
09-06 18:58:25.261  7121  7121 D BtGatt.GattService: start()
09-06 18:58:25.261  7121  7121 I bluedroid-qcom: get_profile_interface gatt
,09-06 18:58:25.261  7121  7121 D BtGatt.AdvertiseManager: advertise manager created
09-06 18:58:25.265  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.265  7121  7121 D HeadsetStateMachine: Proxy object connected
09-06 18:58:25.266  7121  7121 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 18:58:25.266  7121  7121 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-06 18:58:25.267  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.267  7121  7121 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 18:58:25.268  7121  7121 V BluetoothMapService: BluetoothMapBinder()
09-06 18:58:25.268  7121  7121 D BluetoothMapService: Received start request. Starting profile...
09-06 18:58:25.268  7121  7121 D BluetoothMapService: start()
09-06 18:58:25.270  7121  7121 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 18:58:25.270  7121  7121 D BluetoothMapEmailAppObserver: createReceiver()
09-06 18:58:25.271  7121  7121 D BluetoothMapEmailAppObserver: initObservers()
09-06 18:58:25.271  7121  7121 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 18:58:25.276  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.277  7121  7623 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-06 18:58:25.279  7121  7623 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 18:58:25.279  7121  7623 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 18:58:25.280  7121  7121 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:25.282  7121  7121 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:25.284  7121  7121 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:25.285  7121  7121 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:25.285  7121  7121 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 18:58:25.287  7121  7121 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:25.289  7121  7121 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 18:58:25.289  7121  7121 V BluetoothMapService: Handler(): got msg=1
,09-06 18:58:25.290  7121  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 18:58:25.290  7121  7583 I bluedroid-qcom: enable
09-06 18:58:25.290  7121  7653 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 18:58:25.290  7121  7653 I bt-btu  : btu_task pending for preload complete event
09-06 18:58:25.290  7121  7583 I bt_hci_bdroid: init
09-06 18:58:25.291  7121  7121 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:25.291  7121  7583 I bt_vendor: bt-vendor : init
09-06 18:58:25.291  7121  7583 I bt_vendor: bt-vendor : get_bt_soc_type
,09-06 18:58:25.291  7121  7583 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 18:58:25.291  7121  7583 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 18:58:25.291  7121  7583 D bt_userial_mct: userial_init
09-06 18:58:25.292  7121  7583 D bt_hci_bdroid: set_power 1
09-06 18:58:25.292  7121  7583 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 18:58:25.292  7121  7583 I bt_vendor: Starting hciattach daemon
09-06 18:58:25.292  7121  7583 I bt_vendor: try to set true
09-06 18:58:25.292  7121  7121 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:25.292  7121  7121 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:25.292  7121  7121 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:25.292  7121  7121 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:25.292  7121  7121 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 18:58:25.282  7656  7656 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:25.282  7656  7656 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:25.306  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 18:58:25.397  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 18:58:25.416  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 18:58:25.467  7666  7666 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 18:58:25.491  7667  7667 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 18:58:25.504  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 18:58:25.517  7669  7669 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 18:58:25.555  7671  7671 I libmdmdetect: ESOC framework not supported
,09-06 18:58:25.556  7671  7671 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 18:58:25.565  7671  7671 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 18:58:25.565  7671  7671 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 18:58:25.565  7671  7671 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 18:58:25.566  7671  7671 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 18:58:25.566  7671  7671 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 18:58:25.566  7671  7671 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 18:58:25.566  7671  7671 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 18:58:25.608  7671  7675 E QC-QMI  : qmi_client [7671] 14: failed to locate client data
,09-06 18:58:25.609   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 18:58:25.609   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-06 18:58:25.662  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 18:58:25.681  7683  7683 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 18:58:25.699  7121  7583 I bt_vendor: bluetooth satus is on
09-06 18:58:25.699  7121  7583 D bt_hci_bdroid: preload
,09-06 18:58:25.703  7121  7655 D bt_userial_mct: userial_open(port:0)
09-06 18:58:25.703  7121  7655 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 18:58:25.707  7121  7655 I bt_vendor: Done intiailizing UART
09-06 18:58:25.708  7121  7655 I bt_vendor: Done intiailizing UART
09-06 18:58:25.708  7121  7655 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 18:58:25.708  7121  7655 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 18:58:25.708  7121  7653 I bt-btu  : btu_task received preload complete event
09-06 18:58:25.708  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 18:58:25.709  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 18:58:25.711  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 18:58:25.718  7121  7685 D bt_userial_mct: Entering userial_read_thread()
,09-06 18:58:25.722  7121  7653 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 18:58:25.722  7121  7653 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 18:58:25.723  7121  7653 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 18:58:25.778  7121  7653 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-06 18:58:25.778  7121  7653 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa015c061 
09-06 18:58:25.778  7121  7653 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa015c061 
,09-06 18:58:25.795  7121  7587 E bt-btif : Calling BTA_HhEnable
09-06 18:58:25.795  7121  7587 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 18:58:25.795  7121  7587 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 18:58:25.798  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 18:58:25.798  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 18:58:25.798  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 18:58:25.799  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 18:58:25.799  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 18:58:25.799  7121  7587 D BluetoothAdapterProperties: Name is: G3
09-06 18:58:25.800  7121  7587 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:58:25.800  7121  7587 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 18:58:25.800  7121  7587 D bt_hci_bdroid: postload
09-06 18:58:25.801  7121  7655 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:25.801  7121  7587 D bte_conf: Device ID record 1 : primary
09-06 18:58:25.801  7121  7587 D bte_conf:   vendorId            = 00c4
09-06 18:58:25.801  7121  7587 D bte_conf:   vendorIdSource      = 0001
09-06 18:58:25.801  7121  7587 D bte_conf:   product             = 13a1
09-06 18:58:25.801  7121  7587 D bte_conf:   version             = 1000
09-06 18:58:25.801  7121  7587 D bte_conf:   clientExecutableURL = 
09-06 18:58:25.801  7121  7587 D bte_conf:   serviceDescription  = 
09-06 18:58:25.801  7121  7587 D bte_conf:   documentationURL    = 
09-06 18:58:25.801  7121  7587 D bte_conf: bte_load_did_conf no section named DID2.
09-06 18:58:25.802  7121  7653 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 18:58:25.803  7121  7655 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:25.803  7121  7655 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:25.803  7121  7655 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:25.805  7121  7655 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:25.792  7687  7687 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:25.807  7121  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 18:58:25.807  7121  7583 D BluetoothAdapterProperties: ScanMode =  20
09-06 18:58:25.807  7121  7583 D BluetoothAdapterProperties: State =  11
09-06 18:58:25.807  7121  7583 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,09-06 18:58:25.812  7121  7583 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 18:58:25.812  7121  7583 D BluetoothAdapterProperties: Setting state to 12
09-06 18:58:25.812  7121  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 18:58:25.813  7121  7685 E bt_mct  : hci lib postload completed
09-06 18:58:25.802  7687  7687 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:25.814  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:25.814  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 18:58:25.814  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-06 18:58:25.814  7121  7583 I BluetoothAdapterState: Entering On State
09-06 18:58:25.819  7121  7587 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 18:58:25.819  7121  7587 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 18:58:25.821  7121  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:25.821  7121  7653 W bt-smp  : Plain text(LSB ~ MSB) = 89 7a 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-06 18:58:25.825  7121  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 57 be f1 96 e2 1d a2 78 cc ec 12 24 86 d6 62 91 
09-06 18:58:25.826  7121  7653 W bt-btm  : Stopping oneshot timer
09-06 18:58:25.835  1853  4450 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 18:58:25.840  7121  7583 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 18:58:25.840  7121  7583 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 18:58:25.841  7121  7583 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 18:58:25.844  7121  7587 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 18:58:25.845  7121  7587 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 18:58:25.846  7121  7583 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 18:58:25.852  1853  1853 D BluetoothHeadset: Proxy object connected
,09-06 18:58:25.854  7121  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:25.855  7121  7653 W bt-smp  : Plain text(LSB ~ MSB) = ca a7 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:25.855  7121  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b d5 65 38 f3 2a c6 18 bc 27 61 50 c7 dd c7 b4 
09-06 18:58:25.855  7121  7653 W bt-btm  : Stopping oneshot timer
09-06 18:58:25.855  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:25.856  1034  1034 D BluetoothHeadset: Proxy object connected
09-06 18:58:25.861  6995  7011 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 18:58:25.866  7121  7583 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-06 18:58:25.869  7121  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:25.869  7121  7653 W bt-smp  : Plain text(LSB ~ MSB) = a0 bd 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:25.869  7121  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = c3 cf e1 8b f1 55 6f 32 5e 0e 61 e9 84 d5 c6 8d 
09-06 18:58:25.869  7121  7653 W bt-btm  : Stopping oneshot timer
09-06 18:58:25.870  6995  7012 D BluetoothMap: onBluetoothStateChange: up=true
09-06 18:58:25.886  7121  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:25.886  7121  7653 W bt-smp  : Plain text(LSB ~ MSB) = 2c 4f 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:25.886  7121  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a c0 18 e6 d0 1f e4 1a bc 72 96 7b 03 0b 05 d1 
,09-06 18:58:25.891  7121  7653 W bt-btm  : Stopping oneshot timer
09-06 18:58:25.893  6995  7011 D BluetoothPan: onBluetoothStateChange on: true
09-06 18:58:25.893  6995  7011 D BluetoothPan: onBluetoothStateChange call bindService
09-06 18:58:25.894  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 18:58:25.894  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:25.902  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:58:25.906  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:25.908  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:25.909  7121  7653 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:25.909  7121  7653 W bt-smp  : Plain text(LSB ~ MSB) = b8 3f 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:25.909  7121  7653 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e b4 dc 31 6d 4a 27 21 9c bb 42 d4 61 f2 04 90 
09-06 18:58:25.909  7121  7653 W bt-btm  : Stopping oneshot timer
,09-06 18:58:25.910  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:25.910  6995  6995 D BluetoothMap: Proxy object connected
09-06 18:58:25.910  6995  6995 D MapProfile: Bluetooth service connected
09-06 18:58:25.910  6995  6995 D BluetoothMap: getConnectedDevices()
09-06 18:58:25.911  7121  7136 V BluetoothMapService: getConnectedDevices()
09-06 18:58:25.912  7700  7700 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 18:58:25.915  1853  4451 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:25.918  1853  1853 D BluetoothHeadset: Proxy object connected
09-06 18:58:25.918  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 18:58:25.920  1853  1853 D BluetoothHeadset: Proxy object connected
09-06 18:58:25.920  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 18:58:25.922  6995  7701 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 18:58:25.915  6995  6995 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:58:25.922  6995  6995 D PanProfile: Bluetooth service connected
09-06 18:58:25.922  1034  1034 D BluetoothA2dp: Proxy object connected
09-06 18:58:25.924  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 18:58:25.924  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 18:58:25.928  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:25.928  1941  2145 D LGBluetoothAPIService: Message: 1
09-06 18:58:25.928  1941  2145 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 18:58:25.929  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-06 18:58:25.934  6995  6995 D BluetoothInputDevice: Proxy object connected
09-06 18:58:25.934  6995  6995 D HidProfile: Bluetooth service connected
09-06 18:58:25.935  6865  6865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 18:58:25.940  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 18:58:25.940  1034  1096 D BluetoothManagerService: Message: 40
09-06 18:58:25.940  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 18:58:25.941  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:25.942  7121  7121 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:25.942  7121  7121 D BluetoothMapService: STATE_ON
09-06 18:58:25.942  1941  2145 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-06 18:58:25.943  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:25.944  7121  7121 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 18:58:25.944  7121  7121 D LGBluetoothAPIServer: [BTUI] onBind()
,09-06 18:58:25.945  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 18:58:25.945  1941  2145 D LGBluetoothAPIService: Message: 100
09-06 18:58:25.945  1941  2145 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 18:58:25.946  6995  6995 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 18:58:25.948  1034  1096 D BluetoothManagerService: Message: 30
09-06 18:58:25.951  6995  6995 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-06 18:58:25.953  1034  1096 D BluetoothManagerService: Message: 30
09-06 18:58:25.958  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 18:58:25.959  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:25.959  7121  7121 V BluetoothPbapService: Pbap Service onCreate
09-06 18:58:25.960  7121  7121 V BluetoothPbapService: Starting PBAP service
09-06 18:58:25.964  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 18:58:25.964  7121  7121 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 18:58:25.964  7121  7121 V BluetoothPbapService: Pbap Service onBind
09-06 18:58:25.967  6995  6995 D BluetoothA2dp: Proxy object connected
09-06 18:58:25.967  6995  6995 D A2dpProfile: Bluetooth service connected
09-06 18:58:25.969  7121  7121 V BluetoothMapService: Handler(): got msg=1
09-06 18:58:25.970  6995  6995 D BluetoothHeadset: Proxy object connected
09-06 18:58:25.970  6995  6995 D HeadsetProfile: Bluetooth service connected
09-06 18:58:25.971  7121  7121 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 18:58:25.971  7121  7121 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:25.972  7121  7121 V BluetoothPbapService: state: 12
09-06 18:58:25.972  7121  7121 V BluetoothPbapService: Handler(): got msg=1
09-06 18:58:25.972  7121  7121 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 18:58:25.973  7121  7711 D BluetoothMapMasInstance: MAS initSocket()
09-06 18:58:25.973  7121  7711 D BluetoothMapMasInstance:   masId = 00
09-06 18:58:25.973  7121  7711 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 18:58:25.973  7121  7711 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 18:58:25.973  7121  7711 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 18:58:25.975  7121  7121 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:25.975  7121  7121 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:25.975  7121  7121 V BluetoothPbapReceiver: ***********state = 12
09-06 18:58:25.975  7121  7713 V BluetoothPbapService: Pbap Service initSocket
,09-06 18:58:25.976  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:25.976  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:25.979  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 18:58:25.979  6995  6995 D DockEventReceiver: finishStartingService: stopping service
09-06 18:58:25.980  6995  6995 D BluetoothPbap: Proxy object connected
09-06 18:58:25.981  6995  6995 D PbapServerProfile: Bluetooth service connected
,09-06 18:58:25.981  7121  7713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:25.981  7121  7711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:25.982  7332  7360 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-06 18:58:25.983  2215  2215 D c       : Getting all permits...
09-06 18:58:25.983  2215  2215 D a       : Opening database...
09-06 18:58:25.984  7121  7711 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 18:58:25.985  7121  7711 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 18:58:25.985  7121  7711 D BluetoothMapMasInstance: Accepting socket connection...
09-06 18:58:25.985  7121  7587 D BluetoothAdapterProperties: Scan Mode:21
09-06 18:58:25.985  7121  7587 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 18:58:25.986  7121  7713 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 18:58:25.986  7121  7713 V BluetoothPbapService: Succeed to create listening socket 
09-06 18:58:25.986  7121  7713 V BluetoothPbapService: Accepting socket connection...
09-06 18:58:25.987  2215  2215 D a       : Opening database auth.proximity.permit_store...
09-06 18:58:25.987  2215  2215 D a       : Closing database...
,09-06 18:58:25.991  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:25.992  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:25.997  6995  6995 D BluetoothPermissionRequest: onReceive
09-06 18:58:25.999  6995  6995 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-06 18:58:26.000  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 18:58:26.004  7121  7121 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 18:58:26.005  7121  7121 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 18:58:26.012  7121  7121 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 18:58:26.049  7121  7121 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 18:58:26.049  7121  7121 V BtOppService: onCreate
,09-06 18:58:26.054  7121  7121 V BluetoothOppNotification: send message
09-06 18:58:26.058  7121  7121 V BtOppService: Starting RfcommListener
09-06 18:58:26.068  7121  7121 D BluetoothOppPreference: Dumping Names:  
09-06 18:58:26.068  7121  7121 D BluetoothOppPreference: {}
09-06 18:58:26.068  7121  7121 D BluetoothOppPreference: Dumping Channels:  
09-06 18:58:26.068  7121  7121 D BluetoothOppPreference: {}
,09-06 18:58:26.073  7121  7121 V BtOppService: onStartCommand
09-06 18:58:26.077  7121  7722 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 18:58:26.080  7121  7121 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:26.081  7121  7121 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 18:58:26.085  7121  7121 V BluetoothOppNotification: new notify threadi!
,09-06 18:58:26.087  7121  7121 V BluetoothOppNotification: send delay message
09-06 18:58:26.088  7121  7121 V BtOppService: start RfcommListener
09-06 18:58:26.090  7121  7722 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 18:58:26.091  7121  7719 V BtOppService: Deleted complete outbound shares, number =  0
09-06 18:58:26.092  7121  7722 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c581e6c on behalf of 
09-06 18:58:26.094  7121  7723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 18:58:26.094  7121  7722 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 18:58:26.095  7121  7719 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 18:58:26.096  7121  7719 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 18:58:26.097  7121  7723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e520c35 on behalf of 
09-06 18:58:26.097  7121  7121 V BtOppService: RfcommListener started
09-06 18:58:26.098  7121  7724 V BtOppRfcommListener: Starting RFCOMM listener....
,09-06 18:58:26.099  1034  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:26.099  7121  7723 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 18:58:26.100  7121  7719 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ea588ca on behalf of 
09-06 18:58:26.101  7121  7724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:26.102  7121  7724 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-06 18:58:26.102  7121  7724 V BtOppRfcommListener: Started RFCOMM listener....
09-06 18:58:26.102  7121  7724 I BtOppRfcommListener: Accept thread started.
09-06 18:58:26.103  7121  7724 V BtOppRfcommListener: Accepting connection...
09-06 18:58:26.103  7121  7723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 18:58:26.105  7121  7723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3264fa3b on behalf of 
09-06 18:58:26.109  7121  7723 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 18:58:26.110  7121  7723 V BluetoothOppNotification: outbound notification was removed.
09-06 18:58:26.111  7121  7723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-06 18:58:26.112  7121  7723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ddeb558 on behalf of 
09-06 18:58:26.114  7121  7723 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 18:58:26.115  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:26.116  7121  7121 V BluetoothFtpService: Ftp Service onCreate
09-06 18:58:26.116  7121  7121 I BluetoothFtpService: Ftp Service onCreate
09-06 18:58:26.116  7121  7121 V BluetoothFtpService: Ftp Service onStartCommand
09-06 18:58:26.116  7121  7121 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:26.116  7121  7121 V BluetoothFtpService: Starting Listening on sockets
09-06 18:58:26.117  7121  7121 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:26.117  7121  7121 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:26.117  7121  7121 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:26.117  7121  7121 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:26.117  7121  7121 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 18:58:26.117  7121  7121 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 18:58:26.118  7121  7723 V BluetoothOppNotification: inbound notification was removed.
09-06 18:58:26.118  7121  7723 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 18:58:26.120  7121  7121 V BtOppService: ContentObserver received notification
09-06 18:58:26.120  7121  7121 V BtOppService: ContentObserver received notification
09-06 18:58:26.121  7121  7121 V BluetoothFtpService: Handler(): got msg=1
09-06 18:58:26.121  7121  7723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1efb6796 on behalf of 
09-06 18:58:26.121  7121  7121 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 18:58:26.121  7121  7121 V BluetoothFtpService: Ftp Service initSocket
,09-06 18:58:26.124  7121  7725 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 18:58:26.125  7121  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 18:58:26.127  7121  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e9eff17 on behalf of 
09-06 18:58:26.128  1034  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:26.129  7121  7121 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:26.130  7121  7725 V BluetoothOppNotification: update too frequent, put in queue
09-06 18:58:26.132  7121  7725 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-06 18:58:26.133  7121  7121 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 18:58:26.135  7121  7726 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-06 18:58:26.150  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:26.150  7121  7121 V BluetoothSapService: Sap Service onCreate
,09-06 18:58:26.152  7121  7121 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:26.152  7121  7121 V BluetoothSapService: state: 12
09-06 18:58:26.152  7121  7121 V BluetoothSapService: Starting SAP server process
09-06 18:58:26.154  7121  7121 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-06 18:58:26.142  7727  7727 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:26.142  7727  7727 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:26.156  7121  7728 V BluetoothSapService: Sap Service initRfcommSocket
09-06 18:58:26.156  1034  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:26.157  7121  7728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:26.158  7121  7728 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 18:58:26.159  7121  7728 V BluetoothSapService: Succeed to create listening socket 
09-06 18:58:26.159  7121  7728 V BluetoothSapService: Accepting socket connection...
09-06 18:58:26.178  7727  7727 V BT_SAP  : Event pipe created
09-06 18:58:26.178  7727  7727 V BT_SAP  : create_server_socket qcom.sap.server
09-06 18:58:26.178  7727  7727 V BT_SAP  : created socket fd 6
,09-06 18:58:26.846  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:26.846  1034  1391 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:26.906  1034  1393 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 18:58:26.907  1034  1393 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 18:58:26.954  1034  1758 I ActivityManager: Killing 7510:com.lge.bnr/1000 (adj 15): empty #17
,09-06 18:58:26.989  1034  1787 W libprocessgroup: failed to open /acct/uid_1000/pid_7510/cgroup.procs: No such file or directory
,09-06 18:58:27.089  7121  7121 V BluetoothOppNotification: new notify threadi!
,09-06 18:58:27.090  7121  7121 V BluetoothOppNotification: send delay message
,09-06 18:58:27.103  7121  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 18:58:27.107  7121  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c0a75b3 on behalf of 
09-06 18:58:27.112  7121  7738 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-06 18:58:27.120  7121  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 18:58:27.121  7121  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bc2d770 on behalf of 
09-06 18:58:27.122  7121  7738 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 18:58:27.127  7121  7738 V BluetoothOppNotification: outbound notification was removed.
,09-06 18:58:27.127  7121  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 18:58:27.129  7121  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@203a0ae9 on behalf of 
09-06 18:58:27.129  7121  7738 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 18:58:27.131  7121  7738 V BluetoothOppNotification: inbound notification was removed.
09-06 18:58:27.131  7121  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 18:58:27.132  7121  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13fd36e on behalf of 
,09-06 18:58:27.384  1034  1952 I ActivityManager: Killing 7016:com.lge.sync/1000 (adj 15): empty #17
,09-06 18:58:27.417  1034  1405 D WifiService: Client connection lost with reason: 4
,09-06 18:58:27.429  1034  1758 W libprocessgroup: failed to open /acct/uid_1000/pid_7016/cgroup.procs: No such file or directory
,09-06 18:58:27.831  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:27.831  1034  1959 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3300c403 mBinding = false
,09-06 18:58:27.865  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:27.865  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:27.865  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:27.866  1034  1096 D BluetoothManagerService: Message: 2
09-06 18:58:27.867  1034  1096 D BluetoothManagerService: Sending off request.
09-06 18:58:27.868  7121  7600 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 18:58:27.868  7121  7583 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 18:58:27.869  7121  7583 D BluetoothAdapterProperties: Setting state to 13
09-06 18:58:27.869  7121  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 18:58:27.869  7121  7583 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 18:58:27.869  7121  7583 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 18:58:27.871  7121  7587 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:58:27.873  7121  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 18:58:27.874  7121  7711 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-06 18:58:27.879  7121  7713 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:27.879  7121  7724 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:27.880  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 18:58:27.880  7121  7653 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 18:58:27.882  7121  7583 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 18:58:27.888  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 18:58:27.888  7121  7653 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-06 18:58:27.899  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:27.899  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:27.901  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:27.901  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:27.905  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:27.905  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:58:27.908  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:58:27.908  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:27.910  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:27.910  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 18:58:27.910  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 18:58:27.912  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:27.915  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:27.920  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:27.924  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:27.927  7121  7121 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:27.927  7121  7121 D BluetoothMapService: STATE_TURNING_OFF
09-06 18:58:27.927  7121  7121 V BluetoothMapService: Handler(): got msg=4
09-06 18:58:27.927  7121  7121 D BluetoothMapService: MAP Service closeService in
09-06 18:58:27.927  7121  7121 D BluetoothMapMasInstance: MAP Service shutdown
09-06 18:58:27.928  7121  7121 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 18:58:27.928  7121  7121 V BluetoothMapService: MAP Service closeService out
09-06 18:58:27.929  7121  7121 V BtOppService: Receiver DISABLED_ACTION 
09-06 18:58:27.929  7121  7121 I BtOppRfcommListener: stopping Accept Thread
09-06 18:58:27.929  7121  7121 V BtOppRfcommListener: close mBtServerSocket
09-06 18:58:27.930  7121  7724 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 18:58:27.930  7121  7121 V BtOppRfcommListener: waiting for thread to terminate
09-06 18:58:27.930  7121  7121 V BtOppRfcommListener: done waiting for thread to terminate
09-06 18:58:27.933  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-06 18:58:27.939  7121  7726 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:58:27.945  7121  7728 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 18:58:27.952  7121  7121 V BtOppService: onDestroy
09-06 18:58:27.960  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 18:58:27.964  7121  7121 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 18:58:27.971  7121  7121 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:27.971  7121  7121 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:27.971  7121  7121 V BluetoothPbapReceiver: ***********state = 13
09-06 18:58:27.972  7121  7121 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-06 18:58:27.976  7121  7121 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:27.976  7121  7121 V BluetoothPbapService: state: 13
09-06 18:58:27.976  7121  7121 V BluetoothPbapService: Pbap Service closeService in
09-06 18:58:27.978  7121  7121 V BluetoothPbapService: successfully stopped pbap service
09-06 18:58:27.978  7121  7121 V BluetoothPbapService: Pbap Service closeService out
09-06 18:58:27.979  7121  7121 V BluetoothPbapService: Pbap Service onDestroy
09-06 18:58:27.979  7121  7121 V BluetoothPbapService: Pbap Service closeService in
09-06 18:58:27.979  7121  7121 V BluetoothPbapService: Pbap Service closeService out
09-06 18:58:27.979  7121  7121 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 18:58:27.984  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:58:27.995  6995  6995 D DockEventReceiver: finishStartingService: stopping service
09-06 18:58:28.002  6995  6995 D BluetoothPbap: Proxy object disconnected
09-06 18:58:28.002  6995  6995 D PbapServerProfile: Bluetooth service disconnected
,09-06 18:58:28.022  6995  6995 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 18:58:28.029  6995  6995 D BluetoothPermissionRequest: onReceive
09-06 18:58:28.029  6995  6995 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 18:58:28.037  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 18:58:28.044  7121  7121 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 18:58:28.044  7121  7121 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-06 18:58:28.044  7121  7121 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 18:58:28.050  7121  7121 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:28.050  7121  7121 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-06 18:58:28.053  7121  7121 V BluetoothFtpService: Ftp Service onStartCommand
09-06 18:58:28.053  7121  7121 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:28.053  7121  7121 V BluetoothFtpService: Ftp Service closeService
09-06 18:58:28.053  7121  7121 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 18:58:28.057  7121  7121 V BluetoothFtpService: successfully stopped ftp service
09-06 18:58:28.058  7121  7121 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:28.058  7121  7121 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:28.058  7121  7121 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:28.058  7121  7121 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:58:28.058  7121  7121 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 18:58:28.058  7121  7121 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 18:58:28.059  7121  7121 V BluetoothFtpService: Ftp Service onDestroy
09-06 18:58:28.059  7121  7121 V BluetoothFtpService: Ftp Service closeService
09-06 18:58:28.060  7121  7121 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:28.060  7121  7121 V BluetoothSapService: state: 13
09-06 18:58:28.060  7121  7121 V BluetoothSapService: Stopping SAP server process
09-06 18:58:28.061  7121  7121 V BluetoothSapService: Sap Service closeSapService in
09-06 18:58:28.061  7121  7121 V BluetoothSapService: Close listen Socket : 
09-06 18:58:28.062  7121  7121 V BluetoothSapService: Close rfcomm Socket : 
09-06 18:58:28.062  7121  7121 V BluetoothSapService: Close sapd  Socket : 
09-06 18:58:28.064  7121  7121 V BluetoothSapService: Sap Service closeSapService out
09-06 18:58:28.064  7121  7121 V BluetoothSapService: Sap Service onDestroy
09-06 18:58:28.064  7121  7121 V BluetoothSapService: Sap Service closeSapService in
09-06 18:58:28.064  7121  7121 V BluetoothSapService: Close listen Socket : 
09-06 18:58:28.064  7121  7121 V BluetoothSapService: Close rfcomm Socket : 
09-06 18:58:28.064  7121  7121 V BluetoothSapService: Close sapd  Socket : 
09-06 18:58:28.065  7121  7121 V BluetoothSapService: Sap Service closeSapService out
,09-06 18:58:28.644  1034  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{4fc49b9 type 2 when 188775 com.google.android.gms} when 188775
,09-06 18:58:28.656   312  7768 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 18:58:28.657  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-06 18:58:28.791  7121  7587 D bt_hci_bdroid: cleanup
,09-06 18:58:28.797  7121  7655 I bt_lpm  : LPM is already off!!!
,09-06 18:58:28.798  7121  7685 I bt_userial_mct: exiting userial_read_thread
,09-06 18:58:28.798  7121  7685 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 18:58:28.799  7121  7653 W bt-btif : ag scb idx 1 not allocated
09-06 18:58:28.800  7121  7653 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 18:58:28.800  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:58:28.801  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 18:58:28.801  7121  7653 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:58:28.801  7121  7653 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 18:58:28.801  7121  7653 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:58:28.801  7121  7653 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 18:58:28.804  7121  7587 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0,
09-06 18:58:28.804  7121  7655 I bt_vendor: hw_epilog_process
09-06 18:58:28.809  7121  7587 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 18:58:28.809  7121  7587 D bt_userial_mct: userial_close
09-06 18:58:28.809  7121  7587 E bt_userial_mct: pthread_join() FAILED result:3
09-06 18:58:28.809  7121  7587 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 18:58:28.829  7121  7587 D bt_hci_bdroid: set_power 0
09-06 18:58:28.829  7121  7587 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 18:58:28.830  7121  7587 I bt_vendor: bluetooth satus is on
09-06 18:58:28.830  7121  7587 I bt_vendor: bt-vendor : resetting BT status
09-06 18:58:28.830  7121  7587 I bt_vendor: Starting hciattach daemon
09-06 18:58:28.830  7121  7587 I bt_vendor: try to set false
09-06 18:58:28.832  7121  7587 I bt_vendor: Starting hciattach daemon
09-06 18:58:28.832  7121  7587 I bt_vendor: try to set false
,09-06 18:58:28.835  7121  7587 I bt_vendor: cleanup
09-06 18:58:28.836  7121  7653 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 18:58:28.836  7121  7587 I GKI_LINUX: GKI_exit_task 0 done
09-06 18:58:28.836  7121  7587 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 18:58:28.838  7121  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 18:58:28.845  7121  7583 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 18:58:28.849  7121  7121 D HeadsetService: Received stop request...Stopping profile...
09-06 18:58:28.851  7121  7121 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 18:58:28.851  7121  7121 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:58:28.851  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:28.851  7121  7623 D HeadsetStateMachine: Exit Disconnected: -1
09-06 18:58:28.854  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:28.854  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:28.854  1853  1853 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:28.855  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:28.855  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 18:58:28.856  7121  7121 D A2dpService: Received stop request...Stopping profile...
09-06 18:58:28.857  7121  7645 D A2dpStateMachine: Exit Disconnected: -1
09-06 18:58:28.860  7121  7121 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-06 18:58:28.864  7121  7121 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 18:58:28.864  7121  7121 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:58:28.864  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:28.866  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-06 18:58:28.866  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 18:58:28.867  7121  7121 D HidService: Received stop request...Stopping profile...
09-06 18:58:28.867  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:28.869  7121  7121 D HealthService: Received stop request...Stopping profile...
09-06 18:58:28.869  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:28.871  7121  7121 D PanService: Received stop request...Stopping profile...
09-06 18:58:28.873  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
,09-06 18:58:28.876  7121  7121 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:58:28.876  7121  7121 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 18:58:28.876  7121  7121 D BtGatt.GattService: stop()
09-06 18:58:28.877  7121  7121 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 18:58:28.878  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:28.880  7121  7121 D BluetoothMapService: Received stop request...Stopping profile...
09-06 18:58:28.880  7121  7121 D BluetoothMapService: stop()
09-06 18:58:28.880  7121  7121 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 18:58:28.880  7121  7121 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 18:58:28.881  7121  7121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@288c1df3
09-06 18:58:28.882  7121  7121 D HeadsetStateMachine: Unbinding service...
09-06 18:58:28.886  7121  7121 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 18:58:28.886  7121  7121 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 18:58:28.886  7121  7121 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 18:58:28.886  7121  7121 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 18:58:28.887  7121  7121 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 18:58:28.887  7121  7121 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:58:28.887  7121  7121 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-06 18:58:28.891  7121  7121 I BluetoothA2dpServiceJni: cleanupNative
09-06 18:58:28.891  7121  7646 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 18:58:28.893  7121  7121 I GKI_LINUX: GKI_exit_task 2 done
09-06 18:58:28.893  7121  7121 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 18:58:28.894  7121  7121 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 18:58:28.894  7121  7121 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 18:58:28.894  7121  7121 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 18:58:28.894  7121  7121 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 18:58:28.894  7121  7121 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 18:58:28.895  7121  7121 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 18:58:28.895  7121  7121 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 18:58:28.898  7121  7121 V BluetoothMapService: Handler(): got msg=4
09-06 18:58:28.898  7121  7121 D BluetoothMapService: MAP Service closeService in
09-06 18:58:28.898  7121  7121 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 18:58:28.899  7121  7121 V BluetoothMapService: MAP Service closeService out
,09-06 18:58:28.901  7121  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 18:58:28.901  7121  7583 D BluetoothAdapterProperties: Setting state to 10
09-06 18:58:28.901  7121  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 18:58:28.902  7121  7121 D BluetoothMapService: cleanup()
09-06 18:58:28.902  7121  7121 D BluetoothMapService: MAP Service closeService in
09-06 18:58:28.902  7121  7121 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 18:58:28.902  7121  7121 V BluetoothMapService: MAP Service closeService out
09-06 18:58:28.903  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:28.903  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 18:58:28.903  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-06 18:58:28.904  7121  7583 I BluetoothAdapterState: Entering OffState
09-06 18:58:28.904  1853  4450 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:28.904  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:28.905  6995  7012 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:58:28.905  6995  7011 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 18:58:28.906  6995  7012 D BluetoothMap: onBluetoothStateChange: up=false
09-06 18:58:28.907  6995  7701 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:28.909  6995  7011 D BluetoothPan: onBluetoothStateChange on: false
09-06 18:58:28.910  1853  2451 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 18:58:28.913  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:58:28.914  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:58:28.914  6995  7012 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 18:58:28.915  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 18:58:28.915  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 18:58:28.917  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 18:58:28.917  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 18:58:28.917  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3300c403 mBinding = false
09-06 18:58:28.917  1034  1096 D BluetoothManagerService: Sending unbind request.
09-06 18:58:28.920  6995  6995 D BluetoothHeadset: Proxy object disconnected
09-06 18:58:28.920  6995  6995 D HeadsetProfile: Bluetooth service disconnected
09-06 18:58:28.924  7121  7587 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 18:58:28.926  7121  7121 I GKI_LINUX: GKI_exit_task 1 done
09-06 18:58:28.926  7121  7121 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 18:58:28.926  7121  7121 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 18:58:28.926  7121  7121 I art     : --- WEIRD: removing null entry 248
09-06 18:58:28.926  7121  7121 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-06 18:58:28.926  7121  7121 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 18:58:28.928  7121  7121 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 18:58:28.929  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 18:58:28.931  7121  7121 I art     : System.exit called, status: 0
09-06 18:58:28.931  7121  7121 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 18:58:28.950   316  1403 V AudioFlinger: 7121 died, releasing its sessions
09-06 18:58:28.950   316  1403 V AudioFlinger:  pid 1853 @ 0
09-06 18:58:28.950   316  1403 V AudioFlinger:  pid 3383 @ 1
09-06 18:58:28.950   316  1403 V AudioFlinger:  pid 3383 @ 2
,09-06 18:58:28.954  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,09-06 18:58:28.954  1941  2145 D LGBluetoothAPIService: Message: 101
09-06 18:58:28.954  1941  2145 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-06 18:58:28.955  1941  2145 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-06 18:58:28.955  1941  2145 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-06 18:58:28.956  6995  6995 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 18:58:28.960  1034  1787 I ActivityManager: Process com.android.bluetooth (pid 7121) has died
09-06 18:58:28.960  1034  1787 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-06 18:58:28.961  1034  1787 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
09-06 18:58:28.972  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:28.975  1941  2145 D LGBluetoothAPIService: Message: 2
,09-06 18:58:28.976  1941  2145 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,09-06 18:58:28.979  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:28.984  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:28.984  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:28.988  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 18:58:28.988  6995  6995 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-06 18:58:28.991  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 18:58:28.992  1604  1604 D BluetoothAdapter: 647474533: getState() :  mService = null. Returning STATE_OFF
09-06 18:58:28.992  1604  1604 D BluetoothAdapter: 647474533: getState() :  mService = null. Returning STATE_OFF
09-06 18:58:29.032  1034  1959 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7778 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 18:58:29.036  6995  6995 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:58:29.102  7778  7778 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 18:58:29.102  7778  7778 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:29.103  7778  7778 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-06 18:58:29.106  7778  7778 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 18:58:29.125  7778  7778 D BluetoothAdapterApp: Loading JNI Library
,09-06 18:58:29.167  7778  7778 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b92da7b Instance Count = 1
,09-06 18:58:29.258  1034  1092 I art     : Explicit concurrent mark sweep GC freed 98704(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.733ms total 171.341ms
09-06 18:58:29.260  7778  7778 D BluetoothAdapterApp: onCreate
,09-06 18:58:29.289  7778  7778 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 18:58:29.290  7778  7778 D ProfileConfigQcom: Adding HeadsetService
09-06 18:58:29.290  7778  7778 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 18:58:29.290  7778  7778 D ProfileConfigQcom: Adding A2dpService
09-06 18:58:29.290  7778  7778 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 18:58:29.290  7778  7778 D ProfileConfigQcom: Adding HidService
09-06 18:58:29.291  7778  7778 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 18:58:29.291  7778  7778 D ProfileConfigQcom: Adding HealthService
09-06 18:58:29.291  7778  7778 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-06 18:58:29.293  7778  7778 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 18:58:29.293  7778  7778 D ProfileConfigQcom: Adding PanService
09-06 18:58:29.294  7778  7778 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 18:58:29.294  7778  7778 D ProfileConfigQcom: Adding GattService
09-06 18:58:29.295  7778  7778 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 18:58:29.296  7778  7778 D ProfileConfigQcom: Adding BluetoothMapService
09-06 18:58:29.297  7778  7778 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 18:58:29.299  7778  7778 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:29.301  7778  7778 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:29.302  7778  7778 V BluetoothPbapReceiver: ***********state = 10
09-06 18:58:29.306  7778  7778 V LGMDMManagerInternal: Create singleton instance
,09-06 18:58:29.406  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:58:29.417  6995  6995 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-06 18:58:29.422  6995  6995 D BluetoothPermissionRequest: onReceive
09-06 18:58:29.422  7778  7778 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-06 18:58:29.422  7778  7778 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 18:58:29.426  6995  6995 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 18:58:29.426  6995  6995 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 18:58:29.426  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-06 18:58:29.427  1941  2145 D LGBluetoothAPIService: Message: 100
09-06 18:58:29.427  1941  2145 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-06 18:58:29.431  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 18:58:29.440  7778  7778 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 18:58:29.445  7778  7778 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:29.449  7778  7778 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:29.449  7778  7778 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:29.450  7778  7778 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:29.451  7778  7778 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:29.451  7778  7778 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 18:58:29.454  7064  7064 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 18:58:30.955  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:58:30.955  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:58:31.025  1034  1382 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 18:58:31.046  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-06 18:58:31.122  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 18:58:31.129  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7809 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-06 18:58:31.132  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-06 18:58:31.134  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-06 18:58:31.136  1034  1034 D administrator: Handling package changes for user 0
09-06 18:58:31.164  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 18:58:31.200  7809  7809 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 18:58:31.257  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-06 18:58:31.257  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 18:58:31.273  7809  7809 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:31.273  7809  7809 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:31.307  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 18:58:31.319  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 18:58:31.324  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 18:58:31.325  2502  2502 V GmsNetworkLocationProvi: DISABLE
,09-06 18:58:31.345  1034  1091 D LocationProviderProxy: applying state to connected service
09-06 18:58:31.346  2502  2502 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-06 18:58:31.383  7809  7853 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-06 18:58:31.383  7809  7853 I Babel   : MmsConfig.loadMmsSettings
09-06 18:58:31.387  7809  7853 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 18:58:31.387  7809  7853 I Babel   : MmsConfig.loadFromDatabase
,09-06 18:58:31.406  7809  7853 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 18:58:31.406  7809  7853 I Babel   : MmsConfig.loadFromResources
09-06 18:58:31.408  7809  7853 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-06 18:58:31.409  7809  7853 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 18:58:31.418  7809  7852 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 18:58:31.419  7809  7852 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 18:58:31.420  7809  7809 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:31.420  7809  7852 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 18:58:31.426  7809  7852 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-06 18:58:31.427  7809  7852 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 18:58:31.428  7809  7852 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 18:58:31.435  7809  7852 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-06 18:58:31.436  7809  7852 W VideoCapabilities: Unsupported mime video/divx
09-06 18:58:31.437  7809  7852 W VideoCapabilities: Unsupported mime video/divx311
09-06 18:58:31.439  7809  7852 W VideoCapabilities: Unsupported mime video/divx4
09-06 18:58:31.441  1817  7856 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-06 18:58:31.441  1817  7856 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-06 18:58:31.444  7175  7175 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 18:58:31.462  7175  7175 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ee96b2d
09-06 18:58:31.462  7175  7175 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 18:58:31.462  7175  7175 D AppUp4:CustFacade: isPhone : true
09-06 18:58:31.462  1817  4784 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-06 18:58:31.462  7175  7175 D AppUp4:CustModeStarterReceiver: begin check event
09-06 18:58:31.462  7175  7175 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-06 18:58:31.488  7809  7852 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 18:58:31.495  1034  1959 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7858 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-06 18:58:31.502  1034  1952 I ActivityManager: Killing 6774:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-06 18:58:31.510  7809  7852 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-06 18:58:31.514  7809  7852 W AudioCapabilities: Unsupported mime audio/eac3
09-06 18:58:31.515  7809  7852 W AudioCapabilities: Unsupported mime audio/ac3
09-06 18:58:31.515  7809  7852 W AudioCapabilities: Unsupported mime audio/g726
09-06 18:58:31.516  7809  7852 W AudioCapabilities: Unsupported mime audio/wma-voice
,09-06 18:58:31.517  7809  7852 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 18:58:31.518  7809  7852 W AudioCapabilities: Unsupported mime audio/adpcm
09-06 18:58:31.519  7809  7852 W VideoCapabilities: Unsupported mime video/theora
09-06 18:58:31.520  7809  7852 W VideoCapabilities: Unsupported mime video/mjpg
09-06 18:58:31.530  7044  7044 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 18:58:31.530  7044  7044 W System.err: android.os.DeadObjectException
09-06 18:58:31.530  7044  7044 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 18:58:31.530  7044  7044 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 18:58:31.530  7044  7044 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 18:58:31.530  7044  7044 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 18:58:31.530  7044  7044 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:58:31.530  7044  7044 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:58:31.530  7044  7044 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 18:58:31.531  7044  7044 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 18:58:31.531  7044  7044 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 18:58:31.531  7044  7044 W System.err: android.os.DeadObjectException
09-06 18:58:31.531  7044  7044 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 18:58:31.531  7044  7044 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 18:58:31.531  7044  7044 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 18:58:31.531  7044  7044 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 18:58:31.531  7044  7044 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:58:31.531  7044  7044 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:58:31.531  7044  7044 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 18:58:31.532  7044  7044 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 18:58:31.532  7044  7044 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,09-06 18:58:31.532  7044  7044 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 18:58:31.714  1034  1952 E libprocessgroup: failed to kill 1 processes for processgroup 6774
,09-06 18:58:31.779  1034  2030 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-06 18:58:31.786  7044  7044 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 18:58:31.787  7044  7044 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 18:58:31.851  7858  7858 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:58:31.853  7858  7858 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:31.853  7858  7858 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 18:58:31.857  7858  7858 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,09-06 18:58:31.860  1034  2030 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 18:58:31.862  7858  7858 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 18:58:31.865  7044  7044 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 18:58:31.909  7881  7881 D UEI.SmartControl: Quickset Services start...
,09-06 18:58:31.910  7881  7881 I UEI.SmartControl: Manufacture = LGE
09-06 18:58:31.910  7881  7881 D UEI.SmartControl: Id = LGNevo
09-06 18:58:31.912  7881  7881 D UEI.SmartControl: File observer start...
09-06 18:58:31.913  7881  7881 E UEI.SmartControl: IR Port is disabled: false
09-06 18:58:31.913  7881  7881 D UEI.SmartControl: Starting file observer...
09-06 18:58:31.913  7881  7881 D UEI.SmartControl: Extracting JNI libs...
09-06 18:58:31.913  7881  7881 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-06 18:58:31.935  7858  7858 I SystemConfig: BUILD Country: EU
09-06 18:58:31.935  7858  7858 I SystemConfig: BUILD Operator: OPEN
,09-06 18:58:32.000  1034  2033 I ActivityManager: Killing 7044:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 18:58:32.003  7881  7881 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-06 18:58:32.003  7881  7881 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-06 18:58:32.004  7881  7881 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-06 18:58:32.038  7881  7881 I UEI.SmartControl: --- Selecting new region: 6
,09-06 18:58:32.039  7881  7881 I UEI.SmartControl: Model = LG-D855
09-06 18:58:32.041  7881  7881 D UEI.SmartControl: QS Service created
09-06 18:58:32.124  1034  1758 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7902 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-06 18:58:32.128  1034  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_7044/cgroup.procs: No such file or directory
09-06 18:58:32.136  7858  7900 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-06 18:58:32.136  7858  7900 I SystemConfig: existFile = false
09-06 18:58:32.137  7858  7900 I SystemConfig: canReadFile = false
09-06 18:58:32.137  7858  7900 I SystemConfig: systemFeature RCS result false
,09-06 18:58:32.137  7858  7900 D SystemConfig: refreshRcsSupport() :false
09-06 18:58:32.152  7881  7881 I UEI.SmartControl: Service initServices...
,09-06 18:58:32.157  7881  7881 D UEI.SmartControl: QS start get config
09-06 18:58:32.187  7902  7902 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 18:58:32.187  7902  7902 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 18:58:32.188  7902  7902 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 18:58:32.188  7902  7902 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 18:58:32.237  7881  7881 D UEI.SmartControl: Loading JNI Libs...
,09-06 18:58:32.302  7902  7902 I AppConfig: Total System Memory = 2995761152
,09-06 18:58:32.312  7902  7902 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-06 18:58:32.406  1034  2030 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7921 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 18:58:32.409  1034  2030 I ActivityManager: Killing 7211:com.lge.email/u0a23 (adj 15): empty #17
09-06 18:58:32.425   346   346 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 22.903ms
,09-06 18:58:32.447   346   346 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 20.392ms
,09-06 18:58:32.467   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 18.660ms
,09-06 18:58:32.509  1034  1959 W libprocessgroup: failed to open /acct/uid_10023/pid_7211/cgroup.procs: No such file or directory
,09-06 18:58:32.641  7881  7881 I UEI.SmartControl: Supports setup maps: true
09-06 18:58:32.644  7881  7881 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 18:58:32.644  7881  7881 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 18:58:32.644  7881  7881 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 18:58:32.644  7881  7881 I UEI.SmartControl: ### init IR Blaster...
,09-06 18:58:32.649  7921  7921 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-06 18:58:32.650  7881  7881 D serial_port: Configuring serial port
09-06 18:58:32.653  7881  7881 E UEI.SmartControl: UEIBLaster setting for 616
09-06 18:58:32.653  7881  7881 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 18:58:32.653  7881  7881 I UEI.SmartControl: configuring settings for MAXQ616
09-06 18:58:32.653  7881  7881 I UEI.SmartControl: Get version...
09-06 18:58:32.670  7881  7948 D UEI.SmartControl: serial port data available: 21
,09-06 18:58:32.697  7881  7881 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-06 18:58:32.697  7881  7881 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 18:58:32.697  7881  7881 I UEI.SmartControl: QS saving settings...
09-06 18:58:32.697  7921  7921 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:32.697  7921  7921 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:32.697  7881  7881 D UEI.SmartControl: IR Blaster version: 25672567
09-06 18:58:32.713  7881  7948 D UEI.SmartControl: serial port data available: 4
,09-06 18:58:32.730  7921  7921 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 18:58:32.744  7921  7921 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 18:58:32.745  7921  7921 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-06 18:58:32.748  7881  7965 I UEI.SmartControl: Device manager: loading config....
,09-06 18:58:32.749  7881  7965 D UEI.SmartControl: ----------- loading internal config...
09-06 18:58:32.750  7881  7881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 18:58:32.756  7921  7921 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-06 18:58:32.756  7881  7881 E UEI.SmartControl: Services init done
09-06 18:58:32.756  7921  7921 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-06 18:58:32.756  7881  7881 D UEI.SmartControl: QS Service init finished
,09-06 18:58:32.760  7881  7881 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 18:58:32.761  7881  7881 D UEI.SmartControl: QS Service version code: 201091
09-06 18:58:32.762  7881  7881 D UEI.SmartControl: Service requested: Control
09-06 18:58:32.767  7881  7881 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 18:58:32.768  7881  7965 E UEI.SmartControl: Loading SETTINGS...
09-06 18:58:32.773  7881  7881 D UEI.SmartControl: Service.onUnbind: IControl
09-06 18:58:32.774  7881  7881 D UEI.SmartControl: Service.onDestroy
,09-06 18:58:32.774  7881  7881 D UEI.SmartControl: Lock is in USE false
09-06 18:58:32.774  7881  7881 D UEI.SmartControl: unbind internal service
09-06 18:58:32.780  7881  7965 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 18:58:32.781  3479  3495 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-06 18:58:32.783  7881  7881 D serial_port: close(fd = 25)
,09-06 18:58:32.785  7881  7964 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 18:58:32.785  7881  7964 D UEI.SmartControl: -----service ready thread exits
09-06 18:58:32.786  3479  3495 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b167228 on behalf of 7921
09-06 18:58:32.787  7881  7881 I UEI.SmartControl: Serial port is closed.
09-06 18:58:32.787  7881  7881 I UEI.SmartControl: Serial port is closed.
09-06 18:58:32.787  7881  7881 D UEI.SmartControl: Blaster closed
09-06 18:58:32.787  7881  7881 D UEI.SmartControl: Shut down QS...
09-06 18:58:32.788  7881  7881 D UEI.SmartControl: Stopping QS lib
09-06 18:58:32.788  7881  7881 D UEI.SmartControl: QS lib stop result = true
09-06 18:58:32.788  7881  7881 D UEI.SmartControl: Stopped QS lib
09-06 18:58:32.788  7881  7881 D UEI.SmartControl: Stopped file observer...
,09-06 18:58:32.789  7881  7881 D UEI.SmartControl: QS shutdown complete
09-06 18:58:32.790  7881  7881 D UEI.SmartControl: QS Service created
09-06 18:58:32.792  1034  1051 I ActivityManager: Killing 7084:com.lge.formmanager/u0a26 (adj 15): empty #17
09-06 18:58:32.811  7881  7881 I UEI.SmartControl: Service initServices...
09-06 18:58:32.812  7881  7881 D UEI.SmartControl: QS start get config
,09-06 18:58:32.932  1034  2033 W libprocessgroup: failed to open /acct/uid_10026/pid_7084/cgroup.procs: No such file or directory
,09-06 18:58:32.945  4639  7971 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-06 18:58:32.950  7921  7921 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 18:58:32.997  1034  2060 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7972 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-06 18:58:33.026  7921  7921 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-06 18:58:33.064  7972  7972 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-06 18:58:33.088  7972  7972 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-06 18:58:33.088  7972  7972 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-06 18:58:33.088  7972  7972 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-06 18:58:33.088  7972  7972 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-06 18:58:33.088  7972  7972 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-06 18:58:33.088  7972  7972 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-06 18:58:33.102  1034  1952 I ActivityManager: Killing 6568:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-06 18:58:33.136  7881  7881 I UEI.SmartControl: Supports setup maps: true
,09-06 18:58:33.141  7881  7881 D UEI.SmartControl: QS start statue = true Error code = 0
,09-06 18:58:33.141  7881  7881 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 18:58:33.141  7881  7881 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 18:58:33.141  7881  7881 I UEI.SmartControl: ### init IR Blaster...
09-06 18:58:33.145  7881  7881 D serial_port: Configuring serial port
09-06 18:58:33.145  7881  7881 E UEI.SmartControl: UEIBLaster setting for 616
09-06 18:58:33.145  7881  7881 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 18:58:33.145  7881  7881 I UEI.SmartControl: configuring settings for MAXQ616
09-06 18:58:33.145  7881  7881 I UEI.SmartControl: Get version...
09-06 18:58:33.162  7881  7992 D UEI.SmartControl: serial port data available: 21
,09-06 18:58:33.172  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6568/cgroup.procs: No such file or directory
,09-06 18:58:33.189  7881  7881 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 18:58:33.189  7881  7881 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 18:58:33.189  7881  7881 I UEI.SmartControl: QS saving settings...
09-06 18:58:33.191  7881  7881 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 18:58:33.208  7881  7992 D UEI.SmartControl: serial port data available: 4
,09-06 18:58:33.239  7881  7995 I UEI.SmartControl: Device manager: loading config....
,09-06 18:58:33.240  7881  7995 D UEI.SmartControl: ----------- loading internal config...
,09-06 18:58:33.241  7881  7881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 18:58:33.244  7881  7881 E UEI.SmartControl: Services init done
09-06 18:58:33.244  7881  7881 D UEI.SmartControl: QS Service init finished
09-06 18:58:33.246  7881  7881 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 18:58:33.246  7881  7881 D UEI.SmartControl: QS Service version code: 201091
09-06 18:58:33.247  7881  7881 D UEI.SmartControl: Service requested: Control
09-06 18:58:33.254  7881  7881 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 18:58:33.254  7881  7995 E UEI.SmartControl: Loading SETTINGS...
,09-06 18:58:33.260  1034  1887 I ActivityManager: Killing 7247:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-06 18:58:33.263  7881  7995 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 18:58:33.277  7881  7994 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 18:58:33.278  7881  7994 D UEI.SmartControl: -----service ready thread exits
,09-06 18:58:33.425  1034  2030 W libprocessgroup: failed to open /acct/uid_10046/pid_7247/cgroup.procs: No such file or directory
,09-06 18:58:33.436  7881  7881 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@191e8d29 that was originally bound here
09-06 18:58:33.436  7881  7881 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@191e8d29 that was originally bound here
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 18:58:33.436  7881  7881 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 18:58:33.441  7881  7881 D UEI.SmartControl: Internal service binding...
,09-06 18:58:33.535  1034  1758 V SIM_STK : Menu title from STK is T-Mobile
,09-06 18:58:33.559  4639  7971 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 614 ms] updated apps [took 614 ms] 
,09-06 18:58:33.774  7881  7968 D UEI.SmartControl: Internal timer expired: 2
,09-06 18:58:33.972  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:33.972  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b94bd37 added. We now have 6 listener(s)
09-06 18:58:33.972  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:58:33.977  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:33.977  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f8582a4 added. We now have 7 listener(s)
09-06 18:58:33.977  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:33.978  6865  6943 I System.out: IsBluetoothEnabled
09-06 18:58:33.979  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:33.979  1034  2033 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-06 18:58:33.980  1034  1096 D BluetoothManagerService: Message: 2
09-06 18:58:33.984  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:33.986  1034  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:33.986  1034  1787 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 18:58:34.003  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 18:58:34.003  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 18:58:34.003  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-06 18:58:34.006  1034  1096 D BluetoothManagerService: Message: 1
09-06 18:58:34.006  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-06 18:58:34.033  1034  1096 D BluetoothManagerService: Message: 20
09-06 18:58:34.033  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25a59818:true
,09-06 18:58:34.036  7778  7778 D BluetoothAdapterState: make
09-06 18:58:34.041  7778  7778 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 18:58:34.041  7778  7778 I bluedroid-qcom: init
09-06 18:58:34.042  7778  8010 I BluetoothAdapterState: Entering OffState
09-06 18:58:34.043  7778  7778 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 18:58:34.043  7778  7778 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 18:58:34.043  7778  7778 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 18:58:34.043  7778  7778 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 18:58:34.043  7778  7778 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 18:58:34.045  7778  7778 I bluedroid-qcom: get_profile_interface socket
09-06 18:58:34.045  7778  7778 I bluedroid-qcom: get_profile_interface map_client
,09-06 18:58:34.049  7778  8014 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 18:58:34.042  8013  8013 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:34.042  8013  8013 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:34.059  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-06 18:58:34.061  1034  1096 D BluetoothManagerService: Message: 40
09-06 18:58:34.061  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 18:58:34.062  7778  7794 I bluedroid-qcom: config_hci_snoop_log
09-06 18:58:34.064  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 18:58:34.064  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 18:58:34.067  7778  8014 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 18:58:34.071  8013  8013 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 18:58:34.071  8013  8013 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 18:58:34.071  8013  8013 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-06 18:58:34.074  8013  8013 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 18:58:34.078  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 18:58:34.079  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 18:58:34.079  7778  8014 D BluetoothAdapterProperties: Name is: G3
09-06 18:58:34.080  8013  8013 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 18:58:34.080  8013  8013 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 18:58:34.086  7778  8010 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 18:58:34.086  7778  8010 D BluetoothAdapterProperties: Setting state to 11
09-06 18:58:34.086  7778  8010 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-06 18:58:34.090  7778  8010 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 18:58:34.093  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:34.093  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 18:58:34.094  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 18:58:34.098  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:58:34.100  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:34.104  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:34.106  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 18:58:34.112  7778  7778 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:34.112  7778  7778 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:34.112  7778  7778 V BluetoothPbapReceiver: ***********state = 11
,09-06 18:58:34.118  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 18:58:34.134  6995  6995 D BluetoothPermissionRequest: onReceive
,09-06 18:58:34.146  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 18:58:34.146  7778  8010 D BluetoothBondStateMachine: make
09-06 18:58:34.154  7778  7778 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:58:34.157  7778  7778 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:34.157  7778  7778 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:34.157  7778  7778 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:34.157  7778  7778 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:34.158  7778  7778 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 18:58:34.158  7778  8010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.158  7778  8010 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 18:58:34.158  7778  8010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.158  7778  8010 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 18:58:34.159  7778  8010 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 18:58:34.159  7778  8028 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 18:58:34.162  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:34.166  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 18:58:34.169  7778  7778 D HeadsetService: Received start request. Starting profile...
09-06 18:58:34.170  7778  7778 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 18:58:34.170  7778  7778 D LGBluetoothHfpAdapter: Version 1.6
09-06 18:58:34.171  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:34.173  7778  7778 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 18:58:34.174  7778  7778 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 18:58:34.175  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:34.175  7778  7778 D HeadsetStateMachine: make
09-06 18:58:34.180  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 18:58:34.184  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:34.188  7778  8010 E BluetoothAdapterService: File transfer profiles supported!!
09-06 18:58:34.208  7778  8010 V LGMDMManager: Create singleton instance
,09-06 18:58:34.212  7778  7778 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:34.212  7778  7778 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:34.215  7778  8010 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 18:58:34.216  7778  7778 D HeadsetStateMachine: max_hf_connections = 1
09-06 18:58:34.216  7778  7778 I bluedroid-qcom: get_profile_interface handsfree
09-06 18:58:34.218  7778  7778 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 18:58:34.219   316  2165 V AudioPolicyService: registerClient() client 0xb57f66e0, uid 1002
09-06 18:58:34.219   316  1404 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,09-06 18:58:34.219   316  1404 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 18:58:34.219   316  1404 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 18:58:34.219  7778  7778 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 18:58:34.219   316  1403 V AudioFlinger: registerClient() client 0xb14334f0, pid 7778
09-06 18:58:34.220   316  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:34.220   316  1398 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:34.220  1853  4451 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:34.220  1853  4451 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:34.220  1034  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:34.220  1034  1940 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:34.221   316  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:34.221  7778  7778 V ToneGenerator: Create Track: 0xb4928a80
09-06 18:58:34.221   316  1399 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:34.221  7778  7778 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 18:58:34.221  7778  7778 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 18:58:34.222  7778  7793 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:34.222  7778  7793 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 18:58:34.222  7778  7793 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:34.222  7778  7793 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
,09-06 18:58:34.222   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 18:58:34.222   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 18:58:34.222   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 18:58:34.222   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 18:58:34.222  1604  2098 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:34.222  1604  2098 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:34.222  1604  2098 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:34.222  1604  2098 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:34.222   316  2165 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 18:58:34.223  3383  3398 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 18:58:34.223  3383  3398 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 18:58:34.223   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 18:58:34.223  3383  3398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:34.223  3383  3398 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:34.223   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 18:58:34.223   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 18:58:34.223   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 18:58:34.223  7778  7778 V AudioSystem: getLatency() output 2, latency 50
09-06 18:58:34.223  7778  7778 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 18:58:34.223  7778  7778 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 18:58:34.223   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 18:58:34.223   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 18:58:34.223   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 18:58:34.223   316  2162 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 18:58:34.223   316  2162 V AudioFlinger: createTrack() lSessionId: 21
09-06 18:58:34.224  1034  2030 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:34.224  1034  2030 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 18:58:34.224  1853  4450 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 18:58:34.224  1853  4450 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-06 18:58:34.225  7778  7778 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 18:58:34.225   316  1404 V AudioFlinger: acquiring 21 from 7778, for 7778
09-06 18:58:34.225   316  1404 V AudioFlinger:  added new entry for 21
09-06 18:58:34.225  7778  7778 V ToneGenerator: ToneGenerator INIT OK, time: 194377
09-06 18:58:34.225  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.226  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.227  7778  8032 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 18:58:34.227  7778  7778 D A2dpService: Received start request. Starting profile...
,09-06 18:58:34.228  7778  8032 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 18:58:34.228  7778  7778 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 18:58:34.228  7778  8032 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 18:58:34.230  7778  7778 V Avrcp   : make
09-06 18:58:34.231  7778  7778 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 18:58:34.231  7778  7778 I bluedroid-qcom: get_profile_interface avrcp
09-06 18:58:34.232  7778  8032 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,09-06 18:58:34.233   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7778
09-06 18:58:34.234   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 18:58:34.234   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 18:58:34.234   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 18:58:34.234   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 18:58:34.234   316   316 V voice   : voice_set_parameters: exit with code(0)
09-06 18:58:34.234   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 18:58:34.234   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 18:58:34.234   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 18:58:34.234   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 18:58:34.234   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 18:58:34.234   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 18:58:34.237  7778  8032 V ToneGenerator: ToneGenerator destructor
09-06 18:58:34.237  7778  8032 V ToneGenerator: stopTone
09-06 18:58:34.237  7778  8032 V ToneGenerator: Delete Track: 0xb4928a80
09-06 18:58:34.238  7778  8032 V AudioTrack: ~AudioTrack, releasing session id from 7778 on behalf of 7778
09-06 18:58:34.239   316  2165 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 18:58:34.239   316  2165 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 18:58:34.239   316  2162 V AudioFlinger: releasing 21 from 7778 for 7778
09-06 18:58:34.239   316  2162 V AudioFlinger:  decremented refcount to 0
09-06 18:58:34.239   316  2162 V AudioFlinger: purging stale effects
09-06 18:58:34.239   316  1258 V AudioPolicyService: AudioCommandThread() waking up
09-06 18:58:34.239   316  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 18:58:34.239   316  1258 V AudioPolicyManager: releaseOutput() 2
09-06 18:58:34.239   316  1258 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 18:58:34.239   316  2165 V AudioFlinger: PlaybackThread::Track destructor
09-06 18:58:34.239   316  2165 V AudioFlinger: removeClient_l() pid 7778, calling pid 316
09-06 18:58:34.241  7778  7778 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 18:58:34.243  7778  7778 E AudioManager: No RCC entry present to update
09-06 18:58:34.243  7778  7778 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 18:58:34.245  7778  7778 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-06 18:58:34.246  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,09-06 18:58:34.246  7778  7778 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 18:58:34.251  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 18:58:34.349  1034  1887 V SIM_STK : Menu title from STK is T-Mobile
09-06 18:58:34.350  1034  1887 V SIM_STK : Menu title from STK is T-Mobile
,09-06 18:58:34.501  1034  2060 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 18:58:34.514  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 18:58:34.521  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-06 18:58:34.522  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 18:58:34.522  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 18:58:34.522  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 18:58:34.523  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 18:58:34.523  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 18:58:34.523  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 18:58:34.523  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 18:58:34.523  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 18:58:34.523  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 18:58:34.524  7778  7778 I BluetoothA2dpServiceJni: classInitNative
09-06 18:58:34.524  7778  7778 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:58:34.524  7778  7778 D A2dpStateMachine: make
09-06 18:58:34.526  7778  7778 I bluedroid-qcom: get_profile_interface a2dp
09-06 18:58:34.526  7778  8041 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 18:58:34.529  7778  7778 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:58:34.529  7778  7778 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 18:58:34.531  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.531  7778  8040 D A2dpStateMachine: Enter Disconnected: -2
09-06 18:58:34.532  7778  7778 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 18:58:34.534  7778  7778 D HidService: Received start request. Starting profile...
09-06 18:58:34.534  7778  7778 I bluedroid-qcom: get_profile_interface hidhost
09-06 18:58:34.534  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.535  7778  7778 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 18:58:34.537  7778  7778 D HealthService: Received start request. Starting profile...
09-06 18:58:34.540  7778  7778 I bluedroid-qcom: get_profile_interface health
,09-06 18:58:34.541  7778  7778 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 18:58:34.541  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.542  7778  7778 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 18:58:34.544  7778  7778 D PanService: Received start request. Starting profile...
09-06 18:58:34.544  7778  7778 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 18:58:34.544  7778  7778 I bluedroid-qcom: get_profile_interface pan
09-06 18:58:34.553  7778  7778 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 18:58:34.553  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
,09-06 18:58:34.554  7778  7778 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-06 18:58:34.561  7778  7778 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:58:34.562  7778  7778 D BtGatt.GattService: Received start request. Starting profile...
,09-06 18:58:34.562  7778  7778 D BtGatt.GattService: start()
09-06 18:58:34.562  7778  7778 I bluedroid-qcom: get_profile_interface gatt
09-06 18:58:34.563  7778  7778 D BtGatt.AdvertiseManager: advertise manager created
09-06 18:58:34.574  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
,09-06 18:58:34.576  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.576  7778  7778 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 18:58:34.578  7778  7778 V BluetoothMapService: BluetoothMapBinder()
09-06 18:58:34.578  7778  7778 D BluetoothMapService: Received start request. Starting profile...
09-06 18:58:34.578  7778  7778 D BluetoothMapService: start()
09-06 18:58:34.582  7778  7778 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 18:58:34.582  7778  7778 D BluetoothMapEmailAppObserver: createReceiver()
09-06 18:58:34.584  7778  7778 D BluetoothMapEmailAppObserver: initObservers()
09-06 18:58:34.584  7778  7778 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 18:58:34.596  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:34.596  7778  7778 D HeadsetStateMachine: Proxy object connected
09-06 18:58:34.598  7778  7778 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 18:58:34.598  7778  7778 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-06 18:58:34.605  7778  7778 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:34.606  7778  8032 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 18:58:34.607  7778  8032 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 18:58:34.607  7778  8032 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 18:58:34.612  7778  7778 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 18:58:34.618  7778  7778 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:34.623  7778  7778 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:34.627  7778  7778 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 18:58:34.627  7778  7778 V PanService: [BTUI] SIM Extra State :ABSENT
,09-06 18:58:34.633  7778  7778 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 18:58:34.633  7778  7778 V BluetoothMapService: Handler(): got msg=1
09-06 18:58:34.635  7778  8010 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 18:58:34.635  7778  8010 I bluedroid-qcom: enable
09-06 18:58:34.635  7778  8049 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 18:58:34.635  7778  8049 I bt-btu  : btu_task pending for preload complete event
09-06 18:58:34.635  7778  8010 I bt_hci_bdroid: init
09-06 18:58:34.639  7778  8010 I bt_vendor: bt-vendor : init
09-06 18:58:34.639  7778  8010 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 18:58:34.639  7778  8010 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 18:58:34.639  7778  8010 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 18:58:34.639  7778  8010 D bt_userial_mct: userial_init
09-06 18:58:34.639  7778  8010 D bt_hci_bdroid: set_power 1
09-06 18:58:34.639  7778  8010 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 18:58:34.639  7778  8010 I bt_vendor: Starting hciattach daemon
09-06 18:58:34.640  7778  8010 I bt_vendor: try to set true
09-06 18:58:34.632  8052  8052 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:34.642  8052  8052 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 18:58:34.703  8053  8053 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 18:58:34.817  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 18:58:34.840  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 18:58:34.873  8065  8065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 18:58:34.885  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-06 18:58:34.896  8067  8067 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 18:58:34.909  8068  8068 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 18:58:34.931  8070  8070 I libmdmdetect: ESOC framework not supported
09-06 18:58:34.932  8070  8070 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 18:58:34.939  8070  8070 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 18:58:34.940  8070  8070 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 18:58:34.940  8070  8070 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 18:58:34.940  8070  8070 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 18:58:34.940  8070  8070 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 18:58:34.940  8070  8070 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 18:58:34.940  8070  8070 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 18:58:34.976  8070  8071 E QC-QMI  : qmi_client [8070] 15: failed to locate client data
,09-06 18:58:34.976   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-06 18:58:34.976   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-06 18:58:35.012  8072  8072 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 18:58:35.029  8073  8073 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 18:58:35.044  7778  8010 I bt_vendor: bluetooth satus is on
09-06 18:58:35.044  7778  8010 D bt_hci_bdroid: preload
09-06 18:58:35.046  7778  8051 D bt_userial_mct: userial_open(port:0)
09-06 18:58:35.046  7778  8051 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 18:58:35.049  7778  8051 I bt_vendor: Done intiailizing UART
09-06 18:58:35.052  7778  8051 I bt_vendor: Done intiailizing UART
09-06 18:58:35.052  7778  8051 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 18:58:35.053  7778  8051 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 18:58:35.053  7778  8075 D bt_userial_mct: Entering userial_read_thread()
09-06 18:58:35.053  7778  8049 I bt-btu  : btu_task received preload complete event
,09-06 18:58:35.054  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,09-06 18:58:35.054  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-06 18:58:35.058  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_GAP,
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_PAN
,09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_SDP,
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 18:58:35.064  7778  8049 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 18:58:35.171  7778  8049 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-06 18:58:35.171  7778  8049 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa015c061 
09-06 18:58:35.171  7778  8049 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa015c061 ,
,09-06 18:58:35.216  7778  8014 E bt-btif : Calling BTA_HhEnable
09-06 18:58:35.216  7778  8014 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 18:58:35.216  7778  8014 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 18:58:35.219  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 18:58:35.219  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 18:58:35.219  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 18:58:35.221  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 18:58:35.221  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 18:58:35.221  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 18:58:35.222  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 18:58:35.222  7778  8014 D BluetoothAdapterProperties: Name is: G3
09-06 18:58:35.223  7778  8014 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:58:35.223  7778  8014 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 18:58:35.224  7778  8014 D bt_hci_bdroid: postload
09-06 18:58:35.224  7778  8051 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:35.225  7778  8051 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:35.225  7778  8049 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 18:58:35.226  7778  8051 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:35.226  7778  8051 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:35.226  7778  8014 D bte_conf: Device ID record 1 : primary
09-06 18:58:35.226  7778  8014 D bte_conf:   vendorId            = 00c4
09-06 18:58:35.226  7778  8014 D bte_conf:   vendorIdSource      = 0001
09-06 18:58:35.226  7778  8014 D bte_conf:   product             = 13a1
09-06 18:58:35.226  7778  8014 D bte_conf:   version             = 1000
09-06 18:58:35.226  7778  8014 D bte_conf:   clientExecutableURL = 
09-06 18:58:35.226  7778  8014 D bte_conf:   serviceDescription  = 
09-06 18:58:35.226  7778  8014 D bte_conf:   documentationURL    = 
09-06 18:58:35.226  7778  8014 D bte_conf: bte_load_did_conf no section named DID2.
09-06 18:58:35.230  7778  8010 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 18:58:35.230  7778  8010 D BluetoothAdapterProperties: ScanMode =  20
09-06 18:58:35.230  7778  8010 D BluetoothAdapterProperties: State =  11
09-06 18:58:35.231  7778  8010 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 18:58:35.231  7778  8010 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 18:58:35.231  7778  8010 D BluetoothAdapterProperties: Setting state to 12
09-06 18:58:35.231  7778  8010 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 18:58:35.237  7778  8014 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 18:58:35.237  7778  8014 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 18:58:35.232  8080  8080 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:35.232  8080  8080 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:35.249  1034  1096 D BluetoothManagerService: Message: 60
09-06 18:58:35.249  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 18:58:35.249  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-06 18:58:35.254  7778  8049 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:35.255  7778  8049 W bt-smp  : Plain text(LSB ~ MSB) = 49 66 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:35.255  7778  8049 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 62 ef aa a1 20 3f b5 71 e2 6a ac ac c5 43 ce 
09-06 18:58:35.255  7778  8051 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 18:58:35.255  7778  8049 W bt-btm  : Stopping oneshot timer
09-06 18:58:35.264  7778  8075 E bt_mct  : hci lib postload completed
,09-06 18:58:35.287  7778  8049 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:35.287  7778  8049 W bt-smp  : Plain text(LSB ~ MSB) = 76 84 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:35.287  7778  8049 W bt-smp  : Encrypted text(LSB ~ MSB) = 6a 2f 3c 4c d0 35 32 f5 b2 0c 8a ae 0f 98 12 6e 
,09-06 18:58:35.290  7778  8049 W bt-btm  : Stopping oneshot timer
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:35.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:35.295  7778  8010 I BluetoothAdapterState: Entering On State
09-06 18:58:35.295  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:35.305  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:58:35.309  7778  8049 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:35.309  7778  8049 W bt-smp  : Plain text(LSB ~ MSB) = cc 5b 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:35.309  7778  8049 W bt-smp  : Encrypted text(LSB ~ MSB) = 92 c7 38 d5 4e 8e bc 69 7e 37 c1 2b 48 07 b8 aa 
09-06 18:58:35.310  7778  8049 W bt-btm  : Stopping oneshot timer
09-06 18:58:35.337  7778  8049 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:35.337  7778  8049 W bt-smp  : Plain text(LSB ~ MSB) = 73 d6 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 18:58:35.337  7778  8049 W bt-smp  : Encrypted text(LSB ~ MSB) = bc 6c 36 2c 80 ca d6 07 91 9e 62 2e 18 b8 cc e6 
,09-06 18:58:35.341  7778  8049 W bt-btm  : Stopping oneshot timer
09-06 18:58:35.344  7778  8010 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 18:58:35.344  7778  8010 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 18:58:35.344  7778  8010 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 18:58:35.345  7778  8010 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 18:58:35.346  7778  8010 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 18:58:35.352  7778  8014 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 18:58:35.352  7778  8014 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-06 18:58:35.354  7778  8049 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 18:58:35.354  7778  8049 W bt-smp  : Plain text(LSB ~ MSB) = f3 89 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-06 18:58:35.354  7778  8049 W bt-smp  : Encrypted text(LSB ~ MSB) = 0e 6e 37 0b 89 1e 2e af 8f 0b 35 de 6a 14 09 d2 
09-06 18:58:35.354  7778  8049 W bt-btm  : Stopping oneshot timer
09-06 18:58:35.360  1853  1853 D BluetoothHeadset: Proxy object connected
09-06 18:58:35.361  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:35.362  8095  8095 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 18:58:35.368  1034  1034 D BluetoothHeadset: Proxy object connected
,09-06 18:58:35.373  6995  7701 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 18:58:35.375  6995  7011 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 18:58:35.377  6995  7701 D BluetoothMap: onBluetoothStateChange: up=true
09-06 18:58:35.379  6995  7800 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:35.381  6995  7701 D BluetoothPan: onBluetoothStateChange on: true
09-06 18:58:35.381  6995  7701 D BluetoothPan: onBluetoothStateChange call bindService
09-06 18:58:35.382  6995  6995 D BluetoothA2dp: Proxy object connected
09-06 18:58:35.382  6995  6995 D A2dpProfile: Bluetooth service connected
,09-06 18:58:35.386  1853  4451 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:35.388  1853  1853 D BluetoothHeadset: Proxy object connected
09-06 18:58:35.388  1853  2451 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:58:35.389  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 18:58:35.389  1853  1853 D BluetoothHeadset: Proxy object connected
09-06 18:58:35.390  1034  1034 D BluetoothA2dp: Proxy object connected
09-06 18:58:35.390  6995  7011 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 18:58:35.391  6995  6995 D BluetoothMap: Proxy object connected
09-06 18:58:35.391  6995  6995 D MapProfile: Bluetooth service connected
09-06 18:58:35.391  6995  6995 D BluetoothMap: getConnectedDevices()
09-06 18:58:35.392  7778  7793 V BluetoothMapService: getConnectedDevices()
09-06 18:58:35.393  6995  6995 D BluetoothHeadset: Proxy object connected
09-06 18:58:35.393  6995  6995 D HeadsetProfile: Bluetooth service connected
09-06 18:58:35.394  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 18:58:35.394  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 18:58:35.394  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 18:58:35.396  1034  1096 D BluetoothManagerService: Message: 40
09-06 18:58:35.396  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,09-06 18:58:35.400  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.400  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 18:58:35.401  1941  2145 D LGBluetoothAPIService: Message: 1
09-06 18:58:35.401  1941  2145 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 18:58:35.401  1941  2145 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-06 18:58:35.401  1941  2145 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 18:58:35.403  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:35.408  7778  7778 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.408  7778  7778 D BluetoothMapService: STATE_ON
09-06 18:58:35.409  6995  6995 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:58:35.409  6995  6995 D PanProfile: Bluetooth service connected
,09-06 18:58:35.411  6995  6995 D BluetoothInputDevice: Proxy object connected
09-06 18:58:35.411  6995  6995 D HidProfile: Bluetooth service connected
09-06 18:58:35.416  6995  6995 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 18:58:35.417  6995  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 18:58:35.422  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
,09-06 18:58:35.422  6995  6995 D DockEventReceiver: finishStartingService: stopping service
09-06 18:58:35.422  7778  7778 V BluetoothPbapService: Pbap Service onCreate
09-06 18:58:35.422  7778  7778 V BluetoothPbapService: Starting PBAP service
09-06 18:58:35.423  7778  7778 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 18:58:35.423  7778  7778 V BluetoothPbapService: Pbap Service onBind
09-06 18:58:35.425  6995  6995 D BluetoothPbap: Proxy object connected
09-06 18:58:35.425  7778  7778 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.425  6995  6995 D PbapServerProfile: Bluetooth service connected
09-06 18:58:35.425  7778  7778 V BluetoothPbapService: state: 12
09-06 18:58:35.425  7778  7778 V BluetoothMapService: Handler(): got msg=1
09-06 18:58:35.425  7778  7778 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 18:58:35.426  7778  7778 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 18:58:35.426  7778  7778 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.426  7778  7778 V BluetoothPbapReceiver: ***********state = 12
09-06 18:58:35.427  7778  8105 D BluetoothMapMasInstance: MAS initSocket()
09-06 18:58:35.427  7778  7778 V BluetoothPbapService: Handler(): got msg=1
09-06 18:58:35.428  7778  8105 D BluetoothMapMasInstance:   masId = 00
09-06 18:58:35.428  7778  8105 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 18:58:35.428  7778  8105 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 18:58:35.428  7778  8105 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 18:58:35.428  7778  7778 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 18:58:35.429  7778  8106 V BluetoothPbapService: Pbap Service initSocket
09-06 18:58:35.429  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:35.430  2215  2215 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 18:58:35.430  2215  2215 D c       : Getting all permits...
09-06 18:58:35.430  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:35.430  2215  2215 D a       : Opening database...
09-06 18:58:35.431  7778  8105 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:35.432  7778  8105 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 18:58:35.432  7778  8105 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 18:58:35.432  7778  8105 D BluetoothMapMasInstance: Accepting socket connection...
09-06 18:58:35.432  7778  8014 D BluetoothAdapterProperties: Scan Mode:21
09-06 18:58:35.432  7778  8106 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:35.432  7778  8014 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 18:58:35.434  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:35.435  2215  2215 D a       : Opening database auth.proximity.permit_store...
09-06 18:58:35.435  7778  8106 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 18:58:35.435  7778  8106 V BluetoothPbapService: Succeed to create listening socket 
09-06 18:58:35.435  7778  8106 V BluetoothPbapService: Accepting socket connection...
09-06 18:58:35.437  2215  2215 D a       : Closing database...
09-06 18:58:35.445  6995  6995 D BluetoothPermissionRequest: onReceive
,09-06 18:58:35.447  6995  6995 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 18:58:35.449  6995  6995 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 18:58:35.452  7778  7778 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 18:58:35.453  7778  7778 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 18:58:35.458  7778  7778 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 18:58:35.475  7778  7778 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 18:58:35.476  7778  7778 V BtOppService: onCreate
,09-06 18:58:35.481  7778  7778 V BluetoothOppNotification: send message
09-06 18:58:35.484  7778  7778 V BtOppService: Starting RfcommListener
09-06 18:58:35.492  7778  7778 D BluetoothOppPreference: Dumping Names:  
09-06 18:58:35.492  7778  7778 D BluetoothOppPreference: {}
09-06 18:58:35.492  7778  7778 D BluetoothOppPreference: Dumping Channels:  
09-06 18:58:35.492  7778  7778 D BluetoothOppPreference: {}
09-06 18:58:35.492  7778  7778 V BtOppService: onStartCommand
09-06 18:58:35.493  7778  8111 V BtOppService: Deleted complete outbound shares, number =  0
,09-06 18:58:35.495  7778  8111 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 18:58:35.496  7778  8111 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 18:58:35.498  7778  8114 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 18:58:35.498  7778  8111 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c581e6c on behalf of 
09-06 18:58:35.498  7778  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 18:58:35.500  7778  7778 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.500  7778  7778 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 18:58:35.504  7778  7778 V BluetoothOppNotification: new notify threadi!
09-06 18:58:35.505  7778  7778 V BluetoothOppNotification: send delay message
09-06 18:58:35.505  7778  7778 V BtOppService: start RfcommListener
09-06 18:58:35.507  7778  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 18:58:35.508  7778  7778 V BtOppService: RfcommListener started
,09-06 18:58:35.509  7778  7778 V BtOppService: ContentObserver received notification
09-06 18:58:35.509  7778  7778 V BtOppService: ContentObserver received notification
,09-06 18:58:35.515  7778  8116 V BtOppRfcommListener: Starting RFCOMM listener....
,09-06 18:58:35.516  1034  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:35.517  7778  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e520c35 on behalf of 
09-06 18:58:35.523  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:35.523  7778  7778 V BluetoothFtpService: Ftp Service onCreate
09-06 18:58:35.523  7778  7778 I BluetoothFtpService: Ftp Service onCreate
09-06 18:58:35.524  7778  7778 V BluetoothFtpService: Ftp Service onStartCommand
,09-06 18:58:35.524  7778  7778 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.524  7778  7778 V BluetoothFtpService: Starting Listening on sockets
09-06 18:58:35.524  7778  7778 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 18:58:35.524  7778  7778 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 18:58:35.524  7778  7778 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 18:58:35.524  7778  7778 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.524  7778  7778 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 18:58:35.525  7778  7778 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 18:58:35.529  7778  8116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:35.531  7778  8116 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-06 18:58:35.531  7778  8116 V BtOppRfcommListener: Started RFCOMM listener....
09-06 18:58:35.531  7778  7778 V BluetoothFtpService: Handler(): got msg=1
09-06 18:58:35.531  7778  8116 I BtOppRfcommListener: Accept thread started.
09-06 18:58:35.532  7778  8116 V BtOppRfcommListener: Accepting connection...
09-06 18:58:35.534  7778  7778 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 18:58:35.534  7778  7778 V BluetoothFtpService: Ftp Service initSocket
09-06 18:58:35.536  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 18:58:35.537  7778  7778 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:35.538  7778  7778 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
09-06 18:58:35.539  7778  7778 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 18:58:35.540  7778  8117 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 18:58:35.552  7778  7778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bafab0
09-06 18:58:35.552  7778  7778 V BluetoothSapService: Sap Service onCreate
09-06 18:58:35.554  7778  7778 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:58:35.554  7778  7778 V BluetoothSapService: state: 12
09-06 18:58:35.554  7778  7778 V BluetoothSapService: Starting SAP server process
,09-06 18:58:35.556  7778  7778 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 18:58:35.542  8118  8118 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:35.552  8118  8118 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:35.558  1034  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1cb5c625 type 2 when 195693 com.google.android.gms} when 195693
09-06 18:58:35.559  7778  8119 V BluetoothSapService: Sap Service initRfcommSocket
09-06 18:58:35.562  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:35.564   312  8121 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 18:58:35.565  7778  8119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:58:35.566  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-06 18:58:35.570  8118  8118 V BT_SAP  : Event pipe created
09-06 18:58:35.570  8118  8118 V BT_SAP  : create_server_socket qcom.sap.server
09-06 18:58:35.570  8118  8118 V BT_SAP  : created socket fd 6
09-06 18:58:35.570  7778  8119 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
09-06 18:58:35.571  7778  8119 V BluetoothSapService: Succeed to create listening socket 
09-06 18:58:35.571  7778  8119 V BluetoothSapService: Accepting socket connection...
09-06 18:58:35.633  1034  2033 I art     : Explicit concurrent mark sweep GC freed 25415(1254KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.509ms total 121.072ms
09-06 18:58:35.633  7778  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1efb6796 on behalf of 
09-06 18:58:35.634  7778  8115 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-06 18:58:35.636  7778  8114 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 18:58:35.636  7778  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-06 18:58:35.636  7778  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 18:58:35.637  7778  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e9eff17 on behalf of 
09-06 18:58:35.639  7778  8114 V BluetoothOppNotification: update too frequent, put in queue
09-06 18:58:35.640  7778  8114 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 18:58:35.641  7778  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e35cf04 on behalf of 
09-06 18:58:35.643  7778  8115 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 18:58:35.646  7778  8115 V BluetoothOppNotification: outbound notification was removed.
09-06 18:58:35.646  7778  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-06 18:58:35.649  7778  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3148ced on behalf of 
,09-06 18:58:35.650  7778  8115 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 18:58:35.652  7778  8115 V BluetoothOppNotification: inbound notification was removed.
09-06 18:58:35.653  7778  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 18:58:35.655  7778  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3efe6722 on behalf of 
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:36.038  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:58:36.052  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:36.055  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:36.055  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@87ec80d added. We now have 8 listener(s)
09-06 18:58:36.055  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:58:36.061  1034  2030 D WifiServiceImplEx: setWifiEnabled: false pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 18:58:36.061  1034  2030 D WifiService: setWifiEnabled: false pid=6865, uid=10118
09-06 18:58:36.061  1034  2030 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 18:58:36.067  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:58:36.071  1034  1576 D WifiServiceImplEx: setWifiEnabled: true pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 18:58:36.071  1034  1576 D WifiService: setWifiEnabled: true pid=6865, uid=10118
09-06 18:58:36.072  1034  1576 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:58:36.090  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 18:58:36.091  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 18:58:36.091  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-06 18:58:36.092  1034  1393 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 18:58:36.092  1034  1393 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 18:58:36.095  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 18:58:36.095  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 18:58:36.095  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 18:58:36.095  1034  1393 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 18:58:36.095  1034  1393 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 18:58:36.095  1034  1393 E WifiHW  : unknown target_country: EU , set to default
09-06 18:58:36.095  1034  1393 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 18:58:36.095  1034  1393 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 18:58:36.095  1034  1393 I WifiUtil: gEnableBmps=1
09-06 18:58:36.507  7778  7778 V BluetoothOppNotification: new notify threadi!
,09-06 18:58:36.523  7778  7778 V BluetoothOppNotification: send delay message
09-06 18:58:36.530  7778  8134 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 18:58:36.532  7778  8134 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c0a75b3 on behalf of 
09-06 18:58:36.533  7778  8134 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 18:58:36.534  7778  8134 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 18:58:36.535  7778  8134 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bc2d770 on behalf of 
09-06 18:58:36.536  7778  8134 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 18:58:36.539  7778  8134 V BluetoothOppNotification: outbound notification was removed.
09-06 18:58:36.539  7778  8134 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 18:58:36.540  7778  8134 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@203a0ae9 on behalf of 
09-06 18:58:36.541  7778  8134 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 18:58:36.544  7778  8134 V BluetoothOppNotification: inbound notification was removed.
09-06 18:58:36.545  7778  8134 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 18:58:36.546  7778  8134 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13fd36e on behalf of 
09-06 18:58:36.778   312   894 D SoftapController: Softap fwReload - Ok
,09-06 18:58:36.791  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 18:58:36.791  1034  1096 D Tethering: InitialState.processMessage what=4
,09-06 18:58:36.799  1034  1393 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (699ms)
09-06 18:58:36.808   312   894 D CommandListener: Setting iface cfg
09-06 18:58:36.809   312   894 D CommandListener: Trying to bring down wlan0
09-06 18:58:36.812   312   894 D CommandListener: Clearing all IP addresses on wlan0
,09-06 18:58:36.821  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 18:58:36.825  1034  1393 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-06 18:58:36.845  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:36.845  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:36.845  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:36.832  8142  8142 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:36.832  8142  8142 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:36.859  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:36.868  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 18:58:36.899  1034  1393 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 18:58:36.899  1034  1393 D WifiMonitor: connecting to supplicant
,09-06 18:58:36.915  8142  8142 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 18:58:36.919  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 18:58:36.919  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:36.921  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 18:58:36.921  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 18:58:36.921  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 18:58:36.921  6995  6995 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 18:58:36.922  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 18:58:36.923  6995  6995 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 18:58:36.923  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 18:58:36.923  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 18:58:36.923  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 18:58:36.923  6995  6995 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 18:58:36.923  6995  6995 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 18:58:36.925  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 18:58:36.925  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 18:58:36.925  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 18:58:36.925  6995  6995 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 18:58:36.926  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 18:58:36.927  6995  6995 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 18:58:36.927  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 18:58:36.927  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 18:58:36.927  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 18:58:36.927  6995  6995 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 18:58:36.927  6995  6995 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 18:58:36.952  7881  7892 E UEI.SmartControl: file observer is disposed!
,09-06 18:58:36.955  8142  8142 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 18:58:36.956  8142  8142 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-06 18:58:36.981  1034  1905 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8161 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 18:58:37.061  8142  8142 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 18:58:37.117  1034  1960 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8182 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 18:58:37.122  8161  8180 W FormManager: Network not available. Please check & try again.
09-06 18:58:37.131  8161  8181 V FormManager: Network unavailable.
09-06 18:58:37.133  8142  8142 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-06 18:58:37.134  8161  8181 V FormManager: Network unavailable.
,09-06 18:58:37.144  8142  8142 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 18:58:37.146  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 18:58:37.146  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 18:58:37.146  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 18:58:37.146  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 18:58:37.146  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 18:58:37.146  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 18:58:37.147  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 18:58:37.148  1034  1393 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 18:58:37.149  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.149  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.150  1034  1393 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-06 18:58:37.150  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.151  1034  1393 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 18:58:37.151  1034  1393 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 18:58:37.151  1034  1393 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 18:58:37.152  1034  1393 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 18:58:37.152  1034  1393 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-06 18:58:37.153  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.153  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.153  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:58:37.153  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.153  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 18:58:37.154  1034  1393 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 18:58:37.154  1034  1393 E WifiStateMachine: useWiFiOffloading() : false
09-06 18:58:37.154  1034  1393 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 18:58:37.156  1034  1887 I ActivityManager: Killing 7269:com.android.chrome/u0a57 (adj 15): empty #17
09-06 18:58:37.199  1034  1393 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 18:58:37.200  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.200  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,09-06 18:58:37.201  1034  1960 W libprocessgroup: failed to open /acct/uid_10057/pid_7269/cgroup.procs: No such file or directory
09-06 18:58:37.201  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 18:58:37.201  1034  1393 D WifiNative-wlan0: SET update_config 1: returned true
09-06 18:58:37.202  1034  1393 D WifiConfigStore: Loading config and enabling all networks 
09-06 18:58:37.202  1034  1393 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 18:58:37.202  1941  1941 D WfdService: Waiting for WifiP2p enabling
09-06 18:58:37.202  1034  1393 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:58:37.204  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:58:37.206  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:58:37.209  1034  1393 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 18:58:37.221  1034  1393 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-06 18:58:37.221  1034  1393 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 18:58:37.222  1034  1393 D WifiStateMachine: enableVerboseLogging : level 2
09-06 18:58:37.222  1034  1393 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 18:58:37.222  1034  1393 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 18:58:37.223  1034  1393 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 18:58:37.223  1034  1393 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 18:58:37.223  1034  1393 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 18:58:37.223  1034  1393 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 18:58:37.223  1034  1393 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 18:58:37.224  1034  1393 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 18:58:37.224  1034  1393 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 18:58:37.224  1034  1393 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 18:58:37.224  1034  1393 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-06 18:58:37.225  1034  1393 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 18:58:37.225  1034  1393 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 18:58:37.225  1034  1393 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 18:58:37.226  1034  1393 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 18:58:37.226  1034  1393 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 18:58:37.227  1941  1941 D WfdsService: Supplicant Connection state is changed : true
09-06 18:58:37.227  1941  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 18:58:37.227  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-06 18:58:37.227  1941  2345 D WfdsMonitor: WfdsMonitorThread create
09-06 18:58:37.227  7809  7809 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.227  1941  2345 D WfdsMonitor: WFDS Monitor is created and started
09-06 18:58:37.227  1941  2345 D WfdsService: WiFi: Supplicant connection re-established
09-06 18:58:37.227  1034  1393 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 18:58:37.227  1034  1393 D WifiNative-HAL: Setting external_sim to 1
09-06 18:58:37.227  1034  1393 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 18:58:37.228  1941  8201 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 18:58:37.228  1034  1393 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 18:58:37.228  1034  1393 I WifiNative-HAL: startHal
09-06 18:58:37.228  1034  1393 D wifi    : setting scan oui 0x953e4480
09-06 18:58:37.228  1034  1393 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 18:58:37.229  1034  1393 I WifiNative-HAL: startHal
09-06 18:58:37.229  1034  1393 D wifi    : setting scan oui 0x953e4480
09-06 18:58:37.229  1034  1393 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 18:58:37.229  1034  1393 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 18:58:37.229  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 18:58:37.230  1941  8201 E CtrlSupplicant: Succeed to open control connection
09-06 18:58:37.230  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 18:58:37.230  1941  8201 E CtrlSupplicant: Succeed to open monitor connection
09-06 18:58:37.230  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 18:58:37.230  1941  8201 D WfdsMonitor: Supplicant connection established
09-06 18:58:37.230  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 18:58:37.230  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-06 18:58:37.230  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 18:58:37.231  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 18:58:37.231  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 18:58:37.231  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 18:58:37.231  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 18:58:37.231  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 18:58:37.231  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 18:58:37.232  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 18:58:37.232  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,09-06 18:58:37.232  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 18:58:37.232  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 18:58:37.232  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 18:58:37.232  8142  8142 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 18:58:37.233  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 18:58:37.233  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 18:58:37.233  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 18:58:37.233  1034  1393 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 18:58:37.234  1034  1393 E WifiNative: : [197,372,298 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 18:58:37.234  1034  1393 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 18:58:37.235  1034  1393 D WifiNative-wlan0: RECONNECT: returned true
,09-06 18:58:37.235  1034  1393 D WifiNative-wlan0: doString: [STATUS]
09-06 18:58:37.235  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 18:58:37.235  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-06 18:58:37.238  1034  1393 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 18:58:37.238  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:37.239  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
09-06 18:58:37.239  1034  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:37.239  8182  8182 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:37.241   312   894 D CommandListener: Setting iface cfg
09-06 18:58:37.241   312   894 D CommandListener: Trying to bring up p2p0
09-06 18:58:37.241  1034  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 18:58:37.241  1034  1391 D LGWifiP2pService: P2pEnablingState
09-06 18:58:37.241  1034  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.241  1034  1391 D LGWifiP2pService: P2p socket connection successful
09-06 18:58:37.241  1034  1391 D LGWifiP2pService: P2pEnabledState
09-06 18:58:37.242  1034  1391 D LGWifiP2pService: sending p2p connection changed broadcast
,09-06 18:58:37.242  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 18:58:37.242  1034  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 18:58:37.243  1034  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 18:58:37.243  1034  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 18:58:37.243  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 18:58:37.243  1034  1391 D WifiNative-p2p0: SET device_name G3: returned true
09-06 18:58:37.243  1034  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 18:58:37.243  1034  1391 D LGWifiP2pService: before postfix = G3
09-06 18:58:37.243  1034  1391 D WifiServerServiceExt: postfix byte check : 2
09-06 18:58:37.243  1034  1391 D LGWifiP2pService: after postfix = G3
09-06 18:58:37.243  1034  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 18:58:37.244  1034  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 18:58:37.244  1034  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 18:58:37.244  1941  1941 D WfdsService: WifiP2pState is changed : true
09-06 18:58:37.244  1034  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 18:58:37.244  1034  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 18:58:37.244  1941  2345 D WfdsService: Receive the WFDS_ENABLE Method
09-06 18:58:37.244  1941  2345 D WfdsService: Set the WFDS Monitor: true
09-06 18:58:37.244  1941  2345 D WfdsService: Connected to the supplicant for wfds
09-06 18:58:37.244  1941  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 18:58:37.245  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 18:58:37.245  8142  8142 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 18:58:37.245  1941  1941 D WfdsService: isConnected: false
09-06 18:58:37.245  1941  2345 D WfdsService: selectPreferredScanChannel [36]
09-06 18:58:37.245  1941  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 18:58:37.245  1034  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 18:58:37.245  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 18:58:37.246  1034  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 18:58:37.246  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress
09-06 18:58:37.246  1034  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 18:58:37.246  1034  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 18:58:37.246  1034  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 18:58:37.247  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 18:58:37.247  1034  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 18:58:37.247  1034  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 18:58:37.247  1034  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 18:58:37.248  1034  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 18:58:37.248  1034  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 18:58:37.248  1034  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 18:58:37.249  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 18:58:37.249  1941  1941 D WfdsService: Update P2p Interface State: 3
09-06 18:58:37.250  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 18:58:37.250  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-06 18:58:37.250  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.250  1034  1556 I WifiNative-HAL: startHal
09-06 18:58:37.251  1034  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.251  1034  1393 E WifiStateMachine:  Discon,nectedState CMD_SET_OPERATIONAL_MODE 1 0
,09-06 18:58:37.251  1034  1393 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 18:58:37.252  1034  1393 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 18:58:37.252  1034  1393 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 18:58:37.252  1034  1393 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 18:58:37.253  1034  1393 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 18:58:37.253  1034  1393 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 18:58:37.253  1034  1393 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 18:58:37.257  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:37.258  1034  1959 I ActivityManager: Killing 7287:com.lge.drmservice/u0a62 (adj 15): empty #17
09-06 18:58:37.261  8142  8142 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 18:58:37.261  1034  1393 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 18:58:37.262  1034  1393 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 18:58:37.262  1034  1393 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 18:58:37.262  1034  1393 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 18:58:37.262  8142  8142 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 18:58:37.263  1034  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 18:58:37.263  1034  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 18:58:37.263  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0x953e4480
09-06 18:58:37.263  1034  1556 D wifi    : failed to get capabilities : -3
09-06 18:58:37.263  1034  1556 E WifiScanningService: could not get scan capabilities
09-06 18:58:37.263  1034  1393 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 18:58:37.263  1034  1393 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,09-06 18:58:37.264  1034  1393 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 18:58:37.264  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 18:58:37.264  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 18:58:37.265  8142  8142 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.265  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 18:58:37.265  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.265  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.265  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.266  8142  8142 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 18:58:37.266  8142  8142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.266  1034  8200 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.266  1034  8200 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.266  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.266  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.267  8142  8142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.267  1034  8200 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.267  1034  8200 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.267  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-06 18:58:37.267  1941  8201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.267  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.267  1941  8201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.267  1034  1393 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 18:58:37.268  1034  1393 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 18:58:37.268  1034  1393 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 18:58:37.268  1034  1393 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 18:58:37.269  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,09-06 18:58:37.269  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 18:58:37.269  8142  8142 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:37.269  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 18:58:37.269  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:37.269  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:37.269  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 18:58:37.270  1034  1393 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 18:58:37.270  1034  1393 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 18:58:37.270  1034  1393 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,09-06 18:58:37.270  1034  1393 D WifiNative-wlan0: doBoolean: SCAN
09-06 18:58:37.270  1034  1393 D WifiNative-wlan0: SCAN: returned false
09-06 18:58:37.271  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=197409  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 18:58:37.355  1034  1391 D LGWifiP2pService: InactiveState
09-06 18:58:37.355  1034  1905 W libprocessgroup: failed to open /acct/uid_10062/pid_7287/cgroup.procs: No such file or directory
09-06 18:58:37.355  1034  1391 D LGWifiP2pService: InactiveState{ when=-108ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:37.356  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-108ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.356  1034  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 18:58:37.358  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 18:58:37.361  8142  8142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.364  8142  8142 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 18:58:37.364  8142  8142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-06 18:58:37.366  8142  8142 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-06 18:58:37.367  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.367  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.370  1034  8200 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 18:58:37.370  1034  8200 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.371  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 18:58:37.371  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-06 18:58:37.371  1034  8200 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.371  1034  8200 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.371  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.372  1034  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 18:58:37.372  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=197510  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 18:58:37.372  1034  1391 D LGWifiP2pService: InactiveState{ when=-105ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.372  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-105ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:37.372  1034  1391 D LGWifiP2pService: InactiveState{ when=-17ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.372  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.372  1034  1391 D LGWifiP2pService: DefaultState{ when=-17ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.373  1034  1393 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:37.373  1034  1391 D LGWifiP2pService: InactiveState{ when=-18ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.373  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:37.373  1034  1391 D LGWifiP2pService: DefaultState{ when=-18ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.373  1034  1391 D LGWifiP2pService: InactiveState{ when=-18ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.373  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.373  1034  1391 D LGWifiP2pService: DefaultState{ when=-18ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.374  1034  1391 D LGWifiP2pService: InactiveState{ when=-18ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.374  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:58:37.374  1034  1391 D LGWifiP2pService: DefaultState{ when=-19ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.374  1941  2345 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 18:58:37.374  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.374  1034  1034 E WifiServerServiceExt: No p2p device connected
09-06 18:58:37.374  1034  8200 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.374  1034  8200 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.375  1034  8200 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 18:58:37.375  1034  8200 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-06 18:58:37.368  1941  8201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 18:58:37.375  1941  8201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.375  1941  8201 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 18:58:37.376  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.378  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.378  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.379  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 18:58:37.380  1034  1393 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-06 18:58:37.384  1034  1393 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:37.387  1034  1393 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:37.390  1034  1393 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 18:58:37.393  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 18:58:37.393  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 18:58:37.397  8182  8182 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:37.399  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 18:58:37.402  8161  8205 W FormManager: Network not available. Please check & try again.
,09-06 18:58:37.407  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:37.408  8161  8206 V FormManager: Network unavailable.
09-06 18:58:37.413  8161  8206 V FormManager: Network unavailable.
09-06 18:58:37.423  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:37.423  4343  4343 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 18:58:37.425  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 18:58:37.427  4343  4343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 18:58:37.433  4343  8207 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 18:58:37.434  4343  8208 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 18:58:37.435  4343  8208 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 18:58:37.492  1034  1959 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 18:58:37.623  8209  8209 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 18:58:37.623  8209  8209 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 18:58:37.635  8209  8209 V [BNRBootReceiver]: Boot Receiver Return
09-06 18:58:37.636  8209  8209 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 18:58:37.707  1034  1758 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8230 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 18:58:37.710  1034  1758 I ActivityManager: Killing 7308:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-06 18:58:37.739  8142  8142 E wpa_supplicant: USIM:  scard_init function
09-06 18:58:37.740  8142  8142 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 18:58:37.742  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 18:58:37.742  1034  8200 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 18:58:37.742  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 18:58:37.742  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-06 18:58:37.742  1034  8200 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 18:58:37.742  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 18:58:37.742  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-06 18:58:37.743  1034  1393 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 18:58:37.743  1034  1393 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 18:58:37.744  1034  1393 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 18:58:37.744  1034  1393 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 18:58:37.744  1034  1393 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 18:58:37.770  1034  1787 W libprocessgroup: failed to open /acct/uid_10085/pid_7308/cgroup.procs: No such file or directory
,09-06 18:58:37.774  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=197912  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 18:58:37.777  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=197915  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 18:58:37.777  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.777  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.778  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.778  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.778  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 18:58:37.781  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.782  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.782  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.782  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-06 18:58:37.790   304   304 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
09-06 18:58:37.790   304   304 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-06 18:58:37.790   304   304 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 18:58:37.790  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.790   304   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
09-06 18:58:37.790  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.799  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:37.799  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-06 18:58:37.800  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.828  8230  8230 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 18:58:37.850   304   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
09-06 18:58:37.850   304   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 18:58:37.850   304   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
09-06 18:58:37.850   304   912 I rmt_storage: 
,09-06 18:58:37.852   304   304 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
09-06 18:58:37.853   901   910 E Diag_Lib: [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
09-06 18:58:37.856  8230  8230 D PluginManager: init()
09-06 18:58:37.856  8142  8142 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 18:58:37.859  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 18:58:37.860  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-06 18:58:37.860  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 18:58:37.861  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 18:58:37.861  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 18:58:37.862  1034  1393 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.862  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:37.862  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:37.862  1034  1393 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.862  1034  1393 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.863  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.863  1034  1393 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 18:58:37.864  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=198002  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 18:58:37.864  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=198003  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 18:58:37.865  1034  1393 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198003
09-06 18:58:37.865  1034  1393 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198004
09-06 18:58:37.866  1034  1393 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198004
09-06 18:58:37.866  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198004
09-06 18:58:37.866  8142  8142 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 18:58:37.866  1034  1393 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198005
09-06 18:58:37.866  8142  8142 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 18:58:37.867  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=198005  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 18:58:37.871  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:37.871  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:37.871  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 18:58:37.871  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 18:58:37.871  1034  8200 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 18:58:37.871  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 18:58:37.871  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 18:58:37.871  1034  8200 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 18:58:37.872  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:37.872  1034  8200 E Wi,fiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:37.872  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.872  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.873  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.873  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.873  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 18:58:37.874  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.876  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=198014  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 18:58:37.880  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.880  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.880  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,09-06 18:58:37.883  1034  1393 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=198021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 18:58:37.884  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=198022  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 18:58:37.884  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:37.884  1034  1393 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198023
09-06 18:58:37.884  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 18:58:37.885  1034  1393 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198023
09-06 18:58:37.886  1034  1393 D WifiNative-wlan0: doString: [STATUS]
09-06 18:58:37.886  1034  8200 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 18:58:37.886  1034  8200 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 18:58:37.887  1034  1393 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 18:58:37.889  1034  1393 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 18:58:37.893  1034  1393 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 18:58:37.893  1034  1393 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 18:58:37.898  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.898  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.898  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 18:58:37.899  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.899  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.900  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.900  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.900  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 18:58:37.901  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.902  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.902  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.903  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.904  1034  1393 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 18:58:37.904  1034  1393 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:58:37.904  1034  1393 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 18:58:37.904  1034  1414 D ConnectivityService: Got NetworkAgent Messenger
09-06 18:58:37.904  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 18:58:37.904  1034  1393 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 18:58:37.904  1034  1414 D ConnectivityService: NetworkAgent connected
09-06 18:58:37.904  1034  1393 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 18:58:37.905  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.905  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.906  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:37.912  1034  1393 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 18:58:37.913  1034  1393 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:58:37.913  1034  1393 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 18:58:37.915  1034  1393 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 18:58:37.915  1034  1393 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 18:58:37.919  1034  1393 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-06 18:58:37.921   312   894 D CommandListener: Setting iface cfg
09-06 18:58:37.924  1034  1393 E WifiStateMachine: Start Dhcp Watchdog 3
09-06 18:58:37.924  1034  8254 D DhcpStateMachine: StoppedState
09-06 18:58:37.924  1034  8254 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.924  1034  8254 D DhcpStateMachine: WaitBeforeStartState
09-06 18:58:37.924  1034  1393 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=198062  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:37.925  1034  1393 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=198063  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:37.925  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=198063  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:37.926  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:37.926  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-06 18:58:37.927  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:37.927  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 18:58:37.928  1034  1393 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198067  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:37.929  1034  1393 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198067  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:37.929  1034  1393 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198068  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 18:58:37.931  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14194] from screen [on:0 period:7335403] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 18:58:37.931  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:7335403] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 18:58:37.932  1034  1393 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-06 18:58:37.935  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.936  1034  1414 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-06 18:58:37.937  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.937  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.937  1034  1393 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.938  1034  1393 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.939  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.939  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.939  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 18:58:37.940  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=158,0,0
09-06 18:58:37.940  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=158,0,0
09-06 18:58:37.940  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 18:58:37.940  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 18:58:37.941  1034  1393 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 18:58:37.941  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 18:58:37.942  1034  1393 D WifiNative-wlan0: SET ps 0: returned true
09-06 18:58:37.942  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 18:58:37.942  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 18:58:37.942  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 18:58:37.942  1034  1393 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 18:58:37.942  1034  1393 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 18:58:37.942  1034  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1327dcfe target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.942  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1327dcfe target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.942  1034  1393 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 18:58:37.943  1034  8254 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.943  1034  8254 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 18:58:37.943   312   894 D CommandListener: Setting iface cfg
09-06 18:58:37.944   312   894 D CommandListener: Trying to bring up wlan0
,09-06 18:58:37.945  1034  1393 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 18:58:37.946  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.946  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.947  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 18:58:37.947  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 18:58:37.947  1034  1393 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.947  1034  1393 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.948  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.949  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 18:58:37.949  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 18:58:37.949  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 18:58:37.949  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 18:58:37.950  1034  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.950  1034  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:37.950  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 18:58:37.950  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 18:58:37.950  1034  1393 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 18:58:37.950  1034  1393 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 18:58:37.951  8142  8142 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 18:58:37.951  1034  1393 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 18:58:37.951  1034  1393 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 18:58:37.967  1034  1393 D WifiNative-wlan0: SET ps 1: returned true
,09-06 18:58:37.967  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 18:58:37.968  1034  1393 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 18:58:37.968  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 18:58:37.968  1034  1393 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 18:58:37.969  1034  1414 D ConnectivityService: ignoring duplicate network state non-change
09-06 18:58:37.972  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.972  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.972  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.972  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 18:58:37.972  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.974  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:37.976  1034  1414 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 18:58:37.977  1034  1414 D ConnectivityService: Adding iface wlan0 to network 102
09-06 18:58:37.977  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.977  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.977  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 18:58:37.979  1034  1393 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 18:58:37.980  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 18:58:37.982  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 18:58:37.984  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.984  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.984  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 18:58:37.984  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 18:58:37.989  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.989  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:58:37.989  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 18:58:37.997  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:37.997  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 18:58:37.998  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:38.000  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:38.000  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 18:58:38.000  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 18:58:38.002  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:58:38.002  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 18:58:38.002  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:38.013  1034  1414 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 18:58:38.013  1034  1414 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 18:58:38.014  1034  1414 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-06 18:58:38.015   312   894 E Netd    : netlink response contains error (File exists)
09-06 18:58:38.015  1034  1414 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-06 18:58:38.015  1034  1414 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 18:58:38.015  1034  1414 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-06 18:58:38.016  1034  1414 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-06 18:58:38.020  1034  1414 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 18:58:38.020  1034  1414 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.020  1034  1414 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.020  1034  1414 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.020  1034  1414 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:38.020  1034  1414 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:38.020  1034  1414 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 18:58:38.020  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:38.020  1034  1414 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.020  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 18:58:38.020  1034  1414 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 18:58:38.020  1034  1414 D ConnectivityService: currentScore = 0, newScore = 20
09-06 18:58:38.020  1034  1414 D ConnectivityService:    accepting network in place of null
09-06 18:58:38.020  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:58:38.020  1034  1414 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.020  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 18:58:38.020  1034  1393 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.020  1034  1393 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:38.021  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.021  1034  1414 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU:, 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 18:58:38.021  1034  1414 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 18:58:38.021  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 18:58:38.021  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:58:38.023  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 18:58:38.023   312  8258 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 18:58:38.024  1034  1414 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:58:38.024  1034  1414 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 18:58:38.024  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 18:58:38.024  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 18:58:38.024  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 18:58:38.025  1034  1414 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 18:58:38.025  1034  1414 D ConnectivityService: validation of new default Network = false
09-06 18:58:38.025  1034  1414 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 18:58:38.025  1034  1414 D DSQN    : enableDataServiceNotify 
09-06 18:58:38.025  1034  1414 D DSQN    : start dsqn bin
,09-06 18:58:38.031  1034  1414 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.031  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.031  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:38.031  1034  1414 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:38.031  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 18:58:38.022  8259  8259 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:38.022  8259  8259 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:38.038  1034  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-06 18:58:38.048  8259  8259 E DSQN    : DSQN ssw
,09-06 18:58:38.053  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 18:58:38.054  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:38.055  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:38.082   312  8258 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:38.105  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:58:38.107  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:58:38.111  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 18:58:38.111  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 18:58:38.112  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1851047 Bundle[{}]
09-06 18:58:38.113  6865  6943 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 18:58:38.113  6865  6943 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 18:58:38.113  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 18:58:38.114  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 18:58:38.114  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 18:58:38.115  6865  6943 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 18:58:38.115   312  8258 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-06 18:58:38.118  6865  6943 I System.out: Running OutgoingSocketThread
,09-06 18:58:38.121  6865  8263 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 876)
09-06 18:58:38.124  6865  8263 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52025
09-06 18:58:38.125  6865  8263 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-06 18:58:38.144  1034  8254 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 18:58:38.146  1034  8254 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-06 18:58:38.146  1034  8254 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 18:58:38.150   312   893 D LGDataListener: argv[0]=dsqncommand
09-06 18:58:38.150   312   893 D LGDataListener: argv[1]=wlan0
09-06 18:58:38.150   312   893 D LGDataListener: argv[2]=1
09-06 18:58:38.150   312   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 18:58:38.150  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
09-06 18:58:38.150  1034  1094 D DSQN    : start to monitor internet connection
09-06 18:58:38.142  8265  8265 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:38.142  8265  8265 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 18:58:38.168  8265  8265 I dhcpcd  : version 5.5.6 starting
09-06 18:58:38.170  8265  8265 E dhcpcd  : get_duid: m
09-06 18:58:38.170  8265  8265 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 18:58:38.170  8265  8265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-06 18:58:38.183  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 16:58:38 GMT], X-Android-Received-Millis=[1473181118181], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181118149]}
09-06 18:58:38.183  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 18:58:38.183  1034  8252 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-06 18:58:38.184  1034  1414 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.184  1034  1414 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.184  1034  1414 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:38.184  1034  1414 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:38.184  1034  1414 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 18:58:38.184  1034  1414 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-06 18:58:38.184  1034  1414 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 18:58:38.184  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.184  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:38.184  1034  1414 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:38.184  1034  1414 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.185  1034  1414 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 18:58:38.186  1034  1393 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 18:58:38.186  1034  1393 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:58:38.187  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 18:58:38.187  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:38.187  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-06 18:58:38.212  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 18:58:38.213  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:38.214  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 18:58:38.239  8265  8265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 18:58:38.239  7881  7996 D UEI.SmartControl: Internal timer expired: 3
09-06 18:58:38.239  7881  7996 D UEI.SmartControl: unbind internal service
09-06 18:58:38.239  8265  8265 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 18:58:38.239  8265  8265 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 18:58:38.239  8265  8265 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-06 18:58:38.239  8265  8265 D dhcpcd  : wlan0: sending REQUEST (xid 0x766b5e87), next in 3.00 seconds
09-06 18:58:38.241  7881  7881 D UEI.SmartControl: Service.onUnbind: IControl
09-06 18:58:38.241  7881  7881 D UEI.SmartControl: Service.onDestroy
09-06 18:58:38.242  7881  7881 D UEI.SmartControl: Lock is in USE false
09-06 18:58:38.242  7881  7881 D UEI.SmartControl: unbind internal service
09-06 18:58:38.242  7881  7881 D serial_port: close(fd = 24)
09-06 18:58:38.245  7881  7881 I UEI.SmartControl: Serial port is closed.
09-06 18:58:38.245  7881  7881 I UEI.SmartControl: Serial port is closed.
09-06 18:58:38.245  7881  7881 D UEI.SmartControl: Blaster closed
09-06 18:58:38.245  7881  7881 D UEI.SmartControl: Shut down QS...
09-06 18:58:38.245  7881  7881 D UEI.SmartControl: Stopping QS lib
09-06 18:58:38.245  7881  7881 D UEI.SmartControl: QS lib stop result = true
09-06 18:58:38.245  7881  7881 D UEI.SmartControl: Stopped QS lib
09-06 18:58:38.245  7881  7881 D UEI.SmartControl: QS shutdown complete
09-06 18:58:38.277  8230  8230 W ExternalStrings: load override strings
09-06 18:58:38.277  8230  8230 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 18:58:38.277  8230  8230 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 18:58:38.279  8230  8230 D StatusProvider: onCreate
,09-06 18:58:38.290  8265  8265 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-06 18:58:38.315  8230  8230 V Signer  : override build config not found
09-06 18:58:38.315  8230  8230 D Signer  : value of property debug is false
,09-06 18:58:38.328  8265  8265 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds,
09-06 18:58:38.328  8265  8265 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 18:58:38.329  8265  8265 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-06 18:58:38.329  8265  8265 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 18:58:38.329  8265  8265 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-06 18:58:38.330  8265  8265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 18:58:38.330  8265  8265 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 18:58:38.330  8265  8265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-06 18:58:38.340  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-06 18:58:38.340  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-06 18:58:38.340  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-06 18:58:38.340  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,09-06 18:58:38.340  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-06 18:58:38.340  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.,
09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-06 18:58:38.341  8230  8230 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-06 18:58:38.348  8230  8230 V LGMDMManager: Create singleton instance
,09-06 18:58:38.433  8230  8230 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-06 18:58:38.504  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:38.504  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:38.519  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:38.524  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:38.550  1034  1787 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8299 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 18:58:38.550  1034  1787 I ActivityManager: Killing 7332:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-06 18:58:38.700  8230  8288 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 18:58:38.754  1034  8254 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-06 18:58:38.757  1034  8254 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-06 18:58:38.760  1034  8254 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-06 18:58:38.760  1034  8254 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 18:58:38.760  1034  8254 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 18:58:38.760  1034  8254 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,09-06 18:58:38.760  1034  8254 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 18:58:38.760  1034  8254 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 18:58:38.761  1034  8254 D DhcpStateMachine: RunningState
,09-06 18:58:38.809  1034  1959 W libprocessgroup: failed to open /acct/uid_10093/pid_7332/cgroup.procs: No such file or directory
,09-06 18:58:38.854  8299  8299 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 18:58:38.890  8299  8299 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-06 18:58:38.923  8299  8299 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-06 18:58:38.924  8299  8299 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 18:58:38.924  8299  8299 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,09-06 18:58:38.925  8299  8299 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 18:58:38.925  8299  8299 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 18:58:38.927  8299  8299 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 18:58:38.933  8299  8299 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 18:58:38.939  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:38.941  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:38.962  8299  8299 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 18:58:38.964  8299  8299 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 18:58:38.964  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 18:58:38.967  6995  6995 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 18:58:38.970  8299  8299 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 18:58:38.970  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:38.974  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:38.977  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:38.983  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:38.990  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:38.990  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:38.992  8299  8299 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 18:58:38.996  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:38.997  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.006  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:39.015  8230  8288 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:39.015  8230  8288 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:39.019  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:39.035  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.035  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.036  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.039  1034  1393 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:39.039  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 18:58:39.039  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 18:58:39.039  6995  6995 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 18:58:39.040  6995  6995 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 18:58:39.040  1034  1393 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:39.040  1034  1393 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:39.040  1034  1393 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:39.041  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 18:58:39.041  1034  1393 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:39.042  1034  1393 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 18:58:39.042  6995  6995 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 18:58:39.042  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 18:58:39.042  1034  1414 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-06 18:58:39.042  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 18:58:39.042  1034  1414 D ConnectivityService: identical MTU - not setting
,09-06 18:58:39.042  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 18:58:39.042  6995  6995 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 18:58:39.042  1034  1414 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 18:58:39.042  1034  1414 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 18:58:39.043  6995  6995 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 18:58:39.043  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 18:58:39.043  1034  1414 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 18:58:39.043  6995  6995 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 18:58:39.043  1034  1414 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-06 18:58:39.047  1604  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 18:58:39.049  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.050  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.057  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:39.077  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.083  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.084  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.084  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.086  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:39.087  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.095  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:39.101  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.107  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.107  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.108  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.110  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.111  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 18:58:39.119  6865  6943 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 877)
09-06 18:58:39.120  6865  6943 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 877)
09-06 18:58:39.124  6865  6943 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
,09-06 18:58:39.124  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:39.125  6865  6943 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 18:58:39.126  6865  6943 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883)
09-06 18:58:39.130  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.130  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fd53c2 added. We now have 2 listener(s)
09-06 18:58:39.130  1034  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.130  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.134  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.134  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.134  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.134  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.134  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66df5d3 added. We now have 9 listener(s)
,09-06 18:58:39.134  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.136  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:58:39.141  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.141  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.141  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.141  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:39.145  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:39.145  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.147  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.147  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:39.147  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.147  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125cd809 added. We now have 3 listener(s)
09-06 18:58:39.148  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.149  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.149  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 18:58:39.151  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 18:58:39.151  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.151  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.152  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.152  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b50ea0e added. We now have 10 listener(s)
09-06 18:58:39.152  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.153  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:39.153  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.153  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.153  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:39.153  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.153  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.153  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.153  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.153  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fd53c2 removed from the list
09-06 18:58:39.153  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.153  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66df5d3 removed from the list
09-06 18:58:39.153  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:39.153  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.155  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.155  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.156  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.156  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.156  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.156  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66df5d3 not in the list
09-06 18:58:39.156  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.156  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 18:58:39.156  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.157  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryM,anager: stopDiscovery
09-06 18:58:39.157  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.157  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.157  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b50ea0e removed from the list
09-06 18:58:39.157  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.157  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.157  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.157  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.157  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125cd809 removed from the list
09-06 18:58:39.158  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.159  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d981c2f added. We now have 2 listener(s)
09-06 18:58:39.159  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.161  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.161  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.161  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.161  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.162  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db4823c added. We now have 9 listener(s)
09-06 18:58:39.162  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.162  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:58:39.164  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:39.170  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:39.170  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.172  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.172  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:39.172  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.173  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b35991a added. We now have 3 listener(s)
09-06 18:58:39.173  1034  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.176  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.176  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.176  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.176  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.176  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e944c4b added. We now have 10 listener(s)
09-06 18:58:39.176  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.176  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 18:58:39.176  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:58:39.176  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:58:39.176  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.176  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:58:39.176  8230  8288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-06 18:58:39.177  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.177  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.178  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.178  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.181  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.182  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:58:39.183  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.187  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 18:58:39.187  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 18:58:39.189  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:58:39.189  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:58:39.191  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.192  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.194  6865  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 18:58:39.194  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.194  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:39.196  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:39.196  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.196  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:39.196  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.196  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.196  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.196  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.197  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d981c2f removed from the list
09-06 18:58:39.197  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.197  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db4823c removed from the list
09-06 18:58:39.197  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:39.197  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.197  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.197  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.198  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.198  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.198  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.198  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db4823c not in the list
09-06 18:58:39.198  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.198  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.199  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:3,9.200  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:39.200  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:39.200  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.200  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.200  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e944c4b removed from the list
09-06 18:58:39.200  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.200  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.200  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.200  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.200  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b35991a removed from the list
09-06 18:58:39.201  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.201  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e842ce6 added. We now have 2 listener(s)
09-06 18:58:39.202  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 18:58:39.208  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 18:58:39.209  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-06 18:58:39.210  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.210  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.210  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.210  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.210  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13d96227 added. We now have 9 listener(s)
09-06 18:58:39.210  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.211  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:58:39.213  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:39.217  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:39.219  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.219  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.220  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:39.220  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.220  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27bece7d added. We now have 3 listener(s)
09-06 18:58:39.221  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.222  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.225  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.225  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.225  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.225  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.225  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:58:39.225  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d63172 added. We now have 10 listener(s)
09-06 18:58:39.226  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.226  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:39.226  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-06 18:58:39.226  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:39.226  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:58:39.227  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:58:39.227  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.227  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:58:39.228  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 18:58:39.229  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 18:58:39.230  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.230  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.232  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-06 18:58:39.232  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:58:39.232  8230  8288 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-06 18:58:39.233  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.236  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.237  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 18:58:39.238  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:58:39.239  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:58:39.240  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.240  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.242  6865  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-06 18:58:39.242  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:39.242  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.242  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:39.242  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.242  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.242  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.242  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.242  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e842ce6 removed from the list
09-06 18:58:39.242  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.242  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13d96227 removed from the list
09-06 18:58:39.243  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:39.243  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.243  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.243  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.243  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.244  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.244  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.244  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.244  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13d96227 not in the list
09-06 18:58:39.244  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.244  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.244  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-06 18:58:39.245  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.245  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:39.245  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:39.245  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.245  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.245  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnect,orlib.DiscoveryManager@d63172 removed from the list
09-06 18:58:39.246  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.246  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.246  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.246  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.246  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27bece7d removed from the list
09-06 18:58:39.246  8230  8288 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-06 18:58:39.246  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.247  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6ed579 added. We now have 2 listener(s)
09-06 18:58:39.249  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 18:58:39.249  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 18:58:39.256  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.256  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.257  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.257  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.257  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd1f2be added. We now have 9 listener(s)
09-06 18:58:39.257  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:58:39.257  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:58:39.259  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.260  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:39.273  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:58:39.273  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 18:58:39.274  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 18:58:39.274  8299  8299 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 18:58:39.275  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.276  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:39.276  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.276  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113af26c added. We now have 3 listener(s)
09-06 18:58:39.276  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.277  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.278  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.278  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.280  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.280  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.281  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.281  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.281  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.281  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377e5035 added. We now have 10 listener(s)
09-06 18:58:39.281  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.281  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:39.281  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:58:39.281  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:58:39.281  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.281  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:58:39.283  8182  8182 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 18:58:39.285  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:58:39.285  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.288  8182  8182 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 18:58:39.292  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 18:58:39.292  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 18:58:39.293  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 18:58:39.295  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:58:39.295  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.297  6865  6943 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 18:58:39.298  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 18:58:39.303  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:39.303  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.303  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:39.303  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.303  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.303  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.303  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.303  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6ed579 removed from the list
09-06 18:58:39.303  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.303  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd1f2be removed from the list
09-06 18:58:39.303  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:58:39.303  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.304  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.304  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.305  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.305  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.305  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.305  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd1f2be not in the list
09-06 18:58:39.305  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.305  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.307  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.307  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.308  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.308  6865  6943 D BluetoothLeScanner: could not find callback wrapper
09-06 18:58:39.308  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:58:39.308  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.308  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.308  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377e5035 removed from the list
09-06 18:58:39.309  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.309  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.309  8299  8299 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 18:58:39.309  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.309  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.309  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113af26c removed from the list
09-06 18:58:39.310  8299  8299 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 18:58:39.310  8299  8299 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 18:58:39.310  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.310  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@101ac958 added. We now have 2 listener(s)
09-06 18:58:39.311  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 18:58:39.314  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.314  8230  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 18:58:39.317  8182  8182 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 18:58:39.317  8182  8182 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 18:58:39.318  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.318  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.318  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.318  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.318  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d0bab1 added. We now have 9 listener(s)
09-06 18:58:39.318  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.319  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:58:39.323  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:58:39.323  6995  6995 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:58:39.329  6865  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:58:39.332  6865  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:58:39.332  6865  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:58:39.332  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:58:39.333  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c92317 added. We now have 3 listener(s)
09-06 18:58:39.333  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 18:58:39.335  6995  6995 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 18:58:39.335  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.336  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 18:58:39.336  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:58:39.336  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:58:39.336  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:58:39.336  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a1f2304 added. We now have 10 listener(s)
09-06 18:58:39.337  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:58:39.337  6865  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:58:39.337  6865  6943 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:58:39.337  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.337  6865  6943 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:58:39.337  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.337  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.337  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:58:39.337  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othConnector: shutdown: Shutting down...
09-06 18:58:39.337  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@101ac958 removed from the list
09-06 18:58:39.337  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.338  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d0bab1 removed from the list
09-06 18:58:39.338  6865  6943 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:58:39.338  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.341  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:58:39.341  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.342  8299  8299 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 18:58:39.342  8299  8299 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 18:58:39.342  8299  8299 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 18:58:39.343  8299  8299 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 18:58:39.343  8299  8299 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 18:58:39.344  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.344  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.344  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.344  6865  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d0bab1 not in the list
09-06 18:58:39.344  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.344  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.346  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:58:39.346  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:58:39.346  6865  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:58:39.346  6865  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a1f2304 removed from the list
09-06 18:58:39.346  6865  6943 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:58:39.346  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-06 18:58:39.346  6865  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:58:39.347  6865  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:58:39.347  6865  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:58:39.347  6865  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c92317 removed from the list
09-06 18:58:39.348  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 18:58:39.348  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 18:58:39.348  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 18:58:39.349  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:58:39.349  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop ,operation: Should affect listening to advertisements only
09-06 18:58:39.349  6865  6943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:58:39.350  8299  8299 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 18:58:39.351  8299  8299 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 18:58:39.351  8299  8299 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 18:58:39.359  6865  8347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 890, name: My test thread name)
09-06 18:58:39.360  6865  8347 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 890, thread name: My test thread name)
,09-06 18:58:39.360  6865  8347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 890, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 18:58:39.362  6865  8348 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 892, name: My test thread name)
09-06 18:58:39.363  6865  8348 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 892, thread name: My test thread name)
09-06 18:58:39.363  6865  8348 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 892, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 18:58:39.365  6865  6943 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 18:58:39.365  6865  6943 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 18:58:39.365  6865  6943 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 18:58:39.365  6865  6943 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 18:58:39.365  6865  6943 D com.test.thalitest.ThaliTestRunner: Total duration: 23990 ms
09-06 18:58:39.367  6865  6943 I jxcore-log: *Native tests were executed*
09-06 18:58:39.367  6865  6943 I jxcore-log: 
09-06 18:58:39.367  6865  6943 I jxcore-log: Total number of executed tests:  80
09-06 18:58:39.367  6865  6943 I jxcore-log: 
09-06 18:58:39.367  6865  6943 I jxcore-log: Number of passed tests:  80
09-06 18:58:39.367  6865  6943 I jxcore-log: 
09-06 18:58:39.367  6865  6943 I jxcore-log: Number of failed tests:  0
09-06 18:58:39.367  6865  6943 I jxcore-log: 
09-06 18:58:39.367  6865  6943 I jxcore-log: Number of ignored tests:  0
09-06 18:58:39.367  6865  6943 I jxcore-log: 
09-06 18:58:39.368  6865  6943 I jxcore-log: Total duration:  23990
09-06 18:58:39.368  6865  6943 I jxcore-log: 
09-06 18:58:39.368  6865  6943 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 18:58:39.368  6865  6943 I jxcore-log: 
,09-06 18:58:39.372  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.372  6865  6943 I jxcore-log: 
09-06 18:58:39.375  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.375  6865  6943 I jxcore-log: 
09-06 18:58:39.376  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.376  6865  6943 I jxcore-log: 
09-06 18:58:39.377  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.377  6865  6943 I jxcore-log: 
09-06 18:58:39.378  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.378  6865  6943 I jxcore-log: 
09-06 18:58:39.379  6865  6865 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 18:58:39.380  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.380  6865  6943 I jxcore-log: 
09-06 18:58:39.382  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.382  6865  6943 I jxcore-log: 
09-06 18:58:39.384  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:58:39.384  6865  6943 I jxcore-log: 
09-06 18:58:39.385  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:58:39.385  6865  6943 I jxcore-log: 
09-06 18:58:39.385  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.385  6865  6943 I jxcore-log: 
09-06 18:58:39.386  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.386  6865  6943 I jxcore-log: 
09-06 18:58:39.387  8299  8299 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:39.387  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:58:39.387  6865  6943 I jxcore-log: 
09-06 18:58:39.387  8299  8299 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 18:58:39.388  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:58:39.388  6865  6943 I jxcore-log: 
09-06 18:58:39.389  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:58:39.389  6865  6943 I jxcore-log: 
09-06 18:58:39.390  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.390  6865  6943 I jxcore-log: 
09-06 18:58:39.390  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.390  6865  6943 I jxcore-log: 
09-06 18:58:39.391  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.391  6865  6943 I jxcore-log: 
09-06 18:58:39.392  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.392  6865  6943 I jxcore-log: 
,09-06 18:58:39.392  8299  8299 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 18:58:39.392  8299  8299 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 18:58:39.392  8299  8299 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 18:58:39.392  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.392  6865  6943 I jxcore-log: 
09-06 18:58:39.392  8299  8299 V SoundPool: doLoad: loading sample sampleID=1
09-06 18:58:39.393  8299  8299 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 18:58:39.393  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.393  6865  6943 I jxcore-log: 
09-06 18:58:39.394  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.394  6865  6943 I jxcore-log: 
09-06 18:58:39.394  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:58:39.394  6865  6943 I jxcore-log: 
09-06 18:58:39.395  7881  7881 D UEI.SmartControl: QS Service created
09-06 18:58:39.395  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:58:39.395  6865  6943 I jxcore-log: 
09-06 18:58:39.395  8299  8299 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 18:58:39.396  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.396  6865  6943 I jxcore-log: 
09-06 18:58:39.396  8299  8353 V SoundPool: Start decode
09-06 18:58:39.396  8299  8353 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 18:58:39.396  8299  8299 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 18:58:39.396  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.396  6865  6943 I jxcore-log: 
09-06 18:58:39.397  8299  8299 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 18:58:39.397  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.397  6865  6943 I jxcore-log: 
09-06 18:58:39.397   316  1404 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 18:58:39.397   316  1404 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 18:58:39.397   316  1404 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 18:58:39.397   316  1404 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 18:58:39.397   316  1404 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 18:58:39.397   316  1404 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 18:58:39.397   316  1404 V MediaPlayerService: player type = 3
09-06 18:58:39.397   316  1404 V AwesomePlayer: AwesomePlayer create()
09-06 18:58:39.398   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:39.398   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:39.398   316  1404 V AwesomePlayer: setAudioSink() 
09-06 18:58:39.398   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:39.398   316  1404 V AudioCache: notify(0xb04098c0, 8, 0, 0)
09-06 18:58:39.398   316  1404 V AudioCache: ignored
09-06 18:58:39.398   316  ,1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:39.398   316  1404 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 18:58:39.398  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.398  6865  6943 I jxcore-log: 
09-06 18:58:39.398   316  1404 V AwesomePlayer: setDataSource_l dataSource
09-06 18:58:39.398   316  1404 V LGParserOSAL: SniffLGParser start
09-06 18:58:39.398   316  1404 V LGParserOSAL: MainType:5, SubType=0
09-06 18:58:39.398   316  1404 V LGParserOSAL: #### check Mime : application/ogg
09-06 18:58:39.398   316  1404 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 18:58:39.398   316  1404 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 18:58:39.399  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.399  6865  6943 I jxcore-log: 
09-06 18:58:39.399  6865  6943 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:58:39.399  6865  6943 I jxcore-log: 
09-06 18:58:39.416  7881  7881 I UEI.SmartControl: Service initServices...
09-06 18:58:39.416  7881  7881 D UEI.SmartControl: QS start get config
09-06 18:58:39.416  8299  8299 V LGMDMManager: Create singleton instance
,09-06 18:58:39.421   316  1404 V LGParserOSAL: supported mime: application/ogg
09-06 18:58:39.421   316  1404 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 18:58:39.421   316  1404 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 18:58:39.421   316  1404 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 18:58:39.421   316  1404 V AwesomePlayer: AudioTrack Setting
09-06 18:58:39.421   316  1404 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 18:58:39.421   316  1404 V AwesomePlayer: setAudioSource() 
09-06 18:58:39.421   316  1404 V MediaPlayerService: prepare
09-06 18:58:39.421   316  1404 V AwesomePlayer: prepareAsync_l() 
09-06 18:58:39.421   316  1404 V MediaPlayerService: wait for prepare
09-06 18:58:39.422   316  8354 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 18:58:39.422   316  8354 V AwesomePlayer: initAudioDecoder() 
,09-06 18:58:39.422   316  8354 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 18:58:39.422   316  8354 V AudioSystem: isOffloadSupported()
09-06 18:58:39.422   316  8354 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 18:58:39.422   316  8354 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 18:58:39.422   316  8354 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 18:58:39.422   316  8354 V AwesomePlayer: getUseOffload() = 0 
09-06 18:58:39.422   316  8354 V OMXCodec: OMXCodec::Create
09-06 18:58:39.422   316  8354 V OMXCodec: findMatchingCodecs()
09-06 18:58:39.423   316  8354 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,09-06 18:58:39.423   316  8354 V OMXCodec: matchingCodecs.size()=1
09-06 18:58:39.423   316  8354 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 18:58:39.425   316  8354 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 18:58:39.425   316  8354 V LGCodecAdapter: LG Codec Adapter start
09-06 18:58:39.425   316  8354 V OMXCodec: OMXCodec Createtor
09-06 18:58:39.425   316  8354 V OMXCodec: setComponentRole
09-06 18:58:39.425   316  8354 V OMXCodec: configureCodec protected=0
09-06 18:58:39.425   316  8354 V LGCodecAdapter: called getLGCodecSpecificData
09-06 18:58:39.425   316  8354 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 18:58:39.425   316  8354 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 18:58:39.425   316  8354 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 18:58:39.425   316  8354 V LGCodecOSAL: Not support LGCodec
09-06 18:58:39.425   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 18:58:39.425   316  8354 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 18:58:39.425   316  8354 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 18:58:39.425   316  8354 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 18:58:39.425   316  8354 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 18:58:39.425   316  8354 V AudioSystem: isOffloadSupported()
09-06 18:58:39.425   316  8354 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 18:58:39.425   316  8354 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 18:58:39.425   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 18:58:39.425   316  8354 V OMXCodec: init()
09-06 18:58:39.425   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 18:58:39.425   316  8354 V OMXCodec: allocateBuffers
09-06 18:58:39.425   316  8354 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 18:58:39.425   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 18:58:39.425   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-06 18:58:39.426   316  8354 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-06 18:58:39.426   316  8354 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
09-06 18:58:39.426   316  8354 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 18:58:39.426   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 18:58:39.426   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 18:58:39.426   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 18:58:39.426   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 18:58:39.426   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 18:58:39.426   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 18:58:39.426   316  8354 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 18:58:39.426   316  8354 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 18:58:39.426   316  8354 V AudioCache: notify(0xb04098c0, 5, 0, 0)
09-06 18:58:39.426   316  8354 V AudioCache: ignored
09-06 18:58:39.426   316  8354 V AudioCache: notify(0xb04098c0, 1, 0, 0)
09-06 18:58:39.426   316  8354 V AudioCache: prepared
09-06 18:58:39.426   316  1404 V AudioCache: wait - success
09-06 18:58:39.426   316  1404 V MediaPlayerService: start
09-06 18:58:39.426   316  1404 V AwesomePlayer: play_l() 
09-06 18:58:39.426   316  1404 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 18:58:39.426   316  1404 V AwesomePlayer: createAudioPlayer_l
09-06 18:58:39.426   316  1404 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 18:58:39.426   316  1404 V AwesomePlayer: startAudioPlayer_l() 
09-06 18:58:39.426   316  1404 D AudioPlayer: start of Playback, useOffload 0
09-06 18:58:39.426   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 18:58:39.426   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 18:58:39.429   316  8356 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff380 on output port
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 18:58:39.429   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 18:58:39.433   316  1404 V AudioCache: open(48000, 2, 0x0, 1, 4)
,09-06 18:58:39.436   316  1404 V AudioCache: notify(0xb04098c0, 6, 0, 0)
09-06 18:58:39.436   316  1404 V AudioCache: ignored
09-06 18:58:39.437   316  1404 V MediaPlayerService: wait for playback complete
09-06 18:58:39.437   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.437   316  8357 V AudioCache: memcpy(0xac200000, 0xb0405000, 4096)
09-06 18:58:39.439   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.439   316  8357 V AudioCache: memcpy(0xac201000, 0xb0405000, 4096)
09-06 18:58:39.440   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.440   316  8357 V AudioCache: memcpy(0xac202000, 0xb0405000, 4096)
09-06 18:58:39.440   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.440   316  8357 V AudioCache: memcpy(0xac203000, 0xb0405000, 4096)
09-06 18:58:39.441   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.441   316  8357 V AudioCache: memcpy(0xac204000, 0xb0405000, 4096)
09-06 18:58:39.441   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.441   316  8357 V AudioCache: memcpy(0xac205000, 0xb0405000, 4096)
09-06 18:58:39.442   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.442   316  8357 V AudioCache: memcpy(0xac206000, 0xb0405000, 4096)
09-06 18:58:39.442   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.442   316  8357 V AudioCache: memcpy(0xac207000, 0xb0405000, 4096)
09-06 18:58:39.443   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.443   316  8357 V AudioCache: memcpy(0xac208000, 0xb0405000, 4096)
09-06 18:58:39.443   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.443   316  8357 V AudioCache: memcpy(0xac209000, 0xb0405000, 4096)
09-06 18:58:39.444   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.444   316  8357 V AudioCache: memcpy(0xac20a000, 0xb0405000, 4096)
09-06 18:58:39.444   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.444   316  8357 V AudioCache: memcpy(0xac20b000, 0xb0405000, 4096)
09-06 18:58:39.445   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.445   316  8357 V AudioCache: memcpy(0xac20c000, 0xb0405000, 4096)
09-06 18:58:39.445   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.445   316  8357 V AudioCache: memcpy(0xac20d000, 0xb0405000, 4096)
09-06 18:58:39.446   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.446   316  8357 V AudioCache: memcpy(0xac20e000, 0xb0405000, 4096)
09-06 18:58:39.446   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.446   316  8357 V AudioCache: memcpy(0xac20f000, 0xb0405000, 4096)
,09-06 18:58:39.449   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.449   316  8357 V AudioCache: memcpy(0xac210000, 0xb0405000, 4096)
09-06 18:58:39.449   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.449   316  8357 V AudioCache: memcpy(0xac211000, 0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: memcpy(0xac212000, 0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: memcpy(0xac213000, 0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: memcpy(0xac214000, 0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.450   316  8357 V AudioCache: memcpy(0xac215000, 0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: memcpy(0xac216000, 0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: memcpy(0xac217000, 0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: memcpy(0xac218000, 0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.451   316  8357 V AudioCache: memcpy(0xac219000, 0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: memcpy(0xac21a000, 0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: memcpy(0xac21b000, 0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: memcpy(0xac21c000, 0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.452   316  8357 V AudioCache: memcpy(0xac21d000, 0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: memcpy(0xac21e000, 0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: memcpy(0xac21f000, 0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: memcpy(0xac220000, 0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.454   316  8357 V AudioCache: memcpy(0xac221000, 0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: memcpy(0xac222000, 0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: memcpy(0xac223000, 0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: memcpy(0xac224000, 0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: memcpy(0xac225000, 0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.456   316  8357 V AudioCache: memcpy(0xac226000, 0xb0405000, 4096)
09-06 18:58:39.457   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.457   316  8357 V AudioCache: memcpy(0xac227000, 0xb0405000, 4096)
09-06 18:58:39.457   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.457   316  8357 V AudioCache: memcpy(0xac228000, 0xb0405000, 4096)
09-06 18:58:39.457   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.457   316  8357 V AudioCache: memcpy(0xac229000, 0xb0405000, 4096)
09-06 18:58:39.458   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.458   316  8357 V AudioCache: mem,cpy(0xac22a000, 0xb0405000, 4096)
09-06 18:58:39.458   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.459   316  8357 V AudioCache: memcpy(0xac22b000, 0xb0405000, 4096)
,09-06 18:58:39.459   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.459   316  8357 V AudioCache: memcpy(0xac22c000, 0xb0405000, 4096)
09-06 18:58:39.459   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.459   316  8357 V AudioCache: memcpy(0xac22d000, 0xb0405000, 4096)
09-06 18:58:39.460   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.460   316  8357 V AudioCache: memcpy(0xac22e000, 0xb0405000, 4096)
09-06 18:58:39.460   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.460   316  8357 V AudioCache: memcpy(0xac22f000, 0xb0405000, 4096)
09-06 18:58:39.460   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.460   316  8357 V AudioCache: memcpy(0xac230000, 0xb0405000, 4096)
09-06 18:58:39.461   316  8357 V AudioCache: write(0xb0405000, 4096)
09-06 18:58:39.461   316  8357 V AudioCache: memcpy(0xac231000, 0xb0405000, 4096)
09-06 18:58:39.461   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 18:58:39.461   316  8357 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 18:58:39.461   316  8357 V AwesomePlayer: postAudioEOS() 
09-06 18:58:39.461   316  8357 V AudioCache: write(0xb0405000, 280)
09-06 18:58:39.461   316  8357 V AudioCache: memcpy(0xac232000, 0xb0405000, 280)
09-06 18:58:39.468   316  8354 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 18:58:39.468   316  8354 V AwesomePlayer: onStreamDone
09-06 18:58:39.468   316  8354 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 18:58:39.468   316  8354 V AudioCache: notify(0xb04098c0, 2, 0, 0)
09-06 18:58:39.468   316  8354 V AudioCache: playback complete
09-06 18:58:39.468   316  8354 V AwesomePlayer: pause_l() 
09-06 18:58:39.468   316  8354 V AudioCache: notify(0xb04098c0, 7, 0, 0)
09-06 18:58:39.468   316  8354 V AudioCache: ignored
09-06 18:58:39.468   316  8354 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:39.468   316  8354 D AudioPlayer: Pause Playback at 1068125
09-06 18:58:39.469   316  1404 V AudioCache: wait - success
09-06 18:58:39.469   316  1404 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 18:58:39.469   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:39.469   316  1404 V AudioCache: notify(0xb04098c0, 8, 0, 0)
09-06 18:58:39.469   316  1404 V AudioCache: ignored
09-06 18:58:39.469   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:39.469   316  1404 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ff380 on port 1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 18:58:39.469   316  8356 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 18:58:39.469   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 18:58:39.470   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 18:58:39.470   316  1404 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 18:58:39.470   316  1404 D AudioPlayer: AudioPlayer releasing audio source
09-06 18:58:39.470   316  1404 D AudioPlayer: AudioPlayer done releasing audio source
09-06 18:58:39.470   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:39.470   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:39.470   316  1404 V AwesomePlayer: ~AwesomePlayer call
09-06 18:58:39.470   316  1404 V AwesomePlayer: reset_l() 
09-06 18:58:39.470   316  1404 V AwesomePlayer: cancelPlayerEvents
09-06 18:58:39.471  8299  8353 V SoundPool: close(31)
09-06 18:58:39.471  8299  8353 V SoundPool: pointer = 0x9fe50000, size = 205080, sampleRate = 48000, num,Channels = 2
09-06 18:58:39.486  8299  8299 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 18:58:39.486  8299  8299 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 18:58:39.488  8299  8299 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5245
09-06 18:58:39.490  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:39.510  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 18:58:39.511  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.512  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.513  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.514  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.516  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.517  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.518  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.519  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 18:58:39.590  8358  8358 D AndroidRuntime: 
09-06 18:58:39.590  8358  8358 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 18:58:39.593  8358  8358 D AndroidRuntime: CheckJNI is OFF
09-06 18:58:39.713  7881  7881 I UEI.SmartControl: Supports setup maps: true
09-06 18:58:39.715  7881  7881 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 18:58:39.716  7881  7881 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 18:58:39.716  7881  7881 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 18:58:39.716  7881  7881 I UEI.SmartControl: ### init IR Blaster...
,09-06 18:58:39.720  7881  7881 D serial_port: Configuring serial port
09-06 18:58:39.720  7881  7881 E UEI.SmartControl: UEIBLaster setting for 616
09-06 18:58:39.720  7881  7881 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 18:58:39.720  7881  7881 I UEI.SmartControl: configuring settings for MAXQ616
09-06 18:58:39.720  7881  7881 I UEI.SmartControl: Get version...
09-06 18:58:39.725  8358  8358 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-06 18:58:39.736  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-06 18:58:39.737  1034  1092 I ActivityManager: Killing 6865:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-06 18:58:39.739  7881  8371 D UEI.SmartControl: serial port data available: 21
,09-06 18:58:39.767  7881  7881 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 18:58:39.767  7881  7881 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 18:58:39.767  7881  7881 I UEI.SmartControl: QS saving settings...
09-06 18:58:39.767  7881  7881 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 18:58:39.780  7881  8371 D UEI.SmartControl: serial port data available: 4
,09-06 18:58:39.785  1034  1405 D WifiService: Client connection lost with reason: 4
09-06 18:58:39.785  1034  1051 I WindowState: WIN DEATH: Window{2f0df6d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 18:58:39.791  1034  1051 D InputDispatcher: Window went away: Window{2f0df6d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 18:58:39.814  7881  7881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 18:58:39.815  7881  8376 I UEI.SmartControl: Device manager: loading config....
09-06 18:58:39.815  7881  8376 D UEI.SmartControl: ----------- loading internal config...
09-06 18:58:39.818  7881  8376 E UEI.SmartControl: Loading SETTINGS...
09-06 18:58:39.821  7881  8376 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 18:58:39.830  7881  8375 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 18:58:39.830  7881  8375 D UEI.SmartControl: -----service ready thread exits
,09-06 18:58:39.954  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{11dadf8d u0 com.test.thalitest/.MainActivity t6}
,09-06 18:58:40.011   342   353 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 18:58:40.013  1034  1940 W ActivityManager: Spurious death for ProcessRecord{34a7e210 6865:com.test.thalitest/u0a118}, curProc for 6865: null
,09-06 18:58:40.018  1034  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-06 18:58:40.018  7881  7881 E UEI.SmartControl: Services init done
09-06 18:58:40.018  7881  7881 D UEI.SmartControl: QS Service init finished
09-06 18:58:40.022  7881  7881 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 18:58:40.024  7881  7881 D UEI.SmartControl: QS Service version code: 201091
09-06 18:58:40.025  1034  1117 I ActivityManager:   Force finishing activity ActivityRecord{11dadf8d u0 com.test.thalitest/.MainActivity t6 f}
09-06 18:58:40.025  7881  7881 D UEI.SmartControl: Service requested: Control
09-06 18:58:40.025  1034  1117 W ActivityManager: Duplicate finish request for ActivityRecord{11dadf8d u0 com.test.thalitest/.MainActivity t6 f}
,09-06 18:58:40.055  7881  7881 D UEI.SmartControl: Internal service binding...
09-06 18:58:40.056  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,09-06 18:58:40.056  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2fd94b00 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 18:58:40.059  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-06 18:58:40.062  8299  8299 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 18:58:40.063  7881  7897 I UEI.SmartControl: ------ IControl API: 11
09-06 18:58:40.063  7881  7897 D UEI.SmartControl: File observer start...
09-06 18:58:40.066  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-06 18:58:40.067  7881  7897 E UEI.SmartControl: IR Port is disabled: false
09-06 18:58:40.067  7881  7897 D UEI.SmartControl: Starting file observer...
09-06 18:58:40.068  1941  3970 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-06 18:58:40.069  1941  3970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{165f1f39 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-06 18:58:40.071  7881  7897 I UEI.SmartControl: Registering callback...
09-06 18:58:40.073  7881  7997 I UEI.SmartControl: ------ IControl API: 19
09-06 18:58:40.073  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-06 18:58:40.074  7881  7997 I UEI.SmartControl: Registering Services Ready callback...
09-06 18:58:40.074  7881  7997 I UEI.SmartControl: Notify client services are ready...
09-06 18:58:40.074  2034  2125 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-06 18:58:40.075  8299  8316 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 18:58:40.075  8299  8351 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 18:58:40.076  8299  8351 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 18:58:40.076  8299  8299 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 18:58:40.076  8299  8299 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 18:58:40.076  7881  7896 I UEI.SmartControl: ------ IControl API: 8
09-06 18:58:40.083  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-06 18:58:40.090  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 18:58:40.090  3812  3812 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-06 18:58:40.092  1034  1382 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-06 18:58:40.093  8299  8299 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 18:58:40.093  8299  8299 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 18:58:40.093  8299  8299 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 18:58:40.094  8299  8299 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 18:58:40.095  7778  7778 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-06 18:58:40.095  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 18:58:40.098  2502  2674 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 18:58:40.107  8299  8299 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 18:58:40.110  8299  8299 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,09-06 18:58:40.126  4639  4639 I art     : Explicit concurrent mark sweep GC freed 8402(476KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 1.113ms total 87.203ms
09-06 18:58:40.152  1034  1905 V SIM_STK : Menu title from STK is T-Mobile
,09-06 18:58:40.173  4528  4528 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-06 18:58:40.173  4528  4528 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-06 18:58:40.174  4528  4528 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-06 18:58:40.174  4528  4528 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-06 18:58:40.174  4528  4528 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 18:58:40.174  4528  4528 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 18:58:40.174  4528  4528 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 18:58:40.174  4528  4528 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 18:58:40.174  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:58:40.174  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:58:40.174  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 18:58:40.174  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 18:58:40.185  1034  1034 D administrator: Handling package changes for user 0
09-06 18:58:40.186  8230  8230 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 18:58:40.199  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-06 18:58:40.200  1906  1906 D ActionManagerService: notifyUserLog: 1000003
,09-06 18:58:40.201  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-06 18:58:40.202  3812  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-06 18:58:40.203  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-06 18:58:40.209  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-06 18:58:40.210  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-06 18:58:40.211  1604  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 18:58:40.211  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.211  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-06 18:58:40.220  8299  8299 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-06 18:58:40.234  1604  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 18:58:40.234  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.242  1906  1906 D ActionManagerService: notifyUserLog: 1000004
09-06 18:58:40.242  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-06 18:58:40.242  3812  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,09-06 18:58:40.245  2215  2215 I ConfigService: onCreate
09-06 18:58:40.246  2215  2215 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-06 18:58:40.246  3812  3828 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 18:58:40.246  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-06 18:58:40.246  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-06 18:58:40.251  8299  8299 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 18:58:40.252  2215  2215 I ConfigService: onBind returning update interface
,09-06 18:58:40.259  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-06 18:58:40.265  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 18:58:40.266  1604  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:58:40.266  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 18:58:40.268  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 18:58:40.268  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.269  1604  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , display: false
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , animation: false }
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , display: false
09-06 18:58:40.270  2034  2034 I GBoardWebViewUtils: , animation: false }
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: , create_time: 1472828323917
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: , expire_time: 0
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: , display: false
09-06 18:58:40.271  2034  2034 I GBoardWebViewUtils: , animation: false }
09-06 18:58:40.271  2215  2215 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-06 18:58:40.271  2215  2215 I ConfigService: onBind returning config service
09-06 18:58:40.272  1604  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 18:58:40.272  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.275  1870  1870 D SplitUIManager: split_name #11 / not available #0
09-06 18:58:40.276  1870  1870 D SplitUIService: removed split : 
09-06 18:58:40.277  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 18:58:40.277  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:40.278  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.278  1817  1817 I ConfigFetchService: service connected
09-06 18:58:40.278  1604  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 18:58:40.280  1604  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 18:58:40.280  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.280  1034  1940 V SIM_STK : Menu title from STK is T-Mobile
09-06 18:58:40.280  1034  1940 V SIM_STK : Menu title from STK is T-Mobile
09-06 18:58:40.289  2034  8388 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-06 18:58:40.291  1604  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:58:40.291  1604 , 1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 18:58:40.291  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 18:58:40.291  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 18:58:40.298  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.298  1604  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-06 18:58:40.313  1604  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 18:58:40.313  1604  1660 D KeyguardModel: createShortcutInfo...
,09-06 18:58:40.320  1870  1870 D SplitUIManager: split_name #11 / not available #0
09-06 18:58:40.320  1870  1870 I SplitUIService: split app #11
09-06 18:58:40.322  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 18:58:40.322  2215  2215 I ConfigService: onDestroy
09-06 18:58:40.323  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-06 18:58:40.332  1604  1604 D KeyguardModel: handleShortcutListChanged...
09-06 18:58:40.333  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-06 18:58:40.339  1817  8390 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-06 18:58:40.340  1604  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 18:58:40.340  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.340  1034  1887 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 18:58:40.341  7778  7778 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 18:58:40.341  1604  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 18:58:40.341  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.342  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.342  1604  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 18:58:40.343  1604  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 18:58:40.344  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.344  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
09-06 18:58:40.347  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.347  1604  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 18:58:40.349  1604  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 18:58:40.349  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.352  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.352  1604  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-06 18:58:40.356  1604  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 18:58:40.357  1604  1660 D KeyguardModel: createShortcutInfo...
09-06 18:58:40.359  1034  2033 V SIM_STK : Menu title from STK is T-Mobile
09-06 18:58:40.380  5987  8395 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-06 18:58:40.386  1604  1604 D KeyguardModel: handleShortcutListChanged...
09-06 18:58:40.386  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 18:58:40.391  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-06 18:58:40.401  1817  8397 I PeopleContactsSync: CP2 sync disabled
09-06 18:58:40.421  2215  2243 I art     : Explicit concurrent mark sweep GC freed 6940(420KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 550us total 17.467ms
,09-06 18:58:40.422  7175  7175 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-06 18:58:40.429  1817  4784 I Icing   : doRemovePackageData com.test.thalitest
09-06 18:58:40.430  1034  1051 I ActivityManager: Killing 7373:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-06 18:58:40.453  1034  1117 I art     : Explicit concurrent mark sweep GC freed 81921(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 4.416ms total 396.353ms
,09-06 18:58:40.473  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-06 18:58:40.477  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 18:58:40.477  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-06 18:58:40.477  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 18:58:40.478  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 18:58:40.478  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-06 18:58:40.479  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-06 18:58:40.480  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-06 18:58:40.481  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-06 18:58:40.482   334   434 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-06 18:58:40.483  3239  8401 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-06 18:58:40.514  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-06 18:58:40.514  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 18:58:40.515  2034  2166 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,09-06 18:58:40.515  2034  2166 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-06 18:58:40.515  8358  8358 D AndroidRuntime: Shutting down VM
09-06 18:58:40.522  1034  2030 W libprocessgroup: failed to open /acct/uid_10005/pid_7373/cgroup.procs: No such file or directory
09-06 18:58:40.522  1034  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-06 18:58:40.525  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d7299eb u0 com.lge.launcher2/.Launcher t5} time:200677
09-06 18:58:40.530  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-06 18:58:40.530  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 18:58:40.530  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 18:58:40.531  2365  8403 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-06 18:58:40.541  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-06 18:58:40.561  1034  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8405 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 18:58:40.580  1034  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8422 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-06 18:58:40.582  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
09-06 18:58:40.582  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-06 18:58:40.586  2034  2034 D [Concierge]WidgetView: change position of spinner
09-06 18:58:40.586  2581  2581 D [Concierge]Service: Update widget ID : 11
09-06 18:58:40.587  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1473181120587
09-06 18:58:40.588  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
09-06 18:58:40.592  1817  8396 W GmsApplication: Using Auth Proxy for data requests.
,09-06 18:58:40.598  1817  8396 W GmsApplication: Using Auth Proxy for data requests.
09-06 18:58:40.599  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 393954200
09-06 18:58:40.599  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-06 18:58:40.599  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 18:58:40.602  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@104c0d18
09-06 18:58:40.602  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-06 18:58:40.603  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 18:58:40.603  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 18:58:40.608  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-06 18:58:40.609  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-06 18:58:40.609  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 18:58:40.610  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473180948559, New one : 1473181120587
09-06 18:58:40.610  2034  2034 D [Concierge]WidgetView: Unregister all receivers
09-06 18:58:40.610  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 18:58:40.610  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 18:58:40.612  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-06 18:58:40.613  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-06 18:58:40.614  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-06 18:58:40.615  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-06 18:58:40.616  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-06 18:58:40.620  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 18:58:40.620  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 18:58:40.632  8405  8405 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:58:40.633  8405  8405 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 18:58:40.633  8405  8405 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 18:58:40.633  8405  8405 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 18:58:40.649  1034  2030 I ActivityManager: Killing 7809:com.google.android.talk/u0a72 (adj 15): empty #17
09-06 18:58:40.650  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-06 18:58:40.659  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-06 18:58:40.659  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-06 18:58:40.660  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 18:58:40.679  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b3f8b5d time:200831
,09-06 18:58:40.694  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 18:58:40.698  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-06 18:58:40.730  1034  1576 W libprocessgroup: failed to open /acct/uid_10072/pid_7809/cgroup.procs: No such file or directory
09-06 18:58:40.731  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 18:58:40.733  8405  8405 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-06 18:58:40.741  8405  8405 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 18:58:40.755  1817  8440 I art     : Explicit concurrent mark sweep GC freed 24798(1669KB) AllocSpace objects, 19(300KB) LOS objects, 51% free, 30MB/62MB, paused 762us total 23.406ms
,09-06 18:58:40.758  1817  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-06 18:58:40.759  1817  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-06 18:58:40.759  1817  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-06 18:58:40.764  8405  8405 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 18:58:40.799  8405  8405 D LgDataFeature: LgDataFeature() Constructor: none
09-06 18:58:40.799  8405  8405 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 18:58:40.820  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-06 18:58:40.852  8405  8405 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-06 18:58:40.856  7902  7902 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,09-06 18:58:40.857  1034  2030 I ActivityManager: Killing 7921:com.android.vending/u0a44 (adj 15): empty #17
09-06 18:58:40.861  2034  2865 I GBoardtInterface: onReloaded()
09-06 18:58:40.862  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-06 18:58:40.900  1034  1960 W libprocessgroup: failed to open /acct/uid_10044/pid_7921/cgroup.procs: No such file or directory
09-06 18:58:40.901  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 18:58:40.901  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-06 18:58:40.901  3812  3828 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-06 18:58:40.903  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) },
09-06 18:58:40.905  3812  3827 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 18:58:40.907  8230  8230 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 18:58:40.909  8230  8230 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 18:58:40.913  1906,  1906 D ActionManagerService: notifyUserLog: 1000001
09-06 18:58:40.913  7607  7607 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,09-06 18:58:40.916  3812  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 18:58:40.916  6995  6995 D PackageIntentReceiver: Not supported Hotkey customization function 
09-06 18:58:40.916  3812  4517 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 18:58:40.919  1906  1906 D ActionManagerService: notifyUserLog: 1000001
09-06 18:58:40.920  3812  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 18:58:40.920  3812  4517 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 18:58:40.920  3812  4517 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-06 18:58:40.920  3812  4517 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-06 18:58:40.920  3812  3828 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 18:58:40.922  6995  6995 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-06 18:58:40.922  6995  6995 D HideNavigationAppsReceiver: replacing : false
09-06 18:58:40.922  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-06 18:58:40.922  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-06 18:58:40.924  6995  6995 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-06 18:58:40.924  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-06 18:58:40.924  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 18:58:40.926  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-06 18:58:40.926  6995  6995 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-06 18:58:40.926  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 18:58:40.926  6995  6995 D ButtonCombinationReceiver: replacing : false

```
