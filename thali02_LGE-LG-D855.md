#### Test 81418577dce6d7c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 15:51:04.050  2223  2223 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-17 15:51:04.057  2223  2223 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-17 15:51:36.888  6966  6966 D AndroidRuntime: 
08-17 15:51:36.888  6966  6966 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 15:51:36.895  6966  6966 D AndroidRuntime: CheckJNI is OFF
08-17 15:51:37.106  6966  6966 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 15:51:37.117  1035  2114 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 15:51:37.132  1969  2533 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 15:51:37.139  1035  2114 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 15:51:37.140  1035  2114 D ActivityManager: setTaskToReturnTo : TaskRecord{1112f46 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 15:51:37.141  1035  2114 D ActivityManager: setTaskToReturnTo : TaskRecord{1112f46 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 15:51:37.142  1035  2114 D WindowStateEx: AppWindowTokenEx init.. 
08-17 15:51:37.143   333   351 E GBMv2   : DFP En is all cleared set to be enabled
08-17 15:51:37.183  1035  2114 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6981 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 15:51:37.186  6966  6966 D AndroidRuntime: Shutting down VM
08-17 15:51:37.230  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 15:51:37.230  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ffd2f27 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 15:51:37.232  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 15:51:37.232  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{125525d4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 15:51:37.372  1035  1722 I art     : Explicit concurrent mark sweep GC freed 35555(1690KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.589ms total 136.657ms
,08-17 15:51:37.431  6981  6981 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-17 15:51:37.496  6981  6981 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 15:51:37.504  6981  6981 I LibraryLoader: Loading: webviewchromium
08-17 15:51:37.507  6981  6981 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6323-6326)
08-17 15:51:37.507  6981  6981 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:51:37.525  6981  6981 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3335226d}
,08-17 15:51:37.526  6981  6981 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:51:37.526  6981  6981 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 15:51:37.538  6981  6981 I BrowserStartupController: Initializing chromium process, renderers=0
08-17 15:51:37.539  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:51:37.564  6981  6981 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 15:51:37.565  6981  6981 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-17 15:51:37.565  6981  6981 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-17 15:51:37.568   312  1384 V AudioPolicyService: registerClient() client 0xb101fc00, uid 10118
08-17 15:51:37.574  1035  1117 D BluetoothManagerService: Message: 20
08-17 15:51:37.574  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@350ee1a0:true
08-17 15:51:37.596  6981  6981 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:51:37.596  6981  6981 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:51:37.596  6981  6981 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:51:37.596  6981  6981 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:51:37.596  6981  6981 I Adreno-EGL: Remote Branch: 
08-17 15:51:37.596  6981  6981 I Adreno-EGL: Local Patches: 
08-17 15:51:37.596  6981  6981 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:51:37.699  6981  7027 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-17 15:51:37.703  6981  6981 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-17 15:51:37.720  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:51:37.726  6981  6981 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 15:51:37.728  1035  1108 W ActivityManager: Activity pause timeout for ActivityRecord{6dca507 u0 com.test.thalitest/.MainActivity t6}
08-17 15:51:37.729  6981  6981 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 15:51:37.731  6981  6981 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 15:51:37.731  6981  6981 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-17 15:51:37.745  6981  6981 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-17 15:51:37.751  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:51:37.751  6981  6981 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:51:37.787  6981  7043 D OpenGLRenderer: Render dirty regions requested: true
,08-17 15:51:37.788  6981  7043 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 15:51:37.796  6981  7043 D OpenGLRenderer: Enabling debug mode 0
,08-17 15:51:37.811  6981  6981 D Atlas   : Validating map...
,08-17 15:51:37.816  1035  2030 D SplitWindow: check instance of lgWin Window{29d4f8da u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 15:51:37.878  6981  7041 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:51:37.878  6981  7041 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:51:37.956  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +728ms (total +812ms)
08-17 15:51:37.957  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6dca507 u0 com.test.thalitest/.MainActivity t6} time:176776
,08-17 15:51:37.958  6981  6981 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@121a9020 time:176777
08-17 15:51:38.080  6981  6981 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 15:51:38.080  6981  6981 I chromium: 
,08-17 15:51:38.155  6981  6981 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 15:51:38.223  6981  7041 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 15:51:38.223  6981  7041 I chromium: 
,08-17 15:51:38.348  6981  7055 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-17 15:51:38.361  6981  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 15:51:38.361  6981  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 15:51:38.361  6981  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 15:51:38.361  6981  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 15:51:38.361  6981  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 15:51:38.361  6981  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12285ae4 added. We now have 1 listener(s)
08-17 15:51:38.366  1035  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:51:38.371  6981  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 15:51:38.372  6981  7055 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:51:38.374  6981  7055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:38.374  6981  7055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 15:51:38.382  6981  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19fdb13 added. We now have 1 listener(s)
,08-17 15:51:38.382  6981  7055 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:38.387  1035  1544 D WifiService: New client listening to asynchronous messages
08-17 15:51:38.392  6981  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:51:38.392  6981  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 15:51:38.393  6981  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 15:51:38.393  6981  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 15:51:38.393  6981  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 15:51:38.400  6981  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:38.401  1035  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:38.402  6981  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 15:51:38.412  6981  7055 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:38.413  6981  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:38.413  6981  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 15:51:38.413  6981  7055 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:38.417  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:38.417  6981  7055 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 15:51:38.419  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:38.456  6981  6981 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 15:51:38.954   333   353 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 15:51:38.955   333   353 E GBMv2   : Set value is all cleared set the max
08-17 15:51:38.955   333   353 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 15:51:39.442  6981  7058 W jxcore-log: Initializing JXcore engine
08-17 15:51:39.442  6981  7058 W jxcore-log: JXcore engine is ready
,08-17 15:51:39.530  7058  7058 W Thread-811: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10256]" dev="sockfs" ino=10256 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 15:51:39.530  7058  7058 W Thread-811: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 15:51:39.530  7058  7058 W Thread-811: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10383]" dev="sockfs" ino=10383 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 15:51:39.530  7058  7058 W Thread-811: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 15:51:39.530  7058  7058 W Thread-811: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32134]" dev="sockfs" ino=32134 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-17 15:51:39.563  6981  7058 W jxcore-log: Starting JXcore engine
,08-17 15:51:39.691  6981  7058 W jxcore-log: Platform android
08-17 15:51:39.691  6981  7058 W jxcore-log: 
08-17 15:51:39.691  6981  7058 W jxcore-log: Process ARCH arm
08-17 15:51:39.691  6981  7058 W jxcore-log: 
,08-17 15:51:39.884  6981  7058 I jxcore-log: JXcore Cordova bridge is ready!
08-17 15:51:39.884  6981  7058 I jxcore-log: 
08-17 15:51:39.885  6981  7058 W jxcore-log: JXcore engine is started
,08-17 15:51:39.891  6981  7055 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-17 15:51:39.897  6981  6981 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 15:51:49.735  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 15:51:49.735  6981  7058 I jxcore-log: 
08-17 15:51:49.737  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 15:51:49.737  6981  7058 I jxcore-log: 
,08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:49.741  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:49.743  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:49.746  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 15:51:49.746  6981  7058 I jxcore-log: 
08-17 15:51:49.748  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 15:51:49.748  6981  7058 I jxcore-log: 
08-17 15:51:50.071  6981  7058 D ExecuteNativeTests: Running unit tests
,08-17 15:51:50.152  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:51:50.152  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa added. We now have 2 listener(s)
08-17 15:51:50.152  1035  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.153  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:51:50.153  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:50.154  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:50.154  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:50.154  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab added. We now have 2 listener(s)
08-17 15:51:50.154  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:50.154  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:51:50.156  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:50.158  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:51:50.159  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.159  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:50.160  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.161  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.168  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:51:50.171  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:51:50.171  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:51:50.172  6981  7058 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 15:51:50.173  6981  7058 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:51:50.173  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:51:50.173  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:51:50.173  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:51:50.174  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.174  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.174  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.175  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.175  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.175  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.175  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:50.175  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa removed from the list
08-17 15:51:50.175  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.175  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab removed from the list
08-17 15:51:50.175  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.175  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.177  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.177  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.177  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.177  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDi,scovery
08-17 15:51:50.177  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.178  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
,08-17 15:51:50.179  6981  7058 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 15:51:50.180  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 15:51:50.180  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-17 15:51:50.180  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.180  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.180  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 15:51:50.180  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.180  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.180  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.180  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.180  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.180  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:50.180  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.180  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.180  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:50.181  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 15:51:50.181  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:51:50.181  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 15:51:50.181  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.185  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:51:50.185  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:51:50.185  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:51:50.185  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-17 15:51:50.185  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:51:50.186  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:51:50.186  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 15:51:50.186  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.186  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.187  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.187  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.187  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.187  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
,08-17 15:51:50.187  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.188  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.188  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.188  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.188  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.188  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.188  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:50.189  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.189  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.189  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.189  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.190  6981  7058 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:51:50.192  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:50.194  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.195  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.195  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:51:50.196  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.197  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.197  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:50.197  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 15:51:50.197  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:51:50.197  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.197  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:51:50.200  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:51:50.202  1035  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.206  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:51:50.209  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-17 15:51:50.212  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 15:51:50.213  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:51:50.214  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.215  6981  7058 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-17 15:51:50.215  6981  7058 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:51:50.217  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.217  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.217  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:51:50.217  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.217  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.218  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.218  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.218  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.218  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.218  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.218  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.218  6981  7058 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:51:50.220  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:50.222  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.223  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.223  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:50.224  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.225  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.225  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:50.225  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:51:50.226  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:51:50.226  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.226  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:51:50.228  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:51:50.229  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.229  6981  7058 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:51:50.230  6981  7,058 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:51:50.231  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.231  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.231  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.232  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.232  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.232  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.232  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.232  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.232  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.232  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.232  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.232  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.232  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.233  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.233  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.234  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.234  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.234  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.234  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.234  6981  7058 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:51:50.236  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:50.238  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.239  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.239  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:50.239  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:50.239  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:51:50.239  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:51:50.239  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.239  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:51:50.240  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.241  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.243  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:51:50.243  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.244  6981  7058 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:51:50.244  6981  7058 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:51:50.244  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.244  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.244  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.245  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.245  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.245  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.245  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.245  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.245  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:50.245  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.245  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.245  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.245  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.245  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.245  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.246  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.246  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.246  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.247  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.247  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.247  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.247  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.247  6981  7058 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 15:51:50.247  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.247  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.247  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.248  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.248  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.248  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.248  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.248  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.248  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.248  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.248  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.248  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.248  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.248  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.249  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.249  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.249  6981  7058 D BluetoothLeScanner: could not find callback wrapper
,08-17 15:51:50.249  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.249  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.249  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.250  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:51:50.250  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.250  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.250  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.250  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.250  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.250  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.250  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.250  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.250  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.250  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.250  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.250  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.250  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.250  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.251  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.251  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.252  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.252  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.252  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.252  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.252  6981  7058 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 15:51:50.252  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.252  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.252  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.253  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.253  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.253  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.253  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.253  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.253  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.253  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.253  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.253  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.253  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.253  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.254  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.254  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.254  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.254  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.254  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.254  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.255  6981  7058 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 15:51:50.255  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.255  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.255  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.255  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.255  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.255  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.255  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.255  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.255  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.255  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.255  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.255  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.255  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.255  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.256  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.256  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.256  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.256  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.256  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.256  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.257  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:51:50.258  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:51:50.258  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:51:50.258  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:51:50.258  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:51:50.258  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:51:50.258  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.258  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.258  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.259  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.259  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.259  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.259  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.259  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.259  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.259  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.259  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.259  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.259  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.259  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.260  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.260  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.260  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.260  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.260  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.260  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.261  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:51:50.261  6981  7058 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:51:50.261  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:51:50.263  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:51:50.263  6981  7058 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:51:50.263  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:51:50.264  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:51:50.264  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 15:51:50.264  6981  7058 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:51:50.264  6981  7058 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 15:51:50.264  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:51:50.264  6981  7058 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:51:50.264  6981  7058 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 15:51:50.264  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:51:50.264  6981  7058 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:51:50.264  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 15:51:50.266  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 15:51:50.267  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 15:51:50.267  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 15:51:50.268  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 15:51:50.268  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 15:51:50.268  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 15:51:50.268  6981  7058 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:51:50.268  6981  7058 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 15:51:50.268  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.268  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.268  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.269  6981  7059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 875)
08-17 15:51:50.271  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.271  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.271  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.271  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 15:51:50.273  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.273  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.273  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.273  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.273  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.273  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.273  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.273  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.274  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.274  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.275  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.275  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.275  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.275  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.275  6981  7058 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 15:51:50.276  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.276  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.276  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.278  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.278  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.278  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.278  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.278  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.278  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.278  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.278  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.278  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.278  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.278  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.280  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.280  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.281  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.281  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.281  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.281  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.281  6981  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 15:51:50.282  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.282  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.282  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.284  6981  7064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 875
08-17 15:51:50.284  6981  7064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 875)
08-17 15:51:50.284  6981  7064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 875)
08-17 15:51:50.286  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.286  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.286  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.286  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.286  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.286  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.286  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.286  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.286  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.286  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.286  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.291  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.291  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.291  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.291  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.291  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.291  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.292  6981  7058 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 15:51:50.292  6981  7058 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 15:51:50.292  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:51:50.292  6981  7058 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-17 15:51:50.292  6981  7058 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:51:50.292  6981  7058 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 15:51:50.292  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:51:50.292  6981  7058 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 15:51:50.292  6981  7058 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:51:50.292  6981  7058 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:51:50.292  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:51:50.292  6981  7058 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 15:51:50.293  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.293  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.293  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.293  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.293  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.293  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.293  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.293  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.293  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.293  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.293  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.293  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.293  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.293  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.295  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.295  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.296  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.296  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.296  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.296  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.296  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.296  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.296  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.296  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.296  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.296  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.296  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.296  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.296  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.297  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.297  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.297  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.297  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.297  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.297  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.297  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.297  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.297  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.298  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.298  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.298  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.298  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.298  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.298  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.298  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.298  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.298  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.298  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.298  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.298  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.298  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.299  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.299  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.299  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.299  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.300  6981  7058 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 15:51:50.300  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.309  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 15:51:50.310  6981  7058 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 15:51:50.310  6981  7058 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 15:51:50.311  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 15:51:50.311  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:51:50.312  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.312  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 15:51:50.312  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 15:51:50.312  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 15:51:50.312  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.312  6981  7058 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 15:51:50.312  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.312  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.312  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:51:50.312  6981  7058 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:51:50.312  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:51:50.312  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:51:50.313  6981  6981 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 15:51:50.313  6981  6981 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 15:51:50.317  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.317  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:51:50.317  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:50.317  6981  7058 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:51:50.317  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.317  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.318  6981  7067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:51:50.318  6981  7058 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:50.318  6981  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:51:50.318  6981  6981 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:51:50.318  6981  6981 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:50.318  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.318  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.318  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.318  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.319  4378  4399 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-17 15:51:50.319  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.319  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.319  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.319  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.319  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.319  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.319  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.319  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.319  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.319  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.319  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.319  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.319  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.319  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.320  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.320  6981  7067 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 15:51:50.320  6981  7067 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 15:51:50.320  6981  7067 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 15:51:50.320  6981  7058 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 15:51:50.320  6981  6981 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 15:51:50.320  6981  7058 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:51:50.321  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:51:50.322  6981  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:51:50.322  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.322  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.322  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.323  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.323  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.323  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.323  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.323  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.323  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.323  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.323  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.323  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.323  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.323  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.324  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.324  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.324  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.324  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.325  1035  2102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.329  1035  2114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.329  1035  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.330  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.330  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.330  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.330  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.330  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.330  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.330  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.330  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.330  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.330  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.330  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.330  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.330  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.330  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.331  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.331  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.331  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.331  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.331  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:50.331  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:50.331  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:50.332  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:50.332  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.332  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.332  6981  7058 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193db2fa not in the list
08-17 15:51:50.332  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.332  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.332  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:50.332  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.332  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.332  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:50.332  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:50.332  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:50.332  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:50.332  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:50.332  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@332990ab not in the list
08-17 15:51:50.333  6981  7058 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 15:51:50.333  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:51:50.333  6981  7058 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 15:51:50.333  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:51:50.333  6981  7058 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 15:51:50.333  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:51:50.335  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:51:50.335  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 15:51:50.335  6981  7058 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 15:51:50.335  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:51:50.335  6981  7058 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 15:51:50.336  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:51:50.336  6981  7058 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 15:51:50.336  6981  7058 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 15:51:50.336  6981  7058 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 15:51:50.336  6981  7058 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 15:51:50.337  6981  7058 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 15:51:50.337  6981  7058 D io.jxco,re.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 15:51:50.337  6981  7058 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 15:51:50.337  6981  7058 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 15:51:50.337  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:50.337  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ef0b20 added. We now have 2 listener(s)
08-17 15:51:50.338  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:51:50.339  6981  7058 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 15:51:50.339  1035  1950 D WifiServiceImplEx: setWifiEnabled: true pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:51:50.340  1035  1950 D WifiService: setWifiEnabled: true pid=6981, uid=10118
08-17 15:51:50.340  1035  1950 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 15:51:50.341  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:50.341  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cebacd9 added. We now have 3 listener(s)
08-17 15:51:50.341  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:50.344  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:50.344  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d8e69e added. We now have 4 listener(s)
08-17 15:51:50.344  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:50.345  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:50.345  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29d2857f added. We now have 5 listener(s)
08-17 15:51:50.345  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:50.347  1035  1950 D WifiServiceImplEx: setWifiEnabled: false pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:51:50.347  1035  1950 D WifiService: setWifiEnabled: false pid=6981, uid=10118
08-17 15:51:50.347  1035  1950 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:51:50.364  1035  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:50.365  1035  1578 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@9751765 mBinding = false
08-17 15:51:50.365  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:51:50.366  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:50.367  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:50.368  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:51:50.368  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:51:50.368  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:50.369  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:50.369  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:50.369  1035  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 15:51:50.369  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:51:50.369  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:51:50.370  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:51:50.370  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:51:50.373  1035  1117 D BluetoothManagerService: Message: 2
08-17 15:51:50.373  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:51:50.374  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:51:50.374  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:51:50.374  1035  1117 D BluetoothManagerService: Sending off request.
08-17 15:51:50.375  4378  4399 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 15:51:50.375  4378  4454 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 15:51:50.375  4378  4454 D BluetoothAdapterProperties: Setting state to 13
08-17 15:51:50.375  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:50.375  4378  4454 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:51:50.376  4378  4454 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 15:51:50.376  4378  4454 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 15:51:50.377  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:51:50.377  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 15:51:50.377  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-17 15:51:50.379  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:51:50.379  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:51:50.379  2628  2628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:51:50.379  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.379  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.379  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:51:50.380  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:51:50.380  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:51:50.380   308   893 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:51:50.382  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:50.382  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:51:50.383  1035  2836 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.399  6981  7059 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-17 15:51:50.401  4378  4378 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:50.401  4378  4378 D BluetoothMapService: STATE_TURNING_OFF
08-17 15:51:50.401  4378  4378 V BluetoothMapService: Handler(): got msg=4
08-17 15:51:50.401  4378  4378 D BluetoothMapService: MAP Service closeService in
08-17 15:51:50.401  4378  4378 D BluetoothMapMasInstance: MAP Service shutdown
08-17 15:51:50.402  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:50.402  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.404  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.404  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:50.404  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 15:51:50.405  4378  4749 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 15:51:50.406  4378  4378 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:51:50.406  4378  4378 V BluetoothMapService: MAP Service closeService out
08-17 15:51:50.406  4378  4378 V BtOppService: Receiver DISABLED_ACTION 
08-17 15:51:50.407  4378  4378 I BtOppRfcommListener: stopping Accept Thread
08-17 15:51:50.407  4378  4378 V BtOppRfcommListener: close mBtServerSocket
08-17 15:51:50.407  4378  4378 V BtOppRfcommListener: waiting for thread to terminate
08-17 15:51:50.409  4378  4772 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:51:50.409  4378  4772 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:51:50.410  4378  4378 V BtOppRfcommListener: done waiting for thread to terminate
08-17 15:51:50.411  6981  7059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:, Exiting thread (thread ID: 875)
,08-17 15:51:50.412  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 15:51:50.412  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-17 15:51:50.413  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.417  1035  2032 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-17 15:51:50.417  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.417  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.417  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 15:51:50.417  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.417  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-17 15:51:50.430  1035  1108 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7072 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:51:50.439  4378  4461 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:51:50.439  4378  4454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 15:51:50.441  4378  4454 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:51:50.443  4378  4755 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:51:50.443  4378  4790 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:51:50.443  4378  4797 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:51:50.443  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 15:51:50.444  4378  4599 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 15:51:50.447  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:51:50.447  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:51:50.447  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:51:50.447  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:51:50.447  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:51:50.451  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:51:50.451  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:51:50.451  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:51:50.451  4378  4599 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:51:50.451  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 15:51:50.451  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 15:51:50.451  4378  4599 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-17 15:51:50.459  1035  1108 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7088 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-17 15:51:50.467  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-17 15:51:50.471  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.471  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.471  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.471  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.471  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.472  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.472  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 15:51:50.472  1035  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21e3f8d3
08-17 15:51:50.472  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.472  1035  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:51:50.472  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.472  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:50.472  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.473  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:51:50.473  4378  4378 V BtOppService: onDestroy
08-17 15:51:50.473  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 15:51:50.480  1035  1537 D LGWifiP2pService: P2pDisablingState
08-17 15:51:50.480  1035  1537 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.480  1035  1537 D LGWifiP2pService: p2p socket connection lost
08-17 15:51:50.481  1035  1537 D LGWifiP2pService: P2pDisabledState
08-17 15:51:50.481  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.481  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.481  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:51:50.481  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 15:51:50.481  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.481  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.481  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:51:50.481  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 15:51:50.481  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-17 15:51:50.482  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 15:51:50.482  1035  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.483  1035  1558 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.483  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 15:51:50.483  1969  1969 D WfdsService: WifiP2pState is changed : false
08-17 15:51:50.483  1969  2337 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
,08-17 15:51:50.483  1969  2337 D WfdsService: Set the WFDS Monitor: false
08-17 15:51:50.484  1969  2337 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:51:50.484  1969  2337 D WfdsService: STATE : WfdsDisabledState - enter
08-17 15:51:50.484  1969  2703 D CtrlSupplicant: Received on exit socket, terminate
08-17 15:51:50.484  1969  2703 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 15:51:50.485  1969  2703 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 15:51:50.485  1969  2703 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 15:51:50.485  1969  2340 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 15:51:50.485  1969  2337 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 15:51:50.486  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 15:51:50.486  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:51:50.486  2628  2628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:51:50.487  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.487  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.487  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:51:50.487  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:51:50.487  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
,08-17 15:51:50.492  1035  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 15:51:50.492  1035  1545 D DSQN    : disableDataServiceNotify
08-17 15:51:50.492  1035  1545 D DSQN    : stop dsqn bin
08-17 15:51:50.492   308   893 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:51:50.493  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.493  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:50.493   308  7111 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 15:51:50.493  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 15:51:50.494  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-17 15:51:50.496  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 15:51:50.496  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.496  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.496  4378  4378 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 15:51:50.496  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:51:50.498  1035  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 15:51:50.498  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:50.498  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.498  1035  1538 D WifiNative-p2p0: TERMINATE: returned true
08-17 15:51:50.498  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:51:50.498  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:51:50.498  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:51:50.499  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.499  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:50.501  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 15:51:50.501  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-17 15:51:50.502  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:51:50.502  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 15:51:50.504  1035  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 15:51:50.504  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:51:50.504  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:51:50.504  1035  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:51:50.505  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 15:51:50.505  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 15:51:50.505  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.505  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.505  1035  2834 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 15:51:50.505  1035  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 15:51:50.506  1035  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 15:51:50.506  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:51:50.507  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:50.507  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.509  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.509  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:50.510  1035  1545 D Conne,ctivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:50.511  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 15:51:50.511  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:51:50.512  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-17 15:51:50.512  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:51:50.512  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:51:50.512  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:51:50.514  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:50.514  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:50.514  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 15:51:50.514  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:51:50.514  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:51:50.514  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:51:50.515  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.515  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:50.515  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 15:51:50.515  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:50.515  1035  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:51:50.515  1035  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:51:50.515  1035  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:51:50.515  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:51:50.516  1880  1880 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:51:50.516  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:51:50.516  1035  1545 D NetworkManagementService: Removing idletimer
08-17 15:51:50.5,16  1035  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.517  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.517  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:51:50.517  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:51:50.519  1035  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 15:51:50.519  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:50.519  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:50.519  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:51:50.520  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:50.520  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:51:50.525  7072  7072 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:51:50.525  7072  7072 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-17 15:51:50.525  7072  7072 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:51:50.525  7072  7072 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-17 15:51:50.526  7072  7072 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 15:51:50.527  7072  7072 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:51:50.559  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:51:50.559  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:51:50.559  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:50.561  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:51:50.561  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:51:50.561  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:50.566  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:51:50.580  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:51:50.581  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:50.582  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:51:50.593  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-17 15:51:50.594  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:50.594  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:51:50.601  1035  2836 D DhcpStateMachine: StoppedState
08-17 15:51:50.601  1035  2836 D DhcpStateMachine: StoppedState{ when=-113ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:50.601  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 15:51:50.602  1035  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-17 15:51:50.606  7088  7088 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 15:51:50.607  7088  7088 W LG Account v2.2: No ProfileInfo entries
08-17 15:51:50.607  7088  7088 I LG Account v2.2: isEnabled: false
08-17 15:51:50.607  7088  7088 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 15:51:50.607  7088  7088 I Feature : [Lifetracker]Country: EU
08-17 15:51:50.607  7088  7088 I Feature : [Lifetracker]Operator: OPEN
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Ranking support: false
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Comfort support: false
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Accessory: true
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Health device: true
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Extra Pedometer: false
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Blood glucose device: false
08-17 15:51:50.608  7088  7088 I Feature : [Lifetracker]Device Number: 3
,08-17 15:51:50.611  2628  2628 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 15:51:50.611  2628  2628 I wpa_supplicant: monitor socket send errors count : 1
08-17 15:51:50.611  2628  2628 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
08-17 15:51:50.612  1035  2691 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 15:51:50.613  1035  2691 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 15:51:50.613  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:51:50.615  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:51:50.615  4378  4378 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:51:50.615  4378  4378 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:50.615  4378  4378 V BluetoothPbapReceiver: ***********state = 13
08-17 15:51:50.616  4378  4378 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 15:51:50.618  1035  1117 D BluetoothManagerService: Message: 20
08-17 15:51:50.618  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@237596f4:true
08-17 15:51:50.643  1035  1939 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7119 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:51:50.644  1035  1939 I ActivityManager: Killing 6326:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-17 15:51:50.651  2628  2628 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:51:50.651  1035  2691 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 15:51:50.651  1035  2691 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:51:50.651  1035  2691 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:51:50.651  2628  2628 W wpa_supplicant: USIM:  scard_deinit function
08-17 15:51:50.652  1035  1117 D Tethering: InitialState.processMessage what=4
08-17 15:51:50.652  1035  2691 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 15:51:50.652  1035  2691 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:51:50.652  1035  2691 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:51:50.652  1035  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189456
08-17 15:51:50.653  1035  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189456
08-17 15:51:50.653  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=189456  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:51:50.653  1035  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=189457  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:51:50.682  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:51:50.682  4378  4378 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:50.682  4378  4378 V BluetoothPbapService: state: 13
08-17 15:51:50.682  4378  4378 V BluetoothPbapService: Pbap Service closeService in
,08-17 15:51:50.685  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:50.685  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:50.685  1035  1117 D BluetoothManagerService: Message: 30
08-17 15:51:50.685  1035  1050 W libprocessgroup: failed to open /acct/uid_10014/pid_6326/cgroup.procs: No such file or directory
08-17 15:51:50.688  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:51:50.689  4378  4378 V BluetoothPbapService: successfully stopped pbap service
08-17 15:51:50.689  4378  4378 V BluetoothPbapService: Pbap Service closeService out
08-17 15:51:50.690  4378  4378 V BluetoothPbapService: Pbap Service onDestroy
08-17 15:51:50.690  4378  4378 V BluetoothPbapService: Pbap Service closeService in
08-17 15:51:50.690  4378  4378 V BluetoothPbapService: Pbap Service closeService out
08-17 15:51:50.690  4378  4378 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 15:51:50.694  1035  1117 D BluetoothManagerService: Message: 30
,08-17 15:51:50.697  7072  7072 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 15:51:50.699  7072  7072 D BluetoothMap: Create BluetoothMap proxy object
08-17 15:51:50.700  1035  1117 D BluetoothManagerService: Message: 30
08-17 15:51:50.704  1035  1117 D BluetoothManagerService: Message: 30
08-17 15:51:50.706  7072  7072 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-17 15:51:50.708  7072  7072 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-17 15:51:50.724  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-17 15:51:50.726  7072  7072 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-17 15:51:50.728  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:51:50.728  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:51:50.729  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-17 15:51:50.730  1035  2087 I ActivityManager: Killing 6406:com.android.defcontainer/u0a4 (adj 15): empty #17
08-17 15:51:50.732  2628  2628 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 15:51:50.732  1035  2691 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 15:51:50.732  1035  2691 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 15:51:50.732  1035  2691 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 15:51:50.733  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-17 15:51:50.765  1035  2114 W libprocessgroup: failed to open /acct/uid_10004/pid_6406/cgroup.procs: No such file or directory
,08-17 15:51:50.773  7072  7072 D DockEventReceiver: finishStartingService: stopping service
08-17 15:51:50.776  7072  7072 D BluetoothInputDevice: Proxy object connected
,08-17 15:51:50.777  7072  7072 D HidProfile: Bluetooth service connected
08-17 15:51:50.788  7072  7072 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:51:50.789  7072  7072 D PanProfile: Bluetooth service connected
08-17 15:51:50.792  7072  7072 D BluetoothMap: Proxy object connected
,08-17 15:51:50.793  7072  7072 D MapProfile: Bluetooth service connected
08-17 15:51:50.793  7072  7072 D BluetoothMap: getConnectedDevices()
08-17 15:51:50.793  7072  7072 D BluetoothMap: Bluetooth is Not enabled
08-17 15:51:50.806  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:51:50.819  6981  6981 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:51:50.834  1035  1538 D WifiOffDelayIfNotUsed: stopMonitoring
,08-17 15:51:50.834  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:51:50.834  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:51:50.834  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 15:51:50.837  1969  1969 D WfdsService: Supplicant Connection state is changed : false
08-17 15:51:50.837  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-17 15:51:50.838  1969  2337 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-17 15:51:50.838  1969  2337 D WfdsService: Set the WFDS Monitor: false
,08-17 15:51:50.838  1969  2337 D WfdsMonitor: WFDS Monitor is stopped
,08-17 15:51:50.839  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 15:51:50.839  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 15:51:50.840  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:50.840  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:50.841  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 15:51:50.841  2474  2474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:50.843  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:50.867  7072  7072 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:51:50.867  7072  7072 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:51:50.878  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:50.879  7072  7072 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 15:51:50.880  7072  7072 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 15:51:50.887  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:51:50.890  7072  7072 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 15:51:50.897  1035  1050 I ActivityManager: Killing 6601:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-17 15:51:50.902  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:51:51.016  4378  4378 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 15:51:51.017  4378  4378 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-17 15:51:51.019  4378  4378 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 15:51:51.021  1035  2332 W libprocessgroup: failed to open /acct/uid_10008/pid_6601/cgroup.procs: No such file or directory
08-17 15:51:51.124  1035  1986 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7147 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-17 15:51:51.128  4378  4378 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:51.128  4378  4378 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:51:51.133  4378  4378 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:51:51.133  4378  4378 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:51.133  4378  4378 V BluetoothFtpService: Ftp Service closeService
08-17 15:51:51.133  4378  4378 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 15:51:51.136  4378  4378 V BluetoothFtpService: successfully stopped ftp service
08-17 15:51:51.136  4378  4378 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:51:51.136  4378  4378 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:51:51.136  4378  4378 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:51:51.136  4378  4378 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:51.136  4378  4378 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 15:51:51.136  4378  4378 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:51:51.137  4378  4378 V BluetoothFtpService: Ftp Service onDestroy
08-17 15:51:51.137  4378  4378 V BluetoothFtpService: Ftp Service closeService
08-17 15:51:51.138  4378  4378 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:51.138  4378  4378 V BluetoothSapService: state: 13
08-17 15:51:51.138  4378  4378 V BluetoothSapService: Stopping SAP server process
,08-17 15:51:51.139  4378  4378 V BluetoothSapService: Sap Service closeSapService in
08-17 15:51:51.140  4378  4378 V BluetoothSapService: Close listen Socket : 
08-17 15:51:51.140  4378  4378 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:51:51.140  4378  4378 V BluetoothSapService: Close sapd  Socket : 
08-17 15:51:51.141  4378  4378 V BluetoothSapService: Sap Service closeSapService out
08-17 15:51:51.142  4378  4378 V BluetoothSapService: Sap Service onDestroy
08-17 15:51:51.142  4378  4378 V BluetoothSapService: Sap Service closeSapService in
08-17 15:51:51.142  4378  4378 V BluetoothSapService: Close listen Socket : 
08-17 15:51:51.142  4378  4378 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:51:51.142  4378  4378 V BluetoothSapService: Close sapd  Socket : 
08-17 15:51:51.143  4378  4378 V BluetoothSapService: Sap Service closeSapService out
08-17 15:51:51.199  1035  2030 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7167 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:51:51.255  7147  7147 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:51:51.262  7167  7167 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:51:51.278  1035  2102 I ActivityManager: Killing 6640:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-17 15:51:51.308  1035  1050 W libprocessgroup: failed to open /acct/uid_10011/pid_6640/cgroup.procs: No such file or directory
,08-17 15:51:51.310  7147  7147 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-17 15:51:51.347  7147  7147 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-17 15:51:51.348  7147  7147 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-17 15:51:51.348  7147  7147 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 15:51:51.350  7147  7147 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 15:51:51.351  7147  7147 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 15:51:51.353  7147  7147 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-17 15:51:51.360  7147  7147 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-17 15:51:51.368  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:51:51.372  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:51:51.395  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:51:51.399  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:51:51.402  7147  7147 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-17 15:51:51.406  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:51:51.406  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:51:51.406  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:51:51.409  7147  7147 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-17 15:51:51.410  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:51:51.423  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:51.433  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:51:51.434  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:51:51.437  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:51:51.442  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:51:51.448  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:51:51.448  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:51:51.448  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:51:51.450  4378  4461 D bt_hci_bdroid: cleanup
,08-17 15:51:51.450  4378  4602 I bt_lpm  : LPM is already off!!!
08-17 15:51:51.452  4378  4599 W bt-btif : ag scb idx 1 not allocated
08-17 15:51:51.452  4378  4599 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 15:51:51.452  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:51:51.452  4378  4735 I bt_userial_mct: exiting userial_read_thread
08-17 15:51:51.452  4378  4735 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 15:51:51.452  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:51:51.453  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:51:51.453  4378  4461 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 15:51:51.453  4378  4602 I bt_vendor: hw_epilog_process
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:51:51.454  4378  4461 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:51:51.454  4378  4461 D bt_userial_mct: userial_close
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:51:51.454  4378  4461 E bt_userial_mct: pthread_join() FAILED result:3
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:51:51.454  4378  4599 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:51:51.454  4378  4461 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 15:51:51.454  4378  4599 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:51:51.462  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:51:51.475  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:51:51.487  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:51:51.487  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:51:51.490  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:51:51.501  4378  4461 D bt_hci_bdroid: set_power 0
08-17 15:51:51.502  4378  4461 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 15:51:51.502  4378  4461 I bt_vendor: bluetooth satus is on
08-17 15:51:51.502  4378  4461 I bt_vendor: bt-vendor : resetting BT status
08-17 15:51:51.502  4378  4461 I bt_vendor: Starting hciattach daemon
08-17 15:51:51.502  4378  4461 I bt_vendor: try to set false
08-17 15:51:51.503  4378  4461 I bt_vendor: Starting hciattach daemon
08-17 15:51:51.503  4378  4461 I bt_vendor: try to set false
08-17 15:51:51.505  4378  4461 I bt_vendor: cleanup
,08-17 15:51:51.506  4378  4599 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 15:51:51.507  4378  4461 I GKI_LINUX: GKI_exit_task 0 done
08-17 15:51:51.507  4378  4461 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 15:51:51.511  4378  4454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 15:51:51.563  1035  2032 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7189 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-17 15:51:51.568  4378  4378 D HeadsetService: Received stop request...Stopping profile...
08-17 15:51:51.571  4378  4378 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:51:51.571  4378  4378 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:51:51.571  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.571  4378  4532 D HeadsetStateMachine: Exit Disconnected: -1
08-17 15:51:51.573  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-17 15:51:51.573  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 15:51:51.573  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-17 15:51:51.573  1880  1880 D BluetoothHeadset: Proxy object disconnected
,08-17 15:51:51.575  4378  4378 D A2dpService: Received stop request...Stopping profile...
08-17 15:51:51.575  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-17 15:51:51.576  4378  4580 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:51:51.577  4378  4378 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 15:51:51.578  4378  4454 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 15:51:51.580  4378  4378 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 15:51:51.580  4378  4378 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:51:51.580  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.583  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-17 15:51:51.583  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 15:51:51.583  4378  4378 D HidService: Received stop request...Stopping profile...
08-17 15:51:51.583  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.584  7072  7072 D BluetoothInputDevice: Proxy object disconnected
08-17 15:51:51.584  7072  7072 D HidProfile: Bluetooth service disconnected
08-17 15:51:51.584  4378  4378 D HealthService: Received stop request...Stopping profile...
08-17 15:51:51.585  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.586  4378  4378 D PanService: Received stop request...Stopping profile...
08-17 15:51:51.587  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.588  4378  4378 D HeadsetStateMachine: Unbinding service...
08-17 15:51:51.590  4378  4378 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:51:51.590  4378  4378 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:51:51.590  4378  4378 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:51:51.590  4378  4378 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-17 15:51:51.590  4378  4378 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:51:51.590  4378  4378 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:51:51.590  4378  4378 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:51:51.590  4378  4378 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:51:51.588  7072  7072 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:51:51.590  7072  7072 D PanProfile: Bluetooth service disconnected
08-17 15:51:51.591  4378  4378 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:51:51.591  4378  4378 D BtGatt.GattService: stop()
08-17 15:51:51.591  4378  4378 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:51:51.592  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.593  4378  4378 D BluetoothMapService: Received stop request...Stopping profile...
08-17 15:51:51.593  4378  4378 D BluetoothMapService: stop()
08-17 15:51:51.593  4378  4378 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 15:51:51.593  4378  4378 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 15:51:51.594  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b0ea2
08-17 15:51:51.595  4378  4378 I BluetoothA2dpServiceJni: cleanupNative
08-17 15:51:51.595  4378  4583 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 15:51:51.595  4378  4378 I GKI_LINUX: GKI_exit_task 2 done
08-17 15:51:51.595  4378  4378 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 15:51:51.596  4378  4378 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:51:51.596  4378  4378 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:51:51.596  4378  4378 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:51:51.596  4378  4378 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:51:51.596  4378  4378 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:51:51.596  4378  4378 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:51:51.596  4378  4378 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:51:51.598  7072  7072 D BluetoothMap: Proxy object disconnected
08-17 15:51:51.598  7072  7072 D MapProfile: Bluetooth service disconnected
08-17 15:51:51.598  4378  4378 V BluetoothMapService: Handler(): got msg=4
08-17 15:51:51.598  4378  4378 D BluetoothMapService: MAP Service closeService in
,08-17 15:51:51.598  4378  4378 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:51:51.598  4378  4378 V BluetoothMapService: MAP Service closeService out
08-17 15:51:51.599  4378  4454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 15:51:51.599  4378  4454 D BluetoothAdapterProperties: Setting state to 10
08-17 15:51:51.599  4378  4454 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 15:51:51.599  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:51:51.599  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 15:51:51.599  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-17 15:51:51.599  4378  4454 I BluetoothAdapterState: Entering OffState
08-17 15:51:51.599  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:51:51.599  4378  4378 D BluetoothMapService: cleanup()
08-17 15:51:51.599  4378  4378 D BluetoothMapService: MAP Service closeService in
08-17 15:51:51.599  1880  2569 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:51:51.599  4378  4378 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:51:51.599  4378  4378 V BluetoothMapService: MAP Service closeService out
08-17 15:51:51.600  1880  4541 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:51:51.601  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:51:51.601  7072  7098 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:51:51.602  7072  7105 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:51:51.602  7072  7098 D BluetoothMap: onBluetoothStateChange: up=false
08-17 15:51:51.603  1880  4531 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:51:51.603  7072  7105 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 15:51:51.604  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 15:51:51.605  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-17 15:51:51.609  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 15:51:51.609  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 15:51:51.609  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@9751765 mBinding = false
08-17 15:51:51.610  1035  1117 D BluetoothManagerService: Sending unbind request.
08-17 15:51:51.611  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-17 15:51:51.614  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:51.615  1969  2181 D LGBluetoothAPIService: Message: 2
08-17 15:51:51.615  1969  2181 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@15bfe37d mBinding = false
08-17 15:51:51.615  1969  2181 D LGBluetoothAPIService: Sending unbind request.
08-17 15:51:51.615  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:51.616  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:51:51.616  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:51.618  7072  7072 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:51:51.619  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 15:51:51.619  7072  7072 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-17 15:51:51.622  4378  4461 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 15:51:51.623  4378  4378 I GKI_LINUX: GKI_exit_task 1 done
08-17 15:51:51.623  4378  4378 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 15:51:51.624  4378  4378 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:51:51.624  4378  4378 I art     : --- WEIRD: removing null entry 246
08-17 15:51:51.624  4378  4378 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-17 15:51:51.624  1605  1605 D BluetoothAdapter: 196188828: getState() :  mService = null. Returning STATE_OFF
08-17 15:51:51.624  1605  1605 D BluetoothAdapter: 196188828: getState() :  mService = null. Returning STATE_OFF
08-17 15:51:51.624  4378  4378 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 15:51:51.625  4378  4378 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 15:51:51.628  4378  4378 I art     : System.exit called, status: 0
08-17 15:51:51.628  4378  4378 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 15:51:51.629  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 15:51:51.641  7072  7072 D DockEventReceiver: finishStartingService: stopping service
08-17 15:51:51.657   312  4545 V AudioFlinger: 4378 died, releasing its sessions
08-17 15:51:51.657   312  4545 V AudioFlinger:  pid 1880 @ 0
08-17 15:51:51.657   312  4545 V AudioFlinger:  pid 3243 @ 1
08-17 15:51:51.657   312  4545 V AudioFlinger:  pid 3243 @ 2
08-17 15:51:51.657  7072  7072 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-17 15:51:51.681  1035  1939 I ActivityManager: Process com.android.bluetooth (pid 4378) has died
,08-17 15:51:51.681  1035  1939 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-17 15:51:51.685  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:51:51.692  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:51:51.700  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:51:51.707  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:51.708  7189  7216 W FormManager: Network not available. Please check & try again.
08-17 15:51:51.709  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:51:51.710  7072  7072 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 15:51:51.711  7072  7072 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 15:51:51.712  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:51:51.768  1035  1986 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7218 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 15:51:51.783  7189  7217 V FormManager: Network unavailable.
08-17 15:51:51.787  7189  7217 V FormManager: Network unavailable.
,08-17 15:51:51.801  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-17 15:51:51.801  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:51:51.801  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:51:51.801  7072  7072 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:51:51.802  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-17 15:51:51.806   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 477us total 34.138ms
08-17 15:51:51.821  7072  7072 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:51:51.821  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:51:51.821  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:51:51.821  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:51:51.822  7072  7072 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:51:51.822  7072  7072 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:51:51.823  1035  2032 I ActivityManager: Killing 6111:com.android.contacts/u0a19 (adj 15): empty #17
,08-17 15:51:51.826   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.417ms
08-17 15:51:51.844   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 17.237ms
,08-17 15:51:51.918  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:51:51.920  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:51:51.926  1035  1050 W libprocessgroup: failed to open /acct/uid_10019/pid_6111/cgroup.procs: No such file or directory
08-17 15:51:51.930  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:51:51.941  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:51:51.956  7119  7119 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 15:51:51.957  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:51:51.957  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:51:51.961  4866  7239 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:51:51.963  4866  7239 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:51:51.964  7218  7218 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 15:51:51.965  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 15:51:51.965  7218  7218 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:51:51.967  7218  7218 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 15:51:51.971  7218  7218 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:51:51.977  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:51.984  4866  7237 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 15:51:51.986  7189  7241 W FormManager: Network not available. Please check & try again.
08-17 15:51:51.987  7189  7242 V FormManager: Network unavailable.
08-17 15:51:51.993  7218  7218 D BluetoothAdapterApp: Loading JNI Library
,08-17 15:51:51.998  7189  7242 V FormManager: Network unavailable.
,08-17 15:51:52.003  7147  7147 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 15:51:52.004  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 15:51:52.005  7147  7147 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-17 15:51:52.029  7218  7218 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@384e9bbb Instance Count = 1
,08-17 15:51:52.034  7218  7218 D BluetoothAdapterApp: onCreate
08-17 15:51:52.041  7147  7147 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 15:51:52.042  7147  7147 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:51:52.049  7147  7147 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-17 15:51:52.051  7147  7147 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-17 15:51:52.052  7147  7147 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-17 15:51:52.052  7147  7147 V SoundPool: doLoad: loading sample sampleID=1
08-17 15:51:52.053  7147  7245 V SoundPool: Start decode
08-17 15:51:52.053  7147  7147 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 15:51:52.053  7147  7245 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-17 15:51:52.056   312  1384 V MediaPlayerService: decode(22, 10857164, 17813)
08-17 15:51:52.056   312  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-17 15:51:52.056   312  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-17 15:51:52.056   312  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-17 15:51:52.056   312  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-17 15:51:52.056   312  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-17 15:51:52.056   312  1384 V MediaPlayerService: player type = 3
08-17 15:51:52.056   312  1384 V AwesomePlayer: AwesomePlayer create()
,08-17 15:51:52.056   312  1384 V AwesomePlayer: reset_l() 
08-17 15:51:52.056   312  1384 V AwesomePlayer: cancelPlayerEvents
08-17 15:51:52.056   312  1384 V AwesomePlayer: setAudioSink() 
08-17 15:51:52.056   312  1384 V AwesomePlayer: reset_l() 
08-17 15:51:52.056   312  1384 V AudioCache: notify(0xb10114c0, 8, 0, 0)
08-17 15:51:52.056   312  1384 V AudioCache: ignored
08-17 15:51:52.056   312  1384 V AwesomePlayer: cancelPlayerEvents
08-17 15:51:52.056   312  1384 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-17 15:51:52.056   312  1384 V AwesomePlayer: setDataSource_l dataSource
08-17 15:51:52.056   312  1384 V LGParserOSAL: SniffLGParser start
08-17 15:51:52.056   312  1384 V LGParserOSAL: MainType:5, SubType=0
08-17 15:51:52.057   312  1384 V LGParserOSAL: #### check Mime : application/ogg
08-17 15:51:52.057   312  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-17 15:51:52.057   312  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-17 15:51:52.057  7218  7218 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 15:51:52.057  7218  7218 D ProfileConfigQcom: Adding HeadsetService
08-17 15:51:52.057  7218  7218 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 15:51:52.057  7218  7218 D ProfileConfigQcom: Adding A2dpService
08-17 15:51:52.057  7218  7218 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 15:51:52.058  7218  7218 D ProfileConfigQcom: Adding HidService
08-17 15:51:52.058  7218  7218 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 15:51:52.058  7218  7218 D ProfileConfigQcom: Adding HealthService
08-17 15:51:52.058  7218  7218 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 15:51:52.059  7218  7218 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 15:51:52.059  7218  7218 D ProfileConfigQcom: Adding PanService
08-17 15:51:52.059  7218  7218 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 15:51:52.060  7218  7218 D ProfileConfigQcom: Adding GattService
08-17 15:51:52.060  7218  7218 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 15:51:52.060  7218  7218 D ProfileConfigQcom: Adding BluetoothMapService
08-17 15:51:52.060  7218  7218 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 15:51:52.062  6885  6885 D UEI.SmartControl: QS Service created
08-17 15:51:52.063  7147  7147 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 15:51:52.064  7218  7218 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 15:51:52.066  7147  7147 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 15:51:52.066  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 15:51:52.075  7218  7218 V LGMDMManagerInternal: Create singleton instance
08-17 15:51:52.076  6885  6885 I UEI.SmartControl: Service initServices...
08-17 15:51:52.076  6885  6885 D UEI.SmartControl: QS start get config
08-17 15:51:52.081  7072  7072 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-17 15:51:52.082  7147  7147 V LGMDMManager: Create singleton instance
08-17 15:51:52.098   312  1384 V LGParserOSAL: supported mime: application/ogg
08-17 15:51:52.098   312  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-17 15:51:52.098   312  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-17 15:51:52.098   312  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-17 15:51:52.098   312  1384 V AwesomePlayer: AudioTrack Setting
08-17 15:51:52.098   312  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-17 15:51:52.098   312  1384 V AwesomePlayer: setAudioSource() 
08-17 15:51:52.098   312  1384 V MediaPlayerService: prepare
08-17 15:51:52.098   312  1384 V AwesomePlayer: prepareAsync_l() 
08-17 15:51:52.098   312  1384 V MediaPlayerService: wait for prepare
08-17 15:51:52.098   312  7247 V AwesomePlayer: onPrepareAsyncEvent() 
08-17 15:51:52.098   312  7247 V AwesomePlayer: initAudioDecoder() 
08-17 15:51:52.098   312  7247 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 15:51:52.098   312  7247 V AudioSystem: isOffloadSupported()
08-17 15:51:52.098   312  7247 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 15:51:52.098   312  7247 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 15:51:52.098   312  7247 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 15:51:52.098   312  7247 V AwesomePlayer: getUseOffload() = 0 
08-17 15:51:52.098   312  7247 V OMXCodec: OMXCodec::Create
08-17 15:51:52.098   312  7247 V OMXCodec: findMatchingCodecs()
08-17 15:51:52.098   312  7247 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-17 15:51:52.098   312  7247 V OMXCodec: matchingCodecs.size()=1
08-17 15:51:52.098   312  7247 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-17 15:51:52.100   312  7247 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-17 15:51:52.100   312  7247 V LGCodecAdapter: LG Codec Adapter start
08-17 15:51:52.100   312  7247 V OMXCodec: OMXCodec Createtor
08-17 15:51:52.100   312  7247 V OMXCodec: setComponentRole
08-17 15:51:52.100   312  7247 V OMXCodec: configureCodec protected=0
08-17 15:51:52.100   312  7247 V LGCodecAdapter: called getLGCodecSpecificData
08-17 15:51:52.100   312  7247 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-17 15:51:52.100   312  7247 V LGCodecOSAL: Called LGconfigureCodecMETA
08-17 15:51:52.100   312  7247 V LGCodecOSAL: Called LGconfigureCodecMSG
08-17 15:51:52.100   312  7247 V LGCodecOSAL: Not support LGCodec
08-17 15:51:52.100   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 15:51:52.100   312  7247 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-17 15:51:52.100   312  7247 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-17 15:51:52.100   312  7247 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-17 15:51:52.100   312  7247 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 15:51:52.100   312  7247 V AudioSystem: isOffloadSupported()
08-17 15:51:52.100   312  7247 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 15:51:52.100   312  7247 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 15:51:52.100   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-17 15:51:52.100   312  7247 V OMXCodec: init()
,08-17 15:51:52.100   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-17 15:51:52.100   312  7247 V OMXCodec: allocateBuffers
08-17 15:51:52.100   312  7247 V OMXCodec: allocateBuffersOnPort portIndex=0
08-17 15:51:52.100   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-17 15:51:52.101   312  7247 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-17 15:51:52.101   312  7247 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-17 15:51:52.101   312  7247 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 15:51:52.101   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 15:51:52.101   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 15:51:52.101   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-17 15:51:52.101   312  7247 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 15:51:52.101   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-17 15:51:52.101   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-17 15:51:52.101   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-17 15:51:52.101   312  7247 V OMXCodec: init() mAsyncCompletion wait free! 
08-17 15:51:52.101   312  7247 V AwesomePlayer: finishAsyncPrepare_l() 
08-17 15:51:52.101   312  7247 V AudioCache: notify(0xb10114c0, 5, 0, 0)
08-17 15:51:52.101   312  7247 V AudioCache: ignored
08-17 15:51:52.101   312  7247 V AudioCache: notify(0xb10114c0, 1, 0, 0)
08-17 15:51:52.101   312  7247 V AudioCache: prepared
08-17 15:51:52.101   312  1384 V AudioCache: wait - success
08-17 15:51:52.101   312  1384 V MediaPlayerService: start
08-17 15:51:52.101   312  1384 V AwesomePlayer: play_l() 
08-17 15:51:52.101   312  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-17 15:51:52.101   312  1384 V AwesomePlayer: createAudioPlayer_l
08-17 15:51:52.101   312  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
08-17 15:51:52.101   312  1384 V AwesomePlayer: startAudioPlayer_l() 
08-17 15:51:52.101   312  1384 D AudioPlayer: start of Playback, useOffload 0
08-17 15:51:52.101   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 15:51:52.101   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-17 15:51:52.103   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
,08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-17 15:51:52.104   312  7249 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ff60 on output port
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-17 15:51:52.104   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-17 15:51:52.105   312  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-17 15:51:52.106   312  1384 V AudioCache: notify(0xb10114c0, 6, 0, 0)
08-17 15:51:52.106   312  1384 V AudioCache: ignored
,08-17 15:51:52.106   312  1384 V MediaPlayerService: wait for playback complete
,08-17 15:51:52.112   312  7250 V AudioCache: write(0xb17fc000, 4096)
,08-17 15:51:52.112   312  7250 V AudioCache: memcpy(0xaf0f9000, 0xb17fc000, 4096)
08-17 15:51:52.113   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.113   312  7250 V AudioCache: memcpy(0xaf0fa000, 0xb17fc000, 4096)
08-17 15:51:52.113   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.113   312  7250 V AudioCache: memcpy(0xaf0fb000, 0xb17fc000, 4096)
08-17 15:51:52.114   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.114   312  7250 V AudioCache: memcpy(0xaf0fc000, 0xb17fc000, 4096)
08-17 15:51:52.115   312  7250 V AudioCache: write(0xb17fc000, 4096)
,08-17 15:51:52.115   312  7250 V AudioCache: memcpy(0xaf0fd000, 0xb17fc000, 4096)
08-17 15:51:52.115   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.115   312  7250 V AudioCache: memcpy(0xaf0fe000, 0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: memcpy(0xaf0ff000, 0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: memcpy(0xaf100000, 0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: write(0xb17fc000, 4096)
,08-17 15:51:52.116   312  7250 V AudioCache: memcpy(0xaf101000, 0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.116   312  7250 V AudioCache: memcpy(0xaf102000, 0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: memcpy(0xaf103000, 0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: memcpy(0xaf104000, 0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: memcpy(0xaf105000, 0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.118   312  7250 V AudioCache: memcpy(0xaf106000, 0xb17fc000, 4096)
08-17 15:51:52.119   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.119   312  7250 V AudioCache: memcpy(0xaf107000, 0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: memcpy(0xaf108000, 0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: memcpy(0xaf109000, 0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: memcpy(0xaf10a000, 0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.121   312  7250 V AudioCache: memcpy(0xaf10b000, 0xb17fc000, 4096)
08-17 15:51:52.122   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.122   312  7250 V AudioCache: memcpy(0xaf10c000, 0xb17fc000, 4096)
08-17 15:51:52.123   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.124   312  7250 V AudioCache: memcpy(0xaf10d000, 0xb17fc000, 4096)
08-17 15:51:52.124   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.124   312  7250 V AudioCache: memcpy(0xaf10e000, 0xb17fc000, 4096)
08-17 15:51:52.125   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.125   312  7250 V AudioCache: memcpy(0xaf10f000, 0xb17fc000, 4096)
08-17 15:51:52.125   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.125   312  7250 V AudioCache: memcpy(0xaf110000, 0xb17fc000, 4096)
08-17 15:51:52.126   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.126   312  7250 V AudioCache: memcpy(0xaf111000, 0xb17fc000, 4096)
08-17 15:51:52.126   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.126   312  7250 V AudioCache: memcpy(0xaf112000, 0xb17fc000, 4096)
08-17 15:51:52.127   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.127   312  7250 V AudioCache: memcpy(0xaf113000, 0xb17fc000, 4096)
08-17 15:51:52.127   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.127   312  7250 V AudioCache: memcpy(0xaf114000, 0xb17fc000, 4096)
08-17 15:51:52.128   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.128   312  7250 V AudioCache: memcpy(0xaf115000, 0xb17fc000, 4096)
08-17 15:51:52.128   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.128   312  7250 V AudioCache: memcpy(0xaf116000, 0xb17fc000, 4096)
08-17 15:51:52.129   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.129   312  7250 V AudioCache: memcpy(0xaf117000, 0xb17fc000, 4096)
08-17 15:51:52.129   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.129   312  7250 V AudioCache: memcpy(0xaf118000, 0xb17fc000, 4096)
08-17 15:51:52.130   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.130   312  7250 V AudioCache: memcpy(0xaf119000, 0xb17fc000, 4096)
08-17 15:51:52.130   312  7250 V AudioCache: write(0xb17fc000, 4096)
,08-17 15:51:52.130   312  7250 V AudioCache: memcpy(0xaf11a000, 0xb17fc000, 4096)
08-17 15:51:52.131   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.131   312  7250 V AudioCache: memcpy(0xaf11b000, 0xb17fc000, 4096)
08-17 15:51:52.131   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.131   312  7250 V AudioCache: memcpy(0xaf11c000, 0xb17fc000, 4096)
08-17 15:51:52.132   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.132   312  7250 V AudioCache: memcpy(0xaf11d000, 0xb17fc000, 4096)
08-17 15:51:52.133   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.133   312  7250 V AudioCache: memcpy(0xaf11e000, 0xb17fc000, 4096)
08-17 15:51:52.133   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.133   312  7250 V AudioCache: memcpy(0xaf11f000, 0xb17fc000, 4096)
08-17 15:51:52.134   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.134   312  7250 V AudioCache: memcpy(0xaf120000, 0xb17fc000, 4096)
08-17 15:51:52.135   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.135   312  7250 V AudioCache: memcpy(0xaf121000, 0xb17fc000, 4096)
08-17 15:51:52.135   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.135   312  7250 V AudioCache: memcpy(0xaf122000, 0xb17fc000, 4096)
08-17 15:51:52.136   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.136   312  7250 V AudioCache: memcpy(0xaf123000, 0xb17fc000, 4096)
08-17 15:51:52.137   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.137   312  7250 V AudioCache: memcpy(0xaf124000, 0xb17fc000, 4096)
08-17 15:51:52.137   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.137   312  7250 V AudioCache: memcpy(0xaf125000, 0xb17fc000, 4096)
08-17 15:51:52.138   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.138   312  7250 V AudioCache: memcpy(0xaf126000, 0xb17fc000, 4096)
08-17 15:51:52.138   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.138   312  7250 V AudioCache: memcpy(0xaf127000, 0xb17fc000, 4096)
08-17 15:51:52.139   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.139   312  7250 V AudioCache: memcpy(0xaf128000, 0xb17fc000, 4096)
08-17 15:51:52.139   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.139   312  7250 V AudioCache: memcpy(0xaf129000, 0xb17fc000, 4096)
08-17 15:51:52.140   312  7250 V AudioCache: write(0xb17fc000, 4096)
08-17 15:51:52.140   312  7250 V AudioCache: memcpy(0xaf12a000, 0xb17fc000, 4096)
08-17 15:51:52.140   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-17 15:51:52.140   312  7250 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 15:51:52.140   312  7250 V AwesomePlayer: postAudioEOS() 
08-17 15:51:52.140   312  7250 V AudioCache: write(0xb17fc000, 280)
08-17 15:51:52.140   312  7250 V AudioCache: memcpy(0xaf12b000, 0xb17fc000, 280)
08-17 15:51:52.142   312  7247 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-17 15:51:52.142   312  7247 V AwesomePlayer: onStreamDone
08-17 15:51:52.142   312  7247 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-17 15:51:52.142   312  7247 V AudioCache: notify(0xb10114c0, 2, 0, 0)
08-17 15:51:52.142   312  7247 V AudioCache: playback complete
08-17 15:51:52.142   312  7247 V AwesomePlayer: pause_l() 
08-17 15:51:52.142   312  7247 V AudioCache: notify(0xb10114c0, 7, 0, 0)
08-17 15:51:52.142   312  7247 V AudioCache: ignored
08-17 15:51:52.142   312  7247 V AwesomePlayer: cancelPlayerEvents
08-17 15:51:52.142   312  1384 V AudioCache: wait - success
08-17 15:51:52.142   312  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-17 15:51:52.142   312  7247 D AudioPlayer: Pause Playback at 1068125
08-17 15:51:52.142   312  1384 V AwesomePlayer: reset_l() 
08-17 15:51:52.142   312  1384 V AudioCache: notify(0xb10114c0, 8, 0, 0)
08-17 15:51:52.142   312  1384 V AudioCache: ignored
08-17 15:51:52.142   312  1384 V AwesomePlayer: cancelPlayerEvents
08-17 15:51:52.142   312  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-17 15:51:52.142   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-17 15:51:52.142   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-17 15:51:52.142   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-17 15:51:52.143   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040ff60 on port 1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:51:52.143   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-17 15:51:52.144   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 15:51:52.144   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 15:51:52.144   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-17 15:51:52.144   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-17 15:51:52.144   312  7249 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-17 15:51:52.144   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 15:51:52.144   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-17 15:51:52.144   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-17 15:51:52.144   312  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-17 15:51:52.145   312  1384 D AudioPlayer: AudioPlayer releasing audio source
08-17 15:51:52.145   312  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-17 15:51:52.145   312  1384 V AwesomePlayer: reset_l() 
08-17 15:51:52.145   312  1384 V AwesomePlayer: cancelPlayerEvents
08-17 15:51:52.145   312  1384 V AwesomePlayer: ~AwesomePlayer call
08-17 15:51:52.145   312  1384 V AwesomePlayer: reset_l() 
08-17 15:51:52.145   312  1384 V AwesomePlayer: cancelPlayerEvents
08-17 15:51:52.145  7147  7245 V SoundPool: close(31)
08-17 15:51:52.145  7147  7245 V SoundPool: pointer = 0xa0045000, size = 205080, sampleRate = 48000, numChannels = 2
08-17 15:51:52.153  7218  7218 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:52.155  7218  7218 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:51:52.155  7218  7218 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:51:52.155  7218  7218 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:51:52.156  7218  7218 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:52.156  7218  7218 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 15:51:52.163  7167  7167 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-17 15:51:52.165  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-17 15:51:52.166  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-17 15:51:52.168  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:38
08-17 15:51:52.370  6885  6885 I UEI.SmartControl: Supports setup maps: true
,08-17 15:51:52.373  6885  6885 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 15:51:52.373  6885  6885 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 15:51:52.373  6885  6885 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 15:51:52.373  6885  6885 I UEI.SmartControl: ### init IR Blaster...
08-17 15:51:52.378  6885  6885 D serial_port: Configuring serial port
08-17 15:51:52.378  6885  6885 E UEI.SmartControl: UEIBLaster setting for 616
08-17 15:51:52.378  6885  6885 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 15:51:52.378  6885  6885 I UEI.SmartControl: configuring settings for MAXQ616
08-17 15:51:52.378  6885  6885 I UEI.SmartControl: Get version...
08-17 15:51:52.398  6885  7252 D UEI.SmartControl: serial port data available: 21
,08-17 15:51:52.427  6885  6885 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-17 15:51:52.427  6885  6885 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-17 15:51:52.428  6885  6885 I UEI.SmartControl: QS saving settings...
,08-17 15:51:52.432  6885  6885 D UEI.SmartControl: IR Blaster version: 25672567
08-17 15:51:52.448  6885  7252 D UEI.SmartControl: serial port data available: 4
,08-17 15:51:52.483  6885  7261 I UEI.SmartControl: Device manager: loading config....
08-17 15:51:52.484  6885  7261 D UEI.SmartControl: ----------- loading internal config...
08-17 15:51:52.485  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-17 15:51:52.489  6885  6885 E UEI.SmartControl: Services init done
08-17 15:51:52.489  6885  6885 D UEI.SmartControl: QS Service init finished
08-17 15:51:52.493  6885  6885 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 15:51:52.494  6885  6885 D UEI.SmartControl: QS Service version code: 201091
08-17 15:51:52.496  6885  6885 D UEI.SmartControl: Service requested: Control
08-17 15:51:52.504  6885  7261 E UEI.SmartControl: Loading SETTINGS...
,08-17 15:51:52.507  6885  6885 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 15:51:52.518  7147  7147 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-17 15:51:52.521  6885  6900 I UEI.SmartControl: ------ IControl API: 11
08-17 15:51:52.521  6885  6900 D UEI.SmartControl: File observer start...
08-17 15:51:52.522  6885  6900 E UEI.SmartControl: IR Port is disabled: false
08-17 15:51:52.522  6885  6900 D UEI.SmartControl: Starting file observer...
08-17 15:51:52.523  6885  6900 I UEI.SmartControl: Registering callback...
08-17 15:51:52.525  6885  6885 D UEI.SmartControl: Internal service binding...
08-17 15:51:52.525  6885  7013 I UEI.SmartControl: ------ IControl API: 19
08-17 15:51:52.526  6885  7013 I UEI.SmartControl: Registering Services Ready callback...
08-17 15:51:52.530  6885  7261 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-17 15:51:52.541  6885  7260 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 15:51:52.543  7147  7165 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-17 15:51:52.544  7147  7243 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 15:51:52.544  6885  7260 D UEI.SmartControl: -----service ready thread exits
08-17 15:51:52.545  7147  7243 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 15:51:52.546  7147  7147 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-17 15:51:52.546  7147  7147 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 15:51:52.546  6885  6901 I UEI.SmartControl: ------ IControl API: 8
08-17 15:51:52.548  7147  7147 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-17 15:51:52.548  7147  7147 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 15:51:52.549  7147  7147 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 15:51:52.549  7147  7147 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 15:51:52.550  7147  7147 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 15:51:52.550  7147  7147 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-17 15:51:52.554  7147  7147 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-17 15:51:52.559  7147  7147 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 15:51:52.560  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 15:51:52.561  7147  7147 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 15:51:52.561  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 15:51:52.562  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 15:51:52.563  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 15:51:52.563  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 15:51:52.564  7147  7147 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471441912564]
08-17 15:51:52.568  7147  7147 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-17 15:51:52.575  1035  1578 I ActivityManager: Killing 6692:com.android.gallery3d/u0a27 (adj 15): empty #17
08-17 15:51:52.610  7147  7266 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-17 15:51:52.616  1035  1578 I ActivityManager: Killing 6662:com.lge.email/u0a23 (adj 15): empty #18
08-17 15:51:52.652  1035  2087 W libprocessgroup: failed to open /acct/uid_10027/pid_6692/cgroup.procs: No such file or directory
,08-17 15:51:52.658  1035  2332 W libprocessgroup: failed to open /acct/uid_10023/pid_6662/cgroup.procs: No such file or directory
08-17 15:51:52.664  7147  7147 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-17 15:51:52.666  7147  7147 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 15:51:52.666  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 15:51:52.666  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 15:51:52.667  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 15:51:52.667  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 15:51:52.667  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-17 15:51:52.678  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-17 15:51:53.409  1035  2102 D WifiServiceImplEx: setWifiEnabled: true pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-17 15:51:53.417  1035  2102 D WifiService: setWifiEnabled: true pid=6981, uid=10118
08-17 15:51:53.418  1035  2102 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:51:53.447  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:51:53.447  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:51:53.447  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:51:53.449  1035  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 15:51:53.449  1035  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 15:51:53.455  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 15:51:53.455  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:51:53.455  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 15:51:53.455  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:51:53.456  1035  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 15:51:53.456  1035  1538 E WifiHW  : unknown target_country: EU , set to default
08-17 15:51:53.456  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 15:51:53.456  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 15:51:53.456  1035  1538 I WifiUtil: gEnableBmps=1
,08-17 15:51:53.517  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:51:53.532  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-17 15:51:53.544  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:53.548  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:53.550  1035  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:53.551  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:53.553  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-17 15:51:53.562  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:53.567  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:53.568  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 15:51:53.577  6551  7118 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 15:51:53.582  5838  5838 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 15:51:53.596  5838  5838 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-17 15:51:53.616  1035  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:53.617  1035  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:51:53.617  1035  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:51:53.643  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:51:53.712  1035  1968 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7282 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-17 15:51:53.789  7282  7282 I AppUp4:AppBoxCP: onCreate
08-17 15:51:53.790  7282  7282 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-17 15:51:53.800  7282  7282 I AppUp4:DB:  setFingerPrint start
08-17 15:51:53.801  7282  7282 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-17 15:51:53.810  7282  7282 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-17 15:51:53.810  7282  7282 I AppUp4:DB:  SDK version = 21
08-17 15:51:53.810  7282  7282 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-17 15:51:53.812  7282  7282 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-17 15:51:53.814  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:51:53.814  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:53.816  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 15:51:53.816  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 15:51:53.826  7282  7282 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 15:51:53.870  7282  7282 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 15:51:53.870  7282  7282 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:51:53.881  7282  7282 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3335226d
08-17 15:51:53.881  7282  7282 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:51:53.881  7282  7282 D AppUp4:CustFacade: isPhone : true
08-17 15:51:53.882  7282  7282 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:51:53.883  7282  7282 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-17 15:51:53.883  7282  7282 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-17 15:51:53.884  7282  7299 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-17 15:51:53.884  7282  7299 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-17 15:51:53.885  7282  7299 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-17 15:51:53.888  1035  1968 I ActivityManager: Killing 6754:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-17 15:51:53.989  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:51:53.989  1035  2102 W libprocessgroup: failed to open /acct/uid_10061/pid_6754/cgroup.procs: No such file or directory
,08-17 15:51:53.990  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 15:51:54.005  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:51:54.012  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:51:54.019  4866  7312 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 15:51:54.024  4866  7314 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:54.024  4866  7314 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:51:54.074  1035  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7315 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 15:51:54.138  7315  7315 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 15:51:54.138  7315  7315 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:51:54.140  7315  7315 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 15:51:54.141  7315  7315 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 15:51:54.169  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 15:51:54.179  1035  1117 D Tethering: InitialState.processMessage what=4
,08-17 15:51:54.180  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:51:54.191   308   893 D SoftapController: Softap fwReload - Ok
,08-17 15:51:54.194  1035  1538 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (724ms)
,08-17 15:51:54.196   308   893 D CommandListener: Setting iface cfg
08-17 15:51:54.196   308   893 D CommandListener: Trying to bring down wlan0
08-17 15:51:54.197   308   893 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:51:54.199  1035  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-17 15:51:54.202  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:51:54.202  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:51:54.202  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:51:54.202  1035  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 15:51:54.202  1035  1538 D WifiMonitor: connecting to supplicant
08-17 15:51:54.203  1035  1538 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-17 15:51:54.206  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-17 15:51:54.206  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:54.207  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:54.190  7338  7338 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:51:54.190  7338  7338 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:51:54.212  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:51:54.212  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 15:51:54.253  7338  7338 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 15:51:54.270  7315  7315 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-17 15:51:54.289  7315  7315 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-17 15:51:54.311  7338  7338 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 15:51:54.311  7338  7338 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 15:51:54.341  7315  7315 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 15:51:54.376  7315  7315 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:51:54.376  7315  7315 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:51:54.448  7338  7338 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 15:51:54.493  7338  7338 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 15:51:54.498  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-17 15:51:54.498  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 15:51:54.507  7315  7315 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 15:51:54.552  7315  7315 I HubEmail: JNI_OnLoad()
08-17 15:51:54.552  7315  7315 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 15:51:54.553  7315  7315 I HubEmail: registerNatives()
08-17 15:51:54.553  7315  7315 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 15:51:54.553  7315  7315 I HubEmail: registerNativeMethods()
08-17 15:51:54.553  7315  7315 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 15:51:54.553  7315  7315 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-17 15:51:54.567  3243  3243 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:51:54.567  3243  3243 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:54.567  3243  3243 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-17 15:51:54.572  7315  7349 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:54.576  7189  7350 W FormManager: Network not available. Please check & try again.
08-17 15:51:54.638  1035  2087 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7352 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-17 15:51:54.651  7189  7351 V FormManager: Network unavailable.
08-17 15:51:54.654  7189  7351 V FormManager: Network unavailable.
,08-17 15:51:54.663  1035  1648 I ActivityManager: Killing 6810:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-17 15:51:54.724  1035  2032 W libprocessgroup: failed to open /acct/uid_10080/pid_6810/cgroup.procs: No such file or directory
,08-17 15:51:54.842  7352  7352 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:51:54.842  7352  7352 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:51:54.846  7352  7352 D PhoneMonitor: Register our PhoneStateListener
08-17 15:51:54.871  7352  7352 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-17 15:51:54.874  7352  7352 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 15:51:54.902  7352  7352 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-17 15:51:54.903  7352  7352 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-17 15:51:54.904  7352  7352 D TelephonyAutoProfiling: [parse] Load xml
,08-17 15:51:54.907  7352  7352 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-17 15:51:54.907  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-17 15:51:54.907  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-17 15:51:54.907  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-17 15:51:54.908  7352  7352 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-17 15:51:54.908  7352  7352 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-17 15:51:54.916  7352  7352 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-17 15:51:54.954  1035  2030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7371 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:51:54.961  1035  2030 I ActivityManager: Killing 6224:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-17 15:51:55.022  1035  1722 W libprocessgroup: failed to open /acct/uid_10097/pid_6224/cgroup.procs: No such file or directory
,08-17 15:51:55.054  7338  7338 E wpa_supplicant: USIM:  scard_init function
,08-17 15:51:55.055  7338  7338 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 15:51:55.174  7338  7338 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:51:55.185  7338  7338 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:51:55.185  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:51:55.185  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-17 15:51:55.208  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:51:55.208  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 15:51:55.208  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-17 15:51:55.209  1035  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:51:55.210  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:55.211  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:55.212  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:55.213  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 15:51:55.214  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:55.215  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:55.216  1035  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 15:51:55.216  1035  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 15:51:55.217  1035  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 15:51:55.217  1035  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 15:51:55.218  1035  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 15:51:55.268  1035  2032 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7390 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-17 15:51:55.269  1035  2032 I ActivityManager: Killing 6838:com.lge.eula/1000 (adj 15): empty #17
08-17 15:51:55.383  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:51:55.383  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:51:55.383  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:51:55.384  1035  1986 W libprocessgroup: failed to open /acct/uid_1000/pid_6838/cgroup.procs: No such file or directory
,08-17 15:51:55.401  1035  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-17 15:51:55.403  1035  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-17 15:51:55.403  1035  1538 D WifiConfigStore: Loading config and enabling all networks 
08-17 15:51:55.403  1035  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 15:51:55.404  1035  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-17 15:51:55.410  1035  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 15:51:55.421  1035  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 15:51:55.421  1035  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 15:51:55.422  1035  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-17 15:51:55.422  1035  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 15:51:55.423  1035  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 15:51:55.423  1035  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-17 15:51:55.423  1035  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 15:51:55.423  1035  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 15:51:55.424  1035  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 15:51:55.424  1035  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 15:51:55.424  1035  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 15:51:55.424  1035  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 15:51:55.425  1035  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 15:51:55.425  1035  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 15:51:55.425  1035  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 15:51:55.425  1035  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 15:51:55.426  1035  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 15:51:55.426  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:51:55.427  1035  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 15:51:55.428  1035  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 15:51:55.428  1035  1538 D WifiNative-HAL: Setting external_sim to 1
08-17 15:51:55.428  1035  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 15:51:55.429  1035  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 15:51:55.429  1035  1538 I WifiNative-HAL: startHal
08-17 15:51:55.429  1035  1538 D wifi    : setting scan oui 0xaf6b0f80
08-17 15:51:55.429  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:51:55.429  1035  1538 I WifiNative-HAL: startHal
08-17 15:51:55.429  1035  1538 D wifi    : setting scan oui 0xaf6b0f80
08-17 15:51:55.430  1035  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 15:51:55.430  1035  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 15:51:55.431  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 15:51:55.431  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 15:51:55.431  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 15:51:55.432  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:51:55.432  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:51:55.432  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:51:55.432  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 15:51:55.432  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 15:51:55.433  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 15:51:55.433  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:51:55.433  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:51:55.433  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:51:55.433  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:51:55.434  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:51:55.434  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:51:55.434  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 15:51:55.434  7338  7338 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 15:51:55.435  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:55.435  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:55.435  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from andro,id.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:55.435  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:55.435  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:51:55.435  1969  1969 D WfdService: Waiting for WifiP2p enabling
08-17 15:51:55.435  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 15:51:55.435  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:51:55.436  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:55.436  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:51:55.436  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:51:55.437  1035  1538 E WifiNative: : [194,240,204 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 15:51:55.437  1035  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 15:51:55.438  1035  1538 D WifiNative-wlan0: RECONNECT: returned true
08-17 15:51:55.439  1035  1538 D WifiNative-wlan0: doString: [STATUS]
08-17 15:51:55.439  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 15:51:55.440  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 15:51:55.440  1969  1969 D WfdsService: Supplicant Connection state is changed : true
08-17 15:51:55.440  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:51:55.441  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-17 15:51:55.441  1969  2337 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 15:51:55.441  1969  2337 D WfdsService: Set the WFDS Monitor: true
08-17 15:51:55.441  1035  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:51:55.441  1969  2337 D WfdsMonitor: WfdsMonitorThread create
08-17 15:51:55.441  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:51:55.441  1969  2337 D WfdsMonitor: WFDS Monitor is created and started
08-17 15:51:55.441  1969  2337 D WfdsService: WiFi: Supplicant connection re-established
08-17 15:51:55.442  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:51:55.442  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.442  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:55.442  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:51:55.442  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:55.443  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:55.443  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:55.443  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:51:55.443  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:55.444  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:55.444   308   893 D CommandListener: Setti,ng iface cfg
08-17 15:51:55.445   308   893 D CommandListener: Trying to bring up p2p0
08-17 15:51:55.445  1035  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 15:51:55.445  1035  1537 D LGWifiP2pService: P2pEnablingState
08-17 15:51:55.445  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:51:55.445  1035  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.445  1035  1537 D LGWifiP2pService: P2p socket connection successful
08-17 15:51:55.445  1035  1537 D LGWifiP2pService: P2pEnabledState
08-17 15:51:55.446  1035  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 15:51:55.446  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 15:51:55.446  1035  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 15:51:55.446  1035  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 15:51:55.447  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 15:51:55.447  1035  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 15:51:55.447  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 15:51:55.447  1035  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-17 15:51:55.447  1035  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 15:51:55.447  1035  1537 D LGWifiP2pService: before postfix = G3
08-17 15:51:55.447  1035  1537 D WifiServerServiceExt: postfix byte check : 2
08-17 15:51:55.447  1035  1537 D LGWifiP2pService: after postfix = G3
08-17 15:51:55.447  1035  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 15:51:55.448  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 15:51:55.448  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 15:51:55.448  1035  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 15:51:55.448  1035  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 15:51:55.448  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 15:51:55.448  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 15:51:55.449  1035  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 15:51:55.449  1035  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 15:51:55.449  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 15:51:55.449  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-17 15:51:55.449  1035  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 15:51:55.449  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 15:51:55.450  1035  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.450  1035  1558 I WifiNative-HAL: startHal
08-17 15:51:55.450  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 15:51:55.450  1035  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:51:55.451  1035  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 15:51:55.451  1035  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf6b0f80
08-17 15:51:55.451  1035  1558 D wifi    : failed to get capabilities : -3
08-17 15:51:55.451  1035  1558 E WifiScanningService: could not get scan capabilities
08-17 15:51:55.451  1969  1969 D WfdsService: WifiP2pState is changed : true
08-17 15:51:55.451  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-17 15:51:55.451  1969  2337 D WfdsService: Receive the WFDS_ENABLE Method
08-17 15:51:55.451  1969  2337 D WfdsService: Set the WFDS Monitor: true
08-17 15:51:55.451  1969  2337 D WfdsService: Connected to the supplicant for wfds
08-17 15:51:55.451  1969  2337 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 15:51:55.451  1969  2337 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
08-17 15:51:55.451  1969  2337 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
08-17 15:51:55.451  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 15:51:55.451  1969  2337 D WfdsService: selectPreferredScanChannel [36]
08-17 15:51:55.451  1969  2337 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-17 15:51:55.452  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:51:55.452  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.453  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 15:51:55.453  7338  7338 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:51:55.453  1969  1969 D WfdsService: isConnected: false
08-17 15:51:55.453  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.454  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.455  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:51:55.455  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.455  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.455  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.455  1035  7389 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:51:55.455  1035  7389 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.455  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.455  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.455  1035  7389 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:51:55.455  1035  7389 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.455  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.455  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.456  1035  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 15:51:55.456  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:51:55.456  1969  7407 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 15:51:55.457  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:51:55.457  1969  7407 E CtrlSupplicant: Succeed to open control connection
08-17 15:51:55.457  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:51:55.457  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 15:51:55.457  1969  7407 E CtrlSupplicant: Succeed to open monitor connection
08-17 15:51:55.457  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 15:51:55.457  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:51:55.459  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 15:51:55.459  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:51:55.459  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:51:55.460  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:51:55.460  1035  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 15:51:55.460  1035  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 15:51:55.462  1035  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 15:51:55.462  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
08-17 15:51:55.462  1035  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 15:51:55.462  1035  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 15:51:55.462  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-,17 15:51:55.463  1035  1538 D WifiNative-wlan0: SCAN: returned true
08-17 15:51:55.463  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 15:51:55.463  1035  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 15:51:55.463  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 15:51:55.463  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 15:51:55.464  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:51:55.464  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:51:55.464  1969  7407 D WfdsMonitor: Supplicant connection established
08-17 15:51:55.464  1035  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 15:51:55.464  1969  2337 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-17 15:51:55.464  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 15:51:55.464  1035  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 15:51:55.465  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 15:51:55.465  1035  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 15:51:55.465  1969  1969 D WfdsService: Update P2p Interface State: 3
08-17 15:51:55.465  1035  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 15:51:55.465  7338  7338 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 15:51:55.465  1035  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 15:51:55.465  1035  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,08-17 15:51:55.466  1035  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 15:51:55.466  1035  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 15:51:55.467  1035  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 15:51:55.468  1035  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 15:51:55.468  1035  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 15:51:55.468  1035  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 15:51:55.542  1035  1578 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7412 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:51:55.542  1035  1578 I ActivityManager: Killing 6860:com.lge.bnr/1000 (adj 15): empty #17
,08-17 15:51:55.592  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6860/cgroup.procs: No such file or directory
,08-17 15:51:55.623  7412  7412 I art     : Almond Protected OAT
,08-17 15:51:55.632  7338  7338 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 15:51:55.633  1035  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 15:51:55.633  1035  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 15:51:55.633  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=194436  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:51:55.633  1035  1537 D LGWifiP2pService: InactiveState
08-17 15:51:55.634  1035  1537 D LGWifiP2pService: InactiveState{ when=-178ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.634  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-178ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.634  1035  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 15:51:55.635  7338  7338 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:51:55.636  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.636  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:51:55.636  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:51:55.637  7338  7338 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:51:55.637  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-17 15:51:55.637  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.637  1035  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 15:51:55.638  1035  1537 D LGWifiP2pService: InactiveState{ when=-173ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.638  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-173ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.638  1035  1537 D LGWifiP2pService: InactiveState{ when=-158ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.638  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-158ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.638  1969  7407 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:51:55.638  1969  7407 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:51:55.638  1035  1537 D LGWifiP2pService: DefaultState{ when=-158ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.638  1969  7407 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:51:55.638  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.638  1035  7389 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:51:55.638  1035  7389 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.639  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.639  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.639  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:51:55.639  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.639  1035  7389 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:51:55.639  1035  7389 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.639  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.639  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.639  1035  7389 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:51:55.639  1035  7389 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.639  1035  7389 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.639  1035  7389 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:51:55.639  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=194438  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:51:55.640  1035  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:51:55.640  1035  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:51:55.642  1035  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:51:55.642  1035  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:51:55.643  1035  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:51:55.643  1605  1605 D StatusBar.NetworkController: refreshVi,ews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:55.643  1035  1538 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:51:55.644  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:51:55.644  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:55.644  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:51:55.644  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:55.644  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:51:55.645  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:51:55.645  1035  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:51:55.647  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:51:55.647  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-17 15:51:55.650  1035  1537 D LGWifiP2pService: InactiveState{ when=-16ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:51:55.650  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.650  1035  1537 D LGWifiP2pService: DefaultState{ when=-16ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.650  1035  1537 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.651  1969  2337 W WfdsService: DefaultState - msg [9441285] is not handled
,08-17 15:51:55.651  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.651  1035  1537 D LGWifiP2pService: DefaultState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.651  1035  1537 D LGWifiP2pService: InactiveState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.651  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:51:55.651  1035  1537 D LGWifiP2pService: DefaultState{ when=-14ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:55.652  1035  1035 E WifiServerServiceExt: No p2p device connected
08-17 15:51:55.682  7412  7412 D WeatherApplication: removeAccount
,08-17 15:51:55.683  7412  7412 D WeatherApplication: Account.length = 0
,08-17 15:51:55.684  7412  7412 E WeatherApplication: OPERATOR:OPEN
08-17 15:51:55.688  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:51:55
08-17 15:51:55.691  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:51:55.691  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
08-17 15:51:55.692  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 15:51:55.694  7412  7412 D WeatherAncestor: connectivity changed - connection : true
08-17 15:51:55.695  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-17 15:51:55.703  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 15:51:55.703  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-17 15:51:55.703  7412  7412 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-17 15:51:55.718  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:51:55.718  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:51:55
,08-17 15:51:55.760  1035  1051 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7432 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:51:55.761  1035  1051 I ActivityManager: Killing 2223:com.lge.music/u0a34 (adj 15): empty #17
,08-17 15:51:55.804   312   312 V AudioFlinger: 2223 died, releasing its sessions
08-17 15:51:55.804   312   312 V AudioFlinger:  pid 1880 @ 0
08-17 15:51:55.804   312   312 V AudioFlinger:  pid 3243 @ 1
08-17 15:51:55.804   312   312 V AudioFlinger:  pid 3243 @ 2
,08-17 15:51:55.893  1035  1950 W libprocessgroup: failed to open /acct/uid_10034/pid_2223/cgroup.procs: No such file or directory
,08-17 15:51:56.032   278   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-17 15:51:56.032   278   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 15:51:56.032   278   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:51:56.033  7432  7451 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 15:51:56.037   278   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:51:56.037   278   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 15:51:56.037   278   383 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:51:56.038  7432  7451 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 15:51:56.051   278   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:51:56.051   278   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-17 15:51:56.051   278   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:51:56.056  7432  7454 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 15:51:56.061   278   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:51:56.062   278   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 15:51:56.062   278   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:51:56.063  7432  7454 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-17 15:51:56.338  7432  7432 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 15:51:56.341  1035  1939 I art     : Explicit concurrent mark sweep GC freed 72431(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.053ms total 172.390ms
,08-17 15:51:56.356  7432  7432 I LibraryLoader: Loading: webviewchromium
,08-17 15:51:56.359  7432  7432 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5174-5178)
,08-17 15:51:56.359  7432  7432 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:51:56.364  7432  7432 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fb4739e}
08-17 15:51:56.365  7432  7432 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:51:56.366  7432  7432 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 15:51:56.376  7432  7432 I BrowserStartupController: Initializing chromium process, renderers=0
08-17 15:51:56.377  7432  7432 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:51:56.388  7432  7432 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 15:51:56.389  7432  7432 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-17 15:51:56.389  7432  7432 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-17 15:51:56.396   312  4546 V AudioPolicyService: registerClient() client 0xb0403d00, uid 10093
,08-17 15:51:56.397  7432  7485 W AudioManagerAndroid: Requires BLUETOOTH permission
08-17 15:51:56.407  7432  7432 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:51:56.407  7432  7432 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:51:56.407  7432  7432 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:51:56.407  7432  7432 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:51:56.407  7432  7432 I Adreno-EGL: Remote Branch: 
08-17 15:51:56.407  7432  7432 I Adreno-EGL: Local Patches: 
08-17 15:51:56.407  7432  7432 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:51:56.453  1035  2114 D WifiServiceImplEx: setWifiEnabled: false pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:51:56.453  1035  2114 D WifiService: setWifiEnabled: false pid=6981, uid=10118
08-17 15:51:56.453  1035  2114 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:51:56.469  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:51:56.469  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-17 15:51:56.469  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:51:56.470  1035  1538 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:56.471  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:56.473  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,08-17 15:51:56.474  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:51:56.488  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:56.488  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:56.488  1035  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21e3f8d3
08-17 15:51:56.488  1035  1537 D LGWifiP2pService: P2pDisablingState
08-17 15:51:56.488  1035  1537 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:51:56.488  1035  1537 D LGWifiP2pService: p2p socket connection lost
08-17 15:51:56.489  1035  1537 D LGWifiP2pService: P2pDisabledState
08-17 15:51:56.489  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 15:51:56.489  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-17 15:51:56.489  1035  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:56.489  1035  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:51:56.490  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 15:51:56.490   308   893 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:51:56.493  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 15:51:56.493  1969  1969 D WfdsService: WifiP2pState is changed : false
08-17 15:51:56.495  1969  2337 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 15:51:56.495  1969  2337 D WfdsService: Set the WFDS Monitor: false
08-17 15:51:56.497  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 15:51:56.499  1969  2337 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:51:56.499  1969  7407 D CtrlSupplicant: Received on exit socket, terminate
08-17 15:51:56.499  1969  7407 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 15:51:56.499  1969  2337 D WfdsService: STATE : WfdsDisabledState - enter
08-17 15:51:56.499  1969  7407 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 15:51:56.499  1969  7407 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 15:51:56.499  1969  2337 W WfdsService: DefaultState - msg [9445378] is not handled
,08-17 15:51:56.500  1969  2340 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 15:51:56.500  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:51:56.500  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:51:56.501  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:56.502  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:51:56.502  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:51:56.502  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 15:51:56.503  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:56.503  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:51:56.503  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:51:56.503  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:56.503  1035  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 15:51:56.505  1035  1538 D WifiNative-p2p0: TERMINATE: returned true
08-17 15:51:56.505  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:51:56.505  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:51:56.505  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:51:56.508  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:51:56.508  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:51:56.510  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 15:51:56.510  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 15:51:56.510  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:56.511  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:51:56.511  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:56.511  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:51:56.512  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:56.512  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:51:56.512  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:51:56.513  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:51:56.513  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:51:56.514  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:51:56.514  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 15:51:56.517  7432  7432 I NSApplication: Starting up...
08-17 15:51:56.525  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:51:56.552  7338  7338 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 15:51:56.552  7338  7338 I wpa_supplicant: monitor socket send errors count : 1
08-17 15:51:56.552  7338  7338 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-4\x00 that cannot receive messages
,08-17 15:51:56.555  1035  7389 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 15:51:56.555  1035  7389 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 15:51:56.584  1035  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7500 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 15:51:56.585  1035  1050 I ActivityManager: Killing 6715:com.android.vending/u0a44 (adj 15): empty #17
,08-17 15:51:56.627  1035  1722 W libprocessgroup: failed to open /acct/uid_10044/pid_6715/cgroup.procs: No such file or directory
,08-17 15:51:56.666  7500  7500 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 15:51:56.722  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:51:56.723  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 15:51:56.723  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:51:56.723  1035  7389 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:51:56.723  7338  7338 W wpa_supplicant: USIM:  scard_deinit function
,08-17 15:51:56.727  1035  7389 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-17 15:51:56.727  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:51:56.727  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:51:56.728  1035  1117 D Tethering: InitialState.processMessage what=4
08-17 15:51:56.729  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:51:56.729  1035  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=195533
08-17 15:51:56.731  1035  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=195534
08-17 15:51:56.732  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=195535  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:51:56.734  1035  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=195537  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:51:56.735  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:56.736  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:51:56.802  7338  7338 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 15:51:56.808  1035  7389 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 15:51:56.808  1035  7389 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 15:51:56.808  1035  7389 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 15:51:56.809  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
08-17 15:51:56.811  1969  1969 D WfdsService: Supplicant Connection state is changed : false
08-17 15:51:56.811  1969  2337 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 15:51:56.811  1969  2337 D WfdsService: Set the WFDS Monitor: false
08-17 15:51:56.811  1969  2337 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:51:56.811  1035  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 15:51:56.811  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:51:56.811  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:51:56.811  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:51:56.814  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:51:56.815  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-17 15:51:56.815  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 15:51:56.815  2474  2474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:51:56.816  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 15:51:56.816  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated,
08-17 15:51:56.818  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:56.819  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:56.965  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-17 15:51:56.969  6551  7118 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 15:51:56.995  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:51:57.007  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:51:57.007  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:57.008  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 15:51:57.008  7282  7282 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 15:51:57.010  7282  7282 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 15:51:57.015  7282  7282 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3335226d
,08-17 15:51:57.015  7282  7282 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:51:57.015  7282  7282 D AppUp4:CustFacade: isPhone : true
08-17 15:51:57.015  7282  7282 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:51:57.016  7282  7282 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 15:51:57.020  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:57.020  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:51:57.021  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:51:57.024  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:51:57.032  4866  7531 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:51:57.039  7315  7315 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 15:51:57.040  4866  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:57.040  4866  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 15:51:57.062  7315  7534 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:51:57.071  3243  3243 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:51:57.072  3243  3243 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:51:57.072  3243  3243 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 15:51:57.076  7189  7537 W FormManager: Network not available. Please check & try again.
,08-17 15:51:57.084  7352  7352 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 15:51:57.084  7352  7352 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 15:51:57.091  7189  7538 V FormManager: Network unavailable.
,08-17 15:51:57.098  7189  7538 V FormManager: Network unavailable.
08-17 15:51:57.106  7412  7412 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:51:57
,08-17 15:51:57.110  7412  7412 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:51:57.110  7412  7412 D Weather.Utils: 2 : All the weather widget is gone.
08-17 15:51:57.111  7412  7412 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 15:51:57.111  7412  7412 D WeatherAncestor: connectivity changed - connection : true
08-17 15:51:57.111  7412  7412 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e56c733
08-17 15:51:57.112  7412  7412 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 15:51:57.112  7412  7412 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 15:51:57.112  7412  7412 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 15:51:57.112  7412  7412 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:51:57.112  7412  7412 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:51:57
08-17 15:51:57.135  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:51:57.135  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:51:57.135  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:51:57.135  7072  7072 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 15:51:57.138  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:51:57.139  7072  7072 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:51:57.139  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:51:57.139  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:51:57.139  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:51:57.139  7072  7072 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:51:57.139  7072  7072 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:51:57.151  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:51:57.155  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:51:57.159  7189  7546 W FormManager: Network not available. Please check & try again.
08-17 15:51:57.163  7189  7547 V FormManager: Network unavailable.
08-17 15:51:57.165  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.165  7189  7547 V FormManager: Network unavailable.
,08-17 15:51:57.169  1035  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=722457020, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-17 15:51:57.188  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:51:57.191  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 15:51:57.198  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.206  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 15:51:57.208  7189  7549 W FormManager: Network not available. Please check & try again.
08-17 15:51:57.228  7189  7550 V FormManager: Network unavailable.
,08-17 15:51:57.238  7189  7550 V FormManager: Network unavailable.
08-17 15:51:57.241  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:51:57.241  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 15:51:57.243  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:51:57.245  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:51:57.252  4866  7551 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:51:57.258  4866  7552 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 15:51:57.258  4866  7552 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 15:51:57.310  1035  2032 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7553 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 15:51:57.437  7553  7553 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 15:51:57.438  7553  7553 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-17 15:51:57.446  7553  7553 V [BNRBootReceiver]: Boot Receiver Return
08-17 15:51:57.446  7553  7553 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-17 15:51:57.453  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:51:57.468  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:51:57.478  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.483  6885  7262 D UEI.SmartControl: Internal timer expired: 2
08-17 15:51:57.483  6885  7262 D UEI.SmartControl: unbind internal service
,08-17 15:51:57.502  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:51:57.502  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:51:57.503  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:51:57.505  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:51:57.512  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:51:57.512  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:51:57.512  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:51:57.516  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:51:57.523  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.531  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:51:57.531  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:51:57.533  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:51:57.538  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:51:57.542  6885  7256 D serial_port: close(fd = 24)
08-17 15:51:57.545  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:51:57.545  6885  7256 I UEI.SmartControl: Serial port is closed.
08-17 15:51:57.545  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-17 15:51:57.545  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:51:57.549  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:51:57.556  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.564  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:51:57.564  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:51:57.568  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:51:57.582  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:51:57.588  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:51:57.593  7189  7575 W FormManager: Network not available. Please check & try again.
,08-17 15:51:57.598  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.600  7189  7576 V FormManager: Network unavailable.
08-17 15:51:57.606  7189  7576 V FormManager: Network unavailable.
,08-17 15:51:57.613  1035  2102 I ActivityManager: Killing 7088:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-17 15:51:57.644  1035  2030 W libprocessgroup: failed to open /acct/uid_10037/pid_7088/cgroup.procs: No such file or directory
,08-17 15:51:57.650  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:51:57.650  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:51:57.652  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:51:57.655  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:51:57.662  4866  7577 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:51:57.666  4866  7578 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:51:57.666  4866  7578 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 15:51:57.678  7119  7119 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 15:51:57.678  7119  7119 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:51:57.678  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:51:57.684  7189  7580 W FormManager: Network not available. Please check & try again.
08-17 15:51:57.691  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:51:57.696  7189  7581 V FormManager: Network unavailable.
08-17 15:51:57.699  7189  7581 V FormManager: Network unavailable.
08-17 15:51:57.699  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:51:57.719  7147  7147 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-17 15:51:57.719  7147  7147 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:38
08-17 15:51:57.721  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=722457020 [*alarm*], flags=0x0
,08-17 15:51:59.471  1035  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:51:59.471  1035  1788 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 15:51:59.512  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:51:59.512  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:51:59.512  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:51:59.513  1035  1117 D BluetoothManagerService: Message: 1
08-17 15:51:59.513  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 15:51:59.539  1035  1117 D BluetoothManagerService: Message: 20
08-17 15:51:59.539  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a1561e3:true
,08-17 15:51:59.545  7218  7218 D BluetoothAdapterState: make
08-17 15:51:59.549  7218  7218 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 15:51:59.550  7218  7218 I bluedroid-qcom: init
08-17 15:51:59.551  7218  7589 I BluetoothAdapterState: Entering OffState
08-17 15:51:59.551  7218  7218 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 15:51:59.552  7218  7218 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:51:59.552  7218  7218 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:51:59.552  7218  7218 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 15:51:59.552  7218  7218 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 15:51:59.554  7218  7218 I bluedroid-qcom: get_profile_interface socket
08-17 15:51:59.554  7218  7218 I bluedroid-qcom: get_profile_interface map_client
,08-17 15:51:59.540  7592  7592 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:51:59.561  7218  7593 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 15:51:59.563  7218  7593 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:51:59.550  7592  7592 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:51:59.573  7592  7592 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 15:51:59.573  7592  7592 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 15:51:59.573  7592  7592 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-17 15:51:59.578  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:51:59.578  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 15:51:59.580  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 15:51:59.580  1035  1117 D BluetoothManagerService: Message: 40
08-17 15:51:59.580  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 15:51:59.581  7218  7235 I bluedroid-qcom: config_hci_snoop_log
08-17 15:51:59.582  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 15:51:59.582  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 15:51:59.583  7592  7592 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 15:51:59.589  7218  7589 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-17 15:51:59.594  7218  7593 D BluetoothAdapterProperties: Name is: G3
08-17 15:51:59.594  7218  7589 D BluetoothAdapterProperties: Setting state to 11
08-17 15:51:59.594  7218  7589 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 15:51:59.595  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:51:59.595  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 15:51:59.595  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 15:51:59.597  7592  7592 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 15:51:59.597  7592  7592 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 15:51:59.602  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:59.602  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 15:51:59.610  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-17 15:51:59.613  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:59.616  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:59.628  7218  7589 I LGBluetoothServiceJni: classInitNative: succeeds
,08-17 15:51:59.634  7218  7218 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:51:59.635  7218  7218 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:51:59.635  7218  7218 V BluetoothPbapReceiver: ***********state = 11
08-17 15:51:59.636  7218  7589 D BluetoothBondStateMachine: make
08-17 15:51:59.638  7218  7589 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.638  7218  7589 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 15:51:59.638  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:51:59.638  7218  7589 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.638  7218  7589 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 15:51:59.639  7218  7589 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 15:51:59.639  7218  7608 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 15:51:59.642  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:51:59.677  1035  1050 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7610 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-17 15:51:59.682  7218  7218 D HeadsetService: Received start request. Starting profile...
08-17 15:51:59.682  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:51:59.683  7218  7218 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:51:59.683  7218  7218 D LGBluetoothHfpAdapter: Version 1.6
08-17 15:51:59.685  7218  7218 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:51:59.686  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:51:59.686  7218  7218 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:51:59.687  7218  7218 D HeadsetStateMachine: make
08-17 15:51:59.691  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:51:59.695  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:51:59.701  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:51:59.705  7218  7589 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:51:59.714  7218  7218 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:51:59.714  7218  7218 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:51:59.718  7218  7589 V LGMDMManager: Create singleton instance
08-17 15:51:59.720  7218  7589 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 15:51:59.721  7218  7218 D HeadsetStateMachine: max_hf_connections = 1
08-17 15:51:59.721  7218  7218 I bluedroid-qcom: get_profile_interface handsfree
08-17 15:51:59.723  7218  7218 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 15:51:59.723   312  1384 V AudioPolicyService: registerClient() client 0xb101fea0, uid 1002
08-17 15:51:59.724   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:51:59.724   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:51:59.724   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:51:59.724  7218  7218 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:51:59.724   312  4546 V AudioFlinger: registerClient() client 0xb14331d8, pid 7218
08-17 15:51:59.724   312  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:51:59.724   312  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:51:59.725  1880  2569 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:51:59.725  1880  2569 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:51:59.725   312  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:51:59.725   312  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:51:59.725  1880  4541 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:51:59.725  1880  4541 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:51:59.725  7218  7235 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:51:59.725  7218  7235 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 15:51:59.725  1035  2332 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:51:59.725  1035  2332 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:51:59.725  7218  7235 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:51:59.725  1035  2332 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:51:59.725  7218  7235 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 15:51:59.725  1035  2332 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:51:59.725  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:51:59.725  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:51:59.726  7218  7218 V ToneGenerator: Create Track: 0xb4928a80
08-17 15:51:59.726  1605  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:51:59.726  1605  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:51:59.726  7218  7218 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 15:51:59.726  7218  7218 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 15:51:59.726  3243  3259 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:51:59.726  3243  3259 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:51:59.726   312  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:51:59.726   312  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:51:59.726  3243  3259 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:51:59.726   312  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:51:59.726  3243  3259 V AudioSystem: ioConfigChanged,() opening already existing output! 4
08-17 15:51:59.726   312  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:51:59.726   312  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 15:51:59.726   312   312 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:51:59.726   312   312 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 15:51:59.726   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:51:59.726   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:51:59.726  7218  7218 V AudioSystem: getLatency() output 2, latency 50
08-17 15:51:59.726  7218  7218 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 15:51:59.726  7218  7218 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 15:51:59.727   312  4546 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:51:59.727   312  4546 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:51:59.727   312  4546 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:51:59.727   312  4546 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:51:59.727   312  4546 V AudioFlinger: createTrack() lSessionId: 22
08-17 15:51:59.727  7218  7218 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 15:51:59.728   312  4546 V AudioFlinger: acquiring 22 from 7218, for 7218
08-17 15:51:59.728   312  4546 V AudioFlinger:  added new entry for 22
08-17 15:51:59.728  7218  7218 V ToneGenerator: ToneGenerator INIT OK, time: 198547
08-17 15:51:59.728  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:51:59.729  7218  7625 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 15:51:59.729  7218  7625 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:51:59.729  7218  7625 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:51:59.729  7218  7625 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 15:51:59.729   312  4545 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7218
08-17 15:51:59.731  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.731   312  4545 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 15:51:59.731   312  4545 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 15:51:59.731   312  4545 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 15:51:59.731   312  4545 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 15:51:59.731   312  4545 V voice   : voice_set_parameters: exit with code(0)
08-17 15:51:59.731   312  4545 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 15:51:59.731   312  4545 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 15:51:59.731   312  4545 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 15:51:59.731   312  4545 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 15:51:59.731   312  4545 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 15:51:59.731   312  4545 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 15:51:59.732  7218  7625 V ToneGenerator: ToneGenerator destructor
08-17 15:51:59.732  7218  7625 V ToneGenerator: stopTone
08-17 15:51:59.732  7218  7625 V ToneGenerator: Delete Track: 0xb4928a80
08-17 15:51:59.732  7218  7625 V AudioTrack: ~AudioTrack, releasing session id from 7218 on behalf of 7218
08-17 15:51:59.732   312   312 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 15:51:59.732   312   312 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 15:51:59.732   312  4546 V AudioFlinger: releasing 22 from 7218 for 7218
08-17 15:51:59.732   312   312 V AudioFlinger: PlaybackThread::Track destructor
08-17 15:51:59.732   312  4546 V AudioFlinger:  decremented refcount to 0
08-17 15:51:59.732   312  1273 V AudioPolicyService: AudioCommandThread() waking up
08-17 15:51:59.732   312  4546 V AudioFlinger: purging stale effects
08-17 15:51:59.732   312   312 V AudioFlinger: removeClient_l() pid 7218, calling pid 312
08-17 15:51:59.732   312  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 15:51:59.732   312  1273 V AudioPolicyManager: releaseOutput() 2
08-17 15:51:59.732   312  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 15:51:59.733  7218  7218 D A2dpService: Received start request. Starting profile...
08-17 15:51:59.733  7218  7218 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 15:51:59.734  7218  7218 V Avrcp   : make
08-17 15:51:59.735  7218  7218 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 15:51:59.735  7218  7218 I bluedroid-qcom: get_profile_interface avrcp
08-17 15:51:59.735  1035  2332 W Process : Unable to open /proc/7630/status
08-17 15:51:59.743  7218  7218 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 15:51:59.744  7218  7218 E AudioManager: No RCC entry present to update
08-17 15:51:59.744  7218  7218 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 15:51:59.747  7218  7218 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 15:51:59.748  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 15:51:59.748  7218  7218 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 15:51:59.752  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 15:51:59.792  7610  7610 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 15:51:59.792  7610  7610 W LG Account v2.2: No ProfileInfo entries
08-17 15:51:59.792  7610  7610 I LG Account v2.2: isEnabled: false
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]Country: EU
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]Operator: OPEN
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]Ranking support: false
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]Comfort support: false
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]Accessory: true
08-17 15:51:59.792  7610  7610 I Feature : [Lifetracker]Health device: true
08-17 15:51:59.793  7610  7610 I Feature : [Lifetracker]Extra Pedometer: false
08-17 15:51:59.793  7610  7610 I Feature : [Lifetracker]Blood glucose device: false
08-17 15:51:59.793  7610  7610 I Feature : [Lifetracker]Device Number: 3
,08-17 15:51:59.800  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:51:59.803  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 15:51:59.865  1035  1986 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:51:59.865  1035  1986 V SIM_STK : Menu title from STK is T-Mobile
,08-17 15:51:59.948  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 15:51:59.959  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-17 15:51:59.963  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-17 15:51:59.964  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 15:51:59.964  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 15:51:59.964  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 15:51:59.965  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:51:59.965  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 15:51:59.965  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 15:51:59.965  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 15:51:59.965  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:51:59.965  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 15:51:59.965  7218  7218 I BluetoothA2dpServiceJni: classInitNative
08-17 15:51:59.965  7218  7218 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:51:59.966  7218  7218 D A2dpStateMachine: make
08-17 15:51:59.969  7218  7218 I bluedroid-qcom: get_profile_interface a2dp
08-17 15:51:59.969  7218  7636 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 15:51:59.973  7218  7218 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:51:59.973  7218  7218 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 15:51:59.974  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.975  7218  7635 D A2dpStateMachine: Enter Disconnected: -2
08-17 15:51:59.975  7218  7218 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 15:51:59.977  7218  7218 D HidService: Received start request. Starting profile...
08-17 15:51:59.977  7218  7218 I bluedroid-qcom: get_profile_interface hidhost
08-17 15:51:59.977  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.978  7218  7218 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:51:59.979  7218  7218 D HealthService: Received start request. Starting profile...
08-17 15:51:59.983  7218  7218 I bluedroid-qcom: get_profile_interface health
08-17 15:51:59.983  7218  7218 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:51:59.983  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.984  7218  7218 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:51:59.986  7218  7218 D PanService: Received start request. Starting profile...
08-17 15:51:59.986  7218  7218 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:51:59.986  7218  7218 I bluedroid-qcom: get_profile_interface pan
08-17 15:51:59.995  7218  7218 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 15:51:59.995  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:51:59.995  7218  7218 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-17 15:52:00.000  7218  7218 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:52:00.000  7218  7218 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:52:00.000  7218  7218 D BtGatt.GattService: start()
08-17 15:52:00.000  7218  7218 I bluedroid-qcom: get_profile_interface gatt
08-17 15:52:00.001  7218  7218 D BtGatt.AdvertiseManager: advertise manager created
08-17 15:52:00.010  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:00.014  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:52:00.015  7218  7218 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 15:52:00.017  7218  7218 V BluetoothMapService: BluetoothMapBinder()
08-17 15:52:00.018  7218  7218 D BluetoothMapService: Received start request. Starting profile...
08-17 15:52:00.018  7218  7218 D BluetoothMapService: start()
08-17 15:52:00.022  7218  7218 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 15:52:00.025  7218  7218 D BluetoothMapEmailAppObserver: createReceiver()
,08-17 15:52:00.027  7218  7218 D BluetoothMapEmailAppObserver: initObservers()
08-17 15:52:00.028  7218  7218 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-17 15:52:00.048  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-17 15:52:00.048  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-17 15:52:00.048  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-17 15:52:00.048  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-17 15:52:00.049  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:00.050  7218  7218 D HeadsetStateMachine: Proxy object connected
08-17 15:52:00.052  7218  7218 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 15:52:00.052  7218  7218 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-17 15:52:00.058  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 15:52:00.059  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-17 15:52:00.061  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-17 15:52:00.062  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-17 15:52:00.063  7218  7218 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:52:00.064  7218  7625 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 15:52:00.064  7218  7625 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:52:00.065  7218  7625 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 15:52:00.069  7218  7218 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:52:00.076  7218  7218 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:52:00.080  7218  7218 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:52:00.080  7218  7218 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 15:52:00.083  7218  7218 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:52:00.090  7218  7218 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 15:52:00.090  7218  7218 V BluetoothMapService: Handler(): got msg=1
08-17 15:52:00.092  7218  7589 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 15:52:00.092  7218  7589 I bluedroid-qcom: enable
08-17 15:52:00.092  7218  7645 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 15:52:00.092  7218  7645 I bt-btu  : btu_task pending for preload complete event
08-17 15:52:00.092  7218  7589 I bt_hci_bdroid: init
08-17 15:52:00.094  7218  7589 I bt_vendor: bt-vendor : init
08-17 15:52:00.094  7218  7589 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 15:52:00.094  7218  7589 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 15:52:00.094  7218  7589 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 15:52:00.094  7218  7589 D bt_userial_mct: userial_init
08-17 15:52:00.094  7218  7589 D bt_hci_bdroid: set_power 1
08-17 15:52:00.094  7218  7589 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 15:52:00.095  7218  7589 I bt_vendor: Starting hciattach daemon
08-17 15:52:00.095  7218  7589 I bt_vendor: try to set true
08-17 15:52:00.096  7218  7218 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.080  7648  7648 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:00.080  7648  7648 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:00.099  7218  7218 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:52:00.099  7218  7218 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:52:00.099  7218  7218 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:52:00.099  7218  7218 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.100  7218  7218 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-17 15:52:00.126  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 15:52:00.252  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 15:52:00.270  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:52:00.302  7661  7661 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:52:00.315  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 15:52:00.328  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:52:00.340  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 15:52:00.379  7666  7666 I libmdmdetect: ESOC framework not supported
08-17 15:52:00.382  7666  7666 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 15:52:00.395  7666  7666 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-17 15:52:00.395  7666  7666 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 15:52:00.395  7666  7666 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 15:52:00.395  7666  7666 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-17 15:52:00.395  7666  7666 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 15:52:00.395  7666  7666 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 15:52:00.395  7666  7666 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-17 15:52:00.444  7666  7670 E QC-QMI  : qmi_client [7666] 14: failed to locate client data
,08-17 15:52:00.445   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 15:52:00.445   475   475 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-17 15:52:00.486  7671  7671 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 15:52:00.498  7672  7672 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-17 15:52:00.525  1035  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-17 15:52:00.546  7218  7589 I bt_vendor: bluetooth satus is on
08-17 15:52:00.546  7218  7589 D bt_hci_bdroid: preload
,08-17 15:52:00.547  7218  7647 D bt_userial_mct: userial_open(port:0)
08-17 15:52:00.547  7218  7647 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-17 15:52:00.551  7218  7647 I bt_vendor: Done intiailizing UART
08-17 15:52:00.551  7218  7647 I bt_vendor: Done intiailizing UART
08-17 15:52:00.552  7218  7647 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 15:52:00.552  7218  7647 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 15:52:00.552  7218  7645 I bt-btu  : btu_task received preload complete event
08-17 15:52:00.552  7218  7674 D bt_userial_mct: Entering userial_read_thread()
08-17 15:52:00.553  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 15:52:00.553  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 15:52:00.556  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 15:52:00.561  7218  7645 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 15:52:00.561  7218  7645 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 15:52:00.561  7218  7645 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 15:52:00.561  7218  7645 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:52:00.561  7218  7645 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 15:52:00.561  7218  7645 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:52:00.562  7218  7645 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:52:00.629  7218  7645 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 15:52:00.629  7218  7645 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
08-17 15:52:00.629  7218  7645 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,08-17 15:52:00.648  7218  7593 E bt-btif : Calling BTA_HhEnable
,08-17 15:52:00.648  7218  7593 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 15:52:00.648  7218  7593 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:52:00.649  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 15:52:00.649  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 15:52:00.649  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 15:52:00.649  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 15:52:00.649  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-17 15:52:00.651  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:52:00.651  7218  7593 D BluetoothAdapterProperties: Name is: G3
,08-17 15:52:00.654  7218  7593 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:52:00.654  7218  7593 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:52:00.654  7218  7593 D bt_hci_bdroid: postload
08-17 15:52:00.654  7218  7647 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:00.655  7218  7647 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:00.656  7218  7645 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 15:52:00.656  7218  7647 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:00.656  7218  7647 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:00.656  7218  7593 D bte_conf: Device ID record 1 : primary
08-17 15:52:00.656  7218  7593 D bte_conf:   vendorId            = 00c4
08-17 15:52:00.656  7218  7593 D bte_conf:   vendorIdSource      = 0001
08-17 15:52:00.656  7218  7593 D bte_conf:   product             = 13a1
08-17 15:52:00.656  7218  7593 D bte_conf:   version             = 1000
08-17 15:52:00.656  7218  7593 D bte_conf:   clientExecutableURL = 
08-17 15:52:00.656  7218  7593 D bte_conf:   serviceDescription  = 
08-17 15:52:00.656  7218  7593 D bte_conf:   documentationURL    = 
08-17 15:52:00.657  7218  7593 D bte_conf: bte_load_did_conf no section named DID2.
08-17 15:52:00.658  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 15:52:00.659  7218  7589 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 15:52:00.660  7218  7589 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:52:00.660  7218  7589 D BluetoothAdapterProperties: State =  11
08-17 15:52:00.660  7218  7589 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 15:52:00.660  7218  7589 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 15:52:00.660  7218  7589 D BluetoothAdapterProperties: Setting state to 12
08-17 15:52:00.660  7218  7589 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 15:52:00.661  1035  1117 D BluetoothManagerService: Message: 60
,08-17 15:52:00.661  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 15:52:00.661  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-17 15:52:00.661  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:52:00.663  7218  7589 I BluetoothAdapterState: Entering On State
08-17 15:52:00.650  7676  7676 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:00.666  7218  7593 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 15:52:00.650  7676  7676 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:52:00.671  7218  7593 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:52:00.674  7218  7645 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:00.675  7218  7645 W bt-smp  : Plain text(LSB ~ MSB) = 54 be 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:00.675  7218  7645 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 a3 96 c7 ab 6b 2d dc a0 2a 20 da 76 86 17 f4 
08-17 15:52:00.675  7218  7645 W bt-btm  : Stopping oneshot timer
08-17 15:52:00.681  7218  7647 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:00.681  7218  7647 D bt_hci_bdroid: Used up Tx Cmd credits
,08-17 15:52:00.685  7218  7674 E bt_mct  : hci lib postload completed
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:00.687  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:52:00.689  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:00.698  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:52:00.701  7218  7645 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:00.702  7218  7645 W bt-smp  : Plain text(LSB ~ MSB) = 4e df 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:00.702  7218  7645 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f b8 29 3d 3f 0d 1f 80 73 37 85 42 7b b9 14 68 
08-17 15:52:00.702  7218  7645 W bt-btm  : Stopping oneshot timer
08-17 15:52:00.704  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:00.708  7218  7589 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 15:52:00.708  7218  7589 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 15:52:00.709  7218  7589 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 15:52:00.710  7218  7589 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 15:52:00.710  1880  4534 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:52:00.713  7218  7589 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-17 15:52:00.715  1035  1035 D BluetoothA2dp: Proxy object connected
08-17 15:52:00.719  1880  1880 D BluetoothHeadset: Proxy object connected
08-17 15:52:00.720  1880  4535 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:00.721  7218  7645 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:00.721  7218  7645 W bt-smp  : Plain text(LSB ~ MSB) = 2d e4 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:00.721  7218  7645 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 9d b9 26 6d 7c b5 89 6a c9 33 6c 7e 2f 96 b1 
08-17 15:52:00.721  7218  7645 W bt-btm  : Stopping oneshot timer
08-17 15:52:00.726  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:52:00.729  1035  1035 D BluetoothHeadset: Proxy object connected
08-17 15:52:00.730  7218  7593 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:52:00.730  7218  7593 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-17 15:52:00.732  7072  7479 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:52:00.732  1880  1880 D BluetoothHeadset: Proxy object connected
08-17 15:52:00.735  7218  7645 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:00.735  7218  7645 W bt-smp  : Plain text(LSB ~ MSB) = 4d b5 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:00.735  7218  7645 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 02 2c 2e b8 1b 71 9b 75 c9 4a 12 ed eb 01 a1 
08-17 15:52:00.735  7218  7645 W bt-btm  : Stopping oneshot timer
08-17 15:52:00.744  7072  7098 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:52:00.744  7072  7098 D BluetoothPan: onBluetoothStateChange call bindService
08-17 15:52:00.747  7072  7072 D BluetoothInputDevice: Proxy object connected
08-17 15:52:00.748  7686  7686 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 15:52:00.748  7072  7072 D HidProfile: Bluetooth service connected
,08-17 15:52:00.751  7072  7105 D BluetoothMap: onBluetoothStateChange: up=true
08-17 15:52:00.752  7072  7072 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:52:00.752  7072  7072 D PanProfile: Bluetooth service connected
08-17 15:52:00.753  1880  2569 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:00.755  7218  7645 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:00.755  7218  7645 W bt-smp  : Plain text(LSB ~ MSB) = e0 71 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:00.755  7218  7645 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 8d 39 96 0f 55 72 bf ad af cc 7b 74 9f c1 c8 
08-17 15:52:00.755  7218  7645 W bt-btm  : Stopping oneshot timer
08-17 15:52:00.756  1880  1880 D BluetoothHeadset: Proxy object connected
08-17 15:52:00.756  7072  7072 D BluetoothMap: Proxy object connected
08-17 15:52:00.756  7072  7072 D MapProfile: Bluetooth service connected
08-17 15:52:00.756  7072  7072 D BluetoothMap: getConnectedDevices()
08-17 15:52:00.756  7072  7479 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:52:00.757  7218  7690 V BluetoothMapService: getConnectedDevices()
08-17 15:52:00.759  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 15:52:00.759  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 15:52:00.760  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-17 15:52:00.764  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 15:52:00.765  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.765  1969  2181 D LGBluetoothAPIService: Message: 1
08-17 15:52:00.765  1969  2181 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 15:52:00.769  6981  6981 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 15:52:00.770  1035  1117 D BluetoothManagerService: Message: 40
08-17 15:52:00.770  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 15:52:00.773  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:52:00.777  7218  7218 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.777  7218  7218 D BluetoothMapService: STATE_ON
08-17 15:52:00.778  7072  7072 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 15:52:00.778  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:00.778  1969  2181 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-17 15:52:00.780  1035  1117 D BluetoothManagerService: Message: 30
08-17 15:52:00.783  7072  7072 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-17 15:52:00.786  1035  1117 D BluetoothManagerService: Message: 30
08-17 15:52:00.792  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-17 15:52:00.795  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:00.795  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:52:00.795  7218  7218 V BluetoothPbapService: Pbap Service onCreate
08-17 15:52:00.795  7218  7218 V BluetoothPbapService: Starting PBAP service
08-17 15:52:00.796  7218  7218 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 15:52:00.796  7218  7218 V BluetoothMapService: Handler(): got msg=1
08-17 15:52:00.797  7218  7218 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 15:52:00.797  7072  7072 D BluetoothA2dp: Proxy object connected
08-17 15:52:00.798  7218  7218 V BluetoothPbapService: Pbap Service onBind
08-17 15:52:00.798  7072  7072 D A2dpProfile: Bluetooth service connected
08-17 15:52:00.799  7218  7218 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.799  7218  7218 V BluetoothPbapService: state: 12
08-17 15:52:00.801  7218  7218 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 15:52:00.801  7218  7218 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 15:52:00.802  7218  7218 V BluetoothPbapService: Handler(): got msg=1
08-17 15:52:00.802  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 15:52:00.802  1969  2181 D LGBluetoothAPIService: Message: 100
08-17 15:52:00.802  1969  2181 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 15:52:00.803  7218  7218 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 15:52:00.803  7072  7072 D BluetoothHeadset: Proxy object connected
08-17 15:52:00.803  7218  7218 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:52:00.803  7218  7218 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.803  7218  7218 V BluetoothPbapReceiver: ***********state = 12
08-17 15:52:00.804  7072  7072 D HeadsetProfile: Bluetooth service connected
08-17 15:52:00.804  7218  7696 V BluetoothPbapService: Pbap Service initSocket
08-17 15:52:00.804  7218  7695 D BluetoothMapMasInstance: MAS initSocket()
08-17 15:52:00.805  7218  7695 D BluetoothMapMasInstance:   masId = 00
08-17 15:52:00.805  7218  7695 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 15:52:00.805  7218  7695 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 15:52:00.805  7218  7695 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-17 15:52:00.808  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:52:00.808  2246  2246 D c       : Getting all permits...
08-17 15:52:00.808  2246  2246 D a       : Opening database...
08-17 15:52:00.809  1035  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:00.809  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:00.811  7218  7695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:00.812  7218  7696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:00.813  7218  7695 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 15:52:00.813  7218  7695 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 15:52:00.813  7218  7695 D BluetoothMapMasInstance: Accepting socket connection...
08-17 15:52:00.814  2246  2246 D a       : Opening database auth.proximity.permit_store...
08-17 15:52:00.815  7218  7593 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:52:00.815  7218  7593 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 15:52:00.816  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:00.818  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:52:00.819  7072  7072 D DockEventReceiver: finishStartingService: stopping service
08-17 15:52:00.820  7218  7696 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 15:52:00.820  7218  7696 V BluetoothPbapService: Succeed to create listening socket 
08-17 15:52:00.820  7218  7696 V BluetoothPbapService: Accepting socket connection...
08-17 15:52:00.821  2246  2246 D a       : Closing database...
08-17 15:52:00.821  7072  7072 D BluetoothPbap: Proxy object connected
08-17 15:52:00.822  7072  7072 D PbapServerProfile: Bluetooth service connected
08-17 15:52:00.833  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:52:00.835  7072  7072 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 15:52:00.837  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:52:00.841  7218  7218 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 15:52:00.842  7218  7218 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 15:52:00.848  7218  7218 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 15:52:00.868  7218  7218 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:52:00.868  7218  7218 V BtOppService: onCreate
,08-17 15:52:00.872  7218  7218 V BluetoothOppNotification: send message
08-17 15:52:00.876  7218  7218 V BtOppService: Starting RfcommListener
08-17 15:52:00.882  7218  7218 D BluetoothOppPreference: Dumping Names:  
08-17 15:52:00.882  7218  7218 D BluetoothOppPreference: {}
08-17 15:52:00.882  7218  7218 D BluetoothOppPreference: Dumping Channels:  
08-17 15:52:00.882  7218  7218 D BluetoothOppPreference: {}
08-17 15:52:00.884  7218  7218 V BtOppService: onStartCommand
,08-17 15:52:00.888  7218  7218 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.888  7218  7218 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:52:00.889  7218  7703 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:52:00.892  7218  7218 V BluetoothOppNotification: new notify threadi!
08-17 15:52:00.894  7218  7218 V BluetoothOppNotification: send delay message
08-17 15:52:00.896  7218  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:52:00.896  7218  7703 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:52:00.897  7218  7218 V BtOppService: start RfcommListener
08-17 15:52:00.899  7218  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37345b75 on behalf of 
,08-17 15:52:00.899  7218  7703 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31a122ac on behalf of 
08-17 15:52:00.900  7218  7704 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:52:00.901  7218  7700 V BtOppService: Deleted complete outbound shares, number =  0
08-17 15:52:00.902  7218  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:00.903  7218  7703 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:52:00.903  7218  7700 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 15:52:00.904  7218  7700 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 15:52:00.905  7218  7218 V BtOppService: RfcommListener started
08-17 15:52:00.906  7218  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26a6c70a on behalf of 
08-17 15:52:00.907  7218  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@163fb7b on behalf of 
08-17 15:52:00.907  7218  7705 V BtOppRfcommListener: Starting RFCOMM listener....
,08-17 15:52:00.907  1035  2087 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:00.908  7218  7704 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:52:00.909  7218  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:00.911  7218  7704 V BluetoothOppNotification: outbound notification was removed.
08-17 15:52:00.911  7218  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:00.914  7218  7705 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-17 15:52:00.914  7218  7705 V BtOppRfcommListener: Started RFCOMM listener....
08-17 15:52:00.914  7218  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a53bd98 on behalf of 
08-17 15:52:00.914  7218  7705 I BtOppRfcommListener: Accept thread started.
08-17 15:52:00.914  7218  7705 V BtOppRfcommListener: Accepting connection...
08-17 15:52:00.916  7218  7704 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 15:52:00.919  7218  7704 V BluetoothOppNotification: inbound notification was removed.
08-17 15:52:00.919  7218  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:52:00.921  7218  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24fc39f1 on behalf of 
08-17 15:52:00.929  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:00.929  7218  7218 V BluetoothFtpService: Ftp Service onCreate
08-17 15:52:00.929  7218  7218 I BluetoothFtpService: Ftp Service onCreate
08-17 15:52:00.930  7218  7218 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:52:00.930  7218  7218 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.930  7218  7218 V BluetoothFtpService: Starting Listening on sockets
08-17 15:52:00.930  7218  7218 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:52:00.930  7218  7218 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-17 15:52:00.931  7218  7218 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:52:00.931  7218  7218 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.931  7218  7218 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 15:52:00.931  7218  7218 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:52:00.934  7218  7218 V BtOppService: ContentObserver received notification
08-17 15:52:00.934  7218  7218 V BtOppService: ContentObserver received notification
08-17 15:52:00.934  7218  7218 V BluetoothFtpService: Handler(): got msg=1
08-17 15:52:00.935  7218  7706 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:52:00.935  7218  7218 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 15:52:00.935  7218  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:52:00.935  7218  7218 V BluetoothFtpService: Ftp Service initSocket
08-17 15:52:00.937  7218  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6acd457 on behalf of 
08-17 15:52:00.937  7218  7706 V BluetoothOppNotification: update too frequent, put in queue
08-17 15:52:00.938  7218  7706 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:52:00.938  1035  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:00.939  7218  7218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:52:00.942  7218  7218 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-17 15:52:00.942  7218  7218 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 15:52:00.943  7218  7707 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 15:52:00.958  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:00.958  7218  7218 V BluetoothSapService: Sap Service onCreate
08-17 15:52:00.960  7218  7218 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:00.960  7218  7218 V BluetoothSapService: state: 12
08-17 15:52:00.950  7708  7708 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:00.950  7708  7708 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:00.961  7218  7218 V BluetoothSapService: Starting SAP server process
08-17 15:52:00.963  7218  7218 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-17 15:52:00.965  7218  7710 V BluetoothSapService: Sap Service initRfcommSocket
08-17 15:52:00.966  1035  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:00.967  7218  7710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:00.969  7218  7710 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 15:52:00.969  7218  7710 V BluetoothSapService: Succeed to create listening socket 
08-17 15:52:00.969  7218  7710 V BluetoothSapService: Accepting socket connection...
08-17 15:52:00.973  7708  7708 V BT_SAP  : Event pipe created
08-17 15:52:00.973  7708  7708 V BT_SAP  : create_server_socket qcom.sap.server
08-17 15:52:00.973  7708  7708 V BT_SAP  : created socket fd 6
,08-17 15:52:01.063  7432  7453 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-17 15:52:01.493  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:01.493  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:52:01.511  1035  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-17 15:52:01.512  1035  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-17 15:52:01.896  7218  7218 V BluetoothOppNotification: new notify threadi!
,08-17 15:52:01.897  7218  7218 V BluetoothOppNotification: send delay message
,08-17 15:52:01.913  7218  7722 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 15:52:01.916  7218  7722 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21405ef3 on behalf of 
08-17 15:52:01.917  7218  7722 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:52:01.924  7218  7722 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-17 15:52:01.931  7218  7722 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2848a7b0 on behalf of 
08-17 15:52:01.932  7218  7722 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:52:01.936  7218  7722 V BluetoothOppNotification: outbound notification was removed.
08-17 15:52:01.936  7218  7722 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:01.937  7218  7722 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c273629 on behalf of 
08-17 15:52:01.938  7218  7722 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-17 15:52:01.941  7218  7722 V BluetoothOppNotification: inbound notification was removed.
08-17 15:52:01.941  7218  7722 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:52:01.943  7218  7722 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@be8bdae on behalf of 
08-17 15:52:01.966  1035  2332 I ActivityManager: Killing 7282:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-17 15:52:01.999  1035  1968 W libprocessgroup: failed to open /acct/uid_10011/pid_7282/cgroup.procs: No such file or directory
,08-17 15:52:02.526  1035  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:02.526  1035  1950 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@35aae3ef mBinding = false
,08-17 15:52:02.567  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:52:02.568  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:52:02.568  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:52:02.568  1035  1117 D BluetoothManagerService: Message: 2
08-17 15:52:02.569  1035  1117 D BluetoothManagerService: Sending off request.
08-17 15:52:02.570  7218  7694 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 15:52:02.571  7218  7589 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 15:52:02.571  7218  7589 D BluetoothAdapterProperties: Setting state to 13
08-17 15:52:02.571  7218  7589 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:52:02.572  7218  7589 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 15:52:02.572  7218  7589 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 15:52:02.574  7218  7593 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:52:02.581  7218  7589 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 15:52:02.583  7218  7589 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:52:02.586  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 15:52:02.586  7218  7645 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 15:52:02.587  7218  7695 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 15:52:02.590  7218  7696 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 15:52:02.593  7218  7705 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:52:02.594  7218  7707 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:52:02.594  7218  7710 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:52:02.599  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 15:52:02.600  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 15:52:02.600  7218  7645 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:52:02.604  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:02.604  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:52:02.610  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:52:02.610  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:02.613  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:02.613  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:52:02.615  6981  6981 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:52:02.615  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:02.619  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:52:02.619  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 15:52:02.619  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-17 15:52:02.625  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.626  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:52:02.632  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:02.635  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:52:02.638  7218  7218 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.638  7218  7218 D BluetoothMapService: STATE_TURNING_OFF
08-17 15:52:02.638  7218  7218 V BluetoothMapService: Handler(): got msg=4
08-17 15:52:02.638  7218  7218 D BluetoothMapService: MAP Service closeService in
08-17 15:52:02.638  7218  7218 D BluetoothMapMasInstance: MAP Service shutdown
08-17 15:52:02.639  7218  7218 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:52:02.639  7218  7218 V BluetoothMapService: MAP Service closeService out
08-17 15:52:02.640  7218  7218 V BtOppService: Receiver DISABLED_ACTION 
08-17 15:52:02.640  7218  7218 I BtOppRfcommListener: stopping Accept Thread
08-17 15:52:02.640  7218  7218 V BtOppRfcommListener: close mBtServerSocket
08-17 15:52:02.641  7218  7218 V BtOppRfcommListener: waiting for thread to terminate
08-17 15:52:02.641  7218  7705 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:52:02.641  7218  7218 V BtOppRfcommListener: done waiting for thread to terminate
08-17 15:52:02.644  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-17 15:52:02.654  7218  7218 V BtOppService: onDestroy
,08-17 15:52:02.666  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 15:52:02.672  7218  7218 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 15:52:02.678  7218  7218 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:52:02.678  7218  7218 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.678  7218  7218 V BluetoothPbapReceiver: ***********state = 13
08-17 15:52:02.693  7218  7218 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-17 15:52:02.698  7218  7218 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.699  7218  7218 V BluetoothPbapService: state: 13
08-17 15:52:02.699  7218  7218 V BluetoothPbapService: Pbap Service closeService in
08-17 15:52:02.701  7218  7218 V BluetoothPbapService: successfully stopped pbap service
08-17 15:52:02.701  7218  7218 V BluetoothPbapService: Pbap Service closeService out
08-17 15:52:02.702  7218  7218 V BluetoothPbapService: Pbap Service onDestroy
08-17 15:52:02.703  7218  7218 V BluetoothPbapService: Pbap Service closeService in
08-17 15:52:02.703  7218  7218 V BluetoothPbapService: Pbap Service closeService out
08-17 15:52:02.703  7218  7218 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 15:52:02.706  7072  7072 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:52:02.706  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:52:02.708  7072  7072 D BluetoothPbap: Proxy object disconnected
08-17 15:52:02.708  7072  7072 D PbapServerProfile: Bluetooth service disconnected
,08-17 15:52:02.723  7072  7072 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 15:52:02.730  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:52:02.730  7072  7072 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 15:52:02.738  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:52:02.743  7218  7218 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 15:52:02.743  7218  7218 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-17 15:52:02.744  7218  7218 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 15:52:02.749  7218  7218 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.749  7218  7218 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:52:02.751  7218  7218 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:52:02.751  7218  7218 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.752  7218  7218 V BluetoothFtpService: Ftp Service closeService
08-17 15:52:02.752  7218  7218 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 15:52:02.753  7218  7218 V BluetoothFtpService: successfully stopped ftp service
,08-17 15:52:02.754  7218  7218 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:52:02.754  7218  7218 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:52:02.754  7218  7218 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:52:02.754  7218  7218 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.754  7218  7218 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 15:52:02.755  7218  7218 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:52:02.756  7218  7218 V BluetoothFtpService: Ftp Service onDestroy
08-17 15:52:02.756  7218  7218 V BluetoothFtpService: Ftp Service closeService
,08-17 15:52:02.766  7218  7218 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:02.766  7218  7218 V BluetoothSapService: state: 13
08-17 15:52:02.766  7218  7218 V BluetoothSapService: Stopping SAP server process
,08-17 15:52:02.768  7218  7218 V BluetoothSapService: Sap Service closeSapService in
,08-17 15:52:02.768  7218  7218 V BluetoothSapService: Close listen Socket : 
08-17 15:52:02.768  7218  7218 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:52:02.769  7218  7218 V BluetoothSapService: Close sapd  Socket : 
08-17 15:52:02.772  7218  7218 V BluetoothSapService: Sap Service closeSapService out
08-17 15:52:02.772  7218  7218 V BluetoothSapService: Sap Service onDestroy
08-17 15:52:02.772  7218  7218 V BluetoothSapService: Sap Service closeSapService in
,08-17 15:52:02.772  7218  7218 V BluetoothSapService: Close listen Socket : 
08-17 15:52:02.772  7218  7218 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:52:02.773  7218  7218 V BluetoothSapService: Close sapd  Socket : 
08-17 15:52:02.773  7218  7218 V BluetoothSapService: Sap Service closeSapService out
08-17 15:52:03.569  7218  7593 D bt_hci_bdroid: cleanup
,08-17 15:52:03.583  7218  7647 I bt_lpm  : LPM is already off!!!
08-17 15:52:03.583  7218  7674 I bt_userial_mct: exiting userial_read_thread
08-17 15:52:03.583  7218  7674 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 15:52:03.584  7218  7645 W bt-btif : ag scb idx 1 not allocated
08-17 15:52:03.584  7218  7645 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:52:03.584  7218  7645 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:52:03.584  7218  7645 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:52:03.585  7218  7593 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 15:52:03.585  7218  7647 I bt_vendor: hw_epilog_process
08-17 15:52:03.586  7218  7593 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 15:52:03.586  7218  7593 D bt_userial_mct: userial_close
08-17 15:52:03.586  7218  7593 E bt_userial_mct: pthread_join() FAILED result:3
08-17 15:52:03.586  7218  7593 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 15:52:03.591  7218  7593 D bt_hci_bdroid: set_power 0
08-17 15:52:03.591  7218  7593 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 15:52:03.591  7218  7593 I bt_vendor: bluetooth satus is on
08-17 15:52:03.591  7218  7593 I bt_vendor: bt-vendor : resetting BT status
08-17 15:52:03.591  7218  7593 I bt_vendor: Starting hciattach daemon
08-17 15:52:03.591  7218  7593 I bt_vendor: try to set false
,08-17 15:52:03.599  7218  7593 I bt_vendor: Starting hciattach daemon
08-17 15:52:03.599  7218  7593 I bt_vendor: try to set false
08-17 15:52:03.600  7218  7593 I bt_vendor: cleanup
08-17 15:52:03.601  7218  7645 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 15:52:03.601  7218  7593 I GKI_LINUX: GKI_exit_task 0 done
08-17 15:52:03.601  7218  7593 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 15:52:03.603  7218  7589 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 15:52:03.606  7218  7218 D HeadsetService: Received stop request...Stopping profile...
,08-17 15:52:03.609  7218  7625 D HeadsetStateMachine: Exit Disconnected: -1
08-17 15:52:03.610  7218  7218 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:52:03.611  7218  7218 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:52:03.611  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.614  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-17 15:52:03.614  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 15:52:03.615  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-17 15:52:03.615  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-17 15:52:03.615  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-17 15:52:03.617  7218  7218 D HeadsetStateMachine: Unbinding service...
,08-17 15:52:03.620  7218  7218 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:52:03.620  7218  7218 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:52:03.620  7218  7218 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:52:03.622  7218  7218 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:52:03.622  7218  7218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:52:03.622  7218  7218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:52:03.622  7218  7218 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:52:03.628  7218  7589 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 15:52:03.631  7218  7218 D A2dpService: Received stop request...Stopping profile...
,08-17 15:52:03.633  7218  7635 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:52:03.634  7218  7218 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 15:52:03.636  7218  7218 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 15:52:03.636  7218  7218 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:52:03.636  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.637  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-17 15:52:03.637  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 15:52:03.640  7218  7218 D HidService: Received stop request...Stopping profile...
08-17 15:52:03.640  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.642  7218  7218 D HealthService: Received stop request...Stopping profile...
08-17 15:52:03.642  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.646  7218  7218 D PanService: Received stop request...Stopping profile...
,08-17 15:52:03.648  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.650  7218  7218 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:52:03.651  7218  7218 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:52:03.651  7218  7218 D BtGatt.GattService: stop()
08-17 15:52:03.651  7218  7218 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:52:03.652  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.653  7218  7218 D BluetoothMapService: Received stop request...Stopping profile...
08-17 15:52:03.653  7218  7218 D BluetoothMapService: stop()
08-17 15:52:03.654  7218  7218 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 15:52:03.654  7218  7218 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 15:52:03.657  7218  7218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:03.658  7218  7218 I BluetoothA2dpServiceJni: cleanupNative
,08-17 15:52:03.660  7218  7636 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 15:52:03.660  7218  7218 I GKI_LINUX: GKI_exit_task 2 done
08-17 15:52:03.660  7218  7218 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 15:52:03.662  7218  7218 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:52:03.662  7218  7218 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:52:03.662  7218  7218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:52:03.662  7218  7218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:52:03.662  7218  7218 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:52:03.663  7218  7218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:52:03.663  7218  7218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:52:03.668  7218  7218 V BluetoothMapService: Handler(): got msg=4
08-17 15:52:03.668  7218  7218 D BluetoothMapService: MAP Service closeService in
08-17 15:52:03.668  7218  7218 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:52:03.668  7218  7218 V BluetoothMapService: MAP Service closeService out
08-17 15:52:03.675  7218  7589 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 15:52:03.675  7218  7589 D BluetoothAdapterProperties: Setting state to 10
08-17 15:52:03.675  7218  7589 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-17 15:52:03.678  7218  7218 D BluetoothMapService: cleanup()
08-17 15:52:03.678  7218  7218 D BluetoothMapService: MAP Service closeService in
08-17 15:52:03.678  7218  7218 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:52:03.678  7218  7218 V BluetoothMapService: MAP Service closeService out
08-17 15:52:03.680  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:52:03.680  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 15:52:03.680  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-17 15:52:03.681  7218  7589 I BluetoothAdapterState: Entering OffState
08-17 15:52:03.681  7072  7098 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:52:03.691  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:52:03.693  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:52:03.694  1880  4534 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:52:03.695  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:52:03.695  7072  7479 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:52:03.696  7072  7105 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:52:03.696  7072  7098 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:52:03.697  7072  7479 D BluetoothMap: onBluetoothStateChange: up=false
08-17 15:52:03.697  1880  4541 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:52:03.698  7072  7105 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 15:52:03.699  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 15:52:03.699  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 15:52:03.701  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 15:52:03.701  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 15:52:03.701  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@35aae3ef mBinding = false
08-17 15:52:03.701  1035  1117 D BluetoothManagerService: Sending unbind request.
08-17 15:52:03.702  7072  7072 D BluetoothHeadset: Proxy object disconnected
08-17 15:52:03.702  7072  7072 D HeadsetProfile: Bluetooth service disconnected
08-17 15:52:03.707  7218  7593 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 15:52:03.709  7218  7218 I GKI_LINUX: GKI_exit_task 1 done
,08-17 15:52:03.709  7218  7218 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 15:52:03.710  7218  7218 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:52:03.710  7218  7218 I art     : --- WEIRD: removing null entry 248
08-17 15:52:03.710  7218  7218 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-17 15:52:03.710  7218  7218 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 15:52:03.711  7218  7218 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 15:52:03.712  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-17 15:52:03.714  7218  7218 I art     : System.exit called, status: 0
08-17 15:52:03.715  7218  7218 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 15:52:03.728  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:52:03.734  1969  2181 D LGBluetoothAPIService: Message: 2
,08-17 15:52:03.734  1969  2181 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@29b22272 mBinding = false
08-17 15:52:03.735  1969  2181 D LGBluetoothAPIService: Sending unbind request.
08-17 15:52:03.738  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:52:03.742  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:03.742  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:03.745  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 15:52:03.745  7072  7072 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-17 15:52:03.754  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 15:52:03.762   312  4546 V AudioFlinger: 7218 died, releasing its sessions
08-17 15:52:03.762   312  4546 V AudioFlinger:  pid 1880 @ 0
08-17 15:52:03.762   312  4546 V AudioFlinger:  pid 3243 @ 1
08-17 15:52:03.762   312  4546 V AudioFlinger:  pid 3243 @ 2
,08-17 15:52:03.774  1605  1605 D BluetoothAdapter: 196188828: getState() :  mService = null. Returning STATE_OFF
08-17 15:52:03.774  1605  1605 D BluetoothAdapter: 196188828: getState() :  mService = null. Returning STATE_OFF
08-17 15:52:03.822  1035  2114 I ActivityManager: Process com.android.bluetooth (pid 7218) has died
,08-17 15:52:03.822  1035  2114 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-17 15:52:03.896  1035  1051 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7772 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-17 15:52:03.899  7072  7072 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:52:03.901  1035  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=722457020, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-17 15:52:03.902  7072  7072 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 15:52:03.903  1035  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23edd3da type 2 when 202581 com.google.android.gms} when 202581
08-17 15:52:03.914   308  7783 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 15:52:03.915  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-17 15:52:03.922   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 23.553ms
08-17 15:52:03.942   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.364ms
,08-17 15:52:03.960   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.816ms
,08-17 15:52:03.965  7772  7772 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 15:52:03.965  7772  7772 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:52:03.966  7772  7772 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 15:52:03.966  7772  7772 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 15:52:03.982  7772  7772 D BluetoothAdapterApp: Loading JNI Library
,08-17 15:52:04.014  7772  7772 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@384e9bbb Instance Count = 1
,08-17 15:52:04.019  7772  7772 D BluetoothAdapterApp: onCreate
,08-17 15:52:04.037  7772  7772 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 15:52:04.038  7772  7772 D ProfileConfigQcom: Adding HeadsetService
08-17 15:52:04.038  7772  7772 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 15:52:04.038  7772  7772 D ProfileConfigQcom: Adding A2dpService
08-17 15:52:04.038  7772  7772 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 15:52:04.038  7772  7772 D ProfileConfigQcom: Adding HidService
08-17 15:52:04.038  7772  7772 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 15:52:04.039  7772  7772 D ProfileConfigQcom: Adding HealthService
08-17 15:52:04.039  7772  7772 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 15:52:04.039  7772  7772 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 15:52:04.039  7772  7772 D ProfileConfigQcom: Adding PanService
08-17 15:52:04.040  7772  7772 D ProfileConfigQcom: [BTUI] GattService is supported
,08-17 15:52:04.040  7772  7772 D ProfileConfigQcom: Adding GattService
,08-17 15:52:04.040  7772  7772 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-17 15:52:04.040  7772  7772 D ProfileConfigQcom: Adding BluetoothMapService
08-17 15:52:04.041  7772  7772 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 15:52:04.041  7772  7772 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:52:04.042  7772  7772 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:04.042  7772  7772 V BluetoothPbapReceiver: ***********state = 10
08-17 15:52:04.044  7772  7772 V LGMDMManagerInternal: Create singleton instance
08-17 15:52:04.107  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:52:04.123  7072  7072 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-17 15:52:04.127  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:52:04.130  7072  7072 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 15:52:04.130  7072  7072 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-17 15:52:04.132  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:52:04.136  7772  7772 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 15:52:04.139  7772  7772 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:04.141  7772  7772 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:52:04.141  7772  7772 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:52:04.141  7772  7772 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:52:04.142  7772  7772 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:52:04.142  7772  7772 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 15:52:04.146  7167  7167 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-17 15:52:04.148  1035  2114 I ActivityManager: Killing 7315:com.lge.email/u0a23 (adj 15): empty #17
08-17 15:52:04.184  1035  1578 W libprocessgroup: failed to open /acct/uid_10023/pid_7315/cgroup.procs: No such file or directory
,08-17 15:52:04.224  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 15:52:04.252  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=722457020 [*alarm*], flags=0x0
,08-17 15:52:05.660  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:52:05.661  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:52:08.677  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:52:08.677  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17e13d95 added. We now have 6 listener(s)
08-17 15:52:08.677  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:52:08.690  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:08.690  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e8ceaa added. We now have 7 listener(s)
08-17 15:52:08.694  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:08.694  6981  7058 I System.out: IsBluetoothEnabled
,08-17 15:52:08.697  1035  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:08.697  1035  1986 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-17 15:52:08.698  1035  1117 D BluetoothManagerService: Message: 2
08-17 15:52:08.701  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:08.702  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:08.702  1035  2030 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 15:52:08.721  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:52:08.721  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:52:08.722  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:52:08.723  1035  1117 D BluetoothManagerService: Message: 1
08-17 15:52:08.723  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 15:52:08.751  1035  1117 D BluetoothManagerService: Message: 20
08-17 15:52:08.751  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b0561e7:true
,08-17 15:52:08.755  7772  7772 D BluetoothAdapterState: make
08-17 15:52:08.760  7772  7772 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 15:52:08.760  7772  7772 I bluedroid-qcom: init
08-17 15:52:08.761  7772  7805 I BluetoothAdapterState: Entering OffState
08-17 15:52:08.762  7772  7772 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 15:52:08.762  7772  7772 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:52:08.762  7772  7772 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:52:08.762  7772  7772 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 15:52:08.762  7772  7772 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 15:52:08.764  7772  7772 I bluedroid-qcom: get_profile_interface socket
08-17 15:52:08.764  7772  7772 I bluedroid-qcom: get_profile_interface map_client
,08-17 15:52:08.770  7772  7809 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 15:52:08.760  7808  7808 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:08.773  7772  7809 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:52:08.760  7808  7808 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:08.782  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:52:08.783  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-17 15:52:08.789  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 15:52:08.789  1035  1117 D BluetoothManagerService: Message: 40
08-17 15:52:08.789  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 15:52:08.790  7772  7790 I bluedroid-qcom: config_hci_snoop_log
08-17 15:52:08.791  7808  7808 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 15:52:08.791  7808  7808 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 15:52:08.791  7808  7808 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 15:52:08.791  7808  7808 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 15:52:08.794  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 15:52:08.794  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 15:52:08.796  7808  7808 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 15:52:08.796  7808  7808 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-17 15:52:08.801  7772  7809 D BluetoothAdapterProperties: Name is: G3
08-17 15:52:08.806  7772  7805 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 15:52:08.806  7772  7805 D BluetoothAdapterProperties: Setting state to 11
08-17 15:52:08.806  7772  7805 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 15:52:08.807  7772  7805 I LGBluetoothServiceJni: classInitNative: succeeds
08-17 15:52:08.814  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:52:08.814  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 15:52:08.814  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-17 15:52:08.820  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:08.820  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:52:08.823  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:08.827  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-17 15:52:08.839  7772  7805 D BluetoothBondStateMachine: make
,08-17 15:52:08.846  7772  7805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:08.846  7772  7805 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 15:52:08.846  7772  7805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:08.846  7772  7805 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 15:52:08.847  7772  7805 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 15:52:08.848  7772  7822 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 15:52:08.848  7772  7772 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:52:08.848  7772  7772 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:08.849  7772  7772 V BluetoothPbapReceiver: ***********state = 11
08-17 15:52:08.854  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:52:08.862  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:52:08.878  7772  7772 D HeadsetService: Received start request. Starting profile...
,08-17 15:52:08.879  7772  7772 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:52:08.879  7772  7772 D LGBluetoothHfpAdapter: Version 1.6
08-17 15:52:08.883  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:52:08.884  7772  7772 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:52:08.885  7772  7772 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:52:08.886  7772  7772 D HeadsetStateMachine: make
08-17 15:52:08.926  7772  7772 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:52:08.926  7772  7772 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:52:08.998  1035  1578 I art     : Explicit concurrent mark sweep GC freed 53632(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.139ms total 110.995ms
08-17 15:52:08.999  7772  7772 D HeadsetStateMachine: max_hf_connections = 1
08-17 15:52:08.999  7772  7772 I bluedroid-qcom: get_profile_interface handsfree
,08-17 15:52:09.000  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:52:09.001  7772  7772 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 15:52:09.002   312  1384 V AudioPolicyService: registerClient() client 0xb101fec0, uid 1002
08-17 15:52:09.002   312  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:52:09.002   312  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:52:09.002   312  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:52:09.003  7772  7772 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:52:09.006   312   312 V AudioFlinger: registerClient() client 0xb1433160, pid 7772
08-17 15:52:09.006  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:52:09.007  7772  7772 V ToneGenerator: Create Track: 0xb4928080
08-17 15:52:09.007   312  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:52:09.007  7772  7772 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 15:52:09.007  7772  7772 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 15:52:09.007   312  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:52:09.007   312  4545 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:52:09.007   312  4545 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:52:09.007   312  4545 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:52:09.007   312  4545 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:52:09.007  1605  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:52:09.007  1605  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:52:09.009  1035  2332 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:52:09.009  1035  2332 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:52:09.009  3243  3262 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:52:09.009  3243  3262 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:52:09.010  1880  4534 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:52:09.010  1880  4534 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:52:09.010  7772  7772 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:52:09.010  7772  7789 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:52:09.010  7772  7789 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 15:52:09.011   312   312 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 15:52:09.011   312  4546 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:52:09.011   312  4546 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 15:52:09.011   312  4546 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:52:09.011   312  4546 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:52:09.011  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:52:09.011   312  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:52:09.011   312  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:52:09.011  1035  1648 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:52:09.011  1035  1648 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:52:09.011  1605  3125 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:52:09.011  1605  3125 V AudioSystem: ioConfigChanged(), opening already existing output! 2
08-17 15:52:09.011  1880  4535 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:52:09.011  1880  4535 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:52:09.011  3243  3259 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:52:09.011  3243  3259 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:52:09.012  7772  7772 V AudioSystem: getLatency() output 2, latency 50
08-17 15:52:09.012  7772  7772 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 15:52:09.012  7772  7772 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:52:09.012  7772  7790 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:52:09.012  7772  7790 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 15:52:09.012  7772  7772 V AudioTrack: createTrack_l() output 2 afLatency 50
,08-17 15:52:09.012   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:52:09.012   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-17 15:52:09.012   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,08-17 15:52:09.012   312  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:52:09.012   312  1385 V AudioFlinger: createTrack() lSessionId: 23
08-17 15:52:09.013  7772  7772 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 15:52:09.013   312  1385 V AudioFlinger: acquiring 23 from 7772, for 7772
08-17 15:52:09.013   312  1385 V AudioFlinger:  added new entry for 23
08-17 15:52:09.013  7772  7772 V ToneGenerator: ToneGenerator INIT OK, time: 207833
08-17 15:52:09.014  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:09.014  7772  7827 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 15:52:09.014  7772  7827 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:52:09.014  7772  7827 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:52:09.015  7772  7827 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 15:52:09.015   312   312 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7772
08-17 15:52:09.015   312   312 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 15:52:09.015   312   312 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 15:52:09.015   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 15:52:09.015   312   312 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 15:52:09.015   312   312 V voice   : voice_set_parameters: exit with code(0)
08-17 15:52:09.015   312   312 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 15:52:09.015   312   312 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 15:52:09.015   312   312 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 15:52:09.015   312   312 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 15:52:09.015   312   312 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 15:52:09.015   312   312 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 15:52:09.015  7772  7827 V ToneGenerator: ToneGenerator destructor
08-17 15:52:09.015  7772  7827 V ToneGenerator: stopTone
08-17 15:52:09.015  7772  7827 V ToneGenerator: Delete Track: 0xb4928080
08-17 15:52:09.017  7772  7827 V AudioTrack: ~AudioTrack, releasing session id from 7772 on behalf of 7772
08-17 15:52:09.017   312  1385 V AudioFlinger: releasing 23 from 7772 for 7772
08-17 15:52:09.017   312  1385 V AudioFlinger:  decremented refcount to 0
08-17 15:52:09.017   312  1385 V AudioFlinger: purging stale effects
08-17 15:52:09.017   312  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 15:52:09.017   312  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 15:52:09.017   312  1273 V AudioPolicyService: AudioCommandThread() waking up
08-17 15:52:09.017   312  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 15:52:09.017   312  1273 V AudioPolicyManager: releaseOutput() 2
08-17 15:52:09.017   312  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 15:52:09.017   312  1385 V AudioFlinger: PlaybackThread::Track destructor
08-17 15:52:09.017   312  1385 V AudioFlinger: removeClient_l() pid 7772, calling pid 312
08-17 15:52:09.018  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:52:09.020  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:52:09.022  1035  1950 W Process : Unable to open /proc/7829/status
08-17 15:52:09.022  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:52:09.024  7772  7772 D A2dpService: Received start request. Starting profile...
08-17 15:52:09.025  7772  7772 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 15:52:09.026  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:52:09.026  7772  7772 V Avrcp   : make
08-17 15:52:09.027  7772  7772 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 15:52:09.027  7772  7772 I bluedroid-qcom: get_profile_interface avrcp
08-17 15:52:09.031  7772  7805 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:52:09.038  7772  7772 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 15:52:09.038  7772  7805 V LGMDMManager: Create singleton instance
08-17 15:52:09.039  7772  7772 E AudioManager: No RCC entry present to update
08-17 15:52:09.039  7772  7772 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 15:52:09.039  7772  7805 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 15:52:09.043  7772  7772 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-17 15:52:09.044  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 15:52:09.044  7772  7772 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 15:52:09.047  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 15:52:09.130  1035  2087 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:52:09.130  1035  2087 V SIM_STK : Menu title from STK is T-Mobile
,08-17 15:52:09.254  1035  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 15:52:09.264  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 15:52:09.269  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:52:09.270  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 15:52:09.271  7772  7772 I BluetoothA2dpServiceJni: classInitNative
08-17 15:52:09.271  7772  7772 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:52:09.271  7772  7772 D A2dpStateMachine: make
08-17 15:52:09.275  7772  7772 I bluedroid-qcom: get_profile_interface a2dp
,08-17 15:52:09.276  7772  7834 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 15:52:09.283  7772  7772 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:52:09.283  7772  7772 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 15:52:09.287  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:52:09.287  7772  7832 D A2dpStateMachine: Enter Disconnected: -2
08-17 15:52:09.288  7772  7772 D HeadsetStateMachine: Proxy object connected
08-17 15:52:09.291  7772  7772 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 15:52:09.292  7772  7772 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-17 15:52:09.294  7772  7772 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 15:52:09.296  7772  7772 D HidService: Received start request. Starting profile...
08-17 15:52:09.296  7772  7772 I bluedroid-qcom: get_profile_interface hidhost
08-17 15:52:09.297  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:09.297  7772  7772 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:52:09.299  7772  7772 D HealthService: Received start request. Starting profile...
08-17 15:52:09.303  7772  7772 I bluedroid-qcom: get_profile_interface health
08-17 15:52:09.303  7772  7772 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:52:09.303  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:52:09.307  7772  7827 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 15:52:09.308  7772  7772 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:52:09.308  7772  7827 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:52:09.309  7772  7772 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 15:52:09.311  7772  7827 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 15:52:09.311  7772  7772 D PanService: Received start request. Starting profile...
08-17 15:52:09.311  7772  7772 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:52:09.311  7772  7772 I bluedroid-qcom: get_profile_interface pan
08-17 15:52:09.320  7772  7772 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-17 15:52:09.320  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:09.321  7772  7772 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-17 15:52:09.327  7772  7772 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:52:09.328  7772  7772 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:52:09.328  7772  7772 D BtGatt.GattService: start()
08-17 15:52:09.328  7772  7772 I bluedroid-qcom: get_profile_interface gatt
08-17 15:52:09.329  7772  7772 D BtGatt.AdvertiseManager: advertise manager created
08-17 15:52:09.338  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:52:09.343  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:09.344  7772  7772 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 15:52:09.345  7772  7772 V BluetoothMapService: BluetoothMapBinder()
,08-17 15:52:09.346  7772  7772 D BluetoothMapService: Received start request. Starting profile...
08-17 15:52:09.346  7772  7772 D BluetoothMapService: start()
08-17 15:52:09.350  7772  7772 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 15:52:09.350  7772  7772 D BluetoothMapEmailAppObserver: createReceiver()
08-17 15:52:09.352  7772  7772 D BluetoothMapEmailAppObserver: initObservers()
08-17 15:52:09.352  7772  7772 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-17 15:52:09.361  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
,08-17 15:52:09.365  7772  7772 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:52:09.369  7772  7772 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:52:09.373  7772  7772 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:52:09.377  7772  7772 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:52:09.378  7772  7772 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 15:52:09.381  7772  7772 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-17 15:52:09.383  7772  7772 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:09.385  7772  7772 V BluetoothMapService: Handler(): got msg=1
08-17 15:52:09.386  7772  7805 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-17 15:52:09.386  7772  7805 I bluedroid-qcom: enable
08-17 15:52:09.386  7772  7805 I bt_hci_bdroid: init
08-17 15:52:09.386  7772  7772 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:52:09.387  7772  7772 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:52:09.387  7772  7772 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:52:09.387  7772  7772 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:52:09.387  7772  7772 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 15:52:09.388  7772  7805 I bt_vendor: bt-vendor : init
08-17 15:52:09.388  7772  7805 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 15:52:09.388  7772  7805 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 15:52:09.388  7772  7805 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 15:52:09.388  7772  7805 D bt_userial_mct: userial_init
,08-17 15:52:09.389  7772  7844 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting,
08-17 15:52:09.389  7772  7844 I bt-btu  : btu_task pending for preload complete event
08-17 15:52:09.390  7772  7805 D bt_hci_bdroid: set_power 1
08-17 15:52:09.390  7772  7805 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 15:52:09.390  7772  7805 I bt_vendor: Starting hciattach daemon
08-17 15:52:09.390  7772  7805 I bt_vendor: try to set true
08-17 15:52:09.380  7847  7847 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:09.380  7847  7847 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:52:09.420  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 15:52:09.531  7854  7854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 15:52:09.550  7855  7855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:52:09.587  7857  7857 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:52:09.601  7858  7858 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 15:52:09.626  7859  7859 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:52:09.639  7860  7860 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-17 15:52:09.663  7862  7862 I libmdmdetect: ESOC framework not supported
,08-17 15:52:09.664  7862  7862 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 15:52:09.673  7862  7862 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-17 15:52:09.673  7862  7862 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 15:52:09.673  7862  7862 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 15:52:09.673  7862  7862 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 15:52:09.673  7862  7862 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 15:52:09.673  7862  7862 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 15:52:09.673  7862  7862 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 15:52:09.713  7862  7863 E QC-QMI  : qmi_client [7862] 15: failed to locate client data
,08-17 15:52:09.719   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 15:52:09.719   475   475 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-17 15:52:09.745  7867  7867 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 15:52:09.760  7868  7868 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:52:09.793  7772  7805 I bt_vendor: bluetooth satus is on
,08-17 15:52:09.793  7772  7805 D bt_hci_bdroid: preload
08-17 15:52:09.794  7772  7846 D bt_userial_mct: userial_open(port:0)
08-17 15:52:09.794  7772  7846 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 15:52:09.797  7772  7846 I bt_vendor: Done intiailizing UART
08-17 15:52:09.800  7772  7846 I bt_vendor: Done intiailizing UART
08-17 15:52:09.800  7772  7846 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-17 15:52:09.801  7772  7846 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 15:52:09.801  7772  7844 I bt-btu  : btu_task received preload complete event
08-17 15:52:09.801  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 15:52:09.801  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 15:52:09.802  7772  7870 D bt_userial_mct: Entering userial_read_thread()
08-17 15:52:09.804  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:52:09.807  7772  7844 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 15:52:09.890  7772  7844 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 15:52:09.890  7772  7844 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
08-17 15:52:09.890  7772  7844 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,08-17 15:52:09.946  7772  7809 E bt-btif : Calling BTA_HhEnable
,08-17 15:52:09.953  7772  7809 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-17 15:52:09.954  7772  7809 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:52:09.957  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:52:09.957  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 15:52:09.958  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 15:52:09.958  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 15:52:09.958  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 15:52:09.959  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 15:52:09.959  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 15:52:09.960  7772  7809 D BluetoothAdapterProperties: Name is: G3
08-17 15:52:09.967  7772  7809 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:52:09.967  7772  7809 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:52:09.968  7772  7809 D bt_hci_bdroid: postload
,08-17 15:52:09.972  7772  7846 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:09.974  7772  7809 D bte_conf: Device ID record 1 : primary
08-17 15:52:09.974  7772  7809 D bte_conf:   vendorId            = 00c4
08-17 15:52:09.974  7772  7809 D bte_conf:   vendorIdSource      = 0001
08-17 15:52:09.974  7772  7809 D bte_conf:   product             = 13a1
08-17 15:52:09.974  7772  7809 D bte_conf:   version             = 1000
08-17 15:52:09.974  7772  7809 D bte_conf:   clientExecutableURL = 
08-17 15:52:09.974  7772  7809 D bte_conf:   serviceDescription  = 
08-17 15:52:09.974  7772  7809 D bte_conf:   documentationURL    = 
08-17 15:52:09.974  7772  7809 D bte_conf: bte_load_did_conf no section named DID2.
08-17 15:52:09.977  7772  7844 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 15:52:09.980  7772  7805 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 15:52:09.980  7772  7805 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:52:09.980  7772  7805 D BluetoothAdapterProperties: State =  11
08-17 15:52:09.980  7772  7805 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 15:52:09.981  7772  7805 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 15:52:09.981  7772  7805 D BluetoothAdapterProperties: Setting state to 12
08-17 15:52:09.981  7772  7805 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 15:52:09.982  7772  7809 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 15:52:09.982  7772  7809 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 15:52:09.970  7875  7875 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:09.980  7875  7875 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:10.005  7772  7846 D bt_hci_bdroid: Used up Tx Cmd credits
,08-17 15:52:10.009  7772  7809 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:52:10.009  7772  7809 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-17 15:52:10.010  7772  7846 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:10.014  1035  1117 D BluetoothManagerService: Message: 60
08-17 15:52:10.014  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 15:52:10.014  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:10.025  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:52:10.028  7772  7805 I BluetoothAdapterState: Entering On State
08-17 15:52:10.030  7772  7844 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:10.030  7772  7844 W bt-smp  : Plain text(LSB ~ MSB) = 4d 5d 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:10.030  7772  7844 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 bc 4f 87 46 67 c4 df ef 0b cf 38 89 26 be a2 
08-17 15:52:10.030  7772  7846 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:52:10.030  7772  7844 W bt-btm  : Stopping oneshot timer
08-17 15:52:10.032  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:10.033  7772  7870 E bt_mct  : hci lib postload completed
08-17 15:52:10.051  7772  7805 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 15:52:10.051  7772  7805 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 15:52:10.051  7772  7805 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-17 15:52:10.055  7772  7805 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 15:52:10.056  7072  7479 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:10.060  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:52:10.067  1035  1035 D BluetoothA2dp: Proxy object connected
,08-17 15:52:10.073  7772  7844 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:10.073  7772  7844 W bt-smp  : Plain text(LSB ~ MSB) = 93 64 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:10.073  7772  7844 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 2b 1c 5f 68 88 ce dc 98 d7 14 0b bb 98 d1 e4 
08-17 15:52:10.073  7772  7844 W bt-btm  : Stopping oneshot timer
08-17 15:52:10.077  1880  4541 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:10.082  7772  7805 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-17 15:52:10.094  1880  1880 D BluetoothHeadset: Proxy object connected
08-17 15:52:10.094  7772  7844 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:10.094  7772  7844 W bt-smp  : Plain text(LSB ~ MSB) = 97 6e 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:10.094  7772  7844 W bt-smp  : Encrypted text(LSB ~ MSB) = a3 8e c3 7d aa 27 68 26 87 93 bf f4 5b 68 b3 b1 
08-17 15:52:10.096  7772  7844 W bt-btm  : Stopping oneshot timer
,08-17 15:52:10.103  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:10.108  7772  7844 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:10.108  7772  7844 W bt-smp  : Plain text(LSB ~ MSB) = a1 76 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:10.108  7772  7844 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 10 2a 71 66 d6 7a ba bf 20 c8 f8 4c 00 42 72 
08-17 15:52:10.108  7772  7844 W bt-btm  : Stopping oneshot timer
,08-17 15:52:10.121  7072  7072 D BluetoothHeadset: Proxy object connected
08-17 15:52:10.121  7072  7072 D HeadsetProfile: Bluetooth service connected
,08-17 15:52:10.125  1880  1880 D BluetoothHeadset: Proxy object connected
08-17 15:52:10.125  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:10.126  1035  1035 D BluetoothHeadset: Proxy object connected
08-17 15:52:10.126  7772  7844 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:52:10.126  7772  7844 W bt-smp  : Plain text(LSB ~ MSB) = a2 b6 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:52:10.126  7772  7844 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b e7 3a d6 43 b6 f0 4f 35 b6 b5 f1 77 9c 34 40 
08-17 15:52:10.126  7772  7844 W bt-btm  : Stopping oneshot timer
08-17 15:52:10.126  7072  7479 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:52:10.127  7880  7880 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 15:52:10.128  7072  7098 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:52:10.130  7072  7072 D BluetoothA2dp: Proxy object connected
08-17 15:52:10.131  7072  7072 D A2dpProfile: Bluetooth service connected
08-17 15:52:10.132  7072  7479 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:52:10.132  7072  7479 D BluetoothPan: onBluetoothStateChange call bindService
08-17 15:52:10.132  7072  7072 D BluetoothInputDevice: Proxy object connected
08-17 15:52:10.132  7072  7072 D HidProfile: Bluetooth service connected
08-17 15:52:10.134  7072  7098 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:52:10.139  1880  4531 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:52:10.139  7072  7072 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:52:10.139  7072  7072 D PanProfile: Bluetooth service connected
08-17 15:52:10.141  7072  7479 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:52:10.141  1880  1880 D BluetoothHeadset: Proxy object connected
08-17 15:52:10.143  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 15:52:10.143  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 15:52:10.143  7072  7072 D BluetoothMap: Proxy object connected
08-17 15:52:10.143  7072  7072 D MapProfile: Bluetooth service connected
08-17 15:52:10.143  7072  7072 D BluetoothMap: getConnectedDevices()
08-17 15:52:10.144  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.144  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:52:10.146  7772  7789 V BluetoothMapService: getConnectedDevices()
,08-17 15:52:10.147  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:10.148  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 15:52:10.148  1035  1117 D BluetoothManagerService: Message: 40
08-17 15:52:10.148  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 15:52:10.151  1969  2181 D LGBluetoothAPIService: Message: 1
08-17 15:52:10.151  1969  2181 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 15:52:10.151  7772  7772 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.152  7772  7772 D BluetoothMapService: STATE_ON
08-17 15:52:10.153  7072  7072 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 15:52:10.154  1969  2181 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-17 15:52:10.154  7072  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:52:10.159  7072  7072 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:52:10.167  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:10.167  7772  7772 V BluetoothPbapService: Pbap Service onCreate
08-17 15:52:10.167  7772  7772 V BluetoothPbapService: Starting PBAP service
08-17 15:52:10.168  7772  7772 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-17 15:52:10.169  7772  7772 V BluetoothPbapService: Pbap Service onBind
08-17 15:52:10.169  7772  7772 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.169  7072  7072 D BluetoothPbap: Proxy object connected
08-17 15:52:10.169  7072  7072 D PbapServerProfile: Bluetooth service connected
08-17 15:52:10.169  7772  7772 V BluetoothPbapService: state: 12
08-17 15:52:10.170  7772  7772 V BluetoothMapService: Handler(): got msg=1
08-17 15:52:10.170  7772  7772 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 15:52:10.172  7772  7899 D BluetoothMapMasInstance: MAS initSocket()
08-17 15:52:10.173  7772  7899 D BluetoothMapMasInstance:   masId = 00
08-17 15:52:10.173  7772  7899 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 15:52:10.173  7772  7899 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 15:52:10.173  7772  7899 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 15:52:10.174  7772  7772 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 15:52:10.174  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:10.174  7772  7772 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 15:52:10.175  7772  7772 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:52:10.175  7772  7772 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.175  7772  7772 V BluetoothPbapReceiver: ***********state = 12
,08-17 15:52:10.176  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 15:52:10.176  1969  2181 D LGBluetoothAPIService: Message: 100
08-17 15:52:10.176  1969  2181 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 15:52:10.177  7772  7899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:10.179  7772  7899 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 15:52:10.179  7772  7899 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 15:52:10.179  7772  7809 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:52:10.179  7772  7899 D BluetoothMapMasInstance: Accepting socket connection...
08-17 15:52:10.179  7772  7809 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 15:52:10.181  7772  7772 V BluetoothPbapService: Handler(): got msg=1
08-17 15:52:10.183  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:52:10.183  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:10.183  7772  7772 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 15:52:10.183  2246  2246 D c       : Getting all permits...
08-17 15:52:10.184  2246  2246 D a       : Opening database...
08-17 15:52:10.184  7772  7900 V BluetoothPbapService: Pbap Service initSocket
08-17 15:52:10.185  1035  2102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:10.185  7772  7900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:10.186  7772  7900 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 15:52:10.186  7772  7900 V BluetoothPbapService: Succeed to create listening socket 
08-17 15:52:10.186  7772  7900 V BluetoothPbapService: Accepting socket connection...
08-17 15:52:10.188  2246  2246 D a       : Opening database auth.proximity.permit_store...
,08-17 15:52:10.188  2246  2246 D a       : Closing database...
08-17 15:52:10.198  7072  7072 D BluetoothPermissionRequest: onReceive
08-17 15:52:10.200  7072  7072 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 15:52:10.201  7072  7072 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:52:10.204  7772  7772 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 15:52:10.205  7772  7772 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 15:52:10.211  7772  7772 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 15:52:10.234  7772  7772 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:52:10.235  7772  7772 V BtOppService: onCreate
,08-17 15:52:10.239  7772  7772 V BluetoothOppNotification: send message
08-17 15:52:10.243  7772  7772 V BtOppService: Starting RfcommListener
08-17 15:52:10.249  7772  7772 D BluetoothOppPreference: Dumping Names:  
08-17 15:52:10.249  7772  7772 D BluetoothOppPreference: {}
08-17 15:52:10.249  7772  7772 D BluetoothOppPreference: Dumping Channels:  
08-17 15:52:10.249  7772  7772 D BluetoothOppPreference: {}
,08-17 15:52:10.251  7772  7772 V BtOppService: onStartCommand
08-17 15:52:10.255  7772  7907 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:52:10.257  7772  7907 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:52:10.257  7772  7772 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.258  7772  7772 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:52:10.259  7772  7904 V BtOppService: Deleted complete outbound shares, number =  0
08-17 15:52:10.259  7772  7907 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31a122ac on behalf of 
08-17 15:52:10.262  7772  7772 V BluetoothOppNotification: new notify threadi!
,08-17 15:52:10.263  7772  7772 V BluetoothOppNotification: send delay message
08-17 15:52:10.264  7772  7904 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 15:52:10.264  7772  7907 V BluetoothOppNotification: update too frequent, put in queue
08-17 15:52:10.264  7772  7904 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 15:52:10.266  7772  7904 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37345b75 on behalf of 
08-17 15:52:10.266  7772  7907 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:52:10.266  7772  7772 V BtOppService: start RfcommListener
08-17 15:52:10.272  7772  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:52:10.273  7772  7772 V BtOppService: RfcommListener started
08-17 15:52:10.273  7772  7772 V BtOppService: ContentObserver received notification
08-17 15:52:10.273  7772  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26a6c70a on behalf of 
,08-17 15:52:10.275  7772  7909 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 15:52:10.275  1035  2114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:10.276  7772  7908 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:52:10.277  7772  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:10.277  7772  7909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:10.278  7772  7909 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-17 15:52:10.278  7772  7909 V BtOppRfcommListener: Started RFCOMM listener....
08-17 15:52:10.279  7772  7909 I BtOppRfcommListener: Accept thread started.
08-17 15:52:10.279  7772  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@163fb7b on behalf of 
08-17 15:52:10.279  7772  7910 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:52:10.279  7772  7909 V BtOppRfcommListener: Accepting connection...
08-17 15:52:10.280  7772  7908 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:52:10.280  7772  7910 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:52:10.281  7772  7910 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a53bd98 on behalf of 
08-17 15:52:10.282  7772  7908 V BluetoothOppNotification: outbound notification was removed.
08-17 15:52:10.282  7772  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:10.283  7772  7910 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:52:10.284  7772  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24fc39f1 on behalf of 
08-17 15:52:10.284  7772  7908 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-17 15:52:10.286  7772  7908 V BluetoothOppNotification: inbound notification was removed.
08-17 15:52:10.286  7772  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:52:10.288  7772  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a7249d6 on behalf of 
08-17 15:52:10.291  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:10.291  7772  7772 V BluetoothFtpService: Ftp Service onCreate
08-17 15:52:10.291  7772  7772 I BluetoothFtpService: Ftp Service onCreate
08-17 15:52:10.292  7772  7772 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:52:10.292  7772  7772 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.292  7772  7772 V BluetoothFtpService: Starting Listening on sockets
08-17 15:52:10.292  7772  7772 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:52:10.292  7772  7772 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:52:10.292  7772  7772 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:52:10.292  7772  7772 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.292  7772  7772 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 15:52:10.293  7772  7772 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:52:10.295  7772  7772 V BtOppService: ContentObserver received notification
08-17 15:52:10.295  7772  7772 V BluetoothFtpService: Handler(): got msg=1
08-17 15:52:10.296  7772  7772 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 15:52:10.296  7772  7772 V BluetoothFtpService: Ftp Service initSocket
08-17 15:52:10.299  7772  7911 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-17 15:52:10.299  7772  7911 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:52:10.300  7772  7911 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12931b44 on behalf of 
08-17 15:52:10.301  1035  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:10.302  7772  7772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:10.302  7772  7911 V BluetoothOppNotification: update too frequent, put in queue
08-17 15:52:10.303  7772  7911 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:52:10.305  7772  7772 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-17 15:52:10.305  7772  7772 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 15:52:10.311  7772  7913 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-17 15:52:10.321  7772  7772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e56c733
08-17 15:52:10.321  7772  7772 V BluetoothSapService: Sap Service onCreate
,08-17 15:52:10.324  7772  7772 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:52:10.324  7772  7772 V BluetoothSapService: state: 12
08-17 15:52:10.324  7772  7772 V BluetoothSapService: Starting SAP server process
08-17 15:52:10.326  7772  7772 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 15:52:10.310  7914  7914 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:10.327  7772  7915 V BluetoothSapService: Sap Service initRfcommSocket
08-17 15:52:10.310  7914  7914 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:10.328  1035  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:10.329  7772  7915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:52:10.330  7772  7915 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 15:52:10.330  7772  7915 V BluetoothSapService: Succeed to create listening socket 
08-17 15:52:10.330  7772  7915 V BluetoothSapService: Accepting socket connection...
08-17 15:52:10.339  7914  7914 V BT_SAP  : Event pipe created
08-17 15:52:10.340  7914  7914 V BT_SAP  : create_server_socket qcom.sap.server
08-17 15:52:10.340  7914  7914 V BT_SAP  : created socket fd 6
,08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:10.764  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:52:10.777  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:10.783  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:10.783  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93fa9b added. We now have 8 listener(s)
08-17 15:52:10.783  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:52:10.788  1035  1939 D WifiServiceImplEx: setWifiEnabled: false pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:52:10.789  1035  1939 D WifiService: setWifiEnabled: false pid=6981, uid=10118
08-17 15:52:10.789  1035  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 15:52:10.795  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:52:10.799  1035  1986 D WifiServiceImplEx: setWifiEnabled: true pid=6981, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:52:10.799  1035  1986 D WifiService: setWifiEnabled: true pid=6981, uid=10118
08-17 15:52:10.799  1035  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:52:10.820  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:52:10.820  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:52:10.820  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 15:52:10.822  1035  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 15:52:10.822  1035  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 15:52:10.824  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 15:52:10.824  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:52:10.824  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 15:52:10.824  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:52:10.825  1035  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 15:52:10.825  1035  1538 E WifiHW  : unknown target_country: EU , set to default
08-17 15:52:10.825  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 15:52:10.825  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 15:52:10.825  1035  1538 I WifiUtil: gEnableBmps=1
08-17 15:52:11.265  7772  7772 V BluetoothOppNotification: new notify threadi!
08-17 15:52:11.265  7772  7772 V BluetoothOppNotification: send delay message
,08-17 15:52:11.270  7772  7934 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:52:11.271  7772  7934 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2848a7b0 on behalf of 
08-17 15:52:11.272  7772  7934 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:52:11.273  7772  7934 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:11.274  7772  7934 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c273629 on behalf of 
08-17 15:52:11.274  7772  7934 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:52:11.276  7772  7934 V BluetoothOppNotification: outbound notification was removed.
08-17 15:52:11.276  7772  7934 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:52:11.277  7772  7934 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@be8bdae on behalf of 
08-17 15:52:11.277  7772  7934 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-17 15:52:11.282  7772  7934 V BluetoothOppNotification: inbound notification was removed.
08-17 15:52:11.282  7772  7934 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:52:11.283  7772  7934 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e77f74f on behalf of 
08-17 15:52:11.419   308   893 D SoftapController: Softap fwReload - Ok
,08-17 15:52:11.431  1035  1538 E NetdConnector: NDC Command {66 softap fwreload wlan0 STA} took too long (601ms)
08-17 15:52:11.433   308   893 D CommandListener: Setting iface cfg
08-17 15:52:11.433   308   893 D CommandListener: Trying to bring down wlan0
,08-17 15:52:11.442  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:52:11.442  1035  1117 D Tethering: InitialState.processMessage what=4
,08-17 15:52:11.456   308   893 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:52:11.463  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 15:52:11.472  1035  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-17 15:52:11.470  7936  7936 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:11.490  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:52:11.490  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:52:11.490  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:52:11.480  7936  7936 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:11.501  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:52:11.511  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-17 15:52:11.537  1035  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 15:52:11.537  1035  1538 D WifiMonitor: connecting to supplicant
08-17 15:52:11.539  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:11.540  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-17 15:52:11.547  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:52:11.547  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:52:11.547  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:52:11.547  7072  7072 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:52:11.549  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:52:11.551  7072  7072 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:52:11.551  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:52:11.551  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:52:11.551  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:52:11.551  7072  7072 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:52:11.552  7072  7072 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:52:11.555  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:52:11.555  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:52:11.555  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:52:11.555  7072  7072 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:52:11.555  7936  7936 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 15:52:11.556  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:52:11.559  7072  7072 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:52:11.559  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:52:11.559  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:52:11.559  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:52:11.559  7072  7072 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:52:11.559  7072  7072 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:52:11.568  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:52:11.571  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:52:11.577  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:11.591  7936  7936 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 15:52:11.591  7936  7936 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 15:52:11.596  7189  7955 W FormManager: Network not available. Please check & try again.
08-17 15:52:11.598  7189  7956 V FormManager: Network unavailable.
08-17 15:52:11.600  7189  7956 V FormManager: Network unavailable.
08-17 15:52:11.714  7936  7936 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 15:52:11.733  7936  7936 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 15:52:11.741  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:52:11.742  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 15:52:11.742  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:52:11.743  1035  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:52:11.743  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:11.744  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:11.744  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:11.745  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:11.745  1035  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 15:52:11.745  1035  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 15:52:11.746  1035  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 15:52:11.746  1035  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 15:52:11.746  1035  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 15:52:11.747  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:52:11.747  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:52:11.747  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:52:11.748  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.748  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.749  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.749  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.749  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:52:11.752  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:11.752  1969  1969 D WfdService: Waiting for WifiP2p enabling
,08-17 15:52:11.754  1035  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-17 15:52:11.756  1035  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-17 15:52:11.756  1035  1538 D WifiConfigStore: Loading config and enabling all networks 
08-17 15:52:11.756  1035  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 15:52:11.758  1035  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-17 15:52:11.767  1035  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:11.768  6981  6981 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:52:11.771  6981  6981 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:52:11.771  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 15:52:11.772  1035  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 15:52:11.778  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:52:11.778  1035  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 15:52:11.779  1035  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 15:52:11.781  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 15:52:11.782  1035  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-17 15:52:11.782  1035  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 15:52:11.782  1035  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 15:52:11.782  1035  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-17 15:52:11.783  1035  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 15:52:11.783  1035  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 15:52:11.783  1035  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 15:52:11.783  1035  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 15:52:11.784  1035  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 15:52:11.784  1035  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 15:52:11.785  1035  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 15:52:11.785  1035  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 15:52:11.785  1035  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 15:52:11.785  1035  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 15:52:11.786  1035  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 15:52:11.786  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:52:11.786  1035  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 15:52:11.787  1035  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 15:52:11.787  1035  1538 D WifiNative-HAL: Setting external_sim to 1
08-17 15:52:11.787  1035  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 15:52:11.787  1969  1969 D WfdsService: Supplicant Connection state is changed : true
08-17 15:52:11.787  1969  2337 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 15:52:11.787  1969  2337 D WfdsService: Set the WFDS Monitor: true
08-17 15:52:11.787  1969  2337 D WfdsMonitor: WfdsMonitorThread create
08-17 15:52:11.788  1969  2337 D WfdsMonitor: WFDS Monitor is created and started
08-17 15:52:11.788  1969  2337 D WfdsService: WiFi: Supplicant connection re-established
08-17 15:52:11.788  1035  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 15:52:11.788  1035  1538 I WifiNative-HAL: startHal
08-17 15:52:11.788  1035  1538 D wifi    : setting scan oui 0xaf6b0f80
08-17 15:52:11.788  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:52:11.788  1035  1538 I WifiNative-HAL: startHal
08-17 15:52:11.788  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:11.788  1035  1538 D wifi    : setting scan oui 0xaf6b0f80
08-17 15:52:11.789  7189  7960 W FormManager: Network not available. Please check & try again.
08-17 15:52:11.789  1035  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 15:52:11.790  1969  7962 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 15:52:11.790  1035  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 15:52:11.790  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 15:52:11.790  1969  7962 E CtrlSupplicant: Succeed to open control connection
08-17 15:52:11.790  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 15:52:11.790  1969  7962 E CtrlSupplicant: Succeed to open monitor connection
08-17 15:52:11.791  1969  7962 D WfdsMonitor: Supplicant connection established
08-17 15:52:11.791  1969  2337 D WfdsService: Connected to the supplicant for wfds
08-17 15:52:11.791  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 15:52:11.791  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:52:11.791  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:52:11.792  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:52:11.792  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 15:52:11.792  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 15:52:11.793  7936  7936 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 15:52:11.793  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00,:00:00 SSID=]
08-17 15:52:11.793  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 15:52:11.794  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 15:52:11.794  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 15:52:11.794  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:52:11.794  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:52:11.794  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 15:52:11.794  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:52:11.794  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:52:11.795  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:52:11.795  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:52:11.795  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:52:11.795  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:52:11.795  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 15:52:11.795  7936  7936 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 15:52:11.796  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 15:52:11.796  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-17 15:52:11.796  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:52:11.796  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:52:11.797  1035  1538 E WifiNative: : [210,600,005 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 15:52:11.797  1035  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 15:52:11.797  1035  1538 D WifiNative-wlan0: RECONNECT: returned true
08-17 15:52:11.797  1035  1538 D WifiNative-wlan0: doString: [STATUS]
08-17 15:52:11.798  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:52:11.798  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 15:52:11.798  1035  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:52:11.798  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:52:11.799  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:52:11.799  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.801   308   893 D CommandListener: Setting iface cfg
08-17 15:52:11.801   308   893 D CommandListener: Trying to bring up p2p0
08-17 15:52:11.801  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 15:52:11.801  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-17 15:52:11.802  1035  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 15:52:11.802  1035  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.802  1035  1537 D LGWifiP2pService: P2pEnablingState
08-17 15:52:11.802  1035  1558 I WifiNative-HAL: startHal
08-17 15:52:11.802  1035  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf6b0f80
08-17 15:52:11.802  1035  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.802  1035  1558 D wifi    : failed to get capabilities : -3
08-17 15:52:11.802  1035  1537 D LGWifiP2pService: P2p socket connection successful
08-17 15:52:11.802  1035  1558 E WifiScanningService: could not get scan capabilities
08-17 15:52:11.802  1035  1537 D LGWifiP2pService: P2pEnabledState
08-17 15:52:11.802  1035  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.802  1035  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 15:52:11.803  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:52:11.803  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 15:52:11.804  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 15:52:11.804  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 15:52:11.804  1969  1969 D WfdsService: WifiP2pState is changed : true
08-17 15:52:11.805  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 15:52:11.805  1035  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 15:52:11.805  1969  2337 D WfdsService: Receive the WFDS_ENABLE Method
08-17 15:52:11.805  1969  2337 D WfdsService: Set the WFDS Monitor: true
08-17 15:52:11.805  1969  2337 D WfdsService: Connected to the supplicant for wfds
08-17 15:52:11.805  1969  2337 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 15:52:11.805  7936  7936 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 15:52:11.805  1969  2337 D WfdsService: selectPreferredScanChannel [36]
08-17 15:52:11.805  1969  2337 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 15:52:11.806  1035  1537 D WifiNative-p2p0: SET persistent_reconn,ect 1: returned true
08-17 15:52:11.806  1035  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 15:52:11.807  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 15:52:11.808  1969  1969 D WfdsService: isConnected: false
08-17 15:52:11.808  1035  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-17 15:52:11.808  1035  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 15:52:11.808  1035  1537 D LGWifiP2pService: before postfix = G3
08-17 15:52:11.808  1035  1537 D WifiServerServiceExt: postfix byte check : 2
08-17 15:52:11.808  1035  1537 D LGWifiP2pService: after postfix = G3
08-17 15:52:11.808  1035  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 15:52:11.809  1035  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 15:52:11.809  1035  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 15:52:11.809  1035  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 15:52:11.809  1035  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-17 15:52:11.810  1035  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 15:52:11.810  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 15:52:11.810  1035  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 15:52:11.810  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-17 15:52:11.811  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 15:52:11.813  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 15:52:11.813  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 15:52:11.813  1969  1969 D WfdsService: Update P2p Interface State: 3
08-17 15:52:11.813  1035  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 15:52:11.813  1035  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 15:52:11.814  1035  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 15:52:11.814  1035  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 15:52:11.814  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 15:52:11.814  1035  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 15:52:11.815  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:52:11.815  1035  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 15:52:11.815  1035  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 15:52:11.815  1035  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 15:52:11.815  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:52:11.815  1035  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 15:52:11.815  7936  7936 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 15:52:11.815  1035  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 15:52:11.815  1035  1537 D WifiNative-p2p0:    returned OK
08-17 15:52:11.816  1035  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 15:52:11.816  1035  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 15:52:11.816  1035  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 15:52:11.816  1035  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 15:52:11.816  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:52:11.818  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:52:11.824  7189  7961 V FormManager: Network unavailable.
08-17 15:52:11.824  7553  7553 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 15:52:11.824  7553  7553 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-17 15:52:11.824  7553  7553 V [BNRBootReceiver]: Boot Receiver Return
08-17 15:52:11.826  7936  7936 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-17 15:52:11.826  1035  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 15:52:11.826  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 15:52:11.826  1035  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 15:52:11.827  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 15:52:11.827  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 15:52:11.827  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 15:52:11.828  4866  7963 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:52:11.829  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:52:11.829  7936  7936 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.830  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:52:11.830  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.830  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.830  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.830  7936  7936 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:52:11.830  7936  7936 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.831  1035  1537 D LGWifiP2pService: InactiveState
08-17 15:52:11.831  7936  7936 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.831  1035  1537 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.831  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.831  1035  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 15:52:11.831  1035  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 15:52:11.832  1969  7962 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.832  1969  7962 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.832  1035  7957 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.832  1035  7957 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.832  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:52:11.832  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.832  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.832  1035  7957 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.832  1035  7957 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.832  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.832  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.832  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:52:11.833  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:52:11.833  7189  7961 V FormManager: Network unavailable.
08-17 15:52:11.833  7936  7936 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.833  4866  7964 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:52:11.834  4866  7964 D LGDMClient:, [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:52:11.834  7936  7936 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:52:11.834  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:52:11.834  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 15:52:11.834  7936  7936 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.835  1035  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.835  7936  7936 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.835  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1969  7962 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:52:11.836  1969  7962 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1969  7962 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1035  7957 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1035  7957 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.836  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:52:11.836  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:52:11.836  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:11.836  1035  7957 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.836  1035  7957 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.836  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.836  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.836  1035  7957 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:52:11.836  1035  7957 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.836  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:52:11.836  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-17 15:52:11.837  1035  1035 E WifiServerServiceExt: No p2p device connected
08-17 15:52:11.837  1969  2337 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 15:52:11.837  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 15:52:11.838  7936  7936 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:52:11.838  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 15:52:11.838  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:52:11.838  1035  7957 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:52:11.838  1035  7957 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:52:11.839  1035  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-17 15:52:11.839  1035  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 15:52:11.839  1035  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 15:52:11.839  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
,08-17 15:52:11.841  1035  1538 D WifiNative-wlan0: SCAN: returned false
08-17 15:52:11.841  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=210645  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:52:11.841  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:52:11.842  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=210645  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-17 15:52:11.843  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=210646  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:52:11.845  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:11.845  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:11.845  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.845  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.846  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 15:52:11.846  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:52:11.847  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=210650  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:52:11.847  1035  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:52:11.848  1035  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:52:11.848  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:11.848  1035  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:52:11.848  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:11.849  1035  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:52:11.849  1035  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-17 15:52:11.855  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-17 15:52:11.855  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.855  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:11.855  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-17 15:52:11.855  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:52:11.856  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 15:52:11.856  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-17 15:52:11.858  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@14cb7587 Bundle[{}]
08-17 15:52:11.859  6981  7058 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 15:52:11.859  6981  7058 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 15:52:11.860  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 15:52:11.861  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 15:52:11.862  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 15:52:11.862  6981  7058 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 15:52:11.864  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 15:52:11.869  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:11.869  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:11.869  6981  7058 I System.out: Running OutgoingSocketThread
08-17 15:52:11.869  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:11.872  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:52:11.875  6981  7965 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 906)
08-17 15:52:11.876  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:11.876  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:11.877  6981  7965 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52718
08-17 15:52:11.877  6981  7965 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-17 15:52:11.878  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:52:11.881  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:11.887  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:11.892  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:11.898  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:11.898  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:52:11.900  7147  7147 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:52:12.421  7936  7936 E wpa_supplicant: USIM:  scard_init function
08-17 15:52:12.422  7936  7936 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-17 15:52:12.433  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 15:52:12.434  1035  7957 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 15:52:12.434  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 15:52:12.434  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
08-17 15:52:12.434  1035  7957 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 15:52:12.434  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:52:12.434  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 15:52:12.435  1035  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:52:12.436  1035  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:52:12.436  1035  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:52:12.437  1035  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:52:12.437  1035  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-17 15:52:12.452  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=211256  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-17 15:52:12.460  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=211263  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 15:52:12.463  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.463  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.464  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 15:52:12.464  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.465  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:12.469  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:52:12.472  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:52:12.473  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-17 15:52:12.479  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-17 15:52:12.487  7072  7072 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-17 15:52:12.498  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:52:12.508  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:12.516  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.524  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.525  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.525  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:52:12.548  7936  7936 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:52:12.556  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 15:52:12.556  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-17 15:52:12.556  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 15:52:12.556  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 15:52:12.556  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:52:12.556  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:52:12.560  7936  7936 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:52:12.561  7936  7936 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:52:12.565  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=211366  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 15:52:12.565  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=211369  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 15:52:12.566  1035  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211369
08-17 15:52:12.566  1035  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211370
08-17 15:52:12.566  1035  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211370
08-17 15:52:12.567  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211370
08-17 15:52:12.567  1035  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=211371
,08-17 15:52:12.571  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:52:12.571  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:52:12.571  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 15:52:12.571  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:52:12.571  1035  7957 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:52:12.571  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 15:52:12.573  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 15:52:12.588  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:52:12.588  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:52:12.588  7072  7072 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:52:12.589  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:52:12.589  1035  7957 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:52:12.589  7072  7072 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:52:12.590  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:52:12.590  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:52:12.591  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=211394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 15:52:12.591  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-17 15:52:12.598  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.598  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:12.598  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.598  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.599  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 15:52:12.599  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=211403  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 15:52:12.600  7072  7072 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:52:12.600  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.600  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 15:52:12.600  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:52:12.600  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:52:12.600  7072  7072 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:52:12.600  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=211404  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 15:52:12.601  7072  7072 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 15:52:12.601  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=211405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 15:52:12.601  7072  7072 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:52:12.602  1035  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:12.602  1035  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:12.603  1035  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-17 15:52:12.605  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.605  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.605  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 15:52:12.605  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:12.605  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:52:12.605  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 15:52:12.606  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:52:12.606  1035  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=211410
08-17 15:52:12.609  1035  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=211412
08-17 15:52:12.609  1035  1538 D WifiNative-wlan0: doString: [STATUS]
08-17 15:52:12.610  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.610  1035  7957 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:52:12.610  1035  7957 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:52:12.610  1035  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:52:12.613  1035  1538 I WifiServiceExtension: setVHTCapabilityType  : false
08-17 15:52:12.619  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:12.622  1035  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 15:52:12.622  1035  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 15:52:12.623  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.624  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:12.624  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.627  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.629  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.629  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.629  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:52:12.632  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.632  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.633  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:52:12.633  1035  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 15:52:12.633  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:52:12.633  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:52:12.633  1035  1545 D ConnectivityService: Got NetworkAgent Messenger
08-17 15:52:12.634  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 15:52:12.634  1035  1545 D ConnectivityService: NetworkAgent connected
08-17 15:52:12.634  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:52:12.634  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:52:12.640  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:52:12.640  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:52:12.640  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:52:12.641  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:52:12.641  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:52:12.644  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.645  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:12.645  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.645  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.645  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:52:12.647  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-17 15:52:12.648  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:52:12.651   308   893 D CommandListener: Setting iface cfg
08-17 15:52:12.651  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.651  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:52:12.652  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.653  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.659  1035  1538 E WifiStateMachine: Start Dhcp Watchdog 2
08-17 15:52:12.659  1035  7992 D DhcpStateMachine: StoppedState
08-17 15:52:12.659  1035  7992 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.659  1035  7992 D DhcpStateMachine: WaitBeforeStartState
08-17 15:52:12.660  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=211463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:52:12.661  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=211464  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-17 15:52:12.663  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=211466  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:52:12.664  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:52:12.664  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 15:52:12.664  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 15:52:12.664  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=211468  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:52:12.666  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=211468  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:52:12.667  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=211470  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:52:12.668  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:165459] from screen [on:0 period:-1731849860] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 15:52:12.669  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1731849859] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 15:52:12.669  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 15:52:12.670  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.675  1035  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-17 15:52:12.675  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:52:12.676  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:52:12.676  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 15:52:12.677  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:52:12.677  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:52:12.678  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:52:12.678  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.678  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 15:52:12.679  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=96,0,0
08-17 15:52:12.679  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=96,0,0
08-17 15:52:12.679  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 15:52:12.680  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 15:52:12.681  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.681  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.681  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 15:52:12.681  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 15:52:12.682  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:52:12.682  1035  1538 D WifiNative-wlan0: SET ps 0: returned true
08-17 15:52:12.682  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 15:52:12.682  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 15:52:12.682  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 15:52:12.682  1035  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 15:52:12.682  1035  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 15:52:12.682  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a5ce07c target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.682  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a5ce07c target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.682  1035  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 15:52:12.683  1035  7992 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.683  1035  7992 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 15:52:12.683   308   893 D CommandListener: Setting iface cfg
08-17 15:52:12.684   308   893 D CommandListener: Trying to bring up wlan0
08-17 15:52:12.685  1035  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 15:52:12.686  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.687  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:52:12.687  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-17 15:52:12.692  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 15:52:12.692  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 15:52:12.692  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:52:12.692  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:52:12.692  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 15:52:12.692  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.692  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.692  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:52:12.693  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:52:12.693  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 15:52:12.693  7936  7936 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 15:52:12.694  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 15:52:12.694  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:52:12.696  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:12.700  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.706  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.706  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:52:12.706  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:52:12.709  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:52:12.709  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 15:52:12.710  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:12.710  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.710  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:12.711  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 15:52:12.711  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:12.712  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:12.713  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:12.714  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 15:52:12.715  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 15:52:12.715  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 15:52:12.715  1035  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 15:52:12.716  1035  1545 D ConnectivityService: ignoring duplicate network state non-change
08-17 15:52:12.717  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 15:52:12.721  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.722  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:52:12.723  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.724  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.725  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.725  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 15:52:12.725  1035  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 15:52:12.726  1035  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-17 15:52:12.728  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.729  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.729  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.729  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 15:52:12.730  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 15:52:12.732  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 15:52:12.734  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.735  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.735  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 15:52:12.738  1035  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 15:52:12.740  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-17 15:52:12.745  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.745  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:52:12.746  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.747  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.747  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:52:12.747  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 15:52:12.748  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.748  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 15:52:12.748  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.751  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.751  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.751  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:52:12.755  1035  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 15:52:12.755  1035  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-17 15:52:12.755  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:52:12.755  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-17 15:52:12.756  1035  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-17 15:52:12.757   308   893 E Netd    : netlink response contains error (File exists)
08-17 15:52:12.757  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.758  1035  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-17 15:52:12.758  1035  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 15:52:12.758  1035  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-17 15:52:12.759  1035  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-17 15:52:12.760  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 15:52:12.760  1035  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.760  1035  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.760  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.760  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:52:12.760  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:12.760  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 15:52:12.760  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.760  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 15:52:12.760  1035  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-17 15:52:12.760  1035  1545 D ConnectivityService:    accepting network in place of null
08-17 15:52:12.761  1035  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.761  1035  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.761  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:52:12.761  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.761  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 15:52:12.761  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.761  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:52:12.761  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 15:52:12.761  1880  1880 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.762  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:52:12.764  1035  1545 E ConnectivityService: [lg_data] Ad,ding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 15:52:12.764  1035  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 15:52:12.764  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:52:12.767  1035  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:52:12.767  1035  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 15:52:12.767   308  7998 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-17 15:52:12.767  1035  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-17 15:52:12.769  1035  1545 D ConnectivityService: validation of new default Network = false
08-17 15:52:12.769  1035  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 15:52:12.769  1035  1545 D DSQN    : enableDataServiceNotify 
08-17 15:52:12.769  1035  1545 D DSQN    : start dsqn bin
08-17 15:52:12.769  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 15:52:12.770  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:52:12.770  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:52:12.770  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:52:12.774  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.775  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.775  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:12.775  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:12.775  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:52:12.760  7999  7999 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:12.760  7999  7999 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:52:12.789  7999  7999 E DSQN    : DSQN ssw
08-17 15:52:12.792  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:12.796  1035  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-17 15:52:12.798  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.808  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:52:12.808  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.813  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:52:12.813  1835  8003 I CheckinService: active receiver: enabled
08-17 15:52:12.817   308  7998 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-17 15:52:12.822  1835  8003 I CheckinService: Preparing to send checkin request
08-17 15:52:12.822  1835  8003 I EventLogService: Accumulating logs since 1471441764501
08-17 15:52:12.823  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:52:12.823  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.824  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:52:12.825  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.829  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:12.835  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.841  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.841  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.842  7147  7147 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:52:12.850   308  7998 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-17 15:52:12.851  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:52:12.855  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 15:52:12.858  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:52:12.861  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:52:12.867  1835  8003 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 15:52:12.867  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.874  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:52:12.874  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.875  6981  7058 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 907)
08-17 15:52:12.875  6981  7058 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 907)
08-17 15:52:12.875  7147  7147 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 15:52:12.876  7147  7147 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 15:52:12.877  7147  7147 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 15:52:12.878  6981  7058 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 912)
08-17 15:52:12.879   308   892 D LGDataListener: argv[0]=dsqncommand
08-17 15:52:12.879   308   892 D LGDataListener: argv[1]=wlan0
08-17 15:52:12.879   308   892 D LGDataListener: argv[2]=1
08-17 15:52:12.879   308   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 15:52:12.880  6981  7058 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 15:52:12.880  6981  7058 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 913)
08-17 15:52:12.881  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 15:52:12.881  1035  1115 D DSQN    : start to monitor internet connection
08-17 15:52:12.883  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:52:12.884  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:12.884  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43f1e38 added. We now have 2 listener(s)
08-17 15:52:12.885  1035  7992 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 15:52:12.886  1035  7992 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 15:52:12.886  1035  7992 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-17 15:52:12.889  1035  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.870  8007  8007 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:52:12.870  8007  8007 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:52:12.894  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:12.894  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:12.894  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:12.894  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:12.894  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21651e11 added. We now have 9 listener(s)
08-17 15:52:12.894  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:12.894  7119  7119 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 15:52:12.895  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:52:12.896  7119  7119 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:52:12.897  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:52:12.899  8007  8007 I dhcpcd  : version 5.5.6 starting
,08-17 15:52:12.902  8007  8007 E dhcpcd  : get_duid: m
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:52:12.902  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:52:12.902  8007  8007 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 15:52:12.902  8007  8007 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 15:52:12.903  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:12.904  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:52:12.904  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:12.904  7072  7072 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 15:52:12.904  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32da577 added. We now have 3 listener(s)
08-17 15:52:12.904  1035  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.907  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:12.907  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:52:12 GMT], X-Android-Received-Millis=[1471441932906], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471441932878]}
08-17 15:52:12.908  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 15:52:12.908  1035  7991 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 15:52:12.908  1035  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.908  1035  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.908  1035  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:52:12.908  1035  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:12.908  1035  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 15:52:12.908  1035  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-17 15:52:12.909  1035  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 15:52:12.909  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.909  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:12.909  1035  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:12.909  6981  7058 D org.thaliproject.p2p.btconnecto,rlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:12.909  1035  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.909  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:52:12.910  1035  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 15:52:12.910  1035  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.910  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:52:12.911  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:12.911  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:12.911  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:12.911  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e3e5e4 added. We now have 10 listener(s)
08-17 15:52:12.911  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:12.911  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:52:12.911  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:12.911  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:52:12.911  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:52:12.912  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:12.912  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.912  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:12.912  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:12.912  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43f1e38 removed from the list
08-17 15:52:12.912  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:12.913  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21651e11 removed from the list
08-17 15:52:12.913  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:52:12.913  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:52:12.917  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.917  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.918  1880  1880 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:12.918  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-17 15:52:12.919  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:12.919  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:12.919  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:12.919  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21651e11 not in the list
08-17 15:52:12.919  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.919  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.920  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:12.920  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:12.921  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:12.921  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e3e5e4 removed from the list
08-17 15:52:12.921  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:12.921  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.921  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.921  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:12.921  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32da577 removed from the list
08-17 15:52:12.922  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:12.922  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a6c8a4d added. We now have 2 listener(s)
08-17 15:52:12.922  1035  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.926  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:12.926  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:12.926  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:12.926  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:12.926  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e88902 added. We now have 9 listener(s)
08-17 15:52:12.926  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:12.927  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:52:12.930  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:52:12.931  7072  7072 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:52:12.936  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:52:12.938  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:52:12.939  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:52:12.939  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.939  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:52:12.939  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:12.939  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32eb7c50 added. We now have 3 listener(s)
08-17 15:52:12.940  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:52:12.942  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:12.943  1035  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.943  7147  7147 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:52:12.944  7147  7147 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:52:12.944  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:12.944  7147  7147 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 15:52:12.945  7147  7147 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 15:52:12.945  7147  7147 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 15:52:12.946  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:12.946  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:12.946  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:12.946  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:12.946  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24047e49 added. We now have 10 listener(s)
08-17 15:52:12.946  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:12.946  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:52:12.946  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:52:12.946  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:52:12.946  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:52:12.946  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:52:12.949  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:52:12.949  1035  2087 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.953  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: f,alse
,08-17 15:52:12.955  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:52:12.956  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:52:12.957  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:12.959  6981  7058 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:52:12.959  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:52:12.959  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:52:12.960  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:52:12.960  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:52:12.960  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:52:12.961  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:12.961  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.961  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:12.961  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:12.961  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a6c8a4d removed from the list
08-17 15:52:12.961  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:12.961  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e88902 removed from the list
08-17 15:52:12.961  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:52:12.961  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.961  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.961  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.962  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:12.962  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:12.962  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:12.962  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e88902 not in the list
08-17 15:52:12.962  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.962  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.963  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:12.964  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:52:12.964  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:52:12.964  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:12.964  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:12.965  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24047e49 removed from the list
08-17 15:52:12.965  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:12.965  8007  8007 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 15:52:12.965  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:12.965  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:12.965  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:12.965  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32eb7c50 removed from the list
08-17 15:52:12.965  8007  8007 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, lin,k /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 15:52:12.965  8007  8007 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 15:52:12.965  8007  8007 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 15:52:12.965  8007  8007 D dhcpcd  : wlan0: sending REQUEST (xid 0x7c9d92ad), next in 3.28 seconds
08-17 15:52:12.965  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:12.966  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14940d7c added. We now have 2 listener(s)
08-17 15:52:12.966  1035  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:52:12.969  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:12.969  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:12.970  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:12.970  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:12.970  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90db605 added. We now have 9 listener(s)
08-17 15:52:12.970  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:12.970  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:52:12.973  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:52:12.976  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:52:12.977  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:12.978  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:52:12.978  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:52:12.978  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324c08b added. We now have 3 listener(s)
08-17 15:52:12.978  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.980  8007  8007 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-17 15:52:12.983  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:12.983  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:12.983  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:12.983  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:12.983  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd28568 added. We now have 10 listener(s)
08-17 15:52:12.983  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:12.983  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:52:12.984  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:52:12.984  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:52:12.984  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:52:12.984  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:52:12.984  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:52:12.985  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:12.987  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:12.988  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:52:12.988  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:12.991  8007  8007 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 15:52:12.991  8007  8007 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 15:52:12.991  8007  8007 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 15:52:12.991  8007  8007 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 15:52:12.991  8007  8007 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 15:52:12.991  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:52:12.992  8007  8007 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-17 15:52:12.992  8007  8007 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 15:52:12.992  8007  8007 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-17 15:52:12.994  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:52:12.995  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:52:13.048  1035  1968 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8019 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-17 15:52:13.049  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:52:13.051  6981  7058 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:52:13.051  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:52:13.051  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:52:13.051  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:52:13.051  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:13.052  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.052  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:13.052  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:13.052  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14940d7c removed from the list
08-17 15:52:13.052  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.052  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90db605 removed from the list
08-17 15:52:13.052  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:52:13.052  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.052  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.052  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.053  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:13.053  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:13.053  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.053  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90db605 not in the list
08-17 15:52:13.053  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.053  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.059  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:13.060  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:52:13.060  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:52:13.060  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:13.060  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.060  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fd28568 removed from the list
08-17 15:52:13.060  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:13.060  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.060  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.060  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:13.060  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324c08b removed from the list
08-17 15:52:13.061  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:13.061  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionMan,agerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49cda67 added. We now have 2 listener(s)
08-17 15:52:13.061  1035  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:13.064  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:13.064  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:13.064  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:13.065  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:13.065  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fe9014 added. We now have 9 listener(s)
08-17 15:52:13.065  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:13.065  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:52:13.068  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:52:13.074  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:52:13.076  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:13.076  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:52:13.077  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:13.077  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e9936b2 added. We now have 3 listener(s)
08-17 15:52:13.080  1035  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:13.081  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:52:13.083  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:13.083  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:13.083  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:13.083  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:13.084  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:13.084  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1592b603 added. We now have 10 listener(s)
08-17 15:52:13.084  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:13.084  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:52:13.084  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:52:13.084  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:52:13.084  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:52:13.084  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:52:13.090  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:52:13.091  1035  2332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:13.095  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:52:13.095  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:52:13.098  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:52:13.100  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:13.101  6981  7058 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:52:13.103  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:52:13.104  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:52:13.104  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:52:13.104  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:13.104  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.104  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:13.104  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:13.104  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49cda67 removed from the list
08-17 15:52:13.104  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.104  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fe9014 removed from the list
08-17 15:52:13.104  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:52:13.104  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.104  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.104  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.105  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:13.105  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:13.105  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.105  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fe9014 not in the list
08-17 15:52:13.105  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.105  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.106  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:13.107  6981  7058 D BluetoothLeScanner: could not find callback wrapper
08-17 15:52:13.107  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:52:13.107  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:13.107  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.107  6981,  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1592b603 removed from the list
08-17 15:52:13.107  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:13.107  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.107  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.107  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:13.107  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e9936b2 removed from the list
08-17 15:52:13.108  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:13.108  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e00bfe added. We now have 2 listener(s)
,08-17 15:52:13.109  8019  8019 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 15:52:13.110  1035  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:13.110  8019  8019 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-17 15:52:13.112  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:13.112  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:13.112  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:13.112  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:13.112  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b80af5f added. We now have 9 listener(s)
08-17 15:52:13.112  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:13.113  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:52:13.121  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:52:13.125  6981  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:52:13.127  6981  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:52:13.127  6981  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:52:13.127  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:52:13.127  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d412a75 added. We now have 3 listener(s)
08-17 15:52:13.127  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:52:13.129  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:13.130  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:52:13.130  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:52:13.130  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:52:13.130  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:52:13.130  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b2cea0a added. We now have 10 listener(s)
08-17 15:52:13.130  6981  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:52:13.131  6981  7058 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:52:13.131  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:52:13.131  6981  7058 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:52:13.131  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:13.131  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.131  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:52:13.131  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:13.131  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Con,nectionManager@4e00bfe removed from the list
08-17 15:52:13.131  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.131  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b80af5f removed from the list
08-17 15:52:13.132  6981  6981 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:52:13.132  6981  7058 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:52:13.132  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.133  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.133  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.133  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:13.133  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:13.133  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.133  6981  7058 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b80af5f not in the list
08-17 15:52:13.133  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.133  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.134  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:52:13.134  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:52:13.134  6981  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:52:13.134  6981  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b2cea0a removed from the list
,08-17 15:52:13.134  6981  7058 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:52:13.134  6981  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:52:13.134  6981  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:52:13.134  6981  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:52:13.135  6981  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d412a75 removed from the list
,08-17 15:52:13.135  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 15:52:13.136  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 15:52:13.136  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-17 15:52:13.136  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:52:13.137  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 15:52:13.137  6981  7058 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:52:13.147  8019  8019 I MultiDex: VM with version 2.1.0 has multidex support
08-17 15:52:13.147  8019  8019 I MultiDex: install
08-17 15:52:13.147  8019  8019 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-17 15:52:13.156  6981  8048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: My test thread name)
,08-17 15:52:13.156  6981  8048 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: My test thread name)
08-17 15:52:13.157  6981  8048 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 15:52:13.157  8019  8019 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-17 15:52:13.159  6981  8049 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: My test thread name)
08-17 15:52:13.159  6981  8049 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: My test thread name)
08-17 15:52:13.159  6981  8049 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 15:52:13.162  6981  7058 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 15:52:13.162  6981  7058 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 15:52:13.162  6981  7058 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 15:52:13.162  6981  7058 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 15:52:13.162  6981  7058 D com.test.thalitest.ThaliTestRunner: Total duration: 23012 ms
08-17 15:52:13.163  6981  7058 I jxcore-log: Total number of executed tests:  80
08-17 15:52:13.163  6981  7058 I jxcore-log: 
,08-17 15:52:13.163  6981  7058 I jxcore-log: Number of passed tests:  80
08-17 15:52:13.163  6981  7058 I jxcore-log: 
08-17 15:52:13.163  6981  7058 I jxcore-log: Number of failed tests:  0
08-17 15:52:13.163  6981  7058 I jxcore-log: 
08-17 15:52:13.164  6981  7058 I jxcore-log: Number of ignored tests:  0
08-17 15:52:13.164  6981  7058 I jxcore-log: 
08-17 15:52:13.164  6981  7058 I jxcore-log: Total duration:  23012
08-17 15:52:13.164  6981  7058 I jxcore-log: 
08-17 15:52:13.164  6981  7058 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 15:52:13.164  6981  7058 I jxcore-log: 
08-17 15:52:13.166  2246  2246 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-17 15:52:13.175  2246  2246 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-17 15:52:13.175  2246  2246 D c       : Getting all permits...
08-17 15:52:13.175  2246  2246 D a       : Opening database...
08-17 15:52:13.179  2246  2246 D a       : Opening database auth.proximity.permit_store...
08-17 15:52:13.179  2246  2246 D a       : Closing database...
08-17 15:52:13.182  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.182  6981  7058 I jxcore-log: 
08-17 15:52:13.185  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.185  6981  7058 I jxcore-log: 
,08-17 15:52:13.186  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.186  6981  7058 I jxcore-log: 
08-17 15:52:13.187  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.187  6981  7058 I jxcore-log: 
08-17 15:52:13.188  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.188  6981  7058 I jxcore-log: 
08-17 15:52:13.188  6981  6981 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 15:52:13.190  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:52:13.190  6981  7058 I jxcore-log: 
08-17 15:52:13.193  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:52:13.193  6981  7058 I jxcore-log: 
08-17 15:52:13.194  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.194  6981  7058 I jxcore-log: 
08-17 15:52:13.195  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.195  6981  7058 I jxcore-log: 
08-17 15:52:13.196  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.196  6981  7058 I jxcore-log: 
08-17 15:52:13.197  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:52:13.197  6981  7058 I jxcore-log: 
,08-17 15:52:13.199  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:52:13.199  6981  7058 I jxcore-log: 
08-17 15:52:13.200  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:52:13.200  6981  7058 I jxcore-log: 
08-17 15:52:13.201  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.201  6981  7058 I jxcore-log: 
08-17 15:52:13.202  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.202  6981  7058 I jxcore-log: 
08-17 15:52:13.202  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.202  6981  7058 I jxcore-log: 
08-17 15:52:13.203  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.203  6981  7058 I jxcore-log: 
08-17 15:52:13.204  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.204  6981  7058 I jxcore-log: 
,08-17 15:52:13.204  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.204  6981  7058 I jxcore-log: 
08-17 15:52:13.205  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.205  6981  7058 I jxcore-log: 
08-17 15:52:13.205  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:52:13.205  6981  7058 I jxcore-log: 
08-17 15:52:13.206  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:52:13.206  6981  7058 I jxcore-log: 
08-17 15:52:13.207  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:52:13.207  6981  7058 I jxcore-log: 
08-17 15:52:13.208  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.208  6981  7058 I jxcore-log: 
08-17 15:52:13.208  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.208  6981  7058 I jxcore-log: 
08-17 15:52:13.209  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.209  6981  7058 I jxcore-log: 
,08-17 15:52:13.209  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.209  6981  7058 I jxcore-log: 
08-17 15:52:13.210  6981  7058 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:52:13.210  6981  7058 I jxcore-log: 
08-17 15:52:13.289  1035  7992 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-17 15:52:13.292  1035  7992 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 15:52:13.292  1035  7992 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 15:52:13.293  1035  7992 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 15:52:13.293  1035  7992 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 15:52:13.293  1035  7992 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 15:52:13.293  1035  7992 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 15:52:13.293  1035  7992 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-17 15:52:13.293  1035  7992 D DhcpStateMachine: RunningState
,08-17 15:52:13.470  8056  8056 D AndroidRuntime: 
,08-17 15:52:13.470  8056  8056 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 15:52:13.473  8056  8056 D AndroidRuntime: CheckJNI is OFF
,08-17 15:52:13.539  8058  8058 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 15:52:13.598  8056  8056 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 15:52:13.608  1035  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-17 15:52:13.608  1035  1108 I ActivityManager: Killing 6981:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-17 15:52:13.611  8058  8058 I dex2oat : dex2oat took 72.014ms (threads: 4)
,08-17 15:52:13.626  8019  8035 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:52:13.626  8019  8035 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:52:13.626  8019  8035 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:52:13.626  8019  8035 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:52:13.626  8019  8035 I Adreno-EGL: Remote Branch: 
08-17 15:52:13.626  8019  8035 I Adreno-EGL: Local Patches: 
08-17 15:52:13.626  8019  8035 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:52:13.658  1035  1968 I WindowState: WIN DEATH: Window{29d4f8da u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-17 15:52:13.658  1035  1544 D WifiService: Client connection lost with reason: 4
08-17 15:52:13.662  1035  1968 D InputDispatcher: Window went away: Window{29d4f8da u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 15:52:13.731  8019  8035 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:52:13.731  8019  8035 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:52:13.731  8019  8035 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:52:13.731  8019  8035 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:52:13.731  8019  8035 I Adreno-EGL: Remote Branch: 
08-17 15:52:13.731  8019  8035 I Adreno-EGL: Local Patches: 
08-17 15:52:13.731  8019  8035 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:52:13.822  1035  1108 I ActivityManager:   Force finishing activity ActivityRecord{6dca507 u0 com.test.thalitest/.MainActivity t6}
,08-17 15:52:13.875   333   351 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 15:52:13.880  1035  2032 W ActivityManager: Spurious death for ProcessRecord{fb5f1e5 6981:com.test.thalitest/u0a118}, curProc for 6981: null
08-17 15:52:13.881  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-17 15:52:13.882  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-17 15:52:13.883  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d8396c3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 15:52:13.883  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{6dca507 u0 com.test.thalitest/.MainActivity t6 f}
08-17 15:52:13.883  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{6dca507 u0 com.test.thalitest/.MainActivity t6 f}
08-17 15:52:13.884  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-17 15:52:13.885  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{6c8cb40 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-17 15:52:13.922  1035  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:13.922  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:13.922  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:13.923  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:13.923  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:13.924  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:52:13.928  2041  2041 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-17 15:52:13.930  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-17 15:52:13.934  3865  3865 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-17 15:52:13.938  2474  2619 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 15:52:13.941  1035  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-17 15:52:13.941  1035  1545 D ConnectivityService: identical MTU - not setting
08-17 15:52:13.941  1035  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 15:52:13.941  1035  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:52:13.942  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:52:13.942  1035  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:13.942  1035  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:52:13.948  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 15:52:13.948  7772  7772 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-17 15:52:13.948  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 15:52:13.970  1035  1788 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:52:13.977  5129  5129 I art     : Explicit concurrent mark sweep GC freed 725(40KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 539us total 78.031ms
,08-17 15:52:13.989  1035  1428 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 15:52:14.002  2093  2093 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-17 15:52:14.004  2093  2093 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-17 15:52:14.007  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-17 15:52:14.009  2093  2178 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-17 15:52:14.015  6551  6551 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-17 15:52:14.016  5007  5007 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-17 15:52:14.016  5007  5007 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-17 15:52:14.016  5007  5007 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-17 15:52:14.016  5007  5007 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-17 15:52:14.016  5007  5007 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:52:14.016  5007  5007 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:52:14.016  5007  5007 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:52:14.016  5007  5007 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:52:14.016  5007  5007 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:52:14.016  5007  5007 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:52:14.016  5007  5007 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:52:14.016  5007  5007 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:52:14.031  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-17 15:52:14.033  1931  1931 D ActionManagerService: notifyUserLog: 1000003
08-17 15:52:14.034  2093  2093 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-17 15:52:14.034  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-17 15:52:14.034  3865  5033 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-17 15:52:14.037  1835  1835 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-17 15:52:14.053  2093  2093 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-17 15:52:14.061  1035  1035 D administrator: Handling package changes for user 0
08-17 15:52:14.066  1035  1578 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:52:14.066  1035  1578 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:52:14.069  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-17 15:52:14.076  8019  8035 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 15:52:14.076  8019  8035 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:52:14.084  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-17 15:52:14.096  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:52:14.106  2093  2093 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-17 15:52:14.118  1035  1106 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-17 15:52:14.137  1897  1897 D SplitUIManager: split_name #11 / not available #0
08-17 15:52:14.137  1897  1897 D SplitUIService: removed split : 
,08-17 15:52:14.150  1035  1722 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8088 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-17 15:52:14.154  2246  2246 I ConfigService: onCreate
08-17 15:52:14.155  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-17 15:52:14.156  1035  1968 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-17 15:52:14.157  1931  1931 D ActionManagerService: notifyUserLog: 1000004
08-17 15:52:14.157  3865  5033 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 15:52:14.158  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:52:14.158  7772  7772 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 15:52:14.159  2246  2246 I ConfigService: onBind returning update interface
08-17 15:52:14.159  1835  1835 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-17 15:52:14.160  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-17 15:52:14.161  2246  2246 I ConfigService: onBind returning config service
08-17 15:52:14.162  3865  5029 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , create_time: 1430832262123
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , expire_time: 0
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , display: false
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , animation: false }
,08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , create_time: 1430832262287
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , expire_time: 0
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , display: false
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , animation: false }
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , create_time: 1471007226523
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , expire_time: 0
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , display: false
08-17 15:52:14.165  2093  2093 I GBoardWebViewUtils: , animation: false }
08-17 15:52:14.169  8019  8035 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:52:14.169  8019  8035 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:52:14.169  8019  8035 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:52:14.169  8019  8035 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:52:14.169  8019  8035 I Adreno-EGL: Remote Branch: 
08-17 15:52:14.169  8019  8035 I Adreno-EGL: Local Patches: 
08-17 15:52:14.169  8019  8035 I Adreno-EGL: Reconstruct Branch: 
08-17 15:52:14.176  1835  1835 I ConfigFetchService: service connected
08-17 15:52:14.178  1897  1897 D SplitUIManager: split_name #11 / not available #0
08-17 15:52:14.178  1897  1897 I SplitUIService: split app #11
08-17 15:52:14.181  2093  8104 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-17 15:52:14.189  2246  2246 I ConfigService: onDestroy
08-17 15:52:14.192  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 15:52:14.193  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-17 15:52:14.200  1835  8108 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-17 15:52:14.209  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-17 15:52:14.209  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 15:52:14.209  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-17 15:52:14.212  8088  8088 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,08-17 15:52:14.233  1035  2114 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8112 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-17 15:52:14.235  1035  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-17 15:52:14.241  1605  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 15:52:14.241  1605  1660 D KeyguardModel: createShortcutInfo...
,08-17 15:52:14.244  1605  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 15:52:14.244  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.248  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 15:52:14.248  1605  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:52:14.248  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 15:52:14.249  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 15:52:14.253  5876  8124 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-17 15:52:14.257  1605  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 15:52:14.257  1605  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 15:52:14.271  1605  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 15:52:14.271  1605  1660 D KeyguardModel: createShortcutInfo...
,08-17 15:52:14.275  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 15:52:14.275  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:52:14.277  1835  8129 I PeopleContactsSync: CP2 sync disabled
08-17 15:52:14.291  1605  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:52:14.291  1605  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-17 15:52:14.298  1605  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 15:52:14.298  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.301  1835  8125 W GmsApplication: Using Auth Proxy for data requests.
08-17 15:52:14.303  1605  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 15:52:14.303  1835  5291 I Icing   : doRemovePackageData com.test.thalitest
,08-17 15:52:14.303  1605  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 15:52:14.304  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 15:52:14.304  1605  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 15:52:14.305  1605  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:52:14.305  1605  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 15:52:14.307  1605  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 15:52:14.307  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.310  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-17 15:52:14.310  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-17 15:52:14.314  1605  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 15:52:14.314  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.317  1605  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 15:52:14.317  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.318  1835  8125 W GmsApplication: Using Auth Proxy for data requests.
,08-17 15:52:14.321  1605  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:52:14.321  1605  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 15:52:14.323  2093  2093 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-17 15:52:14.324  1605  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 15:52:14.324  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.325  1605  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:52:14.325  1605  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 15:52:14.327  1605  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 15:52:14.327  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.328  1605  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:52:14.328  1605  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 15:52:14.329  1605  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 15:52:14.329  1605  1660 D KeyguardModel: createShortcutInfo...
08-17 15:52:14.372  8112  8112 I AppUp4:AppBoxCP: onCreate
08-17 15:52:14.372  8112  8112 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-17 15:52:14.377  8112  8112 I AppUp4:DB:  setFingerPrint start
08-17 15:52:14.377  8112  8112 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-17 15:52:14.396  8112  8112 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-17 15:52:14.396  8112  8112 I AppUp4:DB:  SDK version = 21
08-17 15:52:14.396  8112  8112 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-17 15:52:14.399  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-17 15:52:14.399  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-17 15:52:14.400  8112  8112 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-17 15:52:14.413  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-17 15:52:14.417  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.418  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-17 15:52:14.420  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-17 15:52:14.421  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-17 15:52:14.422  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-17 15:52:14.431  2246  2343 I art     : Explicit concurrent mark sweep GC freed 5091(302KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 825us total 16.965ms
08-17 15:52:14.437  8112  8112 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-17 15:52:14.437  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1dd574d0 u0 com.lge.launcher2/.Launcher t5} time:213256
08-17 15:52:14.438  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-17 15:52:14.439  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.440  2093  2291 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-17 15:52:14.441  2093  2291 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-17 15:52:14.444  1035  1123 I art     : Explicit concurrent mark sweep GC freed 87515(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 4.160ms total 362.911ms
,08-17 15:52:14.453  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-17 15:52:14.453  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 15:52:14.453  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.468  1035  1950 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8139 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-17 15:52:14.470  1035  1950 I ActivityManager: Killing 7352:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-17 15:52:14.473  8056  8056 D AndroidRuntime: Shutting down VM
08-17 15:52:14.477  2093  2093 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-17 15:52:14.507   308  8157 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 15:52:14.507   308  8157 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-17 15:52:14.552  1035  2332 W libprocessgroup: failed to open /acct/uid_10046/pid_7352/cgroup.procs: No such file or directory
,08-17 15:52:14.562  2629  2629 D [Concierge]Service: onStartCommand(). Type : 8
08-17 15:52:14.562  2629  2629 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-17 15:52:14.564  2629  2629 D [Concierge]Service: Update widget ID : 11
08-17 15:52:14.569   308  8157 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-17 15:52:14.577  2093  2093 D [Concierge]WidgetView: change position of spinner
08-17 15:52:14.581  2629  2629 D [Concierge]Service: onStartCommand(). Type : 0
08-17 15:52:14.581  2093  2093 I [Concierge]WidgetView: initWebView(). Time : 1471441934581
08-17 15:52:14.606  8139  8139 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:52:14.606  1035  1106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:52:14.607  8139  8139 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:52:14.608  8139  8139 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-17 15:52:14.612  1035  1106 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-17 15:52:14.612  8139  8139 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-17 15:52:14.614  8139  8139 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 15:52:14.619  2093  2093 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 165088216
08-17 15:52:14.620  2093  2093 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-17 15:52:14.620  2093  2093 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-17 15:52:14.624  2093  2093 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@19e51a3b
08-17 15:52:14.624  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-17 15:52:14.625  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 15:52:14.625  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.632  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-17 15:52:14.633  2093  2093 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-17 15:52:14.633  2093  2093 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 15:52:14.634  2093  2093 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471441749365, New one : 1471441934581
08-17 15:52:14.634  2093  2093 D [Concierge]WidgetView: Unregister all receivers
08-17 15:52:14.634  2093  2093 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-17 15:52:14.634  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 15:52:14.636  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.637  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-17 15:52:14.638  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-17 15:52:14.639  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-17 15:52:14.640  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-17 15:52:14.642  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-17 15:52:14.642  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.642  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.671  2093  2093 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-17 15:52:14.685  2093  2093 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-17 15:52:14.685  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-17 15:52:14.687  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:52:14.710  2093  2093 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@980d29d time:213529
,08-17 15:52:14.712  8139  8139 I SystemConfig: BUILD Country: EU
08-17 15:52:14.712  8139  8139 I SystemConfig: BUILD Operator: OPEN
08-17 15:52:14.725  1835  8003 I CheckinTask: Sending checkin request (7866 bytes)
08-17 15:52:14.735  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8158 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 15:52:14.779  1035  1648 I ActivityManager: Killing 7371:com.android.chrome/u0a57 (adj 15): empty #17
,08-17 15:52:14.842  1035  1939 W libprocessgroup: failed to open /acct/uid_10057/pid_7371/cgroup.procs: No such file or directory
,08-17 15:52:14.851  1035  1648 I ActivityManager: Killing 7390:com.lge.drmservice/u0a62 (adj 15): empty #17
08-17 15:52:14.857  2188  8180 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-17 15:52:14.857  8139  8177 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-17 15:52:14.857  8139  8177 I SystemConfig: existFile = false
,08-17 15:52:14.858  8139  8177 I SystemConfig: canReadFile = false
08-17 15:52:14.858  8139  8177 I SystemConfig: systemFeature RCS result false
08-17 15:52:14.858  8139  8177 D SystemConfig: refreshRcsSupport() :false
08-17 15:52:14.860  2188  2335 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
