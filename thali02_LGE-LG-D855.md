#### Test 82914073126c10a_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 15:30:15.777  2210  2210 I ConfigService: onDestroy
,09-07 15:30:17.574  6889  6889 D AndroidRuntime: 
09-07 15:30:17.574  6889  6889 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 15:30:17.582  6889  6889 D AndroidRuntime: CheckJNI is OFF
09-07 15:30:17.783  6889  6889 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 15:30:17.794  1035  2030 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 15:30:17.809  1940  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 15:30:17.815  1035  2030 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 15:30:17.816  1035  2030 D ActivityManager: setTaskToReturnTo : TaskRecord{b257065 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 15:30:17.816  1035  2030 D ActivityManager: setTaskToReturnTo : TaskRecord{b257065 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 15:30:17.818  1035  2030 D WindowStateEx: AppWindowTokenEx init.. 
09-07 15:30:17.819   339   348 E GBMv2   : DFP En is all cleared set to be enabled
09-07 15:30:17.847  1035  2030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6904 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 15:30:17.850  6889  6889 D AndroidRuntime: Shutting down VM
09-07 15:30:17.906  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 15:30:17.906  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5e568b1 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 15:30:17.907  1940  2796 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 15:30:17.907  1940  2796 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1279b196 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 15:30:17.975  6904  6904 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 15:30:18.047  6904  6904 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 15:30:18.064  6904  6904 I LibraryLoader: Loading: webviewchromium
,09-07 15:30:18.072  6904  6904 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 9536-9546)
09-07 15:30:18.073  6904  6904 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 15:30:18.098  6904  6904 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34860687}
09-07 15:30:18.099  6904  6904 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 15:30:18.100  6904  6904 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 15:30:18.113  6904  6904 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 15:30:18.114  6904  6904 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 15:30:18.131  6904  6904 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-07 15:30:18.132  6904  6904 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-07 15:30:18.133  6904  6904 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-07 15:30:18.133   315  2156 V AudioPolicyService: registerClient() client 0xb558abc0, uid 10118
09-07 15:30:18.139  1035  1117 D BluetoothManagerService: Message: 20
09-07 15:30:18.139  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2887c1c7:true
09-07 15:30:18.157  6904  6904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 15:30:18.157  6904  6904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 15:30:18.157  6904  6904 I Adreno-EGL: Build Date: 12/12/14 금
09-07 15:30:18.157  6904  6904 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 15:30:18.157  6904  6904 I Adreno-EGL: Remote Branch: 
09-07 15:30:18.157  6904  6904 I Adreno-EGL: Local Patches: 
09-07 15:30:18.157  6904  6904 I Adreno-EGL: Reconstruct Branch: 
,09-07 15:30:18.250  6904  6950 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 15:30:18.258  6904  6904 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 15:30:18.274  6904  6904 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 15:30:18.279  6904  6904 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 15:30:18.281  6904  6904 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 15:30:18.284  6904  6904 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 15:30:18.285  6904  6904 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 15:30:18.298  6904  6904 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 15:30:18.305  6904  6904 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 15:30:18.305  6904  6904 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 15:30:18.347  6904  6966 D OpenGLRenderer: Render dirty regions requested: true
09-07 15:30:18.347  6904  6966 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 15:30:18.352  6904  6966 D OpenGLRenderer: Enabling debug mode 0
,09-07 15:30:18.359  6904  6904 D Atlas   : Validating map...
09-07 15:30:18.365  1035  1778 D SplitWindow: check instance of lgWin Window{253b5989 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 15:30:18.408  6904  6964 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:18.408  6904  6964 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:18.533  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +629ms (total +712ms)
09-07 15:30:18.534  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a4dd13a u0 com.test.thalitest/.MainActivity t6} time:160008
09-07 15:30:18.534  6904  6904 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6e4b02 time:160008
09-07 15:30:18.657  6904  6904 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 15:30:18.657  6904  6904 I chromium: 
,09-07 15:30:18.719  6904  6904 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 15:30:18.913  6904  6977 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435128832
,09-07 15:30:18.930  6904  6977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 15:30:18.930  6904  6977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 15:30:18.930  6904  6977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 15:30:18.930  6904  6977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 15:30:18.930  6904  6977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 15:30:18.930  6904  6977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e3f8026 added. We now have 1 listener(s)
,09-07 15:30:18.943  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 15:30:18.947  6904  6977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-07 15:30:18.949  6904  6977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:18.951  6904  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:18.952  6904  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 15:30:18.960  6904  6977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e93aabd added. We now have 1 listener(s)
,09-07 15:30:18.961  6904  6977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:18.966  1035  1471 D WifiService: New client listening to asynchronous messages
09-07 15:30:18.973  6904  6977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:18.973  6904  6977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 15:30:18.974  6904  6977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 15:30:18.974  6904  6977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 15:30:18.974  6904  6977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 15:30:18.980  6904  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:18.981  1035  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:18.983  6904  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-07 15:30:18.994  6904  6977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:18.995  6904  6977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:18.995  6904  6977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 15:30:18.995  6904  6977 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:18.996  6904  6977 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 15:30:18.998  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:19.000  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:19.036  6904  6964 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 15:30:19.036  6904  6964 I chromium: 
,09-07 15:30:19.096  6904  6904 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 15:30:19.425   339   350 E GBMv2   : DFP En is all cleared set to be enabled
09-07 15:30:19.425   339   350 E GBMv2   : Set value is all cleared set the max
09-07 15:30:19.425   339   350 I GBMv2   : DFP Enabled. Ignore VFP set
,09-07 15:30:20.137  6904  6983 W jxcore-log: Initializing JXcore engine
09-07 15:30:20.137  6904  6983 W jxcore-log: JXcore engine is ready
,09-07 15:30:20.198  6983  6983 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8684]" dev="sockfs" ino=8684 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 15:30:20.198  6983  6983 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-07 15:30:20.198  6983  6983 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8818]" dev="sockfs" ino=8818 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 15:30:20.198  6983  6983 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-07 15:30:20.198  6983  6983 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32791]" dev="sockfs" ino=32791 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 15:30:20.238  6904  6983 W jxcore-log: Starting JXcore engine
,09-07 15:30:20.391  6904  6983 W jxcore-log: Platform android
09-07 15:30:20.391  6904  6983 W jxcore-log: 
09-07 15:30:20.391  6904  6983 W jxcore-log: Process ARCH arm
09-07 15:30:20.391  6904  6983 W jxcore-log: 
,09-07 15:30:20.783  6904  6983 I jxcore-log: JXcore Cordova bridge is ready!
09-07 15:30:20.783  6904  6983 I jxcore-log: 
09-07 15:30:20.784  6904  6983 W jxcore-log: JXcore engine is started
,09-07 15:30:20.791  6904  6977 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 15:30:20.794  6904  6904 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 15:30:30.315  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 15:30:30.315  6904  6983 I jxcore-log: 
,09-07 15:30:30.318  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 15:30:30.318  6904  6983 I jxcore-log: 
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:30.322  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:30.325  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.327  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 15:30:30.327  6904  6983 I jxcore-log: 
09-07 15:30:30.329  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 15:30:30.329  6904  6983 I jxcore-log: 
,09-07 15:30:30.837  6904  6983 D executeNativeTests: Running unit tests
,09-07 15:30:30.917  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:30.917  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 added. We now have 2 listener(s)
,09-07 15:30:30.918  1035  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 15:30:30.920  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-07 15:30:30.920  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:30.920  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-07 15:30:30.920  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-07 15:30:30.920  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 added. We now have 2 listener(s)
,09-07 15:30:30.920  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:30.920  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:30:30.923  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:30.925  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:30:30.926  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-07 15:30:30.926  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:30.927  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:30.928  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:30.931  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:30:30.933  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 15:30:30.933  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:30:30.935  6904  6983 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 15:30:30.936  6904  6983 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
09-07 15:30:30.936  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:30:30.936  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:30:30.936  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:30:30.936  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-07 15:30:30.937  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:30:30.937  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:30.938  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:30.938  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.938  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:30.938  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 15:30:30.938  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 removed from the list
09-07 15:30:30.938  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.938  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 removed from the list
09-07 15:30:30.938  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:30.938  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:30.939  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.939  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.939  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:30.939  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:30.939  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:30.940  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.942  6904  6983 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 15:30:30.942  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:30:30.942  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:30.942  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:30.942  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:30.942  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.942  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:30.942  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:30.942  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.942  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.942  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:30.942  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 15:30:30.943  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.943  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.943  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.943  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:30.943  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 15:30:30.943  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.943  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 15:30:30.949  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 15:30:30.950  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:30.950  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:30.950  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:30.950  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:30.950  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.950  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.950  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:30.950  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.950  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.950  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:30.950  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.950  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.950  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.951  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.951  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:30.951  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:30.951  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.951  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.952  6904  6983 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:30:30.954  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:30.956  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:30.956  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.957  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:30.958  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:30.959  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:30.959  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:30.959  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:30.959  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:30.959  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:30.959  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:30.962  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:30:30.962  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:30.966  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:30:30.970  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:30:30.971  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 15:30:30.973  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:30.973  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:30.974  6904  6983 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 15:30:30.974  6904  6983 I io.jxcore.node.ConnectionHelper: start: OK
09-07 15:30:30.976  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:30.976  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:30.977  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:30.977  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:30.977  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.977  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:30.977  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:30.977  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.977  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.977  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:30.977  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.977  6904  6983 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:30:30.979  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:30.980  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:30.981  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.981  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:30:30.982  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:30.983  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:30.983  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:30.983  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:30.983  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:30.983  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:30.983  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:30.986  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:30.987  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:30.988  6904  6983 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 15:30:30.988  6904  6983 I io.jxcore.node.ConnectionHelper: start: OK
09-07 15:30:30.989  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:30.989  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:30.989  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:30.989  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:30.989  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.989  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:30.989  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:30.989  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.989  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.989  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:30.990  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.990  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:30.990  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:30.990  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:30.990  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:30.992  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:30.992  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:30.992  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:30.992  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:30.993  6904  6983 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:30:30.995  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:30.997  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:30.998  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:30.998  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:30.998  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:30.999  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:30.999  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:30.999  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:30.999  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:30.999  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:31.000  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:31.002  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:31.002  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:31.003  6904  6983 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 15:30:31.003  6904  6983 I io.jxcore.node.ConnectionHelper: start: OK
09-07 15:30:31.003  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.003  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.003  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.004  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.004  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.004  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.004  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.004  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.004  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:31.005  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.005  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.005  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.005  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.005  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.005  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.005  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:31.007  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.007  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.008  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.008  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.008  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.008  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.009  6904  6983 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 15:30:31.009  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.009  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.009  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.009  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.009  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.009  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.009  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.009  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.009  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.010  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.010  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.010  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.010  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.010  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.012  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.012  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.012  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.012  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.012  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.012  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.014  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 15:30:31.014  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.014  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.014  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.014  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.014  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.014  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.014  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.014  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.014  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.014  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.014  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.014  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.015  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.015  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.017  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.017  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.018  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.018  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.018  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.018  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.018  6904  6983 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 15:30:31.019  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.019  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.019  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.019  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.019  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.019  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.019  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.019  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.019  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.019  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.019  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.019  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.019  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.019  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.023  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.023  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.024  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.024  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.024  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.024  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.026  6904  6983 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 15:30:31.026  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.026  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.026  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.026  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.026  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.026  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.026  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.026  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.026  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.026  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.026  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.026  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.026  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.026  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.027  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.027  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.027  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.027  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.027  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.027  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.028  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:30:31.030  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:30:31.030  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:30:31.030  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:30:31.030  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:30:31.030  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:30:31.030  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.030  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.030  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.030  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.030  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.030  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.030  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.030  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.030  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.030  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.030  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.030  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.030  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.030  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.033  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.033  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.034  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.034  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.034  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.034  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.036  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:30:31.036  6904  6983 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 15:30:31.036  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 15:30:31.044  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:30:31.045  6904  6983 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 15:30:31.046  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 15:30:31.047  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 15:30:31.048  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 15:30:31.048  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 15:30:31.049  6904  6983 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:30:31.049  6904  6983 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 15:30:31.049  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:30:31.049  6904  6983 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:30:31.049  6904  6983 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 15:30:31.050  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:30:31.050  6904  6983 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:30:31.050  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 15:30:31.051  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 15:30:31.053  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 15:30:31.053  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 15:30:31.053  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 15:30:31.054  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 15:30:31.054  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 15:30:31.054  6904  6983 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:30:31.054  6904  6983 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 15:30:31.054  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.054  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.054  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.054  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.054  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.054  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.055  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 15:30:31.056  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.056  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.056  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.056  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.056  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.056  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.056  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.056  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.057  6904  6990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
09-07 15:30:31.057  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.057  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.065  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.065  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.065  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.065  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.066  6904  6983 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 15:30:31.066  6904  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
09-07 15:30:31.066  6904  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 876)
09-07 15:30:31.066  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.067  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.067  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.067  6904  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 876)
09-07 15:30:31.067  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.067  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.067  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.067  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.067  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.067  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.067  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.067  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.067  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.067  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.067  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.068  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.068  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.068  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.068  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.068  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.068  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.069  6904  6983 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 15:30:31.069  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.070  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.070  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.072  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.072  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.072  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.072  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.072  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.072  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.072  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.072  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.072  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.072  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.073  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.074  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.074  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.074  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.074  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.074  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.074  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.075  6904  6983 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 15:30:31.085  6904  6983 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 15:30:31.086  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:30:31.086  6904  6983 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 15:30:31.086  6904  6983 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 15:30:31.086  6904  6983 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 15:30:31.086  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:30:31.086  6904  6983 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 15:30:31.086  6904  6983 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 15:30:31.086  6904  6983 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 15:30:31.086  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:30:31.086  6904  6983 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 15:30:31.087  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.087  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:30:31.087  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.088  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.089  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.089  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.089  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.089  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:31.089  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.089  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.089  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.089  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.089  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.089  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.090  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.090  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.091  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.091  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.091  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.091  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.092  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.092  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.092  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.092  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.092  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.092  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.092  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.092  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.092  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.092  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.092  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.092  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.092  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.092  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.093  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.093  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.093  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, disco,very: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.093  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.093  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.093  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.093  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.093  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.093  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.093  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.093  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.093  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.093  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.093  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.093  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.094  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.094  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.095  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.095  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.095  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.095  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.097  6904  6983 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 15:30:31.097  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:31.098  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 15:30:31.099  6904  6983 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 15:30:31.099  6904  6983 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 15:30:31.099  6904  6904 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 15:30:31.099  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 15:30:31.100  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:30:31.101  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.101  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 15:30:31.101  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 15:30:31.101  6904  6983 D org.thaliproject.p2p.b,tconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 15:30:31.101  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.101  6904  6983 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 15:30:31.101  6904  6904 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 15:30:31.102  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.102  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.102  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:30:31.102  6904  6983 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:30:31.102  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:30:31.103  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:30:31.104  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:31.104  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:31.104  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:31.105  6904  6992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:31.105  6904  6983 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:30:31.105  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.105  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.107  4291  4677 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-07 15:30:31.109  6904  6992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 15:30:31.109  6904  6992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 15:30:31.109  6904  6992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 15:30:31.111  6904  6983 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:30:31.111  6904  6904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:31.111  6904  6904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:31.111  6904  6904 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 15:30:31.111  6904  6904 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:30:31.112  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.112  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.112  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.112  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.112  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.112  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.112  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.113  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.113  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.113  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.113  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.113  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.113  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.113  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.113  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.115  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.115  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.115  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.115  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.117  6904  6983 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 15:30:31.117  6904  6983 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 15:30:31.117  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:30:31.117  6904  6983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:30:31.117  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.118  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.118  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.118  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.118  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.118  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.118  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.118  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.118  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.118  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.118  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.118  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.118  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.118  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.120  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.120  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.120  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.120  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.126  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:31.127  1035  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:31.128  1035  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:31.128  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.128  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.128  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.129  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.129  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.129  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.129  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.129  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.129  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.129  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.129  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.129  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.129  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.129  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.130  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.130  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.130  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.130  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.131  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:31.131  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:31.131  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:31.131  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:31.132  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.132  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.132  6904  6983 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34390176 not in the list
09-07 15:30:31.132  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.132  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.132  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:31.132  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.132  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.132  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:31.132  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:31.133  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:31.133  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:31.133  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:31.133  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fbc377 not in the list
09-07 15:30:31.135  6904  6983 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 15:30:31.135  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:30:31.135  6904  6983 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 15:30:31.135  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:30:31.135  6904  6983 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 15:30:31.135  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:30:31.139  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 15:30:31.139  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 15:30:31.140  6904  6983 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 15:30:31.140  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 15:30:31.140  6904  6983 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 15:30:31.140  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 15:30:31.140  6904  6983 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 15:30:31.140  6904  6983 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 15:30:31.141  6904  6983 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 15:30:31.141  6904  6983 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 15:30:31.142  6904  6983 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 15:30:31.142  6904  6983 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 15:30:31.142  6904  6983 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 15:30:31.143  6904  6983 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 15:30:31.144  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:31.144  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14cd937c added. We now have 2 listener(s)
09-07 15:30:31.144  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:31.156  6904  6983 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 15:30:31.157  1035  1921 D WifiServiceImplEx: setWifiEnabled: true pid=6904, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 15:30:31.158  1035  1921 D WifiService: setWifiEnabled: true pid=6904, uid=10118
09-07 15:30:31.158  1035  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 15:30:31.160  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:31.160  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5fc405 added. We now have 3 listener(s)
09-07 15:30:31.160  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:31.168  6904  6990 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-07 15:30:31.169  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:31.169  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@135e2c5a added. We now have 4 listener(s)
09-07 15:30:31.169  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:31.169  6904  6990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
09-07 15:30:31.171  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:31.171  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18387e8b added. We now have 5 listener(s)
09-07 15:30:31.171  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:31.174  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6904, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 15:30:31.174  1035  1051 D WifiService: setWifiEnabled: false pid=6904, uid=10118
09-07 15:30:31.174  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:30:31.188  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:31.188  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:31.189  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:31.190  1035  1432 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:31.190  1035  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:31.190  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:31.191  1035  1993 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4b8c2f0 mBinding = false
09-07 15:30:31.191  1035  1432 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:31.191  1035  1432 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:31.192  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:31.192  1035  1432 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 15:30:31.192  1035  1432 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:30:31.192  1035  1432 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 15:30:31.193  1035  1432 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 15:30:31.193  1035  1432 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 15:30:31.202  1035  1432 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 15:30:31.202  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:31.202  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.202  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 15:30:31.203  2671  2671 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 15:30:31.203  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 15:30:31.203  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 15:30:31.204  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
09-07 15:30:31.205  1035  2823 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.205   310   893 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:30:31.208  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:31.208  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:31.208  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:31.209  1035  1117 D BluetoothManagerService: Message: 2
09-07 15:30:31.211  1035  1117 D BluetoothManagerService: Sending off request.
09-07 15:30:31.212  4291  4310 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 15:30:31.213  4291  4371 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 15:30:31.213  4291  4371 D BluetoothAdapterProperties: Setting state to 13
09-07 15:30:31.213  4291  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 15:30:31.213  4291  4371 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 15:30:31.213  4291  4371 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-07 15:30:31.219  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:31.219  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 15:30:31.219  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-07 15:30:31.221  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:31.222  4291  4375 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:30:31.222  4291  4371 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 15:30:31.223  4291  4371 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 15:30:31.225  4291  4678 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 15:30:31.225  4291  4679 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:31.226  4291  4745 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:31.226  4291  4742 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:31.226  4291  4717 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:31.227  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 15:30:31.227  4291  4486 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 15:30:31.229  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 15:30:31.229  4291  4486 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 15:30:31.241  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.241  6904  6904 V io.jxcore.n,ode.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:31.241  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:30:31.243  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.243  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:31.255  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 15:30:31.255  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-07 15:30:31.277  1035  1889 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-07 15:30:31.280  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:31.280  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:31.284  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-7ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.284  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.284  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-07 15:30:31.284  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.285  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-07 15:30:31.286  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.286  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:31.287  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:31.288  1035  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6997 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-07 15:30:31.290  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:31.290  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:31.291  4291  4291 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:31.291  4291  4291 D BluetoothMapService: STATE_TURNING_OFF
09-07 15:30:31.291  4291  4291 V BluetoothMapService: Handler(): got msg=4
09-07 15:30:31.291  4291  4291 D BluetoothMapService: M,AP Service closeService in
09-07 15:30:31.291  4291  4291 D BluetoothMapMasInstance: MAP Service shutdown
09-07 15:30:31.292  4291  4291 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 15:30:31.292  4291  4291 V BluetoothMapService: MAP Service closeService out
09-07 15:30:31.294  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:31.295  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:31.298  4291  4291 V BtOppService: Receiver DISABLED_ACTION 
09-07 15:30:31.298  4291  4291 I BtOppRfcommListener: stopping Accept Thread
09-07 15:30:31.299  4291  4291 V BtOppRfcommListener: close mBtServerSocket
09-07 15:30:31.299  4291  4291 V BtOppRfcommListener: waiting for thread to terminate
09-07 15:30:31.299  4291  4717 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 15:30:31.300  4291  4291 V BtOppRfcommListener: done waiting for thread to terminate
09-07 15:30:31.301  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:31.303  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:31.305  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:31.305  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:31.306  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.306  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:31.307  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:31.333  1035  1481 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 15:30:31.333  1035  1481 D DSQN    : disableDataServiceNotify
09-07 15:30:31.333   310  7021 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 15:30:31.333  1035  1481 D DSQN    : stop dsqn bin
09-07 15:30:31.334  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,09-07 15:30:31.335  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 15:30:31.354  1035  1481 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 15:30:31.354  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:31.354  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:31.355  1035  1481 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:31.355  1035  1481 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,09-07 15:30:31.356  1035  1481 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 15:30:31.356  1035  1481 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 15:30:31.356  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:30:31.357  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.357  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.357  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 15:30:31.358  1035  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7023 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 15:30:31.358  1035  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 15:30:31.359  4291  4291 V BtOppService: onDestroy
09-07 15:30:31.367  1035  1481 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:31.367  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:30:31.367  4291  4291 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-07 15:30:31.368  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 15:30:31.370  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 15:30:31.371  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-07 15:30:31.372  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.372  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.372  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:31.372  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 15:30:31.372  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 15:30:31.372  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 15:30:31.372  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-07 15:30:31.374  1035  1481 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:31.374  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.374  1035  1481 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:31.374  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.374  1035  1481 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:31.374  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.374  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f78127d
09-07 15:30:31.374  1035  1481 D NetworkManagementService: Removing idletimer
09-07 15:30:31.374  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.375  1035  1390 D LGWifiP2pService: P2pDisablingState
09-07 15:30:31.375  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.375  1035  1481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.375  1035  1390 D LGWifiP2pService: p2p socket connection lost
09-07 15:30:31.375  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.375  1035  1390 D LGWifiP2pService: P2pDisabledState
09-07 15:30:31.376  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:31.376  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-07 15:30:31.376  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 15:30:31.376  1035  1481 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 15:30:31.377  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.377  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.377  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.378  1035  1432 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 15:30:31.379  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.379  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.380  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:31.380  1035  1432 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:31.380  1035  1432 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:31.381  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 15:30:31.381  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 15:30:31.381  2671  2671 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 15:30:31.381  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.381  1035  1390 D LGWifiP2pServ,ice: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:31.382  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.382  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.382  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:31.382  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 15:30:31.382  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.383  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-07 15:30:31.383  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.383  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 15:30:31.383  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 15:30:31.384  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 15:30:31.384  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 15:30:31.384  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 15:30:31.384  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 15:30:31.384  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 15:30:31.385  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
09-07 15:30:31.385   310   893 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:30:31.386  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:31.386  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:31.388  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 15:30:31.388  1940  1940 D WfdsService: WifiP2pState is changed : false
09-07 15:30:31.388  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.388  1940  2330 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 15:30:31.388  1940  2330 D WfdsService: Set the WFDS Monitor: false
09-07 15:30:31.389  1940  2330 D WfdsMonitor: WFDS Monitor is stopped
09-07 15:30:31.390  1940  2330 D WfdsService: STATE : WfdsDisabledState - enter
09-07 15:30:31.390  1940  2728 D CtrlSupplicant: Received on exit socket, terminate
09-07 15:30:31.390  1940  2728 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 15:30:31.390  1940  2728 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 15:30:31.390  1940  2728 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 15:30:31.390  1940  2336 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 15:30:31.390  1940  2330 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 15:30:31.393  1035  1432 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 15:30:31.393  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-07 15:30:31.394  1035  1432 D WifiNative-p2p0: TERMINATE: returned true
09-07 15:30:31.394  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:31.394  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:31.394  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 15:30:31.397  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.397  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.397  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:31.399  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 15:30:31.400  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 15:30:31.400  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:31.400  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 15:30:31.402  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:31.402  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:31.403  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.403  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:31.407  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:31.407  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:30:31.409  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:31.409  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:30:31.429  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:31.430  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.430  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:31.430  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:31.431  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:31.432  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.433  7023  7023 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:30:31.433  7023  7023 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-07 15:30:31.433  7023  7023 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:31.434  7023  7023 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-07 15:30:31.434  1035  2823 D DhcpStateMachine: StoppedState
09-07 15:30:31.434  1035  2823 D DhcpStateMachine: StoppedState{ when=-50ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:31.435  1035  1432 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 15:30:31.435  7023  7023 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 15:30:31.435  1035  1432 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-07 15:30:31.436  7023  7023 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 15:30:31.459  6997  6997 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-07 15:30:31.459  6997  6997 W LG Account v2.2: No ProfileInfo entries
09-07 15:30:31.459  6997  6997 I LG Account v2.2: isEnabled: false
09-07 15:30:31.459  6997  6997 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 15:30:31.459  6997  6997 I Feature : [Lifetracker]Country: EU
09-07 15:30:31.459  6997  6997 I Feature : [Lifetracker]Operator: OPEN
09-07 15:30:31.459  6997  6997 I Feature : [Lifetracker]Ranking support: false
09-07 15:30:31.459  6997  6997 I Feature : [Lifetracker]Comfort support: false
09-07 15:30:31.460  6997  6997 I Feature : [Lifetracker]Accessory: true
09-07 15:30:31.460  6997  6997 I Feature : [Lifetracker]Health device: true
09-07 15:30:31.460  6997  6997 I Feature : [Lifetracker]Extra Pedometer: false
09-07 15:30:31.460  6997  6997 I Feature : [Lifetracker]Blood glucose device: false
09-07 15:30:31.460  6997  6997 I Feature : [Lifetracker]Device Number: 3
,09-07 15:30:31.467  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:31.471  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:31.471  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.472  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.472  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 15:30:31.472  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:31.473  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:31.474  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.497  2671  2671 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 15:30:31.497  2671  2671 I wpa_supplicant: monitor socket send errors count : 1
,09-07 15:30:31.497  2671  2671 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
09-07 15:30:31.498  1035  2724 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 15:30:31.498  1035  2724 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 15:30:31.498  1035  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7044 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 15:30:31.499  1035  1051 I ActivityManager: Killing 6352:com.android.defcontainer/u0a4 (adj 15): empty #17
09-07 15:30:31.536  1035  1938 W libprocessgroup: failed to open /acct/uid_10004/pid_6352/cgroup.procs: No such file or directory
,09-07 15:30:31.538  2671  2671 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:30:31.538  1035  2724 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-07 15:30:31.538  1035  2724 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:30:31.538  1035  2724 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:30:31.538  2671  2671 W wpa_supplicant: USIM:  scard_deinit function
09-07 15:30:31.539  1035  2724 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 15:30:31.539  1035  2724 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:31.539  1035  2724 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:31.540  1035  1432 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=173003
09-07 15:30:31.540  1035  1432 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=173003
09-07 15:30:31.541  1035  1432 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=173003  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 15:30:31.541  1035  1432 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=173003  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 15:30:31.541  1035  1117 D Tethering: InitialState.processMessage what=4
09-07 15:30:31.542  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:30:31.543  1035  1432 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:31.543  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:31.578  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-07 15:30:31.591  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-07 15:30:31.591  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:31.593  1035  1993 I ActivityManager: Killing 6526:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-07 15:30:31.612  6904  6904 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:30:31.623  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 15:30:31.628  2671  2671 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-07 15:30:31.628  1035  2724 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 15:30:31.628  1035  2724 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 15:30:31.628  1035  2724 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 15:30:31.629  1035  1432 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-07 15:30:31.637  1035  1051 W libprocessgroup: failed to open /acct/uid_10008/pid_6526/cgroup.procs: No such file or directory
09-07 15:30:31.646  4291  4291 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:31.646  4291  4291 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:31.646  4291  4291 V BluetoothPbapReceiver: ***********state = 13
,09-07 15:30:31.648  4291  4291 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-07 15:30:31.650  4291  4291 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:31.650  4291  4291 V BluetoothPbapService: state: 13
09-07 15:30:31.650  4291  4291 V BluetoothPbapService: Pbap Service closeService in
09-07 15:30:31.652  4291  4291 V BluetoothPbapService: successfully stopped pbap service
09-07 15:30:31.652  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:30:31.652  4291  4291 V BluetoothPbapService: Pbap Service closeService out
09-07 15:30:31.652  4291  4291 V BluetoothPbapService: Pbap Service onDestroy
09-07 15:30:31.652  4291  4291 V BluetoothPbapService: Pbap Service closeService in
09-07 15:30:31.652  4291  4291 V BluetoothPbapService: Pbap Service closeService out
09-07 15:30:31.652  4291  4291 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 15:30:31.662  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:31.705  7023  7023 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:31.706  7023  7023 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:31.718  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:31.728  1035  1117 D BluetoothManagerService: Message: 20
09-07 15:30:31.728  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@292d01ab:true
09-07 15:30:31.732  1940  1940 D WfdsService: Supplicant Connection state is changed : false
09-07 15:30:31.732  1035  1432 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 15:30:31.732  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:31.732  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:31.732  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:31.732  1940  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 15:30:31.732  1940  2330 D WfdsService: Set the WFDS Monitor: false
09-07 15:30:31.732  1940  2330 D WfdsMonitor: WFDS Monitor is stopped
,09-07 15:30:31.735  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:31.740  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 15:30:31.740  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 15:30:31.740  1035  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 15:30:31.741  1035  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 15:30:31.743  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:31.744  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:31.746  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:31.757  1035  1117 D BluetoothManagerService: Message: 30
,09-07 15:30:31.766  1035  1117 D BluetoothManagerService: Message: 30
,09-07 15:30:31.769  7023  7023 D LocalBluetoothProfileManager: Adding local MAP profile
09-07 15:30:31.770  7023  7023 D BluetoothMap: Create BluetoothMap proxy object
09-07 15:30:31.771  1035  1117 D BluetoothManagerService: Message: 30
09-07 15:30:31.775  1035  1117 D BluetoothManagerService: Message: 30
09-07 15:30:31.778  7023  7023 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 15:30:31.779  7023  7023 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-07 15:30:31.793  7023  7023 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-07 15:30:31.798  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-07 15:30:31.816  7023  7023 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:30:31.841  7023  7023 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 15:30:31.850  7023  7023 D BluetoothInputDevice: Proxy object connected
09-07 15:30:31.852  7023  7023 D HidProfile: Bluetooth service connected
09-07 15:30:31.854  7023  7023 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:30:31.855  7023  7023 D PanProfile: Bluetooth service connected
,09-07 15:30:31.857  7023  7023 D BluetoothMap: Proxy object connected
09-07 15:30:31.859  7023  7023 D MapProfile: Bluetooth service connected
09-07 15:30:31.859  7023  7023 D BluetoothMap: getConnectedDevices()
09-07 15:30:31.860  7023  7023 D BluetoothMap: Bluetooth is Not enabled
09-07 15:30:31.861  7023  7023 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 15:30:31.864  7023  7023 D BluetoothPermissionRequest: onReceive
09-07 15:30:31.867  7023  7023 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 15:30:31.875  1035  1762 I ActivityManager: Killing 6030:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-07 15:30:31.878  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 15:30:31.940  1035  1973 W libprocessgroup: failed to open /acct/uid_10011/pid_6030/cgroup.procs: No such file or directory
09-07 15:30:31.940  4291  4291 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-07 15:30:31.940  4291  4291 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 15:30:31.943  4291  4291 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-07 15:30:32.022  1035  2031 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7072 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-07 15:30:32.027  4291  4291 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:32.028  4291  4291 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 15:30:32.030  4291  4291 V BluetoothFtpService: Ftp Service onStartCommand
09-07 15:30:32.030  4291  4291 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:32.031  4291  4291 V BluetoothFtpService: Ftp Service closeService
09-07 15:30:32.031  4291  4291 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 15:30:32.032  4291  4291 V BluetoothFtpService: successfully stopped ftp service
09-07 15:30:32.033  4291  4291 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:32.033  4291  4291 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:32.033  4291  4291 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:32.033  4291  4291 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:32.033  4291  4291 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 15:30:32.033  4291  4291 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 15:30:32.037  4291  4291 V BluetoothFtpService: Ftp Service onDestroy
09-07 15:30:32.037  4291  4291 V BluetoothFtpService: Ftp Service closeService
09-07 15:30:32.100  1035  1957 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 15:30:32.109  4291  4291 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:32.109  4291  4291 V BluetoothSapService: state: 13
09-07 15:30:32.109  4291  4291 V BluetoothSapService: Stopping SAP server process
09-07 15:30:32.110  4291  4291 V BluetoothSapService: Sap Service closeSapService in
09-07 15:30:32.111  4291  4291 V BluetoothSapService: Close listen Socket : 
09-07 15:30:32.111  4291  4291 V BluetoothSapService: Close rfcomm Socket : 
09-07 15:30:32.111  4291  4291 V BluetoothSapService: Close sapd  Socket : 
09-07 15:30:32.112  4291  4291 V BluetoothSapService: Sap Service closeSapService out
09-07 15:30:32.112  4291  4291 V BluetoothSapService: Sap Service onDestroy
09-07 15:30:32.112  4291  4291 V BluetoothSapService: Sap Service closeSapService in
09-07 15:30:32.112  4291  4291 V BluetoothSapService: Close listen Socket : 
09-07 15:30:32.112  4291  4291 V BluetoothSapService: Close rfcomm Socket : 
09-07 15:30:32.112  4291  4291 V BluetoothSapService: Close sapd  Socket : 
09-07 15:30:32.113  4291  4291 V BluetoothSapService: Sap Service closeSapService out
09-07 15:30:32.133  7072  7072 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 15:30:32.173  7072  7072 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-07 15:30:32.194  7089  7089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 15:30:32.210  1035  1778 I ActivityManager: Killing 6051:com.android.contacts/u0a19 (adj 15): empty #17
,09-07 15:30:32.218  7072  7072 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 15:30:32.219  7072  7072 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 15:30:32.219  7072  7072 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 15:30:32.219  7072  7072 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 15:30:32.220  7072  7072 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 15:30:32.221  7072  7072 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-07 15:30:32.227  7072  7072 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-07 15:30:32.238  4291  4375 D bt_hci_bdroid: cleanup
09-07 15:30:32.238  4291  4488 I bt_lpm  : LPM is already off!!!
09-07 15:30:32.238  4291  4653 I bt_userial_mct: exiting userial_read_thread
09-07 15:30:32.238  4291  4653 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 15:30:32.238  4291  4486 W bt-btif : ag scb idx 1 not allocated
09-07 15:30:32.239  4291  4486 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:32.239  4291  4486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:32.239  4291  4486 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 15:30:32.239  4291  4375 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 15:30:32.239  4291  4488 I bt_vendor: hw_epilog_process
09-07 15:30:32.239  4291  4375 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 15:30:32.239  4291  4375 D bt_userial_mct: userial_close
09-07 15:30:32.239  4291  4375 E bt_userial_mct: pthread_join() FAILED result:3
09-07 15:30:32.239  4291  4375 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 15:30:32.275  4291  4375 D bt_hci_bdroid: set_power 0
09-07 15:30:32.275  4291  4375 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 15:30:32.275  4291  4375 I bt_vendor: bluetooth satus is on
09-07 15:30:32.275  4291  4375 I bt_vendor: bt-vendor : resetting BT status
09-07 15:30:32.275  4291  4375 I bt_vendor: Starting hciattach daemon
09-07 15:30:32.275  4291  4375 I bt_vendor: try to set false
09-07 15:30:32.276  4291  4375 I bt_vendor: Starting hciattach daemon
09-07 15:30:32.276  4291  4375 I bt_vendor: try to set false
,09-07 15:30:32.277  4291  4375 I bt_vendor: cleanup
09-07 15:30:32.278  4291  4486 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 15:30:32.279  4291  4375 I GKI_LINUX: GKI_exit_task 0 done
09-07 15:30:32.279  4291  4375 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 15:30:32.281  1035  1993 W libprocessgroup: failed to open /acct/uid_10019/pid_6051/cgroup.procs: No such file or directory
09-07 15:30:32.282  4291  4371 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 15:30:32.287  4291  4291 D HeadsetService: Received stop request...Stopping profile...
09-07 15:30:32.289  4291  4291 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 15:30:32.289  4291  4291 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:30:32.289  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
09-07 15:30:32.289  4291  4414 D HeadsetStateMachine: Exit Disconnected: -1
,09-07 15:30:32.291  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:32.291  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:32.291  1852  1852 D BluetoothHeadset: Proxy object disconnected
,09-07 15:30:32.296  4291  4291 D A2dpService: Received stop request...Stopping profile...
09-07 15:30:32.297  4291  4466 D A2dpStateMachine: Exit Disconnected: -1
09-07 15:30:32.297  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:32.298  4291  4291 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 15:30:32.299  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 15:30:32.302  4291  4291 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 15:30:32.302  4291  4291 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:30:32.302  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
09-07 15:30:32.304  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:32.304  4291  4371 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 15:30:32.305  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-07 15:30:32.305  4291  4291 D HidService: Received stop request...Stopping profile...
09-07 15:30:32.305  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 15:30:32.305  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
09-07 15:30:32.306  7023  7023 D BluetoothInputDevice: Proxy object disconnected
,09-07 15:30:32.306  7023  7023 D HidProfile: Bluetooth service disconnected
,09-07 15:30:32.308  4291  4291 D HeadsetStateMachine: Unbinding service...
09-07 15:30:32.309  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:32.311  4291  4291 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 15:30:32.311  4291  4291 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 15:30:32.311  4291  4291 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 15:30:32.311  4291  4291 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 15:30:32.311  4291  4291 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 15:30:32.311  4291  4291 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:30:32.311  4291  4291 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-07 15:30:32.313  4291  4291 D HealthService: Received stop request...Stopping profile...
09-07 15:30:32.313  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
09-07 15:30:32.315  4291  4291 D PanService: Received stop request...Stopping profile...
09-07 15:30:32.316  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
09-07 15:30:32.317  7023  7023 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 15:30:32.317  4291  4291 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 15:30:32.317  7023  7023 D PanProfile: Bluetooth service disconnected
09-07 15:30:32.318  4291  4291 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 15:30:32.318  4291  4291 D BtGatt.GattService: stop()
09-07 15:30:32.318  4291  4291 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 15:30:32.320  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
,09-07 15:30:32.321  4291  4291 I BluetoothA2dpServiceJni: cleanupNative
09-07 15:30:32.321  4291  4467 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 15:30:32.322  4291  4291 I GKI_LINUX: GKI_exit_task 2 done
09-07 15:30:32.322  4291  4291 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 15:30:32.323  4291  4291 D BluetoothMapService: Received stop request...Stopping profile...
09-07 15:30:32.323  4291  4291 D BluetoothMapService: stop()
09-07 15:30:32.324  4291  4291 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 15:30:32.324  4291  4291 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 15:30:32.324  4291  4291 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67819b4
09-07 15:30:32.326  4291  4291 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 15:30:32.326  7023  7023 D BluetoothMap: Proxy object disconnected
09-07 15:30:32.326  4291  4291 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 15:30:32.326  7023  7023 D MapProfile: Bluetooth service disconnected
09-07 15:30:32.326  4291  4291 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 15:30:32.326  4291  4291 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:30:32.326  4291  4291 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:30:32.327  4291  4291 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 15:30:32.327  4291  4291 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 15:30:32.328  4291  4291 V BluetoothMapService: Handler(): got msg=4
09-07 15:30:32.328  4291  4291 D BluetoothMapService: MAP Service closeService in
09-07 15:30:32.328  4291  4291 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
,09-07 15:30:32.328  4291  4291 V BluetoothMapService: MAP Service closeService out
09-07 15:30:32.329  4291  4371 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 15:30:32.330  4291  4371 D BluetoothAdapterProperties: Setting state to 10
09-07 15:30:32.330  4291  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 15:30:32.330  4291  4291 D BluetoothMapService: cleanup()
09-07 15:30:32.330  4291  4291 D BluetoothMapService: MAP Service closeService in
09-07 15:30:32.330  4291  4291 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 15:30:32.330  4291  4291 V BluetoothMapService: MAP Service closeService out
,09-07 15:30:32.330  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:32.330  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 15:30:32.330  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-07 15:30:32.330  7023  7038 D BluetoothPan: onBluetoothStateChange on: false
09-07 15:30:32.331  4291  4371 I BluetoothAdapterState: Entering OffState
09-07 15:30:32.332  7023  7040 D BluetoothMap: onBluetoothStateChange: up=false
09-07 15:30:32.332  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:32.334  7023  7038 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 15:30:32.334  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 15:30:32.335  1852  2646 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:32.338  7072  7072 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 15:30:32.339  1852  4447 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:32.340  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:32.341  7023  7040 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 15:30:32.344  7072  7072 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-07 15:30:32.345  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 15:30:32.345  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 15:30:32.346  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:30:32.346  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:32.346  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:32.347  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 15:30:32.347  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-07 15:30:32.350  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 15:30:32.350  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 15:30:32.350  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4b8c2f0 mBinding = false
09-07 15:30:32.351  1035  1117 D BluetoothManagerService: Sending unbind request.
09-07 15:30:32.354  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:32.355  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-07 15:30:32.359  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:32.360  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:32.361  1940  2135 D LGBluetoothAPIService: Message: 2
09-07 15:30:32.361  1940  2135 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@21f08117 mBinding = false
09-07 15:30:32.361  1940  2135 D LGBluetoothAPIService: Sending unbind request.
,09-07 15:30:32.365  4291  4375 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-07 15:30:32.366  4291  4291 I GKI_LINUX: GKI_exit_task 1 done
09-07 15:30:32.366  4291  4291 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 15:30:32.366  4291  4291 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 15:30:32.366  4291  4291 I art     : --- WEIRD: removing null entry 246
09-07 15:30:32.366  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:32.366  4291  4291 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-07 15:30:32.366  4291  4291 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-07 15:30:32.368  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:32.369  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:32.370  7023  7023 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 15:30:32.371  1602  1602 D BluetoothAdapter: 108402175: getState() :  mService = null. Returning STATE_OFF
09-07 15:30:32.371  1602  1602 D BluetoothAdapter: 108402175: getState() :  mService = null. Returning STATE_OFF
09-07 15:30:32.372  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 15:30:32.372  7023  7023 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 15:30:32.374  4291  4291 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-07 15:30:32.376  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 15:30:32.376  4291  4291 I art     : System.exit called, status: 0
09-07 15:30:32.376  4291  4291 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 15:30:32.385  7023  7023 D DockEventReceiver: finishStartingService: stopping service
09-07 15:30:32.392  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:32.392  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:32.394  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 15:30:32.396  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:32.400  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 15:30:32.400  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 15:30:32.400  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:32.403   315   315 V AudioFlinger: 4291 died, releasing its sessions
09-07 15:30:32.403   315   315 V AudioFlinger:  pid 1852 @ 0
09-07 15:30:32.403   315   315 V AudioFlinger:  pid 3237 @ 1
09-07 15:30:32.403   315   315 V AudioFlinger:  pid 3237 @ 2
09-07 15:30:32.403  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:32.413  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:32.414  7023  7023 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-07 15:30:32.436  1035  1993 I ActivityManager: Process com.android.bluetooth (pid 4291) has died
,09-07 15:30:32.437  1035  1993 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-07 15:30:32.454  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:30:32.460  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 15:30:32.461  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:32.473  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 15:30:32.539  1035  1051 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7113 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-07 15:30:32.545  7023  7023 D BluetoothPermissionRequest: onReceive
09-07 15:30:32.550  7023  7023 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 15:30:32.551  7023  7023 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-07 15:30:32.556  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 15:30:32.621  1035  2030 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7130 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-07 15:30:32.643   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 22.475ms
,09-07 15:30:32.662   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 19.220ms
,09-07 15:30:32.671  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:32.677  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:30:32.683  7130  7130 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 15:30:32.683   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 20.462ms
09-07 15:30:32.684  7130  7130 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:32.684  7130  7130 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 15:30:32.685  7130  7130 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 15:30:32.690  7113  7149 W FormManager: Network not available. Please check & try again.
,09-07 15:30:32.692  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
09-07 15:30:32.703  7130  7130 D BluetoothAdapterApp: Loading JNI Library
09-07 15:30:32.704  7113  7150 V FormManager: Network unavailable.
,09-07 15:30:32.707  7113  7150 V FormManager: Network unavailable.
09-07 15:30:32.711  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 15:30:32.712  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 15:30:32.712  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 15:30:32.712  7023  7023 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 15:30:32.712  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 15:30:32.720  7023  7023 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 15:30:32.720  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 15:30:32.720  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 15:30:32.720  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 15:30:32.720  7023  7023 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 15:30:32.721  7023  7023 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-07 15:30:32.725  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 15:30:32.725  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:32.727  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:32.728  1035  1921 I ActivityManager: Killing 6566:com.lge.email/u0a23 (adj 15): empty #17
09-07 15:30:32.738  7130  7130 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@249a8b25 Instance Count = 1
,09-07 15:30:32.758  1035  1778 W libprocessgroup: failed to open /acct/uid_10023/pid_6566/cgroup.procs: No such file or directory
,09-07 15:30:32.759  7130  7130 D BluetoothAdapterApp: onCreate
09-07 15:30:32.761  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:32.769  7044  7044 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 15:30:32.769  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 15:30:32.769  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:32.772  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:30:32.777  4749  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:32.780  4749  7153 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 15:30:32.782  7113  7156 W FormManager: Network not available. Please check & try again.
09-07 15:30:32.782  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:32.784  4749  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 15:30:32.788  7130  7130 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-07 15:30:32.788  7130  7130 D ProfileConfigQcom: Adding HeadsetService
09-07 15:30:32.789  7130  7130 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-07 15:30:32.789  7130  7130 D ProfileConfigQcom: Adding A2dpService
09-07 15:30:32.789  7130  7130 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 15:30:32.791  7130  7130 D ProfileConfigQcom: Adding HidService
09-07 15:30:32.791  7130  7130 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 15:30:32.791  7113  7157 V FormManager: Network unavailable.
09-07 15:30:32.791  7130  7130 D ProfileConfigQcom: Adding HealthService
09-07 15:30:32.792  7130  7130 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-07 15:30:32.792  7130  7130 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 15:30:32.792  7130  7130 D ProfileConfigQcom: Adding PanService
09-07 15:30:32.793  7130  7130 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 15:30:32.793  7130  7130 D ProfileConfigQcom: Adding GattService
09-07 15:30:32.793  7130  7130 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 15:30:32.793  7130  7130 D ProfileConfigQcom: Adding BluetoothMapService
09-07 15:30:32.794  7130  7130 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 15:30:32.795  7130  7130 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-07 15:30:32.800  7023  7023 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 15:30:32.802  7130  7130 V LGMDMManagerInternal: Create singleton instance
,09-07 15:30:32.805  7113  7157 V FormManager: Network unavailable.
09-07 15:30:32.808  7072  7072 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 15:30:32.809  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 15:30:32.810  7072  7072 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-07 15:30:32.835  7072  7072 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:32.836  7072  7072 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:32.842  7072  7072 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-07 15:30:32.843  7072  7072 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-07 15:30:32.843  7072  7072 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-07 15:30:32.843  7072  7072 V SoundPool: doLoad: loading sample sampleID=1
09-07 15:30:32.843  7072  7072 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-07 15:30:32.846  7072  7162 V SoundPool: Start decode
09-07 15:30:32.846  7072  7162 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-07 15:30:32.846   315  1396 V MediaPlayerService: decode(22, 10857164, 17813)
09-07 15:30:32.846   315  1396 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,09-07 15:30:32.846   315  1396 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-07 15:30:32.846   315  1396 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-07 15:30:32.846   315  1396 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-07 15:30:32.846   315  1396 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-07 15:30:32.846   315  1396 V MediaPlayerService: player type = 3
09-07 15:30:32.846   315  1396 V AwesomePlayer: AwesomePlayer create()
09-07 15:30:32.847   315  1396 V AwesomePlayer: reset_l() 
09-07 15:30:32.847   315  1396 V AwesomePlayer: cancelPlayerEvents
09-07 15:30:32.847   315  1396 V AwesomePlayer: setAudioSink() 
09-07 15:30:32.847   315  1396 V AwesomePlayer: reset_l() 
09-07 15:30:32.847   315  1396 V AudioCache: notify(0xb5474c80, 8, 0, 0)
09-07 15:30:32.847   315  1396 V AudioCache: ignored
09-07 15:30:32.847   315  1396 V AwesomePlayer: cancelPlayerEvents
09-07 15:30:32.847   315  1396 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-07 15:30:32.847   315  1396 V AwesomePlayer: setDataSource_l dataSource
09-07 15:30:32.847   315  1396 V LGParserOSAL: SniffLGParser start
09-07 15:30:32.847   315  1396 V LGParserOSAL: MainType:5, SubType=0
09-07 15:30:32.847   315  1396 V LGParserOSAL: #### check Mime : application/ogg
09-07 15:30:32.847   315  1396 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-07 15:30:32.847   315  1396 E MediaExtractor: Use LGExtractor :application/ogg 
09-07 15:30:32.853  7072  7072 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-07 15:30:32.856  6769  6769 D UEI.SmartControl: QS Service created
09-07 15:30:32.859  7072  7072 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 15:30:32.860  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-07 15:30:32.872  7130  7130 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:32.875  7130  7130 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:32.875  7130  7130 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:32.876  7130  7130 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:32.876   315  1396 V LGParserOSAL: supported mime: application/ogg
09-07 15:30:32.877   315  1396 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-07 15:30:32.877   315  1396 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-07 15:30:32.877   315  1396 V AwesomePlayer: mBitrate = -1 bits/sec
09-07 15:30:32.877   315  1396 V AwesomePlayer: AudioTrack Setting
09-07 15:30:32.877   315  1396 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-07 15:30:32.877   315  1396 V AwesomePlayer: setAudioSource() 
09-07 15:30:32.877  7130  7130 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:32.877   315  1396 V MediaPlayerService: prepare
09-07 15:30:32.877   315  1396 V AwesomePlayer: prepareAsync_l() 
09-07 15:30:32.877  7130  7130 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 15:30:32.877   315  1396 V MediaPlayerService: wait for prepare
09-07 15:30:32.877   315  7163 V AwesomePlayer: onPrepareAsyncEvent() 
09-07 15:30:32.877   315  7163 V AwesomePlayer: initAudioDecoder() 
09-07 15:30:32.877   315  7163 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 15:30:32.877   315  7163 V AudioSystem: isOffloadSupported()
09-07 15:30:32.877   315  7163 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 15:30:32.877   315  7163 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 15:30:32.877   315  7163 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 15:30:32.877   315  7163 V AwesomePlayer: getUseOffload() = 0 
09-07 15:30:32.877   315  7163 V OMXCodec: OMXCodec::Create
09-07 15:30:32.877   315  7163 V OMXCodec: findMatchingCodecs()
09-07 15:30:32.877   315  7163 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-07 15:30:32.877   315  7163 V OMXCodec: matchingCodecs.size()=1
09-07 15:30:32.877   315  7163 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-07 15:30:32.879   315  7163 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-07 15:30:32.879   315  7163 V LGCodecAdapter: LG Codec Adapter start
09-07 15:30:32.879   315  7163 V OMXCodec: OMXCodec Createtor
09-07 15:30:32.879   315  7163 V OMXCodec: setComponentRole
09-07 15:30:32.879   315  7163 V OMXCodec: configureCodec protected=0
09-07 15:30:32.879   315  7163 V LGCodecAdapter: called getLGCodecSpecificData
09-07 15:30:32.879   315  7163 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-07 15:30:32.879   315  7163 V LGCodecOSAL: Called LGconfigureCodecMETA
09-07 15:30:32.879   315  7163 V LGCodecOSAL: Called LGconfigureCodecMSG
09-07 15:30:32.879   315  7163 V LGCodecOSAL: Not support LGCodec
09-07 15:30:32.879   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 15:30:32.879   315  7163 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-07 15:30:32.879   315  7163 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-07 15:30:32.879   315  7163 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-07 15:30:32.879   315  7163 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 15:30:32.879   315  7163 V AudioSystem: isOffloadSupported()
09-07 15:30:32.879   315  7163 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 15:30:32.879   315  7163 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 15:30:32.879   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-07 15:30:32.879   315  7163 V OMXCodec: init()
09-07 15:30:32.879   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-07 15:30:32.879   315  7163 V OMXCodec: allocateBuffers
09-07 15:30:32.879   315  7163 V OMXCodec: allocateBuffersOnPort portIndex=0
09-07 15:30:32.879   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-07 15:30:32.880   315  7163 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-07 15:30:32.880   315  7163 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-07 15:30:32.880   315  7163 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 15:30:32.885   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 15:30:32.885   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 15:30:32.885   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-07 15:30:32.885   315  7163 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 15:30:32.887  7072  7072 V LGMDMManager: Create singleton instance
09-07 15:30:32.888  7089  7089 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device, information EasySettings
09-07 15:30:32.891  6769  6769 I UEI.SmartControl: Service initServices...
09-07 15:30:32.891  6769  6769 D UEI.SmartControl: QS start get config
,09-07 15:30:32.895   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-07 15:30:32.895   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-07 15:30:32.895   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-07 15:30:32.895   315  7163 V OMXCodec: init() mAsyncCompletion wait free! 
09-07 15:30:32.895   315  7163 V AwesomePlayer: finishAsyncPrepare_l() 
09-07 15:30:32.895   315  7163 V AudioCache: notify(0xb5474c80, 5, 0, 0)
09-07 15:30:32.895   315  7163 V AudioCache: ignored
09-07 15:30:32.895   315  7163 V AudioCache: notify(0xb5474c80, 1, 0, 0)
09-07 15:30:32.895   315  7163 V AudioCache: prepared
09-07 15:30:32.895   315  1396 V AudioCache: wait - success
09-07 15:30:32.895   315  1396 V MediaPlayerService: start
09-07 15:30:32.895   315  1396 V AwesomePlayer: play_l() 
09-07 15:30:32.895   315  1396 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-07 15:30:32.895   315  1396 V AwesomePlayer: createAudioPlayer_l
09-07 15:30:32.895   315  1396 V AwesomePlayer: seekAudioIfNecessary_l() 
09-07 15:30:32.895   315  1396 V AwesomePlayer: startAudioPlayer_l() 
09-07 15:30:32.895   315  1396 D AudioPlayer: start of Playback, useOffload 0
09-07 15:30:32.895   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 15:30:32.896   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 15:30:32.897   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-07 15:30:32.897   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-07 15:30:32.897   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-07 15:30:32.897   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-07 15:30:32.897   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-07 15:30:32.898   315  7165 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 15:30:32.898   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 15:30:32.899   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-07 15:30:32.899   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-07 15:30:32.899   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-07 15:30:32.899   315  7165 V OMXCodec: [,OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-07 15:30:32.899   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-07 15:30:32.899   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-07 15:30:32.900   315  1396 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-07 15:30:32.900   315  1396 V AudioCache: notify(0xb5474c80, 6, 0, 0)
09-07 15:30:32.900   315  1396 V AudioCache: ignored
09-07 15:30:32.900   315  1396 V MediaPlayerService: wait for playback complete
09-07 15:30:32.900   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.900   315  7167 V AudioCache: memcpy(0xaf0f9000, 0xb1720000, 4096)
09-07 15:30:32.902   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.902   315  7167 V AudioCache: memcpy(0xaf0fa000, 0xb1720000, 4096)
09-07 15:30:32.902   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.902   315  7167 V AudioCache: memcpy(0xaf0fb000, 0xb1720000, 4096)
,09-07 15:30:32.902   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.902   315  7167 V AudioCache: memcpy(0xaf0fc000, 0xb1720000, 4096)
09-07 15:30:32.905   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.905   315  7167 V AudioCache: memcpy(0xaf0fd000, 0xb1720000, 4096)
09-07 15:30:32.905   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.905   315  7167 V AudioCache: memcpy(0xaf0fe000, 0xb1720000, 4096)
09-07 15:30:32.906   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.906   315  7167 V AudioCache: memcpy(0xaf0ff000, 0xb1720000, 4096)
09-07 15:30:32.906   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.906   315  7167 V AudioCache: memcpy(0xaf100000, 0xb1720000, 4096)
09-07 15:30:32.906   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.906   315  7167 V AudioCache: memcpy(0xaf101000, 0xb1720000, 4096)
09-07 15:30:32.907   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.907   315  7167 V AudioCache: memcpy(0xaf102000, 0xb1720000, 4096)
09-07 15:30:32.907   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.907   315  7167 V AudioCache: memcpy(0xaf103000, 0xb1720000, 4096)
09-07 15:30:32.908   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.908   315  7167 V AudioCache: memcpy(0xaf104000, 0xb1720000, 4096)
09-07 15:30:32.908   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.908   315  7167 V AudioCache: memcpy(0xaf105000, 0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: memcpy(0xaf106000, 0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: memcpy(0xaf107000, 0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: memcpy(0xaf108000, 0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.909   315  7167 V AudioCache: memcpy(0xaf109000, 0xb1720000, 4096)
09-07 15:30:32.910   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.910   315  7167 V AudioCache: memcpy(0xaf10a000, 0xb1720000, 4096)
09-07 15:30:32.910   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.911   315  7167 V AudioCache: memcpy(0xaf10b000, 0xb1720000, 4096)
09-07 15:30:32.911   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.911   315  7167 V AudioCache: memcpy(0xaf10c000, 0xb1720000, 4096)
09-07 15:30:32.911   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.911   315  7167 V AudioCache: memcpy(0xaf10d000, 0xb1720000, 4096)
09-07 15:30:32.912   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.912   315  7167 V AudioCache: memcpy(0xaf10e000, 0xb1720000, 4096)
09-07 15:30:32.912   315  7167 V AudioCache: write(0xb1720000, 4096)
,09-07 15:30:32.912   315  7167 V AudioCache: memcpy(0xaf10f000, 0xb1720000, 4096)
09-07 15:30:32.912   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.912   315  7167 V AudioCache: memcpy(0xaf110000, 0xb1720000, 4096)
09-07 15:30:32.913   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.913   315  7167 V AudioCache: memcpy(0xaf111000, 0xb1720000, 4096)
09-07 15:30:32.913   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.913   315  7167 V AudioCache: memcpy(0xaf112000, 0xb1720000, 4096)
09-07 15:30:32.914   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.914   315  7167 V AudioCache: memcpy(0xaf113000, 0xb1720000, 4096)
,09-07 15:30:32.914   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.914   315  7167 V AudioCache: memcpy(0xaf114000, 0xb1720000, 4096)
09-07 15:30:32.915   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.915   315  7167 V AudioCache: memcpy(0xaf115000, 0xb1720000, 4096)
09-07 15:30:32.915   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.915   315  7167 V AudioCache: memcpy(0xaf116000, 0xb1720000, 4096)
09-07 15:30:32.916   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.916   315  7167 V AudioCache: memcpy(0xaf117000, 0xb1720000, 4096)
09-07 15:30:32.917   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.917   315  7167 V AudioCache: memcpy(0xaf118000, 0xb1720000, 4096)
09-07 15:30:32.917   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.917   315  7167 V AudioCache: memcpy(0xaf119000, 0xb1720000, 4096)
09-07 15:30:32.918   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.918   315  7167 V AudioCache: memcpy(0xaf11a000, 0xb1720000, 4096)
09-07 15:30:32.918   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.918   315  7167 V AudioCache: memcpy(0xaf11b000, 0xb1720000, 4096)
09-07 15:30:32.919   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.919   315  7167 V AudioCache: memcpy(0xaf11c000, 0xb1720000, 4096)
09-07 15:30:32.919   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.919   315  7167 V AudioCache: memcpy(0xaf11d000, 0xb1720000, 4096)
09-07 15:30:32.920   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.920   315  7167 V AudioCache: memcpy(0xaf11e000, 0xb1720000, 4096)
09-07 15:30:32.920   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.920   315  7167 V AudioCache: memcpy(0xaf11f000, 0xb1720000, 4096)
09-07 15:30:32.921   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.921   315  7167 V AudioCache: memcpy(0xaf120000, 0xb1720000, 4096)
09-07 15:30:32.921   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.921   315  7167 V AudioCache: memcpy(0xaf121000, 0xb1720000, 4096)
09-07 15:30:32.922   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.922   315  7167 V AudioCache: memcpy(0xaf122000, 0xb1720000, 4096)
09-07 15:30:32.922   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.922   315  7167 V AudioCache: memcpy(0xaf123000, 0xb1720000, 4096)
09-07 15:30:32.923   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.923   315  7167 V AudioCache: memcpy(0xaf124000, 0xb1720000, 4096)
09-07 15:30:32.923   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.923   315  7167 V AudioCache: memcpy(0xaf125000, 0xb1720000, 4096)
09-07 15:30:32.923   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.923   315  7167 V AudioCache: memcpy(0xaf126000, 0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V AudioCache: memcpy(0xaf127000, 0xb1720000, 4096)
09-07 15:30:32.924   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-07 15:30:32.924   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V AudioCache: memcpy(0xaf128000, 0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 15:30:32.924   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V AudioCache: memcpy(0xaf129000, 0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 15:30:32.924   315  7167 V AudioCache: write(0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V AudioCache: memcpy(0xaf12a000, 0xb1720000, 4096)
09-07 15:30:32.924   315  7167 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 15:30:32.924   315  7167 V OMXCodec: [OMX.google.vorbis,.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 15:30:32.924   315  7167 V AwesomePlayer: postAudioEOS() 
,09-07 15:30:32.924   315  7167 V AudioCache: write(0xb1720000, 280)
09-07 15:30:32.925   315  7167 V AudioCache: memcpy(0xaf12b000, 0xb1720000, 280)
09-07 15:30:32.926   315  7163 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-07 15:30:32.926   315  7163 V AwesomePlayer: onStreamDone
09-07 15:30:32.926   315  7163 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-07 15:30:32.926   315  7163 V AudioCache: notify(0xb5474c80, 2, 0, 0)
09-07 15:30:32.926   315  7163 V AudioCache: playback complete
09-07 15:30:32.926   315  7163 V AwesomePlayer: pause_l() 
09-07 15:30:32.926   315  7163 V AudioCache: notify(0xb5474c80, 7, 0, 0)
09-07 15:30:32.926   315  7163 V AudioCache: ignored
09-07 15:30:32.926   315  7163 V AwesomePlayer: cancelPlayerEvents
09-07 15:30:32.926   315  1396 V AudioCache: wait - success
09-07 15:30:32.926   315  1396 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-07 15:30:32.926   315  7163 D AudioPlayer: Pause Playback at 1068125
09-07 15:30:32.927   315  1396 V AwesomePlayer: reset_l() 
09-07 15:30:32.927   315  1396 V AudioCache: notify(0xb5474c80, 8, 0, 0)
09-07 15:30:32.927   315  1396 V AudioCache: ignored
09-07 15:30:32.927   315  1396 V AwesomePlayer: cancelPlayerEvents
09-07 15:30:32.927   315  1396 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-07 15:30:32.927   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-07 15:30:32.927   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-07 15:30:32.927   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-07 15:30:32.927   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-07 15:30:32.927   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-07 15:30:32.928   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
09-07 15:30:32.928   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 15:30:32.928   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-07 15:30:32.928   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-07 15:30:32.928   315  7165 V OMXCodec: [OMX.google.v,orbis.decoder] Now Loaded.
09-07 15:30:32.928   315  7165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-07 15:30:32.928   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 15:30:32.928   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-07 15:30:32.928   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-07 15:30:32.929   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-07 15:30:32.929   315  1396 D AudioPlayer: AudioPlayer releasing audio source
09-07 15:30:32.929   315  1396 D AudioPlayer: AudioPlayer done releasing audio source
09-07 15:30:32.929   315  1396 V AwesomePlayer: reset_l() 
09-07 15:30:32.929   315  1396 V AwesomePlayer: cancelPlayerEvents
09-07 15:30:32.929   315  1396 V AwesomePlayer: ~AwesomePlayer call
09-07 15:30:32.930   315  1396 V AwesomePlayer: reset_l() 
09-07 15:30:32.930   315  1396 V AwesomePlayer: cancelPlayerEvents
09-07 15:30:32.930  7072  7162 V SoundPool: close(31)
09-07 15:30:32.930  7072  7162 V SoundPool: pointer = 0x9fe70000, size = 205080, sampleRate = 48000, numChannels = 2
09-07 15:30:32.960  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 15:30:32.961  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-07 15:30:32.967  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1825
,09-07 15:30:33.158  6769  6769 I UEI.SmartControl: Supports setup maps: true
09-07 15:30:33.161  6769  6769 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 15:30:33.161  6769  6769 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-07 15:30:33.161  6769  6769 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,09-07 15:30:33.161  6769  6769 I UEI.SmartControl: ### init IR Blaster...
09-07 15:30:33.164  6769  6769 D serial_port: Configuring serial port
09-07 15:30:33.165  6769  6769 E UEI.SmartControl: UEIBLaster setting for 616
09-07 15:30:33.165  6769  6769 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 15:30:33.165  6769  6769 I UEI.SmartControl: configuring settings for MAXQ616
09-07 15:30:33.165  6769  6769 I UEI.SmartControl: Get version...
09-07 15:30:33.184  6769  7169 D UEI.SmartControl: serial port data available: 21
,09-07 15:30:33.211  6769  6769 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 15:30:33.211  6769  6769 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 15:30:33.211  6769  6769 I UEI.SmartControl: QS saving settings...
09-07 15:30:33.213  6769  6769 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 15:30:33.231  6769  7169 D UEI.SmartControl: serial port data available: 4
,09-07 15:30:33.263  6769  7178 I UEI.SmartControl: Device manager: loading config....
,09-07 15:30:33.267  6769  7178 D UEI.SmartControl: ----------- loading internal config...
09-07 15:30:33.271  6769  6769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-07 15:30:33.275  6769  6769 E UEI.SmartControl: Services init done
09-07 15:30:33.275  6769  6769 D UEI.SmartControl: QS Service init finished
09-07 15:30:33.277  6769  6769 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 15:30:33.277  6769  6769 D UEI.SmartControl: QS Service version code: 201091
09-07 15:30:33.278  6769  6769 D UEI.SmartControl: Service requested: Control
09-07 15:30:33.279  6769  7178 E UEI.SmartControl: Loading SETTINGS...
09-07 15:30:33.284  6769  6769 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-07 15:30:33.287  7072  7072 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 15:30:33.288  6769  6785 I UEI.SmartControl: ------ IControl API: 11
09-07 15:30:33.288  6769  6785 D UEI.SmartControl: File observer start...
09-07 15:30:33.289  6769  6785 E UEI.SmartControl: IR Port is disabled: false
09-07 15:30:33.289  6769  6769 D UEI.SmartControl: Internal service binding...
09-07 15:30:33.289  6769  6785 D UEI.SmartControl: Starting file observer...
09-07 15:30:33.290  6769  6785 I UEI.SmartControl: Registering callback...
09-07 15:30:33.292  6769  6784 I UEI.SmartControl: ------ IControl API: 19
09-07 15:30:33.293  6769  7178 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 15:30:33.294  6769  6784 I UEI.SmartControl: Registering Services Ready callback...
09-07 15:30:33.301  6769  7177 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-07 15:30:33.301  6769  7177 D UEI.SmartControl: -----service ready thread exits
,09-07 15:30:33.303  7072  7088 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-07 15:30:33.303  7072  7160 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-07 15:30:33.304  7072  7160 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-07 15:30:33.304  7072  7072 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-07 15:30:33.304  7072  7072 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-07 15:30:33.305  6769  6785 I UEI.SmartControl: ------ IControl API: 8
09-07 15:30:33.306  7072  7072 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-07 15:30:33.307  7072  7072 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-07 15:30:33.307  7072  7072 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-07 15:30:33.308  7072  7072 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-07 15:30:33.308  7072  7072 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-07 15:30:33.309  7072  7072 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-07 15:30:33.310  7072  7072 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-07 15:30:33.314  7072  7072 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 15:30:33.316  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-07 15:30:33.316  7072  7072 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 15:30:33.317  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-07 15:30:33.318  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 15:30:33.319  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-07 15:30:33.319  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-07 15:30:33.321  7072  7072 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473255033320]
09-07 15:30:33.325  7072  7072 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-07 15:30:33.330  1035  1050 I ActivityManager: Killing 6638:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-07 15:30:33.345  7072  7180 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-07 15:30:33.365  1035  1050 I ActivityManager: Killing 6073:com.android.gallery3d/u0a27 (adj 15): empty #18
,09-07 15:30:33.395  1035  1973 W libprocessgroup: failed to open /acct/uid_10061/pid_6638/cgroup.procs: No such file or directory
,09-07 15:30:33.399  1035  1051 W libprocessgroup: failed to open /acct/uid_10027/pid_6073/cgroup.procs: No such file or directory
09-07 15:30:33.408  7072  7072 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-07 15:30:33.412  7072  7072 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-07 15:30:33.413  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-07 15:30:33.413  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-07 15:30:33.414  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-07 15:30:33.414  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,09-07 15:30:33.415  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-07 15:30:33.428  7072  7072 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-07 15:30:34.297  1035  1957 D WifiServiceImplEx: setWifiEnabled: true pid=6904, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-07 15:30:34.299  1035  1957 D WifiService: setWifiEnabled: true pid=6904, uid=10118
,09-07 15:30:34.299  1035  1957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:30:34.319  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:34.319  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:34.319  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:34.320  1035  1432 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 15:30:34.320  1035  1432 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-07 15:30:34.324  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 15:30:34.324  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 15:30:34.324  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 15:30:34.324  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 15:30:34.324  1035  1432 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 15:30:34.324  1035  1432 E WifiHW  : unknown target_country: EU , set to default
09-07 15:30:34.324  1035  1432 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 15:30:34.324  1035  1432 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 15:30:34.324  1035  1432 I WifiUtil: gEnableBmps=1
09-07 15:30:34.371  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:34.391  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:30:34.401  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:34.402  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:34.406  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:34.411  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 15:30:34.420  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:34.424  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:34.424  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:34.426  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 15:30:34.430  6465  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 15:30:34.441  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 15:30:34.461  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 15:30:34.487  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:34.525  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:34.571  1035  1050 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7198 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-07 15:30:34.576  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:34.576  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 15:30:34.743  1035  1938 I art     : Explicit concurrent mark sweep GC freed 64783(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.778ms total 140.665ms
,09-07 15:30:34.782  7198  7198 I AppUp4:AppBoxCP: onCreate
,09-07 15:30:34.782  7198  7198 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-07 15:30:34.793  7198  7198 I AppUp4:DB:  setFingerPrint start
09-07 15:30:34.793  7198  7198 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-07 15:30:34.801  7198  7198 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-07 15:30:34.801  7198  7198 I AppUp4:DB:  SDK version = 21
09-07 15:30:34.801  7198  7198 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-07 15:30:34.803  7198  7198 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-07 15:30:34.805  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 15:30:34.805  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:34.807  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 15:30:34.808  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 15:30:34.815  7198  7198 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 15:30:34.883  7198  7198 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:34.884  7198  7198 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:34.894  7198  7198 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34860687
09-07 15:30:34.894  7198  7198 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 15:30:34.894  7198  7198 D AppUp4:CustFacade: isPhone : true
09-07 15:30:34.895  7198  7198 D AppUp4:CustModeStarterReceiver: begin check event
09-07 15:30:34.895  7198  7198 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-07 15:30:34.896  7198  7198 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-07 15:30:34.896  7198  7218 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-07 15:30:34.897  7198  7218 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-07 15:30:34.897  7198  7218 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-07 15:30:34.898  1035  1050 I ActivityManager: Killing 6682:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-07 15:30:34.928  1035  2009 W libprocessgroup: failed to open /acct/uid_10080/pid_6682/cgroup.procs: No such file or directory
,09-07 15:30:34.929  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:34.929  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:34.931  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:34.934  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:34.943  4749  7231 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 15:30:34.949  4749  7232 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:34.949  4749  7232 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 15:30:34.981  1035  1762 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7233 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 15:30:35.045  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 15:30:35.050  1035  1117 D Tethering: InitialState.processMessage what=4
09-07 15:30:35.059   310   893 D SoftapController: Softap fwReload - Ok
09-07 15:30:35.061  1035  1432 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (730ms)
09-07 15:30:35.062  7233  7233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:30:35.063  7233  7233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:35.063   310   893 D CommandListener: Setting iface cfg
09-07 15:30:35.064   310   893 D CommandListener: Trying to bring down wlan0
09-07 15:30:35.064  7233  7233 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 15:30:35.065  7233  7233 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 15:30:35.066   310   893 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:30:35.070  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:30:35.071  1035  1432 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-07 15:30:35.068  7251  7251 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:35.068  7251  7251 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:35.099  7251  7251 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 15:30:35.106  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:35.106  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:35.106  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:35.111  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:35.112  1035  1432 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 15:30:35.112  1035  1432 D WifiMonitor: connecting to supplicant
09-07 15:30:35.112  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 15:30:35.114  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:35.117  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 15:30:35.117  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:35.134  7251  7251 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 15:30:35.135  7251  7251 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-07 15:30:35.173  7233  7233 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-07 15:30:35.188  7233  7233 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-07 15:30:35.234  7233  7233 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 15:30:35.234  7251  7251 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 15:30:35.261  7233  7233 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:35.261  7233  7233 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:35.274  7251  7251 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-07 15:30:35.288  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-07 15:30:35.289  7251  7251 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 15:30:35.291  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-07 15:30:35.291  1035  7260 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 15:30:35.291  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 15:30:35.291  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 15:30:35.291  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 15:30:35.291  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 15:30:35.292  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-07 15:30:35.293  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-07 15:30:35.294  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 15:30:35.295  1035  1432 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 15:30:35.297  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:35.300  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:35.302  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-07 15:30:35.304  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:35.306  1035  1432 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 15:30:35.306  1035  1432 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 15:30:35.307  1035  1432 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 15:30:35.308  1035  1432 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 15:30:35.308  1035  1432 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-07 15:30:35.309  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:35.309  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:35.309  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:35.309  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.309  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.309  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.309  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.309  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:35.310  1035  1432 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 15:30:35.310  1940  1940 D WfdService: Waiting for WifiP2p enabling
09-07 15:30:35.311  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:35.311  1035  1432 D WifiNative-wlan0: SET update_config 1: returned true
09-07 15:30:35.312  1035  1432 D WifiConfigStore: Loading config and enabling all networks 
09-07 15:30:35.312  1035  1432 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 15:30:35.312  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 15:30:35.312  1035  1432 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-07 15:30:35.313  1035  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 15:30:35.313  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:35.313  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:35.313  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:35.313  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:35.317  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:35.317  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:35.317  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:35.317  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:30:35.328  1035  1432 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-07 15:30:35.336  1035  1432 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 15:30:35.336  1035  1432 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-07 15:30:35.338  1035  1432 D WifiStateMachine: enableVerboseLogging : level 2
,09-07 15:30:35.338  1035  1432 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 15:30:35.338  1035  1432 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 15:30:35.338  1035  1432 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 15:30:35.339  1035  1432 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 15:30:35.339  1035  1432 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 15:30:35.339  1035  1432 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 15:30:35.339  1035  1432 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 15:30:35.339  1035  1432 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 15:30:35.339  1035  1432 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 15:30:35.340  1035  1432 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 15:30:35.340  1035  1432 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 15:30:35.340  1035  1432 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 15:30:35.340  1035  1432 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 15:30:35.340  1035  1432 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-07 15:30:35.342  1035  1432 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 15:30:35.342  1035  1432 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 15:30:35.342  1035  1432 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 15:30:35.342  1940  1940 D WfdsService: Supplicant Connection state is changed : true
09-07 15:30:35.342  1035  1432 D WifiNative-HAL: Setting external_sim to 1
09-07 15:30:35.342  1035  1432 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 15:30:35.342  1940  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 15:30:35.342  1940  2330 D WfdsService: Set the WFDS Monitor: true
09-07 15:30:35.342  1940  2330 D WfdsMonitor: WfdsMonitorThread create
09-07 15:30:35.342  1940  2330 D WfdsMonitor: WFDS Monitor is created and started
09-07 15:30:35.342  1940  2330 D WfdsService: WiFi: Supplicant connection re-established
09-07 15:30:35.343  1035  1432 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 15:30:35.343  1035  1432 I WifiNative-HAL: startHal
09-07 15:30:35.343  1035  1432 D wifi    : setting scan oui 0xaf69f020
09-07 15:30:35.343  1035  1432 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 15:30:35.343  1035  1432 I WifiNative-HAL: startHal
09-07 15:30:35.343  1035  1432 D wifi    : setting scan oui 0xaf69f020
09-07 15:30:35.343  1035  1432 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 15:30:35.343  1035  1432 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 15:30:35.344  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 15:30:35.344  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 15:30:35.344  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 15:30:35.344  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 15:30:35.344  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 15:30:35.344  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 15:30:35.344  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 15:30:35.344  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 15:30:35.345  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 15:30:35.345  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 15:30:35.345  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 15:30:35.345  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 15:30:35.345  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 15:30:35.345  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_dri,ver_cmd RXFILTER-STOP
09-07 15:30:35.345  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 15:30:35.345  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 15:30:35.345  7251  7251 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-07 15:30:35.346  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 15:30:35.346  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 15:30:35.346  1940  7263 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 15:30:35.346  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 15:30:35.346  1940  7263 E CtrlSupplicant: Succeed to open control connection
09-07 15:30:35.346  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 15:30:35.346  1940  7263 E CtrlSupplicant: Succeed to open monitor connection
09-07 15:30:35.347  1035  1432 E WifiNative: : [176,809,211 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 15:30:35.347  1035  1432 D WifiNative-wlan0: doBoolean: RECONNECT
09-07 15:30:35.347  1940  7263 D WfdsMonitor: Supplicant connection established
09-07 15:30:35.347  1940  2330 D WfdsService: Connected to the supplicant for wfds
09-07 15:30:35.347  1035  1432 D WifiNative-wlan0: RECONNECT: returned true
,09-07 15:30:35.347  1035  1432 D WifiNative-wlan0: doString: [STATUS]
09-07 15:30:35.348  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 15:30:35.348  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 15:30:35.348  1035  1432 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 15:30:35.348  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 15:30:35.348  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
09-07 15:30:35.349  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.350  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 15:30:35.350  1035  1035 D RttService: SCAN_AVAILABLE : 3
,09-07 15:30:35.350  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.350  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.350  1035  1556 I WifiNative-HAL: startHal
09-07 15:30:35.350  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf69f020
09-07 15:30:35.350  1035  1556 D wifi    : failed to get capabilities : -3
09-07 15:30:35.350  1035  1556 E WifiScanningService: could not get scan capabilities
09-07 15:30:35.351   310   893 D CommandListener: Setting iface cfg
09-07 15:30:35.351   310   893 D CommandListener: Trying to bring up p2p0
09-07 15:30:35.351  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 15:30:35.351  1035  1390 D LGWifiP2pService: P2pEnablingState
,09-07 15:30:35.351  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.351  1035  1390 D LGWifiP2pService: P2p socket connection successful
09-07 15:30:35.351  1035  1390 D LGWifiP2pService: P2pEnabledState
09-07 15:30:35.352  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 15:30:35.352  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,09-07 15:30:35.354  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 15:30:35.354  1940  1940 D WfdsService: WifiP2pState is changed : true
09-07 15:30:35.354  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 15:30:35.354  1940  2330 D WfdsService: Receive the WFDS_ENABLE Method
09-07 15:30:35.354  1940  2330 D WfdsService: Set the WFDS Monitor: true
09-07 15:30:35.355  1940  2330 D WfdsService: Connected to the supplicant for wfds
09-07 15:30:35.355  1940  2330 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 15:30:35.355  1940  1940 D WfdsService: isConnected: false
09-07 15:30:35.355  7251  7251 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 15:30:35.355  1940  2330 D WfdsService: selectPreferredScanChannel [36]
09-07 15:30:35.355  1940  2330 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 15:30:35.355  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 15:30:35.356  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 15:30:35.356  1035  1432 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 15:30:35.356  1035  1432 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 15:30:35.356  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-07 15:30:35.356  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 15:30:35.356  1035  1390 D LGWifiP2pService: before postfix = G3
09-07 15:30:35.356  1035  1432 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 15:30:35.356  1035  1390 D WifiServerServiceExt: postfix byte check : 2
09-07 15:30:35.356  1035  1390 D LGWifiP2pService: after postfix = G3
09-07 15:30:35.356  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 15:30:35.357  1035  1432 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 15:30:35.357  1035  1432 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 15:30:35.357  1035  1432 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 15:30:35.357  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 15:30:35.357  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 15:30:35.357  1035  1432 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 15:30:35.357  1035  1432 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 15:30:35.358  7251  7251 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 15:30:35.358  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 15:30:35.358  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 15:30:35.358  1035  1432 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 15:30:35.359  1035  1432 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 15:30:35.359  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 15:30:35.359  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 15:30:35.359  1035  1432 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 15:30:35.359  1035  1432 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 15:30:35.359  7251  7251 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 15:30:35.359  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 15:30:35.359  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-07 15:30:35.359  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-07 15:30:35.360  1035  1390 D LGWifiP2pService: DeviceAddress: 
09-07 15:30:35.360  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 15:30:35.360  1035  1432 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 15:30:35.360  1035  1432 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 15:30:35.360  1940  1940 I WfdStateTracker: handleP2pThisDevi,ceChanged
09-07 15:30:35.360  1035  1432 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 15:30:35.361  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-07 15:30:35.361  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 15:30:35.361  1940  1940 D WfdsService: Update P2p Interface State: 3
09-07 15:30:35.361  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-07 15:30:35.362  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 15:30:35.362  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 15:30:35.362  7251  7251 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.363  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 15:30:35.363  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.363  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.363  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.363  7251  7251 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 15:30:35.363  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.363  1035  1432 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 15:30:35.363  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.364  1035  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-07 15:30:35.364  1035  1432 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,09-07 15:30:35.364  1940  7263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.364  1940  7263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.364  1035  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.364  1035  1432 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 15:30:35.365  1035  1432 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 15:30:35.365  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 15:30:35.366  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,09-07 15:30:35.366  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 15:30:35.366  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 15:30:35.366  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 15:30:35.379  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
,09-07 15:30:35.379  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 15:30:35.379  1035  1390 D LGWifiP2pService: InactiveState
09-07 15:30:35.379  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 15:30:35.379  7251  7251 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:35.379  1035  1390 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.379  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.379  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 15:30:35.380  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 15:30:35.380  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:35.380  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:35.380  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:35.381  1035  1432 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 15:30:35.381  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 15:30:35.381  1035  1432 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-07 15:30:35.382  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.382  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 15:30:35.382  1035  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.382  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.382  7251  7251 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 15:30:35.382  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:35.382  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.383  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  ,1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1940  2330 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.383  1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:35.384  1940  7263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 15:30:35.384  1035  1035 E WifiServerServiceExt: No p2p device connected
09-07 15:30:35.384  1940  7263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.384  1940  7263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.384  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.384  1035  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.384  7233  7233 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 15:30:35.384  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.384  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.384  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:35.384  1035  7260 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.384  1035  7260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.384  1035  7260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:35.385  1035  1432 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 15:30:35.385  1035  1432 D WifiNative-wlan0: doBoolean: SCAN
09-07 15:30:35.385  1035  1432 D WifiNative-wlan0: SCAN: returned false
09-07 15:30:35.386  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=176848  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 15:30:35.387  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=176849  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 15:30:35.387  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 15:30:35.387  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:35.388  1035  1432 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:35.388  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:35.388  1035  1432 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:35.388  1035  1432 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:35.389  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.389  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 15:30:35.389  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 15:30:35.389  1035  1432 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:35.389  1035  1432 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:35.390  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:35.390  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 15:30:35.411  3237  3237 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-07 15:30:35.411  3237  3237 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:35.411  3237  3237 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 15:30:35.415  7233  7233 I HubEmail: JNI_OnLoad()
09-07 15:30:35.415  7233  7233 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 15:30:35.415  7233  7233 I HubEmail: registerNatives()
09-07 15:30:35.415  7233  7233 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 15:30:35.415  7233  7233 I HubEmail: registerNativeMethods()
09-07 15:30:35.415  7233  7233 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 15:30:35.415  7233  7233 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-07 15:30:35.470  1035  2030 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7269 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-07 15:30:35.482  7233  7267 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.482  7113  7266 W FormManager: Network not available. Please check & try again.
09-07 15:30:35.489  7113  7268 V FormManager: Network unavailable.
,09-07 15:30:35.493  7113  7268 V FormManager: Network unavailable.
09-07 15:30:35.501  1035  1957 I ActivityManager: Killing 6703:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-07 15:30:35.565  1035  1575 W libprocessgroup: failed to open /acct/uid_10097/pid_6703/cgroup.procs: No such file or directory
09-07 15:30:35.663  7269  7269 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:35.663  7269  7269 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:35.667  7269  7269 D PhoneMonitor: Register our PhoneStateListener
09-07 15:30:35.694  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-07 15:30:35.699  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-07 15:30:35.718  7269  7269 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-07 15:30:35.718  7269  7269 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-07 15:30:35.719  7269  7269 D TelephonyAutoProfiling: [parse] Load xml
09-07 15:30:35.722  7269  7269 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-07 15:30:35.722  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-07 15:30:35.722  7269  7269 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-07 15:30:35.734  7269  7269 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-07 15:30:35.751  1035  2030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7291 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 15:30:35.752  1035  2030 I ActivityManager: Killing 6732:com.lge.eula/1000 (adj 15): empty #17
09-07 15:30:35.817  1035  1778 W libprocessgroup: failed to open /acct/uid_1000/pid_6732/cgroup.procs: No such file or directory
,09-07 15:30:35.939  7251  7251 E wpa_supplicant: USIM:  scard_init function
09-07 15:30:35.939  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,09-07 15:30:35.939  1035  7260 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 15:30:35.939  7251  7251 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-07 15:30:35.939  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 15:30:35.939  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-07 15:30:35.939  1035  7260 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 15:30:35.941  1035  1432 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:35.942  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-07 15:30:35.942  1035  1432 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:35.942  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-07 15:30:35.943  1035  1432 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:35.944  1035  1432 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:35.944  1035  1432 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 15:30:35.955  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=177417  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-07 15:30:35.961  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.961  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:35.961  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.961  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:35.965  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 15:30:35.970  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:35.972  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.973  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:35.973  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 15:30:35.974  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=177437  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 15:30:35.975  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:35.975  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-07 15:30:35.978  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:35.979  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:35.980  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.036  1035  1993 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7309 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-07 15:30:36.037  1035  1993 I ActivityManager: Killing 5638:com.lge.bnr/1000 (adj 15): empty #17
,09-07 15:30:36.057  7251  7251 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 15:30:36.061  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 15:30:36.061  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 15:30:36.061  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,09-07 15:30:36.061  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 15:30:36.061  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:36.062  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:36.062  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=177525  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 15:30:36.063  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=177525  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 15:30:36.064  1035  1432 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=177526
09-07 15:30:36.064  1035  1432 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=177527
09-07 15:30:36.065  1035  1432 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=177527
09-07 15:30:36.065  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=177528
,09-07 15:30:36.067  7251  7251 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:30:36.067  7251  7251 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 15:30:36.068  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:36.068  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:36.068  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 15:30:36.068  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:30:36.068  1035  7260 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:30:36.068  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 15:30:36.068  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 15:30:36.069  1035  7260 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 15:30:36.069  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:36.069  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:36.070  1035  1432 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=177532
09-07 15:30:36.071  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=177533  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 15:30:36.096  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 15:30:36.097  1035  2031 W libprocessgroup: failed to open /acct/uid_1000/pid_5638/cgroup.procs: No such file or directory
,09-07 15:30:36.106  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.106  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.106  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 15:30:36.107  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=177569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 15:30:36.110  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.110  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.110  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 15:30:36.110  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.110  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:36.111  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:36.111  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 15:30:36.111  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=177574  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 15:30:36.112  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=177575  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,09-07 15:30:36.113  1035  1432 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=177576
09-07 15:30:36.114  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.114  1035  1432 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=177576
09-07 15:30:36.114  1035  1432 D WifiNative-wlan0: doString: [STATUS]
,09-07 15:30:36.115  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:36.115  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:36.116  1035  1432 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 15:30:36.117  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.117  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:36.118  1035  1432 I WifiServiceExtension: setVHTCapabilityType  : false
09-07 15:30:36.119  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.139  1035  1432 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 15:30:36.139  1035  1432 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-07 15:30:36.148  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.148  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.148  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 15:30:36.150  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.150  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:36.151  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.151  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.151  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 15:30:36.153  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.155  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.155  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:36.156  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:36.160  1035  1432 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 15:30:36.160  1035  1432 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:30:36.160  1035  1432 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 15:30:36.160  1035  1481 D ConnectivityService: Got NetworkAgent Messenger
09-07 15:30:36.160  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 15:30:36.160  1035  1481 D ConnectivityService: NetworkAgent connected
09-07 15:30:36.160  1035  1432 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 15:30:36.160  1035  1432 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 15:30:36.168  1035  1432 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 15:30:36.168  1035  1432 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:30:36.168  1035  1432 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 15:30:36.169  1035  1432 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 15:30:36.169  1035  1432 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-07 15:30:36.177  1035  1432 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 15:30:36.178   310   893 D CommandListener: Setting iface cfg
09-07 15:30:36.226  1035  1889 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7334 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 15:30:36.228  1035  1889 I ActivityManager: Killing 2124:com.lge.music/u0a34 (adj 15): empty #17
09-07 15:30:36.253   315   315 V AudioFlinger: 2124 died, releasing its sessions
09-07 15:30:36.253   315   315 V AudioFlinger:  pid 1852 @ 0
09-07 15:30:36.253   315   315 V AudioFlinger:  pid 3237 @ 1
09-07 15:30:36.253   315   315 V AudioFlinger:  pid 3237 @ 2
,09-07 15:30:36.283  1035  1762 W libprocessgroup: failed to open /acct/uid_10034/pid_2124/cgroup.procs: No such file or directory
,09-07 15:30:36.290  1035  1432 E WifiStateMachine: Start Dhcp Watchdog 2
09-07 15:30:36.290  1035  7333 D DhcpStateMachine: StoppedState
09-07 15:30:36.290  1035  7333 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:36.290  1035  7333 D DhcpStateMachine: WaitBeforeStartState
09-07 15:30:36.290  1035  1432 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=177753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:36.291  1035  1432 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=177753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:36.291  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=177754  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:36.292  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:36.292  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:36.293  1035  1432 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:36.293  1035  1432 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:36.293  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:36.294  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:36.295  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:36.295  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 15:30:36.296  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:36.296  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 15:30:36.296  1035  1432 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=177759  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:36.297  1035  1432 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=177759  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-07 15:30:36.298  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=177760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:36.299  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:130903] from screen [on:0 period:81253771] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 15:30:36.301  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:81253772] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 15:30:36.301  1035  1432 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-07 15:30:36.305  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.306  1035  1481 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-07 15:30:36.306  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:36.307  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:36.307  1035  1432 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:36.308  1035  1432 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:36.308  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:36.309  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:36.309  7334  7334 I art     : Almond Protected OAT
09-07 15:30:36.309  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 15:30:36.309  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=164,0,0
09-07 15:30:36.310  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=164,0,0
09-07 15:30:36.310  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 15:30:36.310  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 15:30:36.311  1035  1432 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 15:30:36.311  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 15:30:36.311  1035  1432 D WifiNative-wlan0: SET ps 0: returned true
09-07 15:30:36.311  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 15:30:36.312  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,09-07 15:30:36.312  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 15:30:36.313  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bdd0340 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.313  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bdd0340 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.313  1035  7333 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.313  1035  7333 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 15:30:36.313  1035  1432 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 15:30:36.314  1035  1432 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 15:30:36.314  1035  1432 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 15:30:36.315   310   893 D CommandListener: Setting iface cfg
09-07 15:30:36.316   310   893 D CommandListener: Trying to bring up wlan0
09-07 15:30:36.317  1035  1432 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 15:30:36.317  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:36.318  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 15:30:36.319  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:36.319  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 15:30:36.319  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-07 15:30:36.319  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-07 15:30:36.320  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.320  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.320  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 15:30:36.320  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 15:30:36.320  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 15:30:36.320  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 15:30:36.321  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 15:30:36.321  1035  1432 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 15:30:36.321  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
,09-07 15:30:36.339  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
,09-07 15:30:36.341  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 15:30:36.342  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:36.342  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:36.343  1035  1432 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:36.343  1035  1432 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:36.344  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:36.344  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:36.345  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 15:30:36.345  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 15:30:36.346  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 15:30:36.346  1035  1432 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 15:30:36.347  1035  1481 D ConnectivityService: ignoring duplicate network state non-change
09-07 15:30:36.351  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.351  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:36.352  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:36.357  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.357  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.357  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 15:30:36.359  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 15:30:36.360  1035  1481 D ConnectivityService: Adding iface wlan0 to network 101
09-07 15:30:36.361  1035  1432 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 15:30:36.361  7334  7334 D WeatherApplication: removeAccount
09-07 15:30:36.363  7334  7334 D WeatherApplication: Account.length = 0
09-07 15:30:36.363  7334  7334 E WeatherApplication: OPERATOR:OPEN
09-07 15:30:36.370  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.370  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.370  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 15:30:36.371  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 15:30:36.374  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-07 15:30:36.375  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:36.375  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.375  7334  7334 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:36
09-07 15:30:36.375  1035  1390 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.377  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.378  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.378  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 15:30:36.379  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 15:30:36.380  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.380  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:36.381  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.384  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.384  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 15:30:36.384  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.384  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.384  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:36.384  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 15:30:36.388  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:36.388  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 15:30:36.388  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:36.392  7334  7334 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 15:30:36.393  7334  7334 D Weather.Utils: 2 : All the weather widget is gone.
09-07 15:30:36.394  7334  7334 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 15:30:36.396  7334  7334 D WeatherAncestor: connectivity changed - connection : true
09-07 15:30:36.397  7334  7334 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-07 15:30:36.397  1035  1481 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 15:30:36.397  1035  1481 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-07 15:30:36.398  1035  1432 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 15:30:36.399  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 15:30:36.399  1035  1432 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 15:30:36.399  1035  1432 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 15:30:36.400  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 15:30:36.400  1035  1432 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 15:30:36.401  1035  1481 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 15:30:36.402   310   893 E Netd    : netlink response contains error (File exists)
09-07 15:30:36.402  1035  1481 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-07 15:30:36.402  7334  7334 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 15:30:36.403  7334  7334 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 15:30:36.403  7334  7334 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-07 15:30:36.403  1035  1481 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 15:30:36.403  1035  1481 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-07 15:30:36.403  1035  1481 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-07 15:30:36.405  1035  1481 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 15:30:36.405  1035  1481 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 15:30:36.405  1035  1481 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 15:30:36.405  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.405  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 15:30:36.405  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:36.406  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 15:30:36.408  1035  1481 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,09-07 15:30:36.408  1035  1481 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:36.408  1035  1481 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:36.408  1035  1481 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 15:30:36.408  1035  1481 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.409  1035  1481 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 15:30:36.409  1035  1481 D ConnectivityService: currentScore = 0, newScore = 20
09-07 15:30:36.409  1035  1481 D ConnectivityService:    accepting network in place of null
09-07 15:30:36.409  1035  1481 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.410  1035  1432 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 15:30:36.410  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.410   310  7355 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 15:30:36.410  1035  1432 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:36.411  1035  1481 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 15:30:36.411  1035  1481 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 15:30:36.411  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 15:30:36.411  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:30:36.412  1035  1481 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:36.412  1035  1481 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 15:30:36.412  1035  1481 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 15:30:36.413  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 15:30:36.413  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 15:30:36.413  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 15:30:36.413  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-07 15:30:36.416  1035  1481 D ConnectivityService: validation of new default Network = false
09-07 15:30:36.416  1035  1481 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 15:30:36.416  1035  1481 D DSQN    : enableDataServiceNotify 
09-07 15:30:36.416  1035  1481 D DSQN    : start dsqn bin
,09-07 15:30:36.422  1035  1481 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 15:30:36.422  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.422  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:36.422  1035  1481 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-07 15:30:36.422  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 15:30:36.408  7356  7356 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:36.408  7356  7356 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:36.429  7334  7334 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 15:30:36.429  7334  7334 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:36
,09-07 15:30:36.436  7356  7356 E DSQN    : DSQN ssw
09-07 15:30:36.455  1035  1575 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7361 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 15:30:36.456  1035  1575 I ActivityManager: Killing 6594:com.android.vending/u0a44 (adj 15): empty #17
,09-07 15:30:36.472   310  7355 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-07 15:30:36.486  1035  1762 W libprocessgroup: failed to open /acct/uid_10044/pid_6594/cgroup.procs: No such file or directory
,09-07 15:30:36.487  1816  7357 I CheckinService: active receiver: enabled
09-07 15:30:36.499  1816  7357 I CheckinService: Preparing to send checkin request
09-07 15:30:36.499  1816  7357 I EventLogService: Accumulating logs since 1473254901733
,09-07 15:30:36.502  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-07 15:30:36.506   310  7355 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-07 15:30:36.515  1035  7333 D DhcpStateMachine: DHCPV4 request on wlan0
,09-07 15:30:36.516  1035  7333 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 15:30:36.516  1035  7333 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 15:30:36.516  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:36.518  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.518  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.508  7379  7379 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:36.508  7379  7379 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:36.526  7379  7379 I dhcpcd  : version 5.5.6 starting
,09-07 15:30:36.529  7379  7379 E dhcpcd  : get_duid: m
09-07 15:30:36.529  7379  7379 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 15:30:36.529  7379  7379 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-07 15:30:36.531   310   892 D LGDataListener: argv[0]=dsqncommand
09-07 15:30:36.531   310   892 D LGDataListener: argv[1]=wlan0
09-07 15:30:36.531   310   892 D LGDataListener: argv[2]=1
09-07 15:30:36.531   310   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-07 15:30:36.531  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 15:30:36.531  1035  1115 D DSQN    : start to monitor internet connection
09-07 15:30:36.537  1816  7357 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 15:30:36.557  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 13:30:36 GMT], X-Android-Received-Millis=[1473255036557], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473255036530]}
09-07 15:30:36.557  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 15:30:36.557  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 15:30:36.558  1035  1481 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-07 15:30:36.558  1035  1481 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 15:30:36.558  1035  1481 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:36.558  1035  1481 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:36.558  1035  1481 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 15:30:36.558  1035  1481 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-07 15:30:36.558  1035  1481 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 15:30:36.558  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.558  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:36.559  1035  1481 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:36.559  1035  1481 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.559  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 15:30:36.559  1035  1432 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.559  1035  1432 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:36.559  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:36.559  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 15:30:36.565  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 15:30:36.578  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-07 15:30:36.579  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:36.579  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:36.581  7379  7379 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 15:30:36.581  7379  7379 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 15:30:36.581  7379  7379 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 15:30:36.581  7379  7379 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-07 15:30:36.581  7379  7379 D dhcpcd  : wlan0: sending REQUEST (xid 0x825fb3a2), next in 3.95 seconds
,09-07 15:30:36.594   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-07 15:30:36.595   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 15:30:36.595   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 15:30:36.595  7361  7389 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-07 15:30:36.596   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 15:30:36.596   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 15:30:36.596   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 15:30:36.597  7361  7389 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-07 15:30:36.606  7379  7379 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-07 15:30:36.606   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 15:30:36.606   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 15:30:36.606   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 15:30:36.606  7361  7392 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-07 15:30:36.607   278   404 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 15:30:36.607   278   404 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 15:30:36.607   278   404 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 15:30:36.608  7361  7392 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-07 15:30:36.628  7379  7379 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 15:30:36.628  7379  7379 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 15:30:36.628  7379  7379 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 15:30:36.628  7379  7379 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 15:30:36.629  7379  7379 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 15:30:36.629  7379  7379 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 15:30:36.629  7379  7379 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 15:30:36.629  7379  7379 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-07 15:30:36.638  1035  1575 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7394 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-07 15:30:36.690  7394  7394 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-07 15:30:36.691  7394  7394 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-07 15:30:36.723  7394  7394 I MultiDex: VM with version 2.1.0 has multidex support
09-07 15:30:36.723  7394  7394 I MultiDex: install
09-07 15:30:36.723  7394  7394 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 15:30:36.732  7394  7394 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-07 15:30:36.794  7361  7361 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 15:30:36.800  7361  7361 I LibraryLoader: Loading: webviewchromium
09-07 15:30:36.802  7361  7361 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8274-8277)
09-07 15:30:36.802  7361  7361 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 15:30:36.817  7361  7361 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32fa154e}
09-07 15:30:36.819  7361  7361 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 15:30:36.819  7361  7361 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 15:30:36.832  7361  7361 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 15:30:36.833  7361  7361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 15:30:36.847  7361  7361 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-07 15:30:36.849  7361  7361 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-07 15:30:36.849  7361  7361 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-07 15:30:36.863   315  2157 V AudioPolicyService: registerClient() client 0xb558a960, uid 10093
,09-07 15:30:36.865  7361  7453 W AudioManagerAndroid: Requires BLUETOOTH permission
09-07 15:30:36.866  7361  7361 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 15:30:36.866  7361  7361 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 15:30:36.866  7361  7361 I Adreno-EGL: Build Date: 12/12/14 금
09-07 15:30:36.866  7361  7361 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 15:30:36.866  7361  7361 I Adreno-EGL: Remote Branch: 
09-07 15:30:36.866  7361  7361 I Adreno-EGL: Local Patches: 
09-07 15:30:36.866  7361  7361 I Adreno-EGL: Reconstruct Branch: 
09-07 15:30:36.918  1035  7333 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-07 15:30:36.919  1035  7333 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 15:30:36.919  1035  7333 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 15:30:36.919  1035  7333 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 15:30:36.919  1035  7333 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,09-07 15:30:36.919  1035  7333 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 15:30:36.919  1035  7333 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 15:30:36.919  1035  7333 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 15:30:36.920  1035  7333 D DhcpStateMachine: RunningState
09-07 15:30:36.942  7361  7361 I NSApplication: Starting up...
,09-07 15:30:36.989  1035  1778 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7466 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-07 15:30:36.989  1035  1778 I ActivityManager: Killing 6842:com.lge.clock/u0a10 (adj 15): empty #17
09-07 15:30:37.039  1035  1921 W libprocessgroup: failed to open /acct/uid_10010/pid_6842/cgroup.procs: No such file or directory
,09-07 15:30:37.075  7466  7466 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:30:37.224  7488  7488 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-07 15:30:37.283  7488  7488 I dex2oat : dex2oat took 58.293ms (threads: 4)
,09-07 15:30:37.299  7394  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 15:30:37.299  7394  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 15:30:37.299  7394  7412 I Adreno-EGL: Build Date: 12/12/14 금
09-07 15:30:37.299  7394  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 15:30:37.299  7394  7412 I Adreno-EGL: Remote Branch: 
09-07 15:30:37.299  7394  7412 I Adreno-EGL: Local Patches: 
09-07 15:30:37.299  7394  7412 I Adreno-EGL: Reconstruct Branch: 
,09-07 15:30:37.327  1035  1938 D WifiServiceImplEx: setWifiEnabled: false pid=6904, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-07 15:30:37.327  1035  1938 D WifiService: setWifiEnabled: false pid=6904, uid=10118
09-07 15:30:37.327  1035  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 15:30:37.347  1035  1432 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:37.347  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:37.348  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:37.348  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:37.348  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:37.348  1035  1432 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:37.348  1035  1432 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:37.349  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 15:30:37.349  1035  1432 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 15:30:37.349  1035  1432 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:30:37.349  1035  1432 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-07 15:30:37.350  1035  1432 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 15:30:37.350  1035  1432 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 15:30:37.361  1035  1432 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 15:30:37.361  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 15:30:37.361  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 15:30:37.362  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.362  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:37.362  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 15:30:37.362  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 15:30:37.362  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
09-07 15:30:37.363   310   893 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:30:37.363  1035  7333 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.382  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 15:30:37.384  6465  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 15:30:37.392  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 15:30:37.392  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-07 15:30:37.406  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:37.412  2210  2210 W GCM     : ACTIVE NETWORK NOT CONNECTED
09-07 15:30:37.426  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:37.426  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 15:30:37.426  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-07 15:30:37.431  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.431  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.431  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:37.433  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-07 15:30:37.436  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.436  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.436  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:37.436  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 15:30:37.435  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 15:30:37.436  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.437  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-07 15:30:37.437  1035  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.438  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.440  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:37.440  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:37.442  1035  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.442  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.442  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f78127d
09-07 15:30:37.443  1035  1390 D LGWifiP2pService: P2pDisablingState
09-07 15:30:37.443  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.443  1035  1390 D LGWifiP2pService: p2p socket connection lost
09-07 15:30:37.443  1035  1390 D LGWifiP2pService: P2pDisabledState
09-07 15:30:37.444  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:37.444  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:37.445  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:37.445  1035  1432 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 15:30:37.449  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 15:30:37.449  1940  1940 D WfdsService: WifiP2pState is changed : false
09-07 15:30:37.450  1940  2330 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 15:30:37.450  1940  2330 D WfdsService: Set the WFDS Monitor: false
09-07 15:30:37.450  1940  2330 D WfdsMonitor: WFDS Monitor is stopped
09-07 15:30:37.450  1940  2330 D WfdsService: STATE : WfdsDisabledState - enter
09-07 15:30:37.451  1940  7263 D CtrlSupplicant: Received on exit socket, terminate
09-07 15:30:37.451  1940  7263 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 15:30:37.451  1940  7263 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 15:30:37.451  1940  7263 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 15:30:37.451  1940  2336 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 15:30:37.451  1940  2330 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 15:30:37.453  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.457  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:37.457  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:37.457  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:37.458  1035  1432 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 15:30:37.459  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.459  1035  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.459  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 15:30:37.461  7251  7251 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 15:30:37.461  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 15:30:37.461  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 15:30:37.461  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
,09-07 15:30:37.465  1035  1762 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-07 15:30:37.465  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.465  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.465  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-07 15:30:37.466  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.466  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-07 15:30:37.468  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 15:30:37.468  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:37.468  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 15:30:37.468  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 15:30:37.474  7198  7198 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 15:30:37.480   310   893 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:30:37.481   310  7512 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 15:30:37.481  1035  1432 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 15:30:37.481  7198  7198 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34860687
09-07 15:30:37.481  1035  1481 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 15:30:37.482  1035  1481 D DSQN    : disableDataServiceNotify
09-07 15:30:37.482  1035  1115 D DSQN    : Dns fail occured do internet check.
09-07 15:30:37.482  1035  1481 D DSQN    : stop dsqn bin
09-07 15:30:37.482  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-07 15:30:37.482  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-07 15:30:37.482  1035  1035 D DSQN    : try Internet connection check
09-07 15:30:37.482  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 15:30:37.482  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:37.482  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.483  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.483  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:37.483  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
09-07 15:30:37.483  1035  1432 D WifiNative-p2p0: TERMINATE: returned true
09-07 15:30:37.483  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:37.483  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:37.483  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:37.481  7198  7198 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 15:30:37.483  7198  7198 D AppUp4:CustFacade: isPhone : true
09-07 15:30:37.485  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 15:30:37.485  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 15:30:37.485  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.486  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:37.486  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-07 15:30:37.488   310  7515 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 15:30:37.489  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 15:30:37.489  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:37.489  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:37.489  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:37.489  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:37.490  1035  7514 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
09-07 15:30:37.490  1035  7513 D DSQN    : ThreadInternetCheck internet check NOK 
09-07 15:30:37.490  1035  7513 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
09-07 15:30:37.490  1035  7513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
09-07 15:30:37.491  1035  1481 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-07 15:30:37.491  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.491  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:37.491  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:37.491  1035  1481 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:37.491  1035  1481 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 15:30:37.491  1035  1481 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 15:30:37.491  1035  1481 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo, [WIFI () - 101] isDefaultNetwork=true
09-07 15:30:37.491  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:30:37.491  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:37.491  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:37.491  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:37.491  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:37.492  1035  1481 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:37.492  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:30:37.492  1035  1481 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:37.492  1035  1481 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:37.492  1035  1481 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:37.492  1035  1481 D NetworkManagementService: Removing idletimer
09-07 15:30:37.492  1035  1481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.492  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 15:30:37.492  7198  7198 D AppUp4:CustModeStarterReceiver: begin check event
09-07 15:30:37.493  7198  7198 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 15:30:37.493  1035  1481 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-07 15:30:37.493  1035  1481 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 15:30:37.493  1035  1035 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
09-07 15:30:37.493  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.493  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:37.493  1035  7331 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 15:30:37.495  1035  1432 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 ,15:30:37.495  1035  1432 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:37.496  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 15:30:37.496  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:37.496  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 15:30:37.499  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 15:30:37.506  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:37.506  1940  2796 D WifiServiceExtension: isInternetCheckAvailable return false
09-07 15:30:37.506  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:37.507  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 15:30:37.507  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:37.507  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 15:30:37.507  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 15:30:37.507  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 15:30:37.507  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 15:30:37.507  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 15:30:37.507  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 15:30:37.507  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 15:30:37.512  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:37.524  7233  7233 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 15:30:37.525  4749  7516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 15:30:37.532  7394  7412 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:37.532  7394  7412 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 15:30:37.537  4749  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:37.537  4749  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 15:30:37.550  7113  7520 W FormManager: Network not available. Please check & try again.
09-07 15:30:37.553  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:37.553  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.554  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.554  3237  3237 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 15:30:37.554  3237  3237 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:37.554  3237  3237 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 15:30:37.557  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 15:30:37.557  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 15:30:37.558  7233  7518 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.563  7113  7521 V FormManager: Network unavailable.
09-07 15:30:37.566  7334  7334 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:37
09-07 15:30:37.566  7251  7251 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 15:30:37.566  7251  7251 I wpa_supplicant: monitor socket send errors count : 1
,09-07 15:30:37.566  7251  7251 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
09-07 15:30:37.567  1035  7260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 15:30:37.567  1035  7260 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 15:30:37.568  7113  7521 V FormManager: Network unavailable.
09-07 15:30:37.570  7334  7334 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 15:30:37.570  7334  7334 D Weather.Utils: 2 : All the weather widget is gone.
09-07 15:30:37.570  7334  7334 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 15:30:37.570  7334  7334 D WeatherAncestor: connectivity changed - connection : true
09-07 15:30:37.570  7334  7334 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e2ff9dd
09-07 15:30:37.571  7334  7334 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 15:30:37.571  7334  7334 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 15:30:37.571  7334  7334 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 15:30:37.571  7334  7334 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 15:30:37.571  7334  7334 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:37
09-07 15:30:37.581  1035  7333 D DhcpStateMachine: StoppedState
09-07 15:30:37.581  1035  7333 D DhcpStateMachine: StoppedState{ when=-120ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:37.585  7394  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 15:30:37.585  7394  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 15:30:37.585  7394  7412 I Adreno-EGL: Build Date: 12/12/14 금
09-07 15:30:37.585  7394  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 15:30:37.585  7394  7412 I Adreno-EGL: Remote Branch: 
09-07 15:30:37.585  7394  7412 I Adreno-EGL: Local Patches: 
09-07 15:30:37.585  7394  7412 I Adreno-EGL: Reconstruct Branch: 
09-07 15:30:37.585  1035  1432 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 15:30:37.586  1035  1432 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-07 15:30:37.588  7251  7251 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:30:37.588  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-07 15:30:37.588  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:30:37.588  1035  7260 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:30:37.588  1035  7260 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 15:30:37.588  7251  7251 W wpa_supplicant: USIM:  scard_deinit function
09-07 15:30:37.589  1035  1117 D Tethering: InitialState.processMessage what=4
09-07 15:30:37.589  1035  1432 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179052
09-07 15:30:37.590  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:30:37.590  1035  1432 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179052
09-07 15:30:37.590  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:37.590  1035  1432 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:37.590  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:37.591  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.591  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:37.591  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:37.591  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.591  1035  1432 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=179054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 15:30:37.592  1035  1432 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=179054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-07 15:30:37.602  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 15:30:37.602  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 15:30:37.602  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 15:30:37.602  7023  7023 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 15:30:37.602  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 15:30:37.606  7023  7023 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 15:30:37.606  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 15:30:37.606  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 15:30:37.606  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 15:30:37.606  7023  7023 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,09-07 15:30:37.607  7023  7023 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 15:30:37.612  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:37.615  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 15:30:37.617  7113  7531 W FormManager: Network not available. Please check & try again.
,09-07 15:30:37.620  7113  7532 V FormManager: Network unavailable.
,09-07 15:30:37.622  7113  7532 V FormManager: Network unavailable.
09-07 15:30:37.622  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:37.643  7394  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 15:30:37.643  7394  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 15:30:37.643  7394  7412 I Adreno-EGL: Build Date: 12/12/14 금
09-07 15:30:37.643  7394  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 15:30:37.643  7394  7412 I Adreno-EGL: Remote Branch: 
09-07 15:30:37.643  7394  7412 I Adreno-EGL: Local Patches: 
09-07 15:30:37.643  7394  7412 I Adreno-EGL: Reconstruct Branch: 
09-07 15:30:37.644  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 15:30:37.647  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:30:37.652  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:37.657  7113  7534 W FormManager: Network not available. Please check & try again.
,09-07 15:30:37.661  7113  7535 V FormManager: Network unavailable.
09-07 15:30:37.665  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:37.666  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:37.666  7113  7535 V FormManager: Network unavailable.
09-07 15:30:37.667  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:37.669  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:37.672  4749  7536 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 15:30:37.675  4749  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:37.675  4749  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 15:30:37.686  7251  7251 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 15:30:37.689  1035  7260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 15:30:37.689  1035  7260 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 15:30:37.689  1035  7260 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 15:30:37.690  1035  1432 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-07 15:30:37.707  1035  1889 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7538 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-07 15:30:37.709  1035  1432 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 15:30:37.710  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:37.710  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:37.710  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:37.710  1940  1940 D WfdsService: Supplicant Connection state is changed : false
09-07 15:30:37.710  1940  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 15:30:37.710  1940  2330 D WfdsService: Set the WFDS Monitor: false
09-07 15:30:37.711  1940  2330 D WfdsMonitor: WFDS Monitor is stopped
09-07 15:30:37.712  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:37.712  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 15:30:37.712  1035  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 15:30:37.712  1035  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 15:30:37.713  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 15:30:37.713  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:37.713  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:37.713  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:37.713  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:30:37.771   310  7556 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 15:30:37.772  1816  7357 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-07 15:30:37.772  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 15:30:37.776  1816  7357 I CheckinService: active receiver: disabled
,09-07 15:30:37.788  7538  7538 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 15:30:37.788  7538  7538 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-07 15:30:37.793  7538  7538 V [BNRBootReceiver]: Boot Receiver Return
09-07 15:30:37.793  7538  7538 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 15:30:37.796  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:37.804  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:37.810  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:37.821  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:37.821  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:37.822  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 15:30:37.828  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-07 15:30:37.832  7023  7023 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 15:30:37.838  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:37.845  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:37.854  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:37.867  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:37.867  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:37.869  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 15:30:37.873  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:37.879  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:37.887  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:37.896  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 15:30:37.897  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:37.898  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 15:30:37.901  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:37.912  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:37.920  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:37.934  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:37.935  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:37.936  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 15:30:37.941  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:37.957  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:37.968  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:37.982  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 15:30:37.983  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:37.984  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:37.992  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:38.010  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.020  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.033  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 15:30:38.034  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:38.035  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:38.039  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:38.058  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.077  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:38.094  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 15:30:38.095  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:38.097  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:38.113  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:38.142  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.151  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:38.164  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.164  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:38.173  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:38.178  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:38.190  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.200  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.209  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.210  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:38.212  7072  7072 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:38.224  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:38.232  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 15:30:38.245  1035  1471 D WifiService: New client listening to asynchronous messages
,09-07 15:30:38.246  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:38.253  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.260  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.264  6769  7179 D UEI.SmartControl: Internal timer expired: 2
09-07 15:30:38.264  6769  7179 D UEI.SmartControl: unbind internal service
09-07 15:30:38.274  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.275  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:38.278  7072  7072 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 15:30:38.280  7072  7072 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 15:30:38.281  7072  7072 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 15:30:38.292  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:38.307  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 15:30:38.310  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:38.319  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.329  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.341  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.341  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:38.342  7072  7072 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 15:30:38.343  7072  7072 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 15:30:38.343  7072  7072 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 15:30:38.346  1035  1050 I ActivityManager: Killing 6997:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-07 15:30:38.353  6769  7173 D serial_port: close(fd = 24)
09-07 15:30:38.356  6769  7173 I UEI.SmartControl: Serial port is closed.
,09-07 15:30:38.393  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-07 15:30:38.406  1035  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_6997/cgroup.procs: No such file or directory
09-07 15:30:38.421  2210  2210 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-07 15:30:38.423  2210  2210 D c       : Getting all permits...
09-07 15:30:38.423  2210  2210 D a       : Opening database...
09-07 15:30:38.427  2210  2210 D a       : Opening database auth.proximity.permit_store...
09-07 15:30:38.428  2210  2210 D a       : Closing database...
09-07 15:30:38.449  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:38.456  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 15:30:38.457  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 15:30:38.457  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:38.462  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.468  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.475  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.475  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:38.477  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 15:30:38.483  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:38.488  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-07 15:30:38.488  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-07 15:30:38.488  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:38.491  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
09-07 15:30:38.492  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:38.499  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.506  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.506  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:38.508  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 15:30:38.512  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:38.515  7044  7044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 15:30:38.516  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 15:30:38.516  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:38.520  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:38.529  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:38.538  7072  7072 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:38.538  7072  7072 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:38.540  7072  7072 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 15:30:38.555  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 15:30:38.560  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 15:30:38.570  7113  7565 W FormManager: Network not available. Please check & try again.
,09-07 15:30:38.571  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.581  7113  7566 V FormManager: Network unavailable.
09-07 15:30:38.584  7113  7566 V FormManager: Network unavailable.
,09-07 15:30:38.590  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:38.591  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:38.594  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:38.597  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:38.602  4749  7567 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 15:30:38.608  7044  7044 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 15:30:38.608  7044  7044 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 15:30:38.608  7044  7044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:38.612  4749  7568 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:38.612  4749  7568 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 15:30:38.615  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 15:30:38.619  7113  7570 W FormManager: Network not available. Please check & try again.
,09-07 15:30:38.621  7113  7571 V FormManager: Network unavailable.
,09-07 15:30:38.624  7113  7571 V FormManager: Network unavailable.
09-07 15:30:38.626  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:38.644  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 15:30:39.307  1035  1432 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:81256779] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 15:30:39.308  1035  1432 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:81256780] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 15:30:39.414  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:39.429  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:30:39.437  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:39.440  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:39.445  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:39.451  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 15:30:39.456  6465  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 15:30:39.469  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 15:30:39.492  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:39.521  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 15:30:39.521  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:39.521  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 15:30:39.521  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-07 15:30:39.529  7198  7198 I AppUp4:CustModeStarterReceiver: onReceive
09-07 15:30:39.533  7198  7198 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34860687
09-07 15:30:39.533  7198  7198 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 15:30:39.533  7198  7198 D AppUp4:CustFacade: isPhone : true
09-07 15:30:39.533  7198  7198 D AppUp4:CustModeStarterReceiver: begin check event
09-07 15:30:39.533  7198  7198 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 15:30:39.539  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:39.539  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:39.541  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 15:30:39.551  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:39.562  7233  7233 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 15:30:39.581  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 15:30:39.587  4749  7590 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 15:30:39.595  4749  7592 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:39.595  4749  7592 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 15:30:39.606  7233  7593 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 15:30:39.612  7113  7597 W FormManager: Network not available. Please check & try again.
09-07 15:30:39.617  3237  3237 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 15:30:39.617  3237  3237 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:39.618  3237  3237 I LgeMiscReceiver: networkInfo.isConnected() = true
09-07 15:30:39.618  3237  3237 D PhoneState: setPdpRejectCasuse : false
09-07 15:30:39.621  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-07 15:30:39.621  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-07 15:30:39.631  7113  7598 V FormManager: Network unavailable.
,09-07 15:30:39.634  7334  7334 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:39
,09-07 15:30:39.636  7334  7334 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 15:30:39.636  7334  7334 D Weather.Utils: 2 : All the weather widget is gone.
09-07 15:30:39.637  7334  7334 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 15:30:39.637  7334  7334 D WeatherAncestor: connectivity changed - connection : true
09-07 15:30:39.637  7334  7334 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e2ff9dd
09-07 15:30:39.637  7113  7598 V FormManager: Network unavailable.
09-07 15:30:39.638  7334  7334 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 15:30:39.638  7334  7334 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 15:30:39.638  7334  7334 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 15:30:39.638  7334  7334 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 15:30:39.638  7334  7334 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:39
09-07 15:30:40.349  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 15:30:40.354  1035  2031 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 15:30:40.388  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:40.388  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:40.388  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:40.389  1035  1117 D BluetoothManagerService: Message: 1
09-07 15:30:40.389  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 15:30:40.416  1035  1117 D BluetoothManagerService: Message: 20
,09-07 15:30:40.429  7130  7130 D BluetoothAdapterState: make
09-07 15:30:40.438  7130  7130 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 15:30:40.438  7130  7130 I bluedroid-qcom: init
,09-07 15:30:40.443  7130  7610 I BluetoothAdapterState: Entering OffState
09-07 15:30:40.443  7130  7130 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 15:30:40.443  7130  7130 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 15:30:40.443  7130  7130 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 15:30:40.443  7130  7130 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 15:30:40.443  7130  7130 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 15:30:40.445  7130  7130 I bluedroid-qcom: get_profile_interface socket
09-07 15:30:40.445  7130  7130 I bluedroid-qcom: get_profile_interface map_client
09-07 15:30:40.447  7130  7614 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 15:30:40.449  7130  7614 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 15:30:40.438  7613  7613 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:40.438  7613  7613 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 15:30:40.462  7613  7613 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 15:30:40.462  7613  7613 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 15:30:40.462  7613  7613 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-07 15:30:40.466  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 15:30:40.466  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-07 15:30:40.470  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 15:30:40.470  7130  7614 D BluetoothAdapterProperties: Name is: G3
09-07 15:30:40.476  7613  7613 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-07 15:30:40.492  7613  7613 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 15:30:40.492  7613  7613 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-07 15:30:40.496  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.501  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.506  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:40.510  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:40.511  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.544  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:40.548  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:40.550  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 15:30:40.552  6465  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 15:30:40.553  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 15:30:40.563  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 15:30:40.566  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.568  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:40.568  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:40.579  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:40.593  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 15:30:40.593  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.593  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 15:30:40.593  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-07 15:30:40.598  7198  7198 I AppUp4:CustModeStarterReceiver: onReceive
09-07 15:30:40.602  7198  7198 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34860687
09-07 15:30:40.602  7198  7198 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 15:30:40.602  7198  7198 D AppUp4:CustFacade: isPhone : true
09-07 15:30:40.602  7198  7198 D AppUp4:CustModeStarterReceiver: begin check event
09-07 15:30:40.602  7198  7198 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 15:30:40.606  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.606  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:40.607  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 15:30:40.610  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:40.618  7233  7233 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 15:30:40.622  4749  7631 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 15:30:40.623  4749  7632 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.623  4749  7632 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 15:30:40.634  7233  7634 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:40.642  3237  3237 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 15:30:40.642  3237  3237 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.642  3237  3237 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 15:30:40.649  7113  7636 W FormManager: Network not available. Please check & try again.
09-07 15:30:40.650  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-07 15:30:40.650  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 15:30:40.657  7113  7638 V FormManager: Network unavailable.
09-07 15:30:40.659  7334  7334 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:40
,09-07 15:30:40.661  7334  7334 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 15:30:40.661  7334  7334 D Weather.Utils: 2 : All the weather widget is gone.
09-07 15:30:40.661  7334  7334 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 15:30:40.661  7113  7638 V FormManager: Network unavailable.
09-07 15:30:40.661  7334  7334 D WeatherAncestor: connectivity changed - connection : true
09-07 15:30:40.661  7334  7334 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e2ff9dd
09-07 15:30:40.662  7334  7334 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 15:30:40.662  7334  7334 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 15:30:40.662  7334  7334 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 15:30:40.662  7334  7334 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 15:30:40.662  7334  7334 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:40
09-07 15:30:40.680  1035  1117 I art     : Explicit concurrent mark sweep GC freed 131279(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.212ms total 259.975ms
09-07 15:30:40.680  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b7ce673:true
09-07 15:30:40.680  1035  1117 D BluetoothManagerService: Message: 40
09-07 15:30:40.680  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 15:30:40.680  6465  6465 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-07 15:30:40.682  7130  7146 I bluedroid-qcom: config_hci_snoop_log
09-07 15:30:40.683  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 15:30:40.684  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 15:30:40.684  6465  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 15:30:40.690  7130  7610 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 15:30:40.690  7130  7610 D BluetoothAdapterProperties: Setting state to 11
09-07 15:30:40.690  7130  7610 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 15:30:40.691  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:30:40.691  7130  7610 I LGBluetoothServiceJni: classInitNative: succeeds
09-07 15:30:40.691  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 15:30:40.691  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:40.691  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 15:30:40.692  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-07 15:30:40.693  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:40.693  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:40.696  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-07 15:30:40.700  7130  7610 D BluetoothBondStateMachine: make
09-07 15:30:40.702  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:40.703  7130  7130 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:40.703  7130  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:40.703  7130  7610 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 15:30:40.703  7130  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:40.703  7130  7610 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 15:30:40.703  7130  7610 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 15:30:40.704  7130  7130 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:40.704  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:40.704  7130  7130 V BluetoothPbapReceiver: ***********state = 11
09-07 15:30:40.705  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:30:40.709  7130  7641 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 15:30:40.712  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.714  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 15:30:40.714  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.714  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 15:30:40.714  7198  7198 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 15:30:40.717  7198  7198 I AppUp4:CustModeStarterReceiver: onReceive
09-07 15:30:40.718  7130  7130 D HeadsetService: Received start request. Starting profile...
09-07 15:30:40.718  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:30:40.719  7130  7130 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 15:30:40.719  7130  7130 D LGBluetoothHfpAdapter: Version 1.6
09-07 15:30:40.719  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.721  7130  7130 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 15:30:40.722  7130  7130 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 15:30:40.723  7130  7130 D HeadsetStateMachine: make
09-07 15:30:40.724  7198  7198 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34860687
09-07 15:30:40.724  7198  7198 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 15:30:40.724  7198  7198 D AppUp4:CustFacade: isPhone : true
09-07 15:30:40.724  7198  7198 D AppUp4:CustModeStarterReceiver: begin check event
09-07 15:30:40.724  7198  7198 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 15:30:40.750  7130  7130 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:40.750  7130  7130 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:40.765  1035  1650 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7643 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-07 15:30:40.777   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 422us total 21.809ms
,09-07 15:30:40.777  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.777  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 15:30:40.778  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:40.784  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.786  7130  7130 D HeadsetStateMachine: max_hf_connections = 1
09-07 15:30:40.787  7130  7130 I bluedroid-qcom: get_profile_interface handsfree
09-07 15:30:40.788  7130  7130 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-07 15:30:40.791   315  1396 V AudioPolicyService: registerClient() client 0xb558adc0, uid 1002
09-07 15:30:40.791   315   315 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 15:30:40.791   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 15:30:40.791   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
,09-07 15:30:40.792  7130  7130 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 15:30:40.792   315  2157 V AudioFlinger: registerClient() client 0xb14330a0, pid 7130
09-07 15:30:40.792   315  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:40.793   315  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:40.793  7130  7130 V ToneGenerator: Create Track: 0xb4928a80
09-07 15:30:40.793  7130  7130 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 15:30:40.793  7130  7130 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 15:30:40.793   315  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 15:30:40.793   315  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 15:30:40.793   315  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 15:30:40.793   315  2157 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 15:30:40.794  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.794  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:40.794  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:40.794  3237  3256 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:40.794  3237  3256 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:40.794  1035  1993 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:40.794  1035  1993 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:40.794  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:40.794  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:40.794  7130  7146 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:40.794  7130  7146 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 15:30:40.794   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:40.794   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:40.795  7130  7145 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:40.795  7130  7145 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 15:30:40.795  3237  3255 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:40.795  1035  1762 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:40.795  1035  1762 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:40.795  3237  3255 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:40.795  1602  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:40.795  1602  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:40.795  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:40.795  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:40.796   315   315 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 15:30:40.796   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 18.485ms
09-07 15:30:40.796   315  2156 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 15:30:40.796   315  2156 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 15:30:40.796   315  2156 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 15:30:40.796   315  2156 V AudioPolicyManagerEx: getOutput() r,eturns output 2
09-07 15:30:40.796  7130  7130 V AudioSystem: getLatency() output 2, latency 50
09-07 15:30:40.796  7130  7130 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 15:30:40.796  7130  7130 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 15:30:40.796   315  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 15:30:40.796   315  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 15:30:40.796   315  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 15:30:40.797   315  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 15:30:40.797   315  2157 V AudioFlinger: createTrack() lSessionId: 20
09-07 15:30:40.798  7130  7130 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 15:30:40.798   315  2157 V AudioFlinger: acquiring 20 from 7130, for 7130
09-07 15:30:40.798   315  2157 V AudioFlinger:  added new entry for 20
09-07 15:30:40.798  7130  7130 V ToneGenerator: ToneGenerator INIT OK, time: 182273
09-07 15:30:40.798  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:40.799  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:40.800  7130  7642 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 15:30:40.800  7130  7642 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 15:30:40.800  7130  7642 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 15:30:40.800  7130  7642 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 15:30:40.800   315  1396 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7130
09-07 15:30:40.801   315  1396 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 15:30:40.801   315  1396 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 15:30:40.801   315  1396 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 15:30:40.801   315  1396 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 15:30:40.801   315  1396 V voice   : voice_set_parameters: exit with code(0)
09-07 15:30:40.801   315  1396 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 15:30:40.801   315  1396 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 15:30:40.801   315  1396 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 15:30:40.801   315  1396 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 15:30:40.801   315  1396 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 15:30:40.801   315  1396 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 15:30:40.801  7130  7642 V ToneGenerator: ToneGenerator destructor
09-07 15:30:40.801  7130  7642 V ToneGenerator: stopTone
09-07 15:30:40.801  7130  7642 V ToneGenerator: Delete Track: 0xb4928a80
09-07 15:30:40.802  7130  7642 V AudioTrack: ~AudioTrack, releasing session id from 7130 on behalf of 7130
09-07 15:30:40.802   315  1397 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 15:30:40.802   315   315 V AudioFlinger: releasing 20 from 7130 for 7130
09-07 15:30:40.802   315   315 V AudioFlinger:  decremented refcount to 0
09-07 15:30:40.802   315  1397 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 15:30:40.802   315   315 V AudioFlinger: purging stale effects
09-07 15:30:40.802   315  1269 V AudioPolicyService: AudioCommandThread() waking up
09-07 15:30:40.802   315  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 15:30:40.802   315  1269 V AudioPolicyManager: releaseOutput() 2
09-07 15:30:40.802   315  1269 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 15:30:40.802   315  1397 V AudioFlinger: PlaybackThread::Track destructor
09-07 15:30:40.802   315  1397 V AudioFlinger: removeClient_l() pid 7130, calling pid 315
09-07 15:30:40.805  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:40.805  1035  2031 W Process : Unable to open /proc/7661/status
09-07 15:30:40.807  7130  7130 D A2dpService: Received start request. Starting profile...
09-07 15:30:40.808  7130  7130 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 15:30:40.808  7130  7130 V Avrcp   : make
09-07 15:30:40.809  7130  7130 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 15:30:40.809  7130  7130 I bluedroid-qcom: get_profile_interface avrcp
09-07 15:30:40.813  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.815   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.636ms
09-07 15:30:40.826  7130  7130 V AudioManager: registerRemoteController: size of Media player list: 0
09-07 15:30:40.827  7130  7130 E AudioManager: No RCC entry present to update
09-07 15:30:40.827  7130  7130 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 15:30:40.828  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.830  7130  7130 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 15:30:40.831  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 15:30:40.831  7130  7130 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 15:30:40.835  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 15:30:40.836  7130  7610 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:40.841  4749  7664 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 15:30:40.846  4749  7665 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.846  4749  7665 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 15:30:40.890  7233  7233 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 15:30:40.904  3237  3237 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 15:30:40.905  3237  3237 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:40.905  3237  3237 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 15:30:40.911  7130  7610 V LGMDMManager: Create singleton instance
09-07 15:30:40.911  7233  7666 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:40.912  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 15:30:40.913  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 15:30:40.916  7130  7610 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 15:30:40.919  7334  7334 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:40
,09-07 15:30:40.921  7113  7669 W FormManager: Network not available. Please check & try again.
09-07 15:30:40.921  7334  7334 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 15:30:40.921  7334  7334 D Weather.Utils: 2 : All the weather widget is gone.
09-07 15:30:40.922  7334  7334 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 15:30:40.922  7334  7334 D WeatherAncestor: connectivity changed - connection : true
09-07 15:30:40.922  7334  7334 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e2ff9dd
09-07 15:30:40.922  7334  7334 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 15:30:40.922  7334  7334 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 15:30:40.922  7334  7334 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 15:30:40.922  7334  7334 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 15:30:40.922  7334  7334 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:40
09-07 15:30:40.928  7113  7670 V FormManager: Network unavailable.
09-07 15:30:40.935  7113  7670 V FormManager: Network unavailable.
,09-07 15:30:40.947  7643  7643 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-07 15:30:40.948  7643  7643 W LG Account v2.2: No ProfileInfo entries
09-07 15:30:40.948  7643  7643 I LG Account v2.2: isEnabled: false
,09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Country: EU
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Operator: OPEN
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Ranking support: false
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Comfort support: false
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Accessory: true
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Health device: true
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Extra Pedometer: false
09-07 15:30:40.948  7643  7643 I Feature : [Lifetracker]Blood glucose device: false
09-07 15:30:40.949  7643  7643 I Feature : [Lifetracker]Device Number: 3
09-07 15:30:40.954  7023  7023 D BluetoothPermissionRequest: onReceive
09-07 15:30:40.957  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 15:30:40.983  1035  1778 V SIM_STK : Menu title from STK is T-Mobile
09-07 15:30:40.983  1035  1778 V SIM_STK : Menu title from STK is T-Mobile
,09-07 15:30:41.095  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 15:30:41.109  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-07 15:30:41.116  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 15:30:41.117  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 15:30:41.118  7130  7130 I BluetoothA2dpServiceJni: classInitNative
09-07 15:30:41.118  7130  7130 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 15:30:41.118  7130  7130 D A2dpStateMachine: make
09-07 15:30:41.121  7130  7130 I bluedroid-qcom: get_profile_interface a2dp
09-07 15:30:41.122  7130  7674 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 15:30:41.124  7130  7130 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 15:30:41.124  7130  7130 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 15:30:41.125  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:41.126  7130  7130 D HeadsetStateMachine: Proxy object connected
09-07 15:30:41.126  7130  7130 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 15:30:41.126  7130  7130 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 15:30:41.127  7130  7673 D A2dpStateMachine: Enter Disconnected: -2
09-07 15:30:41.128  7130  7130 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 15:30:41.130  7130  7130 D HidService: Received start request. Starting profile...
,09-07 15:30:41.130  7130  7130 I bluedroid-qcom: get_profile_interface hidhost
09-07 15:30:41.130  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:41.131  7130  7130 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 15:30:41.132  7130  7130 D HealthService: Received start request. Starting profile...
09-07 15:30:41.134  7130  7130 I bluedroid-qcom: get_profile_interface health
09-07 15:30:41.134  7130  7130 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 15:30:41.134  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:41.138  7130  7130 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:41.139  7130  7130 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 15:30:41.141  7130  7642 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 15:30:41.141  7130  7642 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 15:30:41.141  7130  7642 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 15:30:41.142  7130  7130 D PanService: Received start request. Starting profile...
09-07 15:30:41.142  7130  7130 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 15:30:41.142  7130  7130 I bluedroid-qcom: get_profile_interface pan
09-07 15:30:41.147  7130  7130 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 15:30:41.147  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:41.148  7130  7130 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-07 15:30:41.155  7130  7130 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 15:30:41.156  7130  7130 D BtGatt.GattService: Received start request. Starting profile...
09-07 15:30:41.156  7130  7130 D BtGatt.GattService: start()
09-07 15:30:41.156  7130  7130 I bluedroid-qcom: get_profile_interface gatt
09-07 15:30:41.156  7130  7130 D BtGatt.AdvertiseManager: advertise manager created
09-07 15:30:41.162  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:41.163  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:41.164  7130  7130 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 15:30:41.164  7130  7130 V BluetoothMapService: BluetoothMapBinder()
09-07 15:30:41.165  7130  7130 D BluetoothMapService: Received start request. Starting profile...
09-07 15:30:41.165  7130  7130 D BluetoothMapService: start()
09-07 15:30:41.169  7130  7130 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 15:30:41.169  7130  7130 D BluetoothMapEmailAppObserver: createReceiver()
09-07 15:30:41.170  7130  7130 D BluetoothMapEmailAppObserver: initObservers()
09-07 15:30:41.170  7130  7130 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-07 15:30:41.187  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
,09-07 15:30:41.193  7130  7130 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:41.197  7130  7130 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:41.200  7130  7130 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:41.204  7130  7130 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:41.204  7130  7130 V PanService: [BTUI] SIM Extra State :ABSENT
,09-07 15:30:41.210  7130  7130 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-07 15:30:41.210  7130  7130 V BluetoothMapService: Handler(): got msg=1
09-07 15:30:41.212  7130  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 15:30:41.212  7130  7610 I bluedroid-qcom: enable
09-07 15:30:41.213  7130  7684 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 15:30:41.213  7130  7684 I bt-btu  : btu_task pending for preload complete event
09-07 15:30:41.213  7130  7610 I bt_hci_bdroid: init
09-07 15:30:41.215  7130  7130 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:41.217  7130  7610 I bt_vendor: bt-vendor : init
09-07 15:30:41.217  7130  7610 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 15:30:41.217  7130  7610 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 15:30:41.217  7130  7610 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 15:30:41.217  7130  7610 D bt_userial_mct: userial_init
09-07 15:30:41.218  7130  7610 D bt_hci_bdroid: set_power 1
09-07 15:30:41.218  7130  7130 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:41.218  7130  7610 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 15:30:41.219  7130  7610 I bt_vendor: Starting hciattach daemon
09-07 15:30:41.219  7130  7130 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:41.219  7130  7610 I bt_vendor: try to set true
09-07 15:30:41.219  7130  7130 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:41.219  7130  7130 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:41.219  7130  7130 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 15:30:41.208  7687  7687 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:41.218  7687  7687 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 15:30:41.251  7688  7688 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 15:30:41.340  7694  7694 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 15:30:41.351  7695  7695 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-07 15:30:41.372  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7693
,09-07 15:30:41.374  7697  7697 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 15:30:41.386  7698  7698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 15:30:41.411  7699  7699 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 15:30:41.429  7700  7700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 15:30:41.472  7702  7702 I libmdmdetect: ESOC framework not supported
,09-07 15:30:41.473  7702  7702 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 15:30:41.483  7702  7702 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-07 15:30:41.483  7702  7702 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 15:30:41.483  7702  7702 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 15:30:41.483  7702  7702 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 15:30:41.483  7702  7702 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 15:30:41.483  7702  7702 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 15:30:41.483  7702  7702 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 15:30:41.524  7702  7703 E QC-QMI  : qmi_client [7702] 14: failed to locate client data
,09-07 15:30:41.525   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-07 15:30:41.525   478   478 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-07 15:30:41.604  7704  7704 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 15:30:41.613  7361  7391 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-07 15:30:41.629  7706  7706 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 15:30:41.675  7130  7610 I bt_vendor: bluetooth satus is on
09-07 15:30:41.675  7130  7610 D bt_hci_bdroid: preload
09-07 15:30:41.676  7130  7686 D bt_userial_mct: userial_open(port:0)
09-07 15:30:41.676  7130  7686 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 15:30:41.680  7130  7686 I bt_vendor: Done intiailizing UART
,09-07 15:30:41.684  7130  7686 I bt_vendor: Done intiailizing UART
09-07 15:30:41.684  7130  7686 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 15:30:41.685  7130  7686 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-07 15:30:41.685  7130  7684 I bt-btu  : btu_task received preload complete event
09-07 15:30:41.686  7130  7709 D bt_userial_mct: Entering userial_read_thread()
09-07 15:30:41.687  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 15:30:41.687  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 15:30:41.694  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 15:30:41.703  7130  7684 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 15:30:41.704  7130  7684 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 15:30:41.704  7130  7684 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 15:30:41.816  7130  7684 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-07 15:30:41.817  7130  7684 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
09-07 15:30:41.817  7130  7684 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,09-07 15:30:41.834  7130  7614 E bt-btif : Calling BTA_HhEnable
09-07 15:30:41.834  7130  7614 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 15:30:41.835  7130  7614 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 15:30:41.838  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 15:30:41.839  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 15:30:41.839  7130  7614 D BluetoothAdapterProperties: Name is: G3
09-07 15:30:41.840  7130  7614 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:30:41.841  7130  7614 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:30:41.841  7130  7614 D bt_hci_bdroid: postload
09-07 15:30:41.842  7130  7614 D bte_conf: Device ID record 1 : primary
09-07 15:30:41.842  7130  7614 D bte_conf:   vendorId            = 00c4
09-07 15:30:41.842  7130  7614 D bte_conf:   vendorIdSource      = 0001
09-07 15:30:41.842  7130  7614 D bte_conf:   product             = 13a1
09-07 15:30:41.842  7130  7614 D bte_conf:   version             = 1000
09-07 15:30:41.842  7130  7614 D bte_conf:   clientExecutableURL = 
09-07 15:30:41.842  7130  7614 D bte_conf:   serviceDescription  = 
09-07 15:30:41.842  7130  7614 D bte_conf:   documentationURL    = 
09-07 15:30:41.842  7130  7614 D bte_conf: bte_load_did_conf no section named DID2.
09-07 15:30:41.843  7130  7686 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:41.843  7130  7686 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:41.846  7130  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 15:30:41.846  7130  7610 D BluetoothAdapterProperties: ScanMode =  20
09-07 15:30:41.846  7130  7610 D BluetoothAdapterProperties: State =  11
09-07 15:30:41.846  7130  7610 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 15:30:41.847  7130  7610 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 15:30:41.847  7130  7610 D BluetoothAdapterProperties: Setting state to 12
09-07 15:30:41.847  7130  7610 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 15:30:41.852  7130  7614 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 15:30:41.838  7717  7717 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:41.854  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:41.854  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 15:30:41.854  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-07 15:30:41.848  7717  7717 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:41.877  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:30:41.884  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:41.886  7130  7610 I BluetoothAdapterState: Entering On State
09-07 15:30:41.895  7130  7614 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:30:41.895  7130  7614 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:41.902  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:41.907  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:30:41.919  7130  7610 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 15:30:41.919  7130  7610 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 15:30:41.919  7130  7610 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-07 15:30:41.922  7130  7610 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 15:30:41.923  7130  7686 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:41.923  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 15:30:41.924  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-07 15:30:41.924  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 15:30:41.924  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 15:30:41.924  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 15:30:41.924  7130  7684 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 15:30:41.924  7130  7614 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 15:30:41.925  7023  7038 D BluetoothPan: onBluetoothStateChange on: true
09-07 15:30:41.945  7130  7709 E bt_mct  : hci lib postload completed
,09-07 15:30:41.948  7130  7610 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-07 15:30:41.949  7023  7038 D BluetoothPan: onBluetoothStateChange call bindService
09-07 15:30:41.963  7722  7722 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-07 15:30:41.970  7023  7038 D BluetoothMap: onBluetoothStateChange: up=true
09-07 15:30:41.974  1852  2646 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:41.976  7130  7684 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:41.976  7130  7684 W bt-smp  : Plain text(LSB ~ MSB) = ad 9a 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:41.976  7130  7684 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 58 51 c8 c2 5e 97 ee f8 83 47 aa 7e 9f 8c c3 
09-07 15:30:41.976  7130  7684 W bt-btm  : Stopping oneshot timer
09-07 15:30:41.979  7023  7112 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 15:30:41.991  7023  7023 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:30:41.991  7023  7023 D PanProfile: Bluetooth service connected
,09-07 15:30:41.998  1852  1852 D BluetoothHeadset: Proxy object connected
09-07 15:30:42.000  1852  4447 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:42.000  7023  7023 D BluetoothMap: Proxy object connected
09-07 15:30:42.001  7023  7023 D MapProfile: Bluetooth service connected
09-07 15:30:42.001  7023  7023 D BluetoothMap: getConnectedDevices()
09-07 15:30:42.004  1852  1852 D BluetoothHeadset: Proxy object connected
09-07 15:30:42.004  7130  7146 V BluetoothMapService: getConnectedDevices()
09-07 15:30:42.005  1852  2611 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 15:30:42.009  1852  1852 D BluetoothHeadset: Proxy object connected
09-07 15:30:42.010  7023  7038 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:30:42.013  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 15:30:42.013  7130  7684 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:42.013  7130  7684 W bt-smp  : Plain text(LSB ~ MSB) = b3 2a 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:42.013  7130  7684 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 21 b1 96 90 b4 cf e6 27 89 49 70 6c f3 bb 12 
09-07 15:30:42.013  7130  7684 W bt-btm  : Stopping oneshot timer
09-07 15:30:42.014  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:42.015  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 15:30:42.015  1035  1035 D BluetoothHeadset: Proxy object connected
09-07 15:30:42.015  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 15:30:42.018  1035  1035 D BluetoothA2dp: Proxy object connected
09-07 15:30:42.020  7023  7023 D BluetoothInputDevice: Proxy object connected
09-07 15:30:42.020  7023  7023 D HidProfile: Bluetooth service connected
,09-07 15:30:42.023  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 15:30:42.023  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.024  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:42.024  1940  2135 D LGBluetoothAPIService: Message: 1
09-07 15:30:42.024  1940  2135 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 15:30:42.027  7130  7684 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:42.027  7130  7684 W bt-smp  : Plain text(LSB ~ MSB) = 65 2f 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:42.027  7130  7684 W bt-smp  : Encrypted text(LSB ~ MSB) = 5a 73 b3 db 6c 60 57 11 73 61 52 3e 8f 07 9b 62 
09-07 15:30:42.027  7130  7684 W bt-btm  : Stopping oneshot timer
09-07 15:30:42.028  1940  2135 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-07 15:30:42.028  1035  1117 D BluetoothManagerService: Message: 40
09-07 15:30:42.028  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 15:30:42.029  6904  6904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 15:30:42.034  7130  7130 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.034  7130  7130 D BluetoothMapService: STATE_ON
,09-07 15:30:42.037  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:42.039  7130  7684 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:42.039  7130  7684 W bt-smp  : Plain text(LSB ~ MSB) = c4 8f 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:42.039  7130  7684 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 ea 1b 6b 28 82 b7 e1 65 bf 88 d9 c1 3b ff e1 
09-07 15:30:42.040  7130  7684 W bt-btm  : Stopping oneshot timer
09-07 15:30:42.040  7130  7130 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 15:30:42.040  7130  7130 D LGBluetoothAPIServer: [BTUI] onBind()
09-07 15:30:42.041  7130  7130 V BluetoothMapService: Handler(): got msg=1
09-07 15:30:42.042  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 15:30:42.042  1940  2135 D LGBluetoothAPIService: Message: 100
09-07 15:30:42.042  1940  2135 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 15:30:42.042  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:42.043  7130  7130 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 15:30:42.044  7023  7023 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 15:30:42.046  7130  7739 D BluetoothMapMasInstance: MAS initSocket()
09-07 15:30:42.047  7130  7739 D BluetoothMapMasInstance:   masId = 00
09-07 15:30:42.047  7130  7739 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 15:30:42.047  7130  7739 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 15:30:42.047  7130  7739 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 15:30:42.047  1035  1117 D BluetoothManagerService: Message: 30
09-07 15:30:42.048  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:42.049  7130  7684 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:42.049  7130  7684 W bt-smp  : Plain text(LSB ~ MSB) = a8 2f 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:42.049  7130  7684 W bt-smp  : Encrypted text(LSB ~ MSB) = dd d8 e0 f3 6a fd a3 96 8c 72 78 fc 4e c9 3c 69 
09-07 15:30:42.050  7130  7684 W bt-btm  : Stopping oneshot timer
09-07 15:30:42.050  7130  7739 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:42.052  7130  7614 D BluetoothAdapterProperties: Scan Mode:21
09-07 15:30:42.052  7130  7614 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 15:30:42.053  7130  7739 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 15:30:42.053  7130  7739 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 15:30:42.053  7130  7739 D BluetoothMapMasInstance: Accepting socket connection...
,09-07 15:30:42.056  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:42.057  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:42.059  7023  7023 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 15:30:42.062  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:42.062  7130  7130 V BluetoothPbapService: Pbap Service onCreate
09-07 15:30:42.063  7130  7130 V BluetoothPbapService: Starting PBAP service
09-07 15:30:42.064  7130  7130 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 15:30:42.064  7130  7130 V BluetoothPbapService: Pbap Service onBind
09-07 15:30:42.066  1035  1117 D BluetoothManagerService: Message: 30
09-07 15:30:42.070  7130  7130 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.070  7130  7130 V BluetoothPbapService: state: 12
09-07 15:30:42.070  7130  7130 V BluetoothPbapService: Handler(): got msg=1
,09-07 15:30:42.072  7130  7130 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 15:30:42.073  7130  7741 V BluetoothPbapService: Pbap Service initSocket
09-07 15:30:42.073  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:42.074  7130  7741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:42.075  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-07 15:30:42.075  7130  7741 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-07 15:30:42.075  7130  7741 V BluetoothPbapService: Succeed to create listening socket 
09-07 15:30:42.075  7130  7741 V BluetoothPbapService: Accepting socket connection...
09-07 15:30:42.076  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 15:30:42.080  7023  7023 D BluetoothA2dp: Proxy object connected
09-07 15:30:42.080  7023  7023 D A2dpProfile: Bluetooth service connected
09-07 15:30:42.082  7130  7130 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:42.083  7130  7130 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.083  7130  7130 V BluetoothPbapReceiver: ***********state = 12
,09-07 15:30:42.084  7023  7023 D BluetoothPbap: Proxy object connected
09-07 15:30:42.084  7023  7023 D PbapServerProfile: Bluetooth service connected
09-07 15:30:42.084  7023  7023 D BluetoothHeadset: Proxy object connected
09-07 15:30:42.086  7023  7023 D HeadsetProfile: Bluetooth service connected
09-07 15:30:42.086  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:30:42.086  2210  2210 D c       : Getting all permits...
09-07 15:30:42.086  2210  2210 D a       : Opening database...
09-07 15:30:42.089  7023  7023 D DockEventReceiver: finishStartingService: stopping service
09-07 15:30:42.091  2210  2210 D a       : Opening database auth.proximity.permit_store...
09-07 15:30:42.092  2210  2210 D a       : Closing database...
09-07 15:30:42.101  7023  7023 D BluetoothPermissionRequest: onReceive
,09-07 15:30:42.103  7023  7023 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 15:30:42.105  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 15:30:42.109  7130  7130 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 15:30:42.110  7130  7130 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 15:30:42.116  7130  7130 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 15:30:42.136  7130  7130 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 15:30:42.136  7130  7130 V BtOppService: onCreate
09-07 15:30:42.140  7130  7130 V BluetoothOppNotification: send message
09-07 15:30:42.143  7130  7130 V BtOppService: Starting RfcommListener
09-07 15:30:42.149  7130  7130 D BluetoothOppPreference: Dumping Names:  
09-07 15:30:42.149  7130  7130 D BluetoothOppPreference: {}
09-07 15:30:42.149  7130  7130 D BluetoothOppPreference: Dumping Channels:  
09-07 15:30:42.149  7130  7130 D BluetoothOppPreference: {}
09-07 15:30:42.150  7130  7130 V BtOppService: onStartCommand
,09-07 15:30:42.153  7130  7130 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.154  7130  7130 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 15:30:42.154  7130  7750 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 15:30:42.156  7130  7130 V BluetoothOppNotification: new notify threadi!
09-07 15:30:42.157  7130  7130 V BluetoothOppNotification: send delay message
09-07 15:30:42.158  7130  7130 V BtOppService: start RfcommListener
09-07 15:30:42.161  7130  7130 V BtOppService: RfcommListener started
,09-07 15:30:42.163  7130  7751 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 15:30:42.164  7130  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 15:30:42.166  7130  7752 V BtOppRfcommListener: Starting RFCOMM listener....
,09-07 15:30:42.166  1035  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:42.167  7130  7747 V BtOppService: Deleted complete outbound shares, number =  0
09-07 15:30:42.167  7130  7752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:42.168  7130  7752 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-07 15:30:42.169  7130  7752 V BtOppRfcommListener: Started RFCOMM listener....
09-07 15:30:42.169  7130  7752 I BtOppRfcommListener: Accept thread started.
09-07 15:30:42.169  7130  7752 V BtOppRfcommListener: Accepting connection...
09-07 15:30:42.170  7130  7751 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bde52ae on behalf of 
09-07 15:30:42.172  7130  7751 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 15:30:42.173  7130  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b6e684f on behalf of 
,09-07 15:30:42.175  7130  7747 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 15:30:42.176  7130  7747 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 15:30:42.177  7130  7751 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:42.179  7130  7747 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1de4abdc on behalf of 
09-07 15:30:42.181  7130  7751 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ee264e5 on behalf of 
09-07 15:30:42.183  7130  7750 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 15:30:42.183  7130  7751 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 15:30:42.183  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:42.183  7130  7130 V BluetoothFtpService: Ftp Service onCreate
09-07 15:30:42.183  7130  7130 I BluetoothFtpService: Ftp Service onCreate
09-07 15:30:42.184  7130  7130 V BluetoothFtpService: Ftp Service onStartCommand
09-07 15:30:42.184  7130  7130 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.184  7130  7130 V BluetoothFtpService: Starting Listening on sockets
09-07 15:30:42.184  7130  7130 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:42.185  7130  7130 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:42.185  7130  7130 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:42.185  7130  7130 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:42.185  7130  7130 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-07 15:30:42.185  7130  7130 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 15:30:42.186  7130  7751 V BluetoothOppNotification: outbound notification was removed.
09-07 15:30:42.186  7130  7751 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:42.188  7130  7130 V BtOppService: ContentObserver received notification
09-07 15:30:42.189  7130  7130 V BtOppService: ContentObserver received notification
,09-07 15:30:42.189  7130  7130 V BluetoothFtpService: Handler(): got msg=1
09-07 15:30:42.190  7130  7130 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 15:30:42.190  7130  7130 V BluetoothFtpService: Ftp Service initSocket
09-07 15:30:42.191  7130  7751 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22533a6b on behalf of 
09-07 15:30:42.193  7130  7751 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 15:30:42.194  7130  7753 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 15:30:42.194  7130  7753 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 15:30:42.195  7130  7751 V BluetoothOppNotification: inbound notification was removed.
09-07 15:30:42.195  7130  7751 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 15:30:42.196  7130  7753 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12fea9c8 on behalf of 
09-07 15:30:42.196  1035  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:42.196  7130  7753 V BluetoothOppNotification: update too frequent, put in queue
09-07 15:30:42.197  7130  7130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:30:42.198  7130  7751 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6d96a61 on behalf of 
09-07 15:30:42.198  7130  7753 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 15:30:42.199  7130  7130 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-07 15:30:42.199  7130  7130 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 15:30:42.201  7130  7754 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 15:30:42.216  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
,09-07 15:30:42.216  7130  7130 V BluetoothSapService: Sap Service onCreate
09-07 15:30:42.218  7130  7130 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:42.218  7130  7130 V BluetoothSapService: state: 12
09-07 15:30:42.218  7130  7130 V BluetoothSapService: Starting SAP server process
09-07 15:30:42.220  7130  7130 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 15:30:42.222  7130  7755 V BluetoothSapService: Sap Service initRfcommSocket
09-07 15:30:42.208  7756  7756 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:42.222  1035  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:42.208  7756  7756 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:42.223  7130  7755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:42.225  7130  7755 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-07 15:30:42.225  7130  7755 V BluetoothSapService: Succeed to create listening socket 
09-07 15:30:42.225  7130  7755 V BluetoothSapService: Accepting socket connection...
09-07 15:30:42.234  7756  7756 V BT_SAP  : Event pipe created
09-07 15:30:42.234  7756  7756 V BT_SAP  : create_server_socket qcom.sap.server
09-07 15:30:42.234  7756  7756 V BT_SAP  : created socket fd 6
,09-07 15:30:42.388  1035  1938 I ActivityManager: Killing 7538:com.lge.bnr/1000 (adj 15): empty #17
,09-07 15:30:42.447  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:42.448  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:30:42.468  1035  2368 W libprocessgroup: failed to open /acct/uid_1000/pid_7538/cgroup.procs: No such file or directory
,09-07 15:30:42.487  1035  1432 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-07 15:30:42.488  1035  1432 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-07 15:30:42.780  1035  2009 I ActivityManager: Killing 6769:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-07 15:30:42.807  7072  7072 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-07 15:30:42.808  7072  7072 W System.err: android.os.DeadObjectException
09-07 15:30:42.808  7072  7072 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 15:30:42.808  7072  7072 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 15:30:42.808  7072  7072 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-07 15:30:42.808  7072  7072 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-07 15:30:42.808  7072  7072 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 15:30:42.808  7072  7072 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 15:30:42.808  7072  7072 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:30:42.808  7072  7072 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:30:42.808  7072  7072 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:42.809  7072  7072 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:42.809  7072  7072 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:42.809  7072  7072 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:42.809  7072  7072 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:42.809  7072  7072 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 15:30:42.809  7072  7072 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-07 15:30:42.809  7072  7072 W System.err: android.os.DeadObjectException
09-07 15:30:42.809  7072  7072 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 15:30:42.809  7072  7072 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 15:30:42.809  7072  7072 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-07 15:30:42.809  7072  7072 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-07 15:30:42.810  7072  7072 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 15:30:42.810  7072  7072 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 15:30:42.810  7072  7072 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:30:42.810  7072  7072 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:30:42.810  7072  7072 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:42.810  7072  7072 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:42.810  7072  7072 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:42.810  7072  7072 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:42.810  7072  7072 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:42.810  7072  7072 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 15:30:42.810  7072  7072 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-07 15:30:42.810  7072  7072 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-07 15:30:42.844  1035  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_6769/cgroup.procs: No such file or directory
,09-07 15:30:42.844  1035  1957 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-07 15:30:42.864  7072  7072 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-07 15:30:42.865  7072  7072 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-07 15:30:42.910  1035  1921 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7766 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 15:30:42.974  7072  7072 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-07 15:30:43.002  7766  7766 D UEI.SmartControl: Quickset Services start...
09-07 15:30:43.004  7766  7766 I UEI.SmartControl: Manufacture = LGE
09-07 15:30:43.005  7766  7766 D UEI.SmartControl: Id = LGNevo
,09-07 15:30:43.009  7766  7766 D UEI.SmartControl: File observer start...
,09-07 15:30:43.009  7766  7766 E UEI.SmartControl: IR Port is disabled: false
09-07 15:30:43.010  7766  7766 D UEI.SmartControl: Starting file observer...
09-07 15:30:43.010  7766  7766 D UEI.SmartControl: Extracting JNI libs...
09-07 15:30:43.010  7766  7766 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-07 15:30:43.121  7766  7766 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-07 15:30:43.121  7766  7766 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-07 15:30:43.121  7766  7766 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-07 15:30:43.159  7130  7130 V BluetoothOppNotification: new notify threadi!
,09-07 15:30:43.159  7766  7766 I UEI.SmartControl: --- Selecting new region: 6
09-07 15:30:43.160  7130  7130 V BluetoothOppNotification: send delay message
09-07 15:30:43.163  7766  7766 I UEI.SmartControl: Model = LG-D855
09-07 15:30:43.163  7130  7794 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 15:30:43.165  7766  7766 D UEI.SmartControl: QS Service created
09-07 15:30:43.168  7130  7794 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12e14b9d on behalf of 
09-07 15:30:43.169  7130  7794 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-07 15:30:43.170  7130  7794 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:43.171  7130  7794 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7653812 on behalf of 
09-07 15:30:43.172  7130  7794 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 15:30:43.174  7130  7794 V BluetoothOppNotification: outbound notification was removed.
09-07 15:30:43.174  7130  7794 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:43.176  7130  7794 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d1a8be3 on behalf of 
09-07 15:30:43.176  7130  7794 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 15:30:43.178  7130  7794 V BluetoothOppNotification: inbound notification was removed.
09-07 15:30:43.178  7130  7794 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 15:30:43.179  7130  7794 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f7ee9e0 on behalf of 
,09-07 15:30:43.189  7766  7766 I UEI.SmartControl: Service initServices...
09-07 15:30:43.193  7766  7766 D UEI.SmartControl: QS start get config
,09-07 15:30:43.242  7766  7766 D UEI.SmartControl: Loading JNI Libs...
,09-07 15:30:43.408  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 15:30:43.408  1035  2030 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3ed5d577 mBinding = false
,09-07 15:30:43.437  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:43.438  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-07 15:30:43.441  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:43.442  1035  1117 D BluetoothManagerService: Message: 2
09-07 15:30:43.443  1035  1117 D BluetoothManagerService: Sending off request.
09-07 15:30:43.444  7130  7145 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 15:30:43.446  7130  7610 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 15:30:43.446  7130  7610 D BluetoothAdapterProperties: Setting state to 13
09-07 15:30:43.446  7130  7610 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 15:30:43.447  7130  7610 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 15:30:43.447  7130  7610 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 15:30:43.449  7130  7614 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:30:43.450  7130  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-07 15:30:43.457  7130  7741 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:43.457  7130  7610 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 15:30:43.462  7130  7739 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 15:30:43.463  7130  7752 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:43.463  7130  7754 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:43.464  7130  7755 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:30:43.464  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 15:30:43.464  7130  7684 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,09-07 15:30:43.470  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:43.470  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:43.470  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:43.470  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:43.470  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:30:43.471  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:43.471  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:43.471  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:43.471  7130  7684 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:43.471  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 15:30:43.471  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 15:30:43.471  7130  7684 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 15:30:43.472  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:43.472  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 15:30:43.472  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-07 15:30:43.472  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:43.472  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:43.473  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:43.473  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:43.475  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.476  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:43.479  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-07 15:30:43.480  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 15:30:43.489  7023  7023 D DockEventReceiver: finishStartingService: stopping service
09-07 15:30:43.490  7130  7130 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.490  7130  7130 D BluetoothMapService: STATE_TURNING_OFF
09-07 15:30:43.490  7130  7130 V BtOppService: Receiver DISABLED_ACTION 
09-07 15:30:43.490  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:43.490  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:43.490  7130  7130 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:43.491  7130  7130 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.491  7130  7130 V BluetoothPbapReceiver: ***********state = 13
09-07 15:30:43.491  6904  6904 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:30:43.491  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:43.493  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:43.496  7130  7130 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-07 15:30:43.497  7130  7130 V BluetoothMapService: Handler(): got msg=4
09-07 15:30:43.497  7130  7130 D BluetoothMapService: MAP Service closeService in
09-07 15:30:43.497  7130  7130 D BluetoothMapMasInstance: MAP Service shutdown
,09-07 15:30:43.498  7130  7130 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 15:30:43.498  7130  7130 V BluetoothMapService: MAP Service closeService out
09-07 15:30:43.498  7130  7130 I BtOppRfcommListener: stopping Accept Thread
09-07 15:30:43.498  7130  7130 V BtOppRfcommListener: close mBtServerSocket
09-07 15:30:43.498  7130  7130 V BtOppRfcommListener: waiting for thread to terminate
09-07 15:30:43.498  7130  7752 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 15:30:43.499  7130  7130 V BtOppRfcommListener: done waiting for thread to terminate
09-07 15:30:43.504  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:43.505  7130  7130 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.506  7130  7130 V BluetoothPbapService: state: 13
09-07 15:30:43.506  7130  7130 V BluetoothPbapService: Pbap Service closeService in
,09-07 15:30:43.507  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:30:43.510  7130  7130 V BluetoothPbapService: successfully stopped pbap service
09-07 15:30:43.510  7130  7130 V BluetoothPbapService: Pbap Service closeService out
09-07 15:30:43.510  7130  7130 V BtOppService: onDestroy
09-07 15:30:43.511  7023  7023 D BluetoothPbap: Proxy object disconnected
09-07 15:30:43.511  7023  7023 D PbapServerProfile: Bluetooth service disconnected
09-07 15:30:43.512  7130  7130 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-07 15:30:43.512  7130  7130 V BluetoothPbapService: Pbap Service onDestroy
09-07 15:30:43.512  7130  7130 V BluetoothPbapService: Pbap Service closeService in
09-07 15:30:43.512  7130  7130 V BluetoothPbapService: Pbap Service closeService out
09-07 15:30:43.512  7130  7130 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 15:30:43.513  7023  7023 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 15:30:43.515  7023  7023 D BluetoothPermissionRequest: onReceive
09-07 15:30:43.515  7023  7023 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 15:30:43.519  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 15:30:43.523  7130  7130 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 15:30:43.524  7130  7130 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 15:30:43.524  7130  7130 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-07 15:30:43.533  7130  7130 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:43.533  7130  7130 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 15:30:43.534  7130  7130 V BluetoothFtpService: Ftp Service onStartCommand
09-07 15:30:43.534  7130  7130 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.535  7130  7130 V BluetoothFtpService: Ftp Service closeService
09-07 15:30:43.535  7130  7130 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 15:30:43.536  7130  7130 V BluetoothFtpService: successfully stopped ftp service
09-07 15:30:43.536  7130  7130 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:43.536  7130  7130 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:43.536  7130  7130 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:43.536  7130  7130 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.536  7130  7130 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 15:30:43.536  7130  7130 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 15:30:43.537  7130  7130 V BluetoothFtpService: Ftp Service onDestroy
09-07 15:30:43.537  7130  7130 V BluetoothFtpService: Ftp Service closeService
09-07 15:30:43.539  7130  7130 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:43.539  7130  7130 V BluetoothSapService: state: 13
09-07 15:30:43.539  7130  7130 V BluetoothSapService: Stopping SAP server process
09-07 15:30:43.540  7130  7130 V BluetoothSapService: Sap Service closeSapService in
09-07 15:30:43.540  7130  7130 V BluetoothSapService: Close listen Socket : 
09-07 15:30:43.540  7130  7130 V BluetoothSapService: Close rfcomm Socket : 
09-07 15:30:43.540  7130  7130 V BluetoothSapService: Close sapd  Socket : 
09-07 15:30:43.540  7130  7130 V BluetoothSapService: Sap Service closeSapService out
09-07 15:30:43.541  7130  7130 V BluetoothSapService: Sap Service onDestroy
09-07 15:30:43.541  7130  7130 V BluetoothSapService: Sap Service closeSapService in
09-07 15:30:43.541  7130  7130 V BluetoothSapService: Close listen Socket : 
09-07 15:30:43.541  7130  7130 V BluetoothSapService: Close rfcomm Socket : 
09-07 15:30:43.541  7130  7130 V BluetoothSapService: Close sapd  Socket : 
09-07 15:30:43.541  7130  7130 V BluetoothSapService: Sap Service closeSapService out
09-07 15:30:43.552  7766  7766 I UEI.SmartControl: Supports setup maps: true
,09-07 15:30:43.558  7766  7766 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 15:30:43.558  7766  7766 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 15:30:43.558  7766  7766 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 15:30:43.558  7766  7766 I UEI.SmartControl: ### init IR Blaster...
09-07 15:30:43.563  7766  7766 D serial_port: Configuring serial port
,09-07 15:30:43.568  7766  7766 E UEI.SmartControl: UEIBLaster setting for 616
09-07 15:30:43.568  7766  7766 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 15:30:43.568  7766  7766 I UEI.SmartControl: configuring settings for MAXQ616
09-07 15:30:43.568  7766  7766 I UEI.SmartControl: Get version...
09-07 15:30:43.584  7766  7813 D UEI.SmartControl: serial port data available: 21
,09-07 15:30:43.612  7766  7766 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 15:30:43.612  7766  7766 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-07 15:30:43.613  7766  7766 I UEI.SmartControl: QS saving settings...
09-07 15:30:43.616  7766  7766 D UEI.SmartControl: IR Blaster version: 25672567
09-07 15:30:43.634  7766  7813 D UEI.SmartControl: serial port data available: 4
,09-07 15:30:43.670  7766  7816 I UEI.SmartControl: Device manager: loading config....
,09-07 15:30:43.671  7766  7816 D UEI.SmartControl: ----------- loading internal config...
,09-07 15:30:43.680  7766  7766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-07 15:30:43.684  7766  7766 E UEI.SmartControl: Services init done
09-07 15:30:43.684  7766  7766 D UEI.SmartControl: QS Service init finished
09-07 15:30:43.685  7766  7816 E UEI.SmartControl: Loading SETTINGS...
09-07 15:30:43.686  7766  7766 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 15:30:43.686  7766  7766 D UEI.SmartControl: QS Service version code: 201091
,09-07 15:30:43.693  7766  7766 D UEI.SmartControl: Service requested: Control
09-07 15:30:43.696  7072  7072 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 15:30:43.696  7766  7781 I UEI.SmartControl: ------ IControl API: 11
09-07 15:30:43.697  1035  1973 I ActivityManager: Killing 7072:com.lge.qremote/u0a112 (adj 15): empty #17
09-07 15:30:43.699  7766  7781 I UEI.SmartControl: Registering callback...
09-07 15:30:43.705  7766  7816 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-07 15:30:43.728  7766  7815 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-07 15:30:43.728  7766  7815 D UEI.SmartControl: -----service ready thread exits
,09-07 15:30:43.738  1035  1921 W libprocessgroup: failed to open /acct/uid_10112/pid_7072/cgroup.procs: No such file or directory
,09-07 15:30:43.738  7766  7766 D UEI.SmartControl: Internal service binding...
09-07 15:30:44.373  7130  7614 D bt_hci_bdroid: cleanup
,09-07 15:30:44.382  7130  7686 I bt_lpm  : LPM is already off!!!
,09-07 15:30:44.383  7130  7709 I bt_userial_mct: exiting userial_read_thread
09-07 15:30:44.383  7130  7709 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 15:30:44.384  7130  7684 W bt-btif : ag scb idx 1 not allocated
,09-07 15:30:44.384  7130  7684 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:44.384  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:30:44.385  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 15:30:44.387  7130  7614 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 15:30:44.390  7130  7686 I bt_vendor: hw_epilog_process
09-07 15:30:44.391  7130  7614 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 15:30:44.392  7130  7614 D bt_userial_mct: userial_close
09-07 15:30:44.392  7130  7614 E bt_userial_mct: pthread_join() FAILED result:3
09-07 15:30:44.392  7130  7614 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-07 15:30:44.399  7130  7684 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:30:44.399  7130  7684 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 15:30:44.399  7130  7684 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:30:44.399  7130  7684 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 15:30:44.407  7130  7614 D bt_hci_bdroid: set_power 0
09-07 15:30:44.407  7130  7614 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 15:30:44.407  7130  7614 I bt_vendor: bluetooth satus is on
09-07 15:30:44.407  7130  7614 I bt_vendor: bt-vendor : resetting BT status
09-07 15:30:44.407  7130  7614 I bt_vendor: Starting hciattach daemon
09-07 15:30:44.407  7130  7614 I bt_vendor: try to set false
09-07 15:30:44.410  7130  7614 I bt_vendor: Starting hciattach daemon
09-07 15:30:44.410  7130  7614 I bt_vendor: try to set false
,09-07 15:30:44.413  7130  7614 I bt_vendor: cleanup
09-07 15:30:44.414  7130  7684 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 15:30:44.415  7130  7614 I GKI_LINUX: GKI_exit_task 0 done
09-07 15:30:44.415  7130  7614 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 15:30:44.417  7130  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 15:30:44.422  7130  7130 D HeadsetService: Received stop request...Stopping profile...
,09-07 15:30:44.428  7130  7130 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 15:30:44.429  7130  7130 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:30:44.429  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.429  7130  7642 D HeadsetStateMachine: Exit Disconnected: -1
09-07 15:30:44.433  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:44.433  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:44.433  1852  1852 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:44.434  7130  7130 D A2dpService: Received stop request...Stopping profile...
09-07 15:30:44.435  7130  7673 D A2dpStateMachine: Exit Disconnected: -1
09-07 15:30:44.437  7130  7130 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-07 15:30:44.441  7130  7130 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 15:30:44.442  7130  7130 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:30:44.442  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.444  7130  7610 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 15:30:44.444  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-07 15:30:44.444  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 15:30:44.445  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-07 15:30:44.445  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 15:30:44.446  7130  7130 D HidService: Received stop request...Stopping profile...
09-07 15:30:44.446  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.449  7130  7130 D HealthService: Received stop request...Stopping profile...
09-07 15:30:44.449  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.452  7130  7130 D HeadsetStateMachine: Unbinding service...
,09-07 15:30:44.455  7130  7130 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 15:30:44.455  7130  7130 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 15:30:44.455  7130  7130 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 15:30:44.456  7130  7130 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 15:30:44.456  7130  7130 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 15:30:44.456  7130  7130 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:30:44.456  7130  7130 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 15:30:44.457  7130  7130 D PanService: Received stop request...Stopping profile...
09-07 15:30:44.457  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.458  7130  7130 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 15:30:44.459  7130  7130 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 15:30:44.459  7130  7130 D BtGatt.GattService: stop()
09-07 15:30:44.459  7130  7130 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 15:30:44.460  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.461  7130  7130 D BluetoothMapService: Received stop request...Stopping profile...
09-07 15:30:44.461  7130  7130 D BluetoothMapService: stop()
09-07 15:30:44.463  7130  7130 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 15:30:44.463  7130  7130 D BluetoothMapEmailAppObserver: removeReceiver()
,09-07 15:30:44.466  7130  7130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:44.467  7130  7130 I BluetoothA2dpServiceJni: cleanupNative
09-07 15:30:44.468  7130  7674 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 15:30:44.468  7130  7130 I GKI_LINUX: GKI_exit_task 2 done
09-07 15:30:44.468  7130  7130 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 15:30:44.468  7130  7130 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 15:30:44.468  7130  7130 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 15:30:44.469  7130  7130 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 15:30:44.469  7130  7130 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:30:44.469  7130  7130 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:30:44.469  7130  7130 V BluetoothMapService: Handler(): got msg=4
09-07 15:30:44.469  7130  7130 D BluetoothMapService: MAP Service closeService in
09-07 15:30:44.469  7130  7130 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 15:30:44.469  7130  7130 V BluetoothMapService: MAP Service closeService out
09-07 15:30:44.471  7130  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 15:30:44.471  7130  7610 D BluetoothAdapterProperties: Setting state to 10
09-07 15:30:44.471  7130  7610 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 15:30:44.474  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:44.474  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 15:30:44.474  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-07 15:30:44.477  7130  7610 I BluetoothAdapterState: Entering OffState
,09-07 15:30:44.480  7023  7038 D BluetoothPan: onBluetoothStateChange on: false
09-07 15:30:44.481  7130  7130 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 15:30:44.481  7130  7130 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 15:30:44.483  7130  7130 D BluetoothMapService: cleanup()
09-07 15:30:44.483  7130  7130 D BluetoothMapService: MAP Service closeService in
09-07 15:30:44.483  7130  7130 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 15:30:44.483  7130  7130 V BluetoothMapService: MAP Service closeService out
09-07 15:30:44.484  7023  7038 D BluetoothMap: onBluetoothStateChange: up=false
09-07 15:30:44.484  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:44.485  7023  7038 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:44.486  7023  7038 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 15:30:44.487  1852  2611 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:44.488  1852  4437 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:44.488  7023  7038 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 15:30:44.491  7023  7038 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:30:44.491  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:30:44.492  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:30:44.492  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 15:30:44.492  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-07 15:30:44.494  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 15:30:44.494  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 15:30:44.494  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3ed5d577 mBinding = false
09-07 15:30:44.495  1035  1117 D BluetoothManagerService: Sending unbind request.
09-07 15:30:44.499  7130  7614 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-07 15:30:44.502  7130  7130 I GKI_LINUX: GKI_exit_task 1 done
,09-07 15:30:44.502  7130  7130 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated,
09-07 15:30:44.503  7130  7130 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 15:30:44.503  7130  7130 I art     : --- WEIRD: removing null entry 248
,09-07 15:30:44.503  7130  7130 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-07 15:30:44.503  7130  7130 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,09-07 15:30:44.504  7130  7130 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-07 15:30:44.505  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-07 15:30:44.507  7130  7130 I art     : System.exit called, status: 0
09-07 15:30:44.507  7130  7130 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 15:30:44.533  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:44.545   315   315 V AudioFlinger: 7130 died, releasing its sessions
09-07 15:30:44.545   315   315 V AudioFlinger:  pid 1852 @ 0
09-07 15:30:44.545   315   315 V AudioFlinger:  pid 3237 @ 1
09-07 15:30:44.545  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:44.545   315   315 V AudioFlinger:  pid 3237 @ 2
09-07 15:30:44.547  1940  2135 D LGBluetoothAPIService: Message: 2
09-07 15:30:44.547  1940  2135 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@29862904 mBinding = false
09-07 15:30:44.547  1940  2135 D LGBluetoothAPIService: Sending unbind request.
09-07 15:30:44.547  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-07 15:30:44.547  7023  7023 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-07 15:30:44.550  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:44.551  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:44.554  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 15:30:44.554  7023  7023 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 15:30:44.558  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 15:30:44.559  1602  1602 D BluetoothAdapter: 108402175: getState() :  mService = null. Returning STATE_OFF
,09-07 15:30:44.559  1602  1602 D BluetoothAdapter: 108402175: getState() :  mService = null. Returning STATE_OFF
09-07 15:30:44.605  1035  2368 I ActivityManager: Process com.android.bluetooth (pid 7130) has died
09-07 15:30:44.606  1035  2368 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-07 15:30:44.606  1035  2368 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-07 15:30:44.611  1940  2135 D LGBluetoothAPIService: Message: 101
,09-07 15:30:44.611  1940  2135 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-07 15:30:44.683  1035  1921 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7848 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-07 15:30:44.686  7023  7023 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:30:44.771  7848  7848 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-07 15:30:44.771  7848  7848 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:44.772  7848  7848 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 15:30:44.772  7848  7848 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 15:30:44.802  7848  7848 D BluetoothAdapterApp: Loading JNI Library
,09-07 15:30:44.839  7848  7848 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@249a8b25 Instance Count = 1
,09-07 15:30:44.846  7848  7848 D BluetoothAdapterApp: onCreate
09-07 15:30:44.873  7848  7848 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-07 15:30:44.873  7848  7848 D ProfileConfigQcom: Adding HeadsetService
09-07 15:30:44.873  7848  7848 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-07 15:30:44.873  7848  7848 D ProfileConfigQcom: Adding A2dpService
09-07 15:30:44.874  7848  7848 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 15:30:44.874  7848  7848 D ProfileConfigQcom: Adding HidService
09-07 15:30:44.874  7848  7848 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 15:30:44.874  7848  7848 D ProfileConfigQcom: Adding HealthService
09-07 15:30:44.875  7848  7848 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-07 15:30:44.876  7848  7848 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 15:30:44.876  7848  7848 D ProfileConfigQcom: Adding PanService
09-07 15:30:44.876  7848  7848 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 15:30:44.876  7848  7848 D ProfileConfigQcom: Adding GattService
09-07 15:30:44.877  7848  7848 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 15:30:44.877  7848  7848 D ProfileConfigQcom: Adding BluetoothMapService
09-07 15:30:44.877  7848  7848 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 15:30:44.878  7848  7848 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:44.880  7848  7848 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:44.880  7848  7848 V BluetoothPbapReceiver: ***********state = 10
09-07 15:30:44.882  7848  7848 V LGMDMManagerInternal: Create singleton instance
09-07 15:30:44.982  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:30:44.988  7023  7023 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 15:30:44.991  1035  1889 I ActivityManager: Killing 7044:com.lge.sync/1000 (adj 15): empty #17
09-07 15:30:45.009  1035  1471 D WifiService: Client connection lost with reason: 4
,09-07 15:30:45.027  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_7044/cgroup.procs: No such file or directory
,09-07 15:30:45.063  7023  7023 D BluetoothPermissionRequest: onReceive
,09-07 15:30:45.069  7023  7023 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-07 15:30:45.069  7023  7023 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-07 15:30:45.075  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 15:30:45.087  7848  7848 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-07 15:30:45.105  7848  7848 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:45.116  7848  7848 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:45.117  7848  7848 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:45.117  7848  7848 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:45.118  7848  7848 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:45.119  7848  7848 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 15:30:45.131  7089  7089 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-07 15:30:46.449  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:30:46.449  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:46.546  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-07 15:30:46.574  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 15:30:46.606  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-07 15:30:46.662  1035  1035 D administrator: Handling package changes for user 0
,09-07 15:30:46.684  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7876 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-07 15:30:46.695  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-07 15:30:46.700  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-07 15:30:46.735  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 15:30:46.771  7876  7876 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 15:30:46.818  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-07 15:30:46.818  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-07 15:30:46.832  7876  7876 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:46.833  7876  7876 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 15:30:46.857  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:30:46.864  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 15:30:46.873  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 15:30:46.875  2493  2493 V GmsNetworkLocationProvi: DISABLE
09-07 15:30:46.905  1035  1112 D LocationProviderProxy: applying state to connected service
,09-07 15:30:46.909  2493  2493 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-07 15:30:46.922  7876  7920 I Babel   : MmsConfig: mnc/mcc: 0/0
09-07 15:30:46.922  7876  7920 I Babel   : MmsConfig.loadMmsSettings
09-07 15:30:46.926  7876  7920 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-07 15:30:46.926  7876  7920 I Babel   : MmsConfig.loadFromDatabase
09-07 15:30:46.945  7876  7918 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 15:30:46.956  7876  7918 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 15:30:46.957  7876  7876 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:46.958  7876  7918 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-07 15:30:46.965  7876  7920 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-07 15:30:46.965  7876  7920 I Babel   : MmsConfig.loadFromResources
09-07 15:30:46.967  7876  7920 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-07 15:30:46.967  7876  7918 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-07 15:30:46.967  7876  7920 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-07 15:30:46.968  7876  7918 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 15:30:46.976  7876  7918 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 15:30:46.987  7876  7918 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 15:30:46.990  7876  7918 W VideoCapabilities: Unsupported mime video/divx
09-07 15:30:46.991  7876  7918 W VideoCapabilities: Unsupported mime video/divx311
09-07 15:30:46.994  7876  7918 W VideoCapabilities: Unsupported mime video/divx4
09-07 15:30:47.002  7876  7918 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-07 15:30:47.007  1816  7922 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 15:30:47.007  1816  7922 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-07 15:30:47.014  7198  7198 I AppUp4:CustModeStarterReceiver: onReceive
09-07 15:30:47.023  1816  5222 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-07 15:30:47.024  7198  7198 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34860687
09-07 15:30:47.024  7198  7198 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 15:30:47.024  7198  7198 D AppUp4:CustFacade: isPhone : true
,09-07 15:30:47.025  7198  7198 D AppUp4:CustModeStarterReceiver: begin check event
09-07 15:30:47.025  7198  7198 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-07 15:30:47.036  7876  7918 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 15:30:47.048  7876  7918 W AudioCapabilities: Unsupported mime audio/eac3
09-07 15:30:47.049  7876  7918 W AudioCapabilities: Unsupported mime audio/ac3
09-07 15:30:47.050  7876  7918 W AudioCapabilities: Unsupported mime audio/g726
09-07 15:30:47.050  7876  7918 W AudioCapabilities: Unsupported mime audio/wma-voice
09-07 15:30:47.051  7876  7918 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-07 15:30:47.052  7876  7918 W AudioCapabilities: Unsupported mime audio/adpcm
09-07 15:30:47.053  7876  7918 W VideoCapabilities: Unsupported mime video/theora
09-07 15:30:47.055  7876  7918 W VideoCapabilities: Unsupported mime video/mjpg
09-07 15:30:47.071  1035  1650 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7926 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-07 15:30:47.108  1035  1050 I ActivityManager: Killing 7233:com.lge.email/u0a23 (adj 15): empty #17
09-07 15:30:47.121  7926  7926 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:30:47.121  7926  7926 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:47.121  7926  7926 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 15:30:47.122  7926  7926 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-07 15:30:47.123  7926  7926 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 15:30:47.189  1035  2368 W libprocessgroup: failed to open /acct/uid_10023/pid_7233/cgroup.procs: No such file or directory
,09-07 15:30:47.220  7926  7926 I SystemConfig: BUILD Country: EU
09-07 15:30:47.221  7926  7926 I SystemConfig: BUILD Operator: OPEN
,09-07 15:30:47.269  1035  1957 I ActivityManager: Killing 7113:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-07 15:30:47.435  1035  1762 W libprocessgroup: failed to open /acct/uid_10026/pid_7113/cgroup.procs: No such file or directory
,09-07 15:30:47.497  1035  1957 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7950 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-07 15:30:47.501  7926  7944 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-07 15:30:47.501  7926  7944 I SystemConfig: existFile = false
09-07 15:30:47.502  7926  7944 I SystemConfig: canReadFile = false
09-07 15:30:47.502  7926  7944 I SystemConfig: systemFeature RCS result false
09-07 15:30:47.502  7926  7944 D SystemConfig: refreshRcsSupport() :false
,09-07 15:30:47.569  7950  7950 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:30:47.569  7950  7950 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 15:30:47.569  7950  7950 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-07 15:30:47.570  7950  7950 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 15:30:47.675  7950  7950 I AppConfig: Total System Memory = 2995761152
,09-07 15:30:47.688  7950  7950 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-07 15:30:47.795  1035  1050 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7972 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 15:30:47.796  1035  1050 I ActivityManager: Killing 6465:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-07 15:30:47.886  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6465/cgroup.procs: No such file or directory
,09-07 15:30:48.071  7972  7972 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-07 15:30:48.177  7972  7972 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:48.177  7972  7972 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:48.238  7972  7972 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-07 15:30:48.265  7972  7972 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 15:30:48.267  7972  7972 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 15:30:48.286  7972  7972 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:30:48.287  7972  7972 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-07 15:30:48.319  1035  1938 I ActivityManager: Killing 7269:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-07 15:30:48.351  1035  1973 W libprocessgroup: failed to open /acct/uid_10046/pid_7269/cgroup.procs: No such file or directory
09-07 15:30:48.352  2854  6009 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-07 15:30:48.358  2854  6009 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@210f6a98 on behalf of 7972
09-07 15:30:48.365  7972  7972 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-07 15:30:48.367  5052  8017 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-07 15:30:48.404  1035  1762 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8019 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-07 15:30:48.563  1035  1993 I art     : Explicit concurrent mark sweep GC freed 43655(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.300ms total 146.430ms
,09-07 15:30:48.597  7972  7972 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 15:30:48.609  8019  8019 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-07 15:30:48.624  8019  8019 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-07 15:30:48.624  8019  8019 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-07 15:30:48.624  8019  8019 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-07 15:30:48.624  8019  8019 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-07 15:30:48.624  8019  8019 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-07 15:30:48.624  8019  8019 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-07 15:30:48.639  1035  2031 I ActivityManager: Killing 7291:com.android.chrome/u0a57 (adj 15): empty #17
,09-07 15:30:48.667  1035  1921 W libprocessgroup: failed to open /acct/uid_10057/pid_7291/cgroup.procs: No such file or directory
,09-07 15:30:48.674  7766  7817 D UEI.SmartControl: Internal timer expired: 1
09-07 15:30:48.674  7766  7817 D UEI.SmartControl: unbind internal service
09-07 15:30:48.676  7766  7766 D UEI.SmartControl: Service.onUnbind: IControl
09-07 15:30:48.676  7766  7766 D UEI.SmartControl: Service.onDestroy
09-07 15:30:48.677  7766  7766 D UEI.SmartControl: Lock is in USE false
09-07 15:30:48.677  7766  7766 D UEI.SmartControl: unbind internal service
09-07 15:30:48.677  7766  7766 D serial_port: close(fd = 25)
09-07 15:30:48.680  7766  7766 I UEI.SmartControl: Serial port is closed.
09-07 15:30:48.680  7766  7766 I UEI.SmartControl: Serial port is closed.
09-07 15:30:48.680  7766  7766 D UEI.SmartControl: Blaster closed
09-07 15:30:48.680  7766  7766 D UEI.SmartControl: Shut down QS...
09-07 15:30:48.680  7766  7766 D UEI.SmartControl: Stopping QS lib
09-07 15:30:48.681  7766  7766 D UEI.SmartControl: QS lib stop result = true
09-07 15:30:48.681  7766  7766 D UEI.SmartControl: Stopped QS lib
09-07 15:30:48.681  7766  7766 D UEI.SmartControl: Stopped file observer...
09-07 15:30:48.682  7766  7766 D UEI.SmartControl: QS shutdown complete
,09-07 15:30:48.939  1035  1778 V SIM_STK : Menu title from STK is T-Mobile
,09-07 15:30:48.965  5052  8017 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 598 ms] updated apps [took 598 ms] 
,09-07 15:30:49.462  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:49.462  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@291d9b81 added. We now have 6 listener(s)
,09-07 15:30:49.462  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:30:49.468  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:49.468  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc2b426 added. We now have 7 listener(s)
09-07 15:30:49.468  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:49.469  6904  6983 I System.out: IsBluetoothEnabled
09-07 15:30:49.470  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:49.470  1035  1973 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-07 15:30:49.470  1035  1117 D BluetoothManagerService: Message: 2
09-07 15:30:49.474  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:49.474  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:49.474  1035  1051 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 15:30:49.494  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 15:30:49.495  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:49.495  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:49.495  1035  1117 D BluetoothManagerService: Message: 1
09-07 15:30:49.496  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 15:30:49.521  1035  1117 D BluetoothManagerService: Message: 20
09-07 15:30:49.521  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cbe3682:true
,09-07 15:30:49.525  7848  7848 D BluetoothAdapterState: make
09-07 15:30:49.530  7848  7848 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 15:30:49.530  7848  7848 I bluedroid-qcom: init
09-07 15:30:49.531  7848  8063 I BluetoothAdapterState: Entering OffState
09-07 15:30:49.532  7848  7848 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 15:30:49.532  7848  7848 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 15:30:49.532  7848  7848 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 15:30:49.532  7848  7848 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 15:30:49.532  7848  7848 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 15:30:49.534  7848  7848 I bluedroid-qcom: get_profile_interface socket
,09-07 15:30:49.537  7848  7848 I bluedroid-qcom: get_profile_interface map_client
09-07 15:30:49.539  7848  8067 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 15:30:49.541  7848  8067 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 15:30:49.528  8066  8066 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:49.528  8066  8066 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:49.553  8066  8066 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 15:30:49.553  8066  8066 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 15:30:49.553  8066  8066 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-07 15:30:49.561  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 15:30:49.562  7848  8067 D BluetoothAdapterProperties: Name is: G3
09-07 15:30:49.562  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-07 15:30:49.562  8066  8066 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-07 15:30:49.564  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 15:30:49.564  1035  1117 D BluetoothManagerService: Message: 40
09-07 15:30:49.564  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 15:30:49.565  7848  7863 I bluedroid-qcom: config_hci_snoop_log
09-07 15:30:49.567  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 15:30:49.567  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-07 15:30:49.570  8066  8066 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 15:30:49.570  8066  8066 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 15:30:49.578  7848  8063 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 15:30:49.578  7848  8063 D BluetoothAdapterProperties: Setting state to 11
09-07 15:30:49.578  7848  8063 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 15:30:49.580  7848  8063 I LGBluetoothServiceJni: classInitNative: succeeds
,09-07 15:30:49.582  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:49.582  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 15:30:49.582  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-07 15:30:49.586  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:49.587  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:49.588  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-07 15:30:49.590  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:49.596  7848  7848 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:49.596  7848  7848 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:49.596  7848  7848 V BluetoothPbapReceiver: ***********state = 11
,09-07 15:30:49.598  7848  8063 D BluetoothBondStateMachine: make
09-07 15:30:49.602  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:30:49.606  7848  8063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:49.608  7848  8063 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 15:30:49.609  7848  8063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:49.609  7848  8063 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 15:30:49.610  7848  8063 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-07 15:30:49.616  7848  8078 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 15:30:49.620  7023  7023 D BluetoothPermissionRequest: onReceive
09-07 15:30:49.621  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:49.627  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 15:30:49.631  7848  7848 D HeadsetService: Received start request. Starting profile...
09-07 15:30:49.631  7848  7848 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 15:30:49.632  7848  7848 D LGBluetoothHfpAdapter: Version 1.6
09-07 15:30:49.634  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:49.635  7848  7848 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 15:30:49.636  7848  7848 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 15:30:49.637  7848  7848 D HeadsetStateMachine: make
09-07 15:30:49.639  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 15:30:49.645  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:49.651  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:49.656  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 15:30:49.661  7848  8063 E BluetoothAdapterService: File transfer profiles supported!!
09-07 15:30:49.677  7848  8063 V LGMDMManager: Create singleton instance
,09-07 15:30:49.678  7848  7848 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:49.678  7848  7848 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 15:30:49.679  7848  8063 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 15:30:49.683  7848  7848 D HeadsetStateMachine: max_hf_connections = 1
09-07 15:30:49.683  7848  7848 I bluedroid-qcom: get_profile_interface handsfree
09-07 15:30:49.685  7848  7848 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-07 15:30:49.686   315  2156 V AudioPolicyService: registerClient() client 0xb558af60, uid 1002
09-07 15:30:49.686   315  2157 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 15:30:49.686   315  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 15:30:49.686   315  2157 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 15:30:49.686  7848  7848 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 15:30:49.687   315   315 V AudioFlinger: registerClient() client 0xb16dddf0, pid 7848
09-07 15:30:49.687   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:49.687   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:49.687  1602  2093 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:49.687   315  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:49.687  1602  2093 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:49.687   315  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:49.688  7848  7863 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:49.688  7848  7863 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 15:30:49.688  7848  7863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:49.688  7848  7863 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 15:30:49.688  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:49.688  1602  2538 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:49.688  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:49.688  1602  2538 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:49.688  1852  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:49.688  1852  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:49.688  3237  3255 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:49.688  3237  3255 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 15:30:49.688  3237  3255 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:49.688  3237  3255 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:49.688  1035  2368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 15:30:49.688  1035  2368 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-07 15:30:49.688  1035  2368 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 15:30:49.688  7848  7848 V ToneGenerator: Create Track: 0xb4928a80
09-07 15:30:49.688  1035  2368 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 15:30:49.688  7848  7848 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 15:30:49.688  7848  7848 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 15:30:49.688   315  2156 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 15:30:49.689   315  2156 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 15:30:49.689   315  2156 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 15:30:49.689   315  2156 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 15:30:49.689   315  2157 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 15:30:49.689   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 15:30:49.689   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 15:30:49.689   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 15:30:49.689   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 15:30:49.689  7848  7848 V AudioSystem: getLatency() output 2, latency 50
09-07 15:30:49.689  7848  7848 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 15:30:49.689  7848  7848 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 15:30:49.690   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 15:30:49.690   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 15:30:49.690   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 15:30:49.690   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 15:30:49.690   315  1397 V AudioFlinger: createTrack() lSessionId: 21
09-07 15:30:49.691  7848  7848 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 15:30:49.691   315  1397 V AudioFlinger: acquiring 21 from 7848, for 7848
09-07 15:30:49.691   315  1397 V AudioFlinger:  added new entry for 21
09-07 15:30:49.691  7848  7848 V ToneGenerator: ToneGenerator INIT OK, time: 191166
09-07 15:30:49.691  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:49.692  7848  8085 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 15:30:49.693  7848  8085 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 15:30:49.694  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
,09-07 15:30:49.694  7848  8085 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,09-07 15:30:49.694  7848  8085 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 15:30:49.695   315  1396 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7848
09-07 15:30:49.696   315  1396 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 15:30:49.696   315  1396 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 15:30:49.696   315  1396 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,09-07 15:30:49.696   315  1396 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 15:30:49.696   315  1396 V voice   : voice_set_parameters: exit with code(0)
09-07 15:30:49.696   315  1396 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 15:30:49.696   315  1396 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 15:30:49.696  7848  7848 D A2dpService: Received start request. Starting profile...,
09-07 15:30:49.696   315  1396 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 15:30:49.696   315  1396 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 15:30:49.696   315  1396 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 15:30:49.696   315  1396 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 15:30:49.697  7848  8085 V ToneGenerator: ToneGenerator destructor
09-07 15:30:49.697  7848  8085 V ToneGenerator: stopTone
,09-07 15:30:49.697  7848  8085 V ToneGenerator: Delete Track: 0xb4928a80
09-07 15:30:49.697  7848  7848 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 15:30:49.698  7848  7848 V Avrcp   : make
09-07 15:30:49.698   315  2156 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 15:30:49.698  1035  1889 W Process : Unable to open /proc/8087/status
09-07 15:30:49.698   315  2156 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
,09-07 15:30:49.698   315  1269 V AudioPolicyService: AudioCommandThread() waking up
09-07 15:30:49.698   315  2156 V AudioFlinger: PlaybackThread::Track destructor
09-07 15:30:49.698   315  1269 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 15:30:49.698  7848  7848 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 15:30:49.698   315  2156 V AudioFlinger: removeClient_l() pid 7848, calling pid 315
09-07 15:30:49.698   315  1269 V AudioPolicyManager: releaseOutput() 2
,09-07 15:30:49.698  7848  7848 I bluedroid-qcom: get_profile_interface avrcp
09-07 15:30:49.698   315  1269 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 15:30:49.699  7848  8085 V AudioTrack: ~AudioTrack, releasing session id from 7848 on behalf of 7848
09-07 15:30:49.699   315  1396 V AudioFlinger: releasing 21 from 7848 for 7848
09-07 15:30:49.699   315  1396 V AudioFlinger:  decremented refcount to 0
09-07 15:30:49.699   315  1396 V AudioFlinger: purging stale effects
,09-07 15:30:49.708  7848  7848 V AudioManager: registerRemoteController: size of Media player list: 0
,09-07 15:30:49.710  7848  7848 E AudioManager: No RCC entry present to update
,09-07 15:30:49.710  7848  7848 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 15:30:49.713  7848  7848 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 15:30:49.715  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 15:30:49.715  7848  7848 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 15:30:49.720  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 15:30:49.852  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
,09-07 15:30:49.852  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
,09-07 15:30:49.958  1035  1889 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 15:30:49.981  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-07 15:30:49.988  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-07 15:30:49.989  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-07 15:30:49.989  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 15:30:49.990  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 15:30:49.991  7848  7848 I BluetoothA2dpServiceJni: classInitNative
09-07 15:30:49.991  7848  7848 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 15:30:49.991  7848  7848 D A2dpStateMachine: make
09-07 15:30:49.995  7848  7848 I bluedroid-qcom: get_profile_interface a2dp
09-07 15:30:49.995  7848  8097 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 15:30:49.998  7848  7848 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 15:30:49.998  7848  7848 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 15:30:49.999  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:50.001  7848  7848 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 15:30:50.007  7848  7848 D HidService: Received start request. Starting profile...
09-07 15:30:50.007  7848  7848 I bluedroid-qcom: get_profile_interface hidhost
09-07 15:30:50.007  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:50.008  7848  7848 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 15:30:50.010  7848  8096 D A2dpStateMachine: Enter Disconnected: -2
09-07 15:30:50.011  7848  7848 D HealthService: Received start request. Starting profile...
09-07 15:30:50.014  7848  7848 I bluedroid-qcom: get_profile_interface health
09-07 15:30:50.015  7848  7848 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,09-07 15:30:50.015  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:50.020  7848  7848 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 15:30:50.023  7848  7848 D PanService: Received start request. Starting profile...
09-07 15:30:50.023  7848  7848 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 15:30:50.023  7848  7848 I bluedroid-qcom: get_profile_interface pan
09-07 15:30:50.033  7848  7848 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 15:30:50.033  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
,09-07 15:30:50.035  7848  7848 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-07 15:30:50.044  7848  7848 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 15:30:50.045  7848  7848 D BtGatt.GattService: Received start request. Starting profile...
09-07 15:30:50.045  7848  7848 D BtGatt.GattService: start()
09-07 15:30:50.045  7848  7848 I bluedroid-qcom: get_profile_interface gatt
09-07 15:30:50.045  7848  7848 D BtGatt.AdvertiseManager: advertise manager created
09-07 15:30:50.056  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
,09-07 15:30:50.059  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:50.060  7848  7848 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 15:30:50.061  7848  7848 V BluetoothMapService: BluetoothMapBinder()
09-07 15:30:50.062  7848  7848 D BluetoothMapService: Received start request. Starting profile...
09-07 15:30:50.062  7848  7848 D BluetoothMapService: start()
09-07 15:30:50.065  7848  7848 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 15:30:50.065  7848  7848 D BluetoothMapEmailAppObserver: createReceiver()
09-07 15:30:50.067  7848  7848 D BluetoothMapEmailAppObserver: initObservers()
09-07 15:30:50.067  7848  7848 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-07 15:30:50.077  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
,09-07 15:30:50.077  7848  7848 D HeadsetStateMachine: Proxy object connected
,09-07 15:30:50.079  7848  7848 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 15:30:50.079  7848  7848 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 15:30:50.085  7848  8085 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 15:30:50.086  7848  8085 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 15:30:50.086  7848  8085 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 15:30:50.092  7848  7848 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:50.094  7848  7848 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:30:50.100  7848  7848 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:50.103  7848  7848 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:50.106  7848  7848 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 15:30:50.106  7848  7848 V PanService: [BTUI] SIM Extra State :ABSENT
09-07 15:30:50.110  7848  7848 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 15:30:50.113  7848  7848 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 15:30:50.114  7848  7848 V BluetoothMapService: Handler(): got msg=1
09-07 15:30:50.115  7848  8063 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 15:30:50.115  7848  8063 I bluedroid-qcom: enable
09-07 15:30:50.115  7848  7848 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:50.115  7848  7848 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:50.115  7848  7848 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:50.115  7848  8111 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 15:30:50.115  7848  8111 I bt-btu  : btu_task pending for preload complete event
09-07 15:30:50.115  7848  8063 I bt_hci_bdroid: init
09-07 15:30:50.116  7848  7848 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:50.116  7848  7848 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 15:30:50.117  7848  8063 I bt_vendor: bt-vendor : init
09-07 15:30:50.117  7848  8063 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 15:30:50.117  7848  8063 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 15:30:50.117  7848  8063 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 15:30:50.117  7848  8063 D bt_userial_mct: userial_init
09-07 15:30:50.118  7848  8063 D bt_hci_bdroid: set_power 1
09-07 15:30:50.118  7848  8063 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 15:30:50.118  7848  8063 I bt_vendor: Starting hciattach daemon
09-07 15:30:50.118  7848  8063 I bt_vendor: try to set true
09-07 15:30:50.108  8114  8114 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 15:30:50.108  8114  8114 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 15:30:50.143  8115  8115 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 15:30:50.278  8121  8121 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 15:30:50.299  8122  8122 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 15:30:50.342  8124  8124 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 15:30:50.355  8125  8125 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-07 15:30:50.377  8126  8126 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 15:30:50.400  8130  8130 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 15:30:50.433  8132  8132 I libmdmdetect: ESOC framework not supported
09-07 15:30:50.435  8132  8132 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 15:30:50.444  8132  8132 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-07 15:30:50.444  8132  8132 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 15:30:50.444  8132  8132 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 15:30:50.444  8132  8132 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 15:30:50.444  8132  8132 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 15:30:50.444  8132  8132 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 15:30:50.444  8132  8132 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 15:30:50.480  8132  8133 E QC-QMI  : qmi_client [8132] 15: failed to locate client data
09-07 15:30:50.481   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 15:30:50.481   478   478 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-07 15:30:50.517  8137  8137 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 15:30:50.533  8138  8138 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 15:30:50.573  7848  8063 I bt_vendor: bluetooth satus is on
09-07 15:30:50.573  7848  8063 D bt_hci_bdroid: preload
,09-07 15:30:50.575  7848  8113 D bt_userial_mct: userial_open(port:0)
09-07 15:30:50.576  7848  8113 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-07 15:30:50.579  7848  8113 I bt_vendor: Done intiailizing UART
09-07 15:30:50.580  7848  8113 I bt_vendor: Done intiailizing UART
09-07 15:30:50.580  7848  8113 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 15:30:50.580  7848  8113 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 15:30:50.580  7848  8111 I bt-btu  : btu_task received preload complete event
09-07 15:30:50.581  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 15:30:50.581  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 15:30:50.583  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-07 15:30:50.586  7848  8140 D bt_userial_mct: Entering userial_read_thread()
,09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 15:30:50.593  7848  8111 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 15:30:50.652  7848  8111 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-07 15:30:50.652  7848  8111 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
09-07 15:30:50.652  7848  8111 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,09-07 15:30:50.688  7848  8067 E bt-btif : Calling BTA_HhEnable
09-07 15:30:50.688  7848  8067 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 15:30:50.689  7848  8067 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 15:30:50.694  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-07 15:30:50.694  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,09-07 15:30:50.694  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 15:30:50.695  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 15:30:50.695  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 15:30:50.707  7848  8067 D BluetoothAdapterProperties: Name is: G3
,09-07 15:30:50.718  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 15:30:50.719  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 15:30:50.720  7848  8067 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:30:50.720  7848  8067 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:30:50.720  7848  8067 D bt_hci_bdroid: postload
09-07 15:30:50.720  7848  8113 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:50.722  7848  8111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 15:30:50.723  7848  8067 D bte_conf: Device ID record 1 : primary
09-07 15:30:50.723  7848  8067 D bte_conf:   vendorId            = 00c4
09-07 15:30:50.723  7848  8067 D bte_conf:   vendorIdSource      = 0001
09-07 15:30:50.723  7848  8067 D bte_conf:   product             = 13a1
09-07 15:30:50.723  7848  8067 D bte_conf:   version             = 1000
09-07 15:30:50.723  7848  8067 D bte_conf:   clientExecutableURL = 
09-07 15:30:50.723  7848  8067 D bte_conf:   serviceDescription  = 
09-07 15:30:50.723  7848  8067 D bte_conf:   documentationURL    = 
09-07 15:30:50.723  7848  8067 D bte_conf: bte_load_did_conf no section named DID2.
09-07 15:30:50.728  7848  8111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:50.728  7848  8111 W bt-smp  : Plain text(LSB ~ MSB) = d7 91 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:50.728  7848  8111 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 0e 55 bf fd 5c c7 c3 c9 8c 0b 2f 82 1b 83 f7 
,09-07 15:30:50.731  7848  8113 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:50.731  7848  8111 W bt-btm  : Stopping oneshot timer
09-07 15:30:50.731  7848  8113 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:50.732  7848  8063 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 15:30:50.732  7848  8063 D BluetoothAdapterProperties: ScanMode =  20
09-07 15:30:50.732  7848  8063 D BluetoothAdapterProperties: State =  11
09-07 15:30:50.718  8142  8142 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:50.736  7848  8063 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 15:30:50.736  7848  8063 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 15:30:50.737  7848  8063 D BluetoothAdapterProperties: Setting state to 12
09-07 15:30:50.737  7848  8063 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 15:30:50.737  7848  8067 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 15:30:50.738  7848  8067 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 15:30:50.728  8142  8142 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:50.746  1035  1117 D BluetoothManagerService: Message: 60
09-07 15:30:50.746  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 15:30:50.746  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-07 15:30:50.751  7848  8113 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 15:30:50.754  7848  8063 I BluetoothAdapterState: Entering On State
09-07 15:30:50.760  7848  8140 E bt_mct  : hci lib postload completed
,09-07 15:30:50.775  7848  8067 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:30:50.776  7848  8067 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-07 15:30:50.778  7848  8063 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 15:30:50.783  7848  8063 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 15:30:50.783  7848  8063 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-07 15:30:50.783  7848  8111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:50.783  7848  8111 W bt-smp  : Plain text(LSB ~ MSB) = 47 9a 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:50.783  7848  8111 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 be 69 96 ff 27 bc 8d 00 4b 7d f8 fe df 95 13 
09-07 15:30:50.784  7848  8111 W bt-btm  : Stopping oneshot timer
09-07 15:30:50.784  7848  8063 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 15:30:50.802  7848  8111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:50.802  7848  8111 W bt-smp  : Plain text(LSB ~ MSB) = 4b bb 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:50.802  7848  8111 W bt-smp  : Encrypted text(LSB ~ MSB) = 54 a9 3b b7 19 57 b9 64 79 05 0e fc 77 9a 34 44 
,09-07 15:30:50.805  7848  8063 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-07 15:30:50.805  7848  8111 W bt-btm  : Stopping oneshot timer
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:50.823  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:30:50.831  7848  8111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:50.831  7848  8111 W bt-smp  : Plain text(LSB ~ MSB) = 82 4d 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:50.831  7848  8111 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 35 b9 8d 0f 9d 61 91 50 4d 37 c4 14 a2 96 05 
09-07 15:30:50.832  7848  8111 W bt-btm  : Stopping oneshot timer
09-07 15:30:50.832  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:50.857  7023  7038 D BluetoothPan: onBluetoothStateChange on: true
09-07 15:30:50.857  7023  7038 D BluetoothPan: onBluetoothStateChange call bindService
,09-07 15:30:50.861  7848  8111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 15:30:50.861  7848  8111 W bt-smp  : Plain text(LSB ~ MSB) = 57 41 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 15:30:50.861  7848  8111 W bt-smp  : Encrypted text(LSB ~ MSB) = ef 9a 16 73 b7 85 af 30 82 17 4b d3 d2 75 e1 61 
09-07 15:30:50.862  7848  8111 W bt-btm  : Stopping oneshot timer
09-07 15:30:50.867  7023  7040 D BluetoothMap: onBluetoothStateChange: up=true
09-07 15:30:50.869  8159  8159 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-07 15:30:50.871  1852  2646 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 15:30:50.871  7023  7023 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:30:50.871  7023  7023 D PanProfile: Bluetooth service connected
,09-07 15:30:50.873  7023  7023 D BluetoothMap: Proxy object connected
09-07 15:30:50.873  7023  7023 D MapProfile: Bluetooth service connected
09-07 15:30:50.873  7023  7023 D BluetoothMap: getConnectedDevices()
09-07 15:30:50.874  7023  7040 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:50.874  7848  7864 V BluetoothMapService: getConnectedDevices()
09-07 15:30:50.875  1852  1852 D BluetoothHeadset: Proxy object connected
09-07 15:30:50.876  7023  7038 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 15:30:50.877  7023  7023 D BluetoothHeadset: Proxy object connected
09-07 15:30:50.877  7023  7023 D HeadsetProfile: Bluetooth service connected
09-07 15:30:50.878  1852  4437 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:50.880  1852  1852 D BluetoothHeadset: Proxy object connected
09-07 15:30:50.880  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:50.881  1852  1852 D BluetoothHeadset: Proxy object connected
09-07 15:30:50.882  7023  7040 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:30:50.883  7023  7038 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:30:50.887  7023  7023 D BluetoothInputDevice: Proxy object connected
09-07 15:30:50.887  7023  7023 D HidProfile: Bluetooth service connected
09-07 15:30:50.888  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 15:30:50.889  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:30:50.889  1035  1035 D BluetoothA2dp: Proxy object connected
09-07 15:30:50.889  7023  7023 D BluetoothA2dp: Proxy object connected
09-07 15:30:50.889  7023  7023 D A2dpProfile: Bluetooth service connected
09-07 15:30:50.890  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 15:30:50.890  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 15:30:50.891  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 15:30:50.894  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:50.894  1940  2135 D LGBluetoothAPIService: Message: 1
09-07 15:30:50.894  1940  2135 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 15:30:50.896  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:50.898  1035  1035 D BluetoothHeadset: Proxy object connected
,09-07 15:30:50.900  1940  2135 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-07 15:30:50.901  7848  7848 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:50.901  7848  7848 D BluetoothMapService: STATE_ON
09-07 15:30:50.902  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 15:30:50.902  1035  1117 D BluetoothManagerService: Message: 40
09-07 15:30:50.902  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 15:30:50.903  7848  7848 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 15:30:50.903  7848  7848 D LGBluetoothAPIServer: [BTUI] onBind()
09-07 15:30:50.904  7023  7023 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-07 15:30:50.904  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 15:30:50.904  1940  2135 D LGBluetoothAPIService: Message: 100
09-07 15:30:50.904  1940  2135 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 15:30:50.905  7023  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 15:30:50.910  7023  7023 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:30:50.920  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:50.920  7848  7848 V BluetoothPbapService: Pbap Service onCreate
09-07 15:30:50.920  7848  7848 V BluetoothPbapService: Starting PBAP service
09-07 15:30:50.921  7848  7848 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 15:30:50.921  7848  7848 V BluetoothMapService: Handler(): got msg=1
09-07 15:30:50.921  7848  7848 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 15:30:50.922  7848  7848 V BluetoothPbapService: Pbap Service onBind
09-07 15:30:50.923  7848  8169 D BluetoothMapMasInstance: MAS initSocket()
,09-07 15:30:50.923  7848  7848 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:50.923  7848  7848 V BluetoothPbapService: state: 12
09-07 15:30:50.923  7848  7848 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 15:30:50.923  7848  7848 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:50.923  7848  8169 D BluetoothMapMasInstance:   masId = 00
09-07 15:30:50.923  7848  8169 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 15:30:50.923  7848  8169 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 15:30:50.923  7848  8169 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 15:30:50.923  7848  7848 V BluetoothPbapReceiver: ***********state = 12
09-07 15:30:50.923  7023  7023 D BluetoothPbap: Proxy object connected
09-07 15:30:50.924  7023  7023 D PbapServerProfile: Bluetooth service connected
09-07 15:30:50.924  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:50.925  7848  7848 V BluetoothPbapService: Handler(): got msg=1
09-07 15:30:50.925  7848  7848 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 15:30:50.925  7848  8169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:50.926  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:30:50.927  7848  8171 V BluetoothPbapService: Pbap Service initSocket
09-07 15:30:50.927  2210  2210 D c       : Getting all permits...
09-07 15:30:50.927  2210  2210 D a       : Opening database...
09-07 15:30:50.927  1035  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:50.928  7848  8171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:50.930  7848  8171 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 15:30:50.930  7848  8169 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
09-07 15:30:50.930  7848  8067 D BluetoothAdapterProperties: Scan Mode:21
09-07 15:30:50.930  7848  8067 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 15:30:50.930  7848  8169 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 15:30:50.930  7848  8169 D BluetoothMapMasInstance: Accepting socket connection...
09-07 15:30:50.930  7848  8171 V BluetoothPbapService: Succeed to create listening socket 
09-07 15:30:50.930  7848  8171 V BluetoothPbapService: Accepting socket connection...
09-07 15:30:50.932  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:50.934  2210  2210 D a       : Opening database auth.proximity.permit_store...
09-07 15:30:50.935  2210  2210 D a       : Closing database...
,09-07 15:30:50.947  7023  7023 D BluetoothPermissionRequest: onReceive
,09-07 15:30:50.950  7023  7023 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 15:30:50.952  7023  7023 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 15:30:50.956  7848  7848 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 15:30:50.957  7848  7848 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 15:30:50.964  7848  7848 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 15:30:50.994  7848  7848 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 15:30:50.995  7848  7848 V BtOppService: onCreate
,09-07 15:30:51.000  7848  7848 V BluetoothOppNotification: send message
09-07 15:30:51.004  7848  7848 V BtOppService: Starting RfcommListener
09-07 15:30:51.019  7848  7848 D BluetoothOppPreference: Dumping Names:  
09-07 15:30:51.019  7848  7848 D BluetoothOppPreference: {}
09-07 15:30:51.019  7848  7848 D BluetoothOppPreference: Dumping Channels:  
09-07 15:30:51.019  7848  7848 D BluetoothOppPreference: {}
09-07 15:30:51.020  7848  7848 V BtOppService: onStartCommand
,09-07 15:30:51.024  7848  7848 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:51.024  7848  7848 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 15:30:51.025  7848  8177 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 15:30:51.027  7848  8177 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 15:30:51.028  7848  8174 V BtOppService: Deleted complete outbound shares, number =  0
09-07 15:30:51.028  7848  7848 V BluetoothOppNotification: new notify threadi!
09-07 15:30:51.029  7848  7848 V BluetoothOppNotification: send delay message
09-07 15:30:51.030  7848  7848 V BtOppService: start RfcommListener
09-07 15:30:51.032  7848  8174 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 15:30:51.033  7848  8174 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 15:30:51.033  7848  7848 V BtOppService: RfcommListener started
09-07 15:30:51.034  7848  8178 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-07 15:30:51.041  7848  8174 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bde52ae on behalf of 
09-07 15:30:51.042  7848  8177 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b6e684f on behalf of 
09-07 15:30:51.043  7848  8179 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 15:30:51.045  1035  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:51.046  7848  8177 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-07 15:30:51.047  7848  8179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:51.048  7848  8179 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-07 15:30:51.050  7848  8179 V BtOppRfcommListener: Started RFCOMM listener....
09-07 15:30:51.050  7848  8179 I BtOppRfcommListener: Accept thread started.
09-07 15:30:51.050  7848  8179 V BtOppRfcommListener: Accepting connection...
09-07 15:30:51.050  7848  8178 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1de4abdc on behalf of 
09-07 15:30:51.052  7848  8178 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 15:30:51.053  7848  8178 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:51.055  7848  8178 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ee264e5 on behalf of 
09-07 15:30:51.056  7848  8178 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 15:30:51.059  7848  8178 V BluetoothOppNotification: outbound notification was removed.
,09-07 15:30:51.059  7848  8178 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:51.062  7848  8178 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f40ebba on behalf of 
09-07 15:30:51.063  7848  8178 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 15:30:51.064  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:51.064  7848  7848 V BluetoothFtpService: Ftp Service onCreate
09-07 15:30:51.064  7848  7848 I BluetoothFtpService: Ftp Service onCreate
09-07 15:30:51.064  7848  7848 V BluetoothFtpService: Ftp Service onStartCommand
09-07 15:30:51.064  7848  7848 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:51.065  7848  7848 V BluetoothFtpService: Starting Listening on sockets
09-07 15:30:51.065  7848  7848 V BtOppService: ContentObserver received notification
09-07 15:30:51.065  7848  7848 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 15:30:51.066  7848  7848 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 15:30:51.066  7848  7848 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 15:30:51.066  7848  8178 V BluetoothOppNotification: inbound notification was removed.
09-07 15:30:51.066  7848  7848 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:51.066  7848  7848 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-07 15:30:51.066  7848  8178 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 15:30:51.066  7848  7848 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 15:30:51.067  7848  8180 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 15:30:51.067  7848  8180 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 15:30:51.068  7848  7848 V BtOppService: ContentObserver received notification
09-07 15:30:51.068  7848  7848 V BluetoothFtpService: Handler(): got msg=1
09-07 15:30:51.069  7848  7848 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 15:30:51.069  7848  7848 V BluetoothFtpService: Ftp Service initSocket
09-07 15:30:51.070  7848  8178 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12fea9c8 on behalf of 
09-07 15:30:51.071  7848  8180 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6d96a61 on behalf of 
,09-07 15:30:51.074  7848  8180 V BluetoothOppNotification: update too frequent, put in queue
09-07 15:30:51.075  7848  8180 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 15:30:51.076  7848  8180 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 15:30:51.077  7848  8180 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11020986 on behalf of 
09-07 15:30:51.079  7848  8180 V BluetoothOppNotification: update too frequent, put in queue
09-07 15:30:51.080  7848  8180 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 15:30:51.083  1035  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:51.084  7848  7848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:30:51.085  7848  7848 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-07 15:30:51.086  7848  7848 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 15:30:51.089  7848  8181 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 15:30:51.114  7848  7848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e2ff9dd
09-07 15:30:51.114  7848  7848 V BluetoothSapService: Sap Service onCreate
09-07 15:30:51.116  7848  7848 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:30:51.116  7848  7848 V BluetoothSapService: state: 12
09-07 15:30:51.116  7848  7848 V BluetoothSapService: Starting SAP server process
,09-07 15:30:51.119  7848  7848 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 15:30:51.108  8182  8182 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:51.108  8182  8182 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:51.122  7848  8183 V BluetoothSapService: Sap Service initRfcommSocket
09-07 15:30:51.122  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:51.123  7848  8183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:30:51.125  7848  8183 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-07 15:30:51.126  7848  8183 V BluetoothSapService: Succeed to create listening socket 
09-07 15:30:51.126  7848  8183 V BluetoothSapService: Accepting socket connection...
,09-07 15:30:51.142  8182  8182 V BT_SAP  : Event pipe created
09-07 15:30:51.142  8182  8182 V BT_SAP  : create_server_socket qcom.sap.server
09-07 15:30:51.142  8182  8182 V BT_SAP  : created socket fd 6
,09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:51.544  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:30:51.558  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:51.559  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:51.559  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a2e7867 added. We now have 8 listener(s)
09-07 15:30:51.559  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:51.564  1035  1973 D WifiServiceImplEx: setWifiEnabled: false pid=6904, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 15:30:51.564  1035  1973 D WifiService: setWifiEnabled: false pid=6904, uid=10118
09-07 15:30:51.564  1035  1973 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:30:51.571  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:51.572  1035  1889 D WifiServiceImplEx: setWifiEnabled: true pid=6904, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 15:30:51.573  1035  1889 D WifiService: setWifiEnabled: true pid=6904, uid=10118
09-07 15:30:51.573  1035  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:30:51.590  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-07 15:30:51.590  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 15:30:51.590  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-07 15:30:51.591  1035  1432 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 15:30:51.591  1035  1432 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-07 15:30:51.594  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 15:30:51.594  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 15:30:51.594  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 15:30:51.594  1035  1432 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 15:30:51.594  1035  1432 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 15:30:51.595  1035  1432 E WifiHW  : unknown target_country: EU , set to default
09-07 15:30:51.595  1035  1432 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 15:30:51.595  1035  1432 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 15:30:51.595  1035  1432 I WifiUtil: gEnableBmps=1
09-07 15:30:52.031  7848  7848 V BluetoothOppNotification: new notify threadi!
09-07 15:30:52.032  7848  7848 V BluetoothOppNotification: send delay message
,09-07 15:30:52.042  7848  8202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 15:30:52.045  7848  8202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7653812 on behalf of 
09-07 15:30:52.048  7848  8202 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-07 15:30:52.053  7848  8202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:52.056  7848  8202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d1a8be3 on behalf of 
09-07 15:30:52.056  7848  8202 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 15:30:52.059  7848  8202 V BluetoothOppNotification: outbound notification was removed.
09-07 15:30:52.059  7848  8202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 15:30:52.060  7848  8202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f7ee9e0 on behalf of 
,09-07 15:30:52.063  7848  8202 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 15:30:52.065  7848  8202 V BluetoothOppNotification: inbound notification was removed.
09-07 15:30:52.065  7848  8202 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 15:30:52.066  7848  8202 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@178c0499 on behalf of 
09-07 15:30:52.157   310   893 D SoftapController: Softap fwReload - Ok
,09-07 15:30:52.250  1035  1432 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (651ms)
,09-07 15:30:52.273   310   893 D CommandListener: Setting iface cfg
09-07 15:30:52.274   310   893 D CommandListener: Trying to bring down wlan0
,09-07 15:30:52.277  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:30:52.277  1035  1117 D Tethering: InitialState.processMessage what=4
09-07 15:30:52.280  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:30:52.280   310   893 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:30:52.284  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 15:30:52.285  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 15:30:52.285  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 15:30:52.285  7023  7023 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 15:30:52.285  1035  1432 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-07 15:30:52.287  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 15:30:52.287  7023  7023 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 15:30:52.288  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 15:30:52.288  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 15:30:52.288  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 15:30:52.288  7023  7023 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 15:30:52.288  7023  7023 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 15:30:52.288  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:52.288  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:52.288  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:52.278  8219  8219 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:52.278  8219  8219 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 15:30:52.298  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:52.299  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 15:30:52.302  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 15:30:52.292  1035  1432 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 15:30:52.302  1035  1432 D WifiMonitor: connecting to supplicant
09-07 15:30:52.304  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 15:30:52.304  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 15:30:52.304  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 15:30:52.304  7023  7023 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 15:30:52.305  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 15:30:52.308  7023  7023 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 15:30:52.308  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 15:30:52.308  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 15:30:52.308  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 15:30:52.309  7023  7023 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 15:30:52.309  7023  7023 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 15:30:52.320  8219  8219 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 15:30:52.346  1035  1575 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8222 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-07 15:30:52.353  8219  8219 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 15:30:52.353  8219  8219 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-07 15:30:52.424  8219  8219 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 15:30:52.480  1035  2009 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8244 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 15:30:52.486  8219  8219 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-07 15:30:52.487  8222  8242 W FormManager: Network not available. Please check & try again.
09-07 15:30:52.493  8219  8219 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 15:30:52.495  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-07 15:30:52.495  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-07 15:30:52.496  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 15:30:52.497  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 15:30:52.497  1035  1432 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 15:30:52.497  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 15:30:52.497  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 15:30:52.497  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 15:30:52.497  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:52.498  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:52.498  8222  8243 V FormManager: Network unavailable.
09-07 15:30:52.499  1035  1432 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:52.499  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:52.500  1035  1432 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 15:30:52.500  1035  1432 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 15:30:52.500  8222  8243 V FormManager: Network unavailable.
09-07 15:30:52.501  1035  1432 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 15:30:52.503  1035  1432 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 15:30:52.503  1035  1432 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-07 15:30:52.505  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.505  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.505  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.505  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.505  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 15:30:52.505  1035  1432 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 15:30:52.505  1035  1432 E WifiStateMachine: useWiFiOffloading() : false
09-07 15:30:52.505  1035  1432 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 15:30:52.508  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:52.509  1940  1940 D WfdService: Waiting for WifiP2p enabling
09-07 15:30:52.511  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 15:30:52.511  1035  1444 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 15:30:52.512  1035  1432 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 15:30:52.512  1035  1432 D WifiNative-wlan0: SET update_config 1: returned true
09-07 15:30:52.512  1035  1432 D WifiConfigStore: Loading config and enabling all networks 
09-07 15:30:52.512  1035  1432 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-07 15:30:52.513  1035  1432 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:52.517  6904  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:52.520  1035  1432 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-07 15:30:52.520  6904  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:52.530  1035  1432 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 15:30:52.530  1035  1432 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-07 15:30:52.531  1035  1432 D WifiStateMachine: enableVerboseLogging : level 2
09-07 15:30:52.531  1035  1432 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 15:30:52.532  1035  1432 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 15:30:52.532  1035  1432 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 15:30:52.532  1035  1432 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 15:30:52.532  1035  1432 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 15:30:52.533  1035  1432 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 15:30:52.533  1035  1432 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 15:30:52.533  1035  1432 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 15:30:52.533  1035  1432 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 15:30:52.533  1035  1432 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 15:30:52.534  1035  1432 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 15:30:52.534  1035  1432 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 15:30:52.534  1035  1432 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 15:30:52.534  1035  1432 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-07 15:30:52.537  1940  1940 D WfdsService: Supplicant Connection state is changed : true
09-07 15:30:52.537  1940  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 15:30:52.537  1940  2330 D WfdsService: Set the WFDS Monitor: true
09-07 15:30:52.538  1940  2330 D WfdsMonitor: WfdsMonitorThread create
09-07 15:30:52.538  1035  1432 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 15:30:52.538  1035  1432 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 15:30:52.538  1940  2330 D WfdsMonitor: WFDS Monitor is created and started
09-07 15:30:52.538  1940  2330 D WfdsService: WiFi: Supplicant connection re-established
09-07 15:30:52.538  1035  1432 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 15:30:52.538  1035  1432 D WifiNative-HAL: Setting external_sim to 1
09-07 15:30:52.538  1035  1432 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 15:30:52.539  1940  8263 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 15:30:52.539  1035  1432 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 15:30:52.539  1035  1432 I WifiNative-HAL: startHal
09-07 15:30:52.539  1035  1432 D wifi    : setting scan oui 0xaf69f020
09-07 15:30:52.539  1035  1432 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 15:30:52.540  1035  1432 I WifiNative-HAL: startHal
09-07 15:30:52.540  1035  1432 D wifi    : setting scan oui 0xaf69f020
09-07 15:30:52.540  1035  1432 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 15:30:52.540  1940  8263 E CtrlSupplicant: Succeed to open control connection
09-07 15:30:52.541  1035  1432 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 15:30:52.541  1940  8263 E CtrlSupplicant: Succeed to open monitor connection
09-07 15:30:52.541  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 15:30:52.541  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 15:30:52.541  1940  8263 D WfdsMonitor: Supplicant connection established
09-07 15:30:52.541  1940  2330 D WfdsService: Connected to the supplicant for wfds
09-07 15:30:52.541  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 15:30:52.542  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 15:30:52.543  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 15:30:52.543  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 15:30:52.543  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 15:30:52.543  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 15:30:52.544  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 15:30:52.544  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 15:30:52.544  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 15:30:52.544  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 15:30:52.544  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 15:30:52.544  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 15:30:52.545  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 15:30:52.545  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 15:30:52.545  8219  8219 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-07 15:30:52.546  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 15:30:52.546  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 15:30:52.546  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 15:30:52.546  1035  1432 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 15:30:52.547  1035  1432 E WifiNative: : [194,009,390 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 15:30:52.547  1035  1432 D WifiNative-wlan0: doBoolean: RECONNECT
,09-07 15:30:52.550  1035  1432 D WifiNative-wlan0: RECONNECT: returned true
09-07 15:30:52.550  1035  1432 D WifiNative-wlan0: doString: [STATUS]
09-07 15:30:52.551  1035  1432 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 15:30:52.551  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 15:30:52.551  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
09-07 15:30:52.551  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.552  1035  1432 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 15:30:52.553  1035  1432 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 15:30:52.553   310   893 D CommandListener: Setting iface cfg
09-07 15:30:52.553   310   893 D CommandListener: Trying to bring up p2p0
09-07 15:30:52.553  1035  1432 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 15:30:52.553  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 15:30:52.553  1035  1390 D LGWifiP2pService: P2pEnablingState
09-07 15:30:52.553  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.553  1035  1390 D LGWifiP2pService: P2p socket connection successful
09-07 15:30:52.553  1035  1390 D LGWifiP2pService: P2pEnabledState
09-07 15:30:52.553  1035  1432 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 15:30:52.554  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 15:30:52.554  1035  1432 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 15:30:52.554  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 15:30:52.554  1035  1432 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 15:30:52.554  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 15:30:52.555  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 15:30:52.555  1035  1432 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 15:30:52.555  1035  1432 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 15:30:52.555  8219  8219 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 15:30:52.555  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-07 15:30:52.555  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 15:30:52.555  1035  1390 D LGWifiP2pService: before postfix = G3
09-07 15:30:52.555  1035  1390 D WifiServerServiceExt: postfix byte check : 2
09-07 15:30:52.555  1035  1390 D LGWifiP2pService: after postfix = G3
09-07 15:30:52.555  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 15:30:52.555  1035  1432 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 15:30:52.556  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 15:30:52.556  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 15:30:52.556  1035  1432 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 15:30:52.556  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 15:30:52.556  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 15:30:52.556  1035  1432 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 15:30:52.556  1035  1432 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 15:30:52.556  8219  8219 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 15:30:52.557  1035  1432 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 15:30:52.557  1035  1432 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 15:30:52.557  1035  1432 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 15:30:52.558  1035  1432 D WifiNative-wlan0: doBoolean: D,RIVER COUNTRY CZ
09-07 15:30:52.558  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 15:30:52.558  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 15:30:52.558  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 15:30:52.558  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 15:30:52.558  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 15:30:52.558  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 15:30:52.559  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 15:30:52.559  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-07 15:30:52.559  1940  1940 D WfdsService: WifiP2pState is changed : true
09-07 15:30:52.559  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 15:30:52.559  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.559  1035  1556 I WifiNative-HAL: startHal
09-07 15:30:52.559  8219  8219 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.559  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 15:30:52.559  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.559  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.559  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.560  8219  8219 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 15:30:52.560  8219  8219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-07 15:30:52.560  8219  8219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.561  7876  7876 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.561  1035  1557 D RttService: DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.561  1940  2330 D WfdsService: Receive the WFDS_ENABLE Method
09-07 15:30:52.561  1940  2330 D WfdsService: Set the WFDS Monitor: true
09-07 15:30:52.561  1940  2330 D WfdsService: Connected to the supplicant for wfds
09-07 15:30:52.561  1940  2330 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 15:30:52.561  8219  8219 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,09-07 15:30:52.562  1940  2330 D WfdsService: selectPreferredScanChannel [36]
09-07 15:30:52.562  1940  2330 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 15:30:52.562  1035  8260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.562  1035  8260 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.562  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-07 15:30:52.562  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.562  1035  8260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.562  1035  8260 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.562  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.562  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.564  1035  1432 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 15:30:52.564  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf69f020
09-07 15:30:52.564  1035  1556 D wifi    : failed to get capabilities : -3
09-07 15:30:52.564  1035  1556 E WifiScanningService: could not get scan capabilities
09-07 15:30:52.564  1035  1432 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-07 15:30:52.565  1035  1432 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 15:30:52.566  1940  1940 D WfdsService: isConnected: false
09-07 15:30:52.566  1035  1432 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 15:30:52.566  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 15:30:52.566  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 15:30:52.566  8219  8219 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:52.566  1940  8263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.566  1940  8263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.566  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 15:30:52.566  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:52.566  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:52.566  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 15:30:52.567  1035  1432 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 15:30:52.567  1035  1432 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-07 15:30:52.567  1035  1432 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 15:30:52.567  1035  1432 D WifiNative-wlan0: doBoolean: SCAN
09-07 15:30:52.568  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 15:30:52.568  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-07 15:30:52.568  1035  1432 D WifiNative-wlan0: SCAN: returned false
09-07 15:30:52.569  1035  1432 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:52.569  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-07 15:30:52.569  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-07 15:30:52.569  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 15:30:52.570  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-07 15:30:52.570  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 15:30:52.570  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 15:30:52.570  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 15:30:52.570  1035  1432 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:52.571  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 15:30:52.571  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 15:30:52.571  1035  1432 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:52.571  1940  1940 D WfdsService: Update P2p Interface State: 3
09-07 15:30:52.571  1035  1432 E WifiStateMachine:  SupplicantStartedState P2P_CONN,ECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:52.571  1035  1432 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 15:30:52.572  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=194034  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 15:30:52.572  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=194035  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 15:30:52.573  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 15:30:52.573  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 15:30:52.575  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:52.575  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:52.575  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.575  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:52.576  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 15:30:52.576  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:52.576  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:52.576  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-07 15:30:52.581  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 15:30:52.581  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 15:30:52.581  1035  1390 D LGWifiP2pService: InactiveState
09-07 15:30:52.581  1035  1390 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.581  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.581  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 15:30:52.582  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 15:30:52.583  8219  8219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.583  1035  8260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 15:30:52.583  1035  8260 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.583  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.583  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 15:30:52.583  8219  8219 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 15:30:52.583  1940  8263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 15:30:52.583  8219  8219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.583  1035  8260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.583  1035  8260 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.583  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 15:30:52.583  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.583  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  8219  8219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  8260 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.584  1035  8260 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.584  1035  8260 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.584  1035  8260 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: Inacti,veState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.584  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.585  1940  8263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.585  1940  8263 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 15:30:52.585  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.585  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.585  1035  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:52.585  1035  1035 E WifiServerServiceExt: No p2p device connected
09-07 15:30:52.586  1940  2330 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 15:30:52.600  8244  8244 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:52.602  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:30:52.606  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:52.607  1035  2368 I ActivityManager: Killing 7309:com.lge.drmservice/u0a62 (adj 15): empty #17
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:30:52.608  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:30:52.609  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:30:52.612  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 15:30:52.613  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 15:30:52.614  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2ebc0811 Bundle[{}]
09-07 15:30:52.614  6904  6983 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 15:30:52.614  6904  6983 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 15:30:52.615  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 15:30:52.616  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 15:30:52.616  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 15:30:52.616  6904  6983 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 15:30:52.620  6904  6983 I System.out: Running OutgoingSocketThread
,09-07 15:30:52.622  6904  8266 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 906)
09-07 15:30:52.623  6904  8266 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54982
09-07 15:30:52.623  6904  8266 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-07 15:30:52.637  1035  1993 W libprocessgroup: failed to open /acct/uid_10062/pid_7309/cgroup.procs: No such file or directory
,09-07 15:30:52.650  8244  8244 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 15:30:52.652  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 15:30:52.654  8222  8268 W FormManager: Network not available. Please check & try again.
09-07 15:30:52.657  8222  8269 V FormManager: Network unavailable.
09-07 15:30:52.659  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:52.660  8222  8269 V FormManager: Network unavailable.
,09-07 15:30:52.674  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:52.675  4749  4749 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 15:30:52.677  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 15:30:52.679  4749  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 15:30:52.683  4749  8270 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 15:30:52.687  4749  8271 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 15:30:52.688  4749  8271 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 15:30:52.747  1035  1575 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8272 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-07 15:30:52.863  8272  8272 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 15:30:52.864  8272  8272 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-07 15:30:52.878  8272  8272 V [BNRBootReceiver]: Boot Receiver Return
,09-07 15:30:52.882  8272  8272 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 15:30:52.942  1035  1921 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8293 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 15:30:52.942  1035  1921 I ActivityManager: Killing 7334:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-07 15:30:52.968   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 25.626ms
,09-07 15:30:52.989   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 19.682ms
,09-07 15:30:53.008   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 17.333ms
,09-07 15:30:53.016  1035  1650 W libprocessgroup: failed to open /acct/uid_10085/pid_7334/cgroup.procs: No such file or directory
09-07 15:30:53.047  8293  8293 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 15:30:53.076  8293  8293 D PluginManager: init()
09-07 15:30:53.081  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 15:30:53.081  1035  8260 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 15:30:53.081  8219  8219 E wpa_supplicant: USIM:  scard_init function
09-07 15:30:53.081  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 15:30:53.082  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-07 15:30:53.082  1035  8260 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 15:30:53.082  8219  8219 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-07 15:30:53.083  1035  1432 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:53.084  1035  1432 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:53.085  1035  1432 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:53.085  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-07 15:30:53.085  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-07 15:30:53.086  1035  1432 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 15:30:53.087  1035  1432 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-07 15:30:53.105  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=194567  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 15:30:53.110  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.110  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.110  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 15:30:53.113  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.113  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 15:30:53.118  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=194580  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 15:30:53.121  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.122  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.122  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.122  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 15:30:53.124  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:53.124  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-07 15:30:53.127  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.127  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:53.131  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:53.202  8219  8219 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 15:30:53.206  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 15:30:53.206  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 15:30:53.206  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 15:30:53.206  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 15:30:53.207  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:53.207  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:53.208  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 15:30:53.210  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=194672  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 15:30:53.212  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=194673  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 15:30:53.212  8219  8219 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:30:53.212  8219  8219 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 15:30:53.213  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:53.213  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:53.214  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 15:30:53.214  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:30:53.214  1035  8260 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:30:53.214  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 15:30:53.214  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 15:30:53.214  1035  8260 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 15:30:53.214  1035  8260 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:53.214  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:53.216  1035  1432 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194678
,09-07 15:30:53.216  1035  1432 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194679
09-07 15:30:53.217  1035  1432 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194679
09-07 15:30:53.217  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194680
09-07 15:30:53.218  1035  1432 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194680
09-07 15:30:53.218  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=194681  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 15:30:53.220  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=194682  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 15:30:53.221  1035  1432 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:53.221  1035  1432 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:53.221  1035  1432 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:53.222  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:53.222  1035  1432 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 15:30:53.224  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.224  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.224  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 15:30:53.226  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.226  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:53.227  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.228  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.228  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.228  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 15:30:53.229  1035  1432 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=194691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 15:30:53.229  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.229  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:53.230  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=194692  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 15:30:53.230  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.230  1035  1432 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=194693
09-07 15:30:53.231  1035  1432 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=194693
09-07 15:30:53.231  1035  1432 D WifiNative-wlan0: doString: [STATUS]
09-07 15:30:53.232  1035  8260 D Wi,fiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 15:30:53.232  1035  8260 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 15:30:53.232  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:53.232  1035  1432 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 15:30:53.232  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 15:30:53.234  1035  1432 I WifiServiceExtension: setVHTCapabilityType  : false
,09-07 15:30:53.240  1035  1432 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-07 15:30:53.240  1035  1432 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-07 15:30:53.242  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.243  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.243  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 15:30:53.246  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.246  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.246  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 15:30:53.251  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.251  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 15:30:53.252  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.252  1035  1432 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 15:30:53.252  1035  1481 D ConnectivityService: Got NetworkAgent Messenger
09-07 15:30:53.253  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 15:30:53.253  1035  1481 D ConnectivityService: NetworkAgent connected
09-07 15:30:53.253  1035  1432 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:30:53.253  1035  1432 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 15:30:53.253  1035  1432 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 15:30:53.253  1035  1432 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 15:30:53.254  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.254  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:53.255  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.260  1035  1432 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 15:30:53.261  1035  1432 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:30:53.261  1035  1432 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 15:30:53.261  1035  1432 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 15:30:53.261  1035  1432 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 15:30:53.265  1035  1432 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-07 15:30:53.268   310   893 D CommandListener: Setting iface cfg
09-07 15:30:53.272  1035  1432 E WifiStateMachine: Start Dhcp Watchdog 3
,09-07 15:30:53.272  1035  8311 D DhcpStateMachine: StoppedState
09-07 15:30:53.272  1035  8311 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.272  1035  8311 D DhcpStateMachine: WaitBeforeStartState
09-07 15:30:53.273  1035  1432 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=194735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:53.273  1035  1432 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=194735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:53.274  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=194736  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:53.274  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:53.274  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 15:30:53.275  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:53.275  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 15:30:53.276  1035  1432 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=194738  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:53.277  1035  1432 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=194739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:53.277  1035  1432 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=194739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 15:30:53.278  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13970] from screen [on:0 period:81270750] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 15:30:53.279  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:81270751] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 15:30:53.279  1035  1432 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-07 15:30:53.284  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.287  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.287  1035  1481 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-07 15:30:53.287  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.287  1035  1432 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.288  1035  1432 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.288  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.288  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.289  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 15:30:53.289  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=172,0,0
09-07 15:30:53.290  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=172,0,0
09-07 15:30:53.290  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 15:30:53.290  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 15:30:53.290  1035  1432 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 15:30:53.291  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 15:30:53.291  1035  1432 D WifiNative-wlan0: SET ps 0: returned true
09-07 15:30:53.291  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 15:30:53.291  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 15:30:53.292  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 15:30:53.292  1035  1432 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 15:30:53.292  1035  1432 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 15:30:53.292  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27d0e676 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.292  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27d0e676 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.292  1035  1432 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 15:30:53.292  1035  8311 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.292  1035  8311 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 15:30:53.293   310   893 D CommandListener: Setting iface cfg
09-07 15:30:53.293   310   893 D CommandListener: Trying to bring up wlan0
,09-07 15:30:53.294  1035  1432 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 15:30:53.295  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:53.295  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 15:30:53.298  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 15:30:53.298  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 15:30:53.299  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.299  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.300  1035  1432 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.300  1035  1432 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.301  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.301  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 15:30:53.302  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 15:30:53.302  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 15:30:53.302  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 15:30:53.302  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 15:30:53.302  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.302  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.303  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 15:30:53.303  1035  1432 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 15:30:53.303  1035  1432 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 15:30:53.303  8219  8219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 15:30:53.304  1035  1432 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 15:30:53.304  1035  1432 D WifiNative-wlan0: doBoolean: SET ps 1
,09-07 15:30:53.320  1035  1432 D WifiNative-wlan0: SET ps 1: returned true
09-07 15:30:53.321  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-07 15:30:53.321  1035  1432 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 15:30:53.321  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 15:30:53.321  1035  1432 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 15:30:53.322  1035  1481 D ConnectivityService: ignoring duplicate network state non-change
09-07 15:30:53.326  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.326  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.326  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 15:30:53.326  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.326  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:53.327  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.328  1035  1481 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 15:30:53.328  1035  1481 D ConnectivityService: Adding iface wlan0 to network 102
09-07 15:30:53.330  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.331  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.331  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-07 15:30:53.333  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 15:30:53.333  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.334  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.334  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 15:30:53.334  1035  1432 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 15:30:53.335  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-07 15:30:53.336  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 15:30:53.341  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.341  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:30:53.341  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 15:30:53.347  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.347  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 15:30:53.348  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 15:30:53.349  1035  1481 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 15:30:53.349  1035  1481 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-07 15:30:53.350  1035  1481 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-07 15:30:53.351  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.351   310   893 E Netd    : netlink response contains error (File exists)
09-07 15:30:53.351  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 15:30:53.351  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.351  1035  1481 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-07 15:30:53.352  1035  1481 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 15:30:53.352  1035  1481 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-07 15:30:53.352  1035  1481 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-07 15:30:53.355  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:30:53.355  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 15:30:53.355  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.359  1035  1481 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-07 15:30:53.359  1035  1481 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 15:30:53.359  1035  1481 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 15:30:53.359  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.359  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 15:30:53.359  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:30:53.359  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 15:30:53.361  1035  1481 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 15:30:53.361  1035  1481 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:53.361  1035  1481 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:53.361  1035  1481 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 15:30:53.361  1035  1481 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.361  1035  1481 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 15:30:53.361  1035  1481 D ConnectivityService: currentScore = 0, newScore = 20
09-07 15:30:53.361  1035  1481 D ConnectivityService:    accepting network in place of null
09-07 15:30:53.362  1035  1481 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.362  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 15:30:53.362  1035  1432 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.362  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 15:30:53.362  1035  1432 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:53.362   310  8321 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 15:30:53.363  1035  1481 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 15:30:53.363  1035  1481 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 15:30:53.364  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:30:53.365  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 15:30:53.365  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 15:30:53.365  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 15:30:53.365  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-07 15:30:53.368  1035  1481 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:30:53.369  1035  1481 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 15:30:53.369  1035  1481 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 15:30:53.371  1035  1481 D ConnectivityService: validation of new default Network = false
09-07 15:30:53.371  1035  1481 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 15:30:53.371  1035  1481 D DSQN    : enableDataServiceNotify 
09-07 15:30:53.371  1035  1481 D DSQN    : start dsqn bin
09-07 15:30:53.379  1035  1481 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-07 15:30:53.380  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.368  8322  8322 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:53.368  8322  8322 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:53.380  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:53.380  1035  1481 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:53.380  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 15:30:53.383  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-07 15:30:53.392  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:53.392  8322  8322 E DSQN    : DSQN ssw
09-07 15:30:53.393  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.394  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.415   310  8321 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-07 15:30:53.460   310  8321 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-07 15:30:53.488   310   892 D LGDataListener: argv[0]=dsqncommand
,09-07 15:30:53.488   310   892 D LGDataListener: argv[1]=wlan0
09-07 15:30:53.488   310   892 D LGDataListener: argv[2]=1
09-07 15:30:53.488   310   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,09-07 15:30:53.490  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 15:30:53.490  1035  1115 D DSQN    : start to monitor internet connection
,09-07 15:30:53.496  1035  8311 D DhcpStateMachine: DHCPV4 request on wlan0
09-07 15:30:53.498  1035  8311 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 15:30:53.498  1035  8311 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 15:30:53.488  8328  8328 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 15:30:53.488  8328  8328 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 15:30:53.520  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 13:30:53 GMT], X-Android-Received-Millis=[1473255053519], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473255053486]}
09-07 15:30:53.520  8328  8328 I dhcpcd  : version 5.5.6 starting
09-07 15:30:53.520  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 15:30:53.520  1035  8310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 15:30:53.520  1035  1481 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,09-07 15:30:53.521  1035  1481 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 15:30:53.521  1035  1481 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:53.521  1035  1481 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:53.521  1035  1481 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 15:30:53.521  1035  1481 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-07 15:30:53.522  1035  1481 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-07 15:30:53.522  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.522  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:53.523  8328  8328 E dhcpcd  : get_duid: m
09-07 15:30:53.523  8328  8328 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 15:30:53.523  8328  8328 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-07 15:30:53.523  1035  1481 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:53.525  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 15:30:53.526  1035  1481 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.527  1035  1432 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.527  1035  1481 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 15:30:53.527  1035  1432 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:30:53.528  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:53.528  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-07 15:30:53.561  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 15:30:53.562  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.563  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 15:30:53.587  8328  8328 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 15:30:53.588  8328  8328 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 15:30:53.588  8328  8328 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 15:30:53.588  8328  8328 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-07 15:30:53.588  8328  8328 D dhcpcd  : wlan0: sending REQUEST (xid 0xc3c5d967), next in 3.47 seconds
,09-07 15:30:53.623  6904  6983 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 907)
09-07 15:30:53.623  6904  6983 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 907)
,09-07 15:30:53.627  6904  6983 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 912)
09-07 15:30:53.628  6904  6983 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 15:30:53.628  6904  6983 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 913)
09-07 15:30:53.631  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.631  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2522d614 added. We now have 2 listener(s)
09-07 15:30:53.631  1035  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.633  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.634  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.634  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.634  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.634  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14876ebd added. We now have 9 listener(s)
09-07 15:30:53.634  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.634  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:53.634  8328  8328 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-07 15:30:53.637  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:53.642  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:53.644  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.644  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:53.644  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:53.644  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a03403 added. We now have 3 listener(s)
09-07 15:30:53.644  1035  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.646  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.648  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.649  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.650  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.650  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.650  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.650  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32613f80 added. We now have 10 listener(s)
09-07 15:30:53.650  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.651  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:53.651  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.651  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:53.651  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.651  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.651  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.652  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.652  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2522d614 removed from the list
,09-07 15:30:53.652  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.652  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14876ebd removed from the list
09-07 15:30:53.652  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:53.652  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.653  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.653  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.654  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.654  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.654  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.654  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14876ebd not in the list
09-07 15:30:53.654  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.654  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.655  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.655  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.655  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.655  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32613f80 removed from the list
09-07 15:30:53.655  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.655  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.655  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.655  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.655  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a03403 removed from the list
09-07 15:30:53.656  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.656  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c139b9 added. We now have 2 listener(s)
09-07 15:30:53.656  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.658  8328  8328 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 15:30:53.658  8328  8328 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 15:30:53.659  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.659  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.659  8328  8328 D dhcpcd  : wla,n0: adding route to 192.168.1.0/24
09-07 15:30:53.659  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.659  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.659  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf221fe added. We now have 9 listener(s)
09-07 15:30:53.659  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.659  8328  8328 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 15:30:53.659  8328  8328 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 15:30:53.659  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:53.660  8328  8328 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 15:30:53.660  8328  8328 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 15:30:53.660  8328  8328 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-07 15:30:53.662  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:53.665  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:53.668  8293  8293 W ExternalStrings: load override strings
09-07 15:30:53.668  8293  8293 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:53.668  8293  8293 W Ex,ternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:53.668  8293  8293 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 15:30:53.670  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.671  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:53.671  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.671  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a5ad3ac added. We now have 3 listener(s)
09-07 15:30:53.676  1035  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.678  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.679  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.679  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.679  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.679  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1832b875 added. We now have 10 listener(s)
09-07 15:30:53.679  8293  8293 D StatusProvider: onCreate
09-07 15:30:53.679  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.679  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:53.679  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:53.679  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:53.679  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.679  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:53.686  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:30:53.687  1035  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.689  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.691  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.693  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 15:30:53.693  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:30:53.695  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:53.695  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.701  6904  6983 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 15:30:53.701  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.701  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:53.703  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:53.703  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.703  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:53.704  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.704  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.704  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.704  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.704  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c139b9 removed from the list
09-07 15:30:53.704  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.704  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf221fe removed from the list
09-07 15:30:53.704  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:53.704  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.704  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.704  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:53.706  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.707  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.707  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.707  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf221fe not in the list
09-07 15:30:53.707  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.707  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.707  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.708  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:53.708  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:53.708  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.708  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.708  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1832b875 removed from the list
09-07 15:30:53.708  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.708  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.708  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.708  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.708  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a5ad3ac removed from the list
09-07 15:30:53.709  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.709  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13777e98 added. We now have 2 listener(s)
09-07 15:30:53.710  1035  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.713  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.713  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.713  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.713  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.713  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340366f1 added. We now have 9 listener(s)
09-07 15:30:53.713  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.714  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:53.717  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:53.721  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:53.723  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.723  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:53.723  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.723  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb04957 added. We now have 3 listener(s)
09-07 15:30:53.725  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.727  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.729  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.731  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.731  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.731  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.731  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.731  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30b1ec44 added. We now have 10 listener(s)
09-07 15:30:53.731  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.731  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 15:30:53.732  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:53.732  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:53.732  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:53.732  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.732  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:53.736  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:30:53.736  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.739  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 15:30:53.740  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:30:53.741  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:53.741  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.743  6904  6983 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 15:30:53.743  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:53.743  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.743  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:53.744  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.744  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.744  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.744  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.744  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13777e98 removed from the list
09-07 15:30:53.744  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.744  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340366f1 removed from the list
09-07 15:30:53.744  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:53.744  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.744  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.744  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.745  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.745  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.745  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.745  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340366f1 not in the list
09-07 15:30:53.745  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.745  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.746  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.746  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:53.746  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:53.746  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.746  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.747  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30b1ec44 removed from the list
09-07 15:30:53.747  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.747  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.747  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.747  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.747  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb04957 removed from the list
09-07 15:30:53.747  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.747  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b8623f3 added. We now have 2 listener(s)
09-07 15:30:53.748  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.750  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.750  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.750  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.750  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.750  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180388b0 added. We now have 9 listener(s)
09-07 15:30:53.750  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.750  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:53.752  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:53.755  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:53.758  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.758  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:53.758  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.758  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce906ae added. We now have 3 listener(s)
09-07 15:30:53.758  1035  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.761  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.761  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.761  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.761  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.761  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37d50c4f added. We now have 10 listener(s)
09-07 15:30:53.761  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.761  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:53.761  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:53.761  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:53.761  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.761  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:53.762  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.764  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.765  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:30:53.765  1035  2368 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.769  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 15:30:53.772  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:30:53.775  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:53.775  8293  8293 V Signer  : override build config not found
09-07 15:30:53.776  8293  8293 D Signer  : value of property debug is false
09-07 15:30:53.776  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.777  6904  6983 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 15:30:53.784  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:53.785  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.785  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:53.785  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.785  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.785  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.785  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.785  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b8623f3 removed from the list
09-07 15:30:53.785  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.785  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180388b0 removed from the list
09-07 15:30:53.785  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:53.785  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.786  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.786  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.787  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.787  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.787  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:53.787  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180388b0 not in the list
09-07 15:30:53.787  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.787  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.788  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.788  6904  6983 D BluetoothLeScanner: could not find callback wrapper
09-07 15:30:53.788  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:53.788  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.788  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.788  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37d50c4f removed from the list
09-07 15:30:53.788  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.788  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.788  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.788  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.788  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce906ae removed from the list
09-07 15:30:53.789  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.789  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1842dfba added. We now have 2 listener(s)
09-07 15:30:53.789  1035  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.791  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.791  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.791  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.791  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.791  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38801e6b added. We now have 9 listener(s)
09-07 15:30:53.791  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.791  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:53.793  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:53.796  6904  6983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:53.798  6904  6983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:53.799  6904  6983 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:53.799  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:53.799  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286aee61 added. We now have 3 listener(s)
09-07 15:30:53.802  1035  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 15:30:53.803  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.805  6904  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:53.807  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 15:30:53.807  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:53.807  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:53.807  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:53.807  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2f3d86 added. We now have 10 listener(s)
09-07 15:30:53.807  6904  6983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:53.807  6904  6983 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:53.807  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.807  6904  6983 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:53.807  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.807  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.807  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:53.807  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:53.807  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1842dfba removed from the list
09-07 15:30:53.807  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.807  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38801e6b removed from the list
09-07 15:30:53.807  6904  6983 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:53.807  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.808  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.808  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.808  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.808  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.808  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.808  6904  6983 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38801e6b not in the list
09-07 15:30:53.808  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.808  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.809  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:53.809  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:53.809  6904  6983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:53.809  6904  6983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2f3d86 removed from the list
09-07 15:30:53.809  6904  6983 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:53.809  6904  6983 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:53.809  6904  6983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:53.809  6904  6983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 15:30:53.809  6904  6983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286aee61 removed from the list
09-07 15:30:53.810  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 15:30:53.810  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 15:30:53.810  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 15:30:53.810  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:53.810  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 15:30:53.811  6904  6983 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:53.813  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-07 15:30:53.813  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-07 15:30:53.813  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-07 15:30:53.813  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-07 15:30:53.813  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-07 15:30:53.814  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-07 15:30:53.814  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-07 15:30:53.814  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-07 15:30:53.814  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-07 15:30:53.814  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-07 15:30:53.815  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-07 15:30:53.815  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-07 15:30:53.815  8293  8293 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-07 15:30:53.821  6904  8350 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: My test thread name)
09-07 15:30:53.821  6904  8350 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: My test thread name)
09-07 15:30:53.821  6904  8350 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 15:30:53.824  6904  8352 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: My test thread name)
09-07 15:30:53.824  6904  8352 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: My test thread name)
09-07 15:30:53.824  6904  8352 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 15:30:53.825  6904  6983 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 15:30:53.825  6904  6983 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 15:30:53.825  6904  6983 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 15:30:53.826  6904  6983 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 15:30:53.826  6904  6983 D com.test.thalitest.ThaliTestRunner: Total duration: 22911 ms
09-07 15:30:53.827  6904  6983 I jxcore-log: *Native tests were executed*
09-07 15:30:53.827  6904  6983 I jxcore-log: 
09-07 15:30:53.827  6904  6983 I jxcore-log: Total number of executed tests:  80
09-07 15:30:53.827  6904  6983 I jxcore-log: 
09-07 15:30:53.827  6904  6983 I jxcore-log: Number of passed tests:  80
09-07 15:30:53.827  6904  6983 I jxcore-log: 
09-07 15:30:53.827  8293  8293 V LGMDMManager: Create singleton instance
09-07 15:30:53.827  6904  6983 I jxcore-log: Number of failed tests:  0
09-07 15:30:53.827  6904  6983 I jxcore-log: 
09-07 15:30:53.827  6904  6983 I jxcore-log: Number of ignored tests:  0
09-07 15:30:53.827  6904  6983 I jxcore-log: 
09-07 15:30:53.828  6904  6983 I jxcore-log: Total duration:  22911
09-07 15:30:53.828  6904  6983 I jxcore-log: 
09-07 15:30:53.828  6904  6983 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 15:30:53.828  6904  6983 I jxcore-,log: 
09-07 15:30:53.831  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.831  6904  6983 I jxcore-log: 
09-07 15:30:53.834  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.834  6904  6983 I jxcore-log: 
09-07 15:30:53.836  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.836  6904  6983 I jxcore-log: 
09-07 15:30:53.837  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.837  6904  6983 I jxcore-log: 
,09-07 15:30:53.837  6904  6904 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 15:30:53.838  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.838  6904  6983 I jxcore-log: 
09-07 15:30:53.839  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.839  6904  6983 I jxcore-log: 
09-07 15:30:53.842  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:53.842  6904  6983 I jxcore-log: 
09-07 15:30:53.844  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:53.844  6904  6983 I jxcore-log: 
09-07 15:30:53.846  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.846  6904  6983 I jxcore-log: 
09-07 15:30:53.847  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.847  6904  6983 I jxcore-log: 
09-07 15:30:53.848  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:30:53.848  6904  6983 I jxcore-log: 
09-07 15:30:53.850  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:53.850  6904  6983 I jxcore-log: 
09-07 15:30:53.851  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:53.851  6904  6983 I jxcore-log: 
09-07 15:30:53.852  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.852  6904  6983 I jxcore-log: 
09-07 15:30:53.852  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.852  6904  6983 I jxcore-log: 
09-07 15:30:53.853  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.853  6904  6983 I jxcore-log: 
09-07 15:30:53.854  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.854  6904  6983 I jxcore-log: 
09-07 15:30:53.855  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.855  6904  6983 I jxcore-log: 
09-07 15:30:53.856  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.856  6904  6983 I jxcore-log: 
09-07 15:30:53.857  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.857  6904  6983 I jxcore-log: 
09-07 15:30:53.857  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:53.857  6904  6983 I jxcore-log: 
09-07 15:30:53.858  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:30:53.858  6904  6983 I jxcore-log: 
09-07 15:30:53.859  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:30:53.859  6904  6983 I jxcore-log: 
,09-07 15:30:53.860  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.860  6904  6983 I jxcore-log: 
09-07 15:30:53.861  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.861  6904  6983 I jxcore-log: 
09-07 15:30:53.861  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.861  6904  6983 I jxcore-log: 
09-07 15:30:53.862  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.862  6904  6983 I jxcore-log: 
09-07 15:30:53.863  6904  6983 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:53.863  6904  6983 I jxcore-log: 
09-07 15:30:53.884  8293  8293 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-07 15:30:53.905  1035  8311 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-07 15:30:53.906  1035  8311 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 15:30:53.906  1035  8311 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 15:30:53.906  1035  8311 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 15:30:53.906  1035  8311 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 15:30:53.906  1035  8311 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 15:30:53.906  1035  8311 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 15:30:53.906  1035  8311 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 15:30:53.907  1035  8311 D DhcpStateMachine: RunningState
09-07 15:30:53.946  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:53.946  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-07 15:30:53.955  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:53.961  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:54.001  1035  1957 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8364 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-07 15:30:54.002  1035  1957 I ActivityManager: Killing 7361:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-07 15:30:54.123  8358  8358 D AndroidRuntime: 
09-07 15:30:54.123  8358  8358 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-07 15:30:54.125  8293  8360 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-07 15:30:54.126  8358  8358 D AndroidRuntime: CheckJNI is OFF
,09-07 15:30:54.253  8358  8358 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 15:30:54.286  1035  1993 W libprocessgroup: failed to open /acct/uid_10093/pid_7361/cgroup.procs: No such file or directory
,09-07 15:30:54.358  1035  1432 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-07 15:30:54.360  1035  1432 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:54.361  1035  1432 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:54.364  1035  1432 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:54.366  1035  1432 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:54.367  1035  1432 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 15:30:54.368  1035  1481 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-07 15:30:54.369  1035  1481 D ConnectivityService: identical MTU - not setting
09-07 15:30:54.369  1035  1481 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 15:30:54.369  1035  1481 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 15:30:54.369  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:30:54.370  1035  1481 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:54.371  1035  1481 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 15:30:54.372  1602  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-07 15:30:54.380  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-07 15:30:54.381  1035  1113 I ActivityManager: Killing 6904:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-07 15:30:54.413  8364  8364 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:54.422  1035  1650 I WindowState: WIN DEATH: Window{253b5989 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 15:30:54.422  1035  1471 D WifiService: Client connection lost with reason: 4
09-07 15:30:54.428  1035  1650 D InputDispatcher: Window went away: Window{253b5989 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 15:30:54.497  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{3a4dd13a u0 com.test.thalitest/.MainActivity t6}
,09-07 15:30:54.525   339   348 E GBMv2   : DFP En is all cleared set to be enabled
09-07 15:30:54.530  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-07 15:30:54.538  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{3a4dd13a u0 com.test.thalitest/.MainActivity t6 f}
09-07 15:30:54.539  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3a4dd13a u0 com.test.thalitest/.MainActivity t6 f}
,09-07 15:30:54.587  1035  1938 W ActivityManager: Spurious death for ProcessRecord{1a4d7d6 6904:com.test.thalitest/u0a118}, curProc for 6904: null
09-07 15:30:54.590  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-07 15:30:54.595  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-07 15:30:54.596  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ff217b3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 15:30:54.596  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,09-07 15:30:54.601  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-07 15:30:54.602  2032  2143 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-07 15:30:54.603  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-07 15:30:54.604  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{14bed170 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 15:30:54.609  8364  8364 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-07 15:30:54.610  1904  1904 D ActionManagerService: notifyUserLog: 1000003
,09-07 15:30:54.611  3793  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-07 15:30:54.611  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-07 15:30:54.620  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 15:30:54.620  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-07 15:30:54.622  5052  5052 I art     : Explicit concurrent mark sweep GC freed 8192(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 1.270ms total 67.670ms
09-07 15:30:54.625  2493  2606 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 15:30:54.629  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-07 15:30:54.630  3793  3793 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-07 15:30:54.633  7848  7848 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-07 15:30:54.634  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-07 15:30:54.638  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-07 15:30:54.668  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-07 15:30:54.677  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
09-07 15:30:54.701  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-07 15:30:54.703  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 15:30:54.705  1602  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 15:30:54.705  1602  1651 D KeyguardModel: createShortcutInfo...
,09-07 15:30:54.707  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-07 15:30:54.710  1602  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 15:30:54.710  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.711  4934  4934 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-07 15:30:54.711  4934  4934 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 15:30:54.712  4934  4934 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 15:30:54.712  4934  4934 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-07 15:30:54.712  4934  4934 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:30:54.712  4934  4934 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:30:54.712  4934  4934 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:54.712  4934  4934 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:54.712  4934  4934 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:54.712  4934  4934 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:54.712  4934  4934 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:54.712  4934  4934 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 15:30:54.716  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 15:30:54.717  1602  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:30:54.717  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 15:30:54.718  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 15:30:54.727  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 15:30:54.727  1602  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 15:30:54.729  1602  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 15:30:54.729  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.731  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-07 15:30:54.737  1904  1904 D ActionManagerService: notifyUserLog: 1000004
09-07 15:30:54.746  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,09-07 15:30:54.747  3793  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-07 15:30:54.748  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 15:30:54.750  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 15:30:54.750  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:54.751  8364  8364 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 15:30:54.751  8364  8364 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 15:30:54.751  8364  8364 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 15:30:54.752  8364  8364 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 15:30:54.752  8364  8364 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 15:30:54.753  8364  8364 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-07 15:30:54.756  1035  1035 I art     : Explicit concurrent mark sweep GC freed 79038(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 6.025ms total 182.489ms
09-07 15:30:54.756  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 15:30:54.756  1602  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 15:30:54.758  3793  4954 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: , display: false
09-07 15:30:54.761  2032  2032 I GBoardWebViewUtils: , animation: false }
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , display: false
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , animation: false }
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , create_time: 1472828323917
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , display: false
09-07 15:30:54.762  2032  2032 I GBoardWebViewUtils: , animation: false }
09-07 15:30:54.763  1602  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 15:30:54.763  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.763  1035  1123 I art     : WaitForGcToComplete blocked for 25.808ms for cause Explicit
09-07 15:30:54.768  1602  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:30:54.768  1602  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 15:30:54.768  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 15:30:54.768  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 15:30:54.768  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 15:30:54.768  2032  8409 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-07 15:30:54.769  1602  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 15:30:54.770  1602  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 15:30:54.770  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.777  8293  8360 D LgDataFeature: LgDataFeature() Constructor: none
09-07 15:30:54.777  8293  8360 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 15:30:54.787  8364  8364 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-07 15:30:54.789  1602  1602 D KeyguardModel: handleShortcutListChanged...
09-07 15:30:54.789  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-07 15:30:54.801  1602  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 15:30:54.801  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.802  1035  1889 V SIM_STK : Menu title from STK is T-Mobile
09-07 15:30:54.802  1035  1889 V SIM_STK : Menu title from STK is T-Mobile
09-07 15:30:54.804  1602  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 15:30:54.804  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.806  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 15:30:54.806  1602  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 15:30:54.806  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-07 15:30:54.808  1602  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 15:30:54.808  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.809  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 15:30:54.809  1602  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 15:30:54.811  1602  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 15:30:54.811  1602  1651 D KeyguardModel: createShortcutInfo...
09-07 15:30:54.812  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 15:30:54.812  1869  1869 D SplitUIManager: split_name #11 / not available #0
09-07 15:30:54.812  1602  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 15:30:54.812  1869  1869 D SplitUIService: removed split : 
09-07 15:30:54.813  1602  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 15:30:54.813  1602  1651 D KeyguardModel: createShortcutInfo...
,09-07 15:30:54.830  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:54.833  1602  1602 D KeyguardModel: handleShortcutListChanged...
09-07 15:30:54.833  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-07 15:30:54.844  1869  1869 D SplitUIManager: split_name #11 / not available #0
09-07 15:30:54.844  1869  1869 I SplitUIService: split app #11
,09-07 15:30:54.859  1035  1762 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 15:30:54.859  7848  7848 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 15:30:54.868  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 15:30:54.870  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-07 15:30:54.872  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:54.883  8364  8364 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 15:30:54.885  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 15:30:54.887  8364  8364 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-07 15:30:54.887  1035  1993 V SIM_STK : Menu title from STK is T-Mobile
09-07 15:30:54.891  8364  8364 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-07 15:30:54.892  7023  7023 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 15:30:54.900  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 15:30:54.900  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:54.909  8293  8360 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-07 15:30:54.913  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:54.919  1035  1035 D administrator: Handling package changes for user 0
09-07 15:30:54.920  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:54.925  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:54.925  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:54.926  8364  8364 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 15:30:54.929  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:54.929  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 15:30:54.933  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:54.938  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:54.943  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:54.943  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:54.943  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:54.945  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 15:30:54.945  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 15:30:54.945  7023  7023 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 15:30:54.945  7023  7023 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 15:30:54.945  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 15:30:54.945  7023  7023 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 15:30:54.946  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-07 15:30:54.946  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 15:30:54.946  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 15:30:54.946  7023  7023 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 15:30:54.946  7023  7023 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-07 15:30:54.946  7023  7023 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 15:30:54.948  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:54.948  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 15:30:54.954  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-07 15:30:54.958  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:54.964  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-07 15:30:54.966  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 15:30:54.966  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:54.968  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-07 15:30:54.969  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-07 15:30:54.970  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-07 15:30:54.971  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-07 15:30:54.987  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-07 15:30:54.987  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 15:30:54.996  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22426d15 u0 com.lge.launcher2/.Launcher t5} time:196470
09-07 15:30:54.997  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-07 15:30:54.997  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 15:30:54.998  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 15:30:54.999  2032  2282 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-07 15:30:54.999  2032  2282 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-07 15:30:54.999  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:54.999  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:54.999  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:55.003  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-07 15:30:55.004  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 15:30:55.004  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:55.005  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-07 15:30:55.005  8293  8360 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-07 15:30:55.011  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-07 15:30:55.012  2682  2682 D [Concierge]Service: onStartCommand(). Type : 8
09-07 15:30:55.012  2682  2682 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,09-07 15:30:55.013  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-07 15:30:55.015  2032  2032 D [Concierge]WidgetView: change position of spinner
09-07 15:30:55.016  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1473255055016
09-07 15:30:55.016  2682  2682 D [Concierge]Service: Update widget ID : 11
09-07 15:30:55.016  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 15:30:55.016  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 15:30:55.016  2682  2682 D [Concierge]Service: onStartCommand(). Type : 0
09-07 15:30:55.017  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 15:30:55.017  8293  8360 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-07 15:30:55.018  1035  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-07 15:30:55.019  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.019  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 15:30:55.024  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:55.032  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.036  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.037  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:55.037  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:55.039  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.039  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-07 15:30:55.048  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 525209594
09-07 15:30:55.048  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-07 15:30:55.048  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-07 15:30:55.049  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:55.051  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@24493d7a
09-07 15:30:55.051  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-07 15:30:55.052  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 15:30:55.052  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:55.054  1035  1123 I art     : Explicit concurrent mark sweep GC freed 11998(800KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.031ms total 281.955ms
09-07 15:30:55.057  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.058  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-07 15:30:55.058  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 15:30:55.059  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473254887287, New one : 1473255055016
09-07 15:30:55.059  2032  2032 D [Concierge]WidgetView: Unregister all receivers
09-07 15:30:55.059  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 15:30:55.062  1035  1112 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 15:30:55.065  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-07 15:30:55.066  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:55.067  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.067  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:55.067  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-07 15:30:55.067  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:55.068  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-07 15:30:55.069  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.069  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 15:30:55.069  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-07 15:30:55.071  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-07 15:30:55.072  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-07 15:30:55.072  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:55.073  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:55.075  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:55.079  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.083  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.083  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:55.083  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:55.089  8293  8361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 15:30:55.090  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.115  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-07 15:30:55.125  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-07 15:30:55.125  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-07 15:30:55.127  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 15:30:55.138  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:55.143  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.147  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.147  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:55.148  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c351b37 time:196623
09-07 15:30:55.150  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 15:30:55.152  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.159  8358  8358 D AndroidRuntime: Shutting down VM
09-07 15:30:55.170  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 15:30:55.174  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.178  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.178  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:55.179  8364  8364 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 15:30:55.180  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.182  8244  8244 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 15:30:55.185  8244  8244 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:55.187  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:55.191  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.194  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.195  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 15:30:55.195  8364  8364 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 15:30:55.196  8364  8364 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 15:30:55.196  8364  8364 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 15:30:55.199  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 15:30:55.202  8244  8244 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 15:30:55.202  8244  8244 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 15:30:55.203  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:30:55.205  7023  7023 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 15:30:55.209  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 15:30:55.214  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 15:30:55.226  7023  7023 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 15:30:55.229  8364  8364 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 15:30:55.230  8364  8364 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 15:30:55.230  8364  8364 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 15:30:55.231  8364  8364 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 15:30:55.231  8364  8364 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 15:30:55.233  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 15:30:55.234  8293  8293 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-07 15:30:55.238  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-07 15:30:55.244  2210  2210 I ConfigService: onCreate
09-07 15:30:55.244  2210  2210 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 15:30:55.247  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 15:30:55.252  2210  2210 I ConfigService: onBind returning update interface
09-07 15:30:55.252  2210  2210 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 15:30:55.253  2210  2210 I ConfigService: onBind returning config service
,09-07 15:30:55.270  2210  2210 I ConfigService: onDestroy
,09-07 15:30:55.272  1816  8426 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-07 15:30:55.277  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-07 15:30:55.308  5888  8431 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-07 15:30:55.311  1816  8433 I PeopleContactsSync: CP2 sync disabled
09-07 15:30:55.317  1816  5222 I Icing   : doRemovePackageData com.test.thalitest
,09-07 15:30:55.322  2032  2931 I GBoardtInterface: onReloaded()
09-07 15:30:55.325  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-07 15:30:55.326  3793  4954 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 15:30:55.329  3793  3808 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 15:30:55.335  2210  2228 I art     : Explicit concurrent mark sweep GC freed 8665(501KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 967us total 29.011ms
,09-07 15:30:55.337  1904  1904 D ActionManagerService: notifyUserLog: 1000001
09-07 15:30:55.339  3793  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 15:30:55.339  3793  4933 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-07 15:30:55.342  7198  7198 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-07 15:30:55.345  1904  1904 D ActionManagerService: notifyUserLog: 1000001
09-07 15:30:55.347  3793  3808 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-07 15:30:55.350  3793  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 15:30:55.351  3793  4933 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-07 15:30:55.351  3793  4933 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-07 15:30:55.351  3793  4933 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-07 15:30:55.352  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-07 15:30:55.352  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-07 15:30:55.353  1816  8432 W GmsApplication: Using Auth Proxy for data requests.
09-07 15:30:55.355  1816  8432 W GmsApplication: Using Auth Proxy for data requests.
09-07 15:30:55.356  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-07 15:30:55.356  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 15:30:55.358  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-07 15:30:55.358  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-07 15:30:55.361  2341  8435 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 15:30:55.400  1035  2031 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8436 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 15:30:55.440  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8455 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-07 15:30:55.469  8436  8436 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:30:55.470  8436  8436 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 15:30:55.471  8436  8436 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 15:30:55.471  8436  8436 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 15:30:55.494  1816  8428 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-07 15:30:55.495  1816  8428 E DriveAsyncService: disk I/O error (code 3850)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:55.495  1816  8428 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:30:55.501  1035  1993 I ActivityManager: Killing 7394:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:55.532  8436  8436, E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:55.532  8436  8436 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-07 15:30:55.533  8436  8436 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:55.533  8436  8436 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:55.533  8436  8436 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:55.533  8436  8436 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:55.533  8436  8436 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:55.533  8436  8436 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:55.533  8436  8436 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 15:30:55.537  8436  8436 E SQLi,teDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 15:30:55.537  8436  8436 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 15:30:55.538  8436  8436 D AndroidRuntime: Shutting down VM,
--------- beginning of crash
09-07 15:30:55.538  8436  8436 E AndroidRuntime: FATAL EXCEPTION: main
09-07 15:30:55.538  8436  8436 E AndroidRuntime: Process: com.lge.email, PID: 8436
09-07 15:30:55.538  8436  8436 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	,at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
,09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:30:55.538  8436  8436 E AndroidRuntime: 	
```
