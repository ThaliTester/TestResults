#### Test 82894682da71698_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 00:06:10.729  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
09-13 00:06:10.735  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,09-13 00:06:32.583  6838  6838 D AndroidRuntime: 
09-13 00:06:32.583  6838  6838 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 00:06:32.590  6838  6838 D AndroidRuntime: CheckJNI is OFF
09-13 00:06:32.791  6838  6838 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 00:06:32.802  1033  1050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 00:06:32.817  1940  2791 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 00:06:32.824  1033  1050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 00:06:32.825  1033  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{2c2d4dd2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 00:06:32.826  1033  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{2c2d4dd2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 00:06:32.827  1033  1050 D WindowStateEx: AppWindowTokenEx init.. 
09-13 00:06:32.828   338   354 E GBMv2   : DFP En is all cleared set to be enabled
09-13 00:06:32.857  1033  1050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6853 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 00:06:32.859  6838  6838 D AndroidRuntime: Shutting down VM
09-13 00:06:32.986  1033  1973 I art     : Explicit concurrent mark sweep GC freed 38299(1760KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.879ms total 88.677ms
09-13 00:06:33.018  1940  2791 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 00:06:33.018  1940  2791 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e821e6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 00:06:33.020  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 00:06:33.021  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{280eb327 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 00:06:33.060  6853  6853 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-13 00:06:33.169  6853  6853 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 00:06:33.180  6853  6853 I LibraryLoader: Loading: webviewchromium
09-13 00:06:33.183  6853  6853 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5192-5196)
,09-13 00:06:33.183  6853  6853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 00:06:33.202  6853  6853 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {18877e84}
,09-13 00:06:33.203  6853  6853 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 00:06:33.204  6853  6853 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 00:06:33.215  6853  6853 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 00:06:33.217  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 00:06:33.235  6853  6853 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 00:06:33.236  6853  6853 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 00:06:33.236  6853  6853 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 00:06:33.246   312   312 V AudioPolicyService: registerClient() client 0xb558ad00, uid 10118
,09-13 00:06:33.251  6853  6853 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 00:06:33.251  6853  6853 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 00:06:33.251  6853  6853 I Adreno-EGL: Build Date: 12/12/14 금
09-13 00:06:33.251  6853  6853 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 00:06:33.251  6853  6853 I Adreno-EGL: Remote Branch: 
09-13 00:06:33.251  6853  6853 I Adreno-EGL: Local Patches: 
09-13 00:06:33.251  6853  6853 I Adreno-EGL: Reconstruct Branch: 
09-13 00:06:33.251  1033  1109 D BluetoothManagerService: Message: 20
09-13 00:06:33.251  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@161a2bcc:true
09-13 00:06:33.328  6853  6899 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 00:06:33.338  6853  6853 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 00:06:33.363  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 00:06:33.369  6853  6853 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 00:06:33.373  6853  6853 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-13 00:06:33.377  6853  6853 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 00:06:33.377  6853  6853 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 00:06:33.395  6853  6853 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 00:06:33.403  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 00:06:33.403  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 00:06:33.451  6853  6914 D OpenGLRenderer: Render dirty regions requested: true
09-13 00:06:33.451  6853  6914 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 00:06:33.459  6853  6914 D OpenGLRenderer: Enabling debug mode 0
,09-13 00:06:33.468  6853  6853 D Atlas   : Validating map...
09-13 00:06:33.472  1033  1050 D SplitWindow: check instance of lgWin Window{22e2dca6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 00:06:33.511  6853  6909 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:06:33.511  6853  6909 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 00:06:33.648  1033  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +634ms (total +818ms)
,09-13 00:06:33.649  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f6c4ea3 u0 com.test.thalitest/.MainActivity t6} time:165663
09-13 00:06:33.656  6853  6853 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@176fa723 time:165670
09-13 00:06:33.765  6853  6853 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 00:06:33.765  6853  6853 I chromium: 
,09-13 00:06:33.796  6853  6853 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 00:06:33.870  6853  6909 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 00:06:33.870  6853  6909 I chromium: 
,09-13 00:06:34.055  6853  6925 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435051008
,09-13 00:06:34.071  6853  6925 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 00:06:34.071  6853  6925 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 00:06:34.071  6853  6925 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 00:06:34.071  6853  6925 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 00:06:34.071  6853  6925 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 00:06:34.073  6853  6925 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@395b5277 added. We now have 1 listener(s)
,09-13 00:06:34.083  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:34.086  6853  6925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-13 00:06:34.089  6853  6925 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:06:34.091  6853  6925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:34.091  6853  6925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 00:06:34.099  6853  6925 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93fda02 added. We now have 1 listener(s)
,09-13 00:06:34.100  6853  6925 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:34.105  1033  1423 D WifiService: New client listening to asynchronous messages
09-13 00:06:34.110  6853  6925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:06:34.110  6853  6925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 00:06:34.112  6853  6925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 00:06:34.112  6853  6925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-13 00:06:34.112  6853  6925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 00:06:34.116  6853  6925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:34.117  1033  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:34.117  6853  6925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 00:06:34.134  6853  6925 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:34.134  6853  6925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:34.135  6853  6925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 00:06:34.135  6853  6925 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:34.138  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:34.140  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:34.141  6853  6925 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 00:06:34.178  6853  6853 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 00:06:34.800   338   356 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 00:06:34.800   338   356 E GBMv2   : Set value is all cleared set the max
09-13 00:06:34.800   338   356 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 00:06:35.005  6853  6931 W jxcore-log: Initializing JXcore engine
09-13 00:06:35.005  6853  6931 W jxcore-log: JXcore engine is ready
,09-13 00:06:35.036  6931  6931 W Thread-807: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8650]" dev="sockfs" ino=8650 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 00:06:35.036  6931  6931 W Thread-807: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-13 00:06:35.036  6931  6931 W Thread-807: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7585]" dev="sockfs" ino=7585 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 00:06:35.036  6931  6931 W Thread-807: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 00:06:35.036  6931  6931 W Thread-807: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33092]" dev="sockfs" ino=33092 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-13 00:06:35.067  6853  6931 W jxcore-log: Starting JXcore engine
,09-13 00:06:35.247  6853  6931 W jxcore-log: Platform android
09-13 00:06:35.247  6853  6931 W jxcore-log: 
09-13 00:06:35.248  6853  6931 W jxcore-log: Process ARCH arm
09-13 00:06:35.248  6853  6931 W jxcore-log: 
,09-13 00:06:35.661  6853  6931 I jxcore-log: JXcore Cordova bridge is ready!
09-13 00:06:35.661  6853  6931 I jxcore-log: 
09-13 00:06:35.662  6853  6931 W jxcore-log: JXcore engine is started
,09-13 00:06:35.672  6853  6925 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 00:06:35.677  6853  6853 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 00:06:46.534  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 00:06:46.534  6853  6931 I jxcore-log: 
,09-13 00:06:46.537  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 00:06:46.537  6853  6931 I jxcore-log: 
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:46.541  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:46.544  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:46.547  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 00:06:46.547  6853  6931 I jxcore-log: 
09-13 00:06:46.548  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 00:06:46.548  6853  6931 I jxcore-log: 
,09-13 00:06:47.049  6853  6931 D executeNativeTests: Running unit tests
,09-13 00:06:47.130  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:47.130  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 added. We now have 2 listener(s)
09-13 00:06:47.131  1033  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.133  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:06:47.133  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:47.133  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:47.133  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-13 00:06:47.133  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 added. We now have 2 listener(s)
,09-13 00:06:47.133  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:47.133  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:06:47.136  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:47.139  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.140  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.140  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:47.141  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.142  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.145  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:06:47.146  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:06:47.146  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:06:47.147  6853  6931 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 00:06:47.148  6853  6931 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 00:06:47.148  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:06:47.148  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:06:47.148  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:06:47.149  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.150  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.150  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.150  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.150  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.151  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:47.151  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:47.151  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 removed from the list,
09-13 00:06:47.151  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:47.151  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 removed from the list
,09-13 00:06:47.151  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 00:06:47.151  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.152  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.152  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.153  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.153  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.153  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.153  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.154  6853  6931 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 00:06:47.155  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.155  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.155  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.155  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:47.155  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.155  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.155  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.155  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.155  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.155  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.155  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.155  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.155  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.155  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.156  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:47.156  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.156  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.156  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.161  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 00:06:47.161  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 00:06:47.162  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 00:06:47.162  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.162  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.162  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.163  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.163  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.163  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.163  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.163  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.163  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.163  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.163  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.163  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.163  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.163  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.164  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.164  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.164  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.164  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.165  6853  6931 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 00:06:47.167  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:47.169  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.169  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.170  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:47.171  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.171  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.172  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:47.172  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:47.172  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:06:47.172  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.172  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:06:47.174  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:06:47.175  1033  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.179  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:06:47.183  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 00:06:47.185  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 00:06:47.185  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:06:47.185  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:47.186  6853  6931 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 00:06:47.187  6853  6931 I io.jxcore.node.ConnectionHelper: start: OK
09-13 00:06:47.189  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.189  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.189  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.189  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.189  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.189  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:47.189  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.189  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.189  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.189  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.189  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.190  6853  6931 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 00:06:47.191  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:47.193  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.194  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.194  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:47.195  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.196  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:47.196  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:47.196  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:06:47.196  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.196  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.196  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:06:47.199  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:06:47.199  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:47.200  6853  6931 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 00:06:47.200  6853  6931 I io.jxcore.node.ConnectionHelper: start: OK
09-13 00:06:47.201  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.201  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.201  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.202  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.202  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.202  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:47.202  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.202  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.202  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.202  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.202  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:47.202  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.202  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.203  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.203  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.204  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.204  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.204  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.204  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.205  6853  6931 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 00:06:47.205  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:47.208  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.208  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.208  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:47.209  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.210  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:47.210  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:47.210  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:06:47.210  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.210  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:06:47.211  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.213  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:06:47.213  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:47.214  6853  6931 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 00:06:47.214  6853  6931 I io.jxcore.node.ConnectionHelper: start: OK
09-13 00:06:47.214  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.214  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.214  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.215  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.215  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.215  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.215  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.215  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.215  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:47.215  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.215  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.215  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.215  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.215  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.216  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.216  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.216  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.216  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.217  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.217  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.217  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.217  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.217  6853  6931 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 00:06:47.217  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.217  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.217  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.217  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.217  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.217  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.217  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.217  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.218  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.218  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.218  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.218  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.218  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.218  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.219  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.219  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.219  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.219  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.219  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.219  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.220  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 00:06:47.220  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.220  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.220  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.220  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.220  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.220  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.220  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.220  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.220  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.220  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.220  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.220  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.220  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.220  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.221  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.221  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.221  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.221  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.221  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.221  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.222  6853  6931 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 00:06:47.222  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.222  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.222  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.222  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.222  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.222  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.222  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.222  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.222  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.222  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.222  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.222  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.222  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:47.222  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.223  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.223  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.223  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.223  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.223  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.223  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.224  6853  6931 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 00:06:47.224  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.224  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.224  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.224  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.224  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.224  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.224  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.224  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.224  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.224  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.224  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.224  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.224  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.224  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.225  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.225  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.225  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.225  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.225  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.225  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.226  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:06:47.227  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:06:47.227  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:06:47.228  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:06:47.228  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:06:47.228  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:06:47.228  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.228  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.228  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.228  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.228  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.228  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.228  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.228  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.228  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.228  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.228  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.228  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.228  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.228  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.229  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.229  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.229  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.229  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.229  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.229  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.230  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:06:47.230  6853  6931 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 00:06:47.231  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 00:06:47.233  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:06:47.234  6853  6931 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 00:06:47.234  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 00:06:47.236  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 00:06:47.236  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 00:06:47.236  6853  6931 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:06:47.236  6853  6931 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 00:06:47.237  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:06:47.237  6853  6931 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:06:47.237  6853  6931 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 00:06:47.237  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:06:47.237  6853  6931 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:06:47.237  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 00:06:47.238  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 00:06:47.240  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 00:06:47.240  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 00:06:47.241  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 00:06:47.241  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 00:06:47.241  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 00:06:47.241  6853  6931 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:06:47.241  6853  6931 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 00:06:47.241  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.241  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.241  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.242  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.242  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.242  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.242  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 00:06:47.242  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.242  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.242  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.242  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.242  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.242  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.242  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.242  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.244  6853  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 871
09-13 00:06:47.245  6853  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 871)
09-13 00:06:47.245  6853  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 871)
09-13 00:06:47.245  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.245  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.246  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.246  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.246  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.246  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.246  6853  6931 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 00:06:47.247  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.247  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.247  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.247  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.247  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.247  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.247  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.247  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.247  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.247  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.247  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.247  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.247  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.247  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.248  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.248  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.248  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.248  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.248  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.248  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.249  6853  6931 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 00:06:47.249  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.249  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.249  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.249  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.250  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.250  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.250  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.250  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.250  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.250  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.250  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.250  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.250  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.250  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.251  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.251  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.252  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.252  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.252  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.252  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.252  6853  6931 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 00:06:47.252  6853  6931 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 00:06:47.252  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:06:47.252  6853  6931 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 00:06:47.252  6853  6931 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 00:06:47.252  6853  6931 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 00:06:47.252  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:06:47.253  6853  6931 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 00:06:47.253  6853  6931 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 00:06:47.253  6853  6931 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 00:06:47.253  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:06:47.253  6853  6931 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 00:06:47.253  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.253  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.253  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.253  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.253  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.253  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.253  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.253  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.253  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.253  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.253  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.253  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.253  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.254  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.254  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.254  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.255  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.255  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.255  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.255  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.255  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.255  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.255  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.255  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.255  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.255  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.255  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.255  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.255  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.255  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.255  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.255  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.255  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.255  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.255  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.255  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.255  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.255  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.256  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.256  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.256  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:47.256  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.256  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.256  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.256  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.256  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.256  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.256  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.256  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.257  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.257  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.257  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.257  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.257  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.257  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.258  6853  6931 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 00:06:47.259  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.259  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 00:06:47.260  6853  6931 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 00:06:47.260  6853  6931 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 00:06:47.260  6853  6853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 00:06:47.260  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 00:06:47.260  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:06:47.261  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.261  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 00:06:47.261  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 00:06:47.261  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 00:06:47.261  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.261  6853  6931 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 00:06:47.262  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.263  6853  6853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 00:06:47.263  6853  6943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:47.263  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.263  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.263  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:06:47.264  6853  6931 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:06:47.264  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:06:47.265  4306  4325 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-13 00:06:47.265  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:06:47.265  6853  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 00:06:47.265  6853  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 00:06:47.266  6853  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 00:06:47.266  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:06:47.266  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:47.267  6853  6931 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:06:47.267  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.267  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.267  6853  6931 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:47.267  6853  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:47.268  6853  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:47.268  6853  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 00:06:47.268  6853  6853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:47.268  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.268  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.268  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.268  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.268  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.268  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.268  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.268  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.268  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.268  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.268  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.268  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.268  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.268  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.268  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.269  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.269  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.269  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.269  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.270  6853  6931 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 00:06:47.270  6853  6931 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 00:06:47.270  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:06:47.271  6853  6931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:06:47.271  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.271  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.271  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.272  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.272  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.272  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.272  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.272  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.272  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.272  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.272  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.272  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.272  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.272  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.273  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.273  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.273  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.273  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.275  1033  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.275  1033  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.276  1033  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.276  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.276  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.276  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.277  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.277  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.277  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.277  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.277  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.277  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.277  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.277  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.277  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.277  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.277  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.278  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.278  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.278  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.278  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.279  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:47.279  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:47.279  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:47.279  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:47.279  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.279  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.280  6853  6931 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ca1d87 not in the list
09-13 00:06:47.280  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.280  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.280  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:47.280  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.280  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.280  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:47.280  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:47.281  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:47.281  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:47.281  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:47.281  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77e4b4 not in the list
09-13 00:06:47.282  6853  6931 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 00:06:47.282  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:06:47.282  6853  6931 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 00:06:47.282  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:06:47.282  6853  6931 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 00:06:47.282  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:06:47.284  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 00:06:47.284  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 00:06:47.285  6853  6931 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 00:06:47.285  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 00:06:47.285  6853  6931 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 00:06:47.286  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 00:06:47.286  6853  6931 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 00:06:47.286  6853  6931 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 00:06:47.287  6853  6931 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 00:06:47.287  6853  6931 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 00:06:47.287  6853  6931 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 00:06:47.287  6853  6931 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 00:06:47.288  6853  6931 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 00:06:47.288  6853  6931 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 00:06:47.288  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:47.288  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b9fd695 added. We now have 2 listener(s)
09-13 00:06:47.288  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:47.289  6853  6931 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 00:06:47.290  1033  1592 D WifiServiceImplEx: setWifiEnabled: true pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 00:06:47.290  1033  1592 D WifiService: setWifiEnabled: true pid=6853, uid=10118
09-13 00:06:47.290  1033  1592 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 00:06:47.292  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:47.292  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32adf3aa added. We now have 3 listener(s)
09-13 00:06:47.292  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:47.295  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:47.295  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33cabb9b added. We now have 4 listener(s)
09-13 00:06:47.295  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:47.296  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:47.296  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75d4b38 added. We now have 5 listener(s)
09-13 00:06:47.296  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:47.299  1033  1867 D WifiServiceImplEx: setWifiEnabled: false pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 00:06:47.299  1033  1867 D WifiService: setWifiEnabled: false pid=6853, uid=10118
09-13 00:06:47.299  1033  1867 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 00:06:47.307  1033  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:47.307  1033  1903 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@717a8e1 mBinding = false
09-13 00:06:47.308  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:06:47.310  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:06:47.310  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:06:47.310  1033  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:47.310  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:47.311  1033  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:47.311  1033  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:47.312  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:47.312  1033  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 00:06:47.312  1033  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:06:47.312  1033  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 00:06:47.313  1033  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 00:06:47.313  1033  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 00:06:47.314  1033  1109 D BluetoothManagerService: Message: 2
09-13 00:06:47.315  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:06:47.316  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:06:47.316  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:06:47.317  1033  1109 D BluetoothManagerService: Sending off request.
09-13 00:06:47.317  4306  4327 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 00:06:47.318  4306  4375 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 00:06:47.318  4306  4375 D BluetoothAdapterProperties: Setting state to 13
09-13 00:06:47.318  4306  4375 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 00:06:47.318  4306  4375 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 00:06:47.318  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:06:47.318  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 00:06:47.318  4306  4375 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 00:06:47.318  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 00:06:47.322  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:06:47.323  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:06:47.325  4306  4306 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:47.325  4306  4306 D BluetoothMapService: STATE_TURNING_OFF
09-13 00:06:47.325  4306  4306 V BluetoothMapService: Handler(): got msg=4
09-13 00:06:47.325  4306  4306 D BluetoothMapService: MAP Service closeService in
09-13 00:06:47.325  1033  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 00:06:47.325  4306  4306 D BluetoothMapMasInstance: MAP Service shutdown
09-13 00:06:47.326  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 00:06:47.326  4306  4702 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 00:06:47.327  4306  4306 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 00:06:47.327  4306  4306 V BluetoothMapService: MAP Service closeService out
09-13 00:06:47.328  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:47.328  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.328  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.328  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.328  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:47.330  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.331  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.332  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - w,ill return stored value
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:47.332  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.332  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.332  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:47.333  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:47.336  4306  4306 V BtOppService: Receiver DISABLED_ACTION 
09-13 00:06:47.337  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 00:06:47.338  2657  2657 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 00:06:47.338  1033  1388 D LGWifiP2pService: InactiveState{ when=-13ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.338  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.339  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 00:06:47.339  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:06:47.340  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
09-13 00:06:47.341  1033  2823 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.348  4306  4306 I BtOppRfcommListener: stopping Accept Thread
09-13 00:06:47.348  4306  4306 V BtOppRfcommListener: close mBtServerSocket
09-13 00:06:47.349  4306  4306 V BtOppRfcommListener: waiting for thread to terminate
09-13 00:06:47.349  4306  4785 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:47.350  4306  4785 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 00:06:47.351  4306  4306 V BtOppRfcommListener: done waiting for thread to terminate
09-13 00:06:47.353   308   889 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:06:47.363  1033  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 00:06:47.364  4306  4378 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:06:47.364  4306  4375 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 00:06:47.364  4306  4375 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 00:06:47.365  4306  4709 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-13 00:06:47.366  4306  4788 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:47.366  4306  4791 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:47.366  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 00:06:47.367  4306  4541 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 00:06:47.367  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 00:06:47.367  4306  4541 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 00:06:47.368  4306  4306 V BtOppService: onDestroy
09-13 00:06:47.369  4306  4306 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 00:06:47.384  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 00:06:47.384  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-13 00:06:47.386  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.387  1033  1939 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-13 00:06:47.388  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.388  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.388  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 00:06:47.388  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.388  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-13 00:06:47.392  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:47.392  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:47.393  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.393  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:47.424  1033  1440 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 00:06:47.424  1033  1440 D DSQN    : disableDataServiceNotify
09-13 00:06:47.424  1033  1440 D DSQN    : stop dsqn bin
09-13 00:06:47.424   308  6979 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 00:06:47.424  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 00:06:47.424  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,09-13 00:06:47.430  1033  1440 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 00:06:47.431  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:47.431  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:47.432  1033  1440 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:47.432  1033  1440 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 00:06:47.432  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 00:06:47.433  1033  1440 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 00:06:47.433  1033  1440 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 00:06:47.433  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:06:47.433  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.433  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.433  1033  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 00:06:47.434  1033  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6981 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 00:06:47.435  1033  1440 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:47.435  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:06:47.436  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-13 00:06:47.437  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.437  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.437  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:47.438  1033  1033 D WifiHS20: hidePasspointNotification off =false
,09-13 00:06:47.439  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 00:06:47.440  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.440  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.440  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:47.441  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 00:06:47.441  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 00:06:47.441  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 00:06:47.441  1033  1440 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:47.442  1033  1440 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:47.442  1033  1440 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:47.442  1033  1440 D NetworkManagementService: Removing idletimer
09-13 00:06:47.442  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:47.442  1033  1440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.442  1033  1440 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 00:06:47.442  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 00:06:47.443  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 00:06:47.443  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 00:06:47.443  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.444  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.444  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.444  1033  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 00:06:47.445  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.445  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.445  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.446  1033  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.446  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.446  1033  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2dc2d6c2
09-13 00:06:47.446  1033  1388 D LGWifiP2pService: P2pDisablingState
09-13 00:06:47.446  1033  1388 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.446  1033  1388 D LGWifiP2pService: p2p socket connection lost
09-13 00:06:47.447  1033  1388 D LGWifiP2pService: P2pDisabledState
09-13 00:06:47.447  1033  1387 V Network,Policy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 00:06:47.447  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 00:06:47.447  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 00:06:47.447  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 00:06:47.447  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 00:06:47.449  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 00:06:47.449  1033  1553 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.450  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 00:06:47.450  1940  1940 D WfdsService: WifiP2pState is changed : false
09-13 00:06:47.450  1940  2252 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 00:06:47.450  1940  2252 D WfdsService: Set the WFDS Monitor: false
09-13 00:06:47.450  1033  1033 D RttService: SCAN_AVAILABLE : 1
09-13 00:06:47.450  1033  1554 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.450  1940  2252 D WfdsMonitor: WFDS Monitor is stopped
09-13 00:06:47.451  1940  2252 D WfdsService: STATE : WfdsDisabledState - enter
09-13 00:06:47.451  1940  2744 D CtrlSupplicant: Received on exit socket, terminate
09-13 00:06:47.451  1940  2744 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 00:06:47.451  1940  2253 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 00:06:47.451  1940  2744 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 00:06:47.451  1940  2744 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 00:06:47.451  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.452  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:47.452  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:47.452  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:47.452  1940  2252 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 00:06:47.452  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 00:06:47.452  1033  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:47.452  1033  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:06:47.453  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 00:06:47.453  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 00:06:47.453  2657  2657 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 00:06:47.454  1033  1388 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.454  1033  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.455  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 00:06:47.455  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:06:47.456  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
09-13 00:06:47.456   308   889 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:06:47.458  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.459  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:47.459  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:47.461  1033  1389 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 00:06:47.463  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-13 00:06:47.463  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.463  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.463  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:47.463  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.464  1033  1389 D WifiNative-p2p0: TERMINATE: returned true
09-13 00:06:47.464  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:06:47.464  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:06:47.464  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 00:06:47.466  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 00:06:47.466  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 00:06:47.466  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:47.466  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-13 00:06:47.474  6956  6956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:06:47.474  6956  6956 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 00:06:47.475  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:06:47.475  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 00:06:47.476  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:47.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:47.477  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.477  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:47.478  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:47.478  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:47.478  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:47.479  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:47.480  6956  6956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 00:06:47.480  6956  6956 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 00:06:47.506  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:06:47.507  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:06:47.507  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.523  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:06:47.524  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:06:47.525  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.525  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 00:06:47.525  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:47.526  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.527  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.547  6981  6981 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 00:06:47.548  6981  6981 W LG Account v2.2: No ProfileInfo entries
09-13 00:06:47.548  6981  6981 I LG Account v2.2: isEnabled: false
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Country: EU
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Operator: OPEN
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Ranking support: false
,09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Comfort support: false
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Accessory: true
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Health device: true
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Extra Pedometer: false
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Blood glucose device: false
09-13 00:06:47.548  6981  6981 I Feature : [Lifetracker]Device Number: 3
09-13 00:06:47.555  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:47.575  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 00:06:47.577  2657  2657 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 00:06:47.577  2657  2657 I wpa_supplicant: monitor socket send errors count : 1
09-13 00:06:47.577  2657  2657 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
09-13 00:06:47.578  1033  2737 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 00:06:47.578  1033  2737 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 00:06:47.591  1033  1782 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7001 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 00:06:47.592  1033  1903 I ActivityManager: Killing 6257:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 00:06:47.601  2657  2657 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 00:06:47.602  1033  2737 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 00:06:47.602  2657  2657 W wpa_supplicant: USIM:  scard_deinit function
09-13 00:06:47.602  1033  2737 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 00:06:47.602  1033  2737 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 00:06:47.602  1033  2737 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 00:06:47.603  1033  2737 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:06:47.603  1033  2737 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 00:06:47.603  1033  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179603
09-13 00:06:47.604  1033  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179603
09-13 00:06:47.604  1033  1109 D Tethering: InitialState.processMessage what=4
,09-13 00:06:47.605  1033  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 00:06:47.605  1033  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 00:06:47.607  1033  2823 D DhcpStateMachine: StoppedState
09-13 00:06:47.607  1033  2823 D DhcpStateMachine: StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:47.638  4306  4306 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:06:47.638  4306  4306 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:47.638  4306  4306 V BluetoothPbapReceiver: ***********state = 13
,09-13 00:06:47.640  1033  1389 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 00:06:47.640  4306  4306 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 00:06:47.641  1033  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 00:06:47.642  1033  1973 W libprocessgroup: failed to open /acct/uid_10014/pid_6257/cgroup.procs: No such file or directory
09-13 00:06:47.642  4306  4306 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:47.642  4306  4306 V BluetoothPbapService: state: 13
09-13 00:06:47.642  4306  4306 V BluetoothPbapService: Pbap Service closeService in
09-13 00:06:47.647  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:06:47.647  1033  1109 D BluetoothManagerService: Message: 20
09-13 00:06:47.648  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f79a260:true
09-13 00:06:47.657  4306  4306 V BluetoothPbapService: successfully stopped pbap service
09-13 00:06:47.658  4306  4306 V BluetoothPbapService: Pbap Service closeService out
09-13 00:06:47.658  4306  4306 V BluetoothPbapService: Pbap Service onDestroy
09-13 00:06:47.658  4306  4306 V BluetoothPbapService: Pbap Service closeService in
09-13 00:06:47.658  4306  4306 V BluetoothPbapService: Pbap Service closeService out
09-13 00:06:47.658  4306  4306 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-13 00:06:47.661  1033  1389 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:47.664  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:47.664  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:06:47.679  1033  1109 D BluetoothManagerService: Message: 30
09-13 00:06:47.688  1033  1109 D BluetoothManagerService: Message: 30
,09-13 00:06:47.691  6956  6956 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 00:06:47.692  6956  6956 D BluetoothMap: Create BluetoothMap proxy object
09-13 00:06:47.693  1033  1109 D BluetoothManagerService: Message: 30
09-13 00:06:47.697  2657  2657 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 00:06:47.697  1033  2737 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 00:06:47.697  1033  2737 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 00:06:47.698  1033  2737 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 00:06:47.698  1033  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-13 00:06:47.698  1033  1109 D BluetoothManagerService: Message: 30
09-13 00:06:47.700  6956  6956 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 00:06:47.701  6956  6956 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-13 00:06:47.716  6956  6956 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-13 00:06:47.720  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 00:06:47.726  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 00:06:47.729  6956  6956 D DockEventReceiver: finishStartingService: stopping service
09-13 00:06:47.730  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:47.730  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:06:47.732  1033  1902 I ActivityManager: Killing 6319:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 00:06:47.742  6956  6956 D BluetoothInputDevice: Proxy object connected
09-13 00:06:47.743  6956  6956 D HidProfile: Bluetooth service connected
09-13 00:06:47.744  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:06:47.744  6956  6956 D PanProfile: Bluetooth service connected
09-13 00:06:47.745  6956  6956 D BluetoothMap: Proxy object connected
09-13 00:06:47.746  6956  6956 D MapProfile: Bluetooth service connected
09-13 00:06:47.746  6956  6956 D BluetoothMap: getConnectedDevices()
,09-13 00:06:47.747  6956  6956 D BluetoothMap: Bluetooth is Not enabled
09-13 00:06:47.747  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 00:06:47.768  1033  1782 W libprocessgroup: failed to open /acct/uid_10004/pid_6319/cgroup.procs: No such file or directory
09-13 00:06:47.768  6853  6853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 00:06:47.781  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:47.801  1940  1940 D WfdsService: Supplicant Connection state is changed : false
09-13 00:06:47.801  1940  2252 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 00:06:47.801  1940  2252 D WfdsService: Set the WFDS Monitor: false
09-13 00:06:47.801  1940  2252 D WfdsMonitor: WFDS Monitor is stopped
09-13 00:06:47.801  1033  1389 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 00:06:47.801  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:06:47.801  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:06:47.801  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 00:06:47.803  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 00:06:47.805  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 00:06:47.806  1033  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 00:06:47.806  1033  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 00:06:47.808  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:47.808  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.810  2467  2467 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:47.811  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:47.845  6956  6956 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 00:06:47.845  6956  6956 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:06:47.856  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:47.857  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 00:06:47.863  6956  6956 D BluetoothPermissionRequest: onReceive
09-13 00:06:47.865  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 00:06:47.876  1033  1902 I ActivityManager: Killing 6476:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-13 00:06:47.879  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 00:06:47.911  4306  4306 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 00:06:47.911  4306  4306 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 00:06:47.912  4306  4306 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 00:06:47.914  1033  2030 W libprocessgroup: failed to open /acct/uid_10008/pid_6476/cgroup.procs: No such file or directory
,09-13 00:06:48.005  1033  1902 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7030 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 00:06:48.006  4306  4306 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:48.006  4306  4306 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 00:06:48.010  4306  4306 V BluetoothFtpService: Ftp Service onStartCommand
09-13 00:06:48.011  4306  4306 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:48.011  4306  4306 V BluetoothFtpService: Ftp Service closeService
09-13 00:06:48.012  4306  4306 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 00:06:48.012  4306  4306 V BluetoothFtpService: successfully stopped ftp service
09-13 00:06:48.013  4306  4306 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:06:48.013  4306  4306 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:06:48.014  4306  4306 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:06:48.014  4306  4306 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:48.014  4306  4306 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 00:06:48.014  4306  4306 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 00:06:48.016  4306  4306 V BluetoothFtpService: Ftp Service onDestroy
09-13 00:06:48.016  4306  4306 V BluetoothFtpService: Ftp Service closeService
09-13 00:06:48.061  1033  1973 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7050 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 00:06:48.063  4306  4306 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:48.063  4306  4306 V BluetoothSapService: state: 13
09-13 00:06:48.063  4306  4306 V BluetoothSapService: Stopping SAP server process
09-13 00:06:48.064  4306  4306 V BluetoothSapService: Sap Service closeSapService in
09-13 00:06:48.064  4306  4306 V BluetoothSapService: Close listen Socket : 
09-13 00:06:48.064  4306  4306 V BluetoothSapService: Close rfcomm Socket : 
09-13 00:06:48.065  4306  4306 V BluetoothSapService: Close sapd  Socket : 
09-13 00:06:48.071  4306  4306 V BluetoothSapService: Sap Service closeSapService out
09-13 00:06:48.072  4306  4306 V BluetoothSapService: Sap Service onDestroy
09-13 00:06:48.072  4306  4306 V BluetoothSapService: Sap Service closeSapService in
09-13 00:06:48.072  4306  4306 V BluetoothSapService: Close listen Socket : 
09-13 00:06:48.072  4306  4306 V BluetoothSapService: Close rfcomm Socket : 
09-13 00:06:48.072  4306  4306 V BluetoothSapService: Close sapd  Socket : 
09-13 00:06:48.072  4306  4306 V BluetoothSapService: Sap Service closeSapService out
09-13 00:06:48.091  7030  7030 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 00:06:48.122  7030  7030 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 00:06:48.131  7050  7050 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:06:48.146  1033  1973 I ActivityManager: Killing 6525:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-13 00:06:48.153  7030  7030 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 00:06:48.154  7030  7030 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 00:06:48.154  7030  7030 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 00:06:48.155  7030  7030 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 00:06:48.155  7030  7030 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 00:06:48.157  7030  7030 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 00:06:48.162  7030  7030 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-13 00:06:48.178  1033  1902 W libprocessgroup: failed to open /acct/uid_10011/pid_6525/cgroup.procs: No such file or directory
,09-13 00:06:48.185  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:48.190  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:48.225  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 00:06:48.233  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:48.237  7030  7030 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 00:06:48.244  7030  7030 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-13 00:06:48.246  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 00:06:48.246  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:48.247  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:48.257  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:48.271  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:48.282  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 00:06:48.283  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:48.287  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 00:06:48.291  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:48.298  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 00:06:48.298  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:48.298  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:06:48.303  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:48.311  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:48.324  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:48.325  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:48.327  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 00:06:48.372  4306  4541 W bt-btif : ag scb idx 1 not allocated
09-13 00:06:48.372  4306  4378 D bt_hci_bdroid: cleanup
09-13 00:06:48.372  4306  4541 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 00:06:48.372  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:48.372  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:06:48.372  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:48.372  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 00:06:48.372  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:48.372  4306  4541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:48.373  4306  4543 I bt_lpm  : LPM is already off!!!
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:48.373  4306  4694 I bt_userial_mct: exiting userial_read_thread
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:06:48.373  4306  4694 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:48.373  4306  4541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:06:48.373  4306  4541 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 00:06:48.373  4306  4378 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 00:06:48.374  4306  4543 I bt_vendor: hw_epilog_process
09-13 00:06:48.375  4306  4378 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 00:06:48.375  4306  4378 D bt_userial_mct: userial_close
09-13 00:06:48.375  4306  4378 E bt_userial_mct: pthread_join() FAILED result:3
09-13 00:06:48.375  4306  4378 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-13 00:06:48.406  1033  1592 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7077 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-13 00:06:48.447  4306  4378 D bt_hci_bdroid: set_power 0
09-13 00:06:48.447  4306  4378 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 00:06:48.447  4306  4378 I bt_vendor: bluetooth satus is on
,09-13 00:06:48.447  4306  4378 I bt_vendor: bt-vendor : resetting BT status
09-13 00:06:48.447  4306  4378 I bt_vendor: Starting hciattach daemon
09-13 00:06:48.447  4306  4378 I bt_vendor: try to set false
09-13 00:06:48.450  4306  4378 I bt_vendor: Starting hciattach daemon
09-13 00:06:48.450  4306  4378 I bt_vendor: try to set false
,09-13 00:06:48.452  4306  4378 I bt_vendor: cleanup
09-13 00:06:48.453  4306  4541 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 00:06:48.454  4306  4378 I GKI_LINUX: GKI_exit_task 0 done
09-13 00:06:48.454  4306  4378 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 00:06:48.457  4306  4375 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 00:06:48.461  4306  4306 D HeadsetService: Received stop request...Stopping profile...
09-13 00:06:48.463  4306  4306 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 00:06:48.463  4306  4306 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:06:48.463  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
09-13 00:06:48.465  4306  4471 D HeadsetStateMachine: Exit Disconnected: -1
09-13 00:06:48.467  1850  1850 D BluetoothHeadset: Proxy object disconnected
,09-13 00:06:48.468  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-13 00:06:48.472  4306  4306 D A2dpService: Received stop request...Stopping profile...
09-13 00:06:48.472  4306  4514 D A2dpStateMachine: Exit Disconnected: -1
09-13 00:06:48.473  4306  4306 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 00:06:48.474  1033  1033 D BluetoothHeadset: Proxy object disconnected
09-13 00:06:48.474  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 00:06:48.475  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-13 00:06:48.476  4306  4306 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 00:06:48.476  4306  4306 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:06:48.476  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
09-13 00:06:48.478  1033  1033 D BluetoothA2dp: Proxy object disconnected
09-13 00:06:48.478  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 00:06:48.478  4306  4375 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 00:06:48.479  4306  4306 D HidService: Received stop request...Stopping profile...
09-13 00:06:48.479  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
,09-13 00:06:48.481  4306  4306 D HeadsetStateMachine: Unbinding service...
09-13 00:06:48.482  4306  4306 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 00:06:48.482  4306  4306 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 00:06:48.482  4306  4306 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 00:06:48.482  4306  4306 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 00:06:48.482  4306  4306 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 00:06:48.482  4306  4306 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:06:48.482  4306  4306 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 00:06:48.483  6956  6956 D BluetoothInputDevice: Proxy object disconnected
09-13 00:06:48.483  6956  6956 D HidProfile: Bluetooth service disconnected
09-13 00:06:48.483  4306  4306 D HealthService: Received stop request...Stopping profile...
09-13 00:06:48.483  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
09-13 00:06:48.485  4306  4306 D PanService: Received stop request...Stopping profile...
09-13 00:06:48.486  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
09-13 00:06:48.487  4306  4306 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 00:06:48.488  6956  6956 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 00:06:48.488  6956  6956 D PanProfile: Bluetooth service disconnected
09-13 00:06:48.488  4306  4306 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 00:06:48.488  4306  4306 D BtGatt.GattService: stop()
09-13 00:06:48.488  4306  4306 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 00:06:48.489  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
09-13 00:06:48.490  4306  4306 I BluetoothA2dpServiceJni: cleanupNative
09-13 00:06:48.490  4306  4515 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 00:06:48.490  4306  4306 I GKI_LINUX: GKI_exit_task 2 done
09-13 00:06:48.490  4306  4306 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-13 00:06:48.492  4306  4306 D BluetoothMapService: Received stop request...Stopping profile...
09-13 00:06:48.492  4306  4306 D BluetoothMapService: stop()
09-13 00:06:48.493  4306  4306 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 00:06:48.493  4306  4306 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 00:06:48.493  4306  4306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1855466d
09-13 00:06:48.494  4306  4306 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 00:06:48.494  6956  6956 D BluetoothMap: Proxy object disconnected
09-13 00:06:48.494  4306  4306 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 00:06:48.494  6956  6956 D MapProfile: Bluetooth service disconnected
09-13 00:06:48.495  4306  4306 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 00:06:48.495  4306  4306 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:06:48.495  4306  4306 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:06:48.495  4306  4306 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 00:06:48.495  4306  4306 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 00:06:48.496  4306  4306 V BluetoothMapService: Handler(): got msg=4
09-13 00:06:48.496  4306  4306 D BluetoothMapService: MAP Service closeService in
09-13 00:06:48.496  4306  4306 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 00:06:48.496  4306  4306 V BluetoothMapService: MAP Service closeService out
09-13 00:06:48.497  4306  4306 D BluetoothMapService: cleanup()
09-13 00:06:48.497  4306  4306 D BluetoothMapService: MAP Service closeService in
09-13 00:06:48.497  4306  4306 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 00:06:48.497  4306  4306 V BluetoothMapService: MAP Service closeService out
09-13 00:06:48.497  4306  4375 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 00:06:48.497  4306  4375 D BluetoothAdapterProperties: Setting state to 10
09-13 00:06:48.497  4306  4375 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 00:06:48.498  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:06:48.498  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 00:06:48.498  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 00:06:48.498  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:06:48.498  4306  4375 I BluetoothAdapterState: Entering OffState
09-13 00:06:48.498  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:06:48.499  6956  6978 D BluetoothMap: onBluetoothStateChange: up=false
09-13 00:06:48.499  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:06:48.500  1850  3470 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:06:48.501  6956  6980 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 00:06:48.501  6956  6978 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 00:06:48.502  6956  6980 D BluetoothPan: onBluetoothStateChange on: false
09-13 00:06:48.502  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:06:48.503  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 00:06:48.504  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-13 00:06:48.511  1033  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 00:06:48.511  1033  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 00:06:48.511  1033  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@717a8e1 mBinding = false
09-13 00:06:48.512  1033  1109 D BluetoothManagerService: Sending unbind request.
09-13 00:06:48.514  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 00:06:48.515  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:48.516  1940  2086 D LGBluetoothAPIService: Message: 2
09-13 00:06:48.516  1940  2086 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@259d4 mBinding = false
09-13 00:06:48.516  1940  2086 D LGBluetoothAPIService: Sending unbind request.
09-13 00:06:48.517  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 00:06:48.522  4306  4378 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-13 00:06:48.523  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:48.524  4306  4306 I GKI_LINUX: GKI_exit_task 1 done
09-13 00:06:48.524  4306  4306 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 00:06:48.524  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:48.524  4306  4306 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 00:06:48.524  4306  4306 I art     : --- WEIRD: removing null entry 246
09-13 00:06:48.524  4306  4306 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-13 00:06:48.524  4306  4306 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 00:06:48.526  1601  1601 D BluetoothAdapter: 343617701: getState() :  mService = null. Returning STATE_OFF
09-13 00:06:48.526  1601  1601 D BluetoothAdapter: 343617701: getState() :  mService = null. Returning STATE_OFF
09-13 00:06:48.526  6956  6956 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 00:06:48.527  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 00:06:48.527  6956  6956 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 00:06:48.528  4306  4306 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 00:06:48.530  4306  4306 I art     : System.exit called, status: 0
09-13 00:06:48.530  4306  4306 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 00:06:48.530  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 00:06:48.537  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:06:48.555   312  2174 V AudioFlinger: 4306 died, releasing its sessions
09-13 00:06:48.555   312  2174 V AudioFlinger:  pid 1850 @ 0
,09-13 00:06:48.555   312  2174 V AudioFlinger:  pid 3207 @ 1
09-13 00:06:48.555   312  2174 V AudioFlinger:  pid 3207 @ 2
09-13 00:06:48.555  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 00:06:48.576  1033  1782 I ActivityManager: Process com.android.bluetooth (pid 4306) has died
,09-13 00:06:48.576  1033  1782 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-13 00:06:48.583  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 00:06:48.589  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:06:48.598  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:48.606  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:48.608  6956  6956 D BluetoothPermissionRequest: onReceive
09-13 00:06:48.610  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 00:06:48.611  6956  6956 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 00:06:48.613  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 00:06:48.613  7077  7106 W FormManager: Network not available. Please check & try again.
09-13 00:06:48.667  1033  1973 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7109 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 00:06:48.697  7077  7108 V FormManager: Network unavailable.
,09-13 00:06:48.700  7077  7108 V FormManager: Network unavailable.
09-13 00:06:48.708  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 00:06:48.708  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 00:06:48.708  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 00:06:48.709  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 00:06:48.709  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-13 00:06:48.722  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 00:06:48.722  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 00:06:48.722  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 00:06:48.722  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 00:06:48.722  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 00:06:48.723  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 00:06:48.727  1033  1938 I ActivityManager: Killing 6036:com.android.contacts/u0a19 (adj 15): empty #17
,09-13 00:06:48.734  7109  7109 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-13 00:06:48.734  7109  7109 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:06:48.735  7109  7109 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-13 00:06:48.735  7109  7109 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 00:06:48.751  7109  7109 D BluetoothAdapterApp: Loading JNI Library
,09-13 00:06:48.778  1033  2030 W libprocessgroup: failed to open /acct/uid_10019/pid_6036/cgroup.procs: No such file or directory
09-13 00:06:48.778  7109  7109 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3973944a Instance Count = 1
,09-13 00:06:48.781  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:06:48.781  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 00:06:48.783  7109  7109 D BluetoothAdapterApp: onCreate
09-13 00:06:48.786  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:48.790  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:48.799  7109  7109 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: Adding HeadsetService
09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: Adding A2dpService
09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: Adding HidService
09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 00:06:48.800  7109  7109 D ProfileConfigQcom: Adding HealthService
09-13 00:06:48.801  7109  7109 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 00:06:48.801  7109  7109 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 00:06:48.801  7109  7109 D ProfileConfigQcom: Adding PanService
09-13 00:06:48.802  7109  7109 D ProfileConfigQcom: [BTUI] GattService is supported
09-13 00:06:48.802  7109  7109 D ProfileConfigQcom: Adding GattService
09-13 00:06:48.802  7109  7109 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-13 00:06:48.802  7109  7109 D ProfileConfigQcom: Adding BluetoothMapService
09-13 00:06:48.802  7109  7109 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 00:06:48.803  7109  7109 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 00:06:48.806  7001  7001 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 00:06:48.806  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:48.806  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:48.808  4793  7131 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:06:48.809  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 00:06:48.810  7109  7109 V LGMDMManagerInternal: Create singleton instance
09-13 00:06:48.812  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 00:06:48.813  4793  7128 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 00:06:48.820  7077  7133 W FormManager: Network not available. Please check & try again.
09-13 00:06:48.820  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:48.822  4793  7131 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 00:06:48.830  7077  7134 V FormManager: Network unavailable.
,09-13 00:06:48.834  7077  7134 V FormManager: Network unavailable.
09-13 00:06:48.838  7030  7030 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 00:06:48.839  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 00:06:48.839  7030  7030 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 00:06:48.875  7030  7030 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 00:06:48.875  7030  7030 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:06:48.886  7030  7030 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 00:06:48.889  7109  7109 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:48.889  7030  7030 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
09-13 00:06:48.889  7030  7030 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
09-13 00:06:48.889  7030  7030 V SoundPool: doLoad: loading sample sampleID=1
09-13 00:06:48.890  7030  7137 V SoundPool: Start decode
09-13 00:06:48.890  7030  7137 V MediaPlayer[Native]: decode(30, 10857164, 17813)
09-13 00:06:48.890  7030  7030 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 00:06:48.891   312  2183 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 00:06:48.891   312  2183 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 00:06:48.891   312  2183 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 00:06:48.891   312  2183 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 00:06:48.891   312  2183 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 00:06:48.891   312  2183 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
,09-13 00:06:48.891   312  2183 V MediaPlayerService: player type = 3
09-13 00:06:48.891   312  2183 V AwesomePlayer: AwesomePlayer create()
09-13 00:06:48.892   312  2183 V AwesomePlayer: reset_l() 
09-13 00:06:48.893   312  2183 V AwesomePlayer: cancelPlayerEvents
09-13 00:06:48.893   312  2183 V AwesomePlayer: setAudioSink() 
09-13 00:06:48.893   312  2183 V AwesomePlayer: reset_l() 
09-13 00:06:48.893   312  2183 V AudioCache: notify(0xb5474bc0, 8, 0, 0)
09-13 00:06:48.893   312  2183 V AudioCache: ignored
09-13 00:06:48.893   312  2183 V AwesomePlayer: cancelPlayerEvents
09-13 00:06:48.893   312  2183 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 00:06:48.893   312  2183 V AwesomePlayer: setDataSource_l dataSource
09-13 00:06:48.893   312  2183 V LGParserOSAL: SniffLGParser start
09-13 00:06:48.893   312  2183 V LGParserOSAL: MainType:5, SubType=0
09-13 00:06:48.893   312  2183 V LGParserOSAL: #### check Mime : application/ogg
09-13 00:06:48.893   312  2183 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 00:06:48.893   312  2183 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 00:06:48.895  7030  7030 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 00:06:48.897  6756  6756 D UEI.SmartControl: QS Service created
09-13 00:06:48.897  7030  7030 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 00:06:48.898  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 00:06:48.899  7109  7109 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:06:48.899  7109  7109 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:06:48.899  7109  7109 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:06:48.900  7109  7109 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:06:48.901  7109  7109 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-13 00:06:48.912  6756  6756 I UEI.SmartControl: Service initServices...
09-13 00:06:48.912  7050  7050 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 00:06:48.912  6756  6756 D UEI.SmartControl: QS start get config
09-13 00:06:48.925  7030  7030 V LGMDMManager: Create singleton instance
,09-13 00:06:48.933   312  2183 V LGParserOSAL: supported mime: application/ogg
09-13 00:06:48.933   312  2183 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 00:06:48.933   312  2183 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 00:06:48.933   312  2183 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 00:06:48.933   312  2183 V AwesomePlayer: AudioTrack Setting
09-13 00:06:48.934   312  2183 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 00:06:48.934   312  2183 V AwesomePlayer: setAudioSource() 
09-13 00:06:48.934   312  2183 V MediaPlayerService: prepare
09-13 00:06:48.934   312  2183 V AwesomePlayer: prepareAsync_l() 
09-13 00:06:48.934   312  2183 V MediaPlayerService: wait for prepare
09-13 00:06:48.934   312  7139 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 00:06:48.934   312  7139 V AwesomePlayer: initAudioDecoder() 
09-13 00:06:48.934   312  7139 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 00:06:48.934   312  7139 V AudioSystem: isOffloadSupported()
09-13 00:06:48.934   312  7139 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 00:06:48.935   312  7139 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 00:06:48.935   312  7139 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 00:06:48.935   312  7139 V AwesomePlayer: getUseOffload() = 0 
09-13 00:06:48.935   312  7139 V OMXCodec: OMXCodec::Create
09-13 00:06:48.935   312  7139 V OMXCodec: findMatchingCodecs()
09-13 00:06:48.935   312  7139 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 00:06:48.935   312  7139 V OMXCodec: matchingCodecs.size()=1
09-13 00:06:48.935   312  7139 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 00:06:48.939   312  7139 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 00:06:48.939   312  7139 V LGCodecAdapter: LG Codec Adapter start
09-13 00:06:48.939   312  7139 V OMXCodec: OMXCodec Createtor
09-13 00:06:48.939   312  7139 V OMXCodec: setComponentRole
09-13 00:06:48.939   312  7139 V OMXCodec: configureCodec protected=0
09-13 00:06:48.939   312  7139 V LGCodecAdapter: called getLGCodecSpecificData
09-13 00:06:48.939   312  7139 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 00:06:48.939   312  7139 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 00:06:48.939   312  7139 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 00:06:48.940   312  7139 V LGCodecOSAL: Not support LGCodec
09-13 00:06:48.940   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 00:06:48.940   312  7139 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 00:06:48.940   312  7139 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 00:06:48.940   312  7139 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 00:06:48.940   312  7139 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 00:06:48.940   312  7139 V AudioSystem: isOffloadSupported()
09-13 00:06:48.940   312  7139 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 00:06:48.940   312  7139 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 00:06:48.940   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 00:06:48.940   312  7139 V OMXCodec: init()
09-13 00:06:48.941   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
09-13 00:06:48.941   312  7139 V OMXCodec: allocateBuffers
09-13 00:06:48.941   312  7139 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 00:06:48.941   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 00:06:48.941   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-13 00:06:48.941   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-13 00:06:48.941   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-13 00:06:48.942   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-13 00:06:48.942   312  7139 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 00:06:48.942   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 00:06:48.942   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-13 00:06:48.942   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 00:06:48.942   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
09-13 00:06:48.942   312  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
09-13 00:06:48.942   312  7139 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 00:06:48.942   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 00:06:48.942   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 00:06:48.943   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 00:06:48.943   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 00:06:48.943   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 00:06:48.943   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,09-13 00:06:48.946   312  7139 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 00:06:48.946   312  7139 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 00:06:48.946   312  7139 V AudioCache: notify(0xb5474bc0, 5, 0, 0)
09-13 00:06:48.946   312  7139 V AudioCache: ignored
09-13 00:06:48.946   312  7139 V AudioCache: notify(0xb5474bc0, 1, 0, 0)
09-13 00:06:48.946   312  7139 V AudioCache: prepared
09-13 00:06:48.946   312  2183 V AudioCache: wait - success
09-13 00:06:48.946   312  2183 V MediaPlayerService: start
09-13 00:06:48.946   312  2183 V AwesomePlayer: play_l() 
09-13 00:06:48.946   312  2183 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 00:06:48.946   312  2183 V AwesomePlayer: createAudioPlayer_l
09-13 00:06:48.947   312  2183 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 00:06:48.947   312  2183 V AwesomePlayer: startAudioPlayer_l() 
09-13 00:06:48.947   312  2183 D AudioPlayer: start of Playback, useOffload 0
09-13 00:06:48.947   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 00:06:48.947   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 00:06:48.955   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 00:06:48.956   312  7141 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 00:06:48.956   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 00:06:48.957   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
09-13 00:06:48.957   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 00:06:48.957   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-13 00:06:48.957   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
09-13 00:06:48.957   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,09-13 00:06:48.957   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 00:06:48.958   312  2183 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 00:06:48.959   312  2183 V AudioCache: notify(0xb5474bc0, 6, 0, 0)
09-13 00:06:48.959   312  2183 V AudioCache: ignored
09-13 00:06:48.959   312  2183 V MediaPlayerService: wait for playback complete
09-13 00:06:48.960   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.960   312  7142 V AudioCache: memcpy(0xb0493000, 0xb178c000, 4096)
09-13 00:06:48.962   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.962   312  7142 V AudioCache: memcpy(0xb0494000, 0xb178c000, 4096)
09-13 00:06:48.962   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.962   312  7142 V AudioCache: memcpy(0xb0495000, 0xb178c000, 4096)
09-13 00:06:48.963   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.963   312  7142 V AudioCache: memcpy(0xb0496000, 0xb178c000, 4096)
09-13 00:06:48.963   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.963   312  7142 V AudioCache: memcpy(0xb0497000, 0xb178c000, 4096)
09-13 00:06:48.964   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.964   312  7142 V AudioCache: memcpy(0xb0498000, 0xb178c000, 4096)
09-13 00:06:48.964   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.964   312  7142 V AudioCache: memcpy(0xb0499000, 0xb178c000, 4096)
09-13 00:06:48.965   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.965   312  7142 V AudioCache: memcpy(0xb049a000, 0xb178c000, 4096)
09-13 00:06:48.965   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.965   312  7142 V AudioCache: memcpy(0xb049b000, 0xb178c000, 4096)
09-13 00:06:48.966   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.966   312  7142 V AudioCache: memcpy(0xb049c000, 0xb178c000, 4096)
09-13 00:06:48.966   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.966   312  7142 V AudioCache: memcpy(0xb049d000, 0xb178c000, 4096)
09-13 00:06:48.967   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.967   312  7142 V AudioCache: memcpy(0xb049e000, 0xb178c000, 4096)
09-13 00:06:48.968   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.968   312  7142 V AudioCache: memcpy(0xb049f000, 0xb178c000, 4096)
09-13 00:06:48.968   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.968   312  7142 V AudioCache: memcpy(0xb04a0000, 0xb178c000, 4096)
09-13 00:06:48.969   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.969   312  7142 V AudioCache: memcpy(0xb04a1000, 0xb178c000, 4096)
09-13 00:06:48.969   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.969   312  7142 V AudioCache: memcpy(0xb04a2000, 0xb178c000, 4096)
,09-13 00:06:48.970   312  7142 V AudioCache: write(0xb178c000, 4096),
09-13 00:06:48.970   312  7142 V AudioCache: memcpy(0xb04a3000, 0xb178c000, 4096)
09-13 00:06:48.970   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.970   312  7142 V AudioCache: memcpy(0xb04a4000, 0xb178c000, 4096)
,09-13 00:06:48.971   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.971   312  7142 V AudioCache: memcpy(0xb04a5000, 0xb178c000, 4096)
09-13 00:06:48.971   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.971   312  7142 V AudioCache: memcpy(0xb04a6000, 0xb178c000, 4096)
09-13 00:06:48.972   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.972   312  7142 V AudioCache: memcpy(0xb04a7000, 0xb178c000, 4096)
,09-13 00:06:48.972   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.972   312  7142 V AudioCache: memcpy(0xb04a8000, 0xb178c000, 4096)
09-13 00:06:48.973   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.973   312  7142 V AudioCache: memcpy(0xb04a9000, 0xb178c000, 4096)
,09-13 00:06:48.973   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.973   312  7142 V AudioCache: memcpy(0xb04aa000, 0xb178c000, 4096)
09-13 00:06:48.974   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.974   312  7142 V AudioCache: memcpy(0xb04ab000, 0xb178c000, 4096)
,09-13 00:06:48.974   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.974   312  7142 V AudioCache: memcpy(0xb04ac000, 0xb178c000, 4096)
09-13 00:06:48.975   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.975   312  7142 V AudioCache: memcpy(0xb04ad000, 0xb178c000, 4096)
09-13 00:06:48.975   312  7142 V AudioCache: write(0xb178c000, 4096),
09-13 00:06:48.976   312  7142 V AudioCache: memcpy(0xb04ae000, 0xb178c000, 4096),
09-13 00:06:48.976   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.976   312  7142 V AudioCache: memcpy(0xb04af000, 0xb178c000, 4096)
,09-13 00:06:48.977   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.977   312  7142 V AudioCache: memcpy(0xb04b0000, 0xb178c000, 4096)
09-13 00:06:48.977   312  7142 V AudioCache: write(0xb178c000, 4096),
09-13 00:06:48.977   312  7142 V AudioCache: memcpy(0xb04b1000, 0xb178c000, 4096)
09-13 00:06:48.978   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.978   312  7142 V AudioCache: memcpy(0xb04b2000, 0xb178c000, 4096)
09-13 00:06:48.978   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.978   312  7142 V AudioCache: memcpy(0xb04b3000, 0xb178c000, 4096)
,09-13 00:06:48.979   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.979   312  7142 V AudioCache: memcpy(0xb04b4000, 0xb178c000, 4096)
09-13 00:06:48.979   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.979   312  7142 V AudioCache: memcpy(0xb04b5000, 0xb178c000, 4096)
09-13 00:06:48.980   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.980   312  7142 V AudioCache: memcpy(0xb04b6000, 0xb178c000, 4096),
09-13 00:06:48.980   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.980   312  7142 V AudioCache: memcpy(0xb04b7000, 0xb178c000, 4096)
,09-13 00:06:48.981   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.981   312  7142 V AudioCache: memcpy(0xb04b8000, 0xb178c000, 4096)
09-13 00:06:48.981   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.981   312  7142 V AudioCache: memcpy(0xb04b9000, 0xb178c000, 4096)
09-13 00:06:48.982   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.982   312  7142 V AudioCache: memcpy(0xb04ba000, 0xb178c000, 4096),
09-13 00:06:48.983   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.983   312  7142 V AudioCache: memcpy(0xb04bb000, 0xb178c000, 4096)
09-13 00:06:48.983   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.983   312  7142 V AudioCache: memcpy(0xb04bc000, 0xb178c000, 4096)
09-13 00:06:48.984  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 00:06:48.984   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.984   312  7142 V AudioCache: memcpy(0xb04bd000, 0xb178c000, 4096)
09-13 00:06:48.984  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 00:06:48.985   312  7142 V AudioCache: write(0xb178c000, 4096),
09-13 00:06:48.985   312  7142 V AudioCache: memcpy(0xb04be000, 0xb178c000, 4096)
09-13 00:06:48.985   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.985   312  7142 V AudioCache: memcpy(0xb04bf000, 0xb178c000, 4096),
09-13 00:06:48.986  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3381
09-13 00:06:48.986   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.986   312  7142 V AudioCache: memcpy(0xb04c0000, 0xb178c000, 4096),
09-13 00:06:48.987   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.987   312  7142 V AudioCache: memcpy(0xb04c1000, 0xb178c000, 4096)
09-13 00:06:48.988   312  7142 V AudioCache: write(0xb178c000, 4096)
,09-13 00:06:48.988   312  7142 V AudioCache: memcpy(0xb04c2000, 0xb178c000, 4096)
09-13 00:06:48.988   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.988   312  7142 V AudioCache: memcpy(0xb04c3000, 0xb178c000, 4096)
,09-13 00:06:48.989   312  7142 V AudioCache: write(0xb178c000, 4096)
09-13 00:06:48.989   312  7142 V AudioCache: memcpy(0xb04c4000, 0xb178c000, 4096)
09-13 00:06:48.989   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,09-13 00:06:48.989   312  7142 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 00:06:48.989   312  7142 V AwesomePlayer: postAudioEOS() 
09-13 00:06:48.989   312  7142 V AudioCache: write(0xb178c000, 280)
,09-13 00:06:48.989   312  7142 V AudioCache: memcpy(0xb04c5000, 0xb178c000, 280)
09-13 00:06:48.996   312  7139 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 00:06:48.996   312  7139 V AwesomePlayer: onStreamDone
,09-13 00:06:48.996   312  7139 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 00:06:48.996   312  7139 V AudioCache: notify(0xb5474bc0, 2, 0, 0)
09-13 00:06:48.996   312  7139 V AudioCache: playback complete,
09-13 00:06:48.996   312  2183 V AudioCache: wait - success
09-13 00:06:48.996   312  2183 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 00:06:48.996   312  7139 V AwesomePlayer: pause_l() ,
09-13 00:06:48.996   312  7139 V AudioCache: notify(0xb5474bc0, 7, 0, 0)
09-13 00:06:48.996   312  7139 V AudioCache: ignored
09-13 00:06:48.996   312  7139 V AwesomePlayer: cancelPlayerEvents,
09-13 00:06:48.996   312  7139 D AudioPlayer: Pause Playback at 1068125
09-13 00:06:48.997   312  2183 V AwesomePlayer: reset_l() 
09-13 00:06:48.997   312  2183 V AudioCache: notify(0xb5474bc0, 8, 0, 0)
,09-13 00:06:48.997   312  2183 V AudioCache: ignored
09-13 00:06:48.997   312  2183 V AwesomePlayer: cancelPlayerEvents
09-13 00:06:48.997   312  2183 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,09-13 00:06:48.997   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 00:06:48.997   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 00:06:48.997   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 00:06:48.997   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!,
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
,09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 00:06:48.997   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
,09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fab0 on port 1
,09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1,
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
,09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 00:06:48.998   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 00:06:48.998   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!,
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 00:06:48.998   312  7141 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
,09-13 00:06:48.998   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 00:06:48.998   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 00:06:48.998   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-13 00:06:48.999   312  2183 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 00:06:48.999   312  2183 D AudioPlayer: AudioPlayer releasing audio source
09-13 00:06:48.999   312  2183 D AudioPlayer: AudioPlayer done releasing audio source
09-13 00:06:48.999   312  2183 V AwesomePlayer: reset_l() 
,09-13 00:06:48.999   312  2183 V AwesomePlayer: cancelPlayerEvents
09-13 00:06:48.999   312  2183 V AwesomePlayer: ~AwesomePlayer call
09-13 00:06:48.999   312  2183 V AwesomePlayer: reset_l() 
09-13 00:06:48.999   312  2183 V AwesomePlayer: cancelPlayerEvents
,09-13 00:06:48.999  7030  7137 V SoundPool: close(30)
09-13 00:06:49.000  7030  7137 V SoundPool: pointer = 0x9fe56000, size = 205080, sampleRate = 48000, numChannels = 2
,09-13 00:06:49.179  6756  6756 I UEI.SmartControl: Supports setup maps: true
09-13 00:06:49.182  6756  6756 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 00:06:49.182  6756  6756 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-13 00:06:49.182  6756  6756 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 00:06:49.182  6756  6756 I UEI.SmartControl: ### init IR Blaster...
,09-13 00:06:49.185  6756  6756 D serial_port: Configuring serial port
09-13 00:06:49.186  6756  6756 E UEI.SmartControl: UEIBLaster setting for 616
09-13 00:06:49.186  6756  6756 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 00:06:49.186  6756  6756 I UEI.SmartControl: configuring settings for MAXQ616
09-13 00:06:49.186  6756  6756 I UEI.SmartControl: Get version...
09-13 00:06:49.204  6756  7143 D UEI.SmartControl: serial port data available: 21
,09-13 00:06:49.231  6756  6756 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 00:06:49.231  6756  6756 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-13 00:06:49.231  6756  6756 I UEI.SmartControl: QS saving settings...
,09-13 00:06:49.233  6756  6756 D UEI.SmartControl: IR Blaster version: 25672567
09-13 00:06:49.249  6756  7143 D UEI.SmartControl: serial port data available: 4
,09-13 00:06:49.286  6756  7149 I UEI.SmartControl: Device manager: loading config....
,09-13 00:06:49.289  6756  6756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 00:06:49.290  6756  7149 D UEI.SmartControl: ----------- loading internal config...
09-13 00:06:49.293  6756  6756 E UEI.SmartControl: Services init done
09-13 00:06:49.293  6756  6756 D UEI.SmartControl: QS Service init finished
09-13 00:06:49.295  6756  6756 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 00:06:49.295  6756  6756 D UEI.SmartControl: QS Service version code: 201091
09-13 00:06:49.297  6756  6756 D UEI.SmartControl: Service requested: Control
09-13 00:06:49.302  6756  7149 E UEI.SmartControl: Loading SETTINGS...
09-13 00:06:49.302  6756  6756 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-13 00:06:49.307  6756  6756 D UEI.SmartControl: Internal service binding...
,09-13 00:06:49.309  7030  7030 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 00:06:49.311  6756  7149 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 00:06:49.311  6756  6771 I UEI.SmartControl: ------ IControl API: 11
09-13 00:06:49.311  6756  6771 D UEI.SmartControl: File observer start...
09-13 00:06:49.312  6756  6771 E UEI.SmartControl: IR Port is disabled: false
09-13 00:06:49.313  6756  6771 D UEI.SmartControl: Starting file observer...
09-13 00:06:49.315  6756  6771 I UEI.SmartControl: Registering callback...
,09-13 00:06:49.319  6756  6772 I UEI.SmartControl: ------ IControl API: 19
09-13 00:06:49.322  6756  6772 I UEI.SmartControl: Registering Services Ready callback...
09-13 00:06:49.322  6756  6772 I UEI.SmartControl: Notify client services are ready...
09-13 00:06:49.323  7030  7049 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 00:06:49.324  7030  7135 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 00:06:49.324  7030  7135 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 00:06:49.325  7030  7030 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 00:06:49.325  6756  7148 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 00:06:49.326  7030  7048 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 00:06:49.326  6756  7148 D UEI.SmartControl: -----service ready thread exits
09-13 00:06:49.326  7030  7135 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 00:06:49.326  7030  7135 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 00:06:49.327  7030  7030 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 00:06:49.327  6756  6771 I UEI.SmartControl: ------ IControl API: 8
,09-13 00:06:49.330  7030  7030 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 00:06:49.331  7030  7030 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 00:06:49.332  7030  7030 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 00:06:49.333  7030  7030 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 00:06:49.334  7030  7030 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 00:06:49.335  7030  7030 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 00:06:49.338  7030  7030 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 00:06:49.343  7030  7030 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
,09-13 00:06:49.344  7030  7030 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 00:06:49.347  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 00:06:49.348  7030  7030 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 00:06:49.348  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 00:06:49.350  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 00:06:49.352  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 00:06:49.352  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 00:06:49.354  7030  7030 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473718009354]
,09-13 00:06:49.362  7030  7030 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 00:06:49.366  1033  1988 I ActivityManager: Killing 6577:com.android.gallery3d/u0a27 (adj 15): empty #17
09-13 00:06:49.392  7030  7151 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 00:06:49.467  1033  1988 I ActivityManager: Killing 6548:com.lge.email/u0a23 (adj 15): empty #18
,09-13 00:06:49.589  1033  1939 W libprocessgroup: failed to open /acct/uid_10023/pid_6548/cgroup.procs: No such file or directory
,09-13 00:06:49.592  7030  7030 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-13 00:06:49.594  7030  7030 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 00:06:49.597  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 00:06:49.597  1033  1902 W libprocessgroup: failed to open /acct/uid_10027/pid_6577/cgroup.procs: No such file or directory
09-13 00:06:49.598  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 00:06:49.598  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,09-13 00:06:49.605  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 00:06:49.606  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-13 00:06:49.622  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 00:06:50.340  1033  2006 D WifiServiceImplEx: setWifiEnabled: true pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 00:06:50.342  1033  2006 D WifiService: setWifiEnabled: true pid=6853, uid=10118
09-13 00:06:50.342  1033  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 00:06:50.374  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:06:50.374  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:06:50.374  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:06:50.376  1033  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 00:06:50.376  1033  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-13 00:06:50.379  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini],
09-13 00:06:50.379  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-13 00:06:50.379  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-13 00:06:50.379  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 00:06:50.379  1033  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
09-13 00:06:50.379  1033  1389 E WifiHW  : unknown target_country: EU , set to default
,09-13 00:06:50.379  1033  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,09-13 00:06:50.379  1033  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-13 00:06:50.379  1033  1389 I WifiUtil: gEnableBmps=1
09-13 00:06:50.438  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-13 00:06:50.463  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,09-13 00:06:50.476  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:50.480  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:50.483  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:50.485  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:50.493  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 00:06:50.510  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,09-13 00:06:50.519  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:50.522  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:50.524  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 00:06:50.534  6424  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 00:06:50.554  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 00:06:50.568  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:50.598  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:50.646  1033  1572 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7181 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-13 00:06:50.653  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:50.653  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:50.665   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 21.334ms
,09-13 00:06:50.701   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 33.961ms
,09-13 00:06:50.722  7181  7181 I AppUp4:AppBoxCP: onCreate
09-13 00:06:50.723  7181  7181 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-13 00:06:50.723   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 20.242ms
09-13 00:06:50.732  7181  7181 I AppUp4:DB:  setFingerPrint start
09-13 00:06:50.733  7181  7181 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-13 00:06:50.741  7181  7181 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-13 00:06:50.741  7181  7181 I AppUp4:DB:  SDK version = 21
09-13 00:06:50.741  7181  7181 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 00:06:50.743  7181  7181 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-13 00:06:50.744  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 00:06:50.744  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:50.746  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 00:06:50.747  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 00:06:50.753  7181  7181 I AppUp4:CustModeStarterReceiver: onReceive
09-13 00:06:50.792  7181  7181 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:06:50.792  7181  7181 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 00:06:50.800  7181  7181 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18877e84
09-13 00:06:50.800  7181  7181 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 00:06:50.800  7181  7181 D AppUp4:CustFacade: isPhone : true
09-13 00:06:50.801  7181  7181 D AppUp4:CustModeStarterReceiver: begin check event
09-13 00:06:50.801  7181  7181 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 00:06:50.802  7181  7181 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 00:06:50.802  7181  7201 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 00:06:50.803  7181  7201 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 00:06:50.803  7181  7201 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-13 00:06:50.805  1033  1050 I ActivityManager: Killing 6636:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-13 00:06:50.879  1033  1903 W libprocessgroup: failed to open /acct/uid_10061/pid_6636/cgroup.procs: No such file or directory
09-13 00:06:50.882  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:50.883  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 00:06:50.888  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 00:06:50.891  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:50.901  4793  7210 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 00:06:50.913  4793  7211 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:50.914  4793  7211 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 00:06:50.962  1033  1572 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7212 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 00:06:51.058  7212  7212 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:06:51.059  7212  7212 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:06:51.062  7212  7212 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 00:06:51.064  7212  7212 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 00:06:51.068  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 00:06:51.068  1033  1109 D Tethering: InitialState.processMessage what=4
09-13 00:06:51.070  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:06:51.074   308   889 D SoftapController: Softap fwReload - Ok
,09-13 00:06:51.075  1033  1389 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (690ms)
09-13 00:06:51.077   308   889 D CommandListener: Setting iface cfg
09-13 00:06:51.077   308   889 D CommandListener: Trying to bring down wlan0
09-13 00:06:51.077   308   889 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:06:51.081  1033  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 00:06:51.076  7230  7230 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:51.076  7230  7230 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 00:06:51.110  7230  7230 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 00:06:51.135  7230  7230 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 00:06:51.135  7230  7230 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 00:06:51.158  7212  7212 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 00:06:51.171  7212  7212 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 00:06:51.182  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:06:51.182  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:06:51.182  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 00:06:51.182  1033  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 00:06:51.182  1033  1389 D WifiMonitor: connecting to supplicant
09-13 00:06:51.184  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:51.187  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-13 00:06:51.189  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:51.190  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:51.190  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 00:06:51.218  7212  7212 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 00:06:51.229  7230  7230 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 00:06:51.244  7212  7212 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:06:51.244  7212  7212 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 00:06:51.295  7230  7230 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 00:06:51.309  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-13 00:06:51.309  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 00:06:51.311  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 00:06:51.311  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 00:06:51.312  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 00:06:51.312  1033  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 00:06:51.313  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:51.313  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:51.313  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-13 00:06:51.315  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0,
,09-13 00:06:51.316  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 00:06:51.317  1033  7235 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 00:06:51.317  1033  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 00:06:51.317  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,09-13 00:06:51.317  1033  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 00:06:51.317  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 00:06:51.317  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 00:06:51.317  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 00:06:51.318  1033  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 00:06:51.318  1033  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 00:06:51.318  1033  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 00:06:51.319  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:06:51.319  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:06:51.319  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 00:06:51.319  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.319  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.319  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.320  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.320  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:51.321  1940  1940 D WfdService: Waiting for WifiP2p enabling
09-13 00:06:51.321  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:51.322  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 00:06:51.323  1033  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 00:06:51.323  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:06:51.323  1033  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:51.323  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:51.323  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:51.323  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:51.323  1033  1389 D WifiNative-wlan0: SET update_config 1: returned true
09-13 00:06:51.323  1033  1389 D WifiConfigStore: Loading config and enabling all networks 
09-13 00:06:51.323  1033  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 00:06:51.324  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:51.324  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:51.324  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:51.324  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:51.324  1033  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 00:06:51.330  1033  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 00:06:51.337  1033  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 00:06:51.338  1033  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 00:06:51.339  1033  1389 D WifiStateMachine: enableVerboseLogging : level 2
09-13 00:06:51.339  1033  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 00:06:51.339  1033  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 00:06:51.339  1033  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 00:06:51.340  1033  1389 D WifiNative-wlan0: SET manufacturer LGE: retur,ned true
09-13 00:06:51.340  1033  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 00:06:51.340  1033  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 00:06:51.340  1033  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 00:06:51.341  1033  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 00:06:51.341  1033  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 00:06:51.341  1033  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 00:06:51.341  1033  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 00:06:51.341  1033  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 00:06:51.341  1033  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 00:06:51.342  1033  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 00:06:51.343  1033  1389 D WifiStateMachine: Setting OUI to DA-A1-19
,09-13 00:06:51.343  1033  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 00:06:51.343  1940  1940 D WfdsService: Supplicant Connection state is changed : true
09-13 00:06:51.343  1940  2252 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 00:06:51.343  1940  2252 D WfdsService: Set the WFDS Monitor: true
09-13 00:06:51.343  1940  2252 D WfdsMonitor: WfdsMonitorThread create
09-13 00:06:51.343  1033  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 00:06:51.344  1033  1389 D WifiNative-HAL: Setting external_sim to 1
09-13 00:06:51.344  1033  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 00:06:51.344  1940  2252 D WfdsMonitor: WFDS Monitor is created and started
,09-13 00:06:51.344  1033  1389 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 00:06:51.344  1940  2252 D WfdsService: WiFi: Supplicant connection re-established
09-13 00:06:51.344  1033  1389 I WifiNative-HAL: startHal
09-13 00:06:51.344  1033  1389 D wifi    : setting scan oui 0xaf6cc5c0
09-13 00:06:51.344  1033  1389 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 00:06:51.344  1033  1389 I WifiNative-HAL: startHal
09-13 00:06:51.344  1033  1389 D wifi    : setting scan oui 0xaf6cc5c0
09-13 00:06:51.345  1033  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 00:06:51.346  1033  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 00:06:51.346  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 00:06:51.346  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 00:06:51.346  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 00:06:51.346  1940  7236 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 00:06:51.347  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 00:06:51.347  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 00:06:51.347  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 00:06:51.347  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 00:06:51.347  1940  7236 E CtrlSupplicant: Succeed to open control connection
09-13 00:06:51.347  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 00:06:51.347  1940  7236 E CtrlSupplicant: Succeed to open monitor connection
09-13 00:06:51.347  1940  7236 D WfdsMonitor: Supplicant connection established
09-13 00:06:51.347  1940  2252 D WfdsService: Connected to the supplicant for wfds
09-13 00:06:51.348  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 00:06:51.348  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 00:06:51.348  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 00:06:51.356  7212  7212 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 00:06:51.356  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 00:06:51.356  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 00:06:51.356  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 00:06:51.357  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 00:06:51.357  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 00:06:51.357  7230  7230 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-13 00:06:51.358  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 00:06:51.358  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 00:06:51.359  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 00:06:51.359  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 00:06:51.359  1033  1389 E WifiNative: : [183,358,626 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 00:06:51.359  1033  1389 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 00:06:51.360  1033  1389 D WifiNative-wlan0: RECONNECT: returned true
09-13 00:06:51.360  1033  1389 D WifiNative-wlan0: doString: [STATUS]
09-13 00:06:51.360  1033  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 00:06:51.360  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:06:51.360  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 00:06:51.360  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 00:06:51.360  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
09-13 00:06:51.360  1033  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.361  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 00:06:51.361  1033  1033 D RttService: SCAN_AVAILABLE : 3
09-13 00:06:51.361  1033  1554 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.361  1033  1553 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.361  1033  1553 I WifiNative-HAL: startHal
09-13 00:06:51.361  1033  1553 D wifi    : getting scan capabilities on interface[1] = 0xaf6cc5c0
09-13 00:06:51.361  1033  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 00:06:51.361  1033  1553 D wifi    : failed to get capabilities : -3
09-13 00:06:51.361  1033  1553 E WifiScanningService: could not get scan capabilities
09-13 00:06:51.362  1033  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 00:06:51.362  1033  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 00:06:51.362  1033  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 00:06:51.362   308   889 D CommandListener: Setting iface cfg
09-13 00:06:51.362   308   889 D CommandListener: Trying to bring up p2p0
09-13 00:06:51.362  1033  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 00:06:51.363  1033  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 00:06:51.363  1033  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 00:06:51.363  1033  1388 D LGWifiP2pService: P2pEnablingState
09-13 00:06:51.363  1033  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.363  1033  1388 D LGWifiP2pService: P2p socket connection successful
09-13 00:06:51.363  1033  1388 D LGWifiP2pService: P2pEnabledState
09-13 00:06:51.363  1033  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 00:06:51.363  1033  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 00:06:51.363  7230  7230 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 00:06:51.363  1033  1388 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 00:06:51.363  1033  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 00:06:51.363  1033  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 00:06:51.364  1033  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 00:06:51.364  1033  1389 E WifiStateMachine:  Driv,erStartedState what:132096 -100 0
09-13 00:06:51.364  1033  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 00:06:51.364  7230  7230 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 00:06:51.365  1033  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 00:06:51.365  1033  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 00:06:51.365  1033  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 00:06:51.365  1033  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 00:06:51.365  1033  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 00:06:51.365  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 00:06:51.365  1033  1388 D WifiNative-p2p0: SET device_name G3: returned true
09-13 00:06:51.365  1033  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 00:06:51.365  1033  1388 D LGWifiP2pService: before postfix = G3
09-13 00:06:51.365  1033  1388 D WifiServerServiceExt: postfix byte check : 2
09-13 00:06:51.365  1033  1388 D LGWifiP2pService: after postfix = G3
09-13 00:06:51.365  1033  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 00:06:51.366  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 00:06:51.366  1940  1940 D WfdsService: WifiP2pState is changed : true
09-13 00:06:51.366  1940  2252 D WfdsService: Receive the WFDS_ENABLE Method
09-13 00:06:51.366  1940  2252 D WfdsService: Set the WFDS Monitor: true
09-13 00:06:51.367  1940  2252 D WfdsService: Connected to the supplicant for wfds
09-13 00:06:51.367  1940  2252 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 00:06:51.367  7230  7230 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 00:06:51.367  1033  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 00:06:51.367  1033  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 00:06:51.367  1940  2252 D WfdsService: selectPreferredScanChannel [36]
09-13 00:06:51.367  1940  2252 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 00:06:51.368  1033  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 00:06:51.368  1033  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,09-13 00:06:51.369  1033  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 00:06:51.369  1033  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 00:06:51.370  1033  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 00:06:51.370  1033  1388 D WifiNative-HAL: p2pGetDeviceAddress
09-13 00:06:51.370  1033  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 00:06:51.371  1033  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 00:06:51.371  1033  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 00:06:51.371  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 00:06:51.372  1940  1940 D WfdsService: isConnected: false
09-13 00:06:51.373  1033  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 00:06:51.373  1033  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 00:06:51.373  1033  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 00:06:51.374  1033  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 00:06:51.374  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 00:06:51.374  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 00:06:51.374  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 00:06:51.374  1940  1940 D WfdsService: Update P2p Interface State: 3
09-13 00:06:51.374  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.375  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 00:06:51.375  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.375  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.375  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.375  7230  7230 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 00:06:51.375  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.376  1033  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 00:06:51.376  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.376  1940  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.376  1940  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.377  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.377  1033  7235 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.377  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.377  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.377  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.377  1033  7235 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.377  1033  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 00:06:51.377  1033  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 00:06:51.377  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.377  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.377  1033  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 00:06:51.378  1033  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 00:06:51.380  1033  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,09-13 00:06:51.380  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 00:06:51.397  3207  3207 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-13 00:06:51.398  3207  3207 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:51.398  1033  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 00:06:51.398  1033  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 00:06:51.398  3207  3207 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 00:06:51.398  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 00:06:51.398  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:06:51.398  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 00:06:51.398  1033  1388 D LGWifiP2pService: InactiveState
09-13 00:06:51.398  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:06:51.398  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:06:51.398  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:06:51.398  1033  1388 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.398  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.399  1033  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 00:06:51.399  1033  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 00:06:51.399  1033  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-13 00:06:51.400  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 00:06:51.400  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.401  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 00:06:51.401  7230  7230 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 00:06:51.401  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.402  1033  7235 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.402  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.402  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:06:51.402  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.402  1033  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 00:06:51.402  1033  1388 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.403  1033  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:51.404  1033  1033 E WifiServerServiceExt: No p2p device connected
09-13 00:06:51.404  7212  7212 I HubEmail: JNI_OnLoad()
09-13 00:06:51.404  7212  7212 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 00:06:51.404  7212  7212 I HubEmail: registerNatives()
09-13 00:06:51.404  7212  7212 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 00:06:51.404  7212  7212 I HubEmail: registerNativeMethods()
09-13 00:06:51.404  7212  7212 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 00:06:51.404  7212  7212 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-13 00:06:51.404  1940  7236 D WfdsMo,nitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 00:06:51.404  1940  2252 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 00:06:51.404  1940  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.405  1940  7236 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.405  1033  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 00:06:51.405  1033  1389 D WifiNative-wlan0: doBoolean: SCAN
09-13 00:06:51.405  1033  1389 D WifiNative-wlan0: SCAN: returned false
09-13 00:06:51.405  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=183405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 00:06:51.406  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.406  1033  7235 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.406  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.406  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.407  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:06:51.407  1033  7235 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.407  1033  7235 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.407  1033  7235 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:06:51.432  1033  1938 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7242 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-13 00:06:51.435  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=183434  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 00:06:51.435  1033  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:06:51.436  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.436  1033  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:06:51.436  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.436  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 00:06:51.436  1033  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:06:51.437  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:51.437  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:51.437  1033  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:06:51.437  1033  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:06:51.438  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:51.439  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:51.439  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 00:06:51.441  7077  7239 W FormManager: Network not available. Please check & try again.
09-13 00:06:51.443  7212  7241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.443  7077  7240 V FormManager: Network unavailable.
09-13 00:06:51.448  7077  7240 V FormManager: Network unavailable.
,09-13 00:06:51.457  1033  1572 I ActivityManager: Killing 6682:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-13 00:06:51.481  1033  1939 W libprocessgroup: failed to open /acct/uid_10080/pid_6682/cgroup.procs: No such file or directory
,09-13 00:06:51.530  7242  7242 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:06:51.530  7242  7242 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:06:51.532  7242  7242 D PhoneMonitor: Register our PhoneStateListener
,09-13 00:06:51.552  7242  7242 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 00:06:51.558  7242  7242 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 00:06:51.579  7242  7242 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-13 00:06:51.580  7242  7242 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 00:06:51.582  7242  7242 D TelephonyAutoProfiling: [parse] Load xml
09-13 00:06:51.589  7242  7242 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 00:06:51.589  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 00:06:51.590  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 00:06:51.590  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 00:06:51.590  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 00:06:51.590  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 00:06:51.590  7242  7242 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
,09-13 00:06:51.590  7242  7242 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-13 00:06:51.604  7242  7242 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-13 00:06:51.632  1033  1050 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7262 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 00:06:51.633  1033  1050 I ActivityManager: Killing 6167:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-13 00:06:51.678  1033  2006 W libprocessgroup: failed to open /acct/uid_10097/pid_6167/cgroup.procs: No such file or directory
,09-13 00:06:51.858  1033  2006 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7287 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 00:06:51.860  1033  2006 I ActivityManager: Killing 6701:com.lge.eula/1000 (adj 15): empty #17
09-13 00:06:51.899  7230  7230 E wpa_supplicant: USIM:  scard_init function
,09-13 00:06:51.899  7230  7230 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 00:06:51.902  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 00:06:51.902  1033  7235 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 00:06:51.902  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 00:06:51.903  1033  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 00:06:51.904  1033  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 00:06:51.904  1033  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 00:06:51.905  1033  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 00:06:51.905  1033  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 00:06:51.906  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-13 00:06:51.906  1033  7235 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 00:06:51.906  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 00:06:51.906  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 00:06:51.912  1033  1973 W libprocessgroup: failed to open /acct/uid_1000/pid_6701/cgroup.procs: No such file or directory
,09-13 00:06:51.919  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183918  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 00:06:51.921  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:51.921  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:51.923  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.923  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.923  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 00:06:51.924  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:51.930  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183929  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 00:06:51.934  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.934  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:51.934  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 00:06:51.944  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:51.944  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-13 00:06:51.952  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:51.953  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:51.954  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.014  7230  7230 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 00:06:52.018  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-13 00:06:52.018  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 00:06:52.018  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 00:06:52.018  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 00:06:52.018  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:06:52.018  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:06:52.019  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=184018  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 00:06:52.019  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=184018  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 00:06:52.020  1033  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=184019
09-13 00:06:52.020  1033  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=184019
09-13 00:06:52.021  1033  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=184020
09-13 00:06:52.021  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=184020
09-13 00:06:52.021  1033  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=184021
09-13 00:06:52.022  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=184021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 00:06:52.030  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:06:52.030  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:06:52.031  7230  7230 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 00:06:52.031  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 00:06:52.031  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 00:06:52.031  1033  7235 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 00:06:52.031  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 00:06:52.031  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 00:06:52.031  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 00:06:52.032  1033  7235 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-13 00:06:52.034  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:06:52.034  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 00:06:52.055  1033  2030 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7315 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 00:06:52.057  1033  2030 I ActivityManager: Killing 6730:com.lge.bnr/1000 (adj 15): empty #17
09-13 00:06:52.120  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 00:06:52.123  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.123  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:52.124  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.129  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.129  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.130  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-13 00:06:52.144  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=184143  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 00:06:52.145  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=184144  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 00:06:52.146  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=184145  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 00:06:52.146  1033  1592 W libprocessgroup: failed to open /acct/uid_1000/pid_6730/cgroup.procs: No such file or directory
,09-13 00:06:52.147  1033  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=184146
09-13 00:06:52.147  1033  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=184146
09-13 00:06:52.148  1033  1389 D WifiNative-wlan0: doString: [STATUS]
09-13 00:06:52.148  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:06:52.148  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:06:52.149  1033  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 00:06:52.151  1033  1389 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 00:06:52.153  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.153  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.153  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 00:06:52.153  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:52.153  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 00:06:52.157  1033  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 00:06:52.157  1033  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 00:06:52.157  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.157  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:52.160  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:06:52.162  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.162  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.162  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.162  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:52.162  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 00:06:52.164  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.167  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.167  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.168  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 00:06:52.171  1033  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 00:06:52.171  1033  1440 D ConnectivityService: Got NetworkAgent Messenger
09-13 00:06:52.171  1033  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:06:52.171  1033  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 00:06:52.171  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 00:06:52.171  1033  1440 D ConnectivityService: NetworkAgent connected
09-13 00:06:52.172  1033  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 00:06:52.172  1033  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 00:06:52.182  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 00:06:52.182  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:52.184  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.186  1033  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 00:06:52.187  1033  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:06:52.187  1033  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 00:06:52.188  1033  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 00:06:52.188  1033  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 00:06:52.192  7315  7315 I art     : Almond Protected OAT
09-13 00:06:52.195  1033  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 00:06:52.196   308   889 D CommandListener: Setting iface cfg
09-13 00:06:52.200  1033  1389 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 00:06:52.200  1033  7334 D DhcpStateMachine: StoppedState
09-13 00:06:52.201  1033  7334 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.201  1033  7334 D DhcpStateMachine: WaitBeforeStartState
09-13 00:06:52.201  1033  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=184200  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:06:52.201  1033  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=184201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:06:52.202  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=184201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:06:52.203  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,09-13 00:06:52.203  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:52.204  1033  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:52.205  1033  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:52.205  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:52.206  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:52.207  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:52.207  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 00:06:52.207  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:52.208  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 00:06:52.208  1033  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=184207  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:06:52.209  1033  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=184208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:06:52.209  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=184208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:06:52.210  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:137605] from screen [on:0 period:544229682] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 00:06:52.211  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:544229683] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 00:06:52.211  1033  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 00:06:52.215  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.215  1033  1440 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 00:06:52.216  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 00:06:52.217  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.217  1033  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.218  1033  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.218  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.219  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.219  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 00:06:52.219  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=142,0,0
09-13 00:06:52.220  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=142,0,0
09-13 00:06:52.220  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 00:06:52.220  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 00:06:52.221  1033  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 00:06:52.221  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 00:06:52.221  1033  1389 D WifiNative-wlan0: SET ps 0: returned true
09-13 00:06:52.221  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 00:06:52.221  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 00:06:52.222  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 00:06:52.222  1033  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 00:06:52.222  1033  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 00:06:52.222  1033  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cea4cf1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.222  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cea4cf1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.222  1033  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 00:06:52.222  1033  7334 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.222  1033  7334 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 00:06:52.223   308   889 D CommandListener: Setting iface cfg
09-13 00:06:52.223   308   889 D CommandListener: Trying to bring up wlan0
09-13 00:06:52.224  1033  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 00:06:52.225  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:52.225  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 00:06:52.225  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.226  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.226  1033  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 00:06:52.227  1033  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
09-13 00:06:52.227  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.227  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:52.228  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 00:06:52.228  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 00:06:52.228  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-13 00:06:52.228  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 00:06:52.229  1033  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.229  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.229  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 00:06:52.229  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 00:06:52.229  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 00:06:52.229  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,09-13 00:06:52.230  1033  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 00:06:52.230  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:06:52.248  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
09-13 00:06:52.248  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 00:06:52.249  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 00:06:52.249  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 00:06:52.249  1033  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-13 00:06:52.250  1033  1440 D ConnectivityService: ignoring duplicate network state non-change
09-13 00:06:52.250  7315  7315 D WeatherApplication: removeAccount
,09-13 00:06:52.252  7315  7315 D WeatherApplication: Account.length = 0
09-13 00:06:52.252  7315  7315 E WeatherApplication: OPERATOR:OPEN
09-13 00:06:52.254  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.254  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:52.256  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.256  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.257  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.257  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 00:06:52.258  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 00:06:52.259  1033  1440 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 00:06:52.262  7315  7315 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:52
09-13 00:06:52.266  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.266  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.266  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 00:06:52.267  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 00:06:52.270  7315  7315 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 00:06:52.270  7315  7315 D Weather.Utils: 2 : All the weather widget is gone.
09-13 00:06:52.270  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 00:06:52.272  7315  7315 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 00:06:52.274  7315  7315 D WeatherAncestor: connectivity changed - connection : true
09-13 00:06:52.275  7315  7315 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 00:06:52.277  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.277  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.277  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-13 00:06:52.278  1033  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 00:06:52.281  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 00:06:52.281  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.281  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:52.282  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.282  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:52.282  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 00:06:52.282  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.286  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.286  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 00:06:52.287  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.287  7315  7315 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 00:06:52.287  7315  7315 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 00:06:52.288  1033  1440 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 00:06:52.288  1033  1440 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 00:06:52.288  7315  7315 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-13 00:06:52.289  1033  1440 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 00:06:52.289   308   889 E Netd    : netlink response contains error (File exists)
09-13 00:06:52.291  1033  1440 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 00:06:52.291  1033  1440 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 00:06:52.291  1033  1440 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 00:06:52.291  1033  1440 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 00:06:52.292  1033  1440 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 00:06:52.292  1033  1440 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.292  1033  1440 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.292  1033  1440 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.292  1033  1440 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:06:52.292  1033  1440 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:52.292  1033  1440 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 00:06:52.292  1033  1440 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.292  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.293  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 00:06:52.293  1033  1440 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 00:06:52.293  1033  1440 D ConnectivityService: currentScore = 0, newScore = 20
09-13 00:06:52.293  1033  1440 D ConnectivityService:    accepting network in place of null
09-13 00:06:52.293  1033  1440 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.293  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.293  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 00:06:52.293  1033  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.293  1033  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:06:52.294  1033  1440 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 00:06:52.295  1033  1440 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI (,) - 101] isDefaultNetwork=true
09-13 00:06:52.295  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:06:52.295  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.295  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 00:06:52.296   308  7339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 00:06:52.296  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:52.296  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 00:06:52.297  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.299  1033  1440 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:52.299  1033  1440 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 00:06:52.299  1033  1440 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 00:06:52.299  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 00:06:52.300  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 00:06:52.300  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 00:06:52.300  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-13 00:06:52.301  1033  1440 D ConnectivityService: validation of new default Network = false
09-13 00:06:52.301  1033  1440 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 00:06:52.302  1033  1440 D DSQN    : enableDataServiceNotify 
09-13 00:06:52.302  1033  1440 D DSQN    : start dsqn bin
09-13 00:06:52.315  7315  7315 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 00:06:52.315  7315  7315 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:52
,09-13 00:06:52.319  1033  1440 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.319  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.319  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:52.319  1033  1440 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:52.306  7341  7341 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:52.306  7341  7341 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:52.321  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 00:06:52.326  1033  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-13 00:06:52.343  7341  7341 E DSQN    : DSQN ssw
,09-13 00:06:52.350   308  7339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 00:06:52.351  1033  1939 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7345 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 00:06:52.351  1033  1939 I ActivityManager: Killing 2128:com.lge.music/u0a34 (adj 15): empty #17
09-13 00:06:52.362   312  1400 V AudioFlinger: 2128 died, releasing its sessions
09-13 00:06:52.362   312  1400 V AudioFlinger:  pid 1850 @ 0
09-13 00:06:52.362   312  1400 V AudioFlinger:  pid 3207 @ 1
09-13 00:06:52.362   312  1400 V AudioFlinger:  pid 3207 @ 2
,09-13 00:06:52.381   308  7339 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 00:06:52.389  1033  2031 W libprocessgroup: failed to open /acct/uid_10034/pid_2128/cgroup.procs: No such file or directory
09-13 00:06:52.389  1815  7340 I CheckinService: active receiver: enabled
,09-13 00:06:52.403   308   888 D LGDataListener: argv[0]=dsqncommand
09-13 00:06:52.403   308   888 D LGDataListener: argv[1]=wlan0
09-13 00:06:52.403   308   888 D LGDataListener: argv[2]=1
,09-13 00:06:52.403   308   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 00:06:52.404  1033  1107 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 00:06:52.404  1033  1107 D DSQN    : start to monitor internet connection
,09-13 00:06:52.424  1033  7334 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 00:06:52.424  1033  7334 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 00:06:52.424  1033  7334 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 00:06:52.425  1815  7340 I CheckinService: Preparing to send checkin request
09-13 00:06:52.425  1815  7340 I EventLogService: Accumulating logs since 1473717871542
09-13 00:06:52.416  7364  7364 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:52.416  7364  7364 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:52.431  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 22:06:52 GMT], X-Android-Received-Millis=[1473718012431], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473718012403]}
09-13 00:06:52.431  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 00:06:52.431  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 00:06:52.431  1033  1440 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.431  1033  1440 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.432  1033  1440 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:06:52.432  1033  1440 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:52.432  1033  1440 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 00:06:52.432  1033  1440 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 00:06:52.432  1033  1440 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 00:06:52.432  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.432  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:52.432  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:06:52.432  1033  1440 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:52.432  1033  1440 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.433  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 00:06:52.433  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.433  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.433  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 00:06:52.434  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 00:06:52.434  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.435  1033  1389 D WIFI    : new score 60 for exisiting, request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:52.435  1033  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 00:06:52.436  7364  7364 I dhcpcd  : version 5.5.6 starting
09-13 00:06:52.438  7364  7364 E dhcpcd  : get_duid: m
09-13 00:06:52.438  7364  7364 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 00:06:52.438  7364  7364 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 00:06:52.451  1033  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.451  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:52.451  1033  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:06:52.457  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:06:52.458  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.459  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:52.466  1033  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 00:06:52.467  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 00:06:52.467  1033  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 00:06:52.467  1033  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 00:06:52.468  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 00:06:52.468  1033  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 00:06:52.484  7364  7364 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 00:06:52.548  7364  7364 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-13 00:06:52.548  7364  7364 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 00:06:52.549  7364  7364 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 00:06:52.549  7364  7364 D dhcpcd  : wlan0: sending REQUEST (xid 0xa99e1f2a), next in 4.75 seconds
09-13 00:06:52.567  1815  7340 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 00:06:52.591  1033  2006 I art     : Explicit concurrent mark sweep GC freed 103558(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 2.079ms total 158.734ms
,09-13 00:06:52.645  1033  1903 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7373 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-13 00:06:52.671   278   423 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-13 00:06:52.671   278   423 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 00:06:52.671   278   423 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 00:06:52.671  7345  7389 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 00:06:52.673   278   423 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 00:06:52.673   278   423 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 00:06:52.673   278   423 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 00:06:52.674  7345  7389 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 00:06:52.687   278   423 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 00:06:52.687   278   423 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 00:06:52.687   278   423 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:06:52.690  7345  7394 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 00:06:52.697   278   423 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 00:06:52.697   278   423 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 00:06:52.697   278   423 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 00:06:52.697  7345  7394 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 00:06:52.708  7373  7373 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 00:06:52.708  7373  7373 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 00:06:52.733  7373  7373 I MultiDex: VM with version 2.1.0 has multidex support
09-13 00:06:52.734  7373  7373 I MultiDex: install
09-13 00:06:52.734  7373  7373 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 00:06:52.741  7373  7373 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-13 00:06:52.888  7345  7345 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 00:06:52.896  7345  7345 I LibraryLoader: Loading: webviewchromium
09-13 00:06:52.899  7345  7345 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4909-4913)
09-13 00:06:52.899  7345  7345 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 00:06:52.909  7345  7345 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d8b927f}
,09-13 00:06:52.912  7345  7345 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 00:06:52.913  7345  7345 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 00:06:52.938  7345  7345 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 00:06:52.939  7345  7345 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 00:06:52.950  7345  7345 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 00:06:52.951  7345  7345 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 00:06:52.952  7345  7345 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-13 00:06:52.956   312  2174 V AudioPolicyService: registerClient() client 0xb1427180, uid 10093
09-13 00:06:52.956  7345  7419 W AudioManagerAndroid: Requires BLUETOOTH permission
09-13 00:06:52.965  7345  7345 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 00:06:52.965  7345  7345 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 00:06:52.965  7345  7345 I Adreno-EGL: Build Date: 12/12/14 금
09-13 00:06:52.965  7345  7345 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 00:06:52.965  7345  7345 I Adreno-EGL: Remote Branch: 
09-13 00:06:52.965  7345  7345 I Adreno-EGL: Local Patches: 
09-13 00:06:52.965  7345  7345 I Adreno-EGL: Reconstruct Branch: 
09-13 00:06:53.019  7345  7345 I NSApplication: Starting up...
,09-13 00:06:53.068  1033  1988 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7432 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 00:06:53.069  1033  1988 I ActivityManager: Killing 6597:com.android.vending/u0a44 (adj 15): empty #17
,09-13 00:06:53.197  1033  1973 W libprocessgroup: failed to open /acct/uid_10044/pid_6597/cgroup.procs: No such file or directory
,09-13 00:06:53.227  7449  7449 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 00:06:53.236  7432  7432 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:06:53.276  7449  7449 I dex2oat : dex2oat took 48.930ms (threads: 4)
,09-13 00:06:53.285  7373  7391 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 00:06:53.285  7373  7391 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 00:06:53.285  7373  7391 I Adreno-EGL: Build Date: 12/12/14 금
09-13 00:06:53.285  7373  7391 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 00:06:53.285  7373  7391 I Adreno-EGL: Remote Branch: 
09-13 00:06:53.285  7373  7391 I Adreno-EGL: Local Patches: 
09-13 00:06:53.285  7373  7391 I Adreno-EGL: Reconstruct Branch: 
09-13 00:06:53.319  1033  1440 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 00:06:53.379  1033  2030 D WifiServiceImplEx: setWifiEnabled: false pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 00:06:53.379  1033  2030 D WifiService: setWifiEnabled: false pid=6853, uid=10118
09-13 00:06:53.379  1033  2030 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 00:06:53.395  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:06:53.395  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:06:53.395  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,09-13 00:06:53.398  1033  1389 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-13 00:06:53.399  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:53.399  1033  1389 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:53.399  1033  1389 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:53.400  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 00:06:53.400  1033  1389 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 00:06:53.400  1033  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:06:53.400  1033  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 00:06:53.400  7373  7391 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:06:53.400  7373  7391 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:06:53.401  1033  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 00:06:53.401  1033  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 00:06:53.406  1033  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 00:06:53.406  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 00:06:53.407  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 00:06:53.407  1033  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.407  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.407  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 00:06:53.407  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:06:53.408  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
09-13 00:06:53.408   308   889 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:06:53.420  7373  7391 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 00:06:53.420  7373  7391 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 00:06:53.420  7373  7391 I Adreno-EGL: Build Date: 12/12/14 금
09-13 00:06:53.420  7373  7391 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 00:06:53.420  7373  7391 I Adreno-EGL: Remote Branch: 
09-13 00:06:53.420  7373  7391 I Adreno-EGL: Local Patches: 
09-13 00:06:53.420  7373  7391 I Adreno-EGL: Reconstruct Branch: 
,09-13 00:06:53.435  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 00:06:53.435  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-13 00:06:53.438  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-13 00:06:53.439  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.440  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.440  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:53.447  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-13 00:06:53.448  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:53.448  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:53.458  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:06:53.460  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-13 00:06:53.460  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.460  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.460  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:53.461  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 00:06:53.461  1033  1033 D RttService: SCAN_AVAILABLE : 1
09-13 00:06:53.461  1033  1554 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.462  1033  1388 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.462  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.462  1033  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2dc2d6c2
09-13 00:06:53.462  1033  1388 D LGWifiP2pService: P2pDisablingState
09-13 00:06:53.462  1033  1388 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.462  1033  1388 D LGWifiP2pService: p2p socket connection lost
09-13 00:06:53.462  1033  1388 D LGWifiP2pService: P2pDisabledState
09-13 00:06:53.463  1033  1553 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.464  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 00:06:53.464  1940  1940 D WfdsService: WifiP2pState is changed : false
09-13 00:06:53.464  1940  2252 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 00:06:53.464  1940  2252 D WfdsService: Set the WFDS Monitor: false
09-13 00:06:53.465  1940  2252 D WfdsMonitor: WFDS Monitor is stopped
09-13 00:06:53.465  1940  2252 D WfdsService: STATE : WfdsDisabledState - enter
09-13 00:06:53.465  1940  7236 D CtrlSupplicant: Received on exit socket, terminate
09-13 00:06:53.465  1940  7236 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 00:06:53.466  1940  7236 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 00:06:53.466  1940  7236 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 00:06:53.466  1940  2253 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 00:06:53.467  1940  2252 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 00:06:53.469  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:53.470  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:53.470  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:53.470  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:53.471  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:53.471  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:06:53.471  1033  1389 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 00:06:53.474  1033  1389 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 00:06:53.474  1033  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.474  1033  1388 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.474  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 00:06:53,.475  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 00:06:53.475  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 00:06:53.475  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:06:53.475  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
,09-13 00:06:53.484  7373  7391 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 00:06:53.484  7373  7391 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 00:06:53.484  7373  7391 I Adreno-EGL: Build Date: 12/12/14 금
09-13 00:06:53.484  7373  7391 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 00:06:53.484  7373  7391 I Adreno-EGL: Remote Branch: 
09-13 00:06:53.484  7373  7391 I Adreno-EGL: Local Patches: 
09-13 00:06:53.484  7373  7391 I Adreno-EGL: Reconstruct Branch: 
09-13 00:06:53.484  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:53.484  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:53.485  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.487   308   889 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:06:53.487  1033  1440 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 00:06:53.487  1033  1440 D DSQN    : disableDataServiceNotify
09-13 00:06:53.487  1033  1440 D DSQN    : stop dsqn bin
09-13 00:06:53.489  1033  1389 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 00:06:53.489  1033  1389 D WifiNative-p2p0: TERMINATE: returned true
09-13 00:06:53.489  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:06:53.489  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:06:53.489  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 00:06:53.493  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-13 00:06:53.493  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.493  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.494  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:06:53.494  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 00:06:53.495  1033  1440 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 00:06:53.495  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:53.495  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:53.495  1033  1440 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:06:53.495  1033  1440 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 00:06:53.496  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.496  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:53.496  1033  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 00:06:53.496  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 00:06:53.497  1033  1440 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 00:06:53.497  1033  1440 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 00:06:53.497  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:06:53.499  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 00:06:53.499  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:06:53.499  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 00:06:53.500  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 00:06:53.500  1033  1440 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:53.500  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:06:53.501  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 00:06:53.501  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor,:     - is Wi-Fi Direct supported: true
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:53.501  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:53.502  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:53.502  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:53.502  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 00:06:53.502  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 00:06:53.502  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 00:06:53.503  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:53.503  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:06:53.503  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:53.503  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:53.503  1033  1440 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:53.503  1033  1440 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:53.503  1033  1440 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:53.503  1033  1440 D NetworkManagementService: Removing idletimer
09-13 00:06:53.503  1033  1440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.504  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VP,N] ]
09-13 00:06:53.504  1033  1440 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 00:06:53.504  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 00:06:53.504  1033  1389 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:53.504  1033  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:06:53.505  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 00:06:53.505  1033  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 00:06:53.505  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 00:06:53.505  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 00:06:53.505  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 00:06:53.507  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 00:06:53.507  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:06:53.509  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.511  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.535  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:06:53.536  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.536  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:06:53.552  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:06:53.553  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.554  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.575  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 00:06:53.576  6424  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 00:06:53.587  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:53.593  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-13 00:06:53.593  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:53.593  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 00:06:53.593  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 00:06:53.597  7181  7181 I AppUp4:CustModeStarterReceiver: onReceive
09-13 00:06:53.600  7181  7181 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18877e84
09-13 00:06:53.600  7181  7181 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 00:06:53.600  7181  7181 D AppUp4:CustFacade: isPhone : true
09-13 00:06:53.601  7181  7181 D AppUp4:CustModeStarterReceiver: begin check event
09-13 00:06:53.601  7181  7181 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 00:06:53.604  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:53.604  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 00:06:53.606  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 00:06:53.608  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:53.611  4793  7475 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:06:53.614  7212  7212 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 00:06:53.616  4793  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:53.617  4793  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 00:06:53.623  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 00:06:53.623  7230  7230 I wpa_supplicant: monitor socket send errors count : 1
09-13 00:06:53.623  7230  7230 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
,09-13 00:06:53.625  1033  7235 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 00:06:53.625  1033  7235 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 00:06:53.634  3207  3207 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 00:06:53.634  3207  3207 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:53.634  3207  3207 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 00:06:53.635  7212  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:06:53.637  7242  7242 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 00:06:53.637  7242  7242 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 00:06:53.644  7077  7483 V FormManager: Network unavailable.
09-13 00:06:53.648  7077  7482 W FormManager: Network not available. Please check & try again.
,09-13 00:06:53.649  7077  7483 V FormManager: Network unavailable.
09-13 00:06:53.654  7315  7315 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:53
09-13 00:06:53.657  7315  7315 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 00:06:53.657  7315  7315 D Weather.Utils: 2 : All the weather widget is gone.
09-13 00:06:53.658  7315  7315 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 00:06:53.658  7315  7315 D WeatherAncestor: connectivity changed - connection : true
09-13 00:06:53.658  7315  7315 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d1262a2
09-13 00:06:53.659  7315  7315 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 00:06:53.659  7315  7315 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 00:06:53.659  7315  7315 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 00:06:53.659  7315  7315 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 00:06:53.659  7315  7315 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:53
09-13 00:06:53.664  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 00:06:53.665  7230  7230 W wpa_supplicant: USIM:  scard_deinit function
09-13 00:06:53.665  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-13 00:06:53.665  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 00:06:53.665  1033  7235 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 00:06:53.665  1033  7235 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 00:06:53.666  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:06:53.666  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:06:53.666  1033  1389 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185666
09-13 00:06:53.667  1033  1389 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185666
09-13 00:06:53.667  1033  1389 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185667  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 00:06:53.668  1033  1389 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185667  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 00:06:53.666  1033  1109 D Tethering: InitialState.processMessage what=4
09-13 00:06:53.669  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:06:53.670  1033  1389 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:53.671  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:06:53.687  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 00:06:53.687  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 00:06:53.687  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-13 00:06:53.687  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 00:06:53.687  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 00:06:53.688  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 00:06:53.688   308  7489 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 00:06:53.688  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 00:06:53.688  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 00:06:53.688  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 00:06:53.688  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 00:06:53.688  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 00:06:53.688  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 00:06:53.692  1815  7340 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-13 00:06:53.698  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:53.701  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:53.703  1815  7340 I CheckinService: active receiver: disabled
09-13 00:06:53.707  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:53.715  7077  7491 W FormManager: Network not available. Please check & try again.
,09-13 00:06:53.726  7077  7492 V FormManager: Network unavailable.
09-13 00:06:53.731  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:06:53.733  7077  7492 V FormManager: Network unavailable.
09-13 00:06:53.736  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 00:06:53.740  7077  7493 W FormManager: Network not available. Please check & try again.
09-13 00:06:53.742  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 00:06:53.747  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 00:06:53.754  1033  7235 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 00:06:53.754  1033  7235 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 00:06:53.754  1033  7235 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 00:06:53.756  1033  1389 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-13 00:06:53.758  1033  1389 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 00:06:53.758  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:06:53.758  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:06:53.758  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 00:06:53.758  1940  1940 D WfdsService: Supplicant Connection state is changed : false
09-13 00:06:53.759  1940  2252 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 00:06:53.759  1940  2252 D WfdsService: Set the WFDS Monitor: false
09-13 00:06:53.759  1940  2252 D WfdsMonitor: WFDS Monitor is stopped
09-13 00:06:53.759  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:06:53.760  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 00:06:53.761  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:06:53.761  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 00:06:53.762  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 00:06:53.762  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:53.762  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:53.762  1033  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 00:06:53.762  1033  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 00:06:53.763  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:53.763  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network ty,pe is Wi-Fi: false
09-13 00:06:53.763  2467  2467 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:53.767  7077  7494 V FormManager: Network unavailable.
09-13 00:06:53.768  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:53.771  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:53.775  4793  7495 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:06:53.779  4793  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:06:53.779  4793  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 00:06:53.807  1033  2006 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7497 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 00:06:53.810  7077  7494 V FormManager: Network unavailable.
,09-13 00:06:53.889  7497  7497 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 00:06:53.890  7497  7497 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 00:06:53.900  7497  7497 V [BNRBootReceiver]: Boot Receiver Return
09-13 00:06:53.906  7497  7497 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 00:06:53.907  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:06:53.917  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:53.924  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 00:06:53.935  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:53.935  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:53.938  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 00:06:53.945  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 00:06:53.948  6956  6956 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 00:06:53.954  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:06:53.967  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:53.974  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:53.983  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:53.984  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:53.987  1033  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1005529436, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
09-13 00:06:53.987  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 00:06:53.994  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.012  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.023  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.032  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 00:06:54.032  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:54.033  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:06:54.042  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.051  2622  2622 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 00:06:54.060  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:06:54.065  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 00:06:54.075  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.076  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:54.076  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:06:54.082  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:06:54.091  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:06:54.097  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.102  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.103  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:54.103  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 00:06:54.105  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.112  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.117  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.122  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.122  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:54.123  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:06:54.125  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.132  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.140  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.147  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.147  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:54.147  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 00:06:54.155  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.166  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.173  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.182  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.183  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:54.190  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:06:54.196  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.208  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.216  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.229  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 00:06:54.230  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:54.232  7030  7030 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:06:54.240  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.248  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 00:06:54.262  1033  1423 D WifiService: New client listening to asynchronous messages
,09-13 00:06:54.265  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:54.275  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.287  6756  7150 D UEI.SmartControl: Internal timer expired: 2
09-13 00:06:54.287  6756  7150 D UEI.SmartControl: unbind internal service
,09-13 00:06:54.291  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.306  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.307  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:54.309  7030  7030 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 00:06:54.311  7030  7030 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 00:06:54.312  7030  7030 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 00:06:54.322  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:06:54.335  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 00:06:54.336  6756  7144 D serial_port: close(fd = 24)
09-13 00:06:54.338  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:06:54.343  6756  7144 I UEI.SmartControl: Serial port is closed.
09-13 00:06:54.346  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.357  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.368  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 00:06:54.369  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:54.371  7030  7030 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 00:06:54.372  7030  7030 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 00:06:54.373  7030  7030 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 00:06:54.378  1033  1988 I ActivityManager: Killing 6981:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-13 00:06:54.593  1033  1939 W libprocessgroup: failed to open /acct/uid_10037/pid_6981/cgroup.procs: No such file or directory
,09-13 00:06:54.601  2199  2199 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-13 00:06:54.614  2199  2199 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-13 00:06:54.617  2199  2199 D c       : Getting all permits...
09-13 00:06:54.617  2199  2199 D a       : Opening database...
09-13 00:06:54.626  2199  2199 D a       : Opening database auth.proximity.permit_store...
09-13 00:06:54.627  2199  2199 D a       : Closing database...
,09-13 00:06:54.640  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:06:54.646  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 00:06:54.646  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:54.646  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:54.650  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.658  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.665  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 00:06:54.665  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:06:54.667  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 00:06:54.672  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.679  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 00:06:54.679  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:54.679  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:06:54.687  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:06:54.691  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.697  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.697  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:54.699  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 00:06:54.701  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:06:54.704  7001  7001 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 00:06:54.704  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:54.704  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:54.709  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:06:54.714  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.720  7030  7030 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:06:54.720  7030  7030 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:06:54.723  7030  7030 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 00:06:54.730  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:54.733  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:54.738  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.738  7077  7522 W FormManager: Network not available. Please check & try again.
09-13 00:06:54.751  2199  2199 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 00:06:54.758  7077  7523 V FormManager: Network unavailable.
09-13 00:06:54.760  7077  7523 V FormManager: Network unavailable.
09-13 00:06:54.768  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:06:54.768  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 00:06:54.769  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:54.771  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:54.777  4793  7524 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:06:54.778  7001  7001 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,09-13 00:06:54.778  7001  7001 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 00:06:54.778  7001  7001 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:06:54.782  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:54.787  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:06:54.790  4793  7526 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:06:54.790  4793  7526 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 00:06:54.800  7077  7527 W FormManager: Network not available. Please check & try again.
,09-13 00:06:54.801  7030  7030 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-13 00:06:54.802  7030  7030 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3381
09-13 00:06:54.802  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1005529436 [*alarm*], flags=0x0
09-13 00:06:54.803  7077  7528 V FormManager: Network unavailable.
09-13 00:06:54.806  7077  7528 V FormManager: Network unavailable.
09-13 00:06:55.218  1033  1389 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:544232690] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 00:06:55.219  1033  1389 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:544232691] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 00:06:55.301  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:55.314  1033  1109 D Tethering: MasterInitialState.processMessage what=3
09-13 00:06:55.323  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:55.329  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:55.330  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:55.335  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 00:06:55.345  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 00:06:55.352  6424  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 00:06:55.372  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:55.392  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 00:06:55.392  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:55.392  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 00:06:55.392  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 00:06:55.403  7181  7181 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 00:06:55.410  7181  7181 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18877e84
09-13 00:06:55.410  7181  7181 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 00:06:55.410  7181  7181 D AppUp4:CustFacade: isPhone : true
09-13 00:06:55.410  7181  7181 D AppUp4:CustModeStarterReceiver: begin check event
09-13 00:06:55.411  7181  7181 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 00:06:55.411  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:55.416  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:55.417  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 00:06:55.418  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:55.420  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 00:06:55.427  7212  7212 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 00:06:55.427  4793  7541 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:06:55.428  4793  7542 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:55.428  4793  7542 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 00:06:55.442  7212  7543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:06:55.450  3207  3207 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 00:06:55.450  3207  3207 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:55.450  3207  3207 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 00:06:55.450  3207  3207 D PhoneState: setPdpRejectCasuse : false
09-13 00:06:55.451  7077  7546 V FormManager: Network unavailable.
09-13 00:06:55.451  7077  7545 W FormManager: Network not available. Please check & try again.
09-13 00:06:55.454  7242  7242 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 00:06:55.454  7242  7242 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 00:06:55.459  7077  7546 V FormManager: Network unavailable.
,09-13 00:06:55.462  7315  7315 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:55
09-13 00:06:55.464  7315  7315 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 00:06:55.464  7315  7315 D Weather.Utils: 2 : All the weather widget is gone.
09-13 00:06:55.465  7315  7315 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 00:06:55.465  7315  7315 D WeatherAncestor: connectivity changed - connection : true
09-13 00:06:55.465  7315  7315 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d1262a2
09-13 00:06:55.465  7315  7315 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 00:06:55.465  7315  7315 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 00:06:55.466  7315  7315 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 00:06:55.466  7315  7315 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 00:06:55.466  7315  7315 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:55
09-13 00:06:56.398  1033  1572 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:56.398  1033  1572 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-13 00:06:56.411  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:06:56.412  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:06:56.412  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:06:56.416  1033  1109 D BluetoothManagerService: Message: 1
09-13 00:06:56.416  1033  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-13 00:06:56.469  1033  1109 D BluetoothManagerService: Message: 20
09-13 00:06:56.469  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ec61b04:true
,09-13 00:06:56.474  7109  7109 D BluetoothAdapterState: make
09-13 00:06:56.479  7109  7109 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 00:06:56.479  7109  7109 I bluedroid-qcom: init
09-13 00:06:56.490  7109  7109 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 00:06:56.494  7109  7109 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 00:06:56.494  7109  7109 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 00:06:56.494  7109  7109 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 00:06:56.494  7109  7109 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 00:06:56.486  7571  7571 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:56.497  7109  7109 I bluedroid-qcom: get_profile_interface socket
09-13 00:06:56.497  7109  7109 I bluedroid-qcom: get_profile_interface map_client
09-13 00:06:56.486  7571  7571 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:56.498  7109  7572 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 00:06:56.500  7109  7572 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 00:06:56.502  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 00:06:56.502  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 00:06:56.504  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-13 00:06:56.505  7571  7571 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 00:06:56.505  7571  7571 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 00:06:56.506  7571  7571 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-13 00:06:56.506  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.507  1033  1109 D BluetoothManagerService: Message: 40
09-13 00:06:56.507  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 00:06:56.508  7109  7572 D BluetoothAdapterProperties: Name is: G3
09-13 00:06:56.508  7571  7571 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 00:06:56.509  7109  7126 I bluedroid-qcom: config_hci_snoop_log
09-13 00:06:56.510  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 00:06:56.510  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 00:06:56.513  7571  7571 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 00:06:56.513  7571  7571 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-13 00:06:56.524  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:56.525  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:56.526  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.531  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,09-13 00:06:56.539  1033  1109 D Tethering: MasterInitialState.processMessage what=3
09-13 00:06:56.539  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 00:06:56.539  7109  7559 I BluetoothAdapterState: Entering OffState
09-13 00:06:56.539  7109  7559 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 00:06:56.539  7109  7559 D BluetoothAdapterProperties: Setting state to 11
09-13 00:06:56.540  7109  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 00:06:56.540  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:06:56.540  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 00:06:56.540  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 00:06:56.541  7109  7559 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 00:06:56.541  6424  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 00:06:56.548  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:56.550  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:56.550  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.551  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 00:06:56.554  7109  7559 D BluetoothBondStateMachine: make
09-13 00:06:56.556  7109  7109 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:06:56.556  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:06:56.556  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:56.557  7109  7109 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:56.557  7109  7109 V BluetoothPbapReceiver: ***********state = 11
09-13 00:06:56.559  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:56.564  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:56.565  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:06:56.568  7109  7559 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.568  7109  7559 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 00:06:56.568  7109  7559 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.568  7109  7559 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 00:06:56.568  7109  7559 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 00:06:56.569  7109  7578 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 00:06:56.571  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:06:56.600  1033  1902 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7581 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 00:06:56.604  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.605  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:56.605  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:06:56.605  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:56.605  7109  7109 D HeadsetService: Received start request. Starting profile...
09-13 00:06:56.606  7109  7109 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 00:06:56.606  7109  7109 D LGBluetoothHfpAdapter: Version 1.6
09-13 00:06:56.608  7109  7109 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 00:06:56.608  7109  7109 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 00:06:56.608  7109  7109 D HeadsetStateMachine: make
09-13 00:06:56.608  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 00:06:56.609  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:06:56.613  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:06:56.617  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 00:06:56.620  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 00:06:56.627  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:06:56.628  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.634  7109  7559 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 00:06:56.636  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 00:06:56.636  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.637  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 00:06:56.637  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 00:06:56.638  7181  7181 I AppUp4:CustModeStarterReceiver: onReceive
09-13 00:06:56.641  7181  7181 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18877e84
09-13 00:06:56.641  7181  7181 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 00:06:56.641  7181  7181 D AppUp4:CustFacade: isPhone : true
09-13 00:06:56.644  7109  7559 V LGMDMManager: Create singleton instance
09-13 00:06:56.645  7181  7181 D AppUp4:CustModeStarterReceiver: begin check event
09-13 00:06:56.645  7181  7181 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 00:06:56.648  7109  7559 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 00:06:56.648  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.648  7109  7109 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:06:56.648  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 00:06:56.648  7109  7109 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:06:56.650  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:56.652  7109  7109 D HeadsetStateMachine: max_hf_connections = 1
09-13 00:06:56.652  7109  7109 I bluedroid-qcom: get_profile_interface handsfree
09-13 00:06:56.652  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:56.653  7109  7109 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-13 00:06:56.654   312  2183 V AudioPolicyService: registerClient() client 0xb558a700, uid 1002
09-13 00:06:56.654   312  1400 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,09-13 00:06:56.654   312  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 00:06:56.654   312  1400 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 00:06:56.654  7109  7109 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 00:06:56.655   312  2174 V AudioFlinger: registerClient() client 0xb1433190, pid 7109
09-13 00:06:56.655  7109  7109 V ToneGenerator: Create Track: 0xb4928080
09-13 00:06:56.655  7109  7109 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 00:06:56.656  7109  7109 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 00:06:56.656   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 00:06:56.656   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 00:06:56.656   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 00:06:56.656   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 00:06:56.656  7109  7109 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 00:06:56.656   312  1400 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 00:06:56.657   312  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:06:56.657   312  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:06:56.657  1601  2069 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:06:56.657  1601  2069 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:06:56.657  1850  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:06:56.657  1850  1866 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:06:56.657  3207  3227 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:06:56.657  3207  3227 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:06:56.657  7109  7125 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:06:56.657  7109  7125 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 00:06:56.657   312  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:06:56.657   312  1393 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:06:56.657  1033  1572 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:06:56.657  1033  1572 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:06:56.657  1033  1572 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:06:56.657  1601  3403 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:06:56.657  1033  1572 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:06:56.657  1601  3403 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:06:56.657  1850  3470 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:06:56.657  1850  3470 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:06:56.657   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 00:06:56.657   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 00:06:56.657   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 00:06:56.657   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 00:06:56.657  7109  7125 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:06:56.657  7109  7125 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 00:06:56.658  3207  3226 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:06:56.658  3207  3226 V AudioSystem: ioConfigChan,ged() opening already existing output! 2
09-13 00:06:56.658  7109  7109 V AudioSystem: getLatency() output 2, latency 50
09-13 00:06:56.658  7109  7109 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 00:06:56.658  7109  7109 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 00:06:56.658   312  1401 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 00:06:56.658   312  1401 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 00:06:56.658   312  1401 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 00:06:56.658   312  1401 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 00:06:56.658   312  1401 V AudioFlinger: createTrack() lSessionId: 20
09-13 00:06:56.658  7109  7109 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 00:06:56.659   312  2174 V AudioFlinger: acquiring 20 from 7109, for 7109
09-13 00:06:56.659   312  2174 V AudioFlinger:  added new entry for 20
09-13 00:06:56.659  7109  7109 V ToneGenerator: ToneGenerator INIT OK, time: 188672
09-13 00:06:56.659  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.660  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.661  7109  7594 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 00:06:56.661  7109  7594 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 00:06:56.661  7212  7212 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 00:06:56.662  7109  7594 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 00:06:56.662  7109  7594 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,09-13 00:06:56.665  7109  7109 D A2dpService: Received start request. Starting profile...
09-13 00:06:56.665  7109  7109 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 00:06:56.665   312  2183 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7109
09-13 00:06:56.666   312  2183 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 00:06:56.666   312  2183 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 00:06:56.666   312  2183 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 00:06:56.666   312  2183 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 00:06:56.666   312  2183 V voice   : voice_set_parameters: exit with code(0)
09-13 00:06:56.666   312  2183 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 00:06:56.666   312  2183 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 00:06:56.666   312  2183 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 00:06:56.666   312  2183 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 00:06:56.666  7109  7109 V Avrcp   : make
09-13 00:06:56.666   312  2183 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 00:06:56.666   312  2183 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 00:06:56.666  7109  7594 V ToneGenerator: ToneGenerator destructor
09-13 00:06:56.666  7109  7594 V ToneGenerator: stopTone
09-13 00:06:56.666  7109  7594 V ToneGenerator: Delete Track: 0xb4928080
09-13 00:06:56.666  7109  7109 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 00:06:56.666  7109  7109 I bluedroid-qcom: get_profile_interface avrcp
09-13 00:06:56.666  7109  7594 V AudioTrack: ~AudioTrack, releasing session id from 7109 on behalf of 7109
09-13 00:06:56.667   312   312 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 00:06:56.667   312   312 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 00:06:56.667   312  1267 V AudioPolicyService: AudioCommandThread() waking up
09-13 00:06:56.667   312  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 00:06:56.667   312  1267 V AudioPolicyManager: releaseOutput() 2
09-13 00:06:56.667   312  1267 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 00:06:56.667   312   312 V AudioFlinger: PlaybackThread::Track destructor
09-13 00:06:56.667   312   312 V AudioFlinger: removeClient_l() pid 7109, calling pid 312
09-13 00:06:56.667   312   312 V AudioFlinger: releasing 20 from 7109 for 7109
09-13 00:06:56.667   312   312 V AudioFlinger:  decremented refcount to 0
09-13 00:06:56.667   312   312 V AudioFlinger: purging stale effects
09-13 00:06:56.668  1033  1049 W Process : Unable to open /proc/7601/status
09-13 00:06:56.676  7109  7109 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 00:06:56.677  7109  7109 E AudioManager: No RCC entry present to update
09-13 00:06:56.678  7109  7109 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 00:06:56.680  7109  7109 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 00:06:56.680  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 00:06:56.680  7109  7109 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 00:06:56.683  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 00:06:56.688  4793  7602 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:06:56.691  4793  7605 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.691  4793  7605 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 00:06:56.744  7581  7581 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 00:06:56.744  7581  7581 W LG Account v2.2: No ProfileInfo entries
09-13 00:06:56.744  7581  7581 I LG Account v2.2: isEnabled: false
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Country: EU
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Operator: OPEN
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Ranking support: false
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Comfort support: false
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Accessory: true
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Health device: true
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Extra Pedometer: false
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Blood glucose device: false
09-13 00:06:56.744  7581  7581 I Feature : [Lifetracker]Device Number: 3
,09-13 00:06:56.749  3207  3207 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 00:06:56.749  3207  3207 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.749  3207  3207 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 00:06:56.755  7242  7242 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 00:06:56.756  7242  7242 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 00:06:56.756  1033  2031 V SIM_STK : Menu title from STK is T-Mobile
09-13 00:06:56.756  1033  2031 V SIM_STK : Menu title from STK is T-Mobile
09-13 00:06:56.758  7212  7607 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:06:56.761  6956  6956 D BluetoothPermissionRequest: onReceive
09-13 00:06:56.770  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 00:06:56.773  7077  7611 W FormManager: Network not available. Please check & try again.
09-13 00:06:56.776  7315  7315 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:56
09-13 00:06:56.777  7315  7315 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 00:06:56.777  7315  7315 D Weather.Utils: 2 : All the weather widget is gone.
09-13 00:06:56.777  7315  7315 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 00:06:56.777  7315  7315 D WeatherAncestor: connectivity changed - connection : true
09-13 00:06:56.777  7315  7315 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d1262a2
09-13 00:06:56.778  7077  7612 V FormManager: Network unavailable.
09-13 00:06:56.779  7315  7315 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 00:06:56.779  7315  7315 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 00:06:56.779  7315  7315 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 00:06:56.779  7315  7315 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 00:06:56.779  7315  7315 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:56
09-13 00:06:56.782  7077  7612 V FormManager: Network unavailable.
,09-13 00:06:56.799  6424  6424 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 00:06:56.800  6424  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 00:06:56.806  1033  1592 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 00:06:56.811  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-13 00:06:56.813  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 00:06:56.814  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 00:06:56.815  7109  7109 I BluetoothA2dpServiceJni: classInitNative
09-13 00:06:56.815  7109  7109 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 00:06:56.815  7109  7109 D A2dpStateMachine: make
09-13 00:06:56.816  7109  7109 I bluedroid-qcom: get_profile_interface a2dp
09-13 00:06:56.817  7109  7614 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-13 00:06:56.817  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.818  7109  7109 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 00:06:56.819  7109  7109 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 00:06:56.820  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.820  7109  7109 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 00:06:56.821  7109  7613 D A2dpStateMachine: Enter Disconnected: -2
09-13 00:06:56.822  7109  7109 D HidService: Received start request. Starting profile...
09-13 00:06:56.822  7109  7109 I bluedroid-qcom: get_profile_interface hidhost
09-13 00:06:56.822  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.823  7109  7109 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 00:06:56.825  7109  7109 D HealthService: Received start request. Starting profile...
09-13 00:06:56.826  7109  7109 I bluedroid-qcom: get_profile_interface health
09-13 00:06:56.826  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 00:06:56.826  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.826  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 00:06:56.826  7109  7109 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 00:06:56.826  7181  7181 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 00:06:56.826  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.827  7109  7109 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 00:06:56.828  7181  7181 I AppUp4:CustModeStarterReceiver: onReceive
09-13 00:06:56.828  7109  7109 D PanService: Received start request. Starting profile...
09-13 00:06:56.828  7109  7109 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 00:06:56.828  7109  7109 I bluedroid-qcom: get_profile_interface pan
09-13 00:06:56.829  7181  7181 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18877e84
09-13 00:06:56.829  7181  7181 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 00:06:56.829  7181  7181 D AppUp4:CustFacade: isPhone : true
09-13 00:06:56.830  7181  7181 D AppUp4:CustModeStarterReceiver: begin check event
09-13 00:06:56.830  7181  7181 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 00:06:56.831  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.832  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 00:06:56.832  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 00:06:56.834  7109  7109 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 00:06:56.834  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.835  7109  7109 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 00:06:56.836  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 00:06:56.840  7109  7109 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 00:06:56.841  7109  7109 D BtGatt.GattService: Received start request. Starting profile...
09-13 00:06:56.841  7109  7109 D BtGatt.GattService: start()
09-13 00:06:56.841  7109  7109 I bluedroid-qcom: get_profile_interface gatt
09-13 00:06:56.841  7109  7109 D BtGatt.AdvertiseManager: advertise manager created
09-13 00:06:56.841  4793  7619 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:06:56.842  7212  7212 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 00:06:56.845  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.846  4793  7620 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.846  4793  7620 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 00:06:56.847  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.847  7109  7109 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,09-13 00:06:56.848  7109  7109 V BluetoothMapService: BluetoothMapBinder()
09-13 00:06:56.849  7109  7109 D BluetoothMapService: Received start request. Starting profile...
09-13 00:06:56.849  7109  7109 D BluetoothMapService: start()
09-13 00:06:56.852  7109  7109 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 00:06:56.852  7109  7109 D BluetoothMapEmailAppObserver: createReceiver()
09-13 00:06:56.853  7109  7109 D BluetoothMapEmailAppObserver: initObservers()
09-13 00:06:56.853  7109  7109 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 00:06:56.857  3207  3207 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 00:06:56.857  3207  3207 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:56.857  3207  3207 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 00:06:56.857  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:56.858  7109  7109 D HeadsetStateMachine: Proxy object connected
09-13 00:06:56.858  7109  7109 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,09-13 00:06:56.858  7109  7109 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 00:06:56.859  7109  7594 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 00:06:56.860  7109  7594 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 00:06:56.860  7109  7594 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 00:06:56.860  7242  7242 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 00:06:56.861  7242  7242 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 00:06:56.863  7109  7109 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 00:06:56.866  7212  7624 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:06:56.866  7077  7625 W FormManager: Network not available. Please check & try again.
09-13 00:06:56.866  7109  7109 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:06:56.869  7109  7109 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:06:56.871  7077  7626 V FormManager: Network unavailable.
09-13 00:06:56.871  7109  7109 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:06:56.871  7109  7109 V PanService: [BTUI] SIM Extra State :ABSENT
,09-13 00:06:56.874  7109  7109 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:06:56.876  7109  7109 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 00:06:56.876  7109  7109 V BluetoothMapService: Handler(): got msg=1
09-13 00:06:56.877  7109  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 00:06:56.877  7109  7559 I bluedroid-qcom: enable
09-13 00:06:56.877  7109  7559 I bt_hci_bdroid: init
09-13 00:06:56.877  7077  7626 V FormManager: Network unavailable.
09-13 00:06:56.877  7109  7109 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:56.879  7109  7628 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 00:06:56.880  7109  7109 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:06:56.880  7109  7109 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:06:56.880  7109  7109 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:06:56.880  7109  7559 I bt_vendor: bt-vendor : init
09-13 00:06:56.880  7109  7559 I bt_vendor: bt-vendor : get_bt_soc_type
,09-13 00:06:56.880  7109  7559 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 00:06:56.880  7109  7559 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 00:06:56.880  7109  7559 D bt_userial_mct: userial_init
09-13 00:06:56.880  7109  7109 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:56.880  7109  7109 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 00:06:56.880  7109  7628 I bt-btu  : btu_task pending for preload complete event
09-13 00:06:56.880  7109  7559 D bt_hci_bdroid: set_power 1
09-13 00:06:56.880  7109  7559 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 00:06:56.880  7109  7559 I bt_vendor: Starting hciattach daemon
09-13 00:06:56.880  7109  7559 I bt_vendor: try to set true
09-13 00:06:56.866  7631  7631 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:56.866  7631  7631 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:56.883  7315  7315 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:56
,09-13 00:06:56.888  7315  7315 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 00:06:56.888  7315  7315 D Weather.Utils: 2 : All the weather widget is gone.
09-13 00:06:56.888  7315  7315 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 00:06:56.888  7315  7315 D WeatherAncestor: connectivity changed - connection : true
09-13 00:06:56.888  7315  7315 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d1262a2
09-13 00:06:56.888  7315  7315 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 00:06:56.889  7315  7315 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 00:06:56.889  7315  7315 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 00:06:56.889  7315  7315 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 00:06:56.889  7315  7315 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:6:56
09-13 00:06:56.892  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-13 00:06:56.924  7638  7638 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 00:06:56.929  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 00:06:56.940  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 00:06:56.945  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 00:06:56.952  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 00:06:56.959  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 00:06:56.973  7646  7646 I libmdmdetect: ESOC framework not supported
09-13 00:06:56.974  7646  7646 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 00:06:56.980  7646  7646 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 00:06:56.980  7646  7646 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 00:06:56.980  7646  7646 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 00:06:56.980  7646  7646 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 00:06:56.980  7646  7646 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 00:06:56.980  7646  7646 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 00:06:56.980  7646  7646 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 00:06:56.986  7364  7364 D dhcpcd  : wlan0: sending REQUEST (xid 0xa99e1f2a), next in 7.53 seconds
09-13 00:06:56.986  7364  7364 E dhcpcd  : wlan0: send_raw_packet: m
09-13 00:06:56.986  7364  7364 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason FAIL
,09-13 00:06:57.013  7646  7647 E QC-QMI  : qmi_client [7646] 14: failed to locate client data
09-13 00:06:57.013   457   457 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-13 00:06:57.013   457   457 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 00:06:57.051  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 00:06:57.069  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 00:06:57.081  7109  7559 I bt_vendor: bluetooth satus is on
09-13 00:06:57.081  7109  7559 D bt_hci_bdroid: preload
09-13 00:06:57.081  7109  7630 D bt_userial_mct: userial_open(port:0)
09-13 00:06:57.081  7109  7630 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 00:06:57.085  7109  7630 I bt_vendor: Done intiailizing UART
09-13 00:06:57.085  7109  7630 I bt_vendor: Done intiailizing UART
09-13 00:06:57.085  7109  7630 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 00:06:57.085  7109  7630 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 00:06:57.085  7109  7628 I bt-btu  : btu_task received preload complete event
09-13 00:06:57.086  7109  7662 D bt_userial_mct: Entering userial_read_thread()
09-13 00:06:57.087  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 00:06:57.087  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 00:06:57.089  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 00:06:57.091  7109  7628 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 00:06:57.091  7109  7628 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 00:06:57.091  7109  7628 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 00:06:57.092  7109  7628 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 00:06:57.172  7109  7628 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 00:06:57.172  7109  7628 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
09-13 00:06:57.172  7109  7628 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 
,09-13 00:06:57.208  7109  7572 E bt-btif : Calling BTA_HhEnable
,09-13 00:06:57.208  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 00:06:57.209  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 00:06:57.209  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called fo service_mask
09-13 00:06:57.209  7109  7572 E bt-btif : L2CAP - L2CA_Register() called fo service_mask:0x2140040
09-13 00:06:57.209  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 00:06:57.209  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 00:06:57.209  7109  7572 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 00:06:57.212  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 00:06:57.212  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 00:06:57.213  7109  7572 D BluetoothAdapterProperties: Name is: G3
09-13 00:06:57.217  7109  7572 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:06:57.218  7109  7572 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 00:06:57.218  7109  7572 D bt_hci_bdroid: postload
09-13 00:06:57.218  7109  7630 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:06:57.220  7109  7572 D bte_conf: Device ID record 1 : primary
09-13 00:06:57.220  7109  7572 D bte_conf:   vendorId            = 00c4
09-13 00:06:57.220  7109  7628 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 00:06:57.220  7109  7572 D bte_conf:   vendorIdSource      = 0001
09-13 00:06:57.220  7109  7572 D bte_conf:   product             = 13a1
09-13 00:06:57.220  7109  7572 D bte_conf:   version             = 1000
09-13 00:06:57.220  7109  7572 D bte_conf:   clientExecutableURL = 
,09-13 00:06:57.220  7109  7572 D bte_conf:   serviceDescription  = 
,09-13 00:06:57.220  7109  7572 D bte_conf:   documentationURL    = 
09-13 00:06:57.220  7109  7572 D bte_conf: bte_load_did_conf no section named DID2.
09-13 00:06:57.221  7109  7630 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:06:57.225  7109  7630 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:06:57.225  7109  7630 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 00:06:57.216  7668  7668 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:57.216  7668  7668 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:57.227  7109  7572 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 00:06:57.227  7109  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 00:06:57.228  7109  7630 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:06:57.228  7109  7630 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 00:06:57.228  7109  7559 D BluetoothAdapterProperties: ScanMode =  20
09-13 00:06:57.229  7109  7559 D BluetoothAdapterProperties: State =  11
09-13 00:06:57.231  7109  7662 E bt_mct  : hci lib postload completed
09-13 00:06:57.231  7109  7559 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,09-13 00:06:57.233  1033  7334 D NetUtils: dhcp_do_request failed : wlan0 (new)
09-13 00:06:57.234  7109  7559 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 00:06:57.236  7109  7559 D BluetoothAdapterProperties: Setting state to 12
09-13 00:06:57.236  7109  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 00:06:57.238  7109  7628 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:06:57.238  7109  7628 W bt-smp  : Plain text(LSB ~ MSB) = 37 94 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:06:57.239  7109  7628 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 65 26 f7 f6 44 40 59 df 60 db fa 7c 7a e3 20 
09-13 00:06:57.239  7109  7628 W bt-btm  : Stopping oneshot timer
09-13 00:06:57.240  7109  7572 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 00:06:57.244  7109  7559 I BluetoothAdapterState: Entering On State
,09-13 00:06:57.250  1033  7334 V LgDhcpStateMachineHelper: [getKeyforDhcp] getBSSID, getSSID is null 
09-13 00:06:57.250  1033  7334 E DhcpStateMachine: DHCP failed on wlan0: DHCP result was failed
09-13 00:06:57.244  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:06:57.250  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 00:06:57.250  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 00:06:57.250  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:57.254  7109  7559 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 00:06:57.254  7109  7559 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:57.254  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:57.257  7109  7559 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-13 00:06:57.259  7109  7559 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-13 00:06:57.260  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:57.262  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:57.264  1850  1850 D BluetoothHeadset: Proxy object connected
09-13 00:06:57.264  1033  1033 D BluetoothHeadset: Proxy object connected
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:57.269  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:57.272  7109  7628 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:06:57.272  7109  7628 W bt-smp  : Plain text(LSB ~ MSB) = 60 3b 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:06:57.272  7109  7628 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e 08 a3 58 95 8f b8 1a 30 45 d2 84 42 1c 58 1a 
09-13 00:06:57.272  7109  7628 W bt-btm  : Stopping oneshot timer
09-13 00:06:57.273  6956  6978 D BluetoothMap: onBluetoothStateChange: up=true
09-13 00:06:57.274  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:57.277  1850  3470 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:57.278  6956  6956 D BluetoothMap: Proxy object connected
09-13 00:06:57.278  6956  6956 D MapProfile: Bluetooth service connected
09-13 00:06:57.278  6956  6956 D BluetoothMap: getConnectedDevices()
09-13 00:06:57.280  7109  7572 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 00:06:57.281  7109  7572 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 00:06:57.281  1850  1850 D BluetoothHeadset: Proxy object connected
09-13 00:06:57.281  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 00:06:57.282  7109  7126 V BluetoothMapService: getConnectedDevices()
09-13 00:06:57.285  1850  1850 D BluetoothHeadset: Proxy object connected
09-13 00:06:57.286  6956  6978 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 00:06:57.288  6956  6980 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 00:06:57.288  7109  7628 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:06:57.288  7109  7628 W bt-smp  : Plain text(LSB ~ MSB) = d6 fa 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:06:57.288  7109  7628 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 44 8c 0b 45 2a b6 8a 1f 0b e2 6e fa 8e 90 6f 
09-13 00:06:57.288  7109  7628 W bt-btm  : Stopping oneshot timer
09-13 00:06:57.292  6956  6956 D BluetoothInputDevice: Proxy object connected
09-13 00:06:57.292  6956  6956 D HidProfile: Bluetooth service connected
09-13 00:06:57.292  6956  6978 D BluetoothPan: onBluetoothStateChange on: true
09-13 00:06:57.292  6956  6978 D BluetoothPan: onBluetoothStateChange call bindService
09-13 00:06:57.294  7109  7559 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-13 00:06:57.298  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:06:57.298  6956  6956 D PanProfile: Bluetooth service connected
09-13 00:06:57.298  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:06:57.299  7674  7674 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 00:06:57.299  1033  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 00:06:57.299  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 00:06:57.301  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:06:57.304  7109  7628 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:06:57.305  7109  7628 W bt-smp  : Plain text(LSB ~ MSB) = 9d a1 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:06:57.305  7109  7628 W bt-smp  : Encrypted text(LSB ~ MSB) = cf 9d 46 41 03 b7 dd 66 83 27 5b 38 be e1 91 54 
09-13 00:06:57.305  7109  7628 W bt-btm  : Stopping oneshot timer
09-13 00:06:57.305  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.305  1940  2086 D LGBluetoothAPIService: Message: 1
09-13 00:06:57.305  1940  2086 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 00:06:57.306  1033  1033 D BluetoothA2dp: Proxy object connected
09-13 00:06:57.311  7109  7109 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.311  7109  7109 D BluetoothMapService: STATE_ON
09-13 00:06:57.312  6853  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 00:06:57.312  7109  7109 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 00:06:57.313  7109  7109 D LGBluetoothAPIServer: [BTUI] onBind()
,09-13 00:06:57.316  1940  2086 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 00:06:57.317  7109  7109 V BluetoothMapService: Handler(): got msg=1
09-13 00:06:57.317  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 00:06:57.317  1940  2086 D LGBluetoothAPIService: Message: 100
09-13 00:06:57.317  1940  2086 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 00:06:57.319  7109  7109 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 00:06:57.321  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 00:06:57.321  1033  1109 D BluetoothManagerService: Message: 40
09-13 00:06:57.321  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-13 00:06:57.321  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:57.323  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:57.323  6956  6956 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 00:06:57.325  7109  7628 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:06:57.325  7109  7628 W bt-smp  : Plain text(LSB ~ MSB) = 81 82 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-13 00:06:57.325  7109  7628 W bt-smp  : Encrypted text(LSB ~ MSB) = 23 68 a5 5d 34 b8 5b c6 e1 fa b0 c3 12 e3 0e 2c 
09-13 00:06:57.325  7109  7628 W bt-btm  : Stopping oneshot timer
09-13 00:06:57.327  1033  1109 D BluetoothManagerService: Message: 30
09-13 00:06:57.329  7109  7683 D BluetoothMapMasInstance: MAS initSocket()
09-13 00:06:57.329  7109  7683 D BluetoothMapMasInstance:   masId = 00
09-13 00:06:57.329  7109  7683 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 00:06:57.329  7109  7683 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 00:06:57.329  7109  7683 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 00:06:57.330  1033  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:57.330  6956  6956 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 00:06:57.332  7109  7683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:57.333  7109  7683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 00:06:57.333  7109  7683 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 00:06:57.333  7109  7683 D BluetoothMapMasInstance: Accepting socket connection...
09-13 00:06:57.334  7109  7572 D BluetoothAdapterProperties: Scan Mode:21
09-13 00:06:57.334  7109  7572 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 00:06:57.337  1033  1109 D BluetoothManagerService: Message: 30
,09-13 00:06:57.339  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:57.342  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:57.342  7109  7109 V BluetoothPbapService: Pbap Service onCreate
09-13 00:06:57.342  7109  7109 V BluetoothPbapService: Starting PBAP service
09-13 00:06:57.347  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:57.347  7109  7109 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 00:06:57.348  7109  7109 V BluetoothPbapService: Pbap Service onBind
09-13 00:06:57.453  1033  7334 V LgDhcpStateMachineHelper: [getKeyforDhcp] getBSSID, getSSID is null 
,09-13 00:06:57.453  1033  7334 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 00:06:57.454  1033  7334 D DhcpStateMachine: StoppedState
09-13 00:06:57.454  1033  7334 D DhcpStateMachine: StoppedState{ when=-4s46ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:57.454  1033  7334 D DhcpStateMachine: StoppedState{ when=-3s979ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:57.462  1033  1389 E WifiStateMachine:  InitialState CMD_POST_DHCP_ACTION 2 0 FAIL 
09-13 00:06:57.462  1033  1389 E WifiStateMachine:  DefaultState CMD_POST_DHCP_ACTION 2 0 FAIL 
09-13 00:06:57.462  1033  1389 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
09-13 00:06:57.463  1033  1389 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 00:06:57.488  1033  1867 I art     : Explicit concurrent mark sweep GC freed 95420(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.697ms total 148.545ms
09-13 00:06:57.489  7109  7109 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.490  7109  7109 V BluetoothPbapService: state: 12
09-13 00:06:57.490  7109  7109 V BluetoothPbapService: Handler(): got msg=1
09-13 00:06:57.490  7109  7109 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,09-13 00:06:57.492  7109  7684 V BluetoothPbapService: Pbap Service initSocket
09-13 00:06:57.492  1033  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:57.493  7109  7684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:57.494  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 00:06:57.495  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 00:06:57.496  7109  7684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,09-13 00:06:57.497  7109  7684 V BluetoothPbapService: Succeed to create listening socket 
09-13 00:06:57.497  7109  7684 V BluetoothPbapService: Accepting socket connection...
09-13 00:06:57.498  6956  6956 D BluetoothA2dp: Proxy object connected
09-13 00:06:57.499  6956  6956 D A2dpProfile: Bluetooth service connected
09-13 00:06:57.500  7109  7109 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:06:57.500  7109  7109 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.500  7109  7109 V BluetoothPbapReceiver: ***********state = 12
09-13 00:06:57.504  6956  6956 D BluetoothHeadset: Proxy object connected
09-13 00:06:57.504  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 00:06:57.505  6956  6956 D HeadsetProfile: Bluetooth service connected
09-13 00:06:57.506  2199  2199 D c       : Getting all permits...
09-13 00:06:57.506  2199  2199 D a       : Opening database...
09-13 00:06:57.506  6956  6956 D BluetoothPbap: Proxy object connected
09-13 00:06:57.507  6956  6956 D PbapServerProfile: Bluetooth service connected
,09-13 00:06:57.510  6956  6956 D DockEventReceiver: finishStartingService: stopping service
09-13 00:06:57.510  2199  2199 D a       : Opening database auth.proximity.permit_store...
09-13 00:06:57.511  2199  2199 D a       : Closing database...
09-13 00:06:57.533  6956  6956 D BluetoothPermissionRequest: onReceive
,09-13 00:06:57.536  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 00:06:57.538  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 00:06:57.540  7109  7109 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 00:06:57.542  7109  7109 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 00:06:57.548  7109  7109 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-13 00:06:57.574  7109  7109 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-13 00:06:57.574  7109  7109 V BtOppService: onCreate
,09-13 00:06:57.579  7109  7109 V BluetoothOppNotification: send message
09-13 00:06:57.582  7109  7109 V BtOppService: Starting RfcommListener
09-13 00:06:57.590  7109  7109 D BluetoothOppPreference: Dumping Names:  
,09-13 00:06:57.590  7109  7109 D BluetoothOppPreference: {}
09-13 00:06:57.590  7109  7109 D BluetoothOppPreference: Dumping Channels:  
09-13 00:06:57.590  7109  7109 D BluetoothOppPreference: {}
09-13 00:06:57.590  7109  7109 V BtOppService: onStartCommand
09-13 00:06:57.594  7109  7109 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.595  7109  7109 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 00:06:57.599  7109  7109 V BluetoothOppNotification: new notify threadi!
09-13 00:06:57.600  7109  7109 V BluetoothOppNotification: send delay message
09-13 00:06:57.602  7109  7109 V BtOppService: start RfcommListener
09-13 00:06:57.602  7109  7689 V BtOppService: Deleted complete outbound shares, number =  0
09-13 00:06:57.604  7109  7689 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 00:06:57.604  7109  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 00:06:57.605  7109  7689 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 00:06:57.606  7109  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16c43c5f on behalf of 
09-13 00:06:57.608  7109  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c6cd6ac on behalf of 
09-13 00:06:57.609  7109  7692 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 00:06:57.609  7109  7692 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 00:06:57.610  7109  7693 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 00:06:57.610  7109  7109 V BtOppService: RfcommListener started
,09-13 00:06:57.613  7109  7694 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 00:06:57.614  1033  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:57.616  7109  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:57.619  7109  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 00:06:57.619  7109  7694 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-13 00:06:57.618  7109  7692 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28c7ff75 on behalf of 
09-13 00:06:57.619  7109  7694 V BtOppRfcommListener: Started RFCOMM listener....
09-13 00:06:57.619  7109  7694 I BtOppRfcommListener: Accept thread started.
09-13 00:06:57.619  7109  7694 V BtOppRfcommListener: Accepting connection...
09-13 00:06:57.623  7109  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@167b9b0a on behalf of 
,09-13 00:06:57.623  7109  7692 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 00:06:57.624  7109  7693 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 00:06:57.626  7109  7693 V BluetoothOppNotification: outbound notification was removed.
09-13 00:06:57.626  7109  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 00:06:57.628  7109  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f9a3f7b on behalf of 
,09-13 00:06:57.629  7109  7693 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 00:06:57.630  7109  7693 V BluetoothOppNotification: inbound notification was removed.
09-13 00:06:57.630  7109  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 00:06:57.632  7109  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1826b198 on behalf of 
09-13 00:06:57.633  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:57.633  7109  7109 V BluetoothFtpService: Ftp Service onCreate
09-13 00:06:57.633  7109  7109 I BluetoothFtpService: Ftp Service onCreate
09-13 00:06:57.634  7109  7109 V BluetoothFtpService: Ftp Service onStartCommand
09-13 00:06:57.634  7109  7109 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.634  7109  7109 V BluetoothFtpService: Starting Listening on sockets
09-13 00:06:57.635  7109  7109 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:06:57.635  7109  7109 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:06:57.635  7109  7109 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:06:57.635  7109  7109 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.635  7109  7109 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 00:06:57.635  7109  7109 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 00:06:57.638  7109  7109 V BtOppService: ContentObserver received notification
09-13 00:06:57.640  7109  7109 V BtOppService: ContentObserver received notification
,09-13 00:06:57.640  7109  7109 V BluetoothFtpService: Handler(): got msg=1
,09-13 00:06:57.641  7109  7109 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 00:06:57.642  7109  7109 V BluetoothFtpService: Ftp Service initSocket
09-13 00:06:57.643  7109  7695 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 00:06:57.644  7109  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 00:06:57.644  1033  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:57.646  7109  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14c05dd6 on behalf of 
09-13 00:06:57.646  7109  7109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:57.647  7109  7109 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-13 00:06:57.647  7109  7695 V BluetoothOppNotification: update too frequent, put in queue
09-13 00:06:57.647  7109  7109 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 00:06:57.648  7109  7695 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 00:06:57.649  7109  7696 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 00:06:57.663  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:06:57.664  7109  7109 V BluetoothSapService: Sap Service onCreate
,09-13 00:06:57.666  7109  7109 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:57.666  7109  7109 V BluetoothSapService: state: 12
09-13 00:06:57.666  7109  7109 V BluetoothSapService: Starting SAP server process
09-13 00:06:57.668  7109  7109 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 00:06:57.656  7697  7697 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:57.656  7697  7697 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:06:57.669  7109  7698 V BluetoothSapService: Sap Service initRfcommSocket
09-13 00:06:57.670  1033  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:06:57.671  7109  7698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:57.672  7109  7698 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-13 00:06:57.672  7109  7698 V BluetoothSapService: Succeed to create listening socket 
09-13 00:06:57.672  7109  7698 V BluetoothSapService: Accepting socket connection...
09-13 00:06:57.683  7697  7697 V BT_SAP  : Event pipe created
09-13 00:06:57.683  7697  7697 V BT_SAP  : create_server_socket qcom.sap.server
09-13 00:06:57.683  7697  7697 V BT_SAP  : created socket fd 6
,09-13 00:06:57.687  7345  7393 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-13 00:06:57.829  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3099d690 type 2 when 189826 com.google.android.gms} when 189826
,09-13 00:06:57.843   308  7702 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-13 00:06:57.845  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 00:06:58.469  1033  1388 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:06:58.476  1033  1388 D LGWifiP2pService: DefaultState{ when=-13ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:06:58.491  1033  1389 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 00:06:58.493  1033  1389 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 00:06:58.594  1033  1939 I ActivityManager: Killing 7497:com.lge.bnr/1000 (adj 15): empty #17
,09-13 00:06:58.601  7109  7109 V BluetoothOppNotification: new notify threadi!
09-13 00:06:58.602  7109  7109 V BluetoothOppNotification: send delay message
09-13 00:06:58.608  7109  7712 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 00:06:58.623  7109  7712 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cbc8162 on behalf of 
09-13 00:06:58.624  7109  7712 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-13 00:06:58.628  7109  7712 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 00:06:58.630  7109  7712 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f7b22f3 on behalf of 
09-13 00:06:58.630  7109  7712 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 00:06:58.632  7109  7712 V BluetoothOppNotification: outbound notification was removed.
09-13 00:06:58.632  7109  7712 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 00:06:58.635  7109  7712 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17061bb0 on behalf of 
09-13 00:06:58.636  7109  7712 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-13 00:06:58.641  7109  7712 V BluetoothOppNotification: inbound notification was removed.
,09-13 00:06:58.641  7109  7712 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 00:06:58.642  7109  7712 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4299a29 on behalf of 
09-13 00:06:58.646  1033  1903 W libprocessgroup: failed to open /acct/uid_1000/pid_7497/cgroup.procs: No such file or directory
09-13 00:06:58.654  1033  1592 I ActivityManager: Killing 7001:com.lge.sync/1000 (adj 15): empty #17
,09-13 00:06:58.673  1033  1423 D WifiService: Client connection lost with reason: 4
,09-13 00:06:58.687  1033  2006 W libprocessgroup: failed to open /acct/uid_1000/pid_7001/cgroup.procs: No such file or directory
,09-13 00:06:59.449  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 00:06:59.449  1033  1939 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14406b89 mBinding = false
,09-13 00:06:59.484  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:06:59.484  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:06:59.484  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:06:59.485  1033  1109 D BluetoothManagerService: Message: 2
09-13 00:06:59.486  1033  1109 D BluetoothManagerService: Sending off request.
09-13 00:06:59.487  7109  7682 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 00:06:59.488  7109  7559 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 00:06:59.488  7109  7559 D BluetoothAdapterProperties: Setting state to 13
09-13 00:06:59.488  7109  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 00:06:59.488  7109  7559 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 00:06:59.489  7109  7559 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 00:06:59.490  7109  7572 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:06:59.492  7109  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 00:06:59.495  7109  7559 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 00:06:59.500  7109  7694 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:59.501  7109  7696 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:59.501  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 00:06:59.502  7109  7683 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 00:06:59.502  7109  7698 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:59.502  7109  7628 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 00:06:59.504  7109  7684 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:06:59.507  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:06:59.508  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:06:59.508  7109  7628 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:06:59.508  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 00:06:59.508  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 00:06:59.508  7109  7628 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 00:06:59.517  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:59.517  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:59.517  6853  6853 V io.,jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:59.521  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:59.523  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:59.527  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:59.527  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:06:59.528  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:06:59.530  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:06:59.533  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:06:59.533  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 00:06:59.533  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 00:06:59.537  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.538  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:06:59.542  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:59.546  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:59.548  7109  7109 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.548  7109  7109 D BluetoothMapService: STATE_TURNING_OFF
09-13 00:06:59.548  7109  7109 V BluetoothMapService: Handler(): got msg=4
09-13 00:06:59.549  7109  7109 D BluetoothMapService: MAP Service closeService in
09-13 00:06:59.549  7109  7109 D BluetoothMapMasInstance: MAP Service shutdown
09-13 00:06:59.549  7109  7109 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 00:06:59.549  7109  7109 V BluetoothMapService: MAP Service closeService out
09-13 00:06:59.551  7109  7109 V BtOppService: Receiver DISABLED_ACTION 
09-13 00:06:59.551  7109  7109 I BtOppRfcommListener: stopping Accept Thread
09-13 00:06:59.551  7109  7109 V BtOppRfcommListener: close mBtServerSocket
09-13 00:06:59.551  7109  7694 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 00:06:59.552  7109  7109 V BtOppRfcommListener: waiting for thread to terminate
09-13 00:06:59.552  7109  7109 V BtOppRfcommListener: done waiting for thread to terminate
09-13 00:06:59.555  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-13 00:06:59.567  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 00:06:59.571  7109  7109 V BtOppService: onDestroy
09-13 00:06:59.573  7109  7109 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 00:06:59.577  7109  7109 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:06:59.577  7109  7109 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.577  7109  7109 V BluetoothPbapReceiver: ***********state = 13
09-13 00:06:59.579  7109  7109 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 00:06:59.580  7109  7109 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.580  7109  7109 V BluetoothPbapService: state: 13
09-13 00:06:59.580  7109  7109 V BluetoothPbapService: Pbap Service closeService in
,09-13 00:06:59.586  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 00:06:59.588  7109  7109 V BluetoothPbapService: successfully stopped pbap service
09-13 00:06:59.588  7109  7109 V BluetoothPbapService: Pbap Service closeService out
09-13 00:06:59.588  7109  7109 V BluetoothPbapService: Pbap Service onDestroy
09-13 00:06:59.588  7109  7109 V BluetoothPbapService: Pbap Service closeService in
09-13 00:06:59.588  7109  7109 V BluetoothPbapService: Pbap Service closeService out
09-13 00:06:59.588  7109  7109 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 00:06:59.605  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:06:59.616  6956  6956 D BluetoothPbap: Proxy object disconnected
09-13 00:06:59.616  6956  6956 D PbapServerProfile: Bluetooth service disconnected
09-13 00:06:59.624  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 00:06:59.632  6956  6956 D BluetoothPermissionRequest: onReceive
09-13 00:06:59.632  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 00:06:59.638  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 00:06:59.641  7109  7109 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 00:06:59.641  7109  7109 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 00:06:59.643  7109  7109 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 00:06:59.647  7109  7109 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.647  7109  7109 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 00:06:59.648  7109  7109 V BluetoothFtpService: Ftp Service onStartCommand
09-13 00:06:59.648  7109  7109 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.648  7109  7109 V BluetoothFtpService: Ftp Service closeService
09-13 00:06:59.648  7109  7109 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 00:06:59.650  7109  7109 V BluetoothFtpService: successfully stopped ftp service
09-13 00:06:59.650  7109  7109 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:06:59.650  7109  7109 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:06:59.650  7109  7109 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:06:59.650  7109  7109 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.650  7109  7109 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 00:06:59.650  7109  7109 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-13 00:06:59.654  7109  7109 V BluetoothFtpService: Ftp Service onDestroy
09-13 00:06:59.654  7109  7109 V BluetoothFtpService: Ftp Service closeService
09-13 00:06:59.659  7109  7109 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:59.659  7109  7109 V BluetoothSapService: state: 13
09-13 00:06:59.659  7109  7109 V BluetoothSapService: Stopping SAP server process
09-13 00:06:59.660  7109  7109 V BluetoothSapService: Sap Service closeSapService in
09-13 00:06:59.661  7109  7109 V BluetoothSapService: Close listen Socket : 
09-13 00:06:59.661  7109  7109 V BluetoothSapService: Close rfcomm Socket : 
09-13 00:06:59.661  7109  7109 V BluetoothSapService: Close sapd  Socket : 
09-13 00:06:59.663  7109  7109 V BluetoothSapService: Sap Service closeSapService out
,09-13 00:06:59.665  7109  7109 V BluetoothSapService: Sap Service onDestroy
09-13 00:06:59.665  7109  7109 V BluetoothSapService: Sap Service closeSapService in
09-13 00:06:59.665  7109  7109 V BluetoothSapService: Close listen Socket : 
09-13 00:06:59.665  7109  7109 V BluetoothSapService: Close rfcomm Socket : 
09-13 00:06:59.665  7109  7109 V BluetoothSapService: Close sapd  Socket : 
09-13 00:06:59.665  7109  7109 V BluetoothSapService: Sap Service closeSapService out
09-13 00:06:59.866  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1aa9baf type 2 when 191863 com.google.android.gms} when 191863
,09-13 00:06:59.877   308  7731 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 00:06:59.879  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 00:07:00.048  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-13 00:07:00.048  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 00:07:00.048  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 00:07:00.049  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,09-13 00:07:00.061  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 00:07:00.062  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-13 00:07:00.064  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-13 00:07:00.069  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 00:07:00.419  7109  7572 D bt_hci_bdroid: cleanup
,09-13 00:07:00.425  7109  7630 I bt_lpm  : LPM is already off!!!
09-13 00:07:00.425  7109  7662 I bt_userial_mct: exiting userial_read_thread
09-13 00:07:00.426  7109  7662 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 00:07:00.427  7109  7628 W bt-btif : ag scb idx 1 not allocated
09-13 00:07:00.428  7109  7628 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:07:00.429  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 00:07:00.430  7109  7628 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:07:00.430  7109  7628 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 00:07:00.433  7109  7572 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 00:07:00.436  7109  7630 I bt_vendor: hw_epilog_process
,09-13 00:07:00.440  7109  7572 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 00:07:00.440  7109  7572 D bt_userial_mct: userial_close
09-13 00:07:00.440  7109  7572 E bt_userial_mct: pthread_join() FAILED result:3
09-13 00:07:00.440  7109  7572 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 00:07:00.447  7109  7572 D bt_hci_bdroid: set_power 0
09-13 00:07:00.447  7109  7572 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 00:07:00.447  7109  7572 I bt_vendor: bluetooth satus is on
09-13 00:07:00.447  7109  7572 I bt_vendor: bt-vendor : resetting BT status
09-13 00:07:00.447  7109  7572 I bt_vendor: Starting hciattach daemon
09-13 00:07:00.447  7109  7572 I bt_vendor: try to set false
09-13 00:07:00.450  7109  7572 I bt_vendor: Starting hciattach daemon
09-13 00:07:00.450  7109  7572 I bt_vendor: try to set false
,09-13 00:07:00.453  7109  7572 I bt_vendor: cleanup
09-13 00:07:00.454  7109  7628 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 00:07:00.454  7109  7572 I GKI_LINUX: GKI_exit_task 0 done
09-13 00:07:00.454  7109  7572 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 00:07:00.456  7109  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 00:07:00.458  7109  7109 D HeadsetService: Received stop request...Stopping profile...
09-13 00:07:00.459  7109  7109 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 00:07:00.459  7109  7109 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:07:00.459  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:07:00.461  7109  7594 D HeadsetStateMachine: Exit Disconnected: -1
,09-13 00:07:00.465  1033  1033 D BluetoothHeadset: Proxy object disconnected
09-13 00:07:00.465  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 00:07:00.466  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-13 00:07:00.466  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-13 00:07:00.467  1850  1850 D BluetoothHeadset: Proxy object disconnected
09-13 00:07:00.468  7109  7109 D HeadsetStateMachine: Unbinding service...
09-13 00:07:00.469  7109  7109 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 00:07:00.469  7109  7109 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 00:07:00.469  7109  7109 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 00:07:00.470  7109  7109 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 00:07:00.470  7109  7109 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 00:07:00.470  7109  7109 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:07:00.470  7109  7109 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 00:07:00.475  7109  7109 D A2dpService: Received stop request...Stopping profile...
,09-13 00:07:00.479  7109  7613 D A2dpStateMachine: Exit Disconnected: -1
09-13 00:07:00.482  7109  7109 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 00:07:00.484  7109  7109 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 00:07:00.484  7109  7109 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:07:00.484  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:07:00.486  7109  7559 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 00:07:00.487  1033  1033 D BluetoothA2dp: Proxy object disconnected
09-13 00:07:00.487  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 00:07:00.489  7109  7109 D HidService: Received stop request...Stopping profile...
09-13 00:07:00.489  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
,09-13 00:07:00.493  7109  7109 D HealthService: Received stop request...Stopping profile...
09-13 00:07:00.493  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:07:00.495  7109  7109 D PanService: Received stop request...Stopping profile...
09-13 00:07:00.495  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:07:00.497  7109  7109 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 00:07:00.498  7109  7109 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 00:07:00.498  7109  7109 D BtGatt.GattService: stop()
09-13 00:07:00.498  7109  7109 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 00:07:00.499  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:07:00.502  7109  7109 D BluetoothMapService: Received stop request...Stopping profile...
09-13 00:07:00.502  7109  7109 D BluetoothMapService: stop()
,09-13 00:07:00.505  7109  7109 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 00:07:00.505  7109  7109 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 00:07:00.506  7109  7109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1262a2
09-13 00:07:00.507  7109  7109 I BluetoothA2dpServiceJni: cleanupNative
09-13 00:07:00.507  7109  7614 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 00:07:00.508  7109  7109 I GKI_LINUX: GKI_exit_task 2 done
09-13 00:07:00.508  7109  7109 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 00:07:00.508  7109  7109 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 00:07:00.508  7109  7109 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 00:07:00.509  7109  7109 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 00:07:00.509  7109  7109 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:07:00.509  7109  7109 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:07:00.509  7109  7109 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 00:07:00.509  7109  7109 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 00:07:00.512  7109  7109 V BluetoothMapService: Handler(): got msg=4
09-13 00:07:00.512  7109  7109 D BluetoothMapService: MAP Service closeService in
09-13 00:07:00.512  7109  7109 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 00:07:00.512  7109  7109 V BluetoothMapService: MAP Service closeService out
09-13 00:07:00.515  7109  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 00:07:00.515  7109  7559 D BluetoothAdapterProperties: Setting state to 10
,09-13 00:07:00.515  7109  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-13 00:07:00.520  7109  7109 D BluetoothMapService: cleanup()
09-13 00:07:00.520  7109  7109 D BluetoothMapService: MAP Service closeService in
09-13 00:07:00.520  7109  7109 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 00:07:00.520  7109  7109 V BluetoothMapService: MAP Service closeService out
09-13 00:07:00.521  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:07:00.521  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 00:07:00.521  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 00:07:00.522  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:07:00.523  7109  7559 I BluetoothAdapterState: Entering OffState
09-13 00:07:00.524  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:07:00.524  6956  6978 D BluetoothMap: onBluetoothStateChange: up=false
09-13 00:07:00.526  1850  3470 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:07:00.527  6956  6978 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:07:00.528  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:07:00.528  6956  6978 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:07:00.531  6956  6978 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 00:07:00.531  6956  6978 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 00:07:00.532  6956  6978 D BluetoothPan: onBluetoothStateChange on: false
09-13 00:07:00.532  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:07:00.533  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 00:07:00.533  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-13 00:07:00.535  1033  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 00:07:00.535  1033  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 00:07:00.535  1033  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@14406b89 mBinding = false
09-13 00:07:00.536  1033  1109 D BluetoothManagerService: Sending unbind request.
09-13 00:07:00.541  7109  7572 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-13 00:07:00.544  7109  7109 I GKI_LINUX: GKI_exit_task 1 done
09-13 00:07:00.544  7109  7109 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 00:07:00.544  7109  7109 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 00:07:00.544  7109  7109 I art     : --- WEIRD: removing null entry 248
09-13 00:07:00.544  7109  7109 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-13 00:07:00.544  7109  7109 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 00:07:00.546  7109  7109 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 00:07:00.547  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 00:07:00.549  7109  7109 I art     : System.exit called, status: 0
09-13 00:07:00.549  7109  7109 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 00:07:00.569   312  2183 V AudioFlinger: 7109 died, releasing its sessions
09-13 00:07:00.569   312  2183 V AudioFlinger:  pid 1850 @ 0
09-13 00:07:00.569   312  2183 V AudioFlinger:  pid 3207 @ 1
09-13 00:07:00.569   312  2183 V AudioFlinger:  pid 3207 @ 2
,09-13 00:07:00.573  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-13 00:07:00.573  1940  2086 D LGBluetoothAPIService: Message: 101
09-13 00:07:00.573  1940  2086 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-13 00:07:00.574  1940  2086 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-13 00:07:00.574  1940  2086 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-13 00:07:00.576  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 00:07:00.586  1033  1782 I ActivityManager: Process com.android.bluetooth (pid 7109) has died
09-13 00:07:00.586  1033  1782 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-13 00:07:00.586  1033  1782 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-13 00:07:00.595  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:00.595  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:07:00.600  1940  2086 D LGBluetoothAPIService: Message: 2
09-13 00:07:00.600  1940  2086 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,09-13 00:07:00.604  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 00:07:00.604  6956  6956 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 00:07:00.606  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:00.607  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:00.609  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 00:07:00.624  1601  1601 D BluetoothAdapter: 343617701: getState() :  mService = null. Returning STATE_OFF
09-13 00:07:00.624  1601  1601 D BluetoothAdapter: 343617701: getState() :  mService = null. Returning STATE_OFF
,09-13 00:07:00.680  1033  1049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7744 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-13 00:07:00.686  6956  6956 D DockEventReceiver: finishStartingService: stopping service
09-13 00:07:00.729   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 29.678ms
,09-13 00:07:00.763   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 32.192ms
09-13 00:07:00.784  7744  7744 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-13 00:07:00.784  7744  7744 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:07:00.785  7744  7744 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-13 00:07:00.785  7744  7744 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 00:07:00.786   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 461us total 20.706ms
09-13 00:07:00.804  7744  7744 D BluetoothAdapterApp: Loading JNI Library
,09-13 00:07:00.838  7744  7744 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3973944a Instance Count = 1
,09-13 00:07:00.845  7744  7744 D BluetoothAdapterApp: onCreate
,09-13 00:07:00.869  7744  7744 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 00:07:00.869  7744  7744 D ProfileConfigQcom: Adding HeadsetService
09-13 00:07:00.869  7744  7744 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-13 00:07:00.870  7744  7744 D ProfileConfigQcom: Adding A2dpService
,09-13 00:07:00.870  7744  7744 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 00:07:00.870  7744  7744 D ProfileConfigQcom: Adding HidService
09-13 00:07:00.870  7744  7744 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 00:07:00.870  7744  7744 D ProfileConfigQcom: Adding HealthService
,09-13 00:07:00.871  7744  7744 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 00:07:00.872  7744  7744 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 00:07:00.872  7744  7744 D ProfileConfigQcom: Adding PanService
09-13 00:07:00.872  7744  7744 D ProfileConfigQcom: [BTUI] GattService is supported
,09-13 00:07:00.873  7744  7744 D ProfileConfigQcom: Adding GattService
09-13 00:07:00.873  7744  7744 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-13 00:07:00.873  7744  7744 D ProfileConfigQcom: Adding BluetoothMapService
09-13 00:07:00.873  7744  7744 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 00:07:00.874  7744  7744 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:07:00.876  7744  7744 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:07:00.876  7744  7744 V BluetoothPbapReceiver: ***********state = 10
09-13 00:07:00.878  7744  7744 V LGMDMManagerInternal: Create singleton instance
,09-13 00:07:00.967  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:07:00.982  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-13 00:07:00.984  7744  7744 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 00:07:00.985  7744  7744 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 00:07:00.988  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 00:07:00.988  1940  2086 D LGBluetoothAPIService: Message: 100
09-13 00:07:00.988  1940  2086 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 00:07:00.992  6956  6956 D BluetoothPermissionRequest: onReceive
09-13 00:07:00.995  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 00:07:00.995  6956  6956 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 00:07:00.997  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 00:07:01.003  7744  7744 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 00:07:01.009  7744  7744 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:01.012  7744  7744 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-13 00:07:01.013  7744  7744 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:07:01.013  7744  7744 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:07:01.014  7744  7744 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:01.015  7744  7744 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 00:07:01.018  7050  7050 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 00:07:02.523  1033  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 00:07:02.547  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 00:07:02.576  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:07:02.576  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:07:02.627  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 00:07:02.632  1033  1033 D administrator: Handling package changes for user 0
09-13 00:07:02.639  1033  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7802 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-13 00:07:02.645  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 00:07:02.650  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 00:07:02.674  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 00:07:02.699  7802  7802 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 00:07:02.751  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-13 00:07:02.751  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 00:07:02.780  7802  7802 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:07:02.780  7802  7802 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 00:07:02.798  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:07:02.803  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 00:07:02.812  2467  2467 V GmsNetworkLocationProvi: DISABLE
,09-13 00:07:02.815  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 00:07:02.838  1033  1089 D LocationProviderProxy: applying state to connected service
,09-13 00:07:02.842  2467  2467 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-13 00:07:02.873  7802  7833 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 00:07:02.873  7802  7833 I Babel   : MmsConfig.loadMmsSettings
09-13 00:07:02.877  7802  7833 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 00:07:02.877  7802  7833 I Babel   : MmsConfig.loadFromDatabase
,09-13 00:07:02.899  7802  7833 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 00:07:02.899  7802  7833 I Babel   : MmsConfig.loadFromResources
,09-13 00:07:02.900  7802  7802 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:02.902  7802  7833 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 00:07:02.904  7802  7833 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-13 00:07:02.921  1815  7835 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-13 00:07:02.921  1815  7835 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-13 00:07:02.926  7802  7831 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 00:07:02.929  7181  7181 I AppUp4:CustModeStarterReceiver: onReceive
09-13 00:07:02.931  7802  7831 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 00:07:02.933  7181  7181 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@18877e84
09-13 00:07:02.933  7181  7181 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 00:07:02.933  7181  7181 D AppUp4:CustFacade: isPhone : true
09-13 00:07:02.934  7181  7181 D AppUp4:CustModeStarterReceiver: begin check event
09-13 00:07:02.934  7181  7181 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 00:07:02.935  7802  7831 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-13 00:07:02.941  1815  5153 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-13 00:07:02.945  7802  7831 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 00:07:02.945  7802  7831 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 00:07:02.947  7802  7831 W AudioCapabilities: Unsupported mime audio/evrc
09-13 00:07:02.956  7802  7831 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-13 00:07:02.958  7802  7831 W VideoCapabilities: Unsupported mime video/divx
,09-13 00:07:02.959  7802  7831 W VideoCapabilities: Unsupported mime video/divx311
09-13 00:07:02.960  7802  7831 W VideoCapabilities: Unsupported mime video/divx4
09-13 00:07:02.966  1033  1988 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7839 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-13 00:07:02.968  7802  7831 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-13 00:07:02.969  1033  1592 I ActivityManager: Killing 6756:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-13 00:07:02.980  7802  7831 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 00:07:02.983  7802  7831 W AudioCapabilities: Unsupported mime audio/eac3
09-13 00:07:02.983  7802  7831 W AudioCapabilities: Unsupported mime audio/ac3
09-13 00:07:02.984  7802  7831 W AudioCapabilities: Unsupported mime audio/g726
09-13 00:07:02.985  7802  7831 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 00:07:02.985  7802  7831 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 00:07:02.986  7802  7831 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 00:07:02.999  7802  7831 W VideoCapabilities: Unsupported mime video/theora
09-13 00:07:03.000  7802  7831 W VideoCapabilities: Unsupported mime video/mjpg
,09-13 00:07:03.093  7839  7839 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:07:03.094  7839  7839 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:07:03.095  7839  7839 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 00:07:03.096  1033  2031 W libprocessgroup: failed to open /acct/uid_1000/pid_6756/cgroup.procs: No such file or directory
09-13 00:07:03.097  1033  2031 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-13 00:07:03.097  7030  7030 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 00:07:03.097  7030  7030 W System.err: android.os.DeadObjectException
09-13 00:07:03.097  7030  7030 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 00:07:03.097  7030  7030 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 00:07:03.097  7030  7030 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:03.097  7030  7030 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:03.097  7030  7030 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:03.097  7030  7030 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:07:03.097  7030  7030 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:03.097  7030  7030 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 00:07:03.097  7839  7839 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 00:07:03.098  7030  7030 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 00:07:03.098  7030  7030 W System.err: android.os.DeadObjectException
09-13 00:07:03.098  7030  7030 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 00:07:03.098  7030  7030 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 00:07:03.098  7839  7839 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 00:07:03.098  7030  7030 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:03.098  7030  7030 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:03.098  7030  7030 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:03.098  7030  7030 W System.err: 	at java.lang.reflect.Metho,d.invoke(Method.java:372)
09-13 00:07:03.098  7030  7030 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:03.098  7030  7030 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 00:07:03.098  7030  7030 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 00:07:03.098  7030  7030 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 00:07:03.101  7030  7030 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 00:07:03.101  7030  7030 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 00:07:03.144  1033  2006 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7858 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 00:07:03.145  7030  7030 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 00:07:03.182  7839  7839 I SystemConfig: BUILD Country: EU
09-13 00:07:03.182  7839  7839 I SystemConfig: BUILD Operator: OPEN
09-13 00:07:03.196  7858  7858 D UEI.SmartControl: Quickset Services start...
,09-13 00:07:03.198  7858  7858 I UEI.SmartControl: Manufacture = LGE
09-13 00:07:03.198  7858  7858 D UEI.SmartControl: Id = LGNevo
09-13 00:07:03.199  7858  7858 D UEI.SmartControl: File observer start...
09-13 00:07:03.200  7858  7858 E UEI.SmartControl: IR Port is disabled: false
09-13 00:07:03.200  7858  7858 D UEI.SmartControl: Starting file observer...
09-13 00:07:03.200  7858  7858 D UEI.SmartControl: Extracting JNI libs...
09-13 00:07:03.200  7858  7858 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only,
09-13 00:07:03.224  1033  1592 I ActivityManager: Killing 7030:com.lge.qremote/u0a112 (adj 15): empty #17
,09-13 00:07:03.259  7858  7858 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 00:07:03.259  7858  7858 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 00:07:03.259  7858  7858 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-13 00:07:03.280  7858  7858 I UEI.SmartControl: --- Selecting new region: 6
,09-13 00:07:03.281  7858  7858 I UEI.SmartControl: Model = LG-D855
09-13 00:07:03.282  7858  7858 D UEI.SmartControl: QS Service created
09-13 00:07:03.348  1033  1592 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7878 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 00:07:03.351  1033  1939 W libprocessgroup: failed to open /acct/uid_10112/pid_7030/cgroup.procs: No such file or directory
09-13 00:07:03.356  7839  7876 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 00:07:03.356  7839  7876 I SystemConfig: existFile = false
09-13 00:07:03.356  7839  7876 I SystemConfig: canReadFile = false
09-13 00:07:03.356  7839  7876 I SystemConfig: systemFeature RCS result false
09-13 00:07:03.356  7839  7876 D SystemConfig: refreshRcsSupport() :false
09-13 00:07:03.378  7858  7858 I UEI.SmartControl: Service initServices...
,09-13 00:07:03.383  7858  7858 D UEI.SmartControl: QS start get config
09-13 00:07:03.395  7878  7878 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:07:03.395  7878  7878 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 00:07:03.395  7878  7878 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 00:07:03.395  7878  7878 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 00:07:03.430  7858  7858 D UEI.SmartControl: Loading JNI Libs...
,09-13 00:07:03.452  7878  7878 I AppConfig: Total System Memory = 2995761152
,09-13 00:07:03.458  7878  7878 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-13 00:07:03.512  1033  1440 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-13 00:07:03.556  1033  1867 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7901 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 00:07:03.558  1033  1867 I ActivityManager: Killing 7212:com.lge.email/u0a23 (adj 15): empty #17
,09-13 00:07:03.648  1033  1902 W libprocessgroup: failed to open /acct/uid_10023/pid_7212/cgroup.procs: No such file or directory
,09-13 00:07:03.804  7858  7858 I UEI.SmartControl: Supports setup maps: true
,09-13 00:07:03.808  7858  7858 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 00:07:03.808  7858  7858 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 00:07:03.808  7858  7858 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 00:07:03.808  7858  7858 I UEI.SmartControl: ### init IR Blaster...
,09-13 00:07:03.816  7858  7858 D serial_port: Configuring serial port
09-13 00:07:03.822  7858  7858 E UEI.SmartControl: UEIBLaster setting for 616
09-13 00:07:03.822  7858  7858 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 00:07:03.823  7858  7858 I UEI.SmartControl: configuring settings for MAXQ616
09-13 00:07:03.823  7858  7858 I UEI.SmartControl: Get version...
,09-13 00:07:03.830  7901  7901 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-13 00:07:03.839  7858  7923 D UEI.SmartControl: serial port data available: 21
,09-13 00:07:03.866  7858  7858 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 00:07:03.866  7858  7858 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 00:07:03.867  7858  7858 I UEI.SmartControl: QS saving settings...
09-13 00:07:03.867  7858  7858 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 00:07:03.883  7858  7923 D UEI.SmartControl: serial port data available: 4
,09-13 00:07:03.908  1033  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1005529436, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,09-13 00:07:03.911  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{201eb512 type 2 when 195906 com.google.android.gms} when 195906
09-13 00:07:03.912  7901  7901 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:07:03.914  7858  7858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 00:07:03.913  7901  7901 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:07:03.918  7858  7858 E UEI.SmartControl: Services init done
09-13 00:07:03.918  7858  7858 D UEI.SmartControl: QS Service init finished
09-13 00:07:03.920  7858  7937 I UEI.SmartControl: Device manager: loading config....
09-13 00:07:03.920  7858  7937 D UEI.SmartControl: ----------- loading internal config...
09-13 00:07:03.920  7858  7858 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 00:07:03.921  7858  7858 D UEI.SmartControl: QS Service version code: 201091
09-13 00:07:03.922  7858  7858 D UEI.SmartControl: Service requested: Control
,09-13 00:07:03.928  7858  7937 E UEI.SmartControl: Loading SETTINGS...
09-13 00:07:03.932  7858  7858 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 00:07:03.935  7858  7858 D UEI.SmartControl: Service.onUnbind: IControl
09-13 00:07:03.936  7858  7858 D UEI.SmartControl: Service.onDestroy
09-13 00:07:03.936  7858  7858 D UEI.SmartControl: Lock is in USE false
09-13 00:07:03.936  7858  7937 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 00:07:03.937  7858  7858 D UEI.SmartControl: unbind internal service
09-13 00:07:03.938  7858  7858 D serial_port: close(fd = 25)
09-13 00:07:03.942  7858  7858 I UEI.SmartControl: Serial port is closed.
09-13 00:07:03.942  7858  7858 I UEI.SmartControl: Serial port is closed.
09-13 00:07:03.942  7858  7936 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 00:07:03.942  7858  7858 D UEI.SmartControl: Blaster closed
09-13 00:07:03.942  7858  7936 D UEI.SmartControl: -----service ready thread exits
09-13 00:07:03.942  7858  7858 D UEI.SmartControl: Shut down QS...
09-13 00:07:03.942  7858  7858 D UEI.SmartControl: Stopping QS lib
09-13 00:07:03.943  7858  7858 D UEI.SmartControl: QS lib stop result = true
09-13 00:07:03.943  7858  7858 D UEI.SmartControl: Stopped QS lib
09-13 00:07:03.943  7858  7858 D UEI.SmartControl: Stopped file observer...
09-13 00:07:03.943  7858  7858 D UEI.SmartControl: QS shutdown complete
09-13 00:07:03.944  7858  7858 D UEI.SmartControl: QS Service created
09-13 00:07:03.952  2622  2622 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 00:07:03.963  7858  7858 I UEI.SmartControl: Service initServices...
09-13 00:07:03.964  7858  7858 D UEI.SmartControl: QS start get config
,09-13 00:07:03.993  7901  7901 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 00:07:04.011  7901  7901 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 00:07:04.012  7901  7901 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 00:07:04.027  7901  7901 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 00:07:04.027  7901  7901 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 00:07:04.044  1033  1050 I ActivityManager: Killing 7077:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-13 00:07:04.236  1033  2031 W libprocessgroup: failed to open /acct/uid_10026/pid_7077/cgroup.procs: No such file or directory
,09-13 00:07:04.241  5060  7950 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-13 00:07:04.246  2859  3045 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-13 00:07:04.248  2859  3045 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@28149281 on behalf of 7901
09-13 00:07:04.268  1033  1903 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7951 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 00:07:04.292  7901  7901 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 00:07:04.310  7901  7901 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-13 00:07:04.332  7951  7951 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 00:07:04.346  7951  7951 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 00:07:04.346  7951  7951 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 00:07:04.346  7951  7951 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-13 00:07:04.346  7951  7951 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 00:07:04.346  7951  7951 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 00:07:04.346  7951  7951 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-13 00:07:04.352  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1005529436 [*alarm*], flags=0x0
,09-13 00:07:04.355   308  7973 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 00:07:04.355  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 00:07:04.360  1033  1938 I ActivityManager: Killing 6424:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-13 00:07:04.394  7858  7858 I UEI.SmartControl: Supports setup maps: true
,09-13 00:07:04.400  7858  7858 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 00:07:04.400  7858  7858 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 00:07:04.400  7858  7858 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 00:07:04.400  7858  7858 I UEI.SmartControl: ### init IR Blaster...
,09-13 00:07:04.403  7858  7858 D serial_port: Configuring serial port
09-13 00:07:04.403  7858  7858 E UEI.SmartControl: UEIBLaster setting for 616
09-13 00:07:04.403  7858  7858 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 00:07:04.403  7858  7858 I UEI.SmartControl: configuring settings for MAXQ616
09-13 00:07:04.403  7858  7858 I UEI.SmartControl: Get version...
09-13 00:07:04.410  1033  1592 W libprocessgroup: failed to open /acct/uid_1000/pid_6424/cgroup.procs: No such file or directory
,09-13 00:07:04.420  7858  7974 D UEI.SmartControl: serial port data available: 21
09-13 00:07:04.446  7858  7858 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 00:07:04.446  7858  7858 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 00:07:04.446  7858  7858 I UEI.SmartControl: QS saving settings...
,09-13 00:07:04.448  7858  7858 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 00:07:04.464  7858  7974 D UEI.SmartControl: serial port data available: 4
,09-13 00:07:04.496  7858  7977 I UEI.SmartControl: Device manager: loading config....
09-13 00:07:04.496  7858  7977 D UEI.SmartControl: ----------- loading internal config...
09-13 00:07:04.497  7858  7858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 00:07:04.500  7858  7858 E UEI.SmartControl: Services init done
09-13 00:07:04.500  7858  7858 D UEI.SmartControl: QS Service init finished
09-13 00:07:04.502  7858  7858 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 00:07:04.502  7858  7858 D UEI.SmartControl: QS Service version code: 201091
09-13 00:07:04.503  7858  7858 D UEI.SmartControl: Service requested: Control
09-13 00:07:04.505  7858  7977 E UEI.SmartControl: Loading SETTINGS...
09-13 00:07:04.508  7858  7858 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 00:07:04.511  1033  1939 I ActivityManager: Killing 7242:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-13 00:07:04.515  7858  7977 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 00:07:04.534  7858  7976 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 00:07:04.534  7858  7976 D UEI.SmartControl: -----service ready thread exits
,09-13 00:07:04.599  1033  1592 W libprocessgroup: failed to open /acct/uid_10046/pid_7242/cgroup.procs: No such file or directory
09-13 00:07:04.601  7858  7858 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1e3ffef0 that was originally bound here
09-13 00:07:04.601  7858  7858 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1e3ffef0 that was originally bound here
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:04.601  7858  7858 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 00:07:04.610  7858  7858 D UEI.SmartControl: Internal service binding...
,09-13 00:07:04.756  1033  1867 V SIM_STK : Menu title from STK is T-Mobile
,09-13 00:07:04.782  5060  7950 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 542 ms] updated apps [took 541 ms] 
,09-13 00:07:04.936  7858  7939 D UEI.SmartControl: Internal timer expired: 2
,09-13 00:07:05.429   306   306 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
,09-13 00:07:05.430   306   306 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-13 00:07:05.430   306   306 I rmt_storage: wakelock acquired: 1, error no: 42
,09-13 00:07:05.431   306   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
09-13 00:07:05.595   306   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
09-13 00:07:05.595   306   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-13 00:07:05.595   306   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
09-13 00:07:05.595   306   905 I rmt_storage: 
,09-13 00:07:05.599   306   306 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,09-13 00:07:05.600   903   915 E Diag_Lib: [IMS_FATAL]| 3347 | 915 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
09-13 00:07:05.649  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:05.649  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1cfa076 added. We now have 6 listener(s)
09-13 00:07:05.649  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:07:05.659  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:05.659  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@198f7677 added. We now have 7 listener(s)
09-13 00:07:05.659  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:05.660  6853  6931 I System.out: IsBluetoothEnabled
09-13 00:07:05.661  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:05.661  1033  1938 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-13 00:07:05.662  1033  1109 D BluetoothManagerService: Message: 2
09-13 00:07:05.667  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:07:05.670  1033  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:05.670  1033  1050 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-13 00:07:05.734  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:07:05.735  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:07:05.735  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:07:05.736  1033  1109 D BluetoothManagerService: Message: 1
09-13 00:07:05.736  1033  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-13 00:07:05.762  1033  1109 D BluetoothManagerService: Message: 20
09-13 00:07:05.762  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb66e41:true
,09-13 00:07:05.766  7744  7744 D BluetoothAdapterState: make
09-13 00:07:05.771  7744  7744 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 00:07:05.771  7744  7744 I bluedroid-qcom: init
09-13 00:07:05.772  7744  7992 I BluetoothAdapterState: Entering OffState
09-13 00:07:05.772  7744  7744 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 00:07:05.773  7744  7744 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 00:07:05.773  7744  7744 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 00:07:05.773  7744  7744 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 00:07:05.773  7744  7744 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 00:07:05.775  7744  7744 I bluedroid-qcom: get_profile_interface socket
09-13 00:07:05.775  7744  7744 I bluedroid-qcom: get_profile_interface map_client
,09-13 00:07:05.779  7744  7996 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 00:07:05.766  7995  7995 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:05.784  7744  7996 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 00:07:05.766  7995  7995 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:05.795  7995  7995 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 00:07:05.795  7995  7995 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 00:07:05.795  7995  7995 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-13 00:07:05.800  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 00:07:05.800  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 00:07:05.801  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-13 00:07:05.801  1033  1109 D BluetoothManagerService: Message: 40
09-13 00:07:05.801  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 00:07:05.802  7744  7765 I bluedroid-qcom: config_hci_snoop_log
09-13 00:07:05.803  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 00:07:05.803  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 00:07:05.804  7995  7995 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 00:07:05.811  7995  7995 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 00:07:05.811  7995  7995 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-13 00:07:05.816  7744  7992 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 00:07:05.817  7744  7996 D BluetoothAdapterProperties: Name is: G3
09-13 00:07:05.817  7744  7992 D BluetoothAdapterProperties: Setting state to 11
09-13 00:07:05.817  7744  7992 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 00:07:05.818  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:07:05.818  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 00:07:05.818  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 00:07:05.819  7744  7992 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 00:07:05.826  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:07:05.829  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:07:05.830  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:05.835  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 00:07:05.842  7744  7744 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:07:05.842  7744  7744 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:05.842  7744  7744 V BluetoothPbapReceiver: ***********state = 11
,09-13 00:07:05.853  7744  7992 D BluetoothBondStateMachine: make
09-13 00:07:05.857  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:07:05.862  7744  7992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:05.862  7744  7992 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 00:07:05.862  7744  7992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:05.862  7744  7992 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 00:07:05.863  7744  7992 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 00:07:05.864  7744  7997 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 00:07:05.873  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 00:07:05.887  7744  7744 D HeadsetService: Received start request. Starting profile...
09-13 00:07:05.887  7744  7744 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 00:07:05.888  7744  7744 D LGBluetoothHfpAdapter: Version 1.6
09-13 00:07:05.891  7744  7744 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 00:07:05.892  7744  7744 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 00:07:05.892  7744  7744 D HeadsetStateMachine: make
,09-13 00:07:05.914  6956  6956 D BluetoothPermissionRequest: onReceive
,09-13 00:07:05.930  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 00:07:05.941  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 00:07:05.950  7744  7744 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:07:05.950  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:07:05.950  7744  7744 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 00:07:05.959  7744  7744 D HeadsetStateMachine: max_hf_connections = 1
09-13 00:07:05.959  7744  7744 I bluedroid-qcom: get_profile_interface handsfree
09-13 00:07:05.959  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:07:05.961  7744  7744 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-13 00:07:05.962   312   312 V AudioPolicyService: registerClient() client 0xb558af20, uid 1002
09-13 00:07:05.962   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 00:07:05.962   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 00:07:05.962   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 00:07:05.962  7744  7744 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 00:07:05.963   312  2183 V AudioFlinger: registerClient() client 0xb55815e0, pid 7744
09-13 00:07:05.963   312  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:07:05.963   312  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:07:05.964  7744  7744 V ToneGenerator: Create Track: 0xb4927680
09-13 00:07:05.964  7744  7744 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 00:07:05.964  7744  7744 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 00:07:05.964  7744  7765 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:07:05.964  7744  7765 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 00:07:05.964   312  1401 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 00:07:05.964   312  1401 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 00:07:05.964   312  1401 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 00:07:05.964   312  1401 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 00:07:05.965  7744  7744 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 00:07:05.965  1033  2031 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:07:05.965  1033  2031 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:07:05.965  1601  2069 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:07:05.965  1601  2069 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:07:05.966   312  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-13 00:07:05.966   312  1393 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:07:05.966  1033  1903 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:07:05.966  1033  1903 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:07:05.966  1601  2542 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:07:05.966  1601  2542 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:07:05.966  7744  7759 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:07:05.966  1850  2455 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:07:05.966  1850  2455 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:07:05.966  7744  7759 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 00:07:05.966  1850  2455 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:07:05.966  1850  2455 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:07:05.966  3207  3227 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 00:07:05.966  3207  3227 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 00:07:05.967  3207  3227 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 00:07:05.967  3207  3227 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 00:07:05.968   312  2183 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 00:07:05.968   312  1401 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 00:07:05.968   312  1401 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 00:07:05.968   312  1401 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 00:07:05.968   312  1401 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 00:07:05.968  7744  7744 V AudioSystem: getLatency() output 2, latency 50
09-13 00:07:05.968  7744  7744 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 00:07:05.968  7744  7744 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 00:07:05.969   312  2174 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 00:07:05.969   312  2174 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 00:07:05.969   312  2174 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 00:07:05.969   312  2174 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 00:07:05.969   312  2174 V AudioFlinger: createTrack() lSessionId: 21
09-13 00:07:05.970  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:07:05.971  7744  7744 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 00:07:05.972   312  2174 V AudioFlinger: acquiring 21 from 7744, for 7744
09-13 00:07:05.972   312  2174 V AudioFlinger:  added new entry for 21
09-13 00:07:05.973  7744  7744 V ToneGenerator: ToneGenerator INIT OK, time: 197986
09-13 00:07:05.973  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:05.974  7744  7998 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 00:07:05.974  7744  7998 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 00:07:05.975  7744  7998 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 00:07:05.975  7744  7998 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 00:07:05.975   312  1400 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7744
09-13 00:07:05.975  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:05.977   312  1400 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 00:0,7:05.977   312  1400 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 00:07:05.977   312  1400 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 00:07:05.977   312  1400 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 00:07:05.977   312  1400 V voice   : voice_set_parameters: exit with code(0)
09-13 00:07:05.978   312  1400 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 00:07:05.978   312  1400 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 00:07:05.978   312  1400 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 00:07:05.978   312  1400 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 00:07:05.978   312  1400 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 00:07:05.978   312  1400 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 00:07:05.978  7744  7744 D A2dpService: Received start request. Starting profile...
09-13 00:07:05.979  7744  7998 V ToneGenerator: ToneGenerator destructor
09-13 00:07:05.979  7744  7998 V ToneGenerator: stopTone
09-13 00:07:05.979  7744  7998 V ToneGenerator: Delete Track: 0xb4927680
09-13 00:07:05.979  7744  7744 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 00:07:05.981  7744  7744 V Avrcp   : make
09-13 00:07:05.982  7744  7744 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 00:07:05.982  7744  7744 I bluedroid-qcom: get_profile_interface avrcp
09-13 00:07:05.984   312  2183 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 00:07:05.984   312  2183 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 00:07:05.984   312  1267 V AudioPolicyService: AudioCommandThread() waking up
09-13 00:07:05.984   312  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 00:07:05.984   312  1267 V AudioPolicyManager: releaseOutput() 2
09-13 00:07:05.984   312  1267 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 00:07:05.985   312  2183 V AudioFlinger: PlaybackThread::Track destructor
09-13 00:07:05.985   312  2183 V AudioFlinger: removeClient_l() pid 7744, calling pid 312
09-13 00:07:05.985  7744  7998 V AudioTrack: ~AudioTrack, releasing session id from 7744 on behalf of 7744
09-13 00:07:05.985   312  2174 V AudioFlinger: releasing 21 from 7744 for 7744
09-13 00:07:05.985   312  2174 V AudioFlinger:  decremented refcount to 0
09-13 00:07:05.985   312  2174 V AudioFlinger: purging stale effects
09-13 00:07:05.991  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:07:05.997  7744  7992 E BluetoothAdapterService: File transfer profiles supported!!
09-13 00:07:05.997  7744  7744 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 00:07:05.999  7744  7744 E AudioManager: No RCC entry present to update
09-13 00:07:05.999  7744  7744 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 00:07:06.003  7744  7744 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 00:07:06.005  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 00:07:06.005  7744  7744 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 00:07:06.009  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 00:07:06.019  7744  7992 V LGMDMManager: Create singleton instance
09-13 00:07:06.021  7744  7992 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 00:07:06.119  1033  1903 V SIM_STK : Menu title from STK is T-Mobile
09-13 00:07:06.119  1033  1903 V SIM_STK : Menu title from STK is T-Mobile
,09-13 00:07:06.191  1033  1572 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 00:07:06.200  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 00:07:06.204  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 00:07:06.205  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 00:07:06.205  7744  7744 I BluetoothA2dpServiceJni: classInitNative
09-13 00:07:06.205  7744  7744 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 00:07:06.205  7744  7744 D A2dpStateMachine: make
09-13 00:07:06.208  7744  7744 I bluedroid-qcom: get_profile_interface a2dp
,09-13 00:07:06.208  7744  8020 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 00:07:06.211  7744  7744 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 00:07:06.211  7744  7744 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 00:07:06.212  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.212  7744  8019 D A2dpStateMachine: Enter Disconnected: -2
09-13 00:07:06.213  7744  7744 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 00:07:06.214  7744  7744 D HidService: Received start request. Starting profile...
09-13 00:07:06.214  7744  7744 I bluedroid-qcom: get_profile_interface hidhost
09-13 00:07:06.214  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.215  7744  7744 D HeadsetStateMachine: Proxy object connected
09-13 00:07:06.215  7744  7744 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 00:07:06.215  7744  7744 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 00:07:06.217  7744  7744 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 00:07:06.218  7744  7744 D HealthService: Received start request. Starting profile...
09-13 00:07:06.221  7744  7744 I bluedroid-qcom: get_profile_interface health
,09-13 00:07:06.223  7744  7744 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 00:07:06.223  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.227  7744  7744 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:07:06.228  7744  7998 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 00:07:06.228  7744  7998 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 00:07:06.228  7744  7998 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 00:07:06.229  7744  7744 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 00:07:06.231  7744  7744 D PanService: Received start request. Starting profile...
09-13 00:07:06.231  7744  7744 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 00:07:06.231  7744  7744 I bluedroid-qcom: get_profile_interface pan
09-13 00:07:06.239  7744  7744 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-13 00:07:06.239  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.241  7744  7744 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:06.243  7744  7744 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 00:07:06.247  7744  7744 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 00:07:06.247  7744  7744 D BtGatt.GattService: Received start request. Starting profile...
09-13 00:07:06.247  7744  7744 D BtGatt.GattService: start()
09-13 00:07:06.247  7744  7744 I bluedroid-qcom: get_profile_interface gatt
09-13 00:07:06.248  7744  7744 D BtGatt.AdvertiseManager: advertise manager created
,09-13 00:07:06.411  1033  1939 I art     : Explicit concurrent mark sweep GC freed 29444(1440KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.955ms total 155.143ms
,09-13 00:07:06.413  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.415  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.415  7744  7744 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 00:07:06.416  7744  7744 V BluetoothMapService: BluetoothMapBinder()
09-13 00:07:06.416  7744  7744 D BluetoothMapService: Received start request. Starting profile...
09-13 00:07:06.416  7744  7744 D BluetoothMapService: start()
09-13 00:07:06.420  7744  7744 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 00:07:06.420  7744  7744 D BluetoothMapEmailAppObserver: createReceiver()
09-13 00:07:06.422  7744  7744 D BluetoothMapEmailAppObserver: initObservers()
09-13 00:07:06.422  7744  7744 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 00:07:06.428  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:06.431  7744  7744 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 00:07:06.433  7744  7744 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:07:06.435  7744  7744 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:07:06.435  7744  7744 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 00:07:06.438  7744  7744 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 00:07:06.438  7744  7744 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:07:06.438  7744  7744 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:07:06.438  7744  7744 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:07:06.438  7744  7744 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:06.438  7744  7744 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 00:07:06.442  7744  7744 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 00:07:06.442  7744  7744 V BluetoothMapService: Handler(): got msg=1
09-13 00:07:06.443  7744  7992 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 00:07:06.443  7744  7992 I bluedroid-qcom: enable
09-13 00:07:06.443  7744  7992 I bt_hci_bdroid: init
09-13 00:07:06.444  7744  7992 I bt_vendor: bt-vendor : init
09-13 00:07:06.444  7744  7992 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 00:07:06.444  7744  7992 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-13 00:07:06.444  7744  7992 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 00:07:06.444  7744  7992 D bt_userial_mct: userial_init
09-13 00:07:06.444  7744  7992 D bt_hci_bdroid: set_power 1
09-13 00:07:06.444  7744  7992 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 00:07:06.444  7744  7992 I bt_vendor: Starting hciattach daemon
09-13 00:07:06.444  7744  7992 I bt_vendor: try to set true
09-13 00:07:06.445  7744  8033 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 00:07:06.445  7744  8033 I bt-btu  : btu_task pending for preload complete event
09-13 00:07:06.436  8036  8036 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:06.436  8036  8036 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 00:07:06.467  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 00:07:06.538  8043  8043 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 00:07:06.552  8048  8048 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 00:07:06.579  8050  8050 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 00:07:06.591  8051  8051 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 00:07:06.603  8053  8053 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 00:07:06.629  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 00:07:06.659  8056  8056 I libmdmdetect: ESOC framework not supported
,09-13 00:07:06.661  8056  8056 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-13 00:07:06.672  8056  8056 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 00:07:06.672  8056  8056 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 00:07:06.672  8056  8056 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 00:07:06.672  8056  8056 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 00:07:06.673  8056  8056 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 00:07:06.673  8056  8056 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 00:07:06.673  8056  8056 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-13 00:07:06.722  8056  8058 E QC-QMI  : qmi_client [8056] 15: failed to locate client data
,09-13 00:07:06.722   457   457 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 00:07:06.723   457   457 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-13 00:07:06.784  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 00:07:06.812  8063  8063 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 00:07:06.847  7744  7992 I bt_vendor: bluetooth satus is on
09-13 00:07:06.847  7744  7992 D bt_hci_bdroid: preload
09-13 00:07:06.847  7744  8035 D bt_userial_mct: userial_open(port:0)
09-13 00:07:06.847  7744  8035 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 00:07:06.851  7744  8035 I bt_vendor: Done intiailizing UART
,09-13 00:07:06.851  7744  8035 I bt_vendor: Done intiailizing UART
09-13 00:07:06.851  7744  8035 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 00:07:06.852  7744  8035 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 00:07:06.852  7744  8033 I bt-btu  : btu_task received preload complete event
09-13 00:07:06.852  7744  8065 D bt_userial_mct: Entering userial_read_thread()
09-13 00:07:06.853  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 00:07:06.853  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 00:07:06.855  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 00:07:06.859  7744  8033 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 00:07:06.859  7744  8033 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 00:07:06.859  7744  8033 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 00:07:06.860  7744  8033 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 00:07:06.960  7744  8033 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-13 00:07:06.960  7744  8033 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
,09-13 00:07:06.960  7744  8033 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 
,09-13 00:07:07.013  7744  7996 E bt-btif : Calling BTA_HhEnable
,09-13 00:07:07.013  7744  7996 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 00:07:07.014  7744  7996 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-13 00:07:07.022  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 00:07:07.022  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 00:07:07.023  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 00:07:07.023  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 00:07:07.023  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 00:07:07.029  7744  7996 D BluetoothAdapterProperties: Name is: G3
09-13 00:07:07.038  7744  7996 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:07:07.038  7744  7996 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 00:07:07.038  7744  7996 D bt_hci_bdroid: postload
,09-13 00:07:07.040  7744  8035 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:07:07.041  7744  8033 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 00:07:07.042  7744  7996 D bte_conf: Device ID record 1 : primary
09-13 00:07:07.042  7744  7996 D bte_conf:   vendorId            = 00c4
09-13 00:07:07.042  7744  7996 D bte_conf:   vendorIdSource      = 0001
09-13 00:07:07.042  7744  7996 D bte_conf:   product             = 13a1
09-13 00:07:07.042  7744  7996 D bte_conf:   version             = 1000
09-13 00:07:07.042  7744  7996 D bte_conf:   clientExecutableURL = 
09-13 00:07:07.042  7744  7996 D bte_conf:   serviceDescription  = 
09-13 00:07:07.042  7744  7996 D bte_conf:   documentationURL    = 
09-13 00:07:07.042  7744  7996 D bte_conf: bte_load_did_conf no section named DID2.
09-13 00:07:07.045  7744  8033 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:07:07.045  7744  8033 W bt-smp  : Plain text(LSB ~ MSB) = d9 ea 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:07:07.045  7744  8033 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 76 1b 98 f4 26 b2 fb 00 16 c2 a6 4e 06 ca 64 
09-13 00:07:07.047  7744  8035 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:07:07.047  7744  8033 W bt-btm  : Stopping oneshot timer
09-13 00:07:07.036  8070  8070 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:07.050  7744  8035 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 00:07:07.052  7744  7992 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 00:07:07.053  7744  7992 D BluetoothAdapterProperties: ScanMode =  20
09-13 00:07:07.053  7744  7992 D BluetoothAdapterProperties: State =  11
09-13 00:07:07.054  7744  7992 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 00:07:07.036  8070  8070 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:07.056  7744  7992 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 00:07:07.057  7744  7992 D BluetoothAdapterProperties: Setting state to 12
09-13 00:07:07.057  7744  7992 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 00:07:07.057  7744  7996 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 00:07:07.057  7744  7996 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 00:07:07.070  1033  1109 D BluetoothManagerService: Message: 60
09-13 00:07:07.070  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 00:07:07.070  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 00:07:07.070  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 00:07:07.073  7744  7992 I BluetoothAdapterState: Entering On State
09-13 00:07:07.077  7744  8035 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 00:07:07.081  7744  7992 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 00:07:07.081  7744  7992 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 00:07:07.081  7744  7992 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 00:07:07.083  7744  8065 E bt_mct  : hci lib postload completed
,09-13 00:07:07.085  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 00:07:07.089  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 00:07:07.095  7744  7992 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-13 00:07:07.098  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:07:07.116  7744  8033 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-13 00:07:07.119  7744  8033 W bt-smp  : Plain text(LSB ~ MSB) = 23 ab 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:07:07.119  7744  8033 W bt-smp  : Encrypted text(LSB ~ MSB) = a6 e5 5d f3 50 22 10 60 5c e9 ed f2 66 ca 5b 7e 
09-13 00:07:07.119  7744  8033 W bt-btm  : Stopping oneshot timer
09-13 00:07:07.122  7744  7996 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 00:07:07.122  7744  7996 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 00:07:07.122  7744  7992 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:07:07.134  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:07:07.137  1033  1033 D BluetoothHeadset: Proxy object connected
09-13 00:07:07.143  7744  8033 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:07:07.143  7744  8033 W bt-smp  : Plain text(LSB ~ MSB) = f9 7e 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:07:07.143  7744  8033 W bt-smp  : Encrypted text(LSB ~ MSB) = ab 3e b0 41 ca 4d e0 38 3a 01 1c 4d 61 ae 4a 74 
09-13 00:07:07.144  7744  8033 W bt-btm  : Stopping oneshot timer
09-13 00:07:07.143  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:07:07.157  1850  1850 D BluetoothHeadset: Proxy object connected
,09-13 00:07:07.164  6956  6980 D BluetoothMap: onBluetoothStateChange: up=true
09-13 00:07:07.172  7744  8033 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:07:07.172  7744  8033 W bt-smp  : Plain text(LSB ~ MSB) = d8 ec 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:07:07.172  7744  8033 W bt-smp  : Encrypted text(LSB ~ MSB) = 28 2f ad 2e b5 3c eb 5a 84 44 aa 67 6d dd 61 51 
,09-13 00:07:07.175  7744  8033 W bt-btm  : Stopping oneshot timer
09-13 00:07:07.189  7744  8033 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 00:07:07.189  7744  8033 W bt-smp  : Plain text(LSB ~ MSB) = ea 8d 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 00:07:07.189  7744  8033 W bt-smp  : Encrypted text(LSB ~ MSB) = 60 71 6f 65 6b c0 84 f1 1c b3 eb e1 7d c9 93 d8 
09-13 00:07:07.189  7744  8033 W bt-btm  : Stopping oneshot timer
,09-13 00:07:07.196  6956  6956 D BluetoothMap: Proxy object connected
09-13 00:07:07.197  6956  6956 D MapProfile: Bluetooth service connected
09-13 00:07:07.197  6956  6956 D BluetoothMap: getConnectedDevices()
09-13 00:07:07.200  7744  7759 V BluetoothMapService: getConnectedDevices()
09-13 00:07:07.200  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:07:07.202  1850  1850 D BluetoothHeadset: Proxy object connected
09-13 00:07:07.202  6956  6980 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:07:07.205  6956  6956 D BluetoothHeadset: Proxy object connected
09-13 00:07:07.205  1850  2455 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:07:07.205  6956  6956 D HeadsetProfile: Bluetooth service connected
,09-13 00:07:07.210  1850  1850 D BluetoothHeadset: Proxy object connected
09-13 00:07:07.210  6956  6980 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:07:07.214  6956  6980 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 00:07:07.214  6956  6956 D BluetoothA2dp: Proxy object connected
09-13 00:07:07.214  6956  6956 D A2dpProfile: Bluetooth service connected
09-13 00:07:07.214  8076  8076 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 00:07:07.215  6956  6980 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 00:07:07.217  6956  6980 D BluetoothPan: onBluetoothStateChange on: true
09-13 00:07:07.217  6956  6980 D BluetoothPan: onBluetoothStateChange call bindService
09-13 00:07:07.217  6956  6956 D BluetoothInputDevice: Proxy object connected
09-13 00:07:07.218  6956  6956 D HidProfile: Bluetooth service connected
,09-13 00:07:07.221  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:07:07.221  1033  1033 D BluetoothA2dp: Proxy object connected
09-13 00:07:07.222  1033  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 00:07:07.222  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 00:07:07.223  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 00:07:07.224  1033  1109 D BluetoothManagerService: Message: 40
09-13 00:07:07.224  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-13 00:07:07.224  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:07:07.224  6956  6956 D PanProfile: Bluetooth service connected
09-13 00:07:07.224  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 00:07:07.227  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.227  1940  2086 D LGBluetoothAPIService: Message: 1
09-13 00:07:07.227  1940  2086 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 00:07:07.227  1940  2086 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-13 00:07:07.227  1940  2086 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-13 00:07:07.228  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:07.230  7744  7744 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.231  7744  7744 D BluetoothMapService: STATE_ON
,09-13 00:07:07.236  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 00:07:07.239  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 00:07:07.244  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:07:07.246  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:07.246  7744  7744 V BluetoothPbapService: Pbap Service onCreate
09-13 00:07:07.246  7744  7744 V BluetoothPbapService: Starting PBAP service
09-13 00:07:07.248  7744  7744 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 00:07:07.248  7744  7744 V BluetoothPbapService: Pbap Service onBind
09-13 00:07:07.249  7744  7744 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.249  6956  6956 D BluetoothPbap: Proxy object connected
09-13 00:07:07.249  6956  6956 D PbapServerProfile: Bluetooth service connected
09-13 00:07:07.249  7744  7744 V BluetoothPbapService: state: 12
09-13 00:07:07.249  7744  7744 V BluetoothMapService: Handler(): got msg=1
,09-13 00:07:07.249  7744  7744 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 00:07:07.250  7744  7744 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 00:07:07.250  7744  7744 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.250  7744  7744 V BluetoothPbapReceiver: ***********state = 12
09-13 00:07:07.250  7744  8095 D BluetoothMapMasInstance: MAS initSocket()
09-13 00:07:07.251  7744  8095 D BluetoothMapMasInstance:   masId = 00
09-13 00:07:07.251  7744  8095 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 00:07:07.251  7744  8095 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 00:07:07.251  7744  8095 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 00:07:07.251  7744  7744 V BluetoothPbapService: Handler(): got msg=1
09-13 00:07:07.252  7744  7744 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 00:07:07.253  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:07.253  7744  8096 V BluetoothPbapService: Pbap Service initSocket
09-13 00:07:07.253  1033  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:07.254  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:07:07.254  7744  8095 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:07:07.254  2199  2199 D c       : Getting all permits...
09-13 00:07:07.254  2199  2199 D a       : Opening database...
09-13 00:07:07.255  7744  7996 D BluetoothAdapterProperties: Scan Mode:21
09-13 00:07:07.255  7744  7996 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 00:07:07.256  7744  8095 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 00:07:07.257  7744  8095 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 00:07:07.257  7744  8095 D BluetoothMapMasInstance: Accepting socket connection...
09-13 00:07:07.257  7744  8096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:07:07.257  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:07.258  7744  8096 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 00:07:07.258  7744  8096 V BluetoothPbapService: Succeed to create listening socket 
09-13 00:07:07.258  7744  8096 V BluetoothPbapService: Accepting socket connection...
,09-13 00:07:07.262  2199  2199 D a       : Opening database auth.proximity.permit_store...
09-13 00:07:07.263  2199  2199 D a       : Closing database...
09-13 00:07:07.272  6956  6956 D BluetoothPermissionRequest: onReceive
,09-13 00:07:07.274  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 00:07:07.275  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 00:07:07.278  7744  7744 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 00:07:07.279  7744  7744 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 00:07:07.284  7744  7744 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-13 00:07:07.298  7744  7744 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-13 00:07:07.298  7744  7744 V BtOppService: onCreate
09-13 00:07:07.301  7744  7744 V BluetoothOppNotification: send message
09-13 00:07:07.303  7744  7744 V BtOppService: Starting RfcommListener
09-13 00:07:07.307  7744  7744 D BluetoothOppPreference: Dumping Names:  
09-13 00:07:07.307  7744  7744 D BluetoothOppPreference: {}
09-13 00:07:07.307  7744  7744 D BluetoothOppPreference: Dumping Channels:  
09-13 00:07:07.307  7744  7744 D BluetoothOppPreference: {}
09-13 00:07:07.307  7744  7744 V BtOppService: onStartCommand
09-13 00:07:07.310  7744  8103 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 00:07:07.310  7744  8100 V BtOppService: Deleted complete outbound shares, number =  0
,09-13 00:07:07.311  7744  7744 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.312  7744  7744 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 00:07:07.312  7744  8100 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 00:07:07.312  7744  8100 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 00:07:07.312  7744  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 00:07:07.313  7744  8100 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16c43c5f on behalf of 
09-13 00:07:07.313  7744  7744 V BluetoothOppNotification: new notify threadi!
09-13 00:07:07.314  7744  7744 V BluetoothOppNotification: send delay message
09-13 00:07:07.315  7744  7744 V BtOppService: start RfcommListener
09-13 00:07:07.315  7744  8104 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 00:07:07.317  7744  7744 V BtOppService: RfcommListener started
09-13 00:07:07.317  7744  7744 V BtOppService: ContentObserver received notification
,09-13 00:07:07.317  7744  7744 V BtOppService: ContentObserver received notification
09-13 00:07:07.323  7744  8104 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c6cd6ac on behalf of 
09-13 00:07:07.324  7744  8104 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 00:07:07.325  7744  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28c7ff75 on behalf of 
09-13 00:07:07.326  7744  8104 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 00:07:07.326  7744  8105 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 00:07:07.327  1033  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:07.327  7744  8103 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 00:07:07.327  7744  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-13 00:07:07.328  7744  8105 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:07:07.328  7744  8104 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@167b9b0a on behalf of 
09-13 00:07:07.329  7744  8105 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-13 00:07:07.329  7744  8104 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 00:07:07.329  7744  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f9a3f7b on behalf of 
09-13 00:07:07.329  7744  8105 V BtOppRfcommListener: Started RFCOMM listener....
09-13 00:07:07.330  7744  8105 I BtOppRfcommListener: Accept thread started.
09-13 00:07:07.330  7744  8105 V BtOppRfcommListener: Accepting connection...
09-13 00:07:07.330  7744  8103 V BluetoothOppNotification: update too frequent, put in queue
09-13 00:07:07.331  7744  8104 V BluetoothOppNotification: outbound notification was removed.
09-13 00:07:07.331  7744  8103 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 00:07:07.331  7744  8104 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 00:07:07.332  7744  8104 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1826b198 on behalf of 
09-13 00:07:07.333  7744  8104 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 00:07:07.333  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
09-13 00:07:07.334  7744  7744 V BluetoothFtpService: Ftp Service onCreate
09-13 00:07:07.334  7744  7744 I BluetoothFtpService: Ftp Service onCreate
09-13 00:07:07.334  7744  7744 V BluetoothFtpService: Ftp Service onStartCommand
09-13 00:07:07.334  7744  7744 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.334  7744  7744 V BluetoothFtpService: Starting Listening on sockets
09-13 00:07:07.334  7744  7744 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 00:07:07.334  7744  7744 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 00:07:07.334  7744  7744 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 00:07:07.334  7744  7744 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.334  7744  7744 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 00:07:07.334  7744  7744 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-13 00:07:07.337  7744  7744 V BluetoothFtpService: Handler(): got msg=1
09-13 00:07:07.337  7744  8104 V BluetoothOppNotification: inbound notification was removed.
09-13 00:07:07.337  7744  8104 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 00:07:07.339  7744  7744 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 00:07:07.339  7744  7744 V BluetoothFtpService: Ftp Service initSocket
09-13 00:07:07.341  7744  8104 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14c05dd6 on behalf of 
09-13 00:07:07.343  1033  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:07.344  7744  7744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:07:07.345  7744  7744 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-13 00:07:07.345  7744  7744 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 00:07:07.347  7744  8106 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-13 00:07:07.373  7744  7744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@62d8b33
,09-13 00:07:07.374  7744  7744 V BluetoothSapService: Sap Service onCreate
09-13 00:07:07.376  7744  7744 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:07:07.376  7744  7744 V BluetoothSapService: state: 12
09-13 00:07:07.376  7744  7744 V BluetoothSapService: Starting SAP server process
09-13 00:07:07.377  7744  7744 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 00:07:07.366  8107  8107 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:07.366  8107  8107 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:07.379  7744  8108 V BluetoothSapService: Sap Service initRfcommSocket
09-13 00:07:07.380  1033  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:07.381  7744  8108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:07:07.382  7744  8108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-13 00:07:07.382  7744  8108 V BluetoothSapService: Succeed to create listening socket 
09-13 00:07:07.382  7744  8108 V BluetoothSapService: Accepting socket connection...
09-13 00:07:07.399  8107  8107 V BT_SAP  : Event pipe created
09-13 00:07:07.399  8107  8107 V BT_SAP  : create_server_socket qcom.sap.server
09-13 00:07:07.399  8107  8107 V BT_SAP  : created socket fd 6
,09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:07:07.763  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:07:07.771  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:07:07.775  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:07.775  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f37e2e4 added. We now have 8 listener(s)
09-13 00:07:07.775  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:07.779  1033  1049 D WifiServiceImplEx: setWifiEnabled: false pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 00:07:07.779  1033  1049 D WifiService: setWifiEnabled: false pid=6853, uid=10118
09-13 00:07:07.779  1033  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 00:07:07.787  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:07.788  1033  2006 D WifiServiceImplEx: setWifiEnabled: true pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 00:07:07.788  1033  2006 D WifiService: setWifiEnabled: true pid=6853, uid=10118
09-13 00:07:07.788  1033  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 00:07:07.800  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 00:07:07.800  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 00:07:07.800  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-13 00:07:07.801  1033  1389 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 00:07:07.801  1033  1389 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 00:07:07.802  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 00:07:07.802  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 00:07:07.803  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 00:07:07.803  1033  1389 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 00:07:07.803  1033  1389 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 00:07:07.803  1033  1389 E WifiHW  : unknown target_country: EU , set to default
09-13 00:07:07.803  1033  1389 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 00:07:07.803  1033  1389 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 00:07:07.803  1033  1389 I WifiUtil: gEnableBmps=1
,09-13 00:07:08.247  7858  7869 E UEI.SmartControl: file observer is disposed!
,09-13 00:07:08.319  7744  7744 V BluetoothOppNotification: new notify threadi!
,09-13 00:07:08.319  7744  7744 V BluetoothOppNotification: send delay message
,09-13 00:07:08.332  7744  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-13 00:07:08.335  7744  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cbc8162 on behalf of 
,09-13 00:07:08.340  7744  8127 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-13 00:07:08.348  7744  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 00:07:08.350  7744  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f7b22f3 on behalf of 
09-13 00:07:08.350  7744  8127 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 00:07:08.353  7744  8127 V BluetoothOppNotification: outbound notification was removed.
09-13 00:07:08.354  7744  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 00:07:08.355  7744  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17061bb0 on behalf of 
09-13 00:07:08.359  7744  8127 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-13 00:07:08.415   308   889 D SoftapController: Softap fwReload - Ok
,09-13 00:07:08.419  1033  1389 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (611ms)
09-13 00:07:08.425  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:07:08.425  1033  1109 D Tethering: InitialState.processMessage what=4
09-13 00:07:08.425  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:07:08.437   308   889 D CommandListener: Setting iface cfg
09-13 00:07:08.437   308   889 D CommandListener: Trying to bring down wlan0
,09-13 00:07:08.441   308   889 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:07:08.443  1033  1389 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 00:07:08.436  8129  8129 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 00:07:08.460  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:07:08.460  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:07:08.460  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 00:07:08.446  8129  8129 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:08.513  8129  8129 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 00:07:08.531  1033  1389 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 00:07:08.531  1033  1389 D WifiMonitor: connecting to supplicant
09-13 00:07:08.535  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:07:08.536  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 00:07:08.543  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:08.543  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 00:07:08.544  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 00:07:08.544  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 00:07:08.544  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 00:07:08.545  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 00:07:08.546  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 00:07:08.549  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 00:07:08.549  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 00:07:08.549  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 00:07:08.549  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 00:07:08.549  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 00:07:08.549  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 00:07:08.554  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 00:07:08.554  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 00:07:08.554  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 00:07:08.554  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 00:07:08.554  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 00:07:08.555  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 00:07:08.555  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 00:07:08.558  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 00:07:08.558  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 00:07:08.559  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 00:07:08.559  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 00:07:08.562  7744  8127 V BluetoothOppNotification: inbound notification was removed.
09-13 00:07:08.562  7744  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-13 00:07:08.568  8129  8129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 00:07:08.568  8129  8129 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 00:07:08.568  7744  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4299a29 on behalf of 
09-13 00:07:08.604  1033  2030 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8145 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 00:07:08.635  8129  8129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 00:07:08.699  8129  8129 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 00:07:08.710  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 00:07:08.712  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 00:07:08.712  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 00:07:08.713  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 00:07:08.713  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 00:07:08.713  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 00:07:08.713  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 00:07:08.713  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 00:07:08.713  1033  1389 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,09-13 00:07:08.714  1033  1389 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:08.714  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:08.714  1033  1389 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 00:07:08.714  1033  1389 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 00:07:08.715  1033  1389 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 00:07:08.715  1033  1389 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 00:07:08.715  1033  1389 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 00:07:08.734  1033  1988 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8169 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 00:07:08.736  1033  1389 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 00:07:08.736  1033  1389 E WifiStateMachine: useWiFiOffloading() : false
09-13 00:07:08.736  1033  1389 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 00:07:08.737  1033  1389 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 00:07:08.737  1033  1389 D WifiNative-wlan0: SET update_config 1: returned true
09-13 00:07:08.737  1033  1389 D WifiConfigStore: Loading config and enabling all networks 
09-13 00:07:08.737  1033  1389 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 00:07:08.737  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.737  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.738  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.738  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.738  1033  1389 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 00:07:08.738  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 00:07:08.739  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 00:07:08.739  1940  1940 D WfdService: Waiting for WifiP2p enabling
09-13 00:07:08.739  1033  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 00:07:08.740  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:07:08.743  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:07:08.743  1033  1389 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 00:07:08.744  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:07:08.748  8145  8165 W FormManager: Network not available. Please check & try again.
,09-13 00:07:08.752  1033  1389 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 00:07:08.752  1033  1389 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 00:07:08.753  1033  1389 D WifiStateMachine: enableVerboseLogging : level 2
09-13 00:07:08.753  1033  1389 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 00:07:08.753  1033  1389 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 00:07:08.753  1033  1389 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 00:07:08.754  1033  1389 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 00:07:08.754  1033  1389 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 00:07:08.754  1033  1389 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 00:07:08.754  1033  1389 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 00:07:08.755  8145  8167 V FormManager: Network unavailable.
09-13 00:07:08.755  1033  1389 D WifiNative-wlan0: SET model_number LG-D855: returned true
,09-13 00:07:08.755  1033  1389 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 00:07:08.755  1033  1389 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 00:07:08.755  1033  1389 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 00:07:08.756  1033  1389 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 00:07:08.756  1033  1389 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 00:07:08.756  1033  1389 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 00:07:08.757  1033  1389 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 00:07:08.757  1033  1389 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 00:07:08.757  1033  1389 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 00:07:08.757  1033  1389 D WifiNative-HAL: Setting external_sim to 1
09-13 00:07:08.757  1033  1389 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 00:07:08.758  1940  1940 D WfdsService: Supplicant Connection state is changed : true
09-13 00:07:08.758  1033  1389 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 00:07:08.758  1033  1389 I WifiNative-HAL: startHal
,09-13 00:07:08.758  1033  1389 D wifi    : setting scan oui 0xaf6cc5c0
09-13 00:07:08.759  1033  1389 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 00:07:08.759  1033  1389 I WifiNative-HAL: startHal
09-13 00:07:08.759  1940  2252 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 00:07:08.759  7802  7802 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.759  1940  2252 D WfdsService: Set the WFDS Monitor: true
09-13 00:07:08.759  1033  1389 D wifi    : setting scan oui 0xaf6cc5c0
09-13 00:07:08.759  1940  2252 D WfdsMonitor: WfdsMonitorThread create
09-13 00:07:08.759  1033  1389 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 00:07:08.759  1940  2252 D WfdsMonitor: WFDS Monitor is created and started
09-13 00:07:08.759  1940  2252 D WfdsService: WiFi: Supplicant connection re-established
09-13 00:07:08.759  1033  1389 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 00:07:08.759  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 00:07:08.760  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 00:07:08.760  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 00:07:08.760  1940  8187 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 00:07:08.760  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 00:07:08.760  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 00:07:08.760  1940  8187 E CtrlSupplicant: Succeed to open control connection
09-13 00:07:08.761  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 00:07:08.761  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 00:07:08.761  1940  8187 E CtrlSupplicant: Succeed to open monitor connection
09-13 00:07:08.761  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 00:07:08.761  1940  8187 D WfdsMonitor: Supplicant connection established
09-13 00:07:08.761  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 00:07:08.761  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 00:07:08.761  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 00:07:08.762  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 00:07:08.762  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 00:07:08.762  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 00:07:08.762  1940  2252 D WfdsService: Connected to the supplicant for wfds
09-13 00:07:08.762  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 00:07:08.762  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 00:07:08.762  8129  8129 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 00:07:08.763  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 00:07:08.763  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 00:07:08.763  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 00:07:08.763  1033  1389 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 00:07:08.764  1033  1389 E WifiNative: : [200,763,061 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 00:07:08.764  1033  1389 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 00:07:08.764  1033  1389 D WifiNative-wlan0: RECONNECT: returned true
09-13 00:07:08.765  1033  1389 D WifiNative-wlan0: doString: [STATUS]
09-13 00:07:08.765  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 00:07:08.765  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-13 00:07:08.766  1033  1389 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 00:07:08.766  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:07:08.766  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
09-13 00:07:08.767  1033  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.767  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 00:07:08.767  1033  1033 D RttService: SCAN_AVAILABLE : 3
09-13 00:07:08.768  1033  1554 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.768  1033  1553 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.768  1033  1389 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 00:07:08.768  1033  1553 I WifiNative-HAL: startHal
09-13 00:07:08.768  1033  1553 D wifi    : getting scan capabilities on interface[1] = 0xaf6cc5c0
09-13 00:07:08.768  1033  1553 D wifi    : failed to get capabilities : -3
09-13 00:07:08.768  1033  1553 E WifiScanningService: could not get scan capabilities
09-13 00:07:08.768  1033  1389 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 00:07:08.768  1033  1389 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 00:07:08.769  1033  1389 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 00:07:08.769   308   889 D CommandListener: Setting iface cfg
09-13 00:07:08.769   308   889 D CommandListener: Trying to bring up p2p0
09-13 00:07:08.769  1033  1389 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 00:07:08.769  1033  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 00:07:08.769  1033  1388 D LGWifiP2pService: P2pEnablingState
09-13 00:07:08.770  1033  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.770  1033  1388 D LGWifiP2pService: P2p socket connection successful
09-13 00:07:08.770  1033  1388 D LGWifiP2pService: P2pEnabledState
09-13 00:07:08.770  1033  1389 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 00:07:08.770  1033  1389 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 00:07:08.770  1033  1389 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 00:07:08.770  8129  8129 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 00:07:08.771  1033  1388 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 00:07:08.771  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 00:07:08.771  1940  1940 D WfdsService: WifiP2pState is changed : true
09-13 00:07:08.772  1940  2252 D WfdsService: Receive the WFDS_ENABLE Method
09-13 00:07:08.772  1940  2252 D WfdsService: Set the WFDS Monitor: true
09-13 00:07:08.772  1940  2252 D WfdsService: Connected to the supplicant for wfds
09-13 00:07:08.772  1940  2252 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 00:07:08.772  8129  8129 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 00:07:08.772  1940  2252 D WfdsService: selectPreferredScanChannel [36]
09-13 00:07:08.772  1940  2252 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 00:07:08.772  8145  8167 V FormManager: Network unavailable.
09-13 00:07:08.772  1033  1389 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 00:07:08.773  1033  1389 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 00:07:08.774  1033  1389 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 00:07:08.774  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 00:07:08.774  1033  1389 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 00:07:08.774  8129  8129 E wpa_supplicant: disconnect_rssi_lvl: ,-100
09-13 00:07:08.775  1033  1389 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 00:07:08.775  1940  1940 D WfdsService: isConnected: false
09-13 00:07:08.775  1033  1389 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 00:07:08.776  1033  1389 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 00:07:08.776  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 00:07:08.776  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 00:07:08.776  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.776  1033  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 00:07:08.777  8129  8129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 00:07:08.777  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.778  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.779  1940  8187 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.779  1033  1389 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 00:07:08.779  1940  8187 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.779  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 00:07:08.779  1033  1389 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 00:07:08.779  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.779  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.779  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.779  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.780  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.780  1033  1389 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 00:07:08.780  1033  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 00:07:08.780  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.780  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.780  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.780  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.780  1033  1389 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 00:07:08.780  1033  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 00:07:08.780  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.780  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 00:07:08.780  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.780  1033  1388 D WifiNative-p2p0: SET device_name G3: returned true
09-13 00:07:08.780  1033  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 00:07:08.780  1033  1388 D LGWifiP2pService: before postfix = G3
09-13 00:07:08.780  1033  1388 D WifiServerServiceExt: postfix byte check : 2
09-13 00:07:08.780  1033  1388 D LGWifiP2pService: after postfix = G3
09-13 00:07:08.780  1033  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 00:07:08.781  1033  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 00:07:08.781  1033  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 00:07:08.781  1033  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 00:07:08.781  1033  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 00:07:08.782  1033  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 00:07:08.782  1033  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 00:07:08.782  1033  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 00:07:08.782  1033  1388 D WifiNative-HAL: p2pGetDeviceAddress
09-13 00:07:08.782  1033  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 00:07:08.783  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 00:07:08.783  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:07:08.783  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 00:07:08.783  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:07:08.784  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:07:08.784  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 00:07:08.784  1033  1389 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 00:07:08.784  1033  1389 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 00:07:08.784  1033  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 00:07:08.784  1033  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 00:07:08.784  1033  1389 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 00:07:08.784  1033  1389 D WifiNative-wlan0: doBoolean: SCAN
09-13 00:07:08.785  1033  1389 D WifiNative-wlan0: SCAN: returned false
09-13 00:07:08.785  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200784  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 00:07:08.787  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 00:07:08.787  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 00:07:08.787  1940  1940 D WfdsService: Update P2p Interface State: 3
09-13 00:07:08.790  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:08.790  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:08.790  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200790  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 00:07:08.791  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.791  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:08.791  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 00:07:08.791  1033  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 00:07:08.791  1033  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 00:07:08.792  1033  1389 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:07:08.792  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:08.792  1033  1389 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:07:08.792  1033  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 00:07:08.792  1033  1389 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:07:08.792  1033  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 00:07:08.793  1033  1389 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:07:08.793  1033  1389 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 00:07:08.793  1033  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 00:07:08.793  1033  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 00:07:08.794  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:08.794  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 00:07:08.795  1033  1572 I ActivityManager: Killing 7262:com.android.chrome/u0a57 (adj 15): empty #17
09-13 00:07:08.798  8169  8169 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:07:08.803  1033  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 00:07:08.803  1033  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:07:08.814  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:07:08.816  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:07:08.820  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 00:07:08.821  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 00:07:08.823  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2f605c6 Bundle[{}]
09-13 00:07:08.824  6853  6931 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 00:07:08.824  6853  6931 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 00:07:08.824  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 00:07:08.825  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 00:07:08.826  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 00:07:08.827  6853  6931 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 00:07:08.832  6853  6931 I System.out: Running OutgoingSocketThread
09-13 00:07:08.833  6853  8191 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 902)
09-13 00:07:08.834  6853  8191 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37164
09-13 00:07:08.834  6853  8191 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 00:07:08.837  1033  1388 D LGWifiP2pService: InactiveState
09-13 00:07:08.837  1033  1050 W libprocessgroup: failed to open /acct/uid_10057/pid_7262/cgroup.procs: No such file or directory
,09-13 00:07:08.837  1033  1388 D LGWifiP2pService: InactiveState{ when=-58ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.838  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-58ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.838  1033  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 00:07:08.840  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 00:07:08.840  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.841  1940  8187 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 00:07:08.841  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 00:07:08.841  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.841  8129  8129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 00:07:08.841  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 00:07:08.841  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.841  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.841  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 00:07:08.841  1033  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: InactiveState{ when=-49ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-49ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.842  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1940  8187 D Wf,dsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1033  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:08.842  1940  8187 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.842  1033  1033 E WifiServerServiceExt: No p2p device connected
09-13 00:07:08.842  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 00:07:08.843  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.843  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.843  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 00:07:08.843  1940  2252 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 00:07:08.845  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:08.846  1033  1939 I ActivityManager: Killing 7287:com.lge.drmservice/u0a62 (adj 15): empty #17
09-13 00:07:08.888  1033  1049 W libprocessgroup: failed to open /acct/uid_10062/pid_7287/cgroup.procs: No such file or directory
,09-13 00:07:08.921  8169  8169 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 00:07:08.928  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:07:08.932  8145  8193 W FormManager: Network not available. Please check & try again.
09-13 00:07:08.935  8145  8194 V FormManager: Network unavailable.
,09-13 00:07:08.939  8145  8194 V FormManager: Network unavailable.
09-13 00:07:08.941  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:08.971  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 00:07:08.972  4793  4793 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 00:07:08.974  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 00:07:08.978  4793  4793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 00:07:08.982  4793  8195 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 00:07:08.985  4793  8196 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-13 00:07:08.986  4793  8196 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 00:07:09.060  1033  1572 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8197 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 00:07:09.195  8197  8197 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 00:07:09.196  8197  8197 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 00:07:09.208  8197  8197 V [BNRBootReceiver]: Boot Receiver Return
09-13 00:07:09.209  8197  8197 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-13 00:07:09.277  1033  1782 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 00:07:09.278  1033  1782 I ActivityManager: Killing 7315:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-13 00:07:09.337  1033  1050 W libprocessgroup: failed to open /acct/uid_10085/pid_7315/cgroup.procs: No such file or directory
,09-13 00:07:09.362  8218  8218 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 00:07:09.385  8218  8218 D PluginManager: init()
,09-13 00:07:09.399  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 00:07:09.399  1033  8168 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 00:07:09.400  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 00:07:09.400  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-13 00:07:09.400  1033  8168 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-13 00:07:09.400  8129  8129 E wpa_supplicant: USIM:  scard_init function
,09-13 00:07:09.401  8129  8129 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 00:07:09.403  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 00:07:09.403  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 00:07:09.403  1033  1389 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-13 00:07:09.404  1033  1389 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-13 00:07:09.405  1033  1389 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-13 00:07:09.405  1033  1389 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-13 00:07:09.405  1033  1389 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 00:07:09.420  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=201419  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 00:07:09.422  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.422  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:09.425  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.425  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.425  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.425  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 00:07:09.430  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.430  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.430  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 00:07:09.431  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=201430  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 00:07:09.432  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:09.432  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 00:07:09.446  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.446  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:09.447  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:07:09.496  7858  7978 D UEI.SmartControl: Internal timer expired: 3
09-13 00:07:09.497  7858  7978 D UEI.SmartControl: unbind internal service
09-13 00:07:09.502  7858  7858 D UEI.SmartControl: Service.onUnbind: IControl
09-13 00:07:09.503  7858  7858 D UEI.SmartControl: Service.onDestroy
09-13 00:07:09.503  7858  7858 D UEI.SmartControl: Lock is in USE false
09-13 00:07:09.503  7858  7858 D UEI.SmartControl: unbind internal service
09-13 00:07:09.504  7858  7858 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2d452dab
09-13 00:07:09.504  7858  7858 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-13 00:07:09.505  7858  7858 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-13 00:07:09.505  7858  7858 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-13 00:07:09.505  7858  7858 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-13 00:07:09.505  7858  7858 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-13 00:07:09.505  7858  7858 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-13 00:07:09.505  7858  7858 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-13 00:07:09.505  7858  7858 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-13 00:07:09.505  7858  7858 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:09.506  7858  7858 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:09.506  7858  7858 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:09.506  7858  7858 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:09.506  7858  7858 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:07:09.506  7858  7858 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:09.506  7858  7858 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 00:07:09.506  7858  7858 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2d452dab
,09-13 00:07:09.516  8129  8129 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 00:07:09.517  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 00:07:09.517  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 00:07:09.517  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 00:07:09.518  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 00:07:09.518  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=201517  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 00:07:09.518  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:07:09.518  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:07:09.518  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=201518  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 00:07:09.521  1033  1389 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201520
09-13 00:07:09.521  1033  1389 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201521
09-13 00:07:09.522  1033  1389 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201521
09-13 00:07:09.522  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201521
09-13 00:07:09.523  1033  1389 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=201522
09-13 00:07:09.523  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=201522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 00:07:09.529  7858  7858 D serial_port: close(fd = 24)
,09-13 00:07:09.533  8129  8129 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 00:07:09.533  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 00:07:09.536  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:07:09.537  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:07:09.537  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 00:07:09.537  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 00:07:09.537  1033  8168 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 00:07:09.537  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 00:07:09.537  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 00:07:09.537  1033  8168 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 00:07:09.537  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:07:09.538  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:07:09.538  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 00:07:09.543  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=201542  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 00:07:09.545  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.545  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.545  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 00:07:09.546  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.546  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.546  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 00:07:09.548  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.548  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 00:07:09.551  7858  7858 I UEI.SmartControl: Serial port is closed.
09-13 00:07:09.552  1033  1389 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=201551  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 00:07:09.553  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=201552  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 00:07:09.553  1033  1389 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=201553
09-13 00:07:09.553  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:09.553  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 00:07:09.554  1033  1389 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=201553
09-13 00:07:09.554  1033  1389 D WifiNative-wlan0: doString: [STATUS]
09-13 00:07:09.555  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.555  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 00:07:09.555  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 00:07:09.554  7858  7858 I UEI.SmartControl: Serial port is closed.
09-13 00:07:09.555  7858  7858 D UEI.SmartControl: Blaster closed
09-13 00:07:09.555  7858  7858 D UEI.SmartControl: Shut down QS...
09-13 00:07:09.555  7858  7858 D UEI.SmartControl: Stopping QS lib
09-13 00:07:09.555  7858  7858 D UEI.SmartControl: QS lib stop result = true
09-13 00:07:09.555  7858  7858 D UEI.SmartControl: Stopped QS lib
09-13 00:07:09.555  7858  7858 D UEI.SmartControl: QS shutdown complete
09-13 00:07:09.556  1033  1389 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 00:07:09.558  1033  1389 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 00:07:09.559  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.559  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:09.560  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.565  1033  1389 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 00:07:09.565  1033  1389 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 00:07:09.571  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.571  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.571  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 00:07:09.574  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.574  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.574  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 00:07:09.575  1033  1389 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 00:07:09.575  1033  1440 D ConnectivityService: Got NetworkAgent Messenger
09-13 00:07:09.575  1033  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:07:09.575  1033  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 00:07:09.575  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 00:07:09.575  1033  1440 D ConnectivityService: NetworkAgent connected
09-13 00:07:09.576  1033  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 00:07:09.576  1033  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 00:07:09.578  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.578  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 00:07:09.580  1033  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 00:07:09.580  1033  1389 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:07:09.580  1033  1389 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 00:07:09.580  1033  1389 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 00:07:09.580  1033  1389 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 00:07:09.581  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.583  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.583  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:09.585  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.585  1033  1389 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 00:07:09.587   308   889 D CommandListener: Setting iface cfg
09-13 00:07:09.590  1033  1389 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 00:07:09.590  1033  8241 D DhcpStateMachine: StoppedState
09-13 00:07:09.590  1033  8241 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.590  1033  8241 D DhcpStateMachine: WaitBeforeStartState
09-13 00:07:09.591  1033  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=201590  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:07:09.591  1033  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=201590  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 00:07:09.591  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=201591  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:07:09.592  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:09.592  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:09.592  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 00:07:09.593  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:09.593  1033  1389 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:09.593  1033  1389 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:09.594  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:09.594  1033  1389 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 00:07:09.595  1033  1389 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=201594  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:07:09.595  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:09.595  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 00:07:09.595  1033  1389 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=201594  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:07:09.595  1033  1389 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=201595  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 00:07:09.597  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14377] from screen [on:0 period:544247069] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 00:07:09.598  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:544247070] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 00:07:09.598  1033  1389 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 00:07:09.602  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:07:09.602  1033  1440 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-13 00:07:09.602  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.603  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.603  1033  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.603  1033  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.604  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.604  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.605  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 00:07:09.605  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
09-13 00:07:09.605  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
09-13 00:07:09.605  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 00:07:09.606  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 00:07:09.606  1033  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 00:07:09.606  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 00:07:09.606  1033  1389 D WifiNative-wlan0: SET ps 0: returned true
09-13 00:07:09.607  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 00:07:09.607  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 00:07:09.607  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 00:07:09.607  1033  1389 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 00:07:09.607  1033  1389 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 00:07:09.607  1033  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d7e28e target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.607  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d7e28e target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.607  1033  1389 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 00:07:09.608  1033  8241 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.608  1033  8241 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 00:07:09.609   308   889 D CommandListener: Setting iface cfg
09-13 00:07:09.609   308   889 D CommandListener: Trying to bring up wlan0
09-13 00:07:09.610  1033  1389 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 00:07:09.610  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:09.610  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 00:07:09.611  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 00:07:09.611  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 00:07:09.612  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.612  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.613  1033  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 00:07:09.613  1033  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.614  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.614  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 00:07:09.615  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 00:07:09.615  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 00:07:09.616  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 00:07:09.616  1033  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.616  1033  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.617  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 00:07:09.617  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 00:07:09.617  1033  1389 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 00:07:09.617  1033  1389 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 00:07:09.617  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 00:07:09.618  1033  1389 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 00:07:09.618  1033  1389 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 00:07:09.633  1033  1389 D WifiNative-wlan0: SET ps 1: returned true
,09-13 00:07:09.635  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 00:07:09.635  1033  1389 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 00:07:09.635  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 00:07:09.635  1033  1389 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 00:07:09.636  1033  1440 D ConnectivityService: ignoring duplicate network state non-change
09-13 00:07:09.640  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.640  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:09.642  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.643  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.643  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.643  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 00:07:09.644  1033  1440 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 00:07:09.644  1033  1440 D ConnectivityService: Adding iface wlan0 to network 102
09-13 00:07:09.650  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.650  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.650  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 00:07:09.652  1033  1389 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 00:07:09.654  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 00:07:09.657  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 00:07:09.659  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.659  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.659  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 00:07:09.660  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 00:07:09.661  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.661  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 00:07:09.662  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:07:09.667  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.667  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:07:09.668  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 00:07:09.668  1033  1440 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 00:07:09.668  1033  1440 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 00:07:09.669  1033  1440 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 00:07:09.669  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.669  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 00:07:09.669   308   889 E Netd    : netlink response contains error (File exists)
09-13 00:07:09.669  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.670  1033  1440 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 00:07:09.670  1033  1440 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 00:07:09.670  1033  1440 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 00:07:09.670  1033  1440 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 00:07:09.675  1033  1440 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 00:07:09.675  1033  1440 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.675  1033  1440 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.675  1033  1440 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.675  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.675  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 00:07:09.675  1033  1440 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:07:09.675  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:07:09.675  1033  1440 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:09.675  1033  1440 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 00:07:09.675  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 00:07:09.675  1033  1440 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.676  1033  1440 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 00:07:09.676  1033  1440 D ConnectivityService: currentScore = 0, newScore = 20
09-13 00:07:09.676  1033  1440 D ConnectivityService:    accepting network in place of null
09-13 00:07:09.676  1033  1440 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.676  1850  1,850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 00:07:09.677  1033  1389 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.677  1033  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:07:09.677  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 00:07:09.677   308  8246 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 00:07:09.678  1033  1440 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 00:07:09.678  1033  1440 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 00:07:09.678  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:07:09.680  1033  1440 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:07:09.680  1033  1440 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 00:07:09.681  1033  1440 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 00:07:09.681  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 00:07:09.684  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 00:07:09.684  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 00:07:09.684  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 00:07:09.684  1033  1440 D ConnectivityService: validation of new default Network = false
09-13 00:07:09.684  1033  1440 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 00:07:09.684  1033  1440 D DSQN    : enableDataServiceNotify 
09-13 00:07:09.684  1033  1440 D DSQN    : start dsqn bin
09-13 00:07:09.685  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:07:09.685  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 00:07:09.686  1601  1601 D StatusBar.NetworkCont,roller: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.689  1033  1440 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.689  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.689  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:09.689  1033  1440 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:09.689  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 00:07:09.676  8247  8247 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 00:07:09.676  8247  8247 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:09.694  1033  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 00:07:09.703  8247  8247 E DSQN    : DSQN ssw
,09-13 00:07:09.704  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 00:07:09.704  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.705  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:07:09.732   308  8246 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 00:07:09.764   308  8246 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 00:07:09.790   308   888 D LGDataListener: argv[0]=dsqncommand
09-13 00:07:09.790   308   888 D LGDataListener: argv[1]=wlan0
09-13 00:07:09.790   308   888 D LGDataListener: argv[2]=1
09-13 00:07:09.790   308   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 00:07:09.791  1033  1107 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 00:07:09.791  1033  1107 D DSQN    : start to monitor internet connection
,09-13 00:07:09.810  1033  8241 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 00:07:09.812  1033  8241 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 00:07:09.812  1033  8241 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-13 00:07:09.815  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 22:07:09 GMT], X-Android-Received-Millis=[1473718029815], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473718029789]}
09-13 00:07:09.815  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 00:07:09.816  1033  8239 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 00:07:09.816  1033  1440 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.816  1033  1440 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.806  8253  8253 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:09.806  8253  8253 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 00:07:09.816  1033  1440 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:07:09.817  1033  1440 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:09.817  1033  1440 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 00:07:09.817  1033  1440 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 00:07:09.817  1033  1440 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 00:07:09.817  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.818  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:09.819  1033  1440 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:09.820  1033  1440 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.820  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 00:07:09.823  1033  1389 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.823  1033  1389 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:07:09.828  1033  1440 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 00:07:09.828  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:09.828  8253  8253 I dhcpcd  : version 5.5.6 starting
09-13 00:07:09.829  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-13 00:07:09.830  8253  8253 E dhcpcd  : get_duid: m
09-13 00:07:09.830  8253  8253 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 00:07:09.830  8253  8253 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 00:07:09.836  6853  6931 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 903)
09-13 00:07:09.838  6853  6931 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 903)
09-13 00:07:09.848  6853  6931 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 908)
09-13 00:07:09.849  6853  6931 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 00:07:09.849  6853  6931 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 909)
09-13 00:07:09.853  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.853  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245434d added. We now have 2 listener(s)
,09-13 00:07:09.855  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.859  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.859  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.859  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.859  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.859  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c8d4e02 added. We now have 9 listener(s)
09-13 00:07:09.859  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:07:09.860  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:07:09.865  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 00:07:09.865  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 00:07:09.866  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.868  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:07:09.871  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:07:09.872  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.872  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:07:09.873  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.873  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c024950 added. We now have 3 listener(s)
09-13 00:07:09.873  1033  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.874  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.876  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.876  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.876  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.876  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.877  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.877  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32fc749 added. We now have 10 listener(s)
09-13 00:07:09.877  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.877  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:07:09.877  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:07:09.877  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:07:09.877  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.877  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.878  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.878  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.878  6853  6931 V org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245434d removed from the list
09-13 00:07:09.878  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.878  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c8d4e02 removed from the list
09-13 00:07:09.878  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:07:09.878  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.878  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.878  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:07:09.880  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.880  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.880  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.880  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c8d4e02 not in the list
09-13 00:07:09.880  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.880  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.881  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.881  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.881  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.881  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32fc749 removed from the list
09-13 00:07:09.881  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.882  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.882  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.882  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.882  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c024950 removed from the list
09-13 00:07:09.882  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.882  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1586484e added. We now have 2 listener(s)
09-13 00:07:09.883  1033  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.885  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.885  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.885  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.885  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.885  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e88bd6f added. We now have 9 listener(s)
09-13 00:07:09.886  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.886  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:07:09.889  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:07:09.892  6853  6931 V io.jxcore.node.C,onnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:07:09.892  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:07:09.894  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.894  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:07:09.895  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.895  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a248f05 added. We now have 3 listener(s)
09-13 00:07:09.896  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.897  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.898  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.898  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.898  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.898  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.898  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18029b5a added. We now have 10 listener(s)
09-13 00:07:09.898  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.898  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:07:09.898  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:07:09.898  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:07:09.898  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.898  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:07:09.900  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.901  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:07:09.901  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.906  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:07:09.907  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:07:09.909  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:07:09.909  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.911  6853  6931 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 00:07:09.911  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:07:09.911  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:07:09.913  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:07:09.913  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:07:09.913  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:07:09.913  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.913  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.913  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.913  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.914  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1586484e removed from the list
09-13 00:07:09.914  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.914  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e88bd6f removed from the list
09-13 00:07:09.914  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:07:09.914  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.914  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.914  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.915  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.915  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.915  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.915  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e88bd6f not in the list
09-13 00:07:09.915  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.915  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.916  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.917  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:07:09.917  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stoppe,d
09-13 00:07:09.917  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.917  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.917  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18029b5a removed from the list
09-13 00:07:09.917  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.917  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.917  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.917  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.917  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a248f05 removed from the list
09-13 00:07:09.917  8253  8253 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 00:07:09.917  8253  8253 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 00:07:09.917  8253  8253 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 00:07:09.918  8253  8253 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 00:07:09.918  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.918  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25e41681 added. We now have 2 listener(s)
09-13 00:07:09.918  8253  8253 D dhcpcd  : wlan0: sending REQUEST (xid 0xd4338736), next in 4.87 seconds
09-13 00:07:09.918  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.920  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.920  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.920  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.920  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.920  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bf1326 added. We now have 9 listener(s)
09-13 00:07:09.920  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.921  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:07:09.922  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:07:09.925  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:07:09.927  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.927  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:07:09.927  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.927  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecbcd14 added. We now have 3 listener(s)
09-13 00:07:09.928  1033  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.929  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.931  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.931  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.931  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.931  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.931  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.932  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ba99bd added. We now have 10 listener(s)
09-13 00:07:09.932  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.932  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:07:09.932  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:07:09.932  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:07:09.932  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:07:09.932  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.932  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:07:09.935  6853  6931 V, org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:07:09.935  1033  1903 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 00:07:09.936  8253  8253 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-13 00:07:09.940  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:07:09.940  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 00:07:09.942  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:07:09.942  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:07:09.944  6853  6931 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 00:07:09.944  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:07:09.944  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:07:09.944  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:07:09.944  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.944  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.944  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.944  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.944  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25e41681 removed from the list
09-13 00:07:09.944  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.944  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bf1326 removed from the list
09-13 00:07:09.944  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:07:09.945  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.945  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.945  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.946  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.946  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.946  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.946  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bf1326 not in the list
09-13 00:07:09.946  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.946  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.947  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.947  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:07:09.947  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 00:07:09.948  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.948  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.948  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ba99bd removed from the list
09-13 00:07:09.948  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.948  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.948  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.948  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:07:09.948  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecbcd14 removed from the list
09-13 00:07:09.948  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.948  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3322a680 added. We now have 2 listener(s)
09-13 00:07:09.949  1033  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.951  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.951  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.951  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.951  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.951  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b7c14b9 added. We now have 9 listener(s)
09-13 00:07:09.951  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.951  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:07:09.955  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.956  8253  8253 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 00:07:09.956  8253  8253 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 00:07:09.956  8253  8253 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 00:07:09.956  8253  8253 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 00:07:09.956  8253  8253 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 00:07:09.957  8253  8253 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 00:07:09.957  8253  8253 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 00:07:09.957  8253  8253 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:07:09.958  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:07:09.959  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.959  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:07:09.959  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already ,loaded
09-13 00:07:09.959  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d49e05f added. We now have 3 listener(s)
09-13 00:07:09.960  1033  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.961  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.962  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.963  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.963  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.963  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.963  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.963  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@134baaac added. We now have 10 listener(s)
09-13 00:07:09.963  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.963  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:07:09.963  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:07:09.963  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:07:09.963  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.963  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 00:07:09.967  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:07:09.968  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.971  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:07:09.972  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 00:07:09.973  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:07:09.973  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.974  6853  6931 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 00:07:09.976  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:07:09.976  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:07:09.976  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:07:09.976  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.976  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.976  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.976  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.976  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3322a680 removed from the list
09-13 00:07:09.976  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:07:09.976  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b7c14b9 removed from the list
09-13 00:07:09.976  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:07:09.976  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.977  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.977  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.977  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.977  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.977  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.977  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b7c14b9 not in the list
09-13 00:07:09.977  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.977  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.978  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.978  6853  6931 D BluetoothLeScanner: could not find callback wrapper
09-13 00:07:09.978  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:07:09.978  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.978  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.979  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@134baaac removed from the list
09-13 00:07:09.979  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.979  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.979  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.979  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.979  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d49e05f removed from the list
09-13 00:07:09.979  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.979  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32d6237b added. We now have 2 listener(s)
09-13 00:07:09.980  1033  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.981  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.982  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.982  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIden,tityString: 
09-13 00:07:09.982  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.982  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@101ec598 added. We now have 9 listener(s)
09-13 00:07:09.982  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.982  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:07:09.985  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:07:09.987  6853  6931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:07:09.988  6853  6931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:07:09.988  6853  6931 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:07:09.990  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.991  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:07:09.991  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:07:09.991  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8891d6 added. We now have 3 listener(s)
09-13 00:07:09.992  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 00:07:09.993  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 00:07:09.993  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:07:09.993  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:07:09.993  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:07:09.993  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21197c57 added. We now have 10 listener(s)
09-13 00:07:09.993  6853  6931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:07:09.994  6853  6931 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:07:09.994  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-,13 00:07:09.994  6853  6931 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:07:09.994  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.994  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.994  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:07:09.994  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.994  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32d6237b removed from the list
09-13 00:07:09.995  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.995  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@101ec598 removed from the list
09-13 00:07:09.995  6853  6931 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:07:09.995  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.995  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.995  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.996  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.996  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.996  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.996  6853  6931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@101ec598 not in the list
09-13 00:07:09.996  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.996  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.997  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:07:09.997  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:07:09.997  6853  6931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:07:09.997  6853  6931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21197c57 removed from the list
09-13 00:07:09.997  6853  6931 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:07:09.997  6853  6931 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:07:09.997  6853  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:07:09.997  6853  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:07:09.997  6853  6931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8891d6 removed from the list
09-13 00:07:09.998  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 00:07:09.998  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 00:07:09.998  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 00:07:09.998  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:07:09.998  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 00:07:09.998  6853  6931 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:07:10.006  6853  8265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 916, name: My test thread name)
09-13 00:07:10.006  6853  8265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 916, thread name: My test thread name)
09-13 00:07:10.006  6853  8265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 916, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 00:07:10.010  6853  8267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 918, name: My test thread name)
09-13 00:07:10.010  6853  8267 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 918, thread name: My test thread name)
09-13 00:07:10.010  6853  8267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 918, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 00:07:10.012  6853  6931 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 00:07:10.013  6853  6931 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 00:07:10.013  6853  6931 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 00:07:10.013  6853  6931 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 00:07:10.013  6853  6931 D com.test.thalitest.ThaliTestRunner: Total duration: 22885 ms
09-13 00:07:10.014  6853  6931 I jxcore-log: *Native tests were executed*
09-13 00:07:10.014  6853  6931 I jxcore-log: 
09-13 00:07:10.014  6853  6931 I jxcore-log: Total number of executed tests:  80
09-13 00:07:10.014  6853  6931 I jxcore-log: 
09-13 00:07:10.014  6853  6931 I jxcore-log: Number of passed tests:  80
09-13 00:07:10.014  6853  6931 I jxcore-log: 
09-13 00:07:10.015  6853  6931 I jxcore-log: Number of failed tests:  0
09-13 00:07:10.015  6853  6931 I jxcore-log: 
09-13 00:07:10.015  6853  6931 I jxcore-log: Number of ignored tests:  0
09-13 00:07:10.015  6853  6931 I jxcore-log: 
09-13 00:07:10.015  6853  6931 I jxcore-log: Total duration:  22885
09-13 00:07:10.015  6853  6931 I jxcore-log: 
09-13 00:07:10.015  6853  6931 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 00:07:10.015  6853  6931 I jxcore-log: 
09-13 00:07:10.021  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.021  6853  6931 I jxcore-log: 
09-13 00:07:10.024  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.024  6853  6931 I jxcore-log: 
,09-13 00:07:10.025  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.025  6853  6931 I jxcore-log: 
09-13 00:07:10.026  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.026  6853  6931 I jxcore-log: 
09-13 00:07:10.028  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.028  6853  6931 I jxcore-log: 
09-13 00:07:10.029  6853  6853 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 00:07:10.029  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.029  6853  6931 I jxcore-log: 
09-13 00:07:10.032  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.032  6853  6931 I jxcore-log: 
09-13 00:07:10.034  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:07:10.034  6853  6931 I jxcore-log: 
09-13 00:07:10.035  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.035  6853  6931 I jxcore-log: 
09-13 00:07:10.036  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.036  6853  6931 I jxcore-log: 
09-13 00:07:10.037  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:07:10.037  6853  6931 I jxcore-log: 
09-13 00:07:10.038  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:07:10.038  6853  6931 I jxcore-log: 
,09-13 00:07:10.039  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:07:10.039  6853  6931 I jxcore-log: 
09-13 00:07:10.040  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.040  6853  6931 I jxcore-log: 
09-13 00:07:10.041  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.041  6853  6931 I jxcore-log: 
09-13 00:07:10.042  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.042  6853  6931 I jxcore-log: 
09-13 00:07:10.042  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.042  6853  6931 I jxcore-log: 
09-13 00:07:10.043  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.043  6853  6931 I jxcore-log: 
09-13 00:07:10.044  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.044  6853  6931 I jxcore-log: 
09-13 00:07:10.045  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.045  6853  6931 I jxcore-log: 
09-13 00:07:10.045  8218  8218 W ExternalStrings: load override strings
09-13 00:07:10.045  8218  8218 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:10.045  8218  8218 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 00:07:10.045  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:07:10.045  6853  6931 ,I jxcore-log: 
09-13 00:07:10.046  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:07:10.046  6853  6931 I jxcore-log: 
09-13 00:07:10.047  8218  8218 D StatusProvider: onCreate
09-13 00:07:10.047  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:07:10.047  6853  6931 I jxcore-log: 
09-13 00:07:10.048  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.048  6853  6931 I jxcore-log: 
09-13 00:07:10.049  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.049  6853  6931 I jxcore-log: 
09-13 00:07:10.050  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.050  6853  6931 I jxcore-log: 
09-13 00:07:10.051  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.051  6853  6931 I jxcore-log: 
09-13 00:07:10.052  6853  6931 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:07:10.052  6853  6931 I jxcore-log: 
09-13 00:07:10.103  8218  8218 V Signer  : override build config not found
09-13 00:07:10.103  8218  8218 D Signer  : value of property debug is false
,09-13 00:07:10.132  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-13 00:07:10.132  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-13 00:07:10.132  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-13 00:07:10.132  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-13 00:07:10.133  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-13 00:07:10.134  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-13 00:07:10.134  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-13 00:07:10.142  8218  8218 V LGMDMManager: Create singleton instance
09-13 00:07:10.180  8218  8218 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-13 00:07:10.215  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:07:10.217  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 00:07:10.221  1033  8241 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 00:07:10.224  1033  8241 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 00:07:10.224  1033  8241 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 00:07:10.224  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:07:10.224  1033  8241 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 00:07:10.225  1033  8241 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 00:07:10.225  1033  8241 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,09-13 00:07:10.225  1033  8241 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 00:07:10.225  1033  8241 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 00:07:10.225  1033  8241 D DhcpStateMachine: RunningState
,09-13 00:07:10.242  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:10.297  8278  8278 D AndroidRuntime: 
09-13 00:07:10.297  8278  8278 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 00:07:10.300  8278  8278 D AndroidRuntime: CheckJNI is OFF
09-13 00:07:10.302  1033  1988 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8289 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-13 00:07:10.305  1033  1988 I ActivityManager: Killing 7345:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-13 00:07:10.323   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 23.237ms
,09-13 00:07:10.328  8218  8285 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 00:07:10.343   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 19.806ms
,09-13 00:07:10.363   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.716ms
,09-13 00:07:10.413  8278  8278 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 00:07:10.530  1033  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-13 00:07:10.532  1033  1090 I ActivityManager: Killing 6853:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 00:07:10.615  1033  1867 I WindowState: WIN DEATH: Window{22e2dca6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 00:07:10.615  1033  1423 D WifiService: Client connection lost with reason: 4
,09-13 00:07:10.639  1033  1867 D InputDispatcher: Window went away: Window{22e2dca6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 00:07:10.751  1033  1090 I ActivityManager:   Force finishing activity ActivityRecord{1f6c4ea3 u0 com.test.thalitest/.MainActivity t6}
,09-13 00:07:10.779  1033  1389 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 00:07:10.781  1033  1389 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 00:07:10.782  1033  1389 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 00:07:10.783  1033  1389 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 00:07:10.786  1033  1389 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 00:07:10.792   338   354 E GBMv2   : DFP En is all cleared set to be enabled
09-13 00:07:10.795  1033  1389 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 00:07:10.800  1033  1440 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 00:07:10.800  1033  1440 D ConnectivityService: identical MTU - not setting
09-13 00:07:10.800  1033  1440 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 00:07:10.800  1033  1440 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 00:07:10.801  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:07:10.801  1033  1440 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 00:07:10.802  1033  1440 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 00:07:10.804  1601  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 00:07:10.809  1033  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 00:07:10.817  1033  1122 I ActivityManager:   Force finishing activity ActivityRecord{1f6c4ea3 u0 com.test.thalitest/.MainActivity t6 f}
09-13 00:07:10.817  1033  1122 W ActivityManager: Duplicate finish request for ActivityRecord{1f6c4ea3 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 00:07:10.840  1033  1049 W libprocessgroup: failed to open /acct/uid_10093/pid_7345/cgroup.procs: No such file or directory
09-13 00:07:10.843  1033  1572 W ActivityManager: Spurious death for ProcessRecord{388f0033 6853:com.test.thalitest/u0a118}, curProc for 6853: null
09-13 00:07:10.845  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 00:07:10.846  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 00:07:10.847  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,09-13 00:07:10.847  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f295ac3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 00:07:10.847  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 00:07:10.848  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 00:07:10.849  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34153f40 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 00:07:10.850  2032  2071 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 00:07:10.854  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 00:07:10.855  1904  1904 D ActionManagerService: notifyUserLog: 1000003
09-13 00:07:10.855  3781  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 00:07:10.856  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 00:07:10.857  8289  8289 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:07:10.859  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 00:07:10.891  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 00:07:10.893  3781  3781 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-13 00:07:10.901  7744  7744 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 00:07:10.901  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 00:07:10.902  2467  2615 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 00:07:10.902  4967  4967 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 00:07:10.903  4967  4967 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 00:07:10.903  4967  4967 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 00:07:10.903  4967  4967 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 00:07:10.903  4967  4967 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 00:07:10.903  4967  4967 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 00:07:10.903  4967  4967 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:10.903  4967  4967 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:10.903  4967  4967 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:10.903  4967  4967 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:07:10.903  4967  4967 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:10.903  4967  4967 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 00:07:10.905  5060  5060 I art     : Explicit concurrent mark sweep GC freed 8209(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 528us total 60.665ms
09-13 00:07:10.909  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 00:07:10.913  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-13 00:07:10.915  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-13 00:07:10.926  1033  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 00:07:10.934  1033  2030 V SIM_STK : Menu title from STK is T-Mobile
,09-13 00:07:10.949  1033  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-13 00:07:10.970  1033  1033 D administrator: Handling package changes for user 0
,09-13 00:07:10.971  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 00:07:10.973  3781  4952 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 00:07:10.973  1904  1904 D ActionManagerService: notifyUserLog: 1000004
09-13 00:07:10.973  3781  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 00:07:10.975  8289  8289 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-13 00:07:10.975  1601  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 00:07:10.975  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , display: false
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , animation: false }
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , display: false
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , animation: false }
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , display: false
09-13 00:07:10.975  2032  2032 I GBoardWebViewUtils: , animation: false }
09-13 00:07:10.980  2032  8335 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 00:07:10.989  1601  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 00:07:10.989  1601  1664 D KeyguardModel: createShortcutInfo...
,09-13 00:07:10.998  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 00:07:10.999  1601  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:07:10.999  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 00:07:11.000  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 00:07:11.000  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 00:07:11.000  1601  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 00:07:11.001  1601  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 00:07:11.025  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 00:07:11.025  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-13 00:07:11.036  1033  1939 V SIM_STK : Menu title from STK is T-Mobile
09-13 00:07:11.036  1033  1939 V SIM_STK : Menu title from STK is T-Mobile
09-13 00:07:11.047  1601  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 00:07:11.047  1601  1664 D KeyguardModel: createShortcutInfo...
,09-13 00:07:11.052  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 00:07:11.053  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 00:07:11.053  1601  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 00:07:11.053  1601  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 00:07:11.057  1601  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 00:07:11.057  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:11.061  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-13 00:07:11.061  1868  1868 D SplitUIService: removed split : 
09-13 00:07:11.070  1601  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:07:11.070  1601  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 00:07:11.071  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 00:07:11.071  1601  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 00:07:11.071  1601  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 00:07:11.071  1601  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 00:07:11.073  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 00:07:11.075  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-13 00:07:11.078  8289  8289 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 00:07:11.078  8289  8289 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 00:07:11.078  8289  8289 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 00:07:11.079  8289  8289 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 00:07:11.079  8289  8289 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 00:07:11.080  8289  8289 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 00:07:11.084  8289  8289 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 00:07:11.085  1601  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 00:07:11.085  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:11.087  1033  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 00:07:11.087  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 00:07:11.087  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 00:07:11.088  7744  7744 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-13 00:07:11.089  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-13 00:07:11.089  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 00:07:11.093  1033  1572 V SIM_STK : Menu title from STK is T-Mobile
09-13 00:07:11.097  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.105  8218  8285 D LgDataFeature: LgDataFeature() Constructor: none
09-13 00:07:11.105  8218  8285 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 00:07:11.106  1601  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 00:07:11.106  1601  1664 D KeyguardModel: createShortcutInfo...
,09-13 00:07:11.109  1601  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 00:07:11.109  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:11.110  1601  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 00:07:11.110  1601  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 00:07:11.112  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-13 00:07:11.112  1868  1868 I SplitUIService: split app #11
09-13 00:07:11.112  1601  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 00:07:11.112  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:11.113  1601  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 00:07:11.113  1601  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 00:07:11.114  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.115  1601  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 00:07:11.115  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:11.116  1601  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 00:07:11.116  1601  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 00:07:11.118  1601  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 00:07:11.118  1601  1664 D KeyguardModel: createShortcutInfo...
09-13 00:07:11.132  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-13 00:07:11.132  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-13 00:07:11.146   322   441 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 00:07:11.146  8289  8289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 00:07:11.147  3397  8341 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-13 00:07:11.151  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 00:07:11.155  6956  6956 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-13 00:07:11.158  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.158  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.161  8289  8289 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 00:07:11.163  8289  8289 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 00:07:11.165  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 00:07:11.165  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 00:07:11.165  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 00:07:11.169  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.170  1033  1575 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 00:07:11.173  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 00:07:11.176  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.177  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.181  1033  1122 I art     : Explicit concurrent mark sweep GC freed 81022(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.625ms total 327.988ms
09-13 00:07:11.182  8289  8289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 00:07:11.190  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.190  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.195  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.199  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-13 00:07:11.201  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 00:07:11.203  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 00:07:11.204  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 00:07:11.205  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 00:07:11.206  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 00:07:11.207  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.217  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.217  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 00:07:11.220  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c26a96c u0 com.lge.launcher2/.Launcher t5} time:203233
09-13 00:07:11.221  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 00:07:11.221  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 00:07:11.222  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:07:11.223  2032  2106 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 00:07:11.223  2032  2106 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 00:07:11.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 00:07:11.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 00:07:11.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 00:07:11.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 00:07:11.224  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 00:07:11.225  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 00:07:11.226  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 00:07:11.226  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 00:07:11.226  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 00:07:11.226  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 00:07:11.226  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 00:07:11.228  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 00:07:11.230  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.230  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 00:07:11.235  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 00:07:11.236  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 00:07:11.236  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 00:07:11.236  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:07:11.244  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-13 00:07:11.245  2622  2622 D [Concierge]Service: onStartCommand(). Type : 8
09-13 00:07:11.245  2622  2622 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 00:07:11.247  2622  2622 D [Concierge]Service: Update widget ID : 11
09-13 00:07:11.247  2032  2032 D [Concierge]WidgetView: change position of spinner
09-13 00:07:11.248  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.252  8218  8285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-13 00:07:11.253  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1473718031253
09-13 00:07:11.253  2622  2622 D [Concierge]Service: onStartCommand(). Type : 0
09-13 00:07:11.256  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.256  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.256  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 00:07:11.258  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.259  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.264  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.268  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-13 00:07:11.269  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.272  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.272  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.272  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:07:11.274  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.274  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.277  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.281  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 659221675
09-13 00:07:11.281  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 00:07:11.281  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 00:07:11.282  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.284  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@afd5579
09-13 00:07:11.284  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 00:07:11.285  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.285  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.285  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:07:11.285  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 00:07:11.286  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 00:07:11.287  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.288  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-13 00:07:11.288  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 00:07:11.288  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 00:07:11.289  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-13 00:07:11.289  8218  8285 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-13 00:07:11.289  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.291  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 00:07:11.291  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 00:07:11.291  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 00:07:11.291  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-13 00:07:11.292  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473717855699, New one : 1473718031253
09-13 00:07:11.292  2032  2032 D [Concierge]WidgetView: Unregister all receivers
09-13 00:07:11.292  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:07:11.292  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-13 00:07:11.293  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 00:07:11.294  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 00:07:11.294  8278  8278 D AndroidRuntime: Shutting down VM
09-13 00:07:11.295  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-13 00:07:11.295  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 00:07:11.296  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 00:07:11.297  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 00:07:11.297  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.298  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-13 00:07:11.303  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 00:07:11.304  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 00:07:11.334  1033  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8348 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 00:07:11.340  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.346  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.346  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 00:07:11.356  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 00:07:11.363  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.363  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.369  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 00:07:11.369  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.369  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 00:07:11.372  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 00:07:11.384  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:07:11.388  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.391  1033  1572 I ActivityManager: Killing 7373:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-13 00:07:11.391  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b191174 time:203405
09-13 00:07:11.393  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 00:07:11.505  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.505  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.507  1033  1050 W libprocessgroup: failed to open /acct/uid_10005/pid_7373/cgroup.procs: No such file or directory
,09-13 00:07:11.512  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 00:07:11.513  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-13 00:07:11.513  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:07:11.515  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.515  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.519  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.529  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.533  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.534  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.534  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 00:07:11.536  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.536  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 00:07:11.539  8169  8169 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 00:07:11.541  8169  8169 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:07:11.542  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 00:07:11.545  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 00:07:11.548  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.549  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.552  2032  2856 I GBoardtInterface: onReloaded()
,09-13 00:07:11.552  8289  8289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 00:07:11.552  8289  8289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 00:07:11.553  8289  8289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 00:07:11.555  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 00:07:11.556  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 00:07:11.557  3781  4952 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 00:07:11.559  3781  3797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 00:07:11.564  1904  1904 D ActionManagerService: notifyUserLog: 1000001
,09-13 00:07:11.566  3781  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 00:07:11.566  3781  4956 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 00:07:11.568  1904  1904 D ActionManagerService: notifyUserLog: 1000001
09-13 00:07:11.569  3781  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 00:07:11.569  3781  4956 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 00:07:11.569  3781  4956 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 00:07:11.569  3781  4956 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-13 00:07:11.569  3781  4952 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 00:07:11.571  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 00:07:11.571  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 00:07:11.573  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 00:07:11.573  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 00:07:11.574  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 00:07:11.574  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 00:07:11.606  8169  8169 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 00:07:11.606  8169  8169 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 00:07:11.608  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 00:07:11.620  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 00:07:11.626  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 00:07:11.626  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 00:07:11.626  8289  8289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 00:07:11.627  8289  8289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 00:07:11.627  8289  8289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 00:07:11.630  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 00:07:11.632  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 00:07:11.634  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 00:07:11.639  2199  2199 I ConfigService: onCreate
09-13 00:07:11.639  2199  2199 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 00:07:11.641  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
09-13 00:07:11.643  2199  8371 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
09-13 00:07:11.643  2199  8371 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-13 00:07:11.645  2199  8371 W SQLiteOpenHelper: Opened config.db in read-only mode
09-13 00:07:11.645  2199  2199 I ConfigService: onBind returning update interface
09-13 00:07:11.646  2199  2199 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 00:07:11.646  2199  2199 I ConfigService: onBind returning config service
09-13 00:07:11.646  1815  4009 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
09-13 00:07:11.651  2199  2199 I ConfigService: onDestroy,
09-13 00:07:11.654  1815  8372 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 00:07:11.726  7181  7181 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
,09-13 00:07:11.732  7181  7181 E SQLiteDatabase: Error inserting package=com.test.thalitest
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 00:07:11.732  7181  7181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 00:07:11.745  5827  8378 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-13 00:07:11.748  1815  8379 I PeopleContactsSync: CP2 sync disabled
09-13 00:07:11.752  1815  5153 I Icing   : doRemovePackageData com.test.thalitest
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.754  1815  8376 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:07:11.754  1815  8376 E SQLi,teOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.754  1815  8376 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:07:11.755  2306  8380 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 00:07:11.755  1815  8376 W SQLiteOpenHelper: Opened metrics.db in read-only mode
09-13 00:07:11.756  1815  8376 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
09-13 00:07:11.756  1815  8376 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
09-13 00:07:11.756  1815  8376 E AndroidRuntime: Process: com.google.android.gms, PID: 1815
09-13 00:07:11.756  1815  8376 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.756  1815  8376 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:07:11.757  2306  2513 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException du,ring query
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.757  2306  2513 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:07:11.760  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
09-13 00:07:11.760  1815  5153 E Icing   : Could not init tag ds.tag.corpusid-1
09-13 00:07:11.760  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
09-13 00:07:11.760  1815  5153 E Icing   : Could not init tag ds.tag.corpusid-13
09-13 00:07:11.760  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
09-13 00:07:11.760  1815  5153 E Icing   : Could not init tag ds.tag.corpusid-7
09-13 00:07:11.761  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
09-13 00:07:11.761  1815  5153 E Icing   : Could not init tag ds.tag.corpusid-8
09-13 00:07:11.761  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
09-13 00:07:11.761  1815  5153 E Icing   : Could not init tag ds.tag.corpusid-9
09-13 00:07:11.761  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
09-13 00:07:11.761  1815  5153 E Icing   : Could not init tag ds.tag.deleted
09-13 00:07:11.761  1815  5153 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
09-13 00:07:11.761  1815  5153 E Icing   : Writing status failed
09-13 00:07:11.763  2306  8380 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-13 00:07:11.764  2306  8380 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 00:07:11.764  2306  8380 E AndroidRuntime: Process: android.process.acore, PID: 2306
09-13 00:07:11.764  2306  8380 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.764  2306  8380 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
09-13 00:07:11.769  1815  8381 E SQLiteDatabase: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
09-13 00:07:11.769  1815  8381 I Process : Sending signal. PID: 1815 SIG: 9
09-13 00:07:11.774  4967  5004 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: Error inserting f004=20 f005=1815 f002=1473718031771 f003= f006=-1
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-13 00:07:11.779  4967  5004 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
09-13 00:07:11.781  1033  2031 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8383 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-13 00:07:11.784  1033  1423 D WifiService: Client connection lost with reason: 4
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 00:07:11.790  1033  8395 E DropBoxManagerService: 	... 5 more
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 00:07:11.790  1033  8389 E DropBoxManagerService: 	... 5 more
,09-13 00:07:11.805   338   356 E GBMv2   : DFP En is all cleared set to be enabled
09-13 00:07:11.805   338   356 E GBMv2   : Set value is all cleared set the max
09-13 00:07:11.805   338   356 I GBMv2   : DFP Enabled. Ignore VFP set

```
