#### Test 83627337a1c904e_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 09:35:13.770  2233  2233 I ConfigService: onDestroy
,09-07 09:35:36.849  6644  6644 D AndroidRuntime: 
09-07 09:35:36.849  6644  6644 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 09:35:36.853  6644  6644 D AndroidRuntime: CheckJNI is OFF
09-07 09:35:37.060  6644  6644 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 09:35:37.070  1035  1725 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 09:35:37.086  1963  3964 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 09:35:37.092  1035  1725 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 09:35:37.094  1035  1725 D ActivityManager: setTaskToReturnTo : TaskRecord{1c175467 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 09:35:37.094  1035  1725 D ActivityManager: setTaskToReturnTo : TaskRecord{1c175467 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 09:35:37.096  1035  1725 D WindowStateEx: AppWindowTokenEx init.. 
09-07 09:35:37.097   333   344 E GBMv2   : DFP En is all cleared set to be enabled
09-07 09:35:37.126  1035  1725 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6659 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 09:35:37.128  6644  6644 D AndroidRuntime: Shutting down VM
09-07 09:35:37.183  1963  3966 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 09:35:37.183  1963  3966 D SplitWindowPolicy: topRunningActivity=ActivityInfo{11b872b5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 09:35:37.184  1963  1979 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 09:35:37.184  1963  1979 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b7a2d4a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,09-07 09:35:37.366  1035  1962 I art     : Explicit concurrent mark sweep GC freed 35009(1677KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.541ms total 111.013ms
,09-07 09:35:37.369  6659  6659 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-07 09:35:37.470  6659  6659 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 09:35:37.480  6659  6659 I LibraryLoader: Loading: webviewchromium
09-07 09:35:37.483  6659  6659 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 752-756)
09-07 09:35:37.484  6659  6659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 09:35:37.502  6659  6659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35ab332b}
,09-07 09:35:37.503  6659  6659 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:35:37.504  6659  6659 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 09:35:37.515  6659  6659 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 09:35:37.516  6659  6659 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:35:37.532  6659  6659 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 09:35:37.532   317  4007 V AudioPolicyService: registerClient() client 0xb04102e0, uid 10118
09-07 09:35:37.532  6659  6659 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-07 09:35:37.533  6659  6659 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-07 09:35:37.537  1035  1110 D BluetoothManagerService: Message: 20
09-07 09:35:37.537  1035  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@300335b9:true
09-07 09:35:37.555  6659  6659 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 09:35:37.555  6659  6659 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 09:35:37.555  6659  6659 I Adreno-EGL: Build Date: 12/12/14 금
09-07 09:35:37.555  6659  6659 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 09:35:37.555  6659  6659 I Adreno-EGL: Remote Branch: 
09-07 09:35:37.555  6659  6659 I Adreno-EGL: Local Patches: 
09-07 09:35:37.555  6659  6659 I Adreno-EGL: Reconstruct Branch: 
,09-07 09:35:37.642  6659  6693 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 09:35:37.650  6659  6659 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 09:35:37.664  6659  6659 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 09:35:37.670  6659  6659 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 09:35:37.674  6659  6659 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 09:35:37.677  6659  6659 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,09-07 09:35:37.677  6659  6659 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 09:35:37.683  1035  1098 W ActivityManager: Activity pause timeout for ActivityRecord{508214 u0 com.test.thalitest/.MainActivity t6}
09-07 09:35:37.693  6659  6659 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-07 09:35:37.700  6659  6659 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:35:37.700  6659  6659 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 09:35:37.738  6659  6705 D OpenGLRenderer: Render dirty regions requested: true
09-07 09:35:37.738  6659  6705 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 09:35:37.749  6659  6705 D OpenGLRenderer: Enabling debug mode 0
,09-07 09:35:37.758  6659  6659 D Atlas   : Validating map...
09-07 09:35:37.762  1035  1050 D SplitWindow: check instance of lgWin Window{1a113a6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 09:35:37.810  6659  6703 D LgDataFeature: LgDataFeature() Constructor: none
09-07 09:35:37.810  6659  6703 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 09:35:37.883  1035  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +700ms (total +785ms)
09-07 09:35:37.884  1035  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{508214 u0 com.test.thalitest/.MainActivity t6} time:171156
09-07 09:35:37.884  6659  6659 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25d2ff6 time:171156
,09-07 09:35:38.019  6659  6659 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 09:35:38.019  6659  6659 I chromium: 
,09-07 09:35:38.044  6659  6659 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 09:35:38.219  6659  6716 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435177984
,09-07 09:35:38.242  6659  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 09:35:38.242  6659  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 09:35:38.242  6659  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 09:35:38.242  6659  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 09:35:38.242  6659  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 09:35:38.242  6659  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@148312da added. We now have 1 listener(s)
09-07 09:35:38.248  1035  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:35:38.251  6659  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-07 09:35:38.254  6659  6716 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-07 09:35:38.259  6659  6716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:35:38.260  6659  6716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 09:35:38.272  6659  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dfa9401 added. We now have 1 listener(s)
09-07 09:35:38.272  6659  6716 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:38.279  1035  1529 D WifiService: New client listening to asynchronous messages
09-07 09:35:38.283  6659  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:35:38.284  6659  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 09:35:38.286  6659  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 09:35:38.286  6659  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 09:35:38.286  6659  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 09:35:38.292  6659  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:38.292  1035  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:35:38.293  6659  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-07 09:35:38.303  6659  6716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:38.303  6659  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:38.304  6659  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 09:35:38.304  6659  6716 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:35:38.309  6659  6716 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 09:35:38.309  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:38.311  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:38.348  6659  6703 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 09:35:38.348  6659  6703 I chromium: 
,09-07 09:35:38.412  6659  6659 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 09:35:38.461   333   346 E GBMv2   : DFP En is all cleared set to be enabled
09-07 09:35:38.461   333   346 E GBMv2   : Set value is all cleared set the max
09-07 09:35:38.461   333   346 I GBMv2   : DFP Enabled. Ignore VFP set
09-07 09:35:39.339  6659  6719 W jxcore-log: Initializing JXcore engine
09-07 09:35:39.339  6659  6719 W jxcore-log: JXcore engine is ready
09-07 09:35:39.370  6719  6719 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7525]" dev="sockfs" ino=7525 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 09:35:39.370  6719  6719 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-07 09:35:39.370  6719  6719 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10380]" dev="sockfs" ino=10380 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 09:35:39.370  6719  6719 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-07 09:35:39.370  6719  6719 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31597]" dev="sockfs" ino=31597 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 09:35:39.388  6659  6719 W jxcore-log: Starting JXcore engine
09-07 09:35:39.462  6659  6719 W jxcore-log: Platform android
09-07 09:35:39.462  6659  6719 W jxcore-log: 
09-07 09:35:39.462  6659  6719 W jxcore-log: Process ARCH arm
09-07 09:35:39.462  6659  6719 W jxcore-log: 
,09-07 09:35:39.654  6659  6719 I jxcore-log: JXcore Cordova bridge is ready!
09-07 09:35:39.654  6659  6719 I jxcore-log: 
09-07 09:35:39.654  6659  6719 W jxcore-log: JXcore engine is started
,09-07 09:35:39.663  6659  6716 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 09:35:39.670  6659  6659 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 09:35:50.470  6659  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 09:35:50.470  6659  6719 I jxcore-log: 
,09-07 09:35:50.473  6659  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 09:35:50.473  6659  6719 I jxcore-log: 
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:50.477  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:50.480  6659  6719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:50.482  6659  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 09:35:50.482  6659  6719 I jxcore-log: 
,09-07 09:35:50.484  6659  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 09:35:50.484  6659  6719 I jxcore-log: 
,09-07 09:35:50.985  6659  6719 I jxcore-log: Unit Test app is loaded
09-07 09:35:50.985  6659  6719 I jxcore-log: 
,09-07 09:35:50.994  6659  6659 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 09:35:51.003  6659  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:51.003  6659  6719 I jxcore-log: 
09-07 09:35:51.019  6659  6719 D executeNativeTests: Running unit tests
,09-07 09:35:51.173  6659  6719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 09:35:51.173  6659  6719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a added. We now have 2 listener(s)
09-07 09:35:51.173  1035  2080 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 09:35:51.176  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 09:35:51.176  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:35:51.176  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:35:51.177  6659  6719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:35:51.177  6659  6719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b added. We now have 2 listener(s)
09-07 09:35:51.177  6659  6719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:35:51.178  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:35:51.184  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:51.189  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:35:51.190  6659  6719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:51.191  6659  6719 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:35:51.193  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:51.195  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:51.202  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:35:51.204  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:35:51.204  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:35:51.206  6659  6719 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 09:35:51.207  6659  6719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 09:35:51.207  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:35:51.207  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:35:51.208  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:35:51.208  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:51.208  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:51.208  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:51.209  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 09:35:51.209  6659  6719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a removed from the list
09-07 09:35:51.209  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:51.209  6659  6719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b removed from the list
09-07 09:35:51.209  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:51.209  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:51.212  6659  6719 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 09:35:51.215  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:51.215  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:51.215  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:51.216  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:35:51.216  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:51.216  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:35:51.216  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:51.216  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:51.216  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:35:51.225  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 0,9:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 09:35:51.226  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:51.226  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:51.226  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:51.226  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:35:51.226  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:51.226  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:35:51.226  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:51.226  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:51.226  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:51.227  6659  6719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:35:51.229  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:51.233  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:35:51.235  6659  6719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:51.235  6659  6719 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:35:51.237  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:51.239  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:51.240  6659  6719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 09:35:51.240  6659  6719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:35:51.240  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:35:51.240  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:51.240  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:35:51.245  6659  6719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:35:51.245  1035  1750 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:35:51.252  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:35:51.260  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 09:35:51.263  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 09:35:51.265  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:35:51.265  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:51.268  6659  6719 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:35:51.268  6659  6719 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:35:54.273  6659  6719 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 09:35:54.273  6659  6719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 09:35:54.274  6659  6719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 09:35:57.288  6659  6719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:35:57.289  6659  6719 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 09:35:57.289  6659  6719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:35:57.289  6659  6719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:35:57.290  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:35:57.290  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:57.290  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:35:57.311  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:35:57.313  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:57.315  6659  6719 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:35:57.315  6659  6719 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:36:00.070  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:36:00.070  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:36:00.070  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:36:00.070  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:36:00.081  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:36:00.082  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:36:00.084  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:36:00.086  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:36:00.317  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:36:00.323  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:00.323  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:00.324  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:00.324  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:00.325  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:00.325  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:00.325  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:00.330  6659  6719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:36:00.332  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:36:00.338  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:36:00.340  6659  6719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:00.340  6659  6719 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:36:00.342  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:36:00.344  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:36:00.346  6659  6719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:36:00.346  6659  6719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:36:00.346  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:36:00.346  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:36:00.346  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:36:00.352  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:36:00.352  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:00.354  6659  6719 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:36:00.354  6659  6719 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:36:03.354  6659  6719 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 09:36:03.355  6659  6719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 09:36:03.355  6659  6719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 09:36:06.371  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.371  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.372  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:06.372  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.372  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.372  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.372  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.372  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:36:06.384  6659  6719 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 09:36:06.385  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.385  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.385  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.385  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.385  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.385  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.385  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.385  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.386  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.390  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 09:36:06.391  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.391  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.391  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.391  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.391  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.391  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.391  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.391  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.391  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.392  6659  6719 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 09:36:06.392  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.392  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.392  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.392  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.392  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.392  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.392  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.392  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.392  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:36:06.398  6659  6719 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 09:36:06.398  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.398  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.398  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.399  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.399  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.399  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.399  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.399  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.399  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.400  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:36:06.403  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:36:06.403  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:36:06.403  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:36:06.404  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:36:06.404  6659  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:36:06.405  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.405  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.405  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.405  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.405  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.405  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.405  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.407  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.407  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.408  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:06.409  6659  6719 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:36:06.409  6659  6719 D io.jxc,ore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 09:36:06.421  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 09:36:06.423  6659  6719 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 09:36:06.424  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:36:06.424  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:36:06.424  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:36:06.425  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections:, Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:36:06.426  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 09:36:06.426  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 09:36:06.426  6659  6719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:36:06.427  6659  6719 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 09:36:06.427  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:06.428  6659  6719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:36:06.429  6659  6719 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 09:36:06.429  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:06.429  6659  6719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:36:06.429  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 09:36:06.432  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 09:36:06.434  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 09:36:06.434  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 09:36:06.435  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 09:36:06.435  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 09:36:06.435  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 09:36:06.435  6659  6719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:06.435  6659  6719 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 09:36:06.436  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.436  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.436  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.436  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 09:36:06.436  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.436  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.437  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.437  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop,
09-07 09:36:06.437  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.437  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:36:06.448  6659  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 864)
09-07 09:36:06.458  6659  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 864
09-07 09:36:06.459  6659  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 864)
09-07 09:36:06.459  6659  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 864)
,09-07 09:36:06.461  6659  6719 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 09:36:06.462  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.462  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.462  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.462  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.462  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.462  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.462  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.462  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.463  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.464  6659  6719 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 09:36:06.464  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.464  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.464  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.464  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.465  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.465  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.465  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.465  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.465  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.467  6659  6719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 09:36:06.467  6659  6719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 09:36:06.467  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:36:06.467  6659  6719 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 09:36:06.467  6659  6719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:36:06.467  6659  6719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 09:36:06.467  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:36:06.468  6659  6719 I io.jxcore.,node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 09:36:06.468  6659  6719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:36:06.468  6659  6719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:36:06.468  6659  6719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:36:06.468  6659  6719 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 09:36:06.468  6659  6719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:06.468  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.468  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.468  6659  6719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20047f2a not in the list
09-07 09:36:06.468  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:06.468  6659  6719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@525211b not in the list
09-07 09:36:06.468  6659  6719 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:06.468  6659  6719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:06.469  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:06.469  6659  6719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:36:06.472  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:36:06.482  6659  6719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:36:06.483  6659  6719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:06.483  6659  6719 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:36:06.485  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:36:06.489  6659  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:36:06.489  6659  6719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:36:06.489  6659  6719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:36:06.489  6659  6719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:36:06.489  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:36:06.489  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:36:06.495  6659  6719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:36:06.495  6659  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:06.497  6659  6719 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 09:36:06.499  6659  6719 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:36:06.602  6659  6734 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-07 09:36:06.603  6659  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 864)
,09-07 09:36:13.738  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:36:13.762  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1465ad41 type 2 when 206996 com.google.android.gms} when 206996
,09-07 09:36:13.805  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:36:13.830  1830  1830 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 09:36:13.835  2233  2233 I ConfigService: onCreate
09-07 09:36:13.835  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 09:36:13.844  2233  2233 I ConfigService: onBind returning update interface
,09-07 09:36:13.870  1830  6754 I ConfigFetchService: running network task: configservice_periodic
,09-07 09:36:13.873  1830  1830 I ConfigFetchService: service connected
09-07 09:36:13.873  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 09:36:13.874  2233  2233 I ConfigService: onBind returning config service
09-07 09:36:13.889  1830  6754 I ConfigFetchService: launchTask
,09-07 09:36:13.897  1830  1830 I ConfigClient: service connected
09-07 09:36:13.918  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
,09-07 09:36:13.968  1035  2079 V SIM_STK : Menu title from STK is T-Mobile
,09-07 09:36:13.979  1830  3983 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 09:36:13.982   311  6773 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 09:36:13.982   311  6773 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 09:36:13.982   311  6773 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 09:36:14.193  1830  3983 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 09:36:14.196  1830  1830 I ConfigFetchService: fetch service done; releasing wakelock
09-07 09:36:14.199  1830  1830 I ConfigFetchService: stopping self
09-07 09:36:14.246  2233  2233 I ConfigService: onDestroy
,09-07 09:36:41.039  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2d636f58 type 2 when 224938 android} when 224938
,09-07 09:36:55.251  1582  1582 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:36:55.251  1582  1582 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:36:55.264  1035  1529 D WifiController: battery changed pluggedType: 2
,09-07 09:36:55.268  1582  1582 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
09-07 09:36:55.269  1582  1582 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:36:55.271  1963  2140 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:36:55.271  1963  2140 D LEDHandler: Battery Level Remaining: 100%
09-07 09:36:55.271  1963  2140 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
09-07 09:36:55.273  1582  1582 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:36:55.277  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:36:55.278  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:36:55.281  3873  3995 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:36:55.285  6525  6525 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:37:00.054  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:37:00.054  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:37:00.054  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:37:00.055  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:37:00.066  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:37:00.066  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:37:00.069  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:37:00.070  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:38:00.108  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:38:00.108  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:38:00.109  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:38:00.109  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:38:00.120  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:38:00.120  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:38:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:38:00.124  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:38:14.212  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:38:14.226  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{155368b1 type 2 when 327471 com.google.android.gms} when 327471
09-07 09:38:14.286  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:38:14.310  2233  2233 I ConfigService: onCreate
09-07 09:38:14.310  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-07 09:38:14.315  1830  1830 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 09:38:14.326  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
,09-07 09:38:14.337  1830  6784 I ConfigFetchService: running network task: configservice_periodic
09-07 09:38:14.339  1830  6784 I ConfigFetchService: launchTask
,09-07 09:38:14.341  2233  2233 I ConfigService: onBind returning update interface
09-07 09:38:14.342  1830  1830 I ConfigFetchService: service connected
09-07 09:38:14.343  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 09:38:14.343  2233  2233 I ConfigService: onBind returning config service
09-07 09:38:14.344  1830  1830 I ConfigClient: service connected
09-07 09:38:14.415  1035  2080 V SIM_STK : Menu title from STK is T-Mobile
,09-07 09:38:14.427  1830  4018 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 09:38:14.431   311  6800 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 09:38:14.431   311  6800 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 09:38:14.431   311  6800 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 09:38:14.638  1830  4018 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 09:38:14.641  1830  1830 I ConfigFetchService: fetch service done; releasing wakelock
09-07 09:38:14.643  1830  1830 I ConfigFetchService: stopping self
09-07 09:38:14.704  2233  2233 I ConfigService: onDestroy
,09-07 09:38:22.031  1035  3551 I LocationManagerService: remove 3aeda182
09-07 09:38:22.032  1035  3551 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-07 09:38:22.032  1035  3551 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 09:38:22.034  1035  3551 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 09:38:22.035  1035  3551 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
09-07 09:38:22.036  1035  3551 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,09-07 09:39:00.002  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:39:00.049  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:39:00.062  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:39:00.062  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:39:00.062  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:39:00.062  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:39:00.069  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:39:00.069  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:39:00.070  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:39:00.072  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:39:00.114  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
,09-07 09:40:00.097  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:40:00.097  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:40:00.098  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:40:00.098  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:40:00.109  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:40:00.110  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:40:00.112  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:40:00.114  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:41:00.109  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:41:00.109  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:41:00.110  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:41:00.110  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:41:00.122  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:41:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:41:00.125  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:41:00.128  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:42:00.111  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:42:00.111  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:42:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:42:00.112  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:42:00.123  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:42:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:42:00.126  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:42:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:42:14.655  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:42:14.669  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{5bd5e88 type 2 when 567914 com.google.android.gms} when 567914
09-07 09:42:14.714  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:42:14.738  1830  1830 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 09:42:14.743  2233  2233 I ConfigService: onCreate
09-07 09:42:14.744  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 09:42:14.756  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
09-07 09:42:14.761  1830  6817 I ConfigFetchService: running network task: configservice_periodic
09-07 09:42:14.768  1830  6817 I ConfigFetchService: launchTask
,09-07 09:42:14.771  2233  2233 I ConfigService: onBind returning update interface
09-07 09:42:14.772  1830  1830 I ConfigFetchService: service connected
09-07 09:42:14.772  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 09:42:14.772  2233  2233 I ConfigService: onBind returning config service
09-07 09:42:14.773  1830  1830 I ConfigClient: service connected
09-07 09:42:14.848  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
,09-07 09:42:14.860  1830  6356 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 09:42:14.864   311  6835 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 09:42:14.864   311  6835 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-07 09:42:14.908   311  6835 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 09:42:15.270  1830  6356 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 09:42:15.279  1830  1830 I ConfigFetchService: fetch service done; releasing wakelock
09-07 09:42:15.282  1830  1830 I ConfigFetchService: stopping self
09-07 09:42:15.329  2233  2233 I ConfigService: onDestroy
,09-07 09:42:56.210  1582  1582 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:42:56.210  1582  1582 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:42:56.225  1035  1529 D WifiController: battery changed pluggedType: 2
,09-07 09:42:56.229  1963  2140 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:42:56.229  1963  2140 D LEDHandler: Battery Level Remaining: 100%
09-07 09:42:56.229  1963  2140 D LEDHandler: Battery Temp: 269, mChargingStatus=5, mChargingStop=false
09-07 09:42:56.231  1582  1582 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
09-07 09:42:56.231  1582  1582 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:56.233  1582  1582 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:56.235  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:42:56.235  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:42:56.236  3873  3995 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:42:56.243  6525  6525 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:43:00.056  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:43:00.056  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:43:00.056  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:43:00.057  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:43:00.069  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:43:00.069  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:43:00.070  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:43:00.071  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:43:33.284  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:43:33.329  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:43:33.356  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
,09-07 09:43:39.977  1582  1582 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:39.978  1582  1582 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:43:39.988  1582  1582 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
09-07 09:43:39.990  1035  1529 D WifiController: battery changed pluggedType: 2
,09-07 09:43:39.995  1963  2140 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:39.995  1963  2140 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:39.995  1963  2140 D LEDHandler: Battery Temp: 268, mChargingStatus=5, mChargingStop=false
09-07 09:43:39.996  1582  1582 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:39.997  1582  1582 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:40.000  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:40.000  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:40.001  3873  3995 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:43:40.005  6525  6525 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 09:44:00.069  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:44:00.069  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:44:00.069  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:44:00.070  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:44:00.081  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:44:00.081  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:44:00.084  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:44:00.086  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:44:37.151  1035  2036 I ActivityManager: Killing 5843:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-07 09:44:37.209  1035  1560 W libprocessgroup: failed to open /acct/uid_10014/pid_5843/cgroup.procs: No such file or directory
,09-07 09:45:00.109  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:45:00.109  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:45:00.110  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:45:00.110  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:45:00.122  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:45:00.122  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:45:00.124  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:45:00.126  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:45:01.840  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:45:01.912  1035  1098 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6850 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-07 09:45:01.943  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:45:02.054  6850  6850 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 09:45:02.059  6850  6850 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@90cf99c
09-07 09:45:02.060  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
09-07 09:45:02.060  1035  1750 I ActivityManager: Killing 6191:com.android.defcontainer/u0a4 (adj 15): empty #17
09-07 09:45:02.162  1035  1050 W libprocessgroup: failed to open /acct/uid_10004/pid_6191/cgroup.procs: No such file or directory
,09-07 09:46:00.108  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:46:00.108  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:46:00.109  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:46:00.109  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:46:00.121  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:46:00.121  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:46:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:46:00.125  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:47:00.110  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:47:00.110  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:47:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:47:00.111  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:47:00.123  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:47:00.124  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:47:00.126  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:47:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:47:49.071  1582  1582 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:47:49.072  1582  1582 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:47:49.094  1963  2140 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:47:49.094  1963  2140 D LEDHandler: Battery Level Remaining: 100%
09-07 09:47:49.094  1963  2140 D LEDHandler: Battery Temp: 266, mChargingStatus=5, mChargingStop=false
,09-07 09:47:49.098  1582  1582 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
09-07 09:47:49.098  1582  1582 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:47:49.100  1035  1529 D WifiController: battery changed pluggedType: 2
09-07 09:47:49.103  1582  1582 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:47:49.106  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:47:49.106  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:47:49.109  3873  3995 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:47:49.113  6525  6525 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:48:00.062  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:48:00.063  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:48:00.063  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:48:00.063  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:48:00.075  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:48:00.075  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:48:00.079  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:48:00.079  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:48:28.934  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:48:28.953  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39a8941b type 2 when 942194 com.android.bluetooth} when 942194
,09-07 09:48:28.960  3873  4094 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 09:48:28.960  3873  4094 W bt-smp  : Plain text(LSB ~ MSB) = ac ca 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 09:48:28.960  3873  4094 W bt-smp  : Encrypted text(LSB ~ MSB) = 1d 69 44 84 5f 51 8b a3 ca 31 1c ea 51 c3 03 3b 
09-07 09:48:28.960  3873  4094 W bt-btm  : Stopping oneshot timer
09-07 09:48:28.997  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:48:29.024  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
,09-07 09:49:00.082  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:49:00.082  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:49:00.082  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:49:00.082  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:49:00.094  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:49:00.094  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:49:00.097  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:49:00.099  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:50:00.110  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:50:00.111  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:50:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:50:00.111  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:50:00.123  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:50:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:50:00.125  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:50:00.128  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:50:05.575  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=915074275, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-07 09:50:05.588  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11c979b8 type 2 when 985906 com.google.android.gms} when 985906
,09-07 09:50:05.621  2596  2596 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 09:50:05.647  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=915074275 [*alarm*], flags=0x0
,09-07 09:50:05.668  2233  6166 D GCM     : Message class com.google.e.a.a.h
09-07 09:50:35.684  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{122f1391 type 2 when 1068937 com.google.android.gms} when 1068937
,09-07 09:50:35.740  1830  1830 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 09:50:35.746  2233  2233 I ConfigService: onCreate
09-07 09:50:35.747  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 09:50:35.748  1830  6903 I ConfigFetchService: running network task: configservice_periodic
09-07 09:50:35.756  1830  6903 I ConfigFetchService: launchTask
,09-07 09:50:35.760  2233  2233 I ConfigService: onBind returning update interface
09-07 09:50:35.762  2233  2233 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,09-07 09:50:35.762  2233  2233 I ConfigService: onBind returning config service
09-07 09:50:35.764  1830  1830 I ConfigFetchService: service connected
09-07 09:50:35.764  1830  1830 I ConfigClient: service connected
09-07 09:50:35.854  1035  1725 V SIM_STK : Menu title from STK is T-Mobile
,09-07 09:50:35.869  1830  2358 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 09:50:35.877   311  6912 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 09:50:35.877   311  6912 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-07 09:50:35.926   311  6912 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 09:50:36.236  1830  2358 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 09:50:36.240  1830  1830 I ConfigFetchService: fetch service done; releasing wakelock
09-07 09:50:36.242  1830  1830 I ConfigFetchService: stopping self
09-07 09:50:36.281  2233  2233 I ConfigService: onDestroy
,09-07 09:51:00.097  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:51:00.097  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:51:00.098  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:51:00.098  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:51:00.110  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:51:00.110  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:51:00.112  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:51:00.114  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:52:00.111  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:52:00.111  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:52:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:52:00.112  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:52:00.124  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:52:00.124  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:52:00.127  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:52:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:53:00.112  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:53:00.112  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:53:00.112  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:53:00.113  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:53:00.124  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:53:00.125  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:53:00.128  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:53:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:53:06.755  1035  1097 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 09:54:00.110  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:54:00.110  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:54:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:54:00.111  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:54:00.123  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:54:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:54:00.125  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:54:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:55:00.112  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:55:00.112  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:55:00.112  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:55:00.113  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:55:00.124  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:55:00.124  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:55:00.126  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:55:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:56:00.111  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:56:00.111  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:56:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:56:00.112  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:56:00.123  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:56:00.124  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:56:00.126  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:56:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:57:00.111  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:57:00.111  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:57:00.111  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:57:00.112  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:57:00.124  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:57:00.124  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:57:00.126  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:57:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:58:00.112  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:58:00.112  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:58:00.112  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:58:00.113  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:58:00.124  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:58:00.125  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:58:00.128  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:58:00.129  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 09:59:00.110  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:59:00.110  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:59:00.110  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 09:59:00.111  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:59:00.123  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:59:00.123  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:59:00.125  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:59:00.128  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,TIME-OUT KILL (timeout was 1400000ms)
```
