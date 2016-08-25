#### Test 82728424ebd9a7c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 17:40:01.789  2187  2187 I ConfigService: onDestroy
,08-25 17:40:08.821  6827  6827 D AndroidRuntime: 
08-25 17:40:08.821  6827  6827 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 17:40:08.825  6827  6827 D AndroidRuntime: CheckJNI is OFF
08-25 17:40:08.953  6827  6827 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 17:40:08.958  1032  1701 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 17:40:08.968  1938  3967 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 17:40:08.971  1032  1701 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 17:40:08.972  1032  1701 D ActivityManager: setTaskToReturnTo : TaskRecord{2bc114bf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 17:40:08.972  1032  1701 D ActivityManager: setTaskToReturnTo : TaskRecord{2bc114bf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 17:40:08.973  1032  1701 D WindowStateEx: AppWindowTokenEx init.. 
08-25 17:40:08.974   336   346 E GBMv2   : DFP En is all cleared set to be enabled
08-25 17:40:09.013  1032  1701 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6846 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 17:40:09.015  6827  6827 D AndroidRuntime: Shutting down VM
08-25 17:40:09.052  1938  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 17:40:09.053  1938  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21f1eae8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 17:40:09.053  1938  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 17:40:09.053  1938  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{103e501 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 17:40:09.120  6846  6846 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-25 17:40:09.212  6846  6846 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-25 17:40:09.224  6846  6846 I LibraryLoader: Loading: webviewchromium
,08-25 17:40:09.232  6846  6846 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 951-960)
08-25 17:40:09.232  6846  6846 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:40:09.249  6846  6846 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cf6f8d6}
08-25 17:40:09.250  6846  6846 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:40:09.250  6846  6846 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:40:09.260  6846  6846 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 17:40:09.261  6846  6846 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 17:40:09.271  6846  6846 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 17:40:09.272  6846  6846 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-25 17:40:09.272  6846  6846 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 17:40:09.274   314  2122 V AudioPolicyService: registerClient() client 0xb558a4e0, uid 10118
08-25 17:40:09.279  1032  1094 D BluetoothManagerService: Message: 20
08-25 17:40:09.279  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@301d3351:true
08-25 17:40:09.293  6846  6846 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:40:09.293  6846  6846 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:40:09.293  6846  6846 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:40:09.293  6846  6846 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:40:09.293  6846  6846 I Adreno-EGL: Remote Branch: 
08-25 17:40:09.293  6846  6846 I Adreno-EGL: Local Patches: 
08-25 17:40:09.293  6846  6846 I Adreno-EGL: Reconstruct Branch: 
,08-25 17:40:09.486  1032  1955 I art     : Explicit concurrent mark sweep GC freed 34686(1668KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.095ms total 149.040ms
,08-25 17:40:09.512  6846  6877 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 17:40:09.524  6846  6846 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 17:40:09.539  6846  6846 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:40:09.544  6846  6846 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 17:40:09.546  6846  6846 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 17:40:09.548  6846  6846 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 17:40:09.548  6846  6846 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-25 17:40:09.551  1032  1090 W ActivityManager: Activity pause timeout for ActivityRecord{42378c u0 com.test.thalitest/.MainActivity t6}
08-25 17:40:09.560  6846  6846 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 17:40:09.565  6846  6846 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 17:40:09.566  6846  6846 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 17:40:09.607  6846  6889 D OpenGLRenderer: Render dirty regions requested: true
08-25 17:40:09.607  6846  6889 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 17:40:09.615  6846  6889 D OpenGLRenderer: Enabling debug mode 0
08-25 17:40:09.627  6846  6846 D Atlas   : Validating map...
,08-25 17:40:09.630  1032  1047 D SplitWindow: check instance of lgWin Window{23a97143 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 17:40:09.678  6846  6887 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:40:09.678  6846  6887 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:40:09.747  1032  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +696ms (total +772ms)
08-25 17:40:09.748  6846  6846 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ab94d9d time:171476
,08-25 17:40:09.750  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{42378c u0 com.test.thalitest/.MainActivity t6} time:171478
08-25 17:40:09.869  6846  6846 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 17:40:09.869  6846  6846 I chromium: 
,08-25 17:40:09.927  6846  6846 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 17:40:10.004  6846  6887 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 17:40:10.004  6846  6887 I chromium: 
,08-25 17:40:10.125   336   348 E GBMv2   : DFP En is all cleared set to be enabled
08-25 17:40:10.125   336   348 E GBMv2   : Set value is all cleared set the max
08-25 17:40:10.125   336   348 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 17:40:10.153  6846  6908 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-25 17:40:10.178  6846  6908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 17:40:10.178  6846  6908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 17:40:10.178  6846  6908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 17:40:10.178  6846  6908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 17:40:10.178  6846  6908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 17:40:10.179  6846  6908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f90fd1 added. We now have 1 listener(s)
,08-25 17:40:10.192  1032  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:40:10.195  6846  6908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-25 17:40:10.198  6846  6908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:10.200  6846  6908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:10.200  6846  6908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 17:40:10.208  6846  6908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c6d2a4 added. We now have 1 listener(s)
08-25 17:40:10.209  6846  6908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:40:10.214  1032  1462 D WifiService: New client listening to asynchronous messages
08-25 17:40:10.218  6846  6908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:10.218  6846  6908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 17:40:10.219  6846  6908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 17:40:10.219  6846  6908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 17:40:10.219  6846  6908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 17:40:10.223  6846  6908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:10.224  1032  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:40:10.225  6846  6908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 17:40:10.234  6846  6908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:10.235  6846  6908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:10.235  6846  6908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 17:40:10.235  6846  6908 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:10.236  6846  6908 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 17:40:10.237  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:10.239  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:10.277  6846  6846 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 17:40:11.272  6846  6911 W jxcore-log: Initializing JXcore engine
08-25 17:40:11.272  6846  6911 W jxcore-log: JXcore engine is ready
,08-25 17:40:11.324  6911  6911 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7451]" dev="sockfs" ino=7451 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 17:40:11.324  6911  6911 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 17:40:11.324  6911  6911 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10420]" dev="sockfs" ino=10420 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-25 17:40:11.324  6911  6911 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 17:40:11.324  6911  6911 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32135]" dev="sockfs" ino=32135 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 17:40:11.368  6846  6911 W jxcore-log: Starting JXcore engine
,08-25 17:40:11.521  6846  6911 W jxcore-log: Platform android
08-25 17:40:11.521  6846  6911 W jxcore-log: 
08-25 17:40:11.521  6846  6911 W jxcore-log: Process ARCH arm
08-25 17:40:11.521  6846  6911 W jxcore-log: 
,08-25 17:40:11.759  6846  6911 I jxcore-log: JXcore Cordova bridge is ready!
08-25 17:40:11.759  6846  6911 I jxcore-log: 
08-25 17:40:11.759  6846  6911 W jxcore-log: JXcore engine is started
,08-25 17:40:11.770  6846  6908 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 17:40:11.774  6846  6846 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 17:40:21.365  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 17:40:21.365  6846  6911 I jxcore-log: 
,08-25 17:40:21.368  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 17:40:21.368  6846  6911 I jxcore-log: 
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:21.373  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:21.376  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:21.379  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 17:40:21.379  6846  6911 I jxcore-log: 
08-25 17:40:21.381  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 17:40:21.381  6846  6911 I jxcore-log: 
,08-25 17:40:21.886  6846  6911 D executeNativeTests: Running unit tests
,08-25 17:40:21.966  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:40:21.966  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 added. We now have 2 listener(s),
08-25 17:40:21.967  1032  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,08-25 17:40:21.973  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:21.973  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:21.973  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:21.973  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:21.973  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 added. We now have 2 listener(s)
08-25 17:40:21.973  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:21.973  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:21.976  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:21.979  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:21.980  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:21.981  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:21.982  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:21.984  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:21.986  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
,08-25 17:40:21.988  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:40:21.988  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-25 17:40:21.990  6846  6911 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 17:40:21.991  6846  6911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-25 17:40:21.991  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-25 17:40:21.991  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:40:21.991  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:40:21.992  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:21.992  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-25 17:40:21.992  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:21.993  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:40:21.993  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 17:40:21.993  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-25 17:40:21.993  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:21.993  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 removed from the list
08-25 17:40:21.993  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:21.994  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 removed from the list
08-25 17:40:21.994  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:21.994  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:40:21.994  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:21.994  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:21.996  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:21.996  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:21.996  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:21.996  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
,08-25 17:40:21.997  6846  6911 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 17:40:21.998  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:21.998  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:21.998  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:21.998  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:21.998  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:21.998  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:40:21.998  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:21.998  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:21.998  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:21.998  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:21.998  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:21.998  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:40:21.998  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:21.998  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:21.999  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:21.999  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:21.999  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 17:40:21.999  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.003  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:40:22.003  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:40:22.003  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
08-25 17:40:22.004  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:40:22.005  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:40:22.005  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.005  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.005  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.005  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.005  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.005  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.005  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.006  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.006  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.006  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.006  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.006  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.006  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.006  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.007  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.007  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.007  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.007  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.008  6846  6911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:40:22.009  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:22.011  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:22.012  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.012  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:22.014  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.015  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.015  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:22.015  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:40:22.015  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:40:22.015  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.015  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:40:22.018  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:40:22.018  1032  1700 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:22.022  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:40:22.025  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-25 17:40:22.026  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 17:40:22.028  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:40:22.028  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:22.029  6846  6911 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:40:22.029  6846  6911 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:40:22.031  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:40:22.031  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.031  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.032  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.032  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.032  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:22.032  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
,08-25 17:40:22.032  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.032  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.032  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.032  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.032  6846  6911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:40:22.034  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:22.036  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:40:22.036  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-25 17:40:22.036  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:22.037  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.038  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.039  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:22.039  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:40:22.039  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:40:22.039  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.039  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:40:22.041  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:40:22.042  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:22.042  6846  6911 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:40:22.043  6846  6911 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:40:22.044  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.044  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.044  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.044  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.044  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.044  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:22.044  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.044  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.044  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.044  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.044  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.044  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.044  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.045  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.045  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.046  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.046  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.046  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.046  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.047  6846  6911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 17:40:22.048  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:22.050  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:22.050  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.050  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:22.052  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:22.053  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.053  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:22.053  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:40:22.053  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:40:22.053  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.053  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:40:22.056  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:40:22.056  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:22.057  6846  6911 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:40:22.057  6846  6911 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:40:22.057  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.057  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:40:22.057  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.058  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.058  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.058  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.058  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.058  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 17:40:22.058  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:22.058  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.058  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:40:22.058  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.058  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.058  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.058  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.058  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-25 17:40:22.059  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.059  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.059  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.059  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.059  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.059  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.060  6846  6911 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 17:40:22.060  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.060  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.060  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.060  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.060  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.060  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.060  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.060  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.060  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.060  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.060  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.060  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.060  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.060  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.061  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.061  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.061  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.061  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.061  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.061  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.062  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:40:22.062  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.062  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: ,NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.062  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.063  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.063  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.063  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.063  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.063  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.063  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.063  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.063  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.063  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.063  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.063  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.063  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.064  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.064  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.064  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.064  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.064  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.064  6846  6911 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 17:40:22.065  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.065  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.065  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.065  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.065  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.065  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.065  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.065  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.065  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.065  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.065  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.065  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.065  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.065  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.066  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.066  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.066  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.066  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.066  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.066  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.067  6846  6911 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 17:40:22.067  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.067  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.067  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.068  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.068  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.068  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.068  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.068  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.068  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.068  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.068  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.068  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.068  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.068  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.069  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.069  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.069  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.069  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.069  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.069  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.070  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:40:22.071  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:40:22.071  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:40:22.071  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:40:22.071  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:40:22.071  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:40:22.071  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.071  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.071  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.072  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.072  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.072  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.072  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.072  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.072  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.072  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.072  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.072  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.072  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.072  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.072  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.072  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.073  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.073  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.073  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.073  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.073  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:40:22.073  6846  6911 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:40:22.073  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:40:22.077  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:40:22.077  6846  6911 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:40:22.077  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:40:22.079  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 17:40:22.079  6846  6911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:40:22.079  6846  6911 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 17:40:22.079  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:40:22.079  6846  6911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:40:22.080  6846  6911 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 17:40:22.080  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:40:22.080  6846  6911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:40:22.080  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 17:40:22.081  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 17:40:22.081  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 17:40:22.082  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 17:40:22.083  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 17:40:22.083  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 17:40:22.083  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 17:40:22.083  6846  6911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:40:22.083  6846  6911 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 17:40:22.083  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.083  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.083  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.084  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.084  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.084  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.084  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 17:40:22.084  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.084  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.084  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.084  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.084  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.084  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.084  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.084  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.085  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.085  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.085  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.085  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.085  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.085  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.086  6846  6911 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 17:40:22.086  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.086  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.086  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.086  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.086  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.086  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.086  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.086  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.087  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.087  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.087  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.087  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.087  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.087  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.087  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.087  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.088  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.088  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.088  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:40:22.088  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.088  6846  6911 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 17:40:22.089  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.089  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.089  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.089  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.089  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.089  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.089  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.089  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.089  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.089  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.089  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.089  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.089  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.089  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.090  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.090  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.090  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.090  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.090  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.091  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.091  6846  6911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 17:40:22.091  6846  6911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 17:40:22.091  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:40:22.091  6846  6911 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 17:40:22.092  6846  6911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:40:22.092  6846  6911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 17:40:22.092  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:40:22.092  6846  6911 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 17:40:22.092  6846  6911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:40:22.092  6846  6911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:40:22.092  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:40:22.092  6846  6911 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 17:40:22.092  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.092  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.092  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.092  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.092  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.092  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.093  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.093  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.093  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.093  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.093  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.093  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.093  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.093  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.093  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.093  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.094  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.094  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.094  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.094  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.094  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.094  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.094  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.094  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.094  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.094  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.094  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.094  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.094  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.094  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.095  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.095  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.095  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.095  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.095  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.095  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.095  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.095  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.095  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.095  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.095  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.095  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.095  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.095  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.095  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.095  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.095  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.095  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.095  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.096  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.096  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.096  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.096  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.096  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.096  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.097  6846  6911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 17:40:22.097  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.098  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 17:40:22.099  6846  6911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 17:40:22.099  6846  6911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 17:40:22.100  6846  6846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 17:40:22.100  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 17:40:22.100  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:40:22.101  6846  6917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-25 17:40:22.102  6846  6916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-25 17:40:22.102  6846  6916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-25 17:40:22.103  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.103  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 17:40:22.103  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 17:40:22.103  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 17:40:22.103  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.103  6846  6911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 17:40:22.103  6846  6919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 17:40:22.103  6846  6919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 17:40:22.104  6846  6846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 17:40:22.104  6846  6846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 17:40:22.105  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.105  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.105  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:40:22.105  6846  6911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:40:22.105  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:40:22.105  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:40:22.106  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:22.106  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:22.106  6846  6911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:40:22.106  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.106  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.107  6846  6911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:40:22.107  6846  6846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:40:22.107  6846  6846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:40:22.107  6846  6846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:40:22.107  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.107  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.107  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.107  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.107  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.107  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.108  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.108  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.108  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.108  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.108  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.108  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.108  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.108  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.108  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.108  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.108  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.108  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.108  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.109  6846  6911 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 17:40:22.109  6846  6911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:40:22.109  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:40:22.110  6846  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:40:22.111  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.111  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.111  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.111  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.111  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.111  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.111  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.111  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.111  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.111  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.111  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.111  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.111  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.111  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.112  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.112  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.112  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.112  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.113  1032  1701 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:22.113  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:22.114  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:22.114  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.114  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.114  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.115  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.115  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.115  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.115  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.115  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.115  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.115  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.115  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.115  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.115  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.115  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.115  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.115  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.115  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.115  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.116  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:22.116  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:22.116  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:22.116  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:22.116  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.116  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.116  6846  6911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d46d061 not in the list
08-25 17:40:22.116  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.116  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.116  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:22.117  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.117  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.117  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:22.117  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:22.117  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:22.117  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:22.117  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:22.117  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36aa7786 not in the list
08-25 17:40:22.119  6846  6911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 17:40:22.119  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:40:22.119  6846  6911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 17:40:22.119  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:40:22.119  6846  6911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 17:40:22.119  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:40:22.120  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:40:22.120  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 17:40:22.121  6846  6911 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 17:40:22.121  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:40:22.121  6846  6911 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 17:40:22.121  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:40:22.121  6846  6911 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 17:40:22.121  6846  6911 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 17:40:22.122  6846  6911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 17:40:22.122  6846  6911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 17:40:22.122  6846  6911 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 17:40:22.122  6846  6911 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 17:40:22.123  6846  6911 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 17:40:22.123  6846  6911 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 17:40:22.123  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:22.123  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5df993f added. We now have 2 listener(s)
08-25 17:40:22.123  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:22.124  6846  6911 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 17:40:22.125  1032  1955 D WifiServiceImplEx: setWifiEnabled: true pid=6846, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:40:22.125  1032  1955 D WifiService: setWifiEnabled: true pid=6846, uid=10118
08-25 17:40:22.125  1032  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:40:22.126  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:22.126  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@269fa20c added. We now have 3 listener(s)
08-25 17:40:22.126  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:22.129  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:22.129  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@369fd755 added. We now have 4 listener(s)
08-25 17:40:22.129  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:22.130  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:22.130  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1668c56a added. We now have 5 listener(s)
08-25 17:40:22.130  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:22.132  1032  1973 D WifiServiceImplEx: setWifiEnabled: false pid=6846, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:40:22.132  1032  1973 D WifiService: setWifiEnabled: false pid=6846, uid=10118
08-25 17:40:22.132  1032  1973 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:40:22.145  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:40:22.145  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:22.145  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:22.146  1032  1398 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:22.147  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:22.147  1032  1398 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:22.147  1032  1398 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:22.148  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:22.148  1032  1398 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 17:40:22.148  1032  1398 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:40:22.148  1032  1398 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:40:22.149  1032  1398 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:40:22.149  1032  1398 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:40:22.150  1032  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:22.150  1032  2010 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2192b652 mBinding = false
08-25 17:40:22.157  1032  1398 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:40:22.158  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.158  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.158  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:40:22.158  2736  2736 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:40:22.159  1032  1398 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:40:22.159  1032  1398 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:40:22.159  1032  1398 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:40:22.160  1032  2856 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.160   307   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:40:22.164  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:40:22.164  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:22.165  1032  1094 D BluetoothManagerService: Message: 2
08-25 17:40:22.165  1032  1094 D BluetoothManagerService: Sending off request.
08-25 17:40:22.166  3861  3879 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 17:40:22.167  3861  3943 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 17:40:22.167  3861  3943 D BluetoothAdapterProperties: Setting state to 13
08-25 17:40:22.167  3861  3943 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:40:22.167  3861  3943 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:40:22.167  3861  3943 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 17:40:22.180  3861  3948 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:40:22.181  3861  3943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 17:40:22.182  3861  4190 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 17:40:22.183  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:22.189  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:22.189  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:22.190  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.190  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:22.190  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:22.190  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 17:40:22.190  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 17:40:22.191  3861  4191 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:22.192  3861  4238 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:22.192  3861  4240 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:22.193  1032  1470 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 17:40:22.193  1032  1470 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-25 17:40:22.194  3861  4242 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 17:40:22.197  3861  3943 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:40:22.199  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 17:40:22.199  3861  4055 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 17:40:22.200  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 17:40:22.203  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 17:40:22.203  3861  4055 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 17:40:22.217  1032  1701 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-25 17:40:22.219  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.219  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.219  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 17:40:22.219  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.219  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-25 17:40:22.239  1032  1470 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 17:40:22.239   307  6935 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 17:40:22.239  1032  1470 D DSQN    : disableDataServiceNotify
08-25 17:40:22.240  1032  1470 D DSQN    : stop dsqn bin
08-25 17:40:22.240  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 17:40:22.240  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-25 17:40:22.246  1032  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6934 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-25 17:40:22.247  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:22.249  1032  1470 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 17:40:22.249  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:22.249  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:22.249  1032  1470 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:22.249  1032  1470 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 17:40:22.249  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.249  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.250  1032  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 17:40:22.250  1032  1470 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 17:40:22.250  1032  1470 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 17:40:22.250  1600  2068 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 17:40:22.250  1032  1470 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:40:22.251  1032  1470 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:22.251  1032  1470 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:40:22.251  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-25 17:40:22.253  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-25 17:40:22.253  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:22.253  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:22.253  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:22.254  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.254  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:22.254  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:40:22.254  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.254  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.254  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:40:22.255  1032  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 17:40:22.256  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.258  3861  3861 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.258  3861  3861 D BluetoothMapService: STATE_TURNING_OFF
08-25 17:40:22.259  3861  3861 V BtOppService: Receiver DISABLED_ACTION 
08-25 17:40:22.259  3861  3861 V BluetoothMapService: Handler(): got msg=4
08-25 17:40:22.259  3861  3861 D BluetoothMapService: MAP Service closeService in
08-25 17:40:22.259  3861  3861 D BluetoothMapMasInstance: MAP Service shutdown
08-25 17:40:22.259  3861  3861 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:40:22.259  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 17:40:22.259  3861  3861 V BluetoothMapService: MAP Service closeService out
08-25 17:40:22.259  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.259  3861  3861 I BtOppRfcommListener: stopping Accept Thread
08-25 17:40:22.259  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 17:40:22.259  3861  3861 V BtOppRfcommListener: close mBtServerSocket
08-25 17:40:22.260  3861  3861 V BtOppRfcommListener: waiting for thread to terminate
08-25 17:40:22.260  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:40:22.260  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:40:22.260  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:40:22.261  3861  4238 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:40:22.261  3861  3861 V BtOppRfcommListener: done waiting for thread to terminate
,08-25 17:40:22.300  1032  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6952 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 17:40:22.301  1032  1470 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:22.301  1032  1470 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:22.301  1032  1470 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:22.302  1032  1470 D NetworkManagementService: Removing idletimer
08-25 17:40:22.302  1849  1849 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:22.302  1849  1849 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:40:22.302  1032  1470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.302  1032  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 17:40:22.302  1032  1470 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 17:40:22.303  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 17:40:22.303  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:40:22.303  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:40:22.303  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:40:22.304  1032  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.304  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.304  1032  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2aa9164
08-25 17:40:22.305  1032  1398 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.305  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.305  1032  1398 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.306  1032  1398 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.306  1032  1388 D LGWifiP2pService: P2pDisablingState
08-25 17:40:22.306  1032  1388 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.306  1032  1388 D LGWifiP2pService: p2p socket connection lost
08-25 17:40:22.306  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.306  1032  1388 D LGWifiP2pService: P2pDisabledState
08-25 17:40:22.306  3861  3861 V BtOppService: onDestroy
08-25 17:40:22.307  1032  1398 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.307  1032  1398 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 17:40:22.308  1032  1398 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.308  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.308  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.309  1032  1398 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:22.309  1032  1398 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:22.309  1032  1398 D WIFI    :   my score=60, my filter=[ Tr,ansports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:40:22.310  1032  1398 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 17:40:22.310  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:22.310  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:22.310  1032  1388 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.310  1032  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.311  3861  3861 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 17:40:22.312  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-25 17:40:22.312  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:22.312  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:40:22.315  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:40:22.315  1938  1938 D WfdsService: WifiP2pState is changed : false
08-25 17:40:22.315  1938  2326 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 17:40:22.315  1938  2326 D WfdsService: Set the WFDS Monitor: false
08-25 17:40:22.316  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.316  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.316  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:40:22.316  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 17:40:22.316  1032  1032 D RttService: SCAN_AVAILABLE : 1
08-25 17:40:22.316  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.316  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:22.316  1032  1553 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.316  1032  1554 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:22.316  1938  2326 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:40:22.316  1938  2326 D WfdsService: STATE : WfdsDisabledState - enter
08-25 17:40:22.317  1938  2773 D CtrlSupplicant: Received on exit socket, terminate
08-25 17:40:22.317  1938  2773 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 17:40:22.317  1938  2773 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
,08-25 17:40:22.317  1938  2773 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 17:40:22.317  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:40:22.317  2736  2736 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:40:22.318  1938  2329 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 17:40:22.318  1938  2326 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 17:40:22.318  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.321  1032  1398 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:40:22.321  1032  1398 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:40:22.322  1032  1398 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:40:22.322   307   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:40:22.324  1032  1398 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 17:40:22.325  1032  1398 D WifiNative-p2p0: TERMINATE: returned true
08-25 17:40:22.325  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:22.325  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:22.325  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 17:40:22.328  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-25 17:40:22.328  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.328  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.328  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:40:22.333  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 17:40:22.334  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 17:40:22.334  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:22.334  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 17:40:22.336  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:22.336  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:22.336  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.336  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:22.339  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:22.339  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:40:22.340  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:22.340  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:22.342  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:40:22.343  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.343  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.347  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 17:40:22.371  6952  6952 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:40:22.371  6952  6952 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 17:40:22.371  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:40:22.372  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 17:40:22.373  6952  6952 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 17:40:22.374  6952  6952 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 17:40:22.378  1032  2856 D DhcpStateMachine: StoppedState
08-25 17:40:22.378  1032  2856 D DhcpStateMachine: StoppedState{ when=-56ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:40:22.379  1032  1398 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 17:40:22.379  1032  1398 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 17:40:22.385  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:40:22.386  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.386  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.387  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:22.387  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:22.387  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.404  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-25 17:40:22.404  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:22.405  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.406  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.409  6934  6934 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 17:40:22.409  6934  6934 W LG Account v2.2: No ProfileInfo entries
08-25 17:40:22.409  6934  6934 I LG Account v2.2: isEnabled: false
08-25 17:40:22.409  6934  6934 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 17:40:22.409  6934  6934 I Feature : [Lifetracker]Country: EU
08-25 17:40:22.409  6934  6934 I Feature : [Lifetracker]Operator: OPEN
08-25 17:40:22.409  6934  6934 I Feature : [Lifetracker]Ranking support: false
08-25 17:40:22.410  6934  6934 I Feature : [Lifetracker]Comfort support: false
08-25 17:40:22.410  6934  6934 I Feature : [Lifetracker]Accessory: true
08-25 17:40:22.410  6934  6934 I Feature : [Lifetracker]Health device: true
08-25 17:40:22.410  6934  6934 I Feature : [Lifetracker]Extra Pedometer: false
08-25 17:40:22.410  6934  6934 I Feature : [Lifetracker]Blood glucose device: false
08-25 17:40:22.410  6934  6934 I Feature : [Lifetracker]Device Number: 3
08-25 17:40:22.416  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:22.422  2736  2736 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 17:40:22.422  2736  2736 I wpa_supplicant: monitor socket send errors count : 1
08-25 17:40:22.422  2736  2736 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1938-2\x00 that cannot receive messages
,08-25 17:40:22.424  1032  2766 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 17:40:22.424  1032  2766 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 17:40:22.452  1032  1047 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6973 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 17:40:22.454  1032  1047 I ActivityManager: Killing 6266:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-25 17:40:22.461  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:40:22.461  1032  2766 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 17:40:22.461  1032  2766 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:40:22.461  1032  2766 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:40:22.462  1032  2766 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 17:40:22.462  2736  2736 W wpa_supplicant: USIM:  scard_deinit function
08-25 17:40:22.463  1032  1094 D Tethering: InitialState.processMessage what=4
08-25 17:40:22.464  1032  1398 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=184180
08-25 17:40:22.464  1032  1398 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=184181
08-25 17:40:22.462  1032  2766 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:40:22.465  1032  2766 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:40:22.466  1032  1398 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=184182  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 17:40:22.466  1032  1398 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=184183  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 17:40:22.470   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 16.649ms
,08-25 17:40:22.483   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 11.898ms
,08-25 17:40:22.495   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 224us total 11.761ms
,08-25 17:40:22.514  1032  1991 W libprocessgroup: failed to open /acct/uid_10014/pid_6266/cgroup.procs: No such file or directory
08-25 17:40:22.514  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 17:40:22.529  1032  1398 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:22.529  1032  1398 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:22.556  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 17:40:22.568  3861  3861 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:40:22.568  3861  3861 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.568  3861  3861 V BluetoothPbapReceiver: ***********state = 13
08-25 17:40:22.571  3861  3861 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 17:40:22.574  3861  3861 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.574  3861  3861 V BluetoothPbapService: state: 13
08-25 17:40:22.574  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 17:40:22.574  3861  3861 V BluetoothPbapService: Pbap Service closeService in
08-25 17:40:22.575  3861  3861 V BluetoothPbapService: successfully stopped pbap service
08-25 17:40:22.575  3861  3861 V BluetoothPbapService: Pbap Service closeService out
08-25 17:40:22.576  1032  1094 D BluetoothManagerService: Message: 20
08-25 17:40:22.576  3861  3861 V BluetoothPbapService: Pbap Service onDestroy
08-25 17:40:22.576  3861  3861 V BluetoothPbapService: Pbap Service closeService in
08-25 17:40:22.576  3861  3861 V BluetoothPbapService: Pbap Service closeService out
08-25 17:40:22.576  3861  3861 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 17:40:22.576  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ca18895:true
08-25 17:40:22.579  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:22.580  1032  2766 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 17:40:22.580  1032  2766 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 17:40:22.581  1032  2766 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 17:40:22.582  1032  1398 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 17:40:22.592  1032  1094 D BluetoothManagerService: Message: 30
,08-25 17:40:22.598  1032  1094 D BluetoothManagerService: Message: 30
08-25 17:40:22.599  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:40:22.600  6952  6952 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 17:40:22.602  6952  6952 D BluetoothMap: Create BluetoothMap proxy object
08-25 17:40:22.603  1032  1094 D BluetoothManagerService: Message: 30
08-25 17:40:22.603  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-25 17:40:22.608  1032  1094 D BluetoothManagerService: Message: 30
08-25 17:40:22.608  6846  6846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 17:40:22.608  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:22.610  6952  6952 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 17:40:22.611  1032  1919 I ActivityManager: Killing 6366:com.android.defcontainer/u0a4 (adj 15): empty #17
08-25 17:40:22.611  6952  6952 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 17:40:22.634  1032  1048 W libprocessgroup: failed to open /acct/uid_10004/pid_6366/cgroup.procs: No such file or directory
,08-25 17:40:22.638  6952  6952 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 17:40:22.641  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 17:40:22.653  6952  6952 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:40:22.664  6952  6952 D BluetoothInputDevice: Proxy object connected
08-25 17:40:22.664  6952  6952 D HidProfile: Bluetooth service connected
08-25 17:40:22.666  6952  6952 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:40:22.666  6952  6952 D PanProfile: Bluetooth service connected
,08-25 17:40:22.667  6952  6952 D BluetoothMap: Proxy object connected
08-25 17:40:22.668  6952  6952 D MapProfile: Bluetooth service connected
08-25 17:40:22.668  6952  6952 D BluetoothMap: getConnectedDevices()
08-25 17:40:22.669  6952  6952 D BluetoothMap: Bluetooth is Not enabled
08-25 17:40:22.680  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:22.683  1032  1398 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 17:40:22.683  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:22.683  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:22.683  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:22.685  1938  1938 D WfdsService: Supplicant Connection state is changed : false
08-25 17:40:22.685  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:22.685  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:40:22.686  1938  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 17:40:22.686  1938  2326 D WfdsService: Set the WFDS Monitor: false
08-25 17:40:22.686  1938  2326 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:40:22.686  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 17:40:22.686  1032  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 17:40:22.686  1032  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 17:40:22.689  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.691  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:22.691  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:22.724  6952  6952 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:40:22.724  6952  6952 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 17:40:22.734  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:22.735  6952  6952 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 17:40:22.738  6952  6952 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 17:40:22.744  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:22.746  6952  6952 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 17:40:22.751  1032  1898 I ActivityManager: Killing 6539:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-25 17:40:22.755  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:40:22.794  1032  1573 W libprocessgroup: failed to open /acct/uid_10008/pid_6539/cgroup.procs: No such file or directory
08-25 17:40:22.795  3861  3861 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 17:40:22.796  3861  3861 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 17:40:22.797  3861  3861 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-25 17:40:22.880  1032  1919 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7001 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 17:40:22.881  3861  3861 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.883  3861  3861 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:40:22.887  3861  3861 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:40:22.887  3861  3861 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.888  3861  3861 V BluetoothFtpService: Ftp Service closeService
08-25 17:40:22.888  3861  3861 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 17:40:22.888  3861  3861 V BluetoothFtpService: successfully stopped ftp service
08-25 17:40:22.889  3861  3861 V BluetoothFtpService: Ftp Service onDestroy
08-25 17:40:22.889  3861  3861 V BluetoothFtpService: Ftp Service closeService
08-25 17:40:22.892  3861  3861 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:22.892  3861  3861 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:22.892  3861  3861 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:22.892  3861  3861 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.892  3861  3861 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 17:40:22.892  3861  3861 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:40:22.894  3861  3861 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:22.894  3861  3861 V BluetoothSapService: state: 13
08-25 17:40:22.894  3861  3861 V BluetoothSapService: Stopping SAP server process
08-25 17:40:22.895  3861  3861 V BluetoothSapService: Sap Service closeSapService in
08-25 17:40:22.896  3861  3861 V BluetoothSapService: Close listen Socket : 
08-25 17:40:22.896  3861  3861 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:40:22.896  3861  3861 V BluetoothSapService: Close sapd  Socket : 
,08-25 17:40:22.954  1032  1919 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7021 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 17:40:22.955  3861  3861 V BluetoothSapService: Sap Service closeSapService out
08-25 17:40:22.955  3861  3861 V BluetoothSapService: Sap Service onDestroy
08-25 17:40:22.955  3861  3861 V BluetoothSapService: Sap Service closeSapService in
08-25 17:40:22.955  3861  3861 V BluetoothSapService: Close listen Socket : 
08-25 17:40:22.955  3861  3861 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:40:22.955  3861  3861 V BluetoothSapService: Close sapd  Socket : 
08-25 17:40:22.956  3861  3861 V BluetoothSapService: Sap Service closeSapService out
08-25 17:40:22.980  7001  7001 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:40:23.003  7001  7001 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 17:40:23.029  7021  7021 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:40:23.037  7001  7001 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 17:40:23.037  7001  7001 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 17:40:23.038  7001  7001 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 17:40:23.038  7001  7001 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 17:40:23.038  7001  7001 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 17:40:23.040  7001  7001 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-25 17:40:23.047  1032  1898 I ActivityManager: Killing 6014:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 17:40:23.050  7001  7001 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 17:40:23.077  1032  1919 W libprocessgroup: failed to open /acct/uid_10011/pid_6014/cgroup.procs: No such file or directory
,08-25 17:40:23.089  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:23.093  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:40:23.122  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:40:23.126  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:23.126  7001  7001 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 17:40:23.131  7001  7001 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 17:40:23.131  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:40:23.131  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:40:23.132  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:23.137  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:23.145  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:23.155  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:23.155  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:40:23.157  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:40:23.160  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:23.163  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:40:23.163  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:40:23.163  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:23.167  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:23.175  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:40:23.185  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:23.185  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:23.187  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:40:23.205  3861  4055 W bt-btif : ag scb idx 1 not allocated
08-25 17:40:23.205  3861  4055 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 17:40:23.205  3861  3948 D bt_hci_bdroid: cleanup
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:23.205  3861  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:23.205  3861  4055 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 17:40:23.205  3861  4178 I bt_userial_mct: exiting userial_read_thread
08-25 17:40:23.205  3861  4178 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 17:40:23.206  3861  3948 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 17:40:23.206  3861  4057 I bt_lpm  : LPM is already off!!!
08-25 17:40:23.206  3861  4057 I bt_vendor: hw_epilog_process
,08-25 17:40:23.207  3861  3948 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 17:40:23.207  3861  3948 D bt_userial_mct: userial_close
08-25 17:40:23.207  3861  3948 E bt_userial_mct: pthread_join() FAILED result:3
08-25 17:40:23.207  3861  3948 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 17:40:23.247  1032  1914 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7042 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 17:40:23.272  3861  3948 D bt_hci_bdroid: set_power 0
,08-25 17:40:23.272  3861  3948 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 17:40:23.272  3861  3948 I bt_vendor: bluetooth satus is on
08-25 17:40:23.272  3861  3948 I bt_vendor: bt-vendor : resetting BT status
08-25 17:40:23.272  3861  3948 I bt_vendor: Starting hciattach daemon
08-25 17:40:23.272  3861  3948 I bt_vendor: try to set false
08-25 17:40:23.274  3861  3948 I bt_vendor: Starting hciattach daemon
08-25 17:40:23.274  3861  3948 I bt_vendor: try to set false
08-25 17:40:23.276  3861  3948 I bt_vendor: cleanup
08-25 17:40:23.277  3861  4055 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 17:40:23.278  3861  3948 I GKI_LINUX: GKI_exit_task 0 done
08-25 17:40:23.278  3861  3948 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 17:40:23.280  3861  3943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 17:40:23.284  3861  3861 D HeadsetService: Received stop request...Stopping profile...
08-25 17:40:23.285  3861  3861 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:40:23.285  3861  3861 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 17:40:23.285  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.286  3861  3987 D HeadsetStateMachine: Exit Disconnected: -1
08-25 17:40:23.289  1032  1032 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:23.289  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 17:40:23.290  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:23.290  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:23.290  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:23.293  3861  3861 D A2dpService: Received stop request...Stopping profile...
08-25 17:40:23.295  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 17:40:23.297  3861  4031 D A2dpStateMachine: Exit Disconnected: -1
,08-25 17:40:23.301  3861  3943 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 17:40:23.301  3861  3861 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
,08-25 17:40:23.301  3861  3861 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:40:23.301  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.304  1032  1032 D BluetoothA2dp: Proxy object disconnected
08-25 17:40:23.304  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 17:40:23.306  3861  3861 D HidService: Received stop request...Stopping profile...
08-25 17:40:23.306  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.307  3861  3861 D HeadsetStateMachine: Unbinding service...
08-25 17:40:23.307  6952  6952 D BluetoothInputDevice: Proxy object disconnected
08-25 17:40:23.308  3861  3861 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:40:23.308  3861  3861 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:40:23.308  3861  3861 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:40:23.308  3861  3861 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:40:23.308  3861  3861 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:40:23.308  3861  3861 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:40:23.308  3861  3861 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:40:23.309  3861  3861 D HealthService: Received stop request...Stopping profile...
08-25 17:40:23.309  6952  6952 D HidProfile: Bluetooth service disconnected
08-25 17:40:23.309  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.310  3861  3861 D PanService: Received stop request...Stopping profile...
,08-25 17:40:23.311  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.312  3861  3861 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:40:23.313  3861  3861 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 17:40:23.313  3861  3861 D BtGatt.GattService: stop()
08-25 17:40:23.313  3861  3861 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 17:40:23.314  6952  6952 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:40:23.314  6952  6952 D PanProfile: Bluetooth service disconnected
08-25 17:40:23.314  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.315  3861  3861 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:40:23.315  3861  3861 D BluetoothMapService: stop()
08-25 17:40:23.316  3861  3861 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 17:40:23.316  3861  3861 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 17:40:23.317  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d5757
08-25 17:40:23.318  3861  3861 I BluetoothA2dpServiceJni: cleanupNative
,08-25 17:40:23.319  3861  4035 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 17:40:23.319  6952  6952 D BluetoothMap: Proxy object disconnected
08-25 17:40:23.319  6952  6952 D MapProfile: Bluetooth service disconnected
08-25 17:40:23.319  3861  3861 I GKI_LINUX: GKI_exit_task 2 done
,08-25 17:40:23.319  3861  3861 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 17:40:23.319  3861  3861 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:40:23.319  3861  3861 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:40:23.320  3861  3861 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:40:23.320  3861  3861 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:40:23.320  3861  3861 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-25 17:40:23.320  3861  3861 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:40:23.320  3861  3861 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:40:23.322  3861  3861 V BluetoothMapService: Handler(): got msg=4
08-25 17:40:23.322  3861  3861 D BluetoothMapService: MAP Service closeService in
08-25 17:40:23.322  3861  3861 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
,08-25 17:40:23.322  3861  3861 V BluetoothMapService: MAP Service closeService out
08-25 17:40:23.322  3861  3943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 17:40:23.322  3861  3943 D BluetoothAdapterProperties: Setting state to 10
08-25 17:40:23.322  3861  3943 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 17:40:23.323  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:23.323  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,08-25 17:40:23.323  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 17:40:23.323  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:23.324  3861  3943 I BluetoothAdapterState: Entering OffState
08-25 17:40:23.324  3861  3861 D BluetoothMapService: cleanup()
08-25 17:40:23.324  3861  3861 D BluetoothMapService: MAP Service closeService in
,08-25 17:40:23.325  3861  3861 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:40:23.325  3861  3861 V BluetoothMapService: MAP Service closeService out
08-25 17:40:23.326  6952  6968 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:40:23.327  1849  2744 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:23.329  6952  6967 D BluetoothPan: onBluetoothStateChange on: false
08-25 17:40:23.330  6952  6968 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:40:23.331  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:23.331  1849  2436 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:23.332  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:40:23.332  6952  6967 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:40:23.333  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 17:40:23.333  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 17:40:23.335  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 17:40:23.336  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 17:40:23.336  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2192b652 mBinding = false
08-25 17:40:23.336  1032  1094 D BluetoothManagerService: Sending unbind request.
,08-25 17:40:23.337  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 17:40:23.339  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:23.339  1938  2146 D LGBluetoothAPIService: Message: 2
08-25 17:40:23.339  1938  2146 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3e34ffa6 mBinding = false
08-25 17:40:23.339  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:23.340  1938  2146 D LGBluetoothAPIService: Sending unbind request.
,08-25 17:40:23.343  6952  6952 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:40:23.344  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 17:40:23.344  6952  6952 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 17:40:23.344  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:23.345  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:23.349  3861  3948 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 17:40:23.350  3861  3861 I GKI_LINUX: GKI_exit_task 1 done
08-25 17:40:23.350  3861  3861 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 17:40:23.351  3861  3861 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 17:40:23.352  3861  3861 I art     : --- WEIRD: removing null entry 246
08-25 17:40:23.352  3861  3861 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 17:40:23.352  3861  3861 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 17:40:23.352  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:40:23.353  3861  3861 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 17:40:23.356  3861  3861 I art     : System.exit called, status: 0
08-25 17:40:23.356  3861  3861 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 17:40:23.362  1600  1600 D BluetoothAdapter: 444109007: getState() :  mService = null. Returning STATE_OFF
08-25 17:40:23.362  1600  1600 D BluetoothAdapter: 444109007: getState() :  mService = null. Returning STATE_OFF
08-25 17:40:23.364  6952  6952 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:40:23.377   314   314 V AudioFlinger: 3861 died, releasing its sessions
08-25 17:40:23.377   314   314 V AudioFlinger:  pid 1849 @ 0
08-25 17:40:23.377   314   314 V AudioFlinger:  pid 3428 @ 1
08-25 17:40:23.377   314   314 V AudioFlinger:  pid 3428 @ 2
08-25 17:40:23.378  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:23.378  6952  6952 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 17:40:23.411  1032  1992 I ActivityManager: Process com.android.bluetooth (pid 3861) has died
,08-25 17:40:23.412  1032  1992 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-25 17:40:23.418  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:40:23.419  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:23.424  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:40:23.436  7042  7067 W FormManager: Network not available. Please check & try again.
08-25 17:40:23.450  7042  7068 V FormManager: Network unavailable.
,08-25 17:40:23.460  7042  7068 V FormManager: Network unavailable.
08-25 17:40:23.465  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:23.469  6952  6952 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-25 17:40:23.469  6952  6952 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 17:40:23.478  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:40:23.478  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-25 17:40:23.479  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:40:23.479  6952  6952 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:40:23.480  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:40:23.493  6952  6952 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:40:23.493  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 17:40:23.493  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:40:23.493  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:40:23.494  6952  6952 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:40:23.494  6952  6952 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:40:23.494  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 17:40:23.567  1032  1573 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7073 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 17:40:23.570  1032  1573 I ActivityManager: Killing 6037:com.android.contacts/u0a19 (adj 15): empty #17
,08-25 17:40:23.616  1032  1047 W libprocessgroup: failed to open /acct/uid_10019/pid_6037/cgroup.procs: No such file or directory
,08-25 17:40:23.617  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:23.619  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:40:23.624  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:23.629  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:40:23.651  4341  7090 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:40:23.656  4341  7091 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:23.656  4341  7091 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:40:23.657  6973  6973 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 17:40:23.657  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:40:23.657  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:23.662  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:40:23.662  7073  7073 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 17:40:23.663  7073  7073 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:40:23.664  7073  7073 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-25 17:40:23.665  7073  7073 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 17:40:23.675  7042  7093 W FormManager: Network not available. Please check & try again.
08-25 17:40:23.678  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:40:23.686  7073  7073 D BluetoothAdapterApp: Loading JNI Library
,08-25 17:40:23.693  7042  7094 V FormManager: Network unavailable.
,08-25 17:40:23.696  7042  7094 V FormManager: Network unavailable.
,08-25 17:40:23.705  7001  7001 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 17:40:23.706  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 17:40:23.706  7001  7001 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 17:40:23.723  7073  7073 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@309d09ac Instance Count = 1
,08-25 17:40:23.728  7073  7073 D BluetoothAdapterApp: onCreate
08-25 17:40:23.745  7001  7001 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:40:23.745  7001  7001 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:40:23.756  7073  7073 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 17:40:23.757  7073  7073 D ProfileConfigQcom: Adding HeadsetService
08-25 17:40:23.757  7073  7073 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 17:40:23.758  7073  7073 D ProfileConfigQcom: Adding A2dpService
08-25 17:40:23.758  7001  7001 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 17:40:23.758  7073  7073 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 17:40:23.759  7073  7073 D ProfileConfigQcom: Adding HidService
08-25 17:40:23.759  7073  7073 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 17:40:23.760  7073  7073 D ProfileConfigQcom: Adding HealthService
08-25 17:40:23.760  7001  7001 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 17:40:23.760  7001  7001 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 17:40:23.760  7001  7001 V SoundPool: doLoad: loading sample sampleID=1
08-25 17:40:23.761  7073  7073 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 17:40:23.761  7001  7098 V SoundPool: Start decode
08-25 17:40:23.761  7001  7098 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 17:40:23.762  7073  7073 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 17:40:23.763  7001  7001 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 17:40:23.763  7073  7073 D ProfileConfigQcom: Adding PanService
08-25 17:40:23.763   314  2121 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 17:40:23.763   314  2121 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 17:40:23.763   314  2121 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 17:40:23.763   314  2121 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 17:40:23.764   314  2121 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 17:40:23.764   314  2121 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 17:40:23.764   314  2121 V MediaPlayerService: player type = 3
08-25 17:40:23.764   314  2121 V AwesomePlayer: AwesomePlayer create()
08-25 17:40:23.764  7073  7073 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 17:40:23.764   314  2121 V AwesomePlayer: reset_l() 
08-25 17:40:23.764   314  2121 V AwesomePlayer: cancelPlayerEvents
08-25 17:40:23.764   314  2121 V AwesomePlayer: setAudioSink() 
08-25 17:40:23.764   314  2121 V AwesomePlayer: reset_l() 
08-25 17:40:23.764   314  2121 V AudioCache: notify(0xb5474d00, 8, 0, 0)
08-25 17:40:23.764   314  2121 V AudioCache: ignored
08-25 17:40:23.764   314  2121 V AwesomePlayer: cancelPlayerEvents
08-25 17:40:23.764   314  2121 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 17:40:23.764   314  2121 V AwesomePlayer: setDataSource_l dataSource
08-25 17:40:23.764   314  2121 V LGParserOSAL: SniffLGParser start
08-25 17:40:23.764   314  2121 V LGParserOSAL: MainType:5, SubType=0
08-25 17:40:23.764   314  2121 V LGParserOSAL: #### check Mime : application/ogg
08-25 17:40:23.764  7073  7073 D ProfileConfigQcom: Adding GattService
08-25 17:40:23.764   314  2121 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 17:40:23.765   314  2121 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 17:40:23.765  7073  7073 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-25 17:40:23.765  7073  7073 D ProfileConfigQcom: Adding BluetoothMapService
08-25 17:40:23.766  7073  7073 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 17:40:23.770  7073  7073 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 17:40:23.776  6710  6710 D UEI.SmartControl: QS Service created
08-25 17:40:23.778  6952  6952 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 17:40:23.779  7001  7001 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 17:40:23.781  7073  7073 V LGMDMManagerInternal: Create singleton instance
08-25 17:40:23.782  7001  7001 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 17:40:23.782  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-25 17:40:23.795  6710  6710 I UEI.SmartControl: Service initServices...
08-25 17:40:23.795  6710  6710 D UEI.SmartControl: QS start get config
08-25 17:40:23.798  7001  7001 V LGMDMManager: Create singleton instance
,08-25 17:40:23.808   314  2121 V LGParserOSAL: supported mime: application/ogg
08-25 17:40:23.808   314  2121 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 17:40:23.808   314  2121 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 17:40:23.808   314  2121 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 17:40:23.808   314  2121 V AwesomePlayer: AudioTrack Setting
08-25 17:40:23.808   314  2121 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 17:40:23.808   314  2121 V AwesomePlayer: setAudioSource() 
08-25 17:40:23.808   314  2121 V MediaPlayerService: prepare
08-25 17:40:23.808   314  2121 V AwesomePlayer: prepareAsync_l() 
08-25 17:40:23.808   314  2121 V MediaPlayerService: wait for prepare
08-25 17:40:23.809   314  7099 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 17:40:23.809   314  7099 V AwesomePlayer: initAudioDecoder() 
08-25 17:40:23.809   314  7099 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 17:40:23.809   314  7099 V AudioSystem: isOffloadSupported()
08-25 17:40:23.809   314  7099 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 17:40:23.810   314  7099 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 17:40:23.810   314  7099 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:40:23.810   314  7099 V AwesomePlayer: getUseOffload() = 0 
08-25 17:40:23.810   314  7099 V OMXCodec: OMXCodec::Create
08-25 17:40:23.810   314  7099 V OMXCodec: findMatchingCodecs()
08-25 17:40:23.810   314  7099 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 17:40:23.810   314  7099 V OMXCodec: matchingCodecs.size()=1
08-25 17:40:23.810   314  7099 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 17:40:23.812   314  7099 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 17:40:23.812   314  7099 V LGCodecAdapter: LG Codec Adapter start
08-25 17:40:23.812   314  7099 V OMXCodec: OMXCodec Createtor
08-25 17:40:23.812   314  7099 V OMXCodec: setComponentRole
08-25 17:40:23.812   314  7099 V OMXCodec: configureCodec protected=0
08-25 17:40:23.813   314  7099 V LGCodecAdapter: called getLGCodecSpecificData
08-25 17:40:23.813   314  7099 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 17:40:23.813   314  7099 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 17:40:23.813   314  7099 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 17:40:23.813   314  7099 V LGCodecOSAL: Not support LGCodec
08-25 17:40:23.813   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 17:40:23.813   314  7099 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 17:40:23.813   314  7099 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 17:40:23.813   314  7099 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 17:40:23.813   314  7099 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 17:40:23.813   314  7099 V AudioSystem: isOffloadSupported()
08-25 17:40:23.813   314  7099 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 17:40:23.813   314  7099 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 17:40:23.813   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 17:40:23.813   314  7099 V OMXCodec: init()
08-25 17:40:23.813   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-25 17:40:23.813   314  7099 V OMXCodec: allocateBuffers
08-25 17:40:23.813   314  7099 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 17:40:23.813   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 17:40:23.813   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-25 17:40:23.814   314  7099 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-25 17:40:23.814   314  7099 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-25 17:40:23.814   314  7099 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 17:40:23.814   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 17:40:23.814   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 17:40:23.814   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 17:40:23.814   314  7099 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 17:40:23.814   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 17:40:23.814   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 17:40:23.814   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 17:40:23.814   314  7099 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 17:40:23.814   314  7099 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 17:40:23.814   314  7099 V AudioCache: notify(0xb5474d00, 5, 0, 0)
08-25 17:40:23.814   314  7099 V AudioCache: ignored
08-25 17:40:23.814   314  7099 V AudioCache: notify(0xb5474d00, 1, 0, 0)
08-25 17:40:23.814   314  7099 V AudioCache: prepared
08-25 17:40:23.814   314  2121 V AudioCache: wait - success
08-25 17:40:23.815   314  2121 V MediaPlayerService: start
08-25 17:40:23.815   314  2121 V AwesomePlayer: play_l() 
08-25 17:40:23.815   314  2121 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
,08-25 17:40:23.815   314  2121 V AwesomePlayer: createAudioPlayer_l
08-25 17:40:23.815   314  2121 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 17:40:23.815   314  2121 V AwesomePlayer: startAudioPlayer_l() 
08-25 17:40:23.815   314  2121 D AudioPlayer: start of Playback, useOffload 0
08-25 17:40:23.815   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 17:40:23.815   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 17:40:23.817   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 17:40:23.817   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 17:40:23.817   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 17:40:23.817   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-25 17:40:23.817   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 17:40:23.817   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
,08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 17:40:23.818   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 17:40:23.819   314  7101 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
,08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 17:40:23.819   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 17:40:23.821   314  2121 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 17:40:23.821   314  2121 V AudioCache: notify(0xb5474d00, 6, 0, 0)
08-25 17:40:23.821   314  2121 V AudioCache: ignored
,08-25 17:40:23.828   314  2121 V MediaPlayerService: wait for playback complete,
08-25 17:40:23.828   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.828   314  7102 V AudioCache: memcpy(0xaf004000, 0xb16f2000, 4096)
08-25 17:40:23.831   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.831   314  7102 V AudioCache: memcpy(0xaf005000, 0xb16f2000, 4096)
08-25 17:40:23.832   314  7102 V AudioCache: write(0xb16f2000, 4096)
,08-25 17:40:23.832   314  7102 V AudioCache: memcpy(0xaf006000, 0xb16f2000, 4096)
08-25 17:40:23.833   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.833   314  7102 V AudioCache: memcpy(0xaf007000, 0xb16f2000, 4096)
08-25 17:40:23.833   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.834   314  7102 V AudioCache: memcpy(0xaf008000, 0xb16f2000, 4096)
08-25 17:40:23.834   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.834   314  7102 V AudioCache: memcpy(0xaf009000, 0xb16f2000, 4096)
08-25 17:40:23.835   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.835   314  7102 V AudioCache: memcpy(0xaf00a000, 0xb16f2000, 4096)
08-25 17:40:23.835   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.835   314  7102 V AudioCache: memcpy(0xaf00b000, 0xb16f2000, 4096)
08-25 17:40:23.836   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.836   314  7102 V AudioCache: memcpy(0xaf00c000, 0xb16f2000, 4096)
08-25 17:40:23.836   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.837   314  7102 V AudioCache: memcpy(0xaf00d000, 0xb16f2000, 4096)
08-25 17:40:23.837   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.837   314  7102 V AudioCache: memcpy(0xaf00e000, 0xb16f2000, 4096)
08-25 17:40:23.838   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.838   314  7102 V AudioCache: memcpy(0xaf00f000, 0xb16f2000, 4096)
08-25 17:40:23.838   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.838   314  7102 V AudioCache: memcpy(0xaf010000, 0xb16f2000, 4096)
08-25 17:40:23.839   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.839   314  7102 V AudioCache: memcpy(0xaf011000, 0xb16f2000, 4096)
08-25 17:40:23.839   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.839   314  7102 V AudioCache: memcpy(0xaf012000, 0xb16f2000, 4096)
08-25 17:40:23.839   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.839   314  7102 V AudioCache: memcpy(0xaf013000, 0xb16f2000, 4096)
08-25 17:40:23.840   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.840   314  7102 V AudioCache: memcpy(0xaf014000, 0xb16f2000, 4096)
08-25 17:40:23.841   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.841   314  7102 V AudioCache: memcpy(0xaf015000, 0xb16f2000, 4096)
08-25 17:40:23.841   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.841   314  7102 V AudioCache: memcpy(0xaf016000, 0xb16f2000, 4096)
08-25 17:40:23.841   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.841   314  7102 V AudioCache: memcpy(0xaf017000, 0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: memcpy(0xaf018000, 0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: memcpy(0xaf019000, 0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: memcpy(0xaf01a000, 0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.854   314  7102 V AudioCache: memcpy(0xaf01b000, 0xb16f2000, 4096)
,08-25 17:40:23.857   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.857   314  7102 V AudioCache: memcpy(0xaf01c000, 0xb16f2000, 4096)
08-25 17:40:23.857   314  7102 V AudioCache: write(0xb16f2000, 4096)
,08-25 17:40:23.857   314  7102 V AudioCache: memcpy(0xaf01d000, 0xb16f2000, 4096)
08-25 17:40:23.857   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.857   314  7102 V AudioCache: memcpy(0xaf01e000, 0xb16f2000, 4096)
08-25 17:40:23.857   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.857   314  7102 V AudioCache: memcpy(0xaf01f000, 0xb16f2000, 4096)
08-25 17:40:23.859   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.859   314  7102 V AudioCache: memcpy(0xaf020000, 0xb16f2000, 4096)
08-25 17:40:23.859   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.859   314  7102 V AudioCache: memcpy(0xaf021000, 0xb16f2000, 4096)
08-25 17:40:23.859   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.859   314  7102 V AudioCache: memcpy(0xaf022000, 0xb16f2000, 4096)
08-25 17:40:23.860   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.860   314  7102 V AudioCache: memcpy(0xaf023000, 0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: memcpy(0xaf024000, 0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: memcpy(0xaf025000, 0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: memcpy(0xaf026000, 0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.862   314  7102 V AudioCache: memcpy(0xaf027000, 0xb16f2000, 4096)
08-25 17:40:23.862  7073  7073 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:23.864  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 17:40:23.864   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.864   314  7102 V AudioCache: memcpy(0xaf028000, 0xb16f2000, 4096)
08-25 17:40:23.864   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.864   314  7102 V AudioCache: memcpy(0xaf029000, 0xb16f2000, 4096)
08-25 17:40:23.865  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 17:40:23.866  7073  7073 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:23.867  7073  7073 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:23.867  7073  7073 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:23.867   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.867   314  7102 V AudioCache: memcpy(0xaf02a000, 0xb16f2000, 4096)
08-25 17:40:23.868  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1066
08-25 17:40:23.868   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.868   314  7102 V AudioCache: memcpy(0xaf02b000, 0xb16f2000, 4096)
08-25 17:40:23.868   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.868   314  7102 V AudioCache: memcpy(0xaf02c000, 0xb16f2000, 4096)
08-25 17:40:23.869   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.869   314  7102 V AudioCache: memcpy(0xaf02d000, 0xb16f2000, 4096)
08-25 17:40:23.869   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.869   314  7102 V AudioCache: memcpy(0xaf02e000, 0xb16f2000, 4096)
08-25 17:40:23.869  7073  7073 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:23.869  7073  7073 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 17:40:23.870   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.870   314  7102 V AudioCache: memcpy(0xaf02f000, 0xb16f2000, 4096)
08-25 17:40:23.870   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.870   314  7102 V AudioCache: memcpy(0xaf030000, 0xb16f2000, 4096)
08-25 17:40:23.871   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.871   314  7102 V AudioCache: mem,cpy(0xaf031000, 0xb16f2000, 4096)
08-25 17:40:23.872   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.872   314  7102 V AudioCache: memcpy(0xaf032000, 0xb16f2000, 4096)
,08-25 17:40:23.873   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.873   314  7102 V AudioCache: memcpy(0xaf033000, 0xb16f2000, 4096)
08-25 17:40:23.874   314  7102 V AudioCache: write(0xb16f2000, 4096)
,08-25 17:40:23.874   314  7102 V AudioCache: memcpy(0xaf034000, 0xb16f2000, 4096)
08-25 17:40:23.874   314  7102 V AudioCache: write(0xb16f2000, 4096)
08-25 17:40:23.874   314  7102 V AudioCache: memcpy(0xaf035000, 0xb16f2000, 4096)
,08-25 17:40:23.874   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 17:40:23.874   314  7102 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 17:40:23.874   314  7102 V AwesomePlayer: postAudioEOS() 
08-25 17:40:23.874   314  7102 V AudioCache: write(0xb16f2000, 280)
08-25 17:40:23.874   314  7102 V AudioCache: memcpy(0xaf036000, 0xb16f2000, 280)
08-25 17:40:23.876   314  7099 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 17:40:23.876   314  7099 V AwesomePlayer: onStreamDone
08-25 17:40:23.876   314  7099 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 17:40:23.876   314  7099 V AudioCache: notify(0xb5474d00, 2, 0, 0)
08-25 17:40:23.876   314  7099 V AudioCache: playback complete
08-25 17:40:23.876   314  7099 V AwesomePlayer: pause_l() 
08-25 17:40:23.876   314  7099 V AudioCache: notify(0xb5474d00, 7, 0, 0)
08-25 17:40:23.876   314  7099 V AudioCache: ignored
08-25 17:40:23.876   314  7099 V AwesomePlayer: cancelPlayerEvents
08-25 17:40:23.876   314  2121 V AudioCache: wait - success
08-25 17:40:23.876   314  2121 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 17:40:23.876   314  7099 D AudioPlayer: Pause Playback at 1068125
08-25 17:40:23.876  7021  7021 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 17:40:23.876   314  2121 V AwesomePlayer: reset_l() 
08-25 17:40:23.876   314  2121 V AudioCache: notify(0xb5474d00, 8, 0, 0)
08-25 17:40:23.876   314  2121 V AudioCache: ignored
08-25 17:40:23.876   314  2121 V AwesomePlayer: cancelPlayerEvents
08-25 17:40:23.876   314  2121 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 17:40:23.876   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 17:40:23.876   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 17:40:23.876   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 17:40:23.876   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-25 17:40:23.877   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 17:40,:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 17:40:23.878   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 17:40:23.878   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 17:40:23.878   314  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 17:40:23.878   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 17:40:23.878   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 17:40:23.878   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 17:40:23.879   314  2121 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 17:40:23.879   314  2121 D AudioPlayer: AudioPlayer releasing audio source
08-25 17:40:23.879   314  2121 D AudioPlayer: AudioPlayer done releasing audio source
08-25 17:40:23.879   314  2121 V AwesomePlayer: reset_l() 
08-25 17:40:23.879   314  2121 V AwesomePlayer: cancelPlayerEvents
08-25 17:40:23.879   314  2121 V AwesomePlayer: ~AwesomePlayer call
08-25 17:40:23.879   314  2121 V AwesomePlayer: reset_l() 
08-25 17:40:23.879   314  2121 V AwesomePlayer: cancelPlayerEvents
08-25 17:40:23.880  7001  7098 V SoundPool: close(31)
08-25 17:40:23.880  7001  7098 V SoundPool: pointer = 0x9fe7f000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 17:40:24.083  6710  6710 I UEI.SmartControl: Supports setup maps: true
08-25 17:40:24.086  6710  6710 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 17:40:24.086  6710  6710 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 17:40:24.086  6710  6710 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 17:40:24.086  6710  6710 I UEI.SmartControl: ### init IR Blaster...
08-25 17:40:24.089  6710  6710 D serial_port: Configuring serial port
08-25 17:40:24.090  6710  6710 E UEI.SmartControl: UEIBLaster setting for 616
08-25 17:40:24.090  6710  6710 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 17:40:24.090  6710  6710 I UEI.SmartControl: configuring settings for MAXQ616
08-25 17:40:24.090  6710  6710 I UEI.SmartControl: Get version...
,08-25 17:40:24.109  6710  7104 D UEI.SmartControl: serial port data available: 21,
,08-25 17:40:24.135  6710  6710 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 17:40:24.135  6710  6710 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 17:40:24.135  6710  6710 I UEI.SmartControl: QS saving settings...
,08-25 17:40:24.137  6710  6710 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 17:40:24.154  6710  7104 D UEI.SmartControl: serial port data available: 4
,08-25 17:40:24.184  6710  7110 I UEI.SmartControl: Device manager: loading config....
,08-25 17:40:24.185  6710  7110 D UEI.SmartControl: ----------- loading internal config...
,08-25 17:40:24.186  6710  6710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 17:40:24.189  6710  6710 E UEI.SmartControl: Services init done
08-25 17:40:24.189  6710  6710 D UEI.SmartControl: QS Service init finished
08-25 17:40:24.191  6710  6710 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 17:40:24.191  6710  6710 D UEI.SmartControl: QS Service version code: 201091
08-25 17:40:24.192  6710  6710 D UEI.SmartControl: Service requested: Control
08-25 17:40:24.192  6710  7110 E UEI.SmartControl: Loading SETTINGS...
08-25 17:40:24.194  6710  6710 D UEI.SmartControl: Internal service binding...
08-25 17:40:24.195  7001  7001 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 17:40:24.197  6710  6726 I UEI.SmartControl: ------ IControl API: 11
,08-25 17:40:24.197  6710  6726 D UEI.SmartControl: File observer start...
08-25 17:40:24.198  6710  6726 E UEI.SmartControl: IR Port is disabled: false
08-25 17:40:24.198  6710  6726 D UEI.SmartControl: Starting file observer...
08-25 17:40:24.200  6710  6726 I UEI.SmartControl: Registering callback...
08-25 17:40:24.201  6710  6725 I UEI.SmartControl: ------ IControl API: 19
08-25 17:40:24.203  6710  6725 I UEI.SmartControl: Registering Services Ready callback...
,08-25 17:40:24.206  6710  7110 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 17:40:24.223  6710  7109 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 17:40:24.223  6710  7109 D UEI.SmartControl: -----service ready thread exits
,08-25 17:40:24.224  7001  7019 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 17:40:24.225  7001  7096 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 17:40:24.226  7001  7096 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-25 17:40:24.227  7001  7001 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 17:40:24.228  7001  7001 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 17:40:24.229  6710  6726 I UEI.SmartControl: ------ IControl API: 8
08-25 17:40:24.232  7001  7001 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 17:40:24.232  7001  7001 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 17:40:24.232  7001  7001 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 17:40:24.233  7001  7001 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 17:40:24.234  7001  7001 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 17:40:24.234  7001  7001 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-25 17:40:24.236  7001  7001 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 17:40:24.249  7001  7001 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 17:40:24.251  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 17:40:24.257  7001  7001 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 17:40:24.258  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 17:40:24.259  1600  1600 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-25 17:40:24.259  1600  1600 I [SystemUI]LGPowerUI: On Skip Timer : true
08-25 17:40:24.261  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 17:40:24.264  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-25 17:40:24.265  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 17:40:24.271  1938  2108 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-25 17:40:24.271  1938  2108 D LEDHandler: Battery Level Remaining: 100%
08-25 17:40:24.271  1938  2108 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
08-25 17:40:24.273  1600  1600 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
08-25 17:40:24.273  1032  1462 D WifiController: battery changed pluggedType: 2
08-25 17:40:24.273  1600  1600 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-25 17:40:24.274  7001  7001 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472139624273]
08-25 17:40:24.278  1600  1600 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-25 17:40:24.282  7001  7001 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 17:40:24.283  6688  6688 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-25 17:40:24.288  1032  1919 I ActivityManager: Killing 6060:com.android.gallery3d/u0a27 (adj 15): empty #17
08-25 17:40:24.311  7001  7112 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 17:40:24.323  1032  1919 I ActivityManager: Killing 6588:com.lge.email/u0a23 (adj 15): empty #18
08-25 17:40:24.378  1032  1992 W libprocessgroup: failed to open /acct/uid_10027/pid_6060/cgroup.procs: No such file or directory
,08-25 17:40:24.385  1032  1914 W libprocessgroup: failed to open /acct/uid_10023/pid_6588/cgroup.procs: No such file or directory
08-25 17:40:24.398  7001  7001 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-25 17:40:24.400  7001  7001 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 17:40:24.402  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 17:40:24.403  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 17:40:24.404  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 17:40:24.405  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 17:40:24.406  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 17:40:24.432  7001  7001 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 17:40:25.253  1032  1470 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:25.274  1032  1700 D WifiServiceImplEx: setWifiEnabled: true pid=6846, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:40:25.275  1032  1700 D WifiService: setWifiEnabled: true pid=6846, uid=10118
08-25 17:40:25.275  1032  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:40:25.282  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:25.282  1032  1094 D Tethering: MasterInitialState.processMessage what=3
08-25 17:40:25.298  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:25.302  1032  1470 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:25.302  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:25.306  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:40:25.306  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:25.306  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:25.307  1032  1398 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 17:40:25.307  1032  1398 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 17:40:25.311  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 17:40:25.312  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:40:25.312  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 17:40:25.312  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:40:25.312  1032  1398 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 17:40:25.312  1032  1398 E WifiHW  : unknown target_country: EU , set to default
08-25 17:40:25.312  1032  1398 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 17:40:25.312  1032  1398 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 17:40:25.312  1032  1398 I WifiUtil: gEnableBmps=1
,08-25 17:40:25.324  1032  1094 D Tethering: MasterInitialState.processMessage what=3
08-25 17:40:25.335  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:25.338  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:25.342  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 17:40:25.345  6488  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 17:40:25.355  5776  5776 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 17:40:25.365  5776  5776 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 17:40:25.384  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:25.412  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:25.448  1032  1920 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7134 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 17:40:25.455  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:25.457  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 17:40:25.501  7134  7134 I AppUp4:AppBoxCP: onCreate
,08-25 17:40:25.503  7134  7134 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-25 17:40:25.514  7134  7134 I AppUp4:DB:  setFingerPrint start
08-25 17:40:25.514  7134  7134 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 17:40:25.521  7134  7134 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 17:40:25.521  7134  7134 I AppUp4:DB:  SDK version = 21
08-25 17:40:25.522  7134  7134 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-25 17:40:25.523  7134  7134 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 17:40:25.525  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 17:40:25.525  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:25.527  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:40:25.528  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 17:40:25.535  7134  7134 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 17:40:25.573  7134  7134 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:40:25.573  7134  7134 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:40:25.581  7134  7134 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cf6f8d6
08-25 17:40:25.581  7134  7134 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:40:25.581  7134  7134 D AppUp4:CustFacade: isPhone : true
08-25 17:40:25.582  7134  7134 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:40:25.582  7134  7134 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 17:40:25.582  7134  7134 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 17:40:25.583  7134  7154 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 17:40:25.583  7134  7154 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 17:40:25.583  7134  7154 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 17:40:25.585  1032  1973 I ActivityManager: Killing 6620:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-25 17:40:25.646  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:25.647  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:40:25.647  1032  1573 W libprocessgroup: failed to open /acct/uid_10061/pid_6620/cgroup.procs: No such file or directory
08-25 17:40:25.652  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:40:25.660  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:25.665  4341  7156 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:40:25.670  4341  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:25.671  4341  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:40:25.743  1032  1047 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7162 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 17:40:25.815  7162  7162 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:40:25.815  7162  7162 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:40:25.817  7162  7162 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 17:40:25.817  7162  7162 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:40:25.915  7162  7162 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 17:40:25.932  7162  7162 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 17:40:25.966  7162  7162 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 17:40:25.993  7162  7162 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:40:25.993  7162  7162 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:40:26.072  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:40:26.080   307   892 D SoftapController: Softap fwReload - Ok
08-25 17:40:26.093  1032  1398 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (770ms)
08-25 17:40:26.097   307   892 D CommandListener: Setting iface cfg
08-25 17:40:26.097   307   892 D CommandListener: Trying to bring down wlan0
08-25 17:40:26.097   307   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:40:26.099  1032  1398 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 17:40:26.094  7193  7193 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:26.094  7193  7193 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:26.108  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:26.108  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:26.108  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:26.109  1032  1398 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 17:40:26.109  1032  1398 D WifiMonitor: connecting to supplicant
08-25 17:40:26.113  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:26.113  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 17:40:26.117  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-25 17:40:26.120  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:26.120  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:26.127  7193  7193 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 17:40:26.144  7193  7193 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 17:40:26.144  7193  7193 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-25 17:40:26.148  1032  1094 D Tethering: InitialState.processMessage what=4
08-25 17:40:26.149  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 17:40:26.198  7162  7162 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 17:40:26.209  7193  7193 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 17:40:26.229  7162  7162 I HubEmail: JNI_OnLoad()
08-25 17:40:26.229  7162  7162 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 17:40:26.229  7162  7162 I HubEmail: registerNatives()
08-25 17:40:26.229  7162  7162 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 17:40:26.229  7162  7162 I HubEmail: registerNativeMethods()
08-25 17:40:26.229  7162  7162 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 17:40:26.229  7162  7162 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-25 17:40:26.235  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-25 17:40:26.235  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:26.236  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 17:40:26.237  7162  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.238  7042  7204 W FormManager: Network not available. Please check & try again.
08-25 17:40:26.244  7193  7193 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 17:40:26.251  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:40:26.252  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 17:40:26.252  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:40:26.252  1032  1398 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:40:26.253  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:26.253  1032  1398 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:26.254  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:26.254  1032  1398 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:26.254  1032  1398 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 17:40:26.255  1032  1398 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 17:40:26.255  1032  1398 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 17:40:26.256  1032  1398 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 17:40:26.256  1032  1398 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 17:40:26.274  7193  7193 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-25 17:40:26.277  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:40:26.277  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:40:26.277  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 17:40:26.277  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 17:40:26.277  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:40:26.277  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:40:26.280  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 17:40:26.280  1032  1573 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7211 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-25 17:40:26.281  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 17:40:26.281  1032  7210 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 17:40:26.286  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:26.286  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:26.286  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:26.286  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.286  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.286  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.287  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.287  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:40:26.287  1032  1398 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 17:40:26.289  1032  1398 D WifiNative-wlan0: SET update_config 1: returned true
08-25 17:40:26.289  1032  1398 D WifiConfigStore: Loading config and enabling all networks 
08-25 17:40:26.289  1032  1398 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,08-25 17:40:26.290  1032  1398 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 17:40:26.290  1938  1938 D WfdService: Waiting for WifiP2p enabling
08-25 17:40:26.291  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 17:40:26.291  1032  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 17:40:26.292  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:26.293  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:26.293  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:26.293  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:26.293  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:26.294  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:26.294  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:26.294  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:26.294  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:26.301  1032  1398 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-25 17:40:26.304  7042  7206 V FormManager: Network unavailable.
08-25 17:40:26.306  7042  7206 V FormManager: Network unavailable.
08-25 17:40:26.312  1032  1898 I ActivityManager: Killing 6140:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-25 17:40:26.315  1032  1398 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 17:40:26.315  1032  1398 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 17:40:26.409  1032  1398 D WifiStateMachine: enableVerboseLogging : level 2
08-25 17:40:26.410  1032  1398 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-25 17:40:26.410  1032  1920 W libprocessgroup: failed to open /acct/uid_10080/pid_6140/cgroup.procs: No such file or directory
08-25 17:40:26.411  1032  1398 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 17:40:26.411  1032  1398 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 17:40:26.413  1032  1398 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 17:40:26.413  1032  1398 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 17:40:26.414  1032  1398 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 17:40:26.414  1032  1398 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 17:40:26.416  1032  1398 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 17:40:26.416  1032  1398 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 17:40:26.418  1032  1398 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 17:40:26.418  1032  1398 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-25 17:40:26.419  1032  1398 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 17:40:26.419  1032  1398 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 17:40:26.420  1032  1398 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 17:40:26.423  1938  1938 D WfdsService: Supplicant Connection state is changed : true
08-25 17:40:26.424  1938  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 17:40:26.424  1938  2326 D WfdsService: Set the WFDS Monitor: true
08-25 17:40:26.424  1938  2326 D WfdsMonitor: WfdsMonitorThread create
08-25 17:40:26.424  1938  2326 D WfdsMonitor: WFDS Monitor is created and started
08-25 17:40:26.424  1032  1398 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:40:26.425  1938  2326 D WfdsService: WiFi: Supplicant connection re-established
08-25 17:40:26.425  1032  1398 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 17:40:26.426  1032  1398 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 17:40:26.426  1032  1398 D WifiNative-HAL: Setting external_sim to 1
08-25 17:40:26.426  1032  1398 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-25 17:40:26.427  1032  1398 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 17:40:26.427  1938  7229 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 17:40:26.427  1032  1398 I WifiNative-HAL: startHal
08-25 17:40:26.427  1032  1398 D wifi    : setting scan oui 0x95366240
08-25 17:40:26.428  1032  1398 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:40:26.428  1938  7229 E CtrlSupplicant: Succeed to open control connection
08-25 17:40:26.428  1032  1398 I WifiNative-HAL: startHal
08-25 17:40:26.428  1032  1398 D wifi    : setting scan oui 0x95366240
08-25 17:40:26.429  1938  7229 E CtrlSupplicant: Succeed to open monitor connection
08-25 17:40:26.429  1938  7229 D WfdsMonitor: Supplicant connection established
08-25 17:40:26.429  1032  1398 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 17:40:26.430  1938  2326 D WfdsService: Connected to the supplicant for wfds
08-25 17:40:26.431  1032  1398 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 17:40:26.431  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 17:40:26.431  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 17:40:26.432  1032  1398 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 17:40:26.432  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:40:26.433  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:40:26.433  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:40:26.434  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,08-25 17:40:26.434  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 17:40:26.435  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 17:40:26.435  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:40:26.435  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:40:26.436  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:40:26.436  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:40:26.437  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:40:26.437  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:40:26.437  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 17:40:26.438  7193  7193 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 17:40:26.438  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 17:40:26.438  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:40:26.439  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:40:26.440  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:40:26.442  1032  1398 E WifiNative: : [188,156,934 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 17:40:26.442  1032  1398 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 17:40:26.442  1032  1398 D WifiNative-wlan0: RECONNECT: returned true
08-25 17:40:26.442  1032  1398 D WifiNative-wlan0: doString: [STATUS]
08-25 17:40:26.443  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:40:26.443  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:40:26.443  1032  1398 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 17:40:26.443  1032  1398 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:40:26.444  1032  1398 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:40:26.444  1032  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.446   307   892 D CommandListener: Setting iface cfg
08-25 17:40:26.446   307   892 D CommandListener: Trying to bring up p2p0
,08-25 17:40:26.446  1032  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 17:40:26.446  1032  1388 D LGWifiP2pService: P2pEnablingState
,08-25 17:40:26.446  1032  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.446  1032  1388 D LGWifiP2pService: P2p socket connection successful
08-25 17:40:26.446  1032  1388 D LGWifiP2pService: P2pEnabledState
08-25 17:40:26.447  1032  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 17:40:26.447  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 17:40:26.447  1032  1032 D RttService: SCAN_AVAILABLE : 3
08-25 17:40:26.447  1032  1553 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.447  1032  1553 I WifiNative-HAL: startHal
08-25 17:40:26.447  1032  1553 D wifi    : getting scan capabilities on interface[1] = 0x95366240
08-25 17:40:26.447  1032  1553 D wifi    : failed to get capabilities : -3
08-25 17:40:26.447  1032  1553 E WifiScanningService: could not get scan capabilities
08-25 17:40:26.447  1032  1554 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.448  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 17:40:26.448  1938  1938 D WfdsService: WifiP2pState is changed : true
08-25 17:40:26.448  1032  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 17:40:26.449  1938  2326 D WfdsService: Receive the WFDS_ENABLE Method
08-25 17:40:26.449  1938  2326 D WfdsService: Set the WFDS Monitor: true
08-25 17:40:26.449  1938  2326 D WfdsService: Connected to the supplicant for wfds
08-25 17:40:26.449  1938  2326 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 17:40:26.449  7193  7193 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 17:40:26.449  1938  2326 D WfdsService: selectPreferredScanChannel [36]
08-25 17:40:26.449  1938  2326 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 17:40:26.449  1032  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 17:40:26.450  1032  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 17:40:26.450  1032  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-25 17:40:26.450  1032  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 17:40:26.450  1032  1388 D LGWifiP2pService: before postfix = G3
08-25 17:40:26.450  1032  1388 D WifiServerServiceExt: postfix byte check : 2
08-25 17:40:26.450  1032  1388 D LGWifiP2pService: after postfix = G3
08-25 17:40:26.450  1032  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 17:40:26.451  1032  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 17:40:26.452  1032  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 17:40:26.452  1032  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 17:40:26.452  1032  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 17:40:26.452  1032  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 17:40:26.453  1032  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 17:40:26.453  1938  1938 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 17:40:26.453  1032  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 17:40:26.453  1032  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-25 17:40:26.453  1938  1938 D WfdsService: isConnected: false
08-25 17:40:26.454  1032  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 17:40:26.454  1032  1398 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:40:26.454  1032  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 17:40:26.454  1032  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 17:40:26.455  1032  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 17:40:26.455  1032  1388 D WifiNative-p2p0: doBoolean: P2P,_SERVICE_FLUSH
08-25 17:40:26.455  1032  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 17:40:26.455  1032  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 17:40:26.455  1938  1938 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 17:40:26.456  1938  1938 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 17:40:26.456  1938  1938 D WfdsService: Update P2p Interface State: 3
08-25 17:40:26.456  1032  1398 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 17:40:26.456  1032  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 17:40:26.456  1032  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 17:40:26.456  1032  1398 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 17:40:26.457  1032  1398 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 17:40:26.457  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=188174  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-25 17:40:26.462  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:26.462  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:26.462  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.463  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.463  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:40:26.463  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:26.466  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=188182  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:26.466  1032  1398 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 17:40:26.467  1032  1398 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 17:40:26.467  1032  1398 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 17:40:26.467  1032  1398 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 17:40:26.467  7193  7193 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 17:40:26.468  1032  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 17:40:26.468  1032  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 17:40:26.468  1032  1388 D LGWifiP2pService: InactiveState
08-25 17:40:26.468  1032  1388 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.468  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.468  1032  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 17:40:26.469  1032  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 17:40:26.469  1032  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.469  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:40:26.469  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.469  1032  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.469  1032  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.469  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.469  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.469  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:40:26.469  1032  7210 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.470  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.470  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.470  1938  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:40:26.470  7193  7193 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:40:26.470  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 1,7:40:26.470  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.470  1032  7210 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.470  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.470  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.471  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.471  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.471  1032  7210 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.471  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.471  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.472  1938  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.472  1938  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-25 17:40:26.472  1032  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.472  1032  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.472  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.472  1032  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.473  1938  2326 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 17:40:26.473  1032  1388 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.473  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.473  1032  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.473  1032  1032 E WifiServerServiceExt: No p2p device connected
08-25 17:40:26.474  1032  1398 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 17:40:26.474  1032  1398 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 17:40:26.475  1032  1398 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 17:40:26.475  1032  1398 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 17:40:26.475  7193  7193 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 17:40:26.475  1032  1398 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 17:40:26.476  1032  1398 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 17:40:26.476  1032  1398 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 17:40:26.476  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 17:40:26.478  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:40:26.479  7193  7193 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.479  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:40:26.479  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.479  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.479  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:26.479  7193  7193 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:40:26.479  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.479  1938  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.480  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.480  1032  7210 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.480  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.480  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.480  1032  1398 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 17:40:26.480  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.480  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.480  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.480  1938  7229 D ,WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.480  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:26.480  1032  7210 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.480  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.480  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:26.481  1032  1398 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:40:26.481  1032  1398 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:40:26.482  1032  1398 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:40:26.482  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 17:40:26.482  7193  7193 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 17:40:26.482  7193  7193 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-25 17:40:26.482  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 17:40:26.482  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:26.483  1032  7210 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:26.483  1032  7210 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:26.483  1032  1398 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 17:40:26.483  1032  1398 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 17:40:26.484  1032  1398 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 17:40:26.484  1032  1398 D WifiNative-wlan0: doBoolean: SCAN
08-25 17:40:26.484  1032  1398 D WifiNative-wlan0: SCAN: returned false
08-25 17:40:26.485  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=188201  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:26.486  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=188203  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:26.487  1032  1398 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:26.488  1032  1398 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:26.489  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:26.489  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:26.489  1032  1398 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:26.489  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.489  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:26.489  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:40:26.489  1032  1398 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:26.490  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:26.490  1032  1398 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:26.492  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:26.492  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 17:40:26.495  7211  7211 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:40:26.495  7211  7211 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:40:26.498  7211  7211 D PhoneMonitor: Register our PhoneStateListener
08-25 17:40:26.507  7211  7211 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 17:40:26.509  7211  7211 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 17:40:26.520  7211  7211 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 17:40:26.521  7211  7211 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 17:40:26.522  7211  7211 D TelephonyAutoProfiling: [parse] Load xml
,08-25 17:40:26.525  7211  7211 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 17:40:26.525  7211  7211 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 17:40:26.526  7211  7211 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-25 17:40:26.533  7211  7211 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-25 17:40:26.549  1032  1914 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7232 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:40:26.550  1032  1914 I ActivityManager: Killing 6170:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 17:40:26.592  1032  2046 W libprocessgroup: failed to open /acct/uid_10097/pid_6170/cgroup.procs: No such file or directory
,08-25 17:40:26.729  1032  1701 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7250 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-25 17:40:26.730  1032  1701 I ActivityManager: Killing 6670:com.lge.eula/1000 (adj 15): empty #17
,08-25 17:40:26.774  1032  1700 W libprocessgroup: failed to open /acct/uid_1000/pid_6670/cgroup.procs: No such file or directory
,08-25 17:40:26.900  1032  1701 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7270 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:40:26.902  1032  1701 I ActivityManager: Killing 6688:com.lge.bnr/1000 (adj 15): empty #17
,08-25 17:40:26.929  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 17:40:26.929  1032  7210 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-25 17:40:26.930  1032  1398 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 17:40:26.931  1032  1398 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 17:40:26.932  7193  7193 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
08-25 17:40:26.932  1032  1398 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 17:40:26.933  1938  7229 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-25 17:40:26.933  1032  7210 E WifiMonitor: WifiMonitor:p2p0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 17:40:26.933  1032  7210 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 17:40:26.933  1032  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.933  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.934  1032  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:26.934  1032  1398 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 17:40:26.935  1032  1398 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 17:40:26.962  1032  1700 W libprocessgroup: failed to open /acct/uid_1000/pid_6688/cgroup.procs: No such file or directory
,08-25 17:40:27.007  7270  7270 I art     : Almond Protected OAT
,08-25 17:40:27.074  7270  7270 D WeatherApplication: removeAccount
,08-25 17:40:27.078  7270  7270 D WeatherApplication: Account.length = 0
08-25 17:40:27.078  7270  7270 E WeatherApplication: OPERATOR:OPEN
08-25 17:40:27.091  7270  7270 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:40:27
,08-25 17:40:27.097  7270  7270 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-25 17:40:27.097  7270  7270 D Weather.Utils: 2 : All the weather widget is gone.
08-25 17:40:27.100  7270  7270 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 17:40:27.103  7270  7270 D WeatherAncestor: connectivity changed - connection : true
08-25 17:40:27.104  7270  7270 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-25 17:40:27.117  7270  7270 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:40:27.117  7270  7270 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 17:40:27.117  7270  7270 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-25 17:40:27.140  7270  7270 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 17:40:27.140  7270  7270 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:40:27
,08-25 17:40:27.234  1032  1919 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7288 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:40:27.236  1032  1919 I ActivityManager: Killing 2124:com.lge.music/u0a34 (adj 15): empty #17
,08-25 17:40:27.258   340   340 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 23.821ms
,08-25 17:40:27.265   314  1394 V AudioFlinger: 2124 died, releasing its sessions
,08-25 17:40:27.265   314  1394 V AudioFlinger:  pid 1849 @ 0
08-25 17:40:27.265   314  1394 V AudioFlinger:  pid 3428 @ 1
08-25 17:40:27.265   314  1394 V AudioFlinger:  pid 3428 @ 2
08-25 17:40:27.279   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 20.819ms
,08-25 17:40:27.300   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 20.174ms
,08-25 17:40:27.302  1032  1377 V AlarmManager: RTC_WAKEUP set : Alarm{35d89d0e type 0 when 1472139626646 android} when 1472139626646
08-25 17:40:27.302  1032  1700 W libprocessgroup: failed to open /acct/uid_10034/pid_2124/cgroup.procs: No such file or directory
08-25 17:40:27.306  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:27.306  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:27.306  1032  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:27.309  1032  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{33e9532f type 2 when 188908 com.google.android.gms} when 188908
08-25 17:40:27.325  1032  1398 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:40:27.326  1032  1398 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:40:27.326  1032  1398 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:40:27.327  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:40:27.327  1032  1398 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-25 17:40:27.414   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:40:27.414   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 17:40:27.414   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:40:27.416  7288  7306 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 17:40:27.418   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:40:27.418   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 17:40:27.418   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:40:27.419  7288  7306 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 17:40:27.427   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:40:27.427   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 17:40:27.427   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:40:27.430  7288  7310 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 17:40:27.433   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:40:27.433   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 17:40:27.433   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:40:27.433  7288  7310 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 17:40:27.688  7288  7288 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 17:40:27.700  7288  7288 I LibraryLoader: Loading: webviewchromium
08-25 17:40:27.704  7288  7288 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9427-9432)
08-25 17:40:27.705  7288  7288 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 17:40:27.714  7288  7288 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29e75de3}
,08-25 17:40:27.716  7288  7288 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:40:27.716  7288  7288 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:40:27.731  7288  7288 I BrowserStartupController: Initializing chromium process, renderers=0
,08-25 17:40:27.732  7288  7288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:40:27.759  7288  7288 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 17:40:27.761   314   314 V AudioPolicyService: registerClient() client 0xb558ac60, uid 10093
08-25 17:40:27.761  7288  7288 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 17:40:27.763  7288  7330 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 17:40:27.763  7288  7288 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 17:40:27.788  7288  7288 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:40:27.788  7288  7288 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:40:27.788  7288  7288 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:40:27.788  7288  7288 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:40:27.788  7288  7288 I Adreno-EGL: Remote Branch: 
08-25 17:40:27.788  7288  7288 I Adreno-EGL: Local Patches: 
08-25 17:40:27.788  7288  7288 I Adreno-EGL: Reconstruct Branch: 
,08-25 17:40:27.886  7288  7288 I NSApplication: Starting up...
,08-25 17:40:27.972  1032  2010 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7343 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 17:40:27.977  1032  1920 I ActivityManager: Killing 6084:com.android.vending/u0a44 (adj 15): empty #17
,08-25 17:40:28.094  1032  1919 W libprocessgroup: failed to open /acct/uid_10044/pid_6084/cgroup.procs: No such file or directory
,08-25 17:40:28.203  1032  1914 I art     : Explicit concurrent mark sweep GC freed 74588(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.691ms total 174.520ms
,08-25 17:40:28.248  7343  7343 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:40:28.313  1032  1573 D WifiServiceImplEx: setWifiEnabled: false pid=6846, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:40:28.314  1032  1573 D WifiService: setWifiEnabled: false pid=6846, uid=10118
08-25 17:40:28.314  1032  1573 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:40:28.337  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:40:28.337  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:28.337  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-25 17:40:28.342  1032  1398 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:28.342  1032  1398 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:28.343  1032  1398 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:28.343  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:40:28.350  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:28.350  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:28.350  1032  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2aa9164
08-25 17:40:28.350  1032  1388 D LGWifiP2pService: P2pDisablingState
08-25 17:40:28.350  1032  1388 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:28.350  1032  1388 D LGWifiP2pService: p2p socket connection lost
08-25 17:40:28.350  1032  1388 D LGWifiP2pService: P2pDisabledState
08-25 17:40:28.351  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 17:40:28.351  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-25 17:40:28.352  1938  1938 D WfdsService: WifiP2pState is changed : false
08-25 17:40:28.352  1938  2326 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 17:40:28.352  1938  2326 D WfdsService: Set the WFDS Monitor: false
08-25 17:40:28.353  1938  2326 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:40:28.353  1938  2326 D WfdsService: STATE : WfdsDisabledState - enter
08-25 17:40:28.353  1938  7229 D CtrlSupplicant: Received on exit socket, terminate
08-25 17:40:28.353  1938  7229 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 17:40:28.353  1938  7229 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 17:40:28.353  1938  7229 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 17:40:28.353  1032  1032 D RttService: SCAN_AVAILABLE : 1
08-25 17:40:28.353  1938  2329 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 17:40:28.354  1938  2326 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 17:40:28.354  1032  1554 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:28.354  1032  1553 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:28.355  1032  1398 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 17:40:28.356   307   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:40:28.359  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-25 17:40:28.361  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:28.361  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:28.361  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:40:28.362  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 17:40:28.362  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:28.364  1032  1032 D WifiHS20: hidePasspointNotification off =false
,08-25 17:40:28.366  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:28.366  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:28.366  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:40:28.366  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:28.367  1032  1398 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 17:40:28.367  1032  1398 D WifiNative-p2p0: TERMINATE: returned true
08-25 17:40:28.367  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:28.367  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:28.367  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:28.368  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 17:40:28.368  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:28.369  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:28.370  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 17:40:28.371  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 17:40:28.372  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:28.372  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:28.372  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:28.372  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:28.373  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 1,7:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:28.373  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:28.373  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:28.373  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:28.387  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:40:28.445  7193  7193 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 17:40:28.445  7193  7193 I wpa_supplicant: monitor socket send errors count : 1
08-25 17:40:28.445  7193  7193 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1938-4\x00 that cannot receive messages
08-25 17:40:28.449  1032  7210 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 17:40:28.449  1032  7210 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 17:40:28.449  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:40:28.449  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,08-25 17:40:28.451  1032  1398 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=190168  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,08-25 17:40:28.453  1032  1398 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=190169  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
08-25 17:40:28.533  7193  7193 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 17:40:28.533  1032  7210 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 17:40:28.533  1032  7210 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 17:40:28.533  1032  7210 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 17:40:28.534  1032  1398 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 35 0
,08-25 17:40:28.581  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 17:40:28.583  6488  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 17:40:28.605  2187  2187 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:28.615  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 17:40:28.615  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:28.615  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:40:28.615  7134  7134 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 17:40:28.616  7134  7134 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 17:40:28.622  7134  7134 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cf6f8d6
08-25 17:40:28.622  7134  7134 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:40:28.622  7134  7134 D AppUp4:CustFacade: isPhone : true
08-25 17:40:28.622  7134  7134 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:40:28.622  7134  7134 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 17:40:28.626  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:28.626  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:40:28.628  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:28.632  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:40:28.638  1032  1398 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 17:40:28.638  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:28.638  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:28.638  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:28.638  1938  1938 D WfdsService: Supplicant Connection state is changed : false
08-25 17:40:28.638  1938  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 17:40:28.638  1938  2326 D WfdsService: Set the WFDS Monitor: false
08-25 17:40:28.638  1938  2326 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:40:28.641  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:40:28.642  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:40:28.643  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:28.643  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:28.644  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:28.645  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 17:40:28.645  1032  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 17:40:28.645  1032  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 17:40:28.647  7162  7162 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 17:40:28.664  4341  7375 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:40:28.668  4341  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:28.668  4341  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 17:40:28.676  7162  7377 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:28.682  3428  3428 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 17:40:28.682  3428  3428 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:40:28.684  3428  3428 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 17:40:28.685  7042  7379 W FormManager: Network not available. Please check & try again.
08-25 17:40:28.696  7211  7211 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 17:40:28.698  7211  7211 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 17:40:28.702  7042  7380 V FormManager: Network unavailable.
08-25 17:40:28.715  7270  7270 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:40:28
08-25 17:40:28.716  7270  7270 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 17:40:28.716  7270  7270 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 17:40:28.716  7270  7270 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-25 17:40:28.717  7270  7270 D WeatherAncestor: connectivity changed - connection : true,
08-25 17:40:28.717  7270  7270 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a44e244
08-25 17:40:28.718  7270  7270 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:40:28.718  7270  7270 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 17:40:28.718  7270  7270 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 17:40:28.718  7270  7270 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 17:40:28.718  7270  7270 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:40:28
08-25 17:40:28.719  7042  7380 V FormManager: Network unavailable.
08-25 17:40:28.742  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:40:28.742  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:40:28.742  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:40:28.742  6952  6952 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:40:28.742  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:40:28.743  6952  6952 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:40:28.744  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 17:40:28.744  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:40:28.744  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:40:28.744  6952  6952 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:40:28.744  6952  6952 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 17:40:28.754  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:28.757  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:40:28.762  7042  7389 W FormManager: Network not available. Please check & try again.
08-25 17:40:28.764  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:28.765  7042  7390 V FormManager: Network unavailable.
08-25 17:40:28.771  7042  7390 V FormManager: Network unavailable.
,08-25 17:40:28.787  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:40:28.792  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:40:28.795  7042  7392 W FormManager: Network not available. Please check & try again.
,08-25 17:40:28.800  7042  7393 V FormManager: Network unavailable.
08-25 17:40:28.800  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:28.812  7042  7393 V FormManager: Network unavailable.
,08-25 17:40:28.820  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:28.820  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:40:28.822  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:28.825  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:40:28.832  4341  7394 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 17:40:28.835  4341  7395 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:28.835  4341  7395 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:40:28.898  1032  2010 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7396 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 17:40:29.035  7396  7396 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 17:40:29.035  7396  7396 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 17:40:29.044  7396  7396 V [BNRBootReceiver]: Boot Receiver Return
,08-25 17:40:29.045  7396  7396 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 17:40:29.051  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:29.062  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:29.074  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:29.087  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:29.087  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:40:29.089  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:40:29.097  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:40:29.111  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:29.118  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:29.130  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:40:29.130  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:29.134  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:40:29.142  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 17:40:29.148  6952  6952 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 17:40:29.152  1032  2046 I ActivityManager: Killing 6934:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-25 17:40:29.153  1032  1398 E WifiStateMachine:  InitialState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:144848] from screen [on:0 period:-1034153375]
,08-25 17:40:29.154  1032  1398 E WifiStateMachine:  DefaultState CMD_START_SCAN -2 -2 ic=1 proc(ms):5 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1034153374]
08-25 17:40:29.184  1032  1573 W libprocessgroup: failed to open /acct/uid_10037/pid_6934/cgroup.procs: No such file or directory
08-25 17:40:29.186  6710  7111 D UEI.SmartControl: Internal timer expired: 4
08-25 17:40:29.186  6710  7111 D UEI.SmartControl: unbind internal service
,08-25 17:40:29.195  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:29.198   307  7418 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 17:40:29.199  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 17:40:29.200  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:40:29.200  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:40:29.200  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:40:29.204  6710  7105 D serial_port: close(fd = 24)
08-25 17:40:29.209  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:29.210  6710  7105 I UEI.SmartControl: Serial port is closed.
,08-25 17:40:29.218  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:29.226  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:29.226  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:29.228  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:40:29.232  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:40:29.244  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 17:40:29.244  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:40:29.244  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:40:29.249  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:29.255  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:29.263  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:40:29.263  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:29.265  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:40:29.274  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:29.277  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:40:29.286  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:29.287  7042  7420 W FormManager: Network not available. Please check & try again.
08-25 17:40:29.301  7042  7421 V FormManager: Network unavailable.
,08-25 17:40:29.304  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:29.305  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:40:29.306  7042  7421 V FormManager: Network unavailable.
08-25 17:40:29.306  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:29.309  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:29.317  4341  7422 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:40:29.324  6973  6973 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 17:40:29.324  6973  6973 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:40:29.324  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:29.328  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:40:29.329  4341  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:29.329  4341  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 17:40:29.337  7042  7425 W FormManager: Network not available. Please check & try again.
08-25 17:40:29.339  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:29.346  7042  7426 V FormManager: Network unavailable.
,08-25 17:40:29.354  7042  7426 V FormManager: Network unavailable.
08-25 17:40:31.338  1032  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:31.339  1032  2010 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 17:40:31.372  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:40:31.372  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:31.372  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:31.373  1032  1094 D BluetoothManagerService: Message: 1
08-25 17:40:31.373  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 17:40:31.400  1032  1094 D BluetoothManagerService: Message: 20
08-25 17:40:31.400  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b70c1cc:true
,08-25 17:40:31.412  7073  7073 D BluetoothAdapterState: make
08-25 17:40:31.417  7073  7073 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 17:40:31.417  7073  7073 I bluedroid-qcom: init
,08-25 17:40:31.421  7073  7434 I BluetoothAdapterState: Entering OffState
08-25 17:40:31.422  7073  7073 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 17:40:31.422  7073  7073 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:40:31.422  7073  7073 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:40:31.422  7073  7073 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 17:40:31.422  7073  7073 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 17:40:31.424  7073  7073 I bluedroid-qcom: get_profile_interface socket
08-25 17:40:31.424  7073  7073 I bluedroid-qcom: get_profile_interface map_client
08-25 17:40:31.425  7073  7438 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 17:40:31.427  7073  7438 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 17:40:31.414  7437  7437 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:31.414  7437  7437 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:31.435  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:40:31.436  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 17:40:31.445  7437  7437 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 17:40:31.446  7437  7437 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 17:40:31.446  7437  7437 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 17:40:31.446  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 17:40:31.447  1032  1094 D BluetoothManagerService: Message: 40
08-25 17:40:31.447  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 17:40:31.448  7073  7088 I bluedroid-qcom: config_hci_snoop_log
08-25 17:40:31.451  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 17:40:31.451  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-25 17:40:31.453  7437  7437 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 17:40:31.460  7073  7434 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 17:40:31.463  7073  7438 D BluetoothAdapterProperties: Name is: G3
,08-25 17:40:31.465  7437  7437 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 17:40:31.465  7437  7437 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 17:40:31.466  7073  7434 D BluetoothAdapterProperties: Setting state to 11
08-25 17:40:31.466  7073  7434 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 17:40:31.467  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:31.467  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 17:40:31.467  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 17:40:31.469  7073  7434 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 17:40:31.475  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:40:31.479  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:31.480  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:31.481  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:31.484  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 17:40:31.500  7073  7073 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:40:31.503  7073  7073 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:40:31.503  7073  7073 V BluetoothPbapReceiver: ***********state = 11
08-25 17:40:31.505  7073  7434 D BluetoothBondStateMachine: make
08-25 17:40:31.510  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:31.511  7073  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.511  7073  7434 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 17:40:31.511  7073  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.511  7073  7434 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 17:40:31.512  7073  7451 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 17:40:31.513  7073  7434 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 17:40:31.517  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:40:31.570  1032  1914 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7456 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 17:40:31.577  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:31.578  7073  7073 D HeadsetService: Received start request. Starting profile...
08-25 17:40:31.579  7073  7073 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:40:31.580  7073  7073 D LGBluetoothHfpAdapter: Version 1.6
08-25 17:40:31.583  7073  7073 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:40:31.584  7073  7073 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:40:31.585  7073  7073 D HeadsetStateMachine: make
08-25 17:40:31.587  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:31.593  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:40:31.599  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:31.605  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:31.610  7073  7434 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:40:31.630  7073  7434 V LGMDMManager: Create singleton instance
08-25 17:40:31.631  7073  7073 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:40:31.631  7073  7073 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 17:40:31.634  7073  7434 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 17:40:31.636  7073  7073 D HeadsetStateMachine: max_hf_connections = 1
08-25 17:40:31.636  7073  7073 I bluedroid-qcom: get_profile_interface handsfree
08-25 17:40:31.638  7073  7073 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 17:40:31.638   314  2121 V AudioPolicyService: registerClient() client 0xb0403d00, uid 1002
08-25 17:40:31.639   314  1394 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:40:31.639   314  1394 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:40:31.639   314  1394 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:40:31.639  7073  7073 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 17:40:31.639   314   314 V AudioFlinger: registerClient() client 0xb1433058, pid 7073
08-25 17:40:31.640   314  1389 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:31.640   314  1389 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:31.640  1849  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:31.640  1849  1864 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:31.640  3428  3444 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:31.640  1600  2115 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:31.640  3428  3444 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:31.640  1600  2115 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:31.640   314  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:31.640   314  1390 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:31.640  7073  7088 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:31.640  1600  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:31.640  1600  1617 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:31.640  7073  7088 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 17:40:31.640  7073  7088 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:31.640  3428  3443 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:31.640  7073  7088 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 17:40:31.641  3428  3443 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:31.641  7073  7073 V ToneGenerator: Create Track: 0xb4928a80
08-25 17:40:31.641  7073  7073 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 17:40:31.641  7073  7073 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 17:40:31.641  1032  1898 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:31.641  1849  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:31.641  1849  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:31.641  1032  1898 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:31.641   314  1394 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:40:31.641  1032  1898 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:31.641   314  1394 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:40:31.641  1032  1898 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:31.641   314  1394 V AudioPolicy,ManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:40:31.641   314  1394 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:40:31.642   314  2121 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:40:31.642   314  2122 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:40:31.642   314  2122 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 17:40:31.642   314  2122 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:40:31.642   314  2122 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:40:31.642  7073  7073 V AudioSystem: getLatency() output 2, latency 50
08-25 17:40:31.642  7073  7073 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 17:40:31.642  7073  7073 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 17:40:31.643   314  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,08-25 17:40:31.643   314  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:40:31.643   314  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:40:31.643   314  1395 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:40:31.643   314  1395 V AudioFlinger: createTrack() lSessionId: 20
08-25 17:40:31.643  7073  7073 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 17:40:31.644   314  1395 V AudioFlinger: acquiring 20 from 7073, for 7073
08-25 17:40:31.644   314  1395 V AudioFlinger:  added new entry for 20
08-25 17:40:31.644  7073  7073 V ToneGenerator: ToneGenerator INIT OK, time: 193372
08-25 17:40:31.644  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.645  7073  7466 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 17:40:31.645  7073  7466 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:40:31.645  7073  7466 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:40:31.645  7073  7466 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 17:40:31.645  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.645   314   314 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7073
08-25 17:40:31.646   314   314 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 17:40:31.646   314   314 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 17:40:31.646   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 17:40:31.646   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 17:40:31.646   314   314 V voice   : voice_set_parameters: exit with code(0)
08-25 17:40:31.646   314   314 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 17:40:31.646   314   314 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 17:40:31.646   314   314 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 17:40:31.646   314   314 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 17:40:31.647   314   314 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 17:40:31.647   314   314 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 17:40:31.647  7073  7466 V ToneGenerator: ToneGenerator destructor
08-25 17:40:31.647  7073  7466 V ToneGenerator: stopTone
08-25 17:40:31.647  7073  7466 V ToneGenerator: Delete Track: 0xb4928a80
08-25 17:40:31.647  7073  7073 D A2dpService: Received start request. Starting profile...
08-25 17:40:31.648  7073  7073 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:40:31.649  7073  7073 V Avrcp   : make
08-25 17:40:31.649  7073  7073 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 17:40:31.650  7073  7073 I bluedroid-qcom: get_profile_interface avrcp
08-25 17:40:31.650  7073  7466 V AudioTrack: ~AudioTrack, releasing session id from 7073 on behalf of 7073
08-25 17:40:31.650   314  1394 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 17:40:31.650   314  1394 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 17:40:31.650   314  1395 V AudioFlinger: releasing 20 from 7073 for 7073
08-25 17:40:31.650   314  1395 V AudioFlinger:  decremented refcount to 0
08-25 17:40:31.650   314  1395 V AudioFlinger: purging stale effects
08-25 17:40:31.650   314  1257 V AudioPolicyService: AudioCommandThread() waking up
08-25 17:40:31.650   314  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 17:40:31.650   314  1257 V AudioPolicyManager: releaseOutput() 2
08-25 17:40:31.650   314  1257 ,V AudioPolicyService: AudioCommandThread() going to sleep
08-25 17:40:31.650   314  1394 V AudioFlinger: PlaybackThread::Track destructor
08-25 17:40:31.650   314  1394 V AudioFlinger: removeClient_l() pid 7073, calling pid 314
08-25 17:40:31.650  1032  1973 W Process : Unable to open /proc/7475/status
08-25 17:40:31.660  7073  7073 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 17:40:31.662  7073  7073 E AudioManager: No RCC entry present to update
08-25 17:40:31.662  7073  7073 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 17:40:31.665  7073  7073 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 17:40:31.666  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 17:40:31.666  7073  7073 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 17:40:31.670  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 17:40:31.720  7456  7456 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-25 17:40:31.721  7456  7456 W LG Account v2.2: No ProfileInfo entries
,08-25 17:40:31.721  7456  7456 I LG Account v2.2: isEnabled: false
08-25 17:40:31.721  7456  7456 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 17:40:31.721  7456  7456 I Feature : [Lifetracker]Country: EU
08-25 17:40:31.721  7456  7456 I Feature : [Lifetracker]Operator: OPEN
08-25 17:40:31.721  7456  7456 I Feature : [Lifetracker]Ranking support: false
08-25 17:40:31.721  7456  7456 I Feature : [Lifetracker]Comfort support: false
08-25 17:40:31.722  7456  7456 I Feature : [Lifetracker]Accessory: true
08-25 17:40:31.722  7456  7456 I Feature : [Lifetracker]Health device: true
08-25 17:40:31.722  7456  7456 I Feature : [Lifetracker]Extra Pedometer: false
08-25 17:40:31.722  7456  7456 I Feature : [Lifetracker]Blood glucose device: false,
08-25 17:40:31.722  7456  7456 I Feature : [Lifetracker]Device Number: 3
08-25 17:40:31.732  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:31.736  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 17:40:31.797  1032  1701 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:40:31.797  1032  1701 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:40:31.866  1032  1955 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 17:40:31.872  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 17:40:31.875  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:40:31.876  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 17:40:31.876  7073  7073 I BluetoothA2dpServiceJni: classInitNative
08-25 17:40:31.876  7073  7073 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:40:31.876  7073  7073 D A2dpStateMachine: make
08-25 17:40:31.879  7073  7073 I bluedroid-qcom: get_profile_interface a2dp
08-25 17:40:31.880  7073  7482 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 17:40:31.882  7073  7073 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:40:31.883  7073  7073 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 17:40:31.883  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.884  7073  7481 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:40:31.884  7073  7073 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 17:40:31.886  7073  7073 D HidService: Received start request. Starting profile...
08-25 17:40:31.886  7073  7073 I bluedroid-qcom: get_profile_interface hidhost
08-25 17:40:31.886  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.887  7073  7073 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:40:31.888  7073  7073 D HealthService: Received start request. Starting profile...
,08-25 17:40:31.891  7073  7073 I bluedroid-qcom: get_profile_interface health
,08-25 17:40:31.891  7073  7073 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:40:31.891  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.892  7073  7073 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 17:40:31.894  7073  7073 D PanService: Received start request. Starting profile...
,08-25 17:40:31.894  7073  7073 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:40:31.894  7073  7073 I bluedroid-qcom: get_profile_interface pan
08-25 17:40:31.902  7073  7073 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 17:40:31.902  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:31.903  7073  7073 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-25 17:40:31.908  7073  7073 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:40:31.909  7073  7073 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:40:31.909  7073  7073 D BtGatt.GattService: start()
08-25 17:40:31.909  7073  7073 I bluedroid-qcom: get_profile_interface gatt
,08-25 17:40:31.909  7073  7073 D BtGatt.AdvertiseManager: advertise manager created
08-25 17:40:31.921  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:31.930  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:31.930  7073  7073 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 17:40:31.933  7073  7073 V BluetoothMapService: BluetoothMapBinder()
08-25 17:40:31.935  7073  7073 D BluetoothMapService: Received start request. Starting profile...
08-25 17:40:31.935  7073  7073 D BluetoothMapService: start()
,08-25 17:40:31.940  7073  7073 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 17:40:31.941  7073  7073 D BluetoothMapEmailAppObserver: createReceiver()
08-25 17:40:31.944  7073  7073 D BluetoothMapEmailAppObserver: initObservers()
08-25 17:40:31.944  7073  7073 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-25 17:40:31.959  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:31.959  7073  7073 D HeadsetStateMachine: Proxy object connected
,08-25 17:40:31.960  7073  7073 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-25 17:40:31.960  7073  7073 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 17:40:31.969  7073  7073 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:31.970  7073  7466 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 17:40:31.971  7073  7466 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 17:40:31.971  7073  7466 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 17:40:31.978  7073  7073 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:31.984  7073  7073 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 17:40:31.990  7073  7073 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:32.001  7073  7073 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 17:40:32.001  7073  7073 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 17:40:32.006  7073  7073 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 17:40:32.006  7073  7073 V BluetoothMapService: Handler(): got msg=1
08-25 17:40:32.007  7073  7434 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 17:40:32.007  7073  7434 I bluedroid-qcom: enable
08-25 17:40:32.008  7073  7492 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 17:40:32.008  7073  7492 I bt-btu  : btu_task pending for preload complete event
08-25 17:40:32.008  7073  7434 I bt_hci_bdroid: init
08-25 17:40:32.010  7073  7073 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.011  7073  7434 I bt_vendor: bt-vendor : init
08-25 17:40:32.011  7073  7434 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 17:40:32.011  7073  7434 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 17:40:32.011  7073  7434 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 17:40:32.011  7073  7434 D bt_userial_mct: userial_init
08-25 17:40:32.012  7073  7434 D bt_hci_bdroid: set_power 1
08-25 17:40:32.012  7073  7434 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 17:40:32.012  7073  7434 I bt_vendor: Starting hciattach daemon
08-25 17:40:32.012  7073  7434 I bt_vendor: try to set true
08-25 17:40:32.014  7073  7073 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-25 17:40:32.004  7495  7495 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:32.004  7495  7495 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:32.014  7073  7073 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:32.014  7073  7073 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:32.014  7073  7073 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.014  7073  7073 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 17:40:32.050  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 17:40:32.164  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 17:40:32.188  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:40:32.229  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:40:32.245  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 17:40:32.269  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:40:32.283  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 17:40:32.310  1032  1470 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-25 17:40:32.321  7510  7510 I libmdmdetect: ESOC framework not supported
,08-25 17:40:32.322  7510  7510 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-25 17:40:32.331  7510  7510 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 17:40:32.331  7510  7510 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 17:40:32.331  7510  7510 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 17:40:32.331  7510  7510 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 17:40:32.332  7510  7510 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 17:40:32.332  7510  7510 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 17:40:32.332  7510  7510 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 17:40:32.368  7510  7514 E QC-QMI  : qmi_client [7510] 14: failed to locate client data
08-25 17:40:32.369   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 17:40:32.369   480   480 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-25 17:40:32.386  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 17:40:32.397  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 17:40:32.415  7073  7434 I bt_vendor: bluetooth satus is on
,08-25 17:40:32.415  7073  7434 D bt_hci_bdroid: preload
08-25 17:40:32.416  7073  7494 D bt_userial_mct: userial_open(port:0)
08-25 17:40:32.416  7073  7494 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 17:40:32.419  7073  7494 I bt_vendor: Done intiailizing UART
08-25 17:40:32.420  7073  7494 I bt_vendor: Done intiailizing UART
08-25 17:40:32.420  7073  7494 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 17:40:32.421  7073  7494 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 17:40:32.421  7073  7518 D bt_userial_mct: Entering userial_read_thread()
,08-25 17:40:32.421  7073  7492 I bt-btu  : btu_task received preload complete event
08-25 17:40:32.422  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 17:40:32.422  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 17:40:32.424  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 17:40:32.429  7073  7492 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 17:40:32.429  7073  7492 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 17:40:32.429  7073  7492 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:40:32.429  7073  7492 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:40:32.429  7073  7492 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:40:32.430  7073  7492 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 17:40:32.438  7288  7308 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-25 17:40:32.511  7073  7492 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 17:40:32.511  7073  7492 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-25 17:40:32.511  7073  7492 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-25 17:40:32.557  7073  7438 E bt-btif : Calling BTA_HhEnable
,08-25 17:40:32.557  7073  7438 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-25 17:40:32.558  7073  7438 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 17:40:32.561  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:40:32.562  7073  7438 D BluetoothAdapterProperties: Name is: G3
08-25 17:40:32.565  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 17:40:32.565  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 17:40:32.565  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 17:40:32.566  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 17:40:32.566  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 17:40:32.567  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 17:40:32.571  7073  7438 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:40:32.574  7073  7438 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:40:32.579  7073  7438 D bt_hci_bdroid: postload
08-25 17:40:32.579  7073  7494 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:40:32.580  7073  7492 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-25 17:40:32.584  7073  7438 D bte_conf: Device ID record 1 : primary
08-25 17:40:32.584  7073  7438 D bte_conf:   vendorId            = 00c4
08-25 17:40:32.584  7073  7438 D bte_conf:   vendorIdSource      = 0001
08-25 17:40:32.584  7073  7438 D bte_conf:   product             = 13a1
08-25 17:40:32.584  7073  7438 D bte_conf:   version             = 1000
08-25 17:40:32.584  7073  7438 D bte_conf:   clientExecutableURL = 
08-25 17:40:32.584  7073  7438 D bte_conf:   serviceDescription  = 
08-25 17:40:32.584  7073  7438 D bte_conf:   documentationURL    = 
08-25 17:40:32.584  7073  7438 D bte_conf: bte_load_did_conf no section named DID2.
08-25 17:40:32.586  7073  7492 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:32.586  7073  7492 W bt-smp  : Plain text(LSB ~ MSB) = 82 c9 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:32.586  7073  7492 W bt-smp  : Encrypted text(LSB ~ MSB) = 7d 68 ff 03 85 0e 0c c2 2e 3d ec 6c 19 b2 78 74 
08-25 17:40:32.586  7073  7494 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:40:32.586  7073  7492 W bt-btm  : Stopping oneshot timer
08-25 17:40:32.589  7073  7494 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:40:32.589  7073  7494 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:40:32.590  7073  7434 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 17:40:32.590  7073  7434 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:40:32.590  7073  7434 D BluetoothAdapterProperties: State =  11
08-25 17:40:32.590  7073  7434 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 17:40:32.590  7073  7434 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 17:40:32.590  7073  7434 D BluetoothAdapterProperties: Setting state to 12
08-25 17:40:32.591  7073  7434 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 17:40:32.591  7073  7438 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 17:40:32.591  7073  7438 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:40:32.592  7073  7494 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:40:32.584  7522  7522 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:40:32.584  7522  7522 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:32.598  7073  7518 E bt_mct  : hci lib postload completed
08-25 17:40:32.598  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:32.598  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 17:40:32.598  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 17:40:32.598  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:32.599  7073  7434 I BluetoothAdapterState: Entering On State
08-25 17:40:32.600  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:32.604  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:32.606  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:40:32.618  7073  7438 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:40:32.618  7073  7438 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-25 17:40:32.623  7073  7434 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 17:40:32.623  7073  7434 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 17:40:32.623  7073  7434 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 17:40:32.624  7073  7434 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 17:40:32.625  1032  1032 D BluetoothHeadset: Proxy object connected
08-25 17:40:32.627  6952  6968 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:40:32.630  7073  7492 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:32.630  7073  7492 W bt-smp  : Plain text(LSB ~ MSB) = 99 f3 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:32.630  7073  7492 W bt-smp  : Encrypted text(LSB ~ MSB) = 62 ed 93 1a 00 65 a5 20 e0 06 13 c5 0a 70 9c 0b 
,08-25 17:40:32.630  7073  7492 W bt-btm  : Stopping oneshot timer
08-25 17:40:32.634  1849  2744 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:32.636  1849  1849 D BluetoothHeadset: Proxy object connected
08-25 17:40:32.638  6952  6967 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:40:32.638  6952  6967 D BluetoothPan: onBluetoothStateChange call bindService
08-25 17:40:32.640  6952  6952 D BluetoothMap: Proxy object connected
08-25 17:40:32.640  6952  6952 D MapProfile: Bluetooth service connected
08-25 17:40:32.640  6952  6952 D BluetoothMap: getConnectedDevices()
08-25 17:40:32.640  7073  7492 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:32.640  7073  7492 W bt-smp  : Plain text(LSB ~ MSB) = c2 5c 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:32.640  7073  7492 W bt-smp  : Encrypted text(LSB ~ MSB) = ea 43 5a 46 b0 88 44 6c 7c fe 86 25 f0 9f 36 d0 
08-25 17:40:32.640  7073  7492 W bt-btm  : Stopping oneshot timer
,08-25 17:40:32.645  6952  6968 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:40:32.648  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:32.650  1849  1849 D BluetoothHeadset: Proxy object connected
08-25 17:40:32.651  1849  1864 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:32.652  7073  7492 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:32.652  7073  7492 W bt-smp  : Plain text(LSB ~ MSB) = 8d 40 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:32.652  7073  7492 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d 4a f6 b3 46 38 10 16 fb 9b 32 59 e6 b6 4e 45 
08-25 17:40:32.653  7073  7492 W bt-btm  : Stopping oneshot timer
08-25 17:40:32.655  1849  1849 D BluetoothHeadset: Proxy object connected
,08-25 17:40:32.655  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:40:32.656  7073  7434 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 17:40:32.657  6952  7529 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:40:32.657  7073  7089 V BluetoothMapService: getConnectedDevices()
08-25 17:40:32.659  6952  6952 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:40:32.659  6952  6952 D PanProfile: Bluetooth service connected
08-25 17:40:32.660  1032  1032 D BluetoothA2dp: Proxy object connected
08-25 17:40:32.662  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 17:40:32.662  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 17:40:32.665  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.665  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:32.667  1938  2146 D LGBluetoothAPIService: Message: 1
08-25 17:40:32.667  1938  2146 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 17:40:32.671  6846  6846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 17:40:32.672  7073  7492 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:32.672  7073  7492 W bt-smp  : Plain text(LSB ~ MSB) = 86 7a 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:32.672  7073  7492 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 95 73 17 b3 95 53 3f a6 60 95 0a ac b5 6d 15 
08-25 17:40:32.672  7073  7492 W bt-btm  : Stopping oneshot timer
,08-25 17:40:32.681  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 17:40:32.682  1032  1094 D BluetoothManagerService: Message: 40
08-25 17:40:32.682  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 17:40:32.686  1938  2146 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 17:40:32.687  7539  7539 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 17:40:32.687  7073  7073 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.687  7073  7073 D BluetoothMapService: STATE_ON
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:32.688  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:40:32.690  7073  7073 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 17:40:32.691  7073  7073 V BluetoothMapService: Handler(): got msg=1
08-25 17:40:32.691  7073  7073 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 17:40:32.691  6952  6952 D BluetoothInputDevice: Proxy object connected
08-25 17:40:32.691  6952  6952 D HidProfile: Bluetooth service connected
08-25 17:40:32.693  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:32.693  7073  7073 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 17:40:32.694  7073  7543 D BluetoothMapMasInstance: MAS initSocket()
08-25 17:40:32.694  7073  7543 D BluetoothMapMasInstance:   masId = 00
08-25 17:40:32.694  7073  7543 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 17:40:32.694  7073  7543 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 17:40:32.694  7073  7543 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 17:40:32.694  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 17:40:32.695  1938  2146 D LGBluetoothAPIService: Message: 100
08-25 17:40:32.695  1938  2146 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 17:40:32.696  1032  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:32.696  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:32.698  7073  7543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:32.699  7073  7543 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 17:40:32.699  7073  7543 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-25 17:40:32.699  7073  7543 D BluetoothMapMasInstance: Accepting socket connection...
08-25 17:40:32.700  7073  7438 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:40:32.700  7073  7438 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 17:40:32.702  6952  6952 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 17:40:32.703  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:32.705  1032  1094 D BluetoothManagerService: Message: 30
08-25 17:40:32.706  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:32.711  6952  6952 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 17:40:32.713  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:32.713  7073  7073 V BluetoothPbapService: Pbap Service onCreate
08-25 17:40:32.713  7073  7073 V BluetoothPbapService: Starting PBAP service
08-25 17:40:32.714  1032  1094 D BluetoothManagerService: Message: 30
08-25 17:40:32.714  7073  7073 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 17:40:32.714  7073  7073 V BluetoothPbapService: Pbap Service onBind
08-25 17:40:32.715  7073  7073 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.715  7073  7073 V BluetoothPbapService: state: 12
08-25 17:40:32.716  7073  7073 V BluetoothPbapService: Handler(): got msg=1
08-25 17:40:32.716  7073  7073 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 17:40:32.718  7073  7544 V BluetoothPbapService: Pbap Service initSocket
08-25 17:40:32.718  1032  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:32.719  7073  7544 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:32.719  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 17:40:32.721  7073  7544 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 17:40:32.721  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:40:32.721  7073  7544 V BluetoothPbapService: Succeed to create listening socket 
08-25 17:40:32.721  7073  7544 V BluetoothPbapService: Accepting socket connection...
08-25 17:40:32.723  6952  6952 D BluetoothA2dp: Proxy object connected
,08-25 17:40:32.724  6952  6952 D A2dpProfile: Bluetooth service connected
,08-25 17:40:32.725  7073  7073 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:40:32.726  7073  7073 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.726  7073  7073 V BluetoothPbapReceiver: ***********state = 12
08-25 17:40:32.726  6952  6952 D BluetoothPbap: Proxy object connected
08-25 17:40:32.726  6952  6952 D PbapServerProfile: Bluetooth service connected
08-25 17:40:32.728  6952  6952 D BluetoothHeadset: Proxy object connected
08-25 17:40:32.728  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:32.729  2187  2187 D c       : Getting all permits...
08-25 17:40:32.729  2187  2187 D a       : Opening database...
08-25 17:40:32.729  6952  6952 D HeadsetProfile: Bluetooth service connected
08-25 17:40:32.732  2187  2187 D a       : Opening database auth.proximity.permit_store...
,08-25 17:40:32.733  2187  2187 D a       : Closing database...
08-25 17:40:32.737  6952  6952 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:40:32.744  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:32.746  6952  6952 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:40:32.749  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 17:40:32.753  7073  7073 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 17:40:32.755  7073  7073 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 17:40:32.762  7073  7073 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 17:40:32.800  7073  7073 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 17:40:32.800  7073  7073 V BtOppService: onCreate
08-25 17:40:32.806  7073  7073 V BluetoothOppNotification: send message
08-25 17:40:32.810  7073  7073 V BtOppService: Starting RfcommListener
08-25 17:40:32.819  7073  7073 D BluetoothOppPreference: Dumping Names:  
08-25 17:40:32.819  7073  7073 D BluetoothOppPreference: {}
08-25 17:40:32.819  7073  7073 D BluetoothOppPreference: Dumping Channels:  
08-25 17:40:32.819  7073  7073 D BluetoothOppPreference: {}
08-25 17:40:32.821  7073  7073 V BtOppService: onStartCommand
,08-25 17:40:32.825  7073  7073 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:40:32.832  7073  7073 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:40:32.835  7073  7073 V BluetoothOppNotification: new notify threadi!
,08-25 17:40:32.835  7073  7551 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-25 17:40:32.836  7073  7548 V BtOppService: Deleted complete outbound shares, number =  0
,08-25 17:40:32.837  7073  7073 V BluetoothOppNotification: send delay message
,08-25 17:40:32.837  7073  7073 V BtOppService: start RfcommListener
08-25 17:40:32.842  7073  7548 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 17:40:32.842  7073  7073 V BtOppService: RfcommListener started
08-25 17:40:32.845  7073  7553 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 17:40:32.846  1032  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:32.847  7073  7548 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 17:40:32.847  7073  7551 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-25 17:40:32.848  7073  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 17:40:32.851  7073  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:40:32.851  7073  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24a2e579 on behalf of 
08-25 17:40:32.853  7073  7553 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-25 17:40:32.853  7073  7553 V BtOppRfcommListener: Started RFCOMM listener....
,08-25 17:40:32.853  7073  7553 I BtOppRfcommListener: Accept thread started.
08-25 17:40:32.854  7073  7553 V BtOppRfcommListener: Accepting connection...
,08-25 17:40:32.858  7073  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fdcc2be on behalf of 
08-25 17:40:32.863  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:32.864  7073  7073 V BluetoothFtpService: Ftp Service onCreate
08-25 17:40:32.864  7073  7073 I BluetoothFtpService: Ftp Service onCreate
08-25 17:40:32.864  7073  7551 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aca426c on behalf of 
08-25 17:40:32.865  7073  7552 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 17:40:32.865  7073  7073 V BtOppService: ContentObserver received notification
08-25 17:40:32.865  7073  7073 V BtOppService: ContentObserver received notification
08-25 17:40:32.865  7073  7073 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:40:32.866  7073  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:32.866  7073  7551 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:40:32.866  7073  7551 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-25 17:40:32.866  7073  7073 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.867  7073  7073 V BluetoothFtpService: Starting Listening on sockets
08-25 17:40:32.867  7073  7551 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33e36035 on behalf of 
08-25 17:40:32.867  7073  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d1e4cca on behalf of 
08-25 17:40:32.867  7073  7073 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:32.868  7073  7551 V BluetoothOppNotification: update too frequent, put in queue
08-25 17:40:32.868  7073  7073 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:32.868  7073  7073 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:32.868  7073  7552 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:40:32.868  7073  7073 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.868  7073  7073 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 17:40:32.868  7073  7551 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 17:40:32.868  7073  7073 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:40:32.869  7073  7552 V BluetoothOppNotification: outbound notification was removed.
08-25 17:40:32.870  7073  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-25 17:40:32.871  7073  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f886e3b on behalf of 
08-25 17:40:32.872  7073  7552 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:40:32.873  7073  7073 V BluetoothFtpService: Handler(): got msg=1
08-25 17:40:32.875  7073  7073 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 17:40:32.875  7073  7073 V BluetoothFtpService: Ftp Service initSocket
08-25 17:40:32.877  7073  7552 V BluetoothOppNotification: inbound notification was removed.
08-25 17:40:32.878  7073  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 17:40:32.879  7073  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b4f1958 on behalf of 
08-25 17:40:32.880  1032  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:32.880  7073  7073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:32.881  7073  7073 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-25 17:40:32.881  7073  7073 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 17:40:32.883  7073  7554 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 17:40:32.897  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:32.897  7073  7073 V BluetoothSapService: Sap Service onCreate
08-25 17:40:32.899  7073  7073 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:32.899  7073  7073 V BluetoothSapService: state: 12
08-25 17:40:32.899  7073  7073 V BluetoothSapService: Starting SAP server process
,08-25 17:40:32.901  7073  7073 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 17:40:32.902  7073  7556 V BluetoothSapService: Sap Service initRfcommSocket
08-25 17:40:32.903  1032  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:32.894  7555  7555 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:32.894  7555  7555 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:32.903  7073  7556 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:32.904  7073  7556 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 17:40:32.904  7073  7556 V BluetoothSapService: Succeed to create listening socket 
08-25 17:40:32.904  7073  7556 V BluetoothSapService: Accepting socket connection...
08-25 17:40:32.921  7555  7555 V BT_SAP  : Event pipe created
08-25 17:40:32.921  7555  7555 V BT_SAP  : create_server_socket qcom.sap.server
08-25 17:40:32.921  7555  7555 V BT_SAP  : created socket fd 6
,08-25 17:40:33.356  1032  1388 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:40:33.356  1032  1388 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:40:33.373  1032  1398 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 17:40:33.375  1032  1398 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 17:40:33.586  1032  1920 I ActivityManager: Killing 7134:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 17:40:33.619  1032  2046 W libprocessgroup: failed to open /acct/uid_10011/pid_7134/cgroup.procs: No such file or directory
,08-25 17:40:33.838  7073  7073 V BluetoothOppNotification: new notify threadi!
,08-25 17:40:33.839  7073  7073 V BluetoothOppNotification: send delay message
,08-25 17:40:33.854  7073  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 17:40:33.858  7073  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c487304 on behalf of 
08-25 17:40:33.864  7073  7566 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 17:40:33.867  7073  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:33.868  7073  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36fc60ed on behalf of 
08-25 17:40:33.869  7073  7566 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:40:33.871  7073  7566 V BluetoothOppNotification: outbound notification was removed.
08-25 17:40:33.871  7073  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:33.872  7073  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@334bab22 on behalf of 
08-25 17:40:33.873  7073  7566 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:40:33.877  7073  7566 V BluetoothOppNotification: inbound notification was removed.
08-25 17:40:33.877  7073  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-25 17:40:33.880  7073  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23a869b3 on behalf of 
,08-25 17:40:34.385  1032  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:40:34.385  1032  1898 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@25588aa8 mBinding = false
,08-25 17:40:34.419  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 17:40:34.419  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:34.419  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:34.420  1032  1094 D BluetoothManagerService: Message: 2
08-25 17:40:34.421  1032  1094 D BluetoothManagerService: Sending off request.
08-25 17:40:34.422  7073  7089 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 17:40:34.423  7073  7434 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 17:40:34.423  7073  7434 D BluetoothAdapterProperties: Setting state to 13
08-25 17:40:34.423  7073  7434 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:40:34.423  7073  7434 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:40:34.424  7073  7434 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 17:40:34.425  7073  7438 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:40:34.427  7073  7434 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 17:40:34.429  7073  7543 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-25 17:40:34.435  7073  7544 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:34.436  7073  7554 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:34.438  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 17:40:34.438  7073  7492 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 17:40:34.439  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 17:40:34.439  7073  7492 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 17:40:34.440  7073  7553 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:34.440  7073  7556 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:40:34.441  7073  7434 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:40:34.451  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:34.452  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:40:34.459  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:34.459  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:34.461  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:34.461  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:34.463  6846  6846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:40:34.463  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:34.465  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:34.465  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 17:40:34.465  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-25 17:40:34.470  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.472  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:34.477  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:34.479  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:34.484  7073  7073 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.484  7073  7073 D BluetoothMapService: STATE_TURNING_OFF
08-25 17:40:34.485  7073  7073 V BluetoothMapService: Handler(): got msg=4
08-25 17:40:34.485  7073  7073 D BluetoothMapService: MAP Service closeService in
08-25 17:40:34.485  7073  7073 D BluetoothMapMasInstance: MAP Service shutdown
08-25 17:40:34.485  7073  7073 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:40:34.485  7073  7073 V BluetoothMapService: MAP Service closeService out
08-25 17:40:34.486  7073  7073 V BtOppService: Receiver DISABLED_ACTION 
08-25 17:40:34.486  7073  7073 I BtOppRfcommListener: stopping Accept Thread
08-25 17:40:34.486  7073  7073 V BtOppRfcommListener: close mBtServerSocket
08-25 17:40:34.487  7073  7553 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:40:34.487  7073  7073 V BtOppRfcommListener: waiting for thread to terminate
08-25 17:40:34.487  7073  7073 V BtOppRfcommListener: done waiting for thread to terminate
08-25 17:40:34.490  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-25 17:40:34.501  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 17:40:34.506  7073  7073 V BtOppService: onDestroy
08-25 17:40:34.508  7073  7073 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 17:40:34.513  7073  7073 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:40:34.513  7073  7073 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.513  7073  7073 V BluetoothPbapReceiver: ***********state = 13
08-25 17:40:34.514  7073  7073 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 17:40:34.519  7073  7073 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.519  7073  7073 V BluetoothPbapService: state: 13
08-25 17:40:34.519  7073  7073 V BluetoothPbapService: Pbap Service closeService in
08-25 17:40:34.522  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:34.524  7073  7073 V BluetoothPbapService: successfully stopped pbap service
08-25 17:40:34.524  7073  7073 V BluetoothPbapService: Pbap Service closeService out
08-25 17:40:34.524  7073  7073 V BluetoothPbapService: Pbap Service onDestroy
08-25 17:40:34.524  7073  7073 V BluetoothPbapService: Pbap Service closeService in
08-25 17:40:34.524  7073  7073 V BluetoothPbapService: Pbap Service closeService out
08-25 17:40:34.524  7073  7073 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 17:40:34.540  6952  6952 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:40:34.545  6952  6952 D BluetoothPbap: Proxy object disconnected
08-25 17:40:34.545  6952  6952 D PbapServerProfile: Bluetooth service disconnected
08-25 17:40:34.550  6952  6952 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 17:40:34.556  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:34.556  6952  6952 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 17:40:34.565  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:40:34.572  7073  7073 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 17:40:34.572  7073  7073 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-25 17:40:34.574  7073  7073 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 17:40:34.578  7073  7073 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.579  7073  7073 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:40:34.583  7073  7073 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:40:34.583  7073  7073 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.583  7073  7073 V BluetoothFtpService: Ftp Service closeService
08-25 17:40:34.583  7073  7073 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 17:40:34.584  7073  7073 V BluetoothFtpService: successfully stopped ftp service
,08-25 17:40:34.586  7073  7073 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:34.586  7073  7073 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:34.586  7073  7073 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:34.586  7073  7073 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.587  7073  7073 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 17:40:34.587  7073  7073 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:40:34.593  7073  7073 V BluetoothFtpService: Ftp Service onDestroy
08-25 17:40:34.593  7073  7073 V BluetoothFtpService: Ftp Service closeService
08-25 17:40:34.595  7073  7073 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:34.595  7073  7073 V BluetoothSapService: state: 13
08-25 17:40:34.595  7073  7073 V BluetoothSapService: Stopping SAP server process
08-25 17:40:34.596  7073  7073 V BluetoothSapService: Sap Service closeSapService in
08-25 17:40:34.596  7073  7073 V BluetoothSapService: Close listen Socket : 
08-25 17:40:34.596  7073  7073 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:40:34.596  7073  7073 V BluetoothSapService: Close sapd  Socket : 
,08-25 17:40:34.600  7073  7073 V BluetoothSapService: Sap Service closeSapService out
,08-25 17:40:34.600  7073  7073 V BluetoothSapService: Sap Service onDestroy
08-25 17:40:34.600  7073  7073 V BluetoothSapService: Sap Service closeSapService in
08-25 17:40:34.600  7073  7073 V BluetoothSapService: Close listen Socket : 
08-25 17:40:34.600  7073  7073 V BluetoothSapService: Close rfcomm Socket : 
,08-25 17:40:34.600  7073  7073 V BluetoothSapService: Close sapd  Socket : 
08-25 17:40:34.601  7073  7073 V BluetoothSapService: Sap Service closeSapService out
08-25 17:40:35.441  7073  7438 D bt_hci_bdroid: cleanup
,08-25 17:40:35.453  7073  7494 I bt_lpm  : LPM is already off!!!
08-25 17:40:35.453  7073  7492 W bt-btif : ag scb idx 1 not allocated
08-25 17:40:35.453  7073  7492 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 17:40:35.453  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:35.453  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:40:35.454  7073  7492 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:40:35.455  7073  7518 I bt_userial_mct: exiting userial_read_thread
08-25 17:40:35.456  7073  7518 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 17:40:35.456  7073  7492 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 17:40:35.456  7073  7438 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 17:40:35.456  7073  7494 I bt_vendor: hw_epilog_process
08-25 17:40:35.457  7073  7438 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 17:40:35.457  7073  7438 D bt_userial_mct: userial_close
08-25 17:40:35.457  7073  7438 E bt_userial_mct: pthread_join() FAILED result:3
08-25 17:40:35.457  7073  7438 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 17:40:35.462  7073  7438 D bt_hci_bdroid: set_power 0
08-25 17:40:35.462  7073  7438 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 17:40:35.462  7073  7438 I bt_vendor: bluetooth satus is on
08-25 17:40:35.462  7073  7438 I bt_vendor: bt-vendor : resetting BT status
08-25 17:40:35.462  7073  7438 I bt_vendor: Starting hciattach daemon
08-25 17:40:35.462  7073  7438 I bt_vendor: try to set false
,08-25 17:40:35.469  7073  7438 I bt_vendor: Starting hciattach daemon
08-25 17:40:35.469  7073  7438 I bt_vendor: try to set false
08-25 17:40:35.470  7073  7438 I bt_vendor: cleanup
08-25 17:40:35.470  7073  7492 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 17:40:35.471  7073  7438 I GKI_LINUX: GKI_exit_task 0 done
08-25 17:40:35.471  7073  7438 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 17:40:35.473  7073  7434 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 17:40:35.479  7073  7434 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 17:40:35.482  7073  7073 D HeadsetService: Received stop request...Stopping profile...
08-25 17:40:35.484  7073  7073 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:40:35.484  7073  7073 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:40:35.485  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:35.485  7073  7466 D HeadsetStateMachine: Exit Disconnected: -1
08-25 17:40:35.488  1032  1032 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:35.488  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 17:40:35.489  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:35.489  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:35.489  1849  1849 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:35.490  7073  7073 D A2dpService: Received stop request...Stopping profile...
08-25 17:40:35.491  7073  7481 D A2dpStateMachine: Exit Disconnected: -1
,08-25 17:40:35.495  7073  7073 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 17:40:35.499  7073  7073 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 17:40:35.499  7073  7073 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:40:35.499  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:35.500  1032  1032 D BluetoothA2dp: Proxy object disconnected
08-25 17:40:35.500  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 17:40:35.502  7073  7073 D HidService: Received stop request...Stopping profile...
08-25 17:40:35.502  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:35.504  7073  7073 D HealthService: Received stop request...Stopping profile...
08-25 17:40:35.504  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:35.508  7073  7073 D PanService: Received stop request...Stopping profile...
08-25 17:40:35.510  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:35.513  7073  7073 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:40:35.513  7073  7073 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:40:35.513  7073  7073 D BtGatt.GattService: stop()
08-25 17:40:35.513  7073  7073 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 17:40:35.516  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:35.519  7073  7073 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:40:35.519  7073  7073 D BluetoothMapService: stop()
08-25 17:40:35.519  7073  7073 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 17:40:35.519  7073  7073 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 17:40:35.520  7073  7073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:35.522  7073  7073 D HeadsetStateMachine: Unbinding service...
08-25 17:40:35.524  7073  7073 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:40:35.524  7073  7073 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:40:35.524  7073  7073 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:40:35.524  7073  7073 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:40:35.524  7073  7073 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:40:35.524  7073  7073 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:40:35.524  7073  7073 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:40:35.525  7073  7073 I BluetoothA2dpServiceJni: cleanupNative
08-25 17:40:35.525  7073  7482 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 17:40:35.525  7073  7073 I GKI_LINUX: GKI_exit_task 2 done
08-25 17:40:35.526  7073  7073 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 17:40:35.526  7073  7073 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:40:35.526  7073  7073 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:40:35.526  7073  7073 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:40:35.526  7073  7073 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:40:35.526  7073  7073 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:40:35.527  7073  7073 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:40:35.527  7073  7073 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:40:35.530  7073  7073 V BluetoothMapService: Handler(): got msg=4
08-25 17:40:35.530  7073  7073 D BluetoothMapService: MAP Service closeService in
08-25 17:40:35.530  7073  7073 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:40:35.530  7073  7073 V BluetoothMapService: MAP Service closeService out
,08-25 17:40:35.535  7073  7434 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 17:40:35.535  7073  7434 D BluetoothAdapterProperties: Setting state to 10
08-25 17:40:35.535  7073  7434 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 17:40:35.542  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:35.542  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 17:40:35.542  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 17:40:35.542  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:35.545  7073  7073 D BluetoothMapService: cleanup()
08-25 17:40:35.545  7073  7073 D BluetoothMapService: MAP Service closeService in
08-25 17:40:35.545  7073  7073 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:40:35.545  7073  7073 V BluetoothMapService: MAP Service closeService out
,08-25 17:40:35.548  7073  7434 I BluetoothAdapterState: Entering OffState
08-25 17:40:35.548  6952  6968 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:40:35.549  1849  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:35.550  6952  6967 D BluetoothPan: onBluetoothStateChange on: false
08-25 17:40:35.550  6952  6968 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:40:35.551  1849  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:35.552  1849  2436 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:35.552  6952  6967 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:40:35.558  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 17:40:35.560  6952  6968 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:40:35.561  6952  7529 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:40:35.562  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 17:40:35.562  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 17:40:35.564  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 17:40:35.564  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 17:40:35.564  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@25588aa8 mBinding = false
08-25 17:40:35.565  1032  1094 D BluetoothManagerService: Sending unbind request.
08-25 17:40:35.569  7073  7438 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 17:40:35.570  7073  7073 I GKI_LINUX: GKI_exit_task 1 done
08-25 17:40:35.570  7073  7073 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 17:40:35.570  7073  7073 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 17:40:35.570  7073  7073 I art     : --- WEIRD: removing null entry 248
08-25 17:40:35.570  7073  7073 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 17:40:35.571  7073  7073 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-25 17:40:35.574  7073  7073 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 17:40:35.575  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 17:40:35.580  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:35.580  1938  2146 D LGBluetoothAPIService: Message: 2
08-25 17:40:35.580  1938  2146 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2d99de7 mBinding = false
08-25 17:40:35.580  1938  2146 D LGBluetoothAPIService: Sending unbind request.
08-25 17:40:35.580  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:35.581  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:35.582  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:35.586  6952  6952 D BluetoothHeadset: Proxy object disconnected
08-25 17:40:35.586  6952  6952 D HeadsetProfile: Bluetooth service disconnected
08-25 17:40:35.587  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 17:40:35.587  6952  6952 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-25 17:40:35.597  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:40:35.607  1600  1600 D BluetoothAdapter: 444109007: getState() :  mService = null. Returning STATE_OFF
08-25 17:40:35.607  1600  1600 D BluetoothAdapter: 444109007: getState() :  mService = null. Returning STATE_OFF
,08-25 17:40:35.612  7073  7073 I art     : System.exit called, status: 0
08-25 17:40:35.612  7073  7073 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 17:40:35.621  6952  6952 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:40:35.633   314  1395 V AudioFlinger: 7073 died, releasing its sessions
08-25 17:40:35.633   314  1395 V AudioFlinger:  pid 1849 @ 0
08-25 17:40:35.633   314  1395 V AudioFlinger:  pid 3428 @ 1
08-25 17:40:35.633   314  1395 V AudioFlinger:  pid 3428 @ 2
08-25 17:40:35.633  6952  6952 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 17:40:35.713  1032  1898 I ActivityManager: Process com.android.bluetooth (pid 7073) has died
08-25 17:40:35.713  1032  1898 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-25 17:40:35.717  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:35.733  6952  6952 D BluetoothPermissionRequest: onReceive
,08-25 17:40:35.737  6952  6952 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:40:35.737  6952  6952 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 17:40:35.740  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:40:35.790  1032  1991 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7590 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 17:40:35.850  7590  7590 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 17:40:35.851  7590  7590 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:40:35.852  7590  7590 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 17:40:35.854  7590  7590 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 17:40:35.876  7590  7590 D BluetoothAdapterApp: Loading JNI Library
,08-25 17:40:35.911  7590  7590 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@309d09ac Instance Count = 1
,08-25 17:40:35.917  7590  7590 D BluetoothAdapterApp: onCreate
08-25 17:40:35.942  7590  7590 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 17:40:35.942  7590  7590 D ProfileConfigQcom: Adding HeadsetService
,08-25 17:40:35.942  7590  7590 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 17:40:35.943  7590  7590 D ProfileConfigQcom: Adding A2dpService
08-25 17:40:35.943  7590  7590 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 17:40:35.943  7590  7590 D ProfileConfigQcom: Adding HidService
08-25 17:40:35.943  7590  7590 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 17:40:35.944  7590  7590 D ProfileConfigQcom: Adding HealthService
08-25 17:40:35.944  7590  7590 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 17:40:35.945  7590  7590 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 17:40:35.945  7590  7590 D ProfileConfigQcom: Adding PanService
08-25 17:40:35.945  7590  7590 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 17:40:35.945  7590  7590 D ProfileConfigQcom: Adding GattService
08-25 17:40:35.945  7590  7590 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 17:40:35.946  7590  7590 D ProfileConfigQcom: Adding BluetoothMapService
08-25 17:40:35.946  7590  7590 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 17:40:35.948  7590  7590 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 17:40:35.952  6952  6952 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 17:40:35.954  7590  7590 V LGMDMManagerInternal: Create singleton instance
,08-25 17:40:36.019  7590  7590 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:40:36.024  7590  7590 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:36.024  7590  7590 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:36.024  7590  7590 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:36.025  7590  7590 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:36.025  7590  7590 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 17:40:36.034  7021  7021 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-25 17:40:36.035  1032  2010 I ActivityManager: Killing 7162:com.lge.email/u0a23 (adj 15): empty #17
08-25 17:40:36.121  1032  1701 W libprocessgroup: failed to open /acct/uid_10023/pid_7162/cgroup.procs: No such file or directory
,08-25 17:40:37.498  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:40:37.498  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:40:40.513  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:40.514  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@caad2f8 added. We now have 6 listener(s)
08-25 17:40:40.514  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:40:40.524  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:40.524  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14d393d1 added. We now have 7 listener(s)
08-25 17:40:40.525  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:40.525  6846  6911 I System.out: IsBluetoothEnabled
08-25 17:40:40.526  1032  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:40.526  1032  1919 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 17:40:40.527  1032  1094 D BluetoothManagerService: Message: 2
08-25 17:40:40.530  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:40.534  1032  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:40.534  1032  1991 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 17:40:40.555  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:40:40.555  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:40.555  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:40.556  1032  1094 D BluetoothManagerService: Message: 1
08-25 17:40:40.556  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 17:40:40.585  1032  1094 D BluetoothManagerService: Message: 20
08-25 17:40:40.585  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5098ff9:true
,08-25 17:40:40.589  7590  7590 D BluetoothAdapterState: make
,08-25 17:40:40.594  7590  7590 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 17:40:40.594  7590  7590 I bluedroid-qcom: init
08-25 17:40:40.595  7590  7620 I BluetoothAdapterState: Entering OffState
08-25 17:40:40.596  7590  7590 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 17:40:40.596  7590  7590 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:40:40.596  7590  7590 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:40:40.596  7590  7590 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 17:40:40.596  7590  7590 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 17:40:40.598  7590  7590 I bluedroid-qcom: get_profile_interface socket
08-25 17:40:40.598  7590  7590 I bluedroid-qcom: get_profile_interface map_client
,08-25 17:40:40.603  7590  7624 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 17:40:40.606  7590  7624 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 17:40:40.594  7623  7623 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:40.594  7623  7623 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:40.615  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:40:40.615  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 17:40:40.623  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 17:40:40.623  1032  1094 D BluetoothManagerService: Message: 40
08-25 17:40:40.623  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 17:40:40.624  7590  7605 I bluedroid-qcom: config_hci_snoop_log
08-25 17:40:40.625  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 17:40:40.625  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 17:40:40.626  7623  7623 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 17:40:40.626  7623  7623 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 17:40:40.626  7623  7623 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 17:40:40.627  7590  7624 D BluetoothAdapterProperties: Name is: G3
,08-25 17:40:40.630  7623  7623 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 17:40:40.634  7623  7623 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 17:40:40.634  7623  7623 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 17:40:40.639  7590  7620 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 17:40:40.639  7590  7620 D BluetoothAdapterProperties: Setting state to 11
08-25 17:40:40.639  7590  7620 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 17:40:40.642  7590  7620 I LGBluetoothServiceJni: classInitNative: succeeds
,08-25 17:40:40.647  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:40.647  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 17:40:40.647  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 17:40:40.653  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:40.656  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:40:40.658  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:40.659  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 17:40:40.680  7590  7590 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:40:40.680  7590  7620 D BluetoothBondStateMachine: make
,08-25 17:40:40.684  7590  7590 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:40.684  7590  7590 V BluetoothPbapReceiver: ***********state = 11
08-25 17:40:40.685  7590  7638 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 17:40:40.686  7590  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:40.686  7590  7620 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 17:40:40.686  7590  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:40.686  7590  7620 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 17:40:40.686  7590  7620 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 17:40:40.689  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:40.690  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:40.704  7590  7590 D HeadsetService: Received start request. Starting profile...
08-25 17:40:40.704  7590  7590 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:40:40.704  7590  7590 D LGBluetoothHfpAdapter: Version 1.6
,08-25 17:40:40.707  7590  7590 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:40:40.707  7590  7590 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:40:40.708  7590  7590 D HeadsetStateMachine: make
08-25 17:40:40.711  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:40.713  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:40.716  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 17:40:40.726  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:40.729  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:40.732  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:40.735  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:40:40.739  7590  7620 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:40:40.742  7590  7590 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:40:40.742  7590  7590 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 17:40:40.745  7590  7590 D HeadsetStateMachine: max_hf_connections = 1
08-25 17:40:40.745  7590  7590 I bluedroid-qcom: get_profile_interface handsfree
08-25 17:40:40.747  7590  7590 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 17:40:40.747   314   314 V AudioPolicyService: registerClient() client 0xb558aa40, uid 1002
,08-25 17:40:40.749   314  1395 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:40:40.749   314  1395 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:40:40.749   314  1395 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:40:40.749  7590  7590 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 17:40:40.749   314  2121 V AudioFlinger: registerClient() client 0xb14330a0, pid 7590
08-25 17:40:40.750   314  1389 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:40.750   314  1389 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:40.750  3428  3444 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:40.750  3428  3444 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:40.750  1032  2046 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:40.750  1032  2046 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:40.750  1849  2744 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:40.750  1849  2744 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:40.750  7590  7606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:40.750  1600  1617 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:40:40.750  1600  1617 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:40:40.750  7590  7606 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 17:40:40.750   314  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:40.750   314  1390 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:40.751  1032  1991 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:40.751  1032  1991 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:40.751  1600  2178 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:40.751  1600  2178 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:40.751  1849  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:40.751  1849  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:40.751  3428  3443 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:40.751  3428  3443 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:40:40.751  7590  7605 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:40:40.751  7590  7605 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 17:40:40.751  7590  7590 V ToneGenerator: Create Track: 0xb4928a80
08-25 17:40:40.751  7590  7590 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 17:40:40.751  7590  7590 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 17:40:40.752   314  2122 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:40:40.752   314  2122 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:40:40.752   314  2122 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:40:40.752   314  2122 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:40:40.752   314  1395 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:40:40.752   314  2121 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:40:40.752   314  2121 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 17:40:40.752   314  2121 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:40:40.752   314 , 2121 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:40:40.752  7590  7590 V AudioSystem: getLatency() output 2, latency 50
08-25 17:40:40.752  7590  7590 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 17:40:40.752  7590  7590 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 17:40:40.752   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:40:40.752   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:40:40.752   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:40:40.752   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:40:40.752   314   314 V AudioFlinger: createTrack() lSessionId: 21
08-25 17:40:40.753  7590  7590 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 17:40:40.753   314   314 V AudioFlinger: acquiring 21 from 7590, for 7590
08-25 17:40:40.753   314   314 V AudioFlinger:  added new entry for 21
08-25 17:40:40.753  7590  7590 V ToneGenerator: ToneGenerator INIT OK, time: 202482
08-25 17:40:40.753  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:40.754  7590  7641 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 17:40:40.754  7590  7641 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:40:40.754  7590  7641 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:40:40.754  7590  7641 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 17:40:40.754   314  1394 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7590
08-25 17:40:40.755   314  1394 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 17:40:40.755   314  1394 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 17:40:40.756   314  1394 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 17:40:40.756   314  1394 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 17:40:40.756   314  1394 V voice   : voice_set_parameters: exit with code(0)
08-25 17:40:40.756   314  1394 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 17:40:40.756   314  1394 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 17:40:40.756   314  1394 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 17:40:40.756   314  1394 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 17:40:40.756   314  1394 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 17:40:40.756   314  1394 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 17:40:40.756  7590  7641 V ToneGenerator: ToneGenerator destructor
08-25 17:40:40.756  7590  7641 V ToneGenerator: stopTone
08-25 17:40:40.756  7590  7641 V ToneGenerator: Delete Track: 0xb4928a80
08-25 17:40:40.756  7590  7641 V AudioTrack: ~AudioTrack, releasing session id from 7590 on behalf of 7590
08-25 17:40:40.757   314  2122 V AudioFlinger: releasing 21 from 7590 for 7590
08-25 17:40:40.757   314  2122 V AudioFlinger:  decremented refcount to 0
08-25 17:40:40.757   314  2122 V AudioFlinger: purging stale effects
08-25 17:40:40.757   314  2122 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 17:40:40.757   314  2122 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 17:40:40.757   314  2122 V AudioFlinger: PlaybackThread::Track destructor
08-25 17:40:40.757   314  1257 V AudioPolicyService: AudioCommandThread() waking up
08-25 17:40:40.757   314  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
,08-25 17:40:40.757   314  2122 V AudioFlinger: removeClient_l() pid 7590, calling pid 314
08-25 17:40:40.757   314  1257 V AudioPolicyManager: releaseOutput() 2
08-25 17:40:40.757   314  1257 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 17:40:40.760  1032  1898 W Process : Unable to open /proc/7644/status
,08-25 17:40:40.764  7590  7620 V LGMDMManager: Create singleton instance
08-25 17:40:40.766  7590  7620 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 17:40:40.847  1032  1920 I art     : Explicit concurrent mark sweep GC freed 52827(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.567ms total 96.282ms
,08-25 17:40:40.852  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:40.857  7590  7590 D A2dpService: Received start request. Starting profile...
08-25 17:40:40.859  7590  7590 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 17:40:40.861  7590  7590 V Avrcp   : make
08-25 17:40:40.862  7590  7590 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 17:40:40.862  7590  7590 I bluedroid-qcom: get_profile_interface avrcp
08-25 17:40:40.882  7590  7590 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 17:40:40.883  7590  7590 E AudioManager: No RCC entry present to update
08-25 17:40:40.884  7590  7590 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 17:40:40.887  7590  7590 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-25 17:40:40.888  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 17:40:40.888  7590  7590 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 17:40:40.892  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 17:40:41.038  1032  1973 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:40:41.038  1032  1973 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:40:41.158  1032  2046 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 17:40:41.167  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 17:40:41.172  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 17:40:41.173  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:40:41.174  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 17:40:41.175  7590  7590 I BluetoothA2dpServiceJni: classInitNative
08-25 17:40:41.175  7590  7590 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:40:41.175  7590  7590 D A2dpStateMachine: make
08-25 17:40:41.180  7590  7590 I bluedroid-qcom: get_profile_interface a2dp
08-25 17:40:41.181  7590  7654 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 17:40:41.184  7590  7590 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:40:41.184  7590  7590 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 17:40:41.185  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:41.186  7590  7590 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 17:40:41.187  7590  7590 D HidService: Received start request. Starting profile...
08-25 17:40:41.187  7590  7590 I bluedroid-qcom: get_profile_interface hidhost
08-25 17:40:41.187  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:41.188  7590  7590 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:40:41.189  7590  7650 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:40:41.190  7590  7590 D HealthService: Received start request. Starting profile...
08-25 17:40:41.193  7590  7590 I bluedroid-qcom: get_profile_interface health
08-25 17:40:41.193  7590  7590 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:40:41.193  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:41.197  7590  7590 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 17:40:41.202  7590  7590 D PanService: Received start request. Starting profile...
08-25 17:40:41.202  7590  7590 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:40:41.202  7590  7590 I bluedroid-qcom: get_profile_interface pan
08-25 17:40:41.207  7590  7590 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 17:40:41.207  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:41.208  7590  7590 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-25 17:40:41.211  7590  7590 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:40:41.212  7590  7590 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:40:41.212  7590  7590 D BtGatt.GattService: start()
08-25 17:40:41.212  7590  7590 I bluedroid-qcom: get_profile_interface gatt
08-25 17:40:41.212  7590  7590 D BtGatt.AdvertiseManager: advertise manager created
08-25 17:40:41.220  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
,08-25 17:40:41.223  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:41.223  7590  7590 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 17:40:41.224  7590  7590 V BluetoothMapService: BluetoothMapBinder()
08-25 17:40:41.225  7590  7590 D BluetoothMapService: Received start request. Starting profile...
08-25 17:40:41.225  7590  7590 D BluetoothMapService: start()
08-25 17:40:41.228  7590  7590 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 17:40:41.228  7590  7590 D BluetoothMapEmailAppObserver: createReceiver()
08-25 17:40:41.229  7590  7590 D BluetoothMapEmailAppObserver: initObservers()
08-25 17:40:41.229  7590  7590 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-25 17:40:41.238  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:41.238  7590  7590 D HeadsetStateMachine: Proxy object connected
08-25 17:40:41.239  7590  7590 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 17:40:41.239  7590  7590 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 17:40:41.243  7590  7590 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:41.243  7590  7641 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 17:40:41.243  7590  7641 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 17:40:41.243  7590  7641 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 17:40:41.245  7590  7590 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:41.248  7590  7590 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:41.250  7590  7590 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:41.254  7590  7590 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:41.257  7590  7590 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:40:41.257  7590  7590 V PanService: [BTUI] SIM Extra State :ABSENT
,08-25 17:40:41.260  7590  7590 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 17:40:41.260  7590  7590 V BluetoothMapService: Handler(): got msg=1
08-25 17:40:41.262  7590  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 17:40:41.262  7590  7620 I bluedroid-qcom: enable
08-25 17:40:41.262  7590  7620 I bt_hci_bdroid: init
08-25 17:40:41.262  7590  7661 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 17:40:41.262  7590  7661 I bt-btu  : btu_task pending for preload complete event
08-25 17:40:41.263  7590  7620 I bt_vendor: bt-vendor : init
08-25 17:40:41.263  7590  7620 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 17:40:41.263  7590  7620 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 17:40:41.263  7590  7620 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 17:40:41.263  7590  7620 D bt_userial_mct: userial_init
08-25 17:40:41.264  7590  7620 D bt_hci_bdroid: set_power 1
08-25 17:40:41.264  7590  7620 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 17:40:41.264  7590  7620 I bt_vendor: Starting hciattach daemon
08-25 17:40:41.264  7590  7620 I bt_vendor: try to set true
08-25 17:40:41.265  7590  7590 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:41.265  7590  7590 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:41.265  7590  7590 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:41.265  7590  7590 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:41.265  7590  7590 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 17:40:41.254  7664  7664 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:41.254  7664  7664 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:40:41.299  7665  7665 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 17:40:41.386  7677  7677 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 17:40:41.403  7678  7678 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:40:41.437  7680  7680 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:40:41.450  7681  7681 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 17:40:41.467  7682  7682 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:40:41.491  7683  7683 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 17:40:41.512  7685  7685 I libmdmdetect: ESOC framework not supported
08-25 17:40:41.513  7685  7685 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 17:40:41.522  7685  7685 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 17:40:41.522  7685  7685 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-25 17:40:41.522  7685  7685 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 17:40:41.522  7685  7685 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 17:40:41.522  7685  7685 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 17:40:41.522  7685  7685 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 17:40:41.522  7685  7685 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 17:40:41.567  7685  7686 E QC-QMI  : qmi_client [7685] 15: failed to locate client data
08-25 17:40:41.567   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 17:40:41.567   480   480 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-25 17:40:41.612  7687  7687 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 17:40:41.627  7688  7688 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:40:41.668  7590  7620 I bt_vendor: bluetooth satus is on
08-25 17:40:41.668  7590  7620 D bt_hci_bdroid: preload
08-25 17:40:41.669  7590  7663 D bt_userial_mct: userial_open(port:0)
08-25 17:40:41.669  7590  7663 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 17:40:41.674  7590  7663 I bt_vendor: Done intiailizing UART
08-25 17:40:41.678  7590  7663 I bt_vendor: Done intiailizing UART
08-25 17:40:41.678  7590  7663 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 17:40:41.679  7590  7663 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 17:40:41.679  7590  7690 D bt_userial_mct: Entering userial_read_thread()
08-25 17:40:41.679  7590  7661 I bt-btu  : btu_task received preload complete event
08-25 17:40:41.681  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 17:40:41.681  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 17:40:41.686  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:40:41.698  7590  7661 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:40:41.699  7590  7661 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 17:40:41.699  7590  7661 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:40:41.699  7590  7661 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:40:41.699  7590  7661 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 17:40:41.814  7590  7661 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-25 17:40:41.814  7590  7661 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 ,
08-25 17:40:41.814  7590  7661 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-25 17:40:41.839  7590  7624 E bt-btif : Calling BTA_HhEnable
08-25 17:40:41.839  7590  7624 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 17:40:41.839  7590  7624 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 17:40:41.843  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:40:41.843  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 17:40:41.843  7590  7624 D BluetoothAdapterProperties: Name is: G3
08-25 17:40:41.845  7590  7624 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:40:41.845  7590  7624 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:40:41.845  7590  7624 D bt_hci_bdroid: postload
08-25 17:40:41.846  7590  7624 D bte_conf: Device ID record 1 : primary
08-25 17:40:41.846  7590  7624 D bte_conf:   vendorId            = 00c4
08-25 17:40:41.846  7590  7624 D bte_conf:   vendorIdSource      = 0001
08-25 17:40:41.846  7590  7624 D bte_conf:   product             = 13a1
08-25 17:40:41.846  7590  7624 D bte_conf:   version             = 1000
08-25 17:40:41.846  7590  7624 D bte_conf:   clientExecutableURL = 
08-25 17:40:41.846  7590  7624 D bte_conf:   serviceDescription  = 
08-25 17:40:41.846  7590  7624 D bte_conf:   documentationURL    = 
08-25 17:40:41.847  7590  7663 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:40:41.847  7590  7624 D bte_conf: bte_load_did_conf no section named DID2.
08-25 17:40:41.850  7590  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 17:40:41.850  7590  7620 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:40:41.850  7590  7620 D BluetoothAdapterProperties: State =  11
08-25 17:40:41.850  7590  7620 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 17:40:41.850  7590  7620 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 17:40:41.851  7590  7620 D BluetoothAdapterProperties: Setting state to 12
08-25 17:40:41.851  7590  7620 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 17:40:41.852  7590  7624 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 17:40:41.844  7698  7698 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:41.861  1032  1094 D BluetoothManagerService: Message: 60
08-25 17:40:41.861  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 17:40:41.861  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 17:40:41.854  7698  7698 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:41.863  7590  7620 I BluetoothAdapterState: Entering On State
08-25 17:40:41.874  7590  7663 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 17:40:41.882  7590  7690 E bt_mct  : hci lib postload completed
08-25 17:40:41.882  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:41.885  7590  7624 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:40:41.885  7590  7624 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 17:40:41.887  7590  7620 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 17:40:41.887  7590  7620 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 17:40:41.888  7590  7620 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-25 17:40:41.893  7590  7620 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:41.906  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:40:41.910  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:41.911  6952  7529 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:40:41.915  7590  7620 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 17:40:41.918  1032  1032 D BluetoothHeadset: Proxy object connected
,08-25 17:40:41.927  1849  1864 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:41.933  1849  1849 D BluetoothHeadset: Proxy object connected
,08-25 17:40:41.939  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 17:40:41.939  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 17:40:41.939  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 17:40:41.940  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 17:40:41.940  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 17:40:41.940  7590  7661 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 17:40:41.942  7590  7624 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 17:40:41.943  6952  6952 D BluetoothMap: Proxy object connected
08-25 17:40:41.943  6952  6952 D MapProfile: Bluetooth service connected
08-25 17:40:41.943  6952  6952 D BluetoothMap: getConnectedDevices()
08-25 17:40:41.968  7703  7703 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 17:40:41.975  6952  6968 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:40:41.975  6952  6968 D BluetoothPan: onBluetoothStateChange call bindService
08-25 17:40:41.978  6952  6968 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:40:41.980  1849  2744 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:41.981  7590  7606 V BluetoothMapService: getConnectedDevices()
08-25 17:40:41.982  7590  7661 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:41.982  7590  7661 W bt-smp  : Plain text(LSB ~ MSB) = f5 24 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:41.982  7590  7661 W bt-smp  : Encrypted text(LSB ~ MSB) = a3 79 b9 43 b7 6c 1d 03 16 bb 87 b3 03 bf 3b e0 
08-25 17:40:41.982  7590  7661 W bt-btm  : Stopping oneshot timer
08-25 17:40:41.993  1849  1849 D BluetoothHeadset: Proxy object connected
,08-25 17:40:41.995  1849  2436 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:41.996  6952  6952 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:40:41.996  6952  6952 D PanProfile: Bluetooth service connected
08-25 17:40:41.998  6952  6952 D BluetoothInputDevice: Proxy object connected
08-25 17:40:41.998  6952  6952 D HidProfile: Bluetooth service connected
08-25 17:40:42.001  1849  1849 D BluetoothHeadset: Proxy object connected
08-25 17:40:42.002  6952  6968 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:40:42.003  6952  6952 D BluetoothHeadset: Proxy object connected
08-25 17:40:42.003  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:40:42.003  6952  6952 D HeadsetProfile: Bluetooth service connected
08-25 17:40:42.004  6952  6967 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:40:42.005  1032  1032 D BluetoothA2dp: Proxy object connected
,08-25 17:40:42.007  7590  7661 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:42.007  7590  7661 W bt-smp  : Plain text(LSB ~ MSB) = be 7b 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:42.007  7590  7661 W bt-smp  : Encrypted text(LSB ~ MSB) = 61 74 ae bf ea 23 b3 fc 67 ff 07 31 65 ad 2c 07 
08-25 17:40:42.007  7590  7661 W bt-btm  : Stopping oneshot timer
08-25 17:40:42.009  6952  6952 D BluetoothA2dp: Proxy object connected
08-25 17:40:42.009  6952  6952 D A2dpProfile: Bluetooth service connected
08-25 17:40:42.010  6952  6968 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:40:42.012  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 17:40:42.012  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 17:40:42.013  1938  1938 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:40:42.016  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:40:42.020  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:42.020  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 17:40:42.020  1032  1094 D BluetoothManagerService: Message: 40
08-25 17:40:42.020  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 17:40:42.021  7590  7661 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:42.021  7590  7661 W bt-smp  : Plain text(LSB ~ MSB) = 4e 6a 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:42.021  7590  7661 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a b4 ae 8b 11 64 73 83 c6 be 2d 9f 92 c0 e4 06 
08-25 17:40:42.021  7590  7661 W bt-btm  : Stopping oneshot timer
08-25 17:40:42.021  1938  2146 D LGBluetoothAPIService: Message: 1
08-25 17:40:42.021  1938  2146 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 17:40:42.023  7590  7590 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.023  7590  7590 D BluetoothMapService: STATE_ON
08-25 17:40:42.025  1938  2146 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 17:40:42.028  6952  6952 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-25 17:40:42.031  7590  7661 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-25 17:40:42.031  7590  7661 W bt-smp  : Plain text(LSB ~ MSB) = d7 de 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:42.031  7590  7661 W bt-smp  : Encrypted text(LSB ~ MSB) = 88 e1 30 f8 c7 32 1d 9e 0d 03 a0 83 4f e6 7d 88 
08-25 17:40:42.031  7590  7661 W bt-btm  : Stopping oneshot timer
08-25 17:40:42.032  6952  6952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:40:42.040  6952  6952 D DockEventReceiver: finishStartingService: stopping service
08-25 17:40:42.041  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:42.042  7590  7590 V BluetoothPbapService: Pbap Service onCreate
08-25 17:40:42.042  7590  7590 V BluetoothPbapService: Starting PBAP service
08-25 17:40:42.043  7590  7590 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 17:40:42.043  7590  7590 V BluetoothMapService: Handler(): got msg=1
,08-25 17:40:42.044  7590  7590 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 17:40:42.045  7590  7590 V BluetoothPbapService: Pbap Service onBind
08-25 17:40:42.045  7590  7661 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:40:42.045  7590  7661 W bt-smp  : Plain text(LSB ~ MSB) = 58 54 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:40:42.045  7590  7661 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b 34 67 13 fb 44 39 9f 5f 48 d7 cb cf d6 5b 14 
08-25 17:40:42.045  7590  7661 W bt-btm  : Stopping oneshot timer
08-25 17:40:42.046  7590  7590 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.046  7590  7590 V BluetoothPbapService: state: 12
08-25 17:40:42.047  7590  7590 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 17:40:42.047  7590  7590 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 17:40:42.048  1938  1938 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 17:40:42.048  7590  7590 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:40:42.048  7590  7590 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.048  7590  7590 V BluetoothPbapReceiver: ***********state = 12
08-25 17:40:42.049  1938  2146 D LGBluetoothAPIService: Message: 100
08-25 17:40:42.049  6952  6952 D BluetoothPbap: Proxy object connected
08-25 17:40:42.049  1938  2146 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 17:40:42.049  6952  6952 D PbapServerProfile: Bluetooth service connected
08-25 17:40:42.050  7590  7590 V BluetoothPbapService: Handler(): got msg=1
08-25 17:40:42.051  7590  7590 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 17:40:42.052  2187  2187 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:40:42.052  2187  2187 D c       : Getting all permits...
08-25 17:40:42.052  7590  7721 D BluetoothMapMasInstance: MAS initSocket()
08-25 17:40:42.052  2187  2187 D a       : Opening database...
08-25 17:40:42.053  7590  7721 D BluetoothMapMasInstance:   masId = 00
08-25 17:40:42.053  7590  7721 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 17:40:42.053  7590  7721 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 17:40:42.053  7590  7721 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 17:40:42.054  1032  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:42.055  2187  2187 D a       : Opening database auth.proximity.permit_store...
08-25 17:40:42.055  7590  7723 V BluetoothPbapService: Pbap Service initSocket
08-25 17:40:42.055  2187  2187 D a       : Closing database...
,08-25 17:40:42.059  1032  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:42.060  7590  7723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:42.061  7590  7721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:42.066  7590  7723 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 17:40:42.066  7590  7723 V BluetoothPbapService: Succeed to create listening socket 
08-25 17:40:42.066  7590  7723 V BluetoothPbapService: Accepting socket connection...
08-25 17:40:42.066  7590  7721 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 17:40:42.067  7590  7721 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 17:40:42.067  7590  7721 D BluetoothMapMasInstance: Accepting socket connection...
08-25 17:40:42.070  7590  7624 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:40:42.071  7590  7624 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-25 17:40:42.071  7590  7624 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:40:42.071  7590  7624 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 17:40:42.076  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:42.077  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:42.079  6952  6952 D BluetoothPermissionRequest: onReceive
08-25 17:40:42.082  6952  6952 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:40:42.085  6952  6952 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 17:40:42.088  7590  7590 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 17:40:42.089  7590  7590 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 17:40:42.095  7590  7590 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 17:40:42.113  7590  7590 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:40:42.113  7590  7590 V BtOppService: onCreate
,08-25 17:40:42.117  7590  7590 V BluetoothOppNotification: send message
08-25 17:40:42.120  7590  7590 V BtOppService: Starting RfcommListener
08-25 17:40:42.129  7590  7727 V BtOppService: Deleted complete outbound shares, number =  0
08-25 17:40:42.130  7590  7590 D BluetoothOppPreference: Dumping Names:  
08-25 17:40:42.130  7590  7590 D BluetoothOppPreference: {}
,08-25 17:40:42.130  7590  7590 D BluetoothOppPreference: Dumping Channels:  
08-25 17:40:42.130  7590  7590 D BluetoothOppPreference: {}
08-25 17:40:42.131  7590  7590 V BtOppService: onStartCommand
08-25 17:40:42.132  7590  7727 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 17:40:42.133  7590  7727 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 17:40:42.134  7590  7730 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:40:42.135  7590  7727 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24a2e579 on behalf of 
08-25 17:40:42.137  7590  7590 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.137  7590  7730 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 17:40:42.137  7590  7590 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:40:42.140  7590  7590 V BluetoothOppNotification: new notify threadi!
08-25 17:40:42.141  7590  7590 V BluetoothOppNotification: send delay message
08-25 17:40:42.141  7590  7590 V BtOppService: start RfcommListener
,08-25 17:40:42.144  7590  7730 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fdcc2be on behalf of 
,08-25 17:40:42.144  7590  7731 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 17:40:42.145  7590  7590 V BtOppService: RfcommListener started
08-25 17:40:42.145  7590  7590 V BtOppService: ContentObserver received notification
08-25 17:40:42.145  7590  7590 V BtOppService: ContentObserver received notification
08-25 17:40:42.146  7590  7732 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 17:40:42.147  1032  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:42.147  7590  7732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:42.149  7590  7732 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-25 17:40:42.149  7590  7732 V BtOppRfcommListener: Started RFCOMM listener....
08-25 17:40:42.149  7590  7732 I BtOppRfcommListener: Accept thread started.
08-25 17:40:42.149  7590  7730 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:40:42.149  7590  7732 V BtOppRfcommListener: Accepting connection...
08-25 17:40:42.149  7590  7730 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 17:40:42.150  7590  7731 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@148ff1f on behalf of 
08-25 17:40:42.151  7590  7731 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 17:40:42.151  7590  7730 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aca426c on behalf of 
08-25 17:40:42.152  7590  7731 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:42.152  7590  7730 V BluetoothOppNotification: update too frequent, put in queue
08-25 17:40:42.156  7590  7731 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33e36035 on behalf of 
,08-25 17:40:42.156  7590  7730 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 17:40:42.162  7590  7731 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:40:42.163  7590  7731 V BluetoothOppNotification: outbound notification was removed.
08-25 17:40:42.163  7590  7731 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:42.165  7590  7731 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d1e4cca on behalf of 
,08-25 17:40:42.166  7590  7731 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:40:42.167  7590  7731 V BluetoothOppNotification: inbound notification was removed.
08-25 17:40:42.167  7590  7731 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-25 17:40:42.169  7590  7731 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f886e3b on behalf of 
08-25 17:40:42.171  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:42.172  7590  7590 V BluetoothFtpService: Ftp Service onCreate
08-25 17:40:42.172  7590  7590 I BluetoothFtpService: Ftp Service onCreate
08-25 17:40:42.172  7590  7590 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:40:42.172  7590  7590 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.172  7590  7590 V BluetoothFtpService: Starting Listening on sockets
08-25 17:40:42.173  7590  7590 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:40:42.173  7590  7590 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:40:42.173  7590  7590 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:40:42.173  7590  7590 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.173  7590  7590 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 17:40:42.173  7590  7590 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:40:42.175  7590  7590 V BluetoothFtpService: Handler(): got msg=1
08-25 17:40:42.177  7590  7590 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 17:40:42.177  7590  7590 V BluetoothFtpService: Ftp Service initSocket
,08-25 17:40:42.180  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:42.181  7590  7590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:42.182  7590  7590 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-25 17:40:42.183  7590  7590 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 17:40:42.184  7590  7734 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 17:40:42.199  7590  7590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44e244
08-25 17:40:42.199  7590  7590 V BluetoothSapService: Sap Service onCreate
,08-25 17:40:42.202  7590  7590 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:40:42.202  7590  7590 V BluetoothSapService: state: 12
08-25 17:40:42.203  7590  7590 V BluetoothSapService: Starting SAP server process
08-25 17:40:42.205  7590  7590 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 17:40:42.194  7735  7735 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:42.194  7735  7735 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:42.206  7590  7736 V BluetoothSapService: Sap Service initRfcommSocket
08-25 17:40:42.207  1032  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:42.208  7590  7736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:40:42.209  7590  7736 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 17:40:42.209  7590  7736 V BluetoothSapService: Succeed to create listening socket 
08-25 17:40:42.209  7590  7736 V BluetoothSapService: Accepting socket connection...
08-25 17:40:42.227  7735  7735 V BT_SAP  : Event pipe created
08-25 17:40:42.228  7735  7735 V BT_SAP  : create_server_socket qcom.sap.server
08-25 17:40:42.228  7735  7735 V BT_SAP  : created socket fd 6
,08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:42.588  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:40:42.601  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:42.605  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:42.605  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39c5ce36 added. We now have 8 listener(s)
08-25 17:40:42.605  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:40:42.610  1032  2046 D WifiServiceImplEx: setWifiEnabled: false pid=6846, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:40:42.610  1032  2046 D WifiService: setWifiEnabled: false pid=6846, uid=10118
08-25 17:40:42.610  1032  2046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:40:42.615  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:42.618  1032  1048 D WifiServiceImplEx: setWifiEnabled: true pid=6846, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-25 17:40:42.621  1032  1048 D WifiService: setWifiEnabled: true pid=6846, uid=10118
08-25 17:40:42.621  1032  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:40:42.644  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 17:40:42.644  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:40:42.645  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-25 17:40:42.646  1032  1398 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 17:40:42.646  1032  1398 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 17:40:42.649  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 17:40:42.649  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:40:42.649  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 17:40:42.649  1032  1398 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:40:42.649  1032  1398 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 17:40:42.649  1032  1398 E WifiHW  : unknown target_country: EU , set to default
08-25 17:40:42.649  1032  1398 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 17:40:42.649  1032  1398 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 17:40:42.649  1032  1398 I WifiUtil: gEnableBmps=1
08-25 17:40:43.144  7590  7590 V BluetoothOppNotification: new notify threadi!
,08-25 17:40:43.156  7590  7590 V BluetoothOppNotification: send delay message
08-25 17:40:43.161  7590  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 17:40:43.164  7590  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c487304 on behalf of 
08-25 17:40:43.165  7590  7755 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 17:40:43.168  7590  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:43.169  7590  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36fc60ed on behalf of 
08-25 17:40:43.169  7590  7755 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:40:43.171  7590  7755 V BluetoothOppNotification: outbound notification was removed.
08-25 17:40:43.171  7590  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:40:43.172  7590  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@334bab22 on behalf of 
08-25 17:40:43.173  7590  7755 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:40:43.175  7590  7755 V BluetoothOppNotification: inbound notification was removed.
08-25 17:40:43.175  7590  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 17:40:43.176  7590  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23a869b3 on behalf of 
,08-25 17:40:43.229   307   892 D SoftapController: Softap fwReload - Ok
,08-25 17:40:43.239  1032  1398 E NetdConnector: NDC Command {65 softap fwreload wlan0 STA} took too long (586ms)
08-25 17:40:43.250  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:40:43.256   307   892 D CommandListener: Setting iface cfg
08-25 17:40:43.256   307   892 D CommandListener: Trying to bring down wlan0
08-25 17:40:43.272   307   892 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:40:43.278  1032  1398 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 17:40:43.294  7757  7757 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:40:43.294  7757  7757 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:43.312  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:43.312  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:43.312  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:43.315  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:40:43.332  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-25 17:40:43.345  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:40:43.357  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 17:40:43.357  1032  1398 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 17:40:43.358  1032  1398 D WifiMonitor: connecting to supplicant
,08-25 17:40:43.370  7757  7757 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 17:40:43.373  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:40:43.373  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:40:43.373  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:40:43.373  6952  6952 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 17:40:43.375  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:40:43.375  6952  6952 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:40:43.375  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 17:40:43.375  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:40:43.375  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:40:43.376  6952  6952 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:40:43.376  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 17:40:43.376  6952  6952 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:40:43.383  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:43.386  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:40:43.397  7042  7778 V FormManager: Network unavailable.
08-25 17:40:43.398  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:40:43.403  7042  7777 W FormManager: Network not available. Please check & try again.
08-25 17:40:43.406  7042  7778 V FormManager: Network unavailable.
08-25 17:40:43.412  7757  7757 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 17:40:43.413  7757  7757 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 17:40:43.415  1032  1094 D Tethering: InitialState.processMessage what=4
08-25 17:40:43.417  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:40:43.418  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:40:43.418  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:40:43.418  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:40:43.418  6952  6952 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:40:43.418  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:40:43.419  6952  6952 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:40:43.419  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 17:40:43.419  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:40:43.419  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:40:43.419  6952  6952 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:40:43.419  6952  6952 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:40:43.470  7757  7757 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 17:40:43.496  7757  7757 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 17:40:43.504  7757  7757 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-25 17:40:43.507  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:40:43.508  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 17:40:43.508  1032  7779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-25 17:40:43.508  1032  7779 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 17:40:43.509  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:40:43.509  1032  1398 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:40:43.510  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:43.511  1032  1398 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 17:40:43.512  1032  1398 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:43.512  1032  1398 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:43.513  1032  1398 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 17:40:43.513  1032  1398 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-25 17:40:43.514  1032  1398 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 17:40:43.514  1032  1398 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 17:40:43.514  1032  1398 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-25 17:40:43.515  1032  1398 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:40:43.515  1032  1398 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:40:43.515  1032  1398 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:40:43.515  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.516  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.516  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:40:43.516  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.516  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-25 17:40:43.521  1032  1398 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 17:40:43.521  1032  1398 D WifiNative-wlan0: SET update_config 1: returned true
08-25 17:40:43.521  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 17:40:43.522  1032  1398 D WifiConfigStore: Loading config and enabling all networks 
08-25 17:40:43.522  1032  1398 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 17:40:43.522  1938  1938 D WfdService: Waiting for WifiP2p enabling
08-25 17:40:43.522  1032  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 17:40:43.522  1032  1398 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 17:40:43.525  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:43.526  6846  6846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:43.529  1032  1398 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-25 17:40:43.530  6846  6846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:40:43.534  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:43.538  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:40:43.539  1032  1398 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 17:40:43.539  1032  1398 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 17:40:43.540  1032  1398 D WifiStateMachine: enableVerboseLogging : level 2
08-25 17:40:43.540  1032  1398 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 17:40:43.540  1032  1398 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 17:40:43.540  1032  1398 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 17:40:43.541  1032  1398 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 17:40:43.541  1032  1398 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 17:40:43.541  1032  1398 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 17:40:43.541  1032  1398 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 17:40:43.542  1032  1398 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 17:40:43.542  1032  1398 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 17:40:43.543  7757  7757 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 17:40:43.543  1032  1398 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 17:40:43.543  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:40:43.543  1032  1398 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 17:40:43.543  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:40:43.543  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 17:40:43.543  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-25 17:40:43.543  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:40:43.544  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:40:43.544  1032  1398 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 17:40:43.544  1032  1398 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 17:40:43.544  1032  1398 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 17:40:43.546  1032  1398 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:40:43.546  1032  1398 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 17:40:43.546  1938  1938 D WfdsService: Supplicant Connection state is changed : true
08-25 17:40:43.546  1032  1398 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 17:40:43.546  1032  1398 D WifiNative-HAL: Setting external_sim to 1
08-25 17:40:43.547  1032  1398 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 17:40:43.547  1938  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 17:40:43.547  1938  2326 D WfdsService: Set the WFDS Monitor: true
08-25 17:40:43.547  1032  1398 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 17:40:43.547  1938  2326 D WfdsMonitor: WfdsMonitorThread create
08-25 17:40:43.547  1032  1398 I WifiNative-HAL: startHal
08-25 17:40:43.547  1032  1398 D wifi    : setting scan oui 0x95366240
08-25 17:40:43.547  1938  2326 D WfdsMonitor: WFDS Monitor is created and started
08-25 17:40:43.547  1938  2326 D WfdsService: WiFi: Supplicant connection re-established
08-25 17:40:43.548  1032  1398 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:40:43.548  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:43.548  1032  1398 I WifiNative-HAL: startHal
08-25 17:40:43.548  1032  1398 D wifi    : setting scan oui 0x95366240
08-25 17:40:43.548  1032  1398 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 17:40:43.549  1032  1398 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 17:40:43.549  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 17:40:43.549  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 17:40:43.550  1938  7783 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 17:40:43.550  1938  7783 E CtrlSupplicant: Succeed to open control connection
08-25 17:40:43.550  1938  7783 E CtrlSupplicant: Succeed to open monitor connection
08-25 17:40:43.551  1032  1398 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 17:40:43.551  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:40:43.551  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:40:43.552  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:40:43.552  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 17:40:43.552  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 17:40:43.552  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 17:40:43.552  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:40:43.552  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:40:43.552  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:40:43.552  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:40:43.553  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:40:43.553  1938  7783 D WfdsMonitor: Supplicant connection established
08-25 17:40:43.553  1938  2326 D WfdsService: Connected to the supplicant for wfds
08-25 17:40:43.553  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:40:43.553  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 17:40:43.553  7757  7757 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 17:40:43.553  1032  1398 D WifiNativ,e-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 17:40:43.553  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:40:43.554  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:40:43.554  1032  1398 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:40:43.555  1032  1398 E WifiNative: : [205,271,105 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 17:40:43.555  1032  1398 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 17:40:43.555  1032  1398 D WifiNative-wlan0: RECONNECT: returned true
08-25 17:40:43.555  1032  1398 D WifiNative-wlan0: doString: [STATUS]
08-25 17:40:43.555  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:40:43.555  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:40:43.556  1032  1398 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 17:40:43.556  1032  1398 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:40:43.556  1032  1398 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:40:43.556  1032  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.557  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 17:40:43.557  1032  1398 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:40:43.557  1032  1032 D RttService: SCAN_AVAILABLE : 3
08-25 17:40:43.557  1032  1553 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.557  1032  1553 I WifiNative-HAL: startHal
08-25 17:40:43.557  1032  1398 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 17:40:43.557  1032  1553 D wifi    : getting scan capabilities on interface[1] = 0x95366240
08-25 17:40:43.557  1032  1553 D wifi    : failed to get capabilities : -3
08-25 17:40:43.557  1032  1553 E WifiScanningService: could not get scan capabilities
08-25 17:40:43.558  1032  1398 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 17:40:43.558  1032  1554 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.559   307   892 D CommandListener: Setting iface cfg
08-25 17:40:43.559   307   892 D CommandListener: Trying to bring up p2p0
,08-25 17:40:43.559  1032  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 17:40:43.559  1032  1388 D LGWifiP2pService: P2pEnablingState
08-25 17:40:43.559  1032  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.559  1032  1388 D LGWifiP2pService: P2p socket connection successful
08-25 17:40:43.559  1032  1388 D LGWifiP2pService: P2pEnabledState
08-25 17:40:43.559  1032  1398 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 17:40:43.560  1032  1398 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 17:40:43.560  1032  1398 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 17:40:43.561  1032  1398 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 17:40:43.561  1032  1398 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 17:40:43.561  7757  7757 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 17:40:43.562  1032  1398 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 17:40:43.562  1032  1398 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 17:40:43.562  1032  1398 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 17:40:43.562  1032  1398 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 17:40:43.562  1032  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 17:40:43.563  7757  7757 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 17:40:43.563  7042  7782 V FormManager: Network unavailable.
08-25 17:40:43.563  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=205280  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:43.565  7042  7781 W FormManager: Network not available. Please check & try again.
08-25 17:40:43.566  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=205283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:43.566  1032  1398 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 17:40:43.567  1032  1398 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 17:40:43.567  1032  1398 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 17:40:43.567  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 17:40:43.567  1032  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 17:40:43.568  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:40:43.568  7757  7757 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.568  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:40:43.568  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.568  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.568  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.569  7757  7757 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:40:43.569  7757  7757 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.569  1938  1938 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 17:40:43.569  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:43.569  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:43.569  1938  1938 D WfdsService: WifiP2pState is changed : true
08-25 17:40:43.569  7757  7757 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  1938  7783 D WfdsM,onitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.570  1938  2326 D WfdsService: Receive the WFDS_ENABLE Method
08-25 17:40:43.570  1938  7783 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.570  1938  2326 D WfdsService: Set the WFDS Monitor: true
08-25 17:40:43.570  1938  2326 D WfdsService: Connected to the supplicant for wfds
08-25 17:40:43.570  1938  2326 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 17:40:43.570  1032  1398 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 17:40:43.570  1032  7779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.570  1032  7779 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  7757  7757 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 17:40:43.570  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  1032  7779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.570  1032  7779 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.570  1032  1398 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:40:43.571  1032  1398 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:40:43.572  1032  1398 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:40:43.572  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 17:40:43.572  1938  2326 D WfdsService: selectPreferredScanChannel [36]
08-25 17:40:43.572  1938  2326 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-25 17:40:43.572  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 17:40:43.573  7757  7757 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:43.573  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 17:40:43.573  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:43.573  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:43.573  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:40:43.573  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.573  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.574  1032  1398 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 17:40:43.574  1032  1398 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 17:40:43.574  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:40:43.574  1032  1398 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 17:40:43.574  1032  1398 D WifiNative-wlan0: doBoolean: SCAN
,08-25 17:40:43.575  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:43.575  1032  1398 D WifiNative-wlan0: SCAN: returned false
08-25 17:40:43.575  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=205292  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:43.576  1032  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 17:40:43.576  1032  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 17:40:43.576  1032  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-25 17:40:43.576  1032  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 17:40:43.576  1032  1388 D LGWifiP2pService: before postfix = G3
08-25 17:40:43.576  1032  1388 D WifiServerServiceExt: postfix byte check : 2
08-25 17:40:43.576  1032  1388 D LGWifiP2pService: after postfix = G3
08-25 17:40:43.576  1032  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 17:40:43.577  1032  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 17:40:43.577  1032  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 17:40:43.577  1032  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 17:40:43.577  1032  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 17:40:43.578  1032  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 17:40:43.578  1032  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 17:40:43.578  1032  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 17:40:43.578  1032  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-25 17:40:43.579  1032  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 17:40:43.581  1032  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 17:40:43.581  1032  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 17:40:43.581  1032  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 17:40:43.581  1032  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 17:40:43.582  1032  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 17:40:43.582  1032  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 17:40:43.582  1032  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 17:40:43.582  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=205299  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:40:43.582  1032  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 17:40:43.583  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:43.584  4341  4341 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:40:43.585  1938  1938 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 17:40:43.585  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:43.586  1938  1938 D WfdsService: isConnected: false
08-25 17:40:43.586  1938  1938 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 17:40:43.586  1938  1938 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 17:40:43.586  1938  1938 D WfdsService: Update P2p Interface State: 3
,08-25 17:40:43.587  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.587  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:43.587  1032  1398 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:43.587  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:40:43.588  1032  1398 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:43.588  1032  1398 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:43.589  1032  1398 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:43.590  1032  1398 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:40:43.591  1032  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 17:40:43.591  1032  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 17:40:43.592  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:43.592  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 17:40:43.592  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:43.592  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 17:40:43.592  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:40:43.593  1032  1388 D LGWifiP2pService: InactiveState
08-25 17:40:43.593  1032  1388 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.593  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.593  1032  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 17:40:43.593  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:40:43.594  7757  7757 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.594  1032  7779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:40:43.594  1032  7779 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.594  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.594  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:40:43.594  7757  7757 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:40:43.595  7757  7757 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  1032  7779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.595  1032  7779 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  7757  7757 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  1032  7779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.595  1032 , 7779 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  1032  7779 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.595  1032  7779 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:40:43.596  1938  7783 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:40:43.596  1938  7783 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.596  1938  7783 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:40:43.596  1032  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 17:40:43.596  1032  1388 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.596  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.596  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.596  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1032 E WifiServerServiceExt: No p2p device connected
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.597  1032  1388 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:43.598  1938  2326 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 17:40:43.598  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:43.599  7042  7782 V FormManager: Network unavailable.
08-25 17:40:43.601  4341  7784 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:40:43.606  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:43.606  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:43.607  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:43.609  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:43.611  4341  7785 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:40:43.611  4341  7785 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 17:40:43.614  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:43.619  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:43.620  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:43.621  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:40:43.624  7396  7396 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 17:40:43.624  7396  7396 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-25 17:40:43.624  7396  7396 V [BNRBootReceiver]: Boot Receiver Return
,08-25 17:40:43.629  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:43.634  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:43.638  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:40:43.642  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:43.642  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:43.644  7001  7001 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:40:43.660  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:40:43.661  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:40:43.665  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 17:40:43.665  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 17:40:43.667  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3ed4d3c8 Bundle[{}]
08-25 17:40:43.667  6846  6911 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 17:40:43.667  6846  6911 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 17:40:43.668  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 17:40:43.669  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 17:40:43.669  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 17:40:43.670  6846  6911 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 17:40:43.675  6846  6911 I System.out: Running OutgoingSocketThread
08-25 17:40:43.678  6846  7786 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 872)
,08-25 17:40:43.680  6846  7786 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57934
08-25 17:40:43.681  6846  7786 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 17:40:44.209  7757  7757 E wpa_supplicant: USIM:  scard_init function
08-25 17:40:44.210  7757  7757 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-25 17:40:44.220  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 17:40:44.221  1032  7779 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 17:40:44.221  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 17:40:44.221  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: WPS-AP-AVAILABLE 
08-25 17:40:44.224  1032  1398 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 17:40:44.224  1032  1398 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 17:40:44.224  1032  1398 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 17:40:44.225  1032  1398 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 17:40:44.225  1032  1398 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 17:40:44.231  1032  7779 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 17:40:44.231  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:40:44.231  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 17:40:44.251  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=205968  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 17:40:44.259  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.259  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:44.262  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.265  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.265  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.265  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-25 17:40:44.269  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=205986  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 17:40:44.271  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:44.271  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 17:40:44.276  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 17:40:44.286  6952  6952 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 17:40:44.291  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:40:44.305  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:44.314  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.321  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:40:44.323  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.324  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:40:44.342  7757  7757 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 17:40:44.350  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 17:40:44.350  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 17:40:44.350  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 17:40:44.350  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 17:40:44.351  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:40:44.351  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:40:44.355  7757  7757 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:40:44.355  7757  7757 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:40:44.358  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=206074  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 17:40:44.358  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=206075  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-25 17:40:44.364  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:40:44.364  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:40:44.365  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 17:40:44.365  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:40:44.365  1032  7779 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:40:44.365  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 17:40:44.365  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:40:44.365  1032  7779 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:40:44.365  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:40:44.365  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:40:44.367  1032  1398 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 49 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206084
08-25 17:40:44.367  1032  1398 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 49 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206084
08-25 17:40:44.368  1032  1398 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 49 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206084
08-25 17:40:44.368  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 49 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206085
08-25 17:40:44.368  1032  1398 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 49 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206085
08-25 17:40:44.369  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=206086  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 17:40:44.372  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:40:44.383  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.383  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:44.383  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.383  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.383  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 17:40:44.384  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:40:44.403  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.403  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.403  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 17:40:44.407  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.407  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:44.407  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=206124  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 17:40:44.408  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:44.408  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 17:40:44.410  1032  1398 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=206126  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 17:40:44.410  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=206127  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 17:40:44.411  1032  1398 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206127
08-25 17:40:44.411  1032  1398 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206128
08-25 17:40:44.413  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:40:44.418  1032  1398 D WifiNative-wlan0: doString: [STATUS]
08-25 17:40:44.419  1032  7779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:40:44.419  1032  7779 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:40:44.419  1032  1398 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 17:40:44.421  1032  1398 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 17:40:44.423  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.429  1032  1398 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 17:40:44.429  1032  1398 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 17:40:44.439  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.439  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.440  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-25 17:40:44.458  1032  1398 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 17:40:44.461  1032  1470 D ConnectivityService: Got NetworkAgent Messenger
,08-25 17:40:44.461  1032  1470 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 17:40:44.461  1032  1470 D ConnectivityService: NetworkAgent connected
08-25 17:40:44.462  1032  1398 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:40:44.462  1032  1398 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:40:44.463  1032  1398 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:40:44.464  1032  1398 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:40:44.466  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.466  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.466  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 17:40:44.467  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.467  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:44.470  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.473  1032  1398 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:40:44.473  1032  1398 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:40:44.473  1032  1398 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-25 17:40:44.474  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.474  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:44.475  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.476  1032  1398 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:40:44.476  1032  1398 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:40:44.479  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:44.482  1032  1398 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:40:44.484   307   892 D CommandListener: Setting iface cfg
,08-25 17:40:44.487  1032  1398 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 17:40:44.488  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.489  1032  7807 D DhcpStateMachine: StoppedState
,08-25 17:40:44.490  1032  7807 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.490  1032  7807 D DhcpStateMachine: WaitBeforeStartState
08-25 17:40:44.492  1032  1398 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=206208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:40:44.492  1032  1398 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=206209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:40:44.493  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=206209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:40:44.493  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:44.494  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:44.494  1032  1398 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:44.494  1032  1398 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:44.495  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:44.495  1032  1398 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:40:44.497  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.497  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.497  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:40:44.497  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:44.497  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 17:40:44.501  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:40:44.502  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:40:44.502  6952  6952 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:40:44.502  6952  6952 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:40:44.503  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:44.503  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 17:40:44.503  1032  1398 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=206220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-25 17:40:44.504  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:40:44.505  1032  1398 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=206221  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:40:44.505  6952  6952 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:40:44.505  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 17:40:44.505  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:40:44.505  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:40:44.505  6952  6952 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:40:44.505  6952  6952 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 17:40:44.505  6952  6952 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:40:44.506  1032  1398 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=206223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:40:44.509  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.509  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15354] from screen [on:0 period:-1034138019] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 17:40:44.513  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1034138015] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 17:40:44.513  1032  1398 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 17:40:44.515  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:44.518  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:44.518  1032  1470 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 17:40:44.519  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:44.519  1032  1398 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:44.519  1032  1398 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:44.519  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.520  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:44.521  1032  1398 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:40:44.522  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
08-25 17:40:44.522  1032  1470 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 17:40:44.522  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
08-25 17:40:44.522  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 17:40:44.522  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 17:40:44.523  1032  1398 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 17:40:44.523  1032  1398 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 17:40:44.524  1032  1398 D WifiNative-wlan0: SET ps 0: returned true
08-25 17:40:44.524  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 17:40:44.524  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 17:40:44.524  1032  1398 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 17:40:44.525  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@235fcae6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.525  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@235fcae6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.525  1032  7807 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.525  1032  7807 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 17:40:44.525  1032  1398 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 17:40:44.525  1032  1398 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 17:40:44.525  1032  1398 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 17:40:44.525  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.526   307   892 D CommandListener: Setting iface cfg
08-25 17:40:44.526   307   892 D CommandListener: Trying to bring up wlan0
08-25 17:40:44.527  1032  1398 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-25 17:40:44.532  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 17:40:44.532  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:40:44.532  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 17:40:44.532  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 17:40:44.532  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:40:44.532  1032  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.532  1032  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.532  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:40:44.533  1032  1398 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:40:44.533  1032  1398 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 17:40:44.533  7757  7757 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 17:40:44.533  1032  1398 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 17:40:44.533  1032  1398 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:40:44.536  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.536  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.537  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:40:44.539  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.543  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:44.548  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.549  1032  1398 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:40:44.550  1032  1470 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 17:40:44.550  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:44.550  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:44.551  1032  1398 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:44.551  1032  1398 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:44.552  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:44.552  1032  1398 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:44.553  1032  1470 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 17:40:44.553  1032  1398 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 17:40:44.553  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 17:40:44.553  1032  1398 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-25 17:40:44.554  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.554  1032  1470 D ConnectivityService: ignoring duplicate network state non-change
08-25 17:40:44.554  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.555  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:40:44.557  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.557  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.557  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 17:40:44.558  1032  1470 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 17:40:44.560  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.560  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:40:44.561  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.562  1032  1470 D ConnectivityService: Adding iface wlan0 to network 101
08-25 17:40:44.563  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.563  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.563  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 17:40:44.563  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 17:40:44.573  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.573  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 17:40:44.575  1938  1938 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 17:40:44.578  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.578  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.578  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.578  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 17:40:44.579  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.580  1032  1398 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 17:40:44.581  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 17:40:44.584  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.584  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 17:40:44.584  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:40:44.585  1032  1470 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 17:40:44.585  1032  1470 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 17:40:44.585  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.585  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:40:44.585  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 17:40:44.586  1032  1470 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 17:40:44.587   307   892 E Netd    : netlink response contains error (File exists)
08-25 17:40:44.587  1032  1470 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 17:40:44.588  1032  1470 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 17:40:44.588  1032  1470 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 17:40:44.588  1032  1470 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 17:40:44.591  1032  1470 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 17:40:44.591  1032  1470 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.591  1032  1470 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.592  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.592  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 17:40:44.592  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:40:44.592  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 17:40:44.593  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:40:44.593  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 17:40:44.593  1032  1470 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.593  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.594  1032  1470 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:40:44.594  1032  1470 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:44.594  1032  1470 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 17:40:44.594  1032  1470 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.594  1032  1470 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 17:40:44.594  1032  1470 D ConnectivityService: currentScore = 0, newScore = 20
08-25 17:40:44.594  1032  1470 D ConnectivityService:    accepting network in place of null
08-25 17:40:44.594  1032  1470 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.594  1032  1,398 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.594  1032  1398 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:40:44.595   307  7819 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 17:40:44.597  1849  1849 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.597  1849  1849 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-25 17:40:44.600  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:44.600  1032  1470 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 17:40:44.600  1032  1470 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 17:40:44.600  1032  1470 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:40:44.602  1032  1470 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:40:44.602  1032  1470 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 17:40:44.602  1032  1470 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 17:40:44.603  1032  1470 D ConnectivityService: validation of new default Network = false
08-25 17:40:44.603  1032  1470 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 17:40:44.603  1032  1470 D DSQN    : enableDataServiceNotify 
08-25 17:40:44.603  1032  1470 D DSQN    : start dsqn bin
08-25 17:40:44.604  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 17:40:44.604  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:40:44.604  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:40:44.604  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:40:44.608  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.611  1032  1470 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.611  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.611  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:44.611  1032  1470 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:44.594  7820  7820 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:44.594  7820  7820 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcont,ext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:40:44.614  1600  2068 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:40:44.622  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.622  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.623  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:40:44.625  7820  7820 E DSQN    : DSQN ssw
08-25 17:40:44.634  1032  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-25 17:40:44.642  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.647  1813  7824 I CheckinService: active receiver: enabled
,08-25 17:40:44.649   307  7819 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 17:40:44.649  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:40:44.650  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.650  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.659  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:40:44.661  1813  7824 I CheckinService: Preparing to send checkin request
08-25 17:40:44.661  1813  7824 I EventLogService: Accumulating logs since 1472139496500
08-25 17:40:44.664  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.668  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.668  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.671  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:40:44.674  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.677  6846  6911 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 873)
08-25 17:40:44.677  6846  6911 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 873)
08-25 17:40:44.680  6846  6911 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-25 17:40:44.681  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:44.681  6846  6911 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 17:40:44.681  6846  6911 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 879)
,08-25 17:40:44.684  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.684  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d17137 added. We now have 2 listener(s)
08-25 17:40:44.685  1032  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:40:44.685   307  7819 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 17:40:44.687  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.687  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.687  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.687  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.687  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.687  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3626a4 added. We now have 9 listener(s)
08-25 17:40:44.687  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.688  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:44.689  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:44.692  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.693  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:44.693  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:44.693  7001  7001 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:40:44.696  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:40:44.698  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.698  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:44.698  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.698  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171897c2 added. We now have 3 listener(s)
,08-25 17:40:44.700  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.700  1032  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.701  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.702  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 17:40:44.703  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.703  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.703  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.703  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.703  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c1e9d3 added. We now have 10 listener(s)
08-25 17:40:44.704  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.704  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:44.704  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:40:44.704  1813  7824 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-25 17:40:44.704  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:44.704  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.704  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.704  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.704  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.704  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d17137 removed from the list
08-25 17:40:44.704  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.704  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3626a4 removed from the list
08-25 17:40:44.704  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:44.704  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.705  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.705  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.706  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.706  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.706  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.706  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3626a4 not in the list
08-25 17:40:44.706  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.706  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.707  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:44.707  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.707  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.707  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.707  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c1e9d3 removed from the list
08-25 17:40:44.707  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.707  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.707  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.707  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.708  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171897c2 remo,ved from the list
08-25 17:40:44.708  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.708  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25010910 added. We now have 2 listener(s)
08-25 17:40:44.710  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:44.710  1032  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.711   307   891 D LGDataListener: argv[0]=dsqncommand
08-25 17:40:44.711   307   891 D LGDataListener: argv[1]=wlan0
08-25 17:40:44.711   307   891 D LGDataListener: argv[2]=1
08-25 17:40:44.711   307   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 17:40:44.712  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 17:40:44.712  1032  1092 D DSQN    : start to monitor internet connection
,08-25 17:40:44.714  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.714  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.714  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.714  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.714  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2493ec09 added. We now have 9 listener(s)
08-25 17:40:44.714  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.715  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:44.719  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:44.724  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:44.726  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.726  1032  7807 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 17:40:44.727  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.727  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:44.727  1032  7807 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 17:40:44.727  1032  7807 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 17:40:44.727  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.727  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37502f added. We now have 3 listener(s)
08-25 17:40:44.728  1032  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.729  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.730  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.730  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.731  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.731  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.731  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2555a63c added. We now have 10 listener(s)
08-25 17:40:44.731  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.731  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:44.731  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:40:44.731  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:40:44.731  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:44.731  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:40:44.714  7828  7828 W dhcpcd  : typ,e=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:44.714  7828  7828 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:40:44.732  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.733  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.734  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:40:44 GMT], X-Android-Received-Millis=[1472139644734], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472139644710]}
08-25 17:40:44.734  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 17:40:44.734  1032  7796 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 17:40:44.734  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:40:44.735  1032  1470 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.735  7828  7828 I dhcpcd  : version 5.5.6 starting
08-25 17:40:44.735  1032  1470 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.735  1032  1470 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:40:44.735  1032  1470 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:44.735  1032  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.735  1032  1470 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 17:40:44.735  1032  1470 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 17:40:44.735  1032  1470 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 17:40:44.735  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.735  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:44.735  1032  1470 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:44.736  1032  1470 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.736  1032  1470 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 17:40:44.736  7828  7828 E dhcpcd  : get_duid: m
,08-25 17:40:44.736  7828  7828 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 17:40:44.736  7828  7828 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 17:40:44.737  1600  2068 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:40:44.737  1032  1398 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.737  1032  1398 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:40:44.737  1849  1849 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:44.738  1849  1849 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:40:44.742  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.743  7001  7001 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 17:40:44.744  7001  7001 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 17:40:44.745  7001  7001 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 17:40:44.746  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:40:44.746  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:40:44.747  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:40:44.748  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:40:44.749  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.751  6846  6911 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:40:44.751  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:44.751  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:44.753  6973  6973 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 17:40:44.754  6973  6973 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:40:44.754  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:44.754  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:40:44.754  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:44.754  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.754  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.754  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.754  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.754  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25010910 removed from the list
08-25 17:40:44.754  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.754  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2493ec09 removed from the list
08-25 17:40:44.754  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:44.754  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.757  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.757  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.758  6952  6952 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:40:44.762  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.762  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.762  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.762  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2493ec09 not in the list
08-25 17:40:44.762  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.763  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:40:44.764  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.764  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:44.764  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:44.765  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.765  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.765  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2555a63c removed from the list
08-25 17:40:44.765  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.765  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.765  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.765  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.765  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37502f removed from the list
08-25 17:40:44.765  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.765  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df2c04b added. We now have 2 listener(s)
08-25 17:40:44.765  1032  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.766  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:40:44.766  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.767  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:40:44.769  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.769  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.769  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.769  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.769  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf4ea28 added. We now have 9 listener(s)
08-25 17:40:44.769  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.769  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:44.773  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:40:44.776  6952  6952 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:44.777  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:44.778  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.778  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:44.779  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.779  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d7c30e6 added. We now have 3 listener(s)
08-25 17:40:44.780  1032  1701 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.780  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.781  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.781  7001  7001 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:40:44.782  7001  7001 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:40:44.782  7001  7001 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 17:40:44.783  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.783  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.783  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.783  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:40:44.783  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cab1627 added. We now have 10 listener(s)
08-25 17:40:44.783  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.783  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:44.783  7001  7001 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 17:40:44.783  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:44.783  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:40:44.783  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:40:44.783  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:44.783  7001  7001 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 17:40:44.783  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:40:44.786  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:40:44.788  1032  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.791  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:40:44.791  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:40:44.792  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:40:44.792  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.793  7828  7828 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 17:40:44.793  7828  7828 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 17:40:44.793  7828  7828 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 17:40:44.793  7828  7828 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 17:40:44.793  6846  6911 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:40:44.793  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:44.793  7828  7828 D dhcpcd  : wlan0: sending REQUEST (xid 0x97436513), next in 4.91 seconds
08-25 17:40:44.794  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:44.794  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:44.794  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.794  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.794  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.794  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.794  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df2c04b removed from the list
08-25 17:40:44.794  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.794  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf4ea28 removed from the list
08-25 17:40:44.794  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:44.794  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.794  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.794  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.795  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.795  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.795  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:40:44.795  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf4ea28 not in the list
08-25 17:40:44.795  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.795  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.798  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.798  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:44.798  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:44.798  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.798  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.798  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cab1627 removed from the list
08-25 17:40:44.798  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.798  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.798  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.798  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.798  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d7c30e6 removed from the list
08-25 17:40:44.799  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.799  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a7572 added. We now have 2 listener(s)
08-25 17:40:44.799  1032  1701 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.801  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.801  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.802  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.802  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.802  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a8edc3 added. We now have 9 listener(s)
08-25 17:40:44.802  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.802  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:44.813  7828  7828 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 17:40:44.842  7828  7828 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 17:40:44.842  7828  7828 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-25 17:40:44.842  7828  7828 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 17:40:44.842  7828  7828 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 17:40:44.842  7828  7828 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 17:40:44.843  7828  7828 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 17:40:44.843  7828  7828 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 17:40:44.843  7828  7828 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 17:40:44.846  1032  2046 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7835 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 17:40:44.850  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:44.856  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:40:44.858  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:40:44.859  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:44.859  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.859  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1792e979 added. We now have 3 listener(s)
08-25 17:40:44.861  1032  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:40:44.863  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.865  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.868  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.868  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.869  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.869  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.869  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194676be added. We now have 10 listener(s)
08-25 17:40:44.869  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.869  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:44.869  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:40:44.869  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:40:44.869  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:40:44.869  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:40:44.874  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:40:44.875  1032  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.879  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:40:44.879  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:40:44.881  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:40:44.882  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:40:44.886  6846  6911 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:40:44.892  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:44.893  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:44.893  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:44.893  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.893  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.893  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.893  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.893  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a7572 removed from the list
08-25 17:40:44.893  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.893  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a8edc3 removed from the list
08-25 17:40:44.893  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:44.893  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.894  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.894  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.895  7835  7835 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 17:40:44.895  7835  7835 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 17:40:44.898  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.898  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.898  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.898  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a8edc3 not in the list
08-25 17:40:44.898  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.898  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.898  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.899  6846  6911 D BluetoothLeScanner: could not find callback wrapper
08-25 17:40:44.899  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:40:44.899  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.899  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.899  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194676be removed from the list
08-25 17:40:44.899  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.899  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.899  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.899  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.899  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1792e979 removed from the list
08-25 17:40:44.900  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.900  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fcfa435 added. We now have 2 listener(s)
08-25 17:40:44.900  1032  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.903  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.903  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.903  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.903  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.903  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f40ca added. We now have 9 listener(s)
08-25 17:40:44.903  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.903  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:40:44.906  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: bind: Binding a new listener
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:40:44.908  6846  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:40:44.912  6846  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:40:44.912  6846  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:40:44.913  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:40:44.913  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4b2d58 added. We now have 3 listener(s)
08-25 17:40:44.914  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.914  1032  1701 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:40:44.914  7835  7835 I MultiDex: VM with version 2.1.0 has multidex support
,08-25 17:40:44.914  7835  7835 I MultiDex: install
08-25 17:40:44.914  7835  7835 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-25 17:40:44.916  6846  6846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:40:44.917  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:40:44.917  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:40:44.917  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:40:44.917  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:40:44.917  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34e34eb1 added. We now have 10 listener(s)
08-25 17:40:44.917  6846  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:40:44.918  6846  6911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:40:44.918  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:44.918  6846  6911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:40:44.919  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.919  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.919  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:40:44.919  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.919  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fcfa435 removed from the list
08-25 17:40:44.919  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.919  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f40ca removed from the list
08-25 17:40:44.919  6846  6911 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:40:44.919  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.920  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.920  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.920  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.920  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.920  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:40:44.921  6846  6911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256f40ca not in the list
08-25 17:40:44.921  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.921  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:40:44.925  7835  7835 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 17:40:44.926  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:40:44.926  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:40:44.926  6846  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:40:44.926  6846  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34e34eb1 removed from the list
,08-25 17:40:44.927  6846  6911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:40:44.927  6846  6911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:40:44.927  6846  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:40:44.927  6846  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:40:44.927  6846  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4b2d58 removed from the list
08-25 17:40:44.928  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 17:40:44.928  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 17:40:44.928  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 17:40:44.928  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:40:44.928  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 17:40:44.928  6846  6911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:40:44.930  2187  2187 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 17:40:44.939  2187  2187 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-25 17:40:44.940  2187  2187 D c       : Getting all permits...
08-25 17:40:44.940  2187  2187 D a       : Opening database...
08-25 17:40:44.940  6846  7865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 886, name: My test thread name)
08-25 17:40:44.940  6846  7865 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 886, thread name: My test thread name)
08-25 17:40:44.940  6846  7865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 886, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 17:40:44.944  6846  7868 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: My test thread name)
08-25 17:40:44.944  6846  7868 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 888, thread name: My test thread name)
08-25 17:40:44.944  6846  7868 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 888, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 17:40:44.944  2187  2187 D a       : Opening database auth.proximity.permit_store...
08-25 17:40:44.945  2187  2187 D a       : Closing database...
08-25 17:40:44.953  6846  6911 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 17:40:44.953  6846  6911 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 17:40:44.953  6846  6911 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 17:40:44.953  6846  6911 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 17:40:44.953  6846  6911 D com.test.thalitest.ThaliTestRunner: Total duration: 22989 ms
,08-25 17:40:44.954  6846  6911 I jxcore-log: Total number of executed tests:  80
08-25 17:40:44.954  6846  6911 I jxcore-log: 
08-25 17:40:44.955  6846  6911 I jxcore-log: Number of passed tests:  80
08-25 17:40:44.955  6846  6911 I jxcore-log: 
08-25 17:40:44.955  6846  6911 I jxcore-log: Number of failed tests:  0
08-25 17:40:44.955  6846  6911 I jxcore-log: 
08-25 17:40:44.955  6846  6911 I jxcore-log: Number of ignored tests:  0
08-25 17:40:44.955  6846  6911 I jxcore-log: 
08-25 17:40:44.955  6846  6911 I jxcore-log: Total duration:  22989
08-25 17:40:44.955  6846  6911 I jxcore-log: 
08-25 17:40:44.956  6846  6911 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 17:40:44.956  6846  6911 I jxcore-log: 
08-25 17:40:44.960  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.960  6846  6911 I jxcore-log: 
08-25 17:40:44.967  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.967  6846  6911 I jxcore-log: 
08-25 17:40:44.967  6846  6846 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 17:40:44.968  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.968  6846  6911 I jxcore-log: 
,08-25 17:40:44.968  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.968  6846  6911 I jxcore-log: 
08-25 17:40:44.969  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.969  6846  6911 I jxcore-log: 
08-25 17:40:44.973  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.973  6846  6911 I jxcore-log: 
08-25 17:40:44.977  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:40:44.977  6846  6911 I jxcore-log: 
08-25 17:40:44.979  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:40:44.979  6846  6911 I jxcore-log: 
08-25 17:40:44.980  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.980  6846  6911 I jxcore-log: 
,08-25 17:40:44.981  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.981  6846  6911 I jxcore-log: 
08-25 17:40:44.982  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:40:44.982  6846  6911 I jxcore-log: 
08-25 17:40:44.983  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:40:44.983  6846  6911 I jxcore-log: 
08-25 17:40:44.984  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:40:44.984  6846  6911 I jxcore-log: 
08-25 17:40:44.985  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.985  6846  6911 I jxcore-log: 
08-25 17:40:44.986  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.986  6846  6911 I jxcore-log: 
08-25 17:40:44.987  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.987  6846  6911 I jxcore-log: 
08-25 17:40:44.988  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.988  6846  6911 I jxcore-log: 
08-25 17:40:44.989  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.989  6846  6911 I jxcore-log: 
08-25 17:40:44.989  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.989  6846  6911 I jxcore-log: 
08-25 17:40:44.990  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.990  6846  6911 I jxcore-log: 
08-25 17:40:44.991  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:40:44.991  6846  6911 I jxcore-log: 
,08-25 17:40:44.992  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:40:44.992  6846  6911 I jxcore-log: 
08-25 17:40:44.993  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:40:44.993  6846  6911 I jxcore-log: 
08-25 17:40:44.994  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.994  6846  6911 I jxcore-log: 
08-25 17:40:44.994  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.994  6846  6911 I jxcore-log: 
08-25 17:40:44.995  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.995  6846  6911 I jxcore-log: 
08-25 17:40:44.996  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.996  6846  6911 I jxcore-log: 
08-25 17:40:44.996  6846  6911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:40:44.996  6846  6911 I jxcore-log: 
08-25 17:40:45.131  1032  7807 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 17:40:45.135  1032  7807 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 17:40:45.135  1032  7807 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 17:40:45.136  1032  7807 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 17:40:45.136  1032  7807 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 17:40:45.136  1032  7807 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 17:40:45.136  1032  7807 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 17:40:45.136  1032  7807 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 17:40:45.137  1032  7807 D DhcpStateMachine: RunningState
08-25 17:40:45.307  7878  7878 D AndroidRuntime: 
08-25 17:40:45.307  7878  7878 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 17:40:45.312  7878  7878 D AndroidRuntime: CheckJNI is OFF
08-25 17:40:45.421  7835  7852 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:40:45.422  7835  7852 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:40:45.469  7893  7893 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 17:40:45.486  7878  7878 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 17:40:45.504  1032  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 17:40:45.506  1032  1090 I ActivityManager: Killing 6846:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-25 17:40:45.544  1032  1919 I WindowState: WIN DEATH: Window{23a97143 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 17:40:45.548  1032  1462 D WifiService: Client connection lost with reason: 4
08-25 17:40:45.551  1032  1919 D InputDispatcher: Window went away: Window{23a97143 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 17:40:45.564  7893  7893 I dex2oat : dex2oat took 94.256ms (threads: 4)
,08-25 17:40:45.583  7835  7852 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:40:45.583  7835  7852 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:40:45.583  7835  7852 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:40:45.583  7835  7852 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:40:45.583  7835  7852 I Adreno-EGL: Remote Branch: 
08-25 17:40:45.583  7835  7852 I Adreno-EGL: Local Patches: 
08-25 17:40:45.583  7835  7852 I Adreno-EGL: Reconstruct Branch: 
,08-25 17:40:45.682  7835  7852 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:40:45.682  7835  7852 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:40:45.682  7835  7852 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:40:45.682  7835  7852 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:40:45.682  7835  7852 I Adreno-EGL: Remote Branch: 
08-25 17:40:45.682  7835  7852 I Adreno-EGL: Local Patches: 
08-25 17:40:45.682  7835  7852 I Adreno-EGL: Reconstruct Branch: 
,08-25 17:40:45.734  1032  1090 I ActivityManager:   Force finishing activity ActivityRecord{42378c u0 com.test.thalitest/.MainActivity t6}
,08-25 17:40:45.768  7835  7852 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:40:45.768  7835  7852 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:40:45.768  7835  7852 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:40:45.768  7835  7852 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:40:45.768  7835  7852 I Adreno-EGL: Remote Branch: 
08-25 17:40:45.768  7835  7852 I Adreno-EGL: Local Patches: 
08-25 17:40:45.768  7835  7852 I Adreno-EGL: Reconstruct Branch: 
,08-25 17:40:45.781   336   346 E GBMv2   : DFP En is all cleared set to be enabled
08-25 17:40:45.789  1032  1047 W ActivityManager: Spurious death for ProcessRecord{14a44607 6846:com.test.thalitest/u0a118}, curProc for 6846: null
08-25 17:40:45.790  2029  2029 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 17:40:45.791  2029  2029 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-25 17:40:45.792  1032  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 17:40:45.793  1032  1103 I ActivityManager:   Force finishing activity ActivityRecord{42378c u0 com.test.thalitest/.MainActivity t6 f}
08-25 17:40:45.793  1032  1103 W ActivityManager: Duplicate finish request for ActivityRecord{42378c u0 com.test.thalitest/.MainActivity t6 f}
,08-25 17:40:45.835  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 17:40:45.835  2029  2120 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-25 17:40:45.836  1938  3967 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 17:40:45.837  1938  3967 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c6ecd94 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 17:40:45.838  1938  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 17:40:45.838  1938  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2248d03d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 17:40:45.839  1901  1901 D ActionManagerService: notifyUserLog: 1000003
08-25 17:40:45.840  3810  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 17:40:45.840  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 17:40:45.841  2029  2029 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-25 17:40:45.842  2029  2029 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 17:40:45.844  2029  2029 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 17:40:45.853  1901  1901 D ActionManagerService: notifyUserLog: 1000004
08-25 17:40:45.853  3810  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 17:40:45.852  4631  4631 I art     : Explicit concurrent mark sweep GC freed 739(42KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 572us total 40.621ms
,08-25 17:40:45.856  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 17:40:45.859  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-25 17:40:45.862  3810  3810 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 17:40:45.863  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 17:40:45.863  7590  7590 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 17:40:45.863  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 17:40:45.875  2503  2684 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 17:40:45.878  1032  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 17:40:45.905  1032  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 17:40:45.906  1032  1700 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:40:45.916  6488  6488 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 17:40:45.917  4524  4524 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 17:40:45.917  4524  4524 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 17:40:45.917  4524  4524 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 17:40:45.917  4524  4524 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 17:40:45.918  4524  4524 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:40:45.918  4524  4524 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:40:45.918  4524  4524 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:40:45.918  4524  4524 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:40:45.918  4524  4524 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:40:45.918  4524  4524 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:40:45.918  4524  4524 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:40:45.918  4524  4524 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:40:45.925  1032  1032 D administrator: Handling package changes for user 0
,08-25 17:40:45.952  1032  1920 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7905 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 17:40:45.958  1813  1813 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-25 17:40:45.959  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 17:40:45.961  3810  3825 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , display: false
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , animation: false }
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , display: false
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , animation: false }
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , display: false
08-25 17:40:45.968  2029  2029 I GBoardWebViewUtils: , animation: false }
,08-25 17:40:45.970  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-25 17:40:45.971  1866  1866 D SplitUIService: removed split : 
08-25 17:40:45.977  1032  1992 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:40:45.978  1032  1992 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:40:45.983  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 17:40:45.983  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 17:40:45.987  2029  7921 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 17:40:46.013  2187  2187 I ConfigService: onCreate
08-25 17:40:46.013  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 17:40:46.019  2187  2187 I ConfigService: onBind returning update interface
,08-25 17:40:46.021  1813  1813 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-25 17:40:46.025  1032  1955 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 17:40:46.025  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 17:40:46.025  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:40:46.026  7590  7590 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 17:40:46.027  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 17:40:46.027  2187  2187 I ConfigService: onBind returning config service
08-25 17:40:46.031  2187  2187 I ConfigService: onDestroy
,08-25 17:40:46.044  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-25 17:40:46.046  1813  7928 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 17:40:46.047  1032  1047 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:40:46.051  1866  1866 D SplitUIManager: split_name #11 / not available #0
08-25 17:40:46.051  1866  1866 I SplitUIService: split app #11
,08-25 17:40:46.056   307  7931 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 17:40:46.056   307  7931 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-25 17:40:46.059  7905  7905 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-25 17:40:46.089  1032  1701 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7932 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 17:40:46.095   307  7931 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-25 17:40:46.104  1600  1658 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 17:40:46.104  1600  1658 D KeyguardModel: createShortcutInfo...
,08-25 17:40:46.106  1600  1658 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 17:40:46.106  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.110  1032  1103 I art     : Explicit concurrent mark sweep GC freed 79255(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 1.887ms total 232.139ms
08-25 17:40:46.115  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 17:40:46.115  1600  1658 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:40:46.116  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 17:40:46.117  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:40:46.129  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 17:40:46.129  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 17:40:46.129  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 17:40:46.132  1032  1398 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:46.133  1032  1398 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:46.133  1032  1398 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:46.133  1032  1398 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:46.133  1032  1398 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:46.134  1032  1398 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:40:46.134  1032  1470 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-25 17:40:46.134  1032  1470 D ConnectivityService: identical MTU - not setting
08-25 17:40:46.134  1032  1470 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 17:40:46.134  1032  1470 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 17:40:46.134  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:40:46.134  1032  1470 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:46.135  1032  1470 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:40:46.135  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 17:40:46.135  1600  1658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:40:46.135  1600  1658 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 17:40:46.136  1600  2068 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 17:40:46.137  1600  1658 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 17:40:46.137  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.137  5942  7952 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-25 17:40:46.137  1032  1575 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 17:40:46.139  2029  2029 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 17:40:46.141  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 17:40:46.141  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:40:46.145  1600  1658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:40:46.145  1600  1658 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 17:40:46.147  1813  7954 I PeopleContactsSync: CP2 sync disabled
08-25 17:40:46.152  1600  1658 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 17:40:46.152  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.154  1813  4776 I Icing   : doRemovePackageData com.test.thalitest
08-25 17:40:46.158  1600  1658 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:40:46.158  1600  1658 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 17:40:46.159  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 17:40:46.159  1600  1658 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:40:46.160  1600  1658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:40:46.160  1600  1658 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 17:40:46.162  1600  1658 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 17:40:46.162  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.165  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-25 17:40:46.165  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 17:40:46.168  1600  1658 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 17:40:46.168  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.169  1600  1658 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 17:40:46.169  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.169  1813  7953 W GmsApplication: Using Auth Proxy for data requests.
08-25 17:40:46.170  1600  1658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:40:46.170  1600  1658 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 17:40:46.172  1600  1658 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 17:40:46.172  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.173  1600  1658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:40:46.173  1600  1658 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 17:40:46.174  1813  7953 W GmsApplication: Using Auth Proxy for data requests.
08-25 17:40:46.174  1600  1658 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 17:40:46.174  1600  1658 D KeyguardModel: createShortcutInfo...
08-25 17:40:46.175  1600  1658 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:40:46.175  1600  1658 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 17:40:46.177  1600  1658 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 17:40:46.177  1600  1658 D KeyguardModel: createShortcutInfo...
,08-25 17:40:46.215  1600  1600 D KeyguardModel: handleShortcutListChanged...
,08-25 17:40:46.215  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 17:40:46.218   324   409 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 17:40:46.219  3211  7957 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 17:40:46.225  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-25 17:40:46.232  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 17:40:46.233  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 17:40:46.234  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 17:40:46.235  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 17:40:46.237  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 17:40:46.247  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34b31818 u0 com.lge.launcher2/.Launcher t5} time:207976
,08-25 17:40:46.252  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 17:40:46.252  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.257  2029  2175 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 17:40:46.257  2029  2175 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-25 17:40:46.264  1813  7824 I CheckinTask: Sending checkin request (7948 bytes)
08-25 17:40:46.268  7932  7932 I AppUp4:AppBoxCP: onCreate
08-25 17:40:46.269  7932  7932 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-25 17:40:46.274  7932  7932 I AppUp4:DB:  setFingerPrint start
08-25 17:40:46.274  7932  7932 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 17:40:46.275  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-25 17:40:46.276  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 17:40:46.276  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.278  7932  7932 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 17:40:46.278  7932  7932 I AppUp4:DB:  SDK version = 21
08-25 17:40:46.278  7932  7932 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 17:40:46.279  7932  7932 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 17:40:46.282  7878  7878 D AndroidRuntime: Shutting down VM
,08-25 17:40:46.284  2029  2029 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 17:40:46.298  7932  7932 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-25 17:40:46.303  1032  1103 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7960 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-25 17:40:46.305  2575  2575 D [Concierge]Service: onStartCommand(). Type : 8
08-25 17:40:46.305  2575  2575 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 17:40:46.307  2575  2575 D [Concierge]Service: Update widget ID : 11
08-25 17:40:46.307  2029  2029 D [Concierge]WidgetView: change position of spinner
08-25 17:40:46.309  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:40:46.313  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-25 17:40:46.333  1032  1920 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7977 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-25 17:40:46.335  1032  1920 I ActivityManager: Killing 7211:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-25 17:40:46.372  2029  2029 I [Concierge]WidgetView: initWebView(). Time : 1472139646372
08-25 17:40:46.372  2575  2575 D [Concierge]Service: onStartCommand(). Type : 0
,08-25 17:40:46.374  1032  1573 W libprocessgroup: failed to open /acct/uid_10046/pid_7211/cgroup.procs: No such file or directory
,08-25 17:40:46.394  7977  7977 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:40:46.394  7977  7977 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:40:46.394  7977  7977 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 17:40:46.394  1032  1955 I ActivityManager: Killing 7232:com.android.chrome/u0a57 (adj 15): empty #17
08-25 17:40:46.395  7977  7977 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 17:40:46.395  7977  7977 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 17:40:46.405  2187  2208 I art     : Explicit concurrent mark sweep GC freed 6696(383KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 622us total 16.616ms
,08-25 17:40:46.473  1032  1991 W libprocessgroup: failed to open /acct/uid_10057/pid_7232/cgroup.procs: No such file or directory
,08-25 17:40:46.480  2029  2029 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 344526309
08-25 17:40:46.480  2029  2029 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 17:40:46.480  2029  2029 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 17:40:46.483  2029  2029 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@4d19e2c
08-25 17:40:46.483  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-25 17:40:46.486  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 17:40:46.486  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.492  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 17:40:46.493  2029  2029 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 17:40:46.493  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 17:40:46.494  2029  2029 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-25 17:40:46.495  2029  2029 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472139466859, New one : 1472139646372
08-25 17:40:46.495  2029  2029 D [Concierge]WidgetView: Unregister all receivers
08-25 17:40:46.495  2029  2029 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 17:40:46.496  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.498  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 17:40:46.499  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 17:40:46.500  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-25 17:40:46.501  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 17:40:46.502  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 17:40:46.505  7977  7977 I SystemConfig: BUILD Country: EU
08-25 17:40:46.505  7977  7977 I SystemConfig: BUILD Operator: OPEN
,08-25 17:40:46.512  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.512  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.517  1813  7824 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-25 17:40:46.531  1813  7824 I CheckinService: active receiver: disabled
,08-25 17:40:46.542  1032  1973 I ActivityManager: Killing 7250:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 17:40:46.553  2029  2029 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 17:40:46.560  2029  2029 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 17:40:46.561  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-25 17:40:46.562  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:40:46.580  2029  2275 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
,08-25 17:40:46.583  2029  2029 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1304e646 time:208311
08-25 17:40:46.583  1032  1992 W libprocessgroup: failed to open /acct/uid_10062/pid_7250/cgroup.procs: No such file or directory
08-25 17:40:46.585  2360  2480 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:40:46.586  2360  2480 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:40:46.586  7977  7996 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 17:40:46.586  7977  7996 I SystemConfig: existFile = false
08-25 17:40:46.586  7977  7996 I SystemConfig: canReadFile = false
08-25 17:40:46.587  7977  7996 I SystemConfig: systemFeature RCS result false
08-25 17:40:46.587  7977  7996 D SystemConfig: refreshRcsSupport() :false
08-25 17:40:46.589  2360  7999 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-25 17:40:46.594  2360  7999 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-25 17:40:46.594  2360  7999 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 17:40:46.594  2360  7999 E AndroidRuntime: Process: android.process.acore, PID: 2360
08-25 17:40:46.594  2360  7999 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:40:46.594  2360  7999 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:40:46.616  1032  1700 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8000 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a

```
