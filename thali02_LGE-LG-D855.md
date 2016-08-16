#### Test 8149356279477ac_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 17:59:31.288  6767  6767 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 17:59:45.471  7027  7027 D AndroidRuntime: 
08-16 17:59:45.471  7027  7027 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:59:45.476  7027  7027 D AndroidRuntime: CheckJNI is OFF
08-16 17:59:45.680  7027  7027 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 17:59:45.690  1028  2043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 17:59:45.706  1936  1951 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 17:59:45.712  1028  2043 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 17:59:45.714  1028  2043 D ActivityManager: setTaskToReturnTo : TaskRecord{1fed32ba #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 17:59:45.714  1028  2043 D ActivityManager: setTaskToReturnTo : TaskRecord{1fed32ba #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 17:59:45.716  1028  2043 D WindowStateEx: AppWindowTokenEx init.. 
08-16 17:59:45.717   342   352 E GBMv2   : DFP En is all cleared set to be enabled
08-16 17:59:45.746  1028  2043 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7042 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:59:45.748  7027  7027 D AndroidRuntime: Shutting down VM
08-16 17:59:45.805  1936  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 17:59:45.805  1936  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1bd8577e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 17:59:45.807  1936  3965 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 17:59:45.807  1936  3965 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f39d4df co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 17:59:45.854  7042  7042 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 17:59:45.925  7042  7042 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 17:59:45.932  7042  7042 I LibraryLoader: Loading: webviewchromium
08-16 17:59:45.934  7042  7042 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3051-3054)
08-16 17:59:45.935  7042  7042 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:59:45.950  7042  7042 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1db8c6ae}
08-16 17:59:45.952  7042  7042 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:59:45.952  7042  7042 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:59:45.963  7042  7042 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 17:59:45.964  7042  7042 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:59:45.977  7042  7042 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 17:59:45.977  7042  7042 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 17:59:45.978  7042  7042 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 17:59:45.978   319   319 V AudioPolicyService: registerClient() client 0xb1427180, uid 10118
08-16 17:59:45.986  1028  1110 D BluetoothManagerService: Message: 20
08-16 17:59:45.986  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11eaa974:true
08-16 17:59:45.995  7042  7042 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 17:59:45.995  7042  7042 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 17:59:45.995  7042  7042 I Adreno-EGL: Build Date: 12/12/14 금
08-16 17:59:45.995  7042  7042 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 17:59:45.995  7042  7042 I Adreno-EGL: Remote Branch: 
08-16 17:59:45.995  7042  7042 I Adreno-EGL: Local Patches: 
08-16 17:59:45.995  7042  7042 I Adreno-EGL: Reconstruct Branch: 
,08-16 17:59:46.068  7042  7088 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 17:59:46.073  7042  7042 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 17:59:46.089  7042  7042 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:59:46.093  7042  7042 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 17:59:46.096  7042  7042 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 17:59:46.099  7042  7042 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 17:59:46.099  7042  7042 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 17:59:46.112  7042  7042 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 17:59:46.119  7042  7042 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:59:46.119  7042  7042 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:59:46.167  7042  7104 D OpenGLRenderer: Render dirty regions requested: true
08-16 17:59:46.167  7042  7104 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 17:59:46.176  7042  7104 D OpenGLRenderer: Enabling debug mode 0
,08-16 17:59:46.185  7042  7042 D Atlas   : Validating map...
08-16 17:59:46.196  1028  1935 D SplitWindow: check instance of lgWin Window{34a170e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 17:59:46.269  7042  7099 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 17:59:46.270  7042  7099 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:59:46.275  7042  7042 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a3c5555 time:203395
,08-16 17:59:46.299  1028  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +500ms (total +582ms)
,08-16 17:59:46.301  1028  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{134f756b u0 com.test.thalitest/.MainActivity t6} time:203421
08-16 17:59:46.425  7042  7042 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 17:59:46.425  7042  7042 I chromium: 
,08-16 17:59:46.467  7042  7042 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:59:46.645  7042  7118 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-16 17:59:46.663  7042  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
08-16 17:59:46.663  7042  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:59:46.663  7042  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:59:46.663  7042  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:59:46.663  7042  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 17:59:46.663  7042  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37280a09 added. We now have 1 listener(s)
,08-16 17:59:46.669  1028  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:46.672  7042  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 17:59:46.673  7042  7118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:59:46.675  7042  7118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:59:46.675  7042  7118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:59:46.683  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 17:59:46.684  7042  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3416dc3c added. We now have 1 listener(s)
08-16 17:59:46.684  7042  7118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:59:46.691  1028  1539 D WifiService: New client listening to asynchronous messages
,08-16 17:59:46.696  7042  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:59:46.696  7042  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 17:59:46.697  7042  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 17:59:46.697  7042  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 17:59:46.697  7042  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:59:46.747   342   354 E GBMv2   : DFP En is all cleared set to be enabled
08-16 17:59:46.747   342   354 E GBMv2   : Set value is all cleared set the max
08-16 17:59:46.747   342   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 17:59:46.870  1028  1935 I art     : Explicit concurrent mark sweep GC freed 30312(1487KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.260ms total 167.851ms
,08-16 17:59:46.876  7042  7118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:46.877  1028  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:46.880  7042  7118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 17:59:46.894  7042  7118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:46.894  7042  7118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:59:46.894  7042  7118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:59:46.895  7042  7118 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:59:46.900  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:46.902  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:46.903  7042  7118 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:59:46.939  7042  7099 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 17:59:46.939  7042  7099 I chromium: 
,08-16 17:59:47.018  7042  7042 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:59:47.932  7042  7121 W jxcore-log: Initializing JXcore engine
,08-16 17:59:47.932  7042  7121 W jxcore-log: JXcore engine is ready
,08-16 17:59:47.998  7121  7121 W Thread-817: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10340]" dev="sockfs" ino=10340 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 17:59:47.998  7121  7121 W Thread-817: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 17:59:47.998  7121  7121 W Thread-817: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10117]" dev="sockfs" ino=10117 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 17:59:47.998  7121  7121 W Thread-817: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 17:59:47.998  7121  7121 W Thread-817: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31359]" dev="sockfs" ino=31359 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-16 17:59:48.032  7042  7121 W jxcore-log: Starting JXcore engine
,08-16 17:59:48.197  7042  7121 W jxcore-log: Platform android
08-16 17:59:48.197  7042  7121 W jxcore-log: 
08-16 17:59:48.197  7042  7121 W jxcore-log: Process ARCH arm
08-16 17:59:48.197  7042  7121 W jxcore-log: 
,08-16 17:59:48.462  7042  7121 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:59:48.462  7042  7121 I jxcore-log: 
08-16 17:59:48.462  7042  7121 W jxcore-log: JXcore engine is started
,08-16 17:59:48.475  7042  7118 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:59:48.484  7042  7042 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:59:58.231  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:59:58.231  7042  7121 I jxcore-log: 
08-16 17:59:58.233  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:59:58.233  7042  7121 I jxcore-log: 
,08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:58.236  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:59:58.239  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.241  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:59:58.241  7042  7121 I jxcore-log: 
08-16 17:59:58.243  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:59:58.243  7042  7121 I jxcore-log: 
08-16 17:59:58.557  7042  7121 D ExecuteNativeTests: Running unit tests
,08-16 17:59:58.625  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:59:58.625  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 added. We now have 2 listener(s)
08-16 17:59:58.626  1028  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.627  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:59:58.627  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:59:58.627  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:59:58.627  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:59:58.627  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 added. We now have 2 listener(s)
08-16 17:59:58.627  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:59:58.628  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:59:58.630  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:58.632  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:59:58.632  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:59:58.633  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:59:58.634  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:59:58.635  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:59:58.637  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-16 17:59:58.638  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:59:58.638  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-16 17:59:58.639  7042  7121 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
08-16 17:59:58.640  7042  7121 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
,08-16 17:59:58.640  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:59:58.640  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:59:58.640  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:59:58.641  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.641  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:59:58.641  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.642  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.642  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:59:58.642  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.642  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:59:58.642  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 removed from the list
08-16 17:59:58.642  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.642  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 removed from the list,
08-16 17:59:58.642  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.642  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.643  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.643  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:59:58.644  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.644  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.644  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.644  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.646  7042  7121 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 17:59:58.646  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:59:58.646  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.646  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.646  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.646  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.646  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.646  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
,08-16 17:59:58.646  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.646  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.646  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.646  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.646  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.646  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.646  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:59:58.647  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.647  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.647  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.647  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:59:58.651  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:59:58.652  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:59:58.653  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 17:59:58.653  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:59:58.653  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:59:58.653  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:59:58.653  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:59:58.653  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.653  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.653  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 17:59:58.654  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.654  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.654  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.654  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.654  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.654  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.654  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:59:58.654  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.654  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.655  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.655  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.655  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.655  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.655  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:59:58.655  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.656  7042  7121 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:59:58.658  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:58.660  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:59:58.661  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.661  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:59:58.662  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.663  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.663  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:59:58.664  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:59:58.664  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:59:58.664  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.664  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:59:58.666  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:59:58.666  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.670  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:59:58.674  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:59:58.675  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
08-16 17:59:58.676  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:59:58.677  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.678  7042  7121 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:59:58.678  7042  7121 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:59:58.680  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.680  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.680  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:59:58.680  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.680  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.680  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.680  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.680  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.680  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.680  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:59:58.680  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.681  7042  7121 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:59:58.682  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-16 17:59:58.684  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:59:58.685  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.685  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:59:58.686  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:59:58.687  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.687  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:59:58.687  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:59:58.687  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:59:58.687  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.687  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:59:58.690  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:59:58.690  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.691  7042  7121 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:59:58.691  7042  7121 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:59:58.692  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.692  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.692  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.692  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.692  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.692  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.692  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.692  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.692  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.693  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.693  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.693  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.693  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.693  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.693  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.694  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.694  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.695  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.695  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.695  7042  7121 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:59:58.696  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:58.698  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:59:58.699  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.699  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:59:58.700  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.701  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:59:58.701  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:59:58.701  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:59:58.701  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.701  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:59:58.702  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.704  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:59:58.704  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.705  7042  7121 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:59:58.705  7042  7121 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:59:58.705  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.705  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.705  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.705  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.705  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.705  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.706  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.706  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probab,ly already removed
08-16 17:59:58.706  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:59:58.706  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.706  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.706  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.706  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.706  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.706  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.706  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.707  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.707  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.707  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.707  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.707  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.707  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.708  7042  7121 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 17:59:58.708  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.708  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.708  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.708  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.708  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.708  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.708  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.708  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.708  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.708  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.708  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.708  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.708  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.708  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.709  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.709  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.709  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.709  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.709  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.709  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.710  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:59:58.710  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.710  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.710  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.711  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.711  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.711  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.711  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.711  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.711  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.711  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.711  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.711  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.711  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.711  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.711  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.711  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.712  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.712  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.712  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.712  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.712  7042  7121 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:59:58.712  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.713  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.713  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.713  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.713  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.713  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.713  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.713  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.713  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.713  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.713  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.713  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.713  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.713  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.714  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.714  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.714  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.714  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.714  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.714  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.715  7042  7121 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 17:59:58.715  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.715  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.715  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.715  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.715  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.715  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.715  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.715  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.715  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.715  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.715  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.715  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.715  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.715  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.716  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.716  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.716  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.716  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.716  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.716  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.717  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:59:58.717  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:59:58.717  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:59:58.717  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:59:58.717  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:59:58.717  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:59:58.717  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.717  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.717  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.718  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.718  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.718  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.718  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.718  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.719  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.719  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.719  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.719  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.719  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.719  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.720  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.720  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.721  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.721  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.721  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.721  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.721  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:59:58.721  7042  7121 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:59:58.722  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:59:58.723  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:59:58.723  7042  7121 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:59:58.723  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:59:58.724  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:59:58.724  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:59:58.724  7042  7121 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:59:58.724  7042  7121 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:59:58.724  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:59:58.724  7042  7121 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:59:58.724  7042  7121 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:59:58.724  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:59:58.724  7042  7121 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:59:58.724  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:59:58.727  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:59:58.736  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:59:58.736  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:59:58.740  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:59:58.740  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:59:58.740  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:59:58.740  7042  7121 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:59:58.740  7042  7121 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:59:58.740  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.740  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.740  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:59:58.741  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.741  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.741  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.741  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:59:58.743  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.743  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.743  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.743  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.743  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.743  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.743  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.743  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.743  7042  7137 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 881)
08-16 17:59:58.744  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.744  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.744  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.744  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.744  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.744  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.745  7042  7138 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 881
08-16 17:59:58.746  7042  7121 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:59:58.746  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.746  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.746  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.746  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.746  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.746  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.746  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.746  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.746  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.746  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.746  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.746  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.746  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.746  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.747  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.747  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.747  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.747  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.747  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.747  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.748  7042  7121 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:59:58.748  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.748  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.748  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.749  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.749  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.749  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.749  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.749  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.749  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.749  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.749  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.749  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.749  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.749  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.750  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.750  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.751  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.751  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.751  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.751  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.751  7042  7121 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:59:58.751  7042  7121 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:59:58.751  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:59:58.752  7042  7121 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:59:58.752  7042  7121 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:59:58.752  7042  7121 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:59:58.752  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:59:58.752  7042  7121 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:59:58.752  7042  7121 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:59:58.752  7042  7121 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:59:58.752  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:59:58.752  7042  7121 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:59:58.752  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.752  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.752  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.753  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.753  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.753  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.753  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.753  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.753  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.753  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.753  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.753  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.753  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.753  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.754  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.754  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.754  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.754  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.754  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.754  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.754  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.755  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.755  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.755  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.755  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.755  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.755  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.755  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.755  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.755  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.755  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.755  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.755  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.755  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.755  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.755  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.755  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.755  7042  7121 V io.jxcore.node.StartStopOperationHandler: execut,eCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.756  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.756  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.756  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.756  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.756  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.756  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.756  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.756  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.756  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.756  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.756  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.756  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.756  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.757  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.757  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.757  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.757  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.758  7042  7121 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:59:58.758  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.770  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:59:58.770  7042  7121 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:59:58.770  7042  7121 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:59:58.771  7042  7042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:59:58.771  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:59:58.771  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:59:58.772  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.772  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:59:58.772  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:59:58.772  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:59:58.772  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.772  7042  7121 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:59:58.773  7042  7042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:59:58.773  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.773  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.773  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:59:58.773  7042  7121 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:59:58.773  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:59:58.773  1028  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.774  7042  7139 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:59:58.774  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:59:58.775  3864  3881 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 17:59:58.775  7042  7139 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 17:59:58.775  7042  7139 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:59:58.775  7042  7139 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:59:58.776  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 17:59:58.776  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:59:58.776  7042  7121 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:59:58.777  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.777  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.778  7042  7121 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:59:58.778  7042  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:59:58.778  7042  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:59:58.778  7042  7042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:59:58.778  7042  7042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:59:58.778  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.778  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.778  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.778  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.779  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.779  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.779  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.779  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.779  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.779  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.779  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:59:58.779  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.779  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.779  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.779  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 17:59:58.779  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.779  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.779  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.779  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.780  7042  7121 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:59:58.780  7042  7121 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:59:58.780  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:59:58.780  7042  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:59:58.780  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.780  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.780  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.781  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.781  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.781  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.781  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.781  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.781  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.781  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.781  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.781  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.781  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.781  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.781  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.781  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.781  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.781  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.782  1028  2043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.783  1028  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.783  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.784  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.784  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:59:58.784  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.784  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.784  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.784  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.784  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.784  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.784  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.784  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:59:58.784  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.784  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.784  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.784  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.785  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.785  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.785  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.785  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.785  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:59:58.785  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:59:58.785  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:59:58.786  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:59:58.786  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.786  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.786  7042  7121 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb30d47 not in the list
08-16 17:59:58.786  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.786  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.786  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 17:59:58.786  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.786  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.786  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:59:58.786  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:59:58.787  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:59:58.787  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:59:58.787  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:59:58.787  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c327974 not in the list
08-16 17:59:58.788  7042  7121 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:59:58.788  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:59:58.788  7042  7121 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:59:58.788  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:59:58.788  7042  7121 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-16 17:59:58.788  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:59:58.789  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:59:58.789  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 17:59:58.790  7042  7121 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1,
08-16 17:59:58.790  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:59:58.790  7042  7121 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:59:58.790  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:59:58.790  7042  7121 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:59:58.790  7042  7121 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:59:58.791  7042  7121 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:59:58.791  7042  7121 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:59:58.791  7042  7121 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:59:58.791  7042  7121 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-16 17:59:58.791  7042  7121 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:59:58.791  7042  7121 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:59:58.792  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:59:58.792  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a50a455 added. We now have 2 listener(s)
08-16 17:59:58.792  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:59:58.793  7042  7121 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 17:59:58.794  1028  1989 D WifiServiceImplEx: setWifiEnabled: true pid=7042, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 17:59:58.794  1028  1989 D WifiService: setWifiEnabled: true pid=7042, uid=10118
08-16 17:59:58.794  1028  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:59:58.795  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:59:58.795  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15260e6a added. We now have 3 listener(s)
08-16 17:59:58.795  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:59:58.798  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:59:58.798  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29949f5b added. We now have 4 listener(s)
08-16 17:59:58.798  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:59:58.800  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:59:58.800  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1837c3f8 added. We now have 5 listener(s)
08-16 17:59:58.800  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:59:58.801  1028  1989 D WifiServiceImplEx: setWifiEnabled: false pid=7042, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 17:59:58.802  1028  1989 D WifiService: setWifiEnabled: false pid=7042, uid=10118
08-16 17:59:58.802  1028  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:59:58.812  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:59:58.812  1028  1534 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 17:59:58.812  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 17:59:58.812  1028  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 17:59:58.812  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:59:58.812  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 17:59:58.812  1028  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 17:59:58.813  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 17:59:58.813  1028  1534 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:59:58.813  1028  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:59:58.813  1028  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:59:58.813  1028  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:59:58.813  1028  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:59:58.813  1028  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 17:59:58.813  1028  2026 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@11054fe9 mBinding = false
,08-16 17:59:58.819  1028  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 17:59:58.819  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:59:58.820  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.820  2712  2712 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:59:58.820  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.820  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:59:58.820  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:59:58.820  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:59:58.820   309   886 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:59:58.820  1028  2863 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.828  7042  7137 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 17:59:58.828  7042  7137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:59:58.829  3864  3880 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:59:58.829  3864  4060 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,08-16 17:59:58.835  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:59:58.835  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:59:58.835  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 17:59:58.836  1028  1110 D BluetoothManagerService: Message: 2
08-16 17:59:58.836  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:59:58.837  1028  1110 D BluetoothManagerService: Sending off request.
08-16 17:59:58.837  3864  4242 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 17:59:58.838  3864  3951 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 17:59:58.838  3864  3951 D BluetoothAdapterProperties: Setting state to 13
08-16 17:59:58.838  3864  3951 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:59:58.838  3864  3951 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:59:58.838  3864  3951 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 17:59:58.841  3864  3954 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:59:58.841  3864  3951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:59:58.841  3864  3951 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 17:59:58.842  3864  4246 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 17:59:58.843  3864  4247 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:59:58.843  3864  4267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:59:58.843  3864  4289 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:59:58.844  3864  4291 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:59:58.844  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 17:59:58.844  3864  4060 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 17:59:58.845  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 17:59:58.845  3864  4060 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 17:59:58.850  7042  7137 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 881)
08-16 17:59:58.850  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.850  7042  7121 V io.j,xcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:58.850  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:59:58.851  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.851  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:59:58.854  1028  1110 D BluetoothManagerService: Message: 60
08-16 17:59:58.854  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 17:59:58.854  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-16 17:59:58.856  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:59:58.862  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:59:58.862  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:59:58.864  1028  1640 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-16 17:59:58.867  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 17:59:58.867  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.867  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.867  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 17:59:58.867  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 17:59:58.867  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.867  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 17:59:58.874  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.874  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:59:58.876  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:59:58.876  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:59:58.879  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:59:58.879  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:59:58.879  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.879  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:59:58.880  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.888  1028  1103 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7145 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 17:59:58.891  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:58.891  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:59:58.891  3864  3864 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:58.892  3864  3864 D BluetoothMapService: STATE_TURNING_OFF
08-16 17:59:58.892  3864  3864 V BtOppService: Receiver DISABLED_ACTION 
08-16 17:59:58.892  3864  3864 V BluetoothMapService: Handler(): got msg=4
08-16 17:59:58.892  3864  3864 D BluetoothMapService: MAP Service closeService in
08-16 17:59:58.892  3864  3864 D BluetoothMapMasInstance: MAP Service shutdown
08-16 17:59:58.892  3864  3864 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:59:58.892  3864  3864 V BluetoothMapService: MAP Service closeService out
08-16 17:59:58.892  3864  3864 I BtOppRfcommListener: stopping Accept Thread
08-16 17:59:58.892  3864  3864 V BtOppRfcommListener: close mBtServerSocket
08-16 17:59:58.893  3864  3864 V BtOppRfcommListener: waiting for thread to terminate
08-16 17:59:58.893  3864  4267 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:59:58.893  3864  3864 V BtOppRfcommListener: done waiting for thread to terminate
08-16 17:59:58.894  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.894  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:58.921  1028  1540 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 17:59:58.921  1028  1540 D DSQN    : disableDataServiceNotify
08-16 17:59:58.921  1028  1540 D DSQN    : stop dsqn bin
08-16 17:59:58.922   309  7164 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 17:59:58.924  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 17:59:58.924  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 17:59:58.927  1028  1540 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 17:59:58.927  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:59:58.927  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:59:58.927  1028  1540 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:59:58.927  1028  1540 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 17:59:58.927  1028  1540 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 17:59:58.927  1028  1540 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 17:59:58.928  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:59:58.928  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.928  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.928  1028  2861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 17:59:58.929  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:59:58.934  1028  1103 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7165 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 17:59:58.935  3864  3864 V BtOppService: onDestroy
08-16 17:59:58.936  3864  3864 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 17:59:58.943  1028  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:59:58.943  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 17:59:58.943  1028  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:59:58.944  1028  1540 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:59:58.944  1028  1540 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:59:58.944  1028  1540 D NetworkManagementService: Removing idletimer
08-16 17:59:58.944  1028  1540 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:58.946  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 17:59:58.946  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 17:59:58.946  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:59:58.946  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:59:58.946  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:59:58.946  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:59:58.946  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:59:58.946  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:59:58.947  1028  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 17:59:58.947  1028  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 17:59:58.947  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.947  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.947  1028  1532 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2905b2fc
08-16 17:59:58.948  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.948  1028  1532 D LGWifiP2pService: P2pDisablingState
08-16 17:59:58.948  1028  1532 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.948  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 17:59:58.948  1028  1532 D LGWifiP2pService: p2p socket connection lost
08-16 17:59:58.948  1028  1532 D LGWifiP2pService: P2pDisabledState
08-16 17:59:58.948  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.949  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.949  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.950  1028  1540 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 17:59:58.950  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.951  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-16 17:59:58.951  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.952  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.952  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:59:58.952  1028  1534 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:59:58.952  1028  1534 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:59:58.953  1028  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:59:58.953  1846  1846 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:59:58.953  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 17:59:58.953  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 17:59:58.953  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:59:58.953  2712  2712 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:59:58.954  1028  1532 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.954  1028  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.954  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:58.954  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:58.955  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:59:58.955  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-16 17:59:58.956  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:58.956  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:59:58.956  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:59:58.956  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:59:58.957  1028  1028 D RttService: SCAN_AVAILABLE : 1
08-16 17:59:58.957  1028  1552 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.957  1028  1553 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:58.958  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:59:58.958  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:59:58.958  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 17:59:58.958  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:59:58.959   309   886 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:59:58.959  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 17:59:58.960  1936  1936 D WfdsService: WifiP2pState is changed : false
08-16 17:59:58.960  1936  2289 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 17:59:58.960  1936  2289 D WfdsService: Set the WFDS Monitor: false
08-16 17:59:58.961  1936  2289 D WfdsMonitor: WFDS Monitor is stopped
08-16 17:59:58.961  1936  2289 D WfdsService: STATE : WfdsDisabledState - enter
08-16 17:59:58.961  1936  2774 D CtrlSupplicant: Received on exit socket, terminate
08-16 17:59:58.961  1936  2774 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 17:59:58.961  1936  2774 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 17:59:58.961  1936  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 17:59:58.961  1936  2774 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 17:59:58.961  1936  2289 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 17:59:58.963  1028  1534 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 17:59:58.964  1028  1534 D WifiNative-p2p0: TERMINATE: returned true
08-16 17:59:58.964  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:59:58.964  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:59:58.964  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:59:58.966  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-16 17:59:58.966  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:58.966  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:58.967  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 17:59:58.970  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 17:59:58.970  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 17:59:58.970  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:59:58.970  1028  1028 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 17:59:58.972  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:59:58.972  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:59:58.972  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.972  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:59:58.974  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:59:58.974  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:59:58.974  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:59:58.974  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:59:58.988  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:59:58.988  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:58.989  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:59:59.010  7165  7165 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:59:59.010  7165  7165 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 17:59:59.011  7165  7165 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:59:59.011  7165  7165 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 17:59:59.011  7165  7165 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 17:59:59.012  7165  7165 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 17:59:59.013  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:59:59.014  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:59.015  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:59.018  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:59:59.018  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:59:59.019  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:59:59.033  1028  2863 D DhcpStateMachine: StoppedState
,08-16 17:59:59.033  1028  2863 D DhcpStateMachine: StoppedState{ when=-75ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:59:59.034  1028  1534 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 17:59:59.034  1028  1534 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 17:59:59.042  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:59:59.042  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:59:59.042  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:59.044  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:59:59.044  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:59:59.045  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:59.046  7145  7145 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 17:59:59.046  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:59.046  7145  7145 W LG Account v2.2: No ProfileInfo entries
08-16 17:59:59.046  7145  7145 I LG Account v2.2: isEnabled: false
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Country: EU
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Operator: OPEN
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Ranking support: false
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Comfort support: false
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Accessory: true
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Health device: true
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Extra Pedometer: false
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Blood glucose device: false
08-16 17:59:59.047  7145  7145 I Feature : [Lifetracker]Device Number: 3
,08-16 17:59:59.057  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:59:59.071  2712  2712 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 17:59:59.071  2712  2712 I wpa_supplicant: monitor socket send errors count : 1
08-16 17:59:59.071  2712  2712 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1936-2\x00 that cannot receive messages
,08-16 17:59:59.073  1028  2768 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 17:59:59.073  1028  2768 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 17:59:59.092  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 17:59:59.101  1028  1641 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7191 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 17:59:59.102  1028  1641 I ActivityManager: Killing 6525:com.lge.email/u0a23 (adj 15): empty #17
08-16 17:59:59.136  2712  2712 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:59:59.137  1028  1989 W libprocessgroup: failed to open /acct/uid_10023/pid_6525/cgroup.procs: No such file or directory
08-16 17:59:59.137  1028  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 17:59:59.137  1028  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:59:59.137  1028  2768 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 17:59:59.138  2712  2712 W wpa_supplicant: USIM:  scard_deinit function
08-16 17:59:59.138  1028  2768 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 17:59:59.138  1028  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:59:59.138  1028  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:59:59.139  1028  1534 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=216247
08-16 17:59:59.141  1028  1534 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=216248
08-16 17:59:59.142  1028  1534 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=216250  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 17:59:59.142  1028  1110 D Tethering: InitialState.processMessage what=4
08-16 17:59:59.143  1028  1534 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=216251  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 17:59:59.144  3864  3864 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 17:59:59.144  3864  3864 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:59.144  3864  3864 V BluetoothPbapReceiver: ***********state = 13
08-16 17:59:59.145  3864  3864 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 17:59:59.145  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:59:59.146  3864  3864 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:59.146  3864  3864 V BluetoothPbapService: state: 13
08-16 17:59:59.146  3864  3864 V BluetoothPbapService: Pbap Service closeService in
08-16 17:59:59.148  1028  1534 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:59:59.149  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:59:59.149  1028  1110 D BluetoothManagerService: Message: 20
08-16 17:59:59.149  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2aed7d88:true
08-16 17:59:59.153  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:59:59.154  3864  3864 V BluetoothPbapService: successfully stopped pbap service
08-16 17:59:59.154  3864  3864 V BluetoothPbapService: Pbap Service closeService out
08-16 17:59:59.155  3864  3864 V BluetoothPbapService: Pbap Service onDestroy
08-16 17:59:59.155  3864  3864 V BluetoothPbapService: Pbap Service closeService in
08-16 17:59:59.155  3864  3864 V BluetoothPbapService: Pbap Service closeService out
08-16 17:59:59.155  3864  3864 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-16 17:59:59.176  1028  1110 D BluetoothManagerService: Message: 30
,08-16 17:59:59.182  1028  1110 D BluetoothManagerService: Message: 30
08-16 17:59:59.186  7165  7165 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 17:59:59.189  7165  7165 D BluetoothMap: Create BluetoothMap proxy object
08-16 17:59:59.189  1028  1110 D BluetoothManagerService: Message: 30
,08-16 17:59:59.196  1028  1110 D BluetoothManagerService: Message: 30
08-16 17:59:59.198  7165  7165 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 17:59:59.200  7165  7165 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 17:59:59.214  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 17:59:59.219  7165  7165 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 17:59:59.219  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:59:59.221  2712  2712 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 17:59:59.221  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:59:59.222  1028  2768 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 17:59:59.222  1028  2768 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 17:59:59.222  1028  2768 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 17:59:59.225  1028  1534 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 17:59:59.228  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 17:59:59.228  1028  1970 I ActivityManager: Killing 2166:com.lge.music/u0a34 (adj 15): empty #17
,08-16 17:59:59.245   319  2183 V AudioFlinger: 2166 died, releasing its sessions
08-16 17:59:59.245   319  2183 V AudioFlinger:  pid 1846 @ 0
,08-16 17:59:59.245   319  2183 V AudioFlinger:  pid 3419 @ 1
,08-16 17:59:59.245   319  2183 V AudioFlinger:  pid 3419 @ 2
08-16 17:59:59.279  7042  7042 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:59:59.281  1028  2043 W libprocessgroup: failed to open /acct/uid_10034/pid_2166/cgroup.procs: No such file or directory
08-16 17:59:59.297  7165  7165 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:59:59.321  7165  7165 D BluetoothInputDevice: Proxy object connected
08-16 17:59:59.322  7165  7165 D HidProfile: Bluetooth service connected
,08-16 17:59:59.324  7165  7165 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:59:59.325  7165  7165 D PanProfile: Bluetooth service connected
08-16 17:59:59.326  7165  7165 D BluetoothMap: Proxy object connected
08-16 17:59:59.327  7165  7165 D MapProfile: Bluetooth service connected
08-16 17:59:59.327  7165  7165 D BluetoothMap: getConnectedDevices()
08-16 17:59:59.327  1028  1534 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 17:59:59.328  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:59:59.328  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:59:59.328  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:59:59.328  7165  7165 D BluetoothMap: Bluetooth is Not enabled
08-16 17:59:59.329  1936  1936 D WfdsService: Supplicant Connection state is changed : false
08-16 17:59:59.329  6948  6948 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:59.329  1936  2289 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 17:59:59.329  1936  2289 D WfdsService: Set the WFDS Monitor: false
08-16 17:59:59.329  1936  2289 D WfdsMonitor: WFDS Monitor is stopped
08-16 17:59:59.335  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:59:59.339  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-16 17:59:59.348  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:59.348  2466  2466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:59:59.349  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 17:59:59.350  1028  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 17:59:59.350  1028  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 17:59:59.352  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:59:59.353  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:59:59.391  7165  7165 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:59:59.392  7165  7165 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:59:59.402  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:59:59.402  7165  7165 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 17:59:59.404  7165  7165 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 17:59:59.410  7165  7165 D BluetoothPermissionRequest: onReceive
08-16 17:59:59.414  7165  7165 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 17:59:59.426  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:59:59.426  1028  1970 I ActivityManager: Killing 6626:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-16 17:59:59.464  3864  3864 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 17:59:59.464  3864  3864 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 17:59:59.466  3864  3864 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 17:59:59.467  1028  1571 W libprocessgroup: failed to open /acct/uid_10061/pid_6626/cgroup.procs: No such file or directory
,08-16 17:59:59.563  1028  1970 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7220 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 17:59:59.564  3864  3864 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:59.565  3864  3864 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 17:59:59.568  3864  3864 V BluetoothFtpService: Ftp Service onStartCommand
08-16 17:59:59.569  3864  3864 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:59.570  3864  3864 V BluetoothFtpService: Ftp Service closeService
08-16 17:59:59.570  3864  3864 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 17:59:59.573  3864  3864 V BluetoothFtpService: successfully stopped ftp service
08-16 17:59:59.573  3864  3864 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:59:59.573  3864  3864 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:59:59.573  3864  3864 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:59:59.574  3864  3864 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:59.574  3864  3864 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 17:59:59.574  3864  3864 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 17:59:59.575  3864  3864 V BluetoothFtpService: Ftp Service onDestroy
08-16 17:59:59.575  3864  3864 V BluetoothFtpService: Ftp Service closeService
08-16 17:59:59.646  1028  2026 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 17:59:59.646  3864  3864 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:59:59.646  3864  3864 V BluetoothSapService: state: 13
08-16 17:59:59.646  3864  3864 V BluetoothSapService: Stopping SAP server process
08-16 17:59:59.649  3864  3864 V BluetoothSapService: Sap Service closeSapService in
08-16 17:59:59.649  3864  3864 V BluetoothSapService: Close listen Socket : 
08-16 17:59:59.649  3864  3864 V BluetoothSapService: Close rfcomm Socket : 
08-16 17:59:59.649  3864  3864 V BluetoothSapService: Close sapd  Socket : 
,08-16 17:59:59.662  3864  3864 V BluetoothSapService: Sap Service closeSapService out
08-16 17:59:59.662  3864  3864 V BluetoothSapService: Sap Service onDestroy
08-16 17:59:59.662  3864  3864 V BluetoothSapService: Sap Service closeSapService in
08-16 17:59:59.662  3864  3864 V BluetoothSapService: Close listen Socket : 
08-16 17:59:59.662  3864  3864 V BluetoothSapService: Close rfcomm Socket : 
08-16 17:59:59.662  3864  3864 V BluetoothSapService: Close sapd  Socket : 
08-16 17:59:59.663  3864  3864 V BluetoothSapService: Sap Service closeSapService out
08-16 17:59:59.686  7220  7220 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 17:59:59.711  7237  7237 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 17:59:59.730  1028  2007 I ActivityManager: Killing 6733:com.lge.eula/1000 (adj 15): empty #17
,08-16 17:59:59.731  7220  7220 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 17:59:59.790  1028  1971 W libprocessgroup: failed to open /acct/uid_1000/pid_6733/cgroup.procs: No such file or directory
,08-16 17:59:59.840  7220  7220 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 17:59:59.841  7220  7220 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-16 17:59:59.841  7220  7220 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 17:59:59.841  7220  7220 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 17:59:59.842  7220  7220 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-16 17:59:59.844  7220  7220 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 17:59:59.848  3864  3954 D bt_hci_bdroid: cleanup
08-16 17:59:59.848  3864  4060 W bt-btif : ag scb idx 1 not allocated
08-16 17:59:59.848  3864  4060 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:59:59.848  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:59:59.848  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:59:59.848  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:59:59.848  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:59:59.848  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:59:59.848  3864  4060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:59:59.849  3864  4064 I bt_lpm  : LPM is already off!!!
08-16 17:59:59.849  3864  4217 I bt_userial_mct: exiting userial_read_thread
08-16 17:59:59.849  3864  4217 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:59:59.849  3864  3954 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:59:59.849  3864  4064 I bt_vendor: hw_epilog_process
08-16 17:59:59.850  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:59:59.850  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:59:59.850  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:59:59.850  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:59:59.851  3864  3954 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:59:59.851  3864  3954 D bt_userial_mct: userial_close
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:59:59.851  3864  3954 E bt_userial_mct: pthread_join() FAILED result:3
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:59:59.851  3864  3954 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:59:59.851  3864  4060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:59:59.851  3864  4060 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 17:59:59.852  7220  7220 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 17:59:59.866  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 17:59:59.872  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:59:59.900  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 17:59:59.903  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:59:59.905  7220  7220 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 17:59:59.909  7220  7220 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 17:59:59.916  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:59:59.916  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 17:59:59.916  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:59:59.924  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:59:59.931  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:59:59.943  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:59:59.943  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:59:59.946  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:59:59.950  3864  3954 D bt_hci_bdroid: set_power 0
08-16 17:59:59.950  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:59:59.950  3864  3954 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:59:59.950  3864  3954 I bt_vendor: bluetooth satus is on
08-16 17:59:59.950  3864  3954 I bt_vendor: bt-vendor : resetting BT status
08-16 17:59:59.950  3864  3954 I bt_vendor: Starting hciattach daemon
08-16 17:59:59.950  3864  3954 I bt_vendor: try to set false
08-16 17:59:59.951  3864  3954 I bt_vendor: Starting hciattach daemon
08-16 17:59:59.952  3864  3954 I bt_vendor: try to set false
08-16 17:59:59.953  3864  3954 I bt_vendor: cleanup
08-16 17:59:59.953  3864  4060 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 17:59:59.954  3864  3954 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:59:59.954  3864  3954 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 17:59:59.956  3864  3951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 17:59:59.959  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:59:59.959  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:59:59.959  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:59:59.963  3864  3864 D HeadsetService: Received stop request...Stopping profile...
08-16 17:59:59.967  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:59:59.970  3864  3864 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 17:59:59.970  3864  3864 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:59:59.970  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.971  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-16 17:59:59.971  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-16 17:59:59.971  3864  3986 D HeadsetStateMachine: Exit Disconnected: -1
,08-16 17:59:59.972  1028  1028 D BluetoothHeadset: Proxy object disconnected
08-16 17:59:59.972  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 17:59:59.972  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-16 17:59:59.973  3864  3864 D A2dpService: Received stop request...Stopping profile...
08-16 17:59:59.974  3864  4047 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:59:59.974  3864  3864 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 17:59:59.976  3864  3951 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:59:59.977  3864  3864 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 17:59:59.977  3864  3864 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:59:59.977  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.977  1028  1028 D BluetoothA2dp: Proxy object disconnected
08-16 17:59:59.977  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 17:59:59.978  3864  3864 D HidService: Received stop request...Stopping profile...
08-16 17:59:59.978  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.980  3864  3864 D HealthService: Received stop request...Stopping profile...
08-16 17:59:59.980  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.982  3864  3864 D PanService: Received stop request...Stopping profile...
08-16 17:59:59.982  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.982  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:59:59.983  7165  7165 D BluetoothInputDevice: Proxy object disconnected
08-16 17:59:59.983  7165  7165 D HidProfile: Bluetooth service disconnected
08-16 17:59:59.987  3864  3864 D HeadsetStateMachine: Unbinding service...
,08-16 17:59:59.988  3864  3864 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:59:59.988  3864  3864 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:59:59.988  3864  3864 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:59:59.988  3864  3864 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:59:59.988  3864  3864 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:59:59.988  3864  3864 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:59:59.988  3864  3864 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 17:59:59.989  3864  3864 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:59:59.990  3864  3864 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:59:59.990  3864  3864 D BtGatt.GattService: stop()
08-16 17:59:59.990  3864  3864 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 17:59:59.992  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.995  3864  3864 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:59:59.995  3864  3864 D BluetoothMapService: stop()
08-16 17:59:59.996  7165  7165 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:59:59.996  7165  7165 D PanProfile: Bluetooth service disconnected
08-16 17:59:59.997  3864  3864 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 17:59:59.997  3864  3864 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 17:59:59.998  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc9cc4f
08-16 17:59:59.998  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:59:59.998  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:59:59.999  7165  7165 D BluetoothMap: Proxy object disconnected
08-16 17:59:59.999  7165  7165 D MapProfile: Bluetooth service disconnected
08-16 17:59:59.999  3864  3864 I BluetoothA2dpServiceJni: cleanupNative
08-16 17:59:59.999  3864  4048 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:00:00.000  3864  3864 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:00:00.000  3864  3864 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:00:00.000  3864  3864 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:00:00.000  3864  3864 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:00:00.000  3864  3864 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:00:00.000  3864  3864 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:00:00.000  3864  3864 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:00:00.001  3864  3864 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:00:00.001  3864  3864 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 18:00:00.001  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:00:00.002  3864  3864 V BluetoothMapService: Handler(): got msg=4
08-16 18:00:00.002  3864  3864 D BluetoothMapService: MAP Service closeService in
08-16 18:00:00.002  3864  3864 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:00:00.002  3864  3864 V BluetoothMapService: MAP Service closeService out
,08-16 18:00:00.003  3864  3951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:00:00.003  3864  3951 D BluetoothAdapterProperties: Setting state to 10
08-16 18:00:00.003  3864  3951 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:00:00.004  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:00.004  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 18:00:00.004  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 18:00:00.004  3864  3864 D BluetoothMapService: cleanup()
08-16 18:00:00.004  3864  3864 D BluetoothMapService: MAP Service closeService in
,08-16 18:00:00.004  3864  3864 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:00:00.004  3864  3864 V BluetoothMapService: MAP Service closeService out
08-16 18:00:00.006  1846  2499 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:00.007  3864  3951 I BluetoothAdapterState: Entering OffState
08-16 18:00:00.048  1598  1598 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 18:00:00.048  1598  1598 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-16 18:00:00.048  1598  1598 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 18:00:00.048  1598  1598 I [SystemUI]Clock: called onTimeUpdated()
,08-16 18:00:00.056  1598  1598 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 18:00:00.056  1598  1598 I [SystemUI]DateView: called onTimeUpdated()
08-16 18:00:00.058  1598  1598 I [SystemUI]DateView: called onTimeUpdated()
08-16 18:00:00.059  1598  1598 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 18:00:00.083  1028  1641 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7261 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 18:00:00.088  7165  7186 D BluetoothPan: onBluetoothStateChange on: false
08-16 18:00:00.089  7165  7187 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:00:00.089  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:00.090  7165  7186 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 18:00:00.092  7165  7187 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:00:00.093  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:00.093  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:00:00.093  1846  2671 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:00.095  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 18:00:00.095  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 18:00:00.101  1028  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 18:00:00.101  1028  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 18:00:00.101  1028  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@11054fe9 mBinding = false
,08-16 18:00:00.102  1028  1110 D BluetoothManagerService: Sending unbind request.
08-16 18:00:00.103  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 18:00:00.105   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 494us total 22.712ms
08-16 18:00:00.113  3864  3954 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 18:00:00.115  3864  3864 I GKI_LINUX: GKI_exit_task 1 done
08-16 18:00:00.115  3864  3864 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 18:00:00.115  3864  3864 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 18:00:00.115  3864  3864 I art     : --- WEIRD: removing null entry 246
08-16 18:00:00.117  3864  3864 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 18:00:00.117  3864  3864 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 18:00:00.117  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:00.118  3864  3864 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 18:00:00.118  1936  2094 D LGBluetoothAPIService: Message: 2
08-16 18:00:00.118  1936  2094 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3df5c52c mBinding = false
08-16 18:00:00.118  1936  2094 D LGBluetoothAPIService: Sending unbind request.
08-16 18:00:00.120  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:00.121  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:00.122  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:00:00.123  3864  3864 I art     : System.exit called, status: 0
08-16 18:00:00.123  3864  3864 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 18:00:00.124  7165  7165 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:00:00.125  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 18:00:00.125  7165  7165 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-16 18:00:00.126   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.408ms
08-16 18:00:00.131  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 18:00:00.137  1598  1598 D BluetoothAdapter: 522976455: getState() :  mService = null. Returning STATE_OFF
08-16 18:00:00.137  1598  1598 D BluetoothAdapter: 522976455: getState() :  mService = null. Returning STATE_OFF
08-16 18:00:00.141  7165  7165 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:00:00.149   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 19.643ms
08-16 18:00:00.159   319   319 V AudioFlinger: 3864 died, releasing its sessions
08-16 18:00:00.159   319   319 V AudioFlinger:  pid 1846 @ 0
08-16 18:00:00.159   319   319 V AudioFlinger:  pid 3419 @ 1
08-16 18:00:00.159   319   319 V AudioFlinger:  pid 3419 @ 2
,08-16 18:00:00.161  7165  7165 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 18:00:00.180  1028  1970 I ActivityManager: Process com.android.bluetooth (pid 3864) has died
08-16 18:00:00.180  1028  1970 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 18:00:00.192  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:00:00.205  7165  7165 D BluetoothPermissionRequest: onReceive
08-16 18:00:00.208  7165  7165 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:00:00.208  7165  7165 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-16 18:00:00.212  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:00:00.269  1028  1898 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7285 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 18:00:00.283  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:00:00.287  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:00:00.295  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:00:00.326  7261  7305 W FormManager: Network not available. Please check & try again.
,08-16 18:00:00.326  7285  7285 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 18:00:00.327  7285  7285 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 18:00:00.327  7285  7285 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 18:00:00.328  7285  7285 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 18:00:00.331  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:00:00.332  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:00:00.332  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:00:00.332  7165  7165 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:00:00.333  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:00:00.339  7261  7306 V FormManager: Network unavailable.
08-16 18:00:00.343  7261  7306 V FormManager: Network unavailable.
08-16 18:00:00.344  7165  7165 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:00:00.344  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:00:00.344  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:00:00.344  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:00:00.345  7165  7165 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-16 18:00:00.345  7165  7165 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:00:00.349  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:00.349  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:00.352  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:00.354  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:00.358  7285  7285 D BluetoothAdapterApp: Loading JNI Library
,08-16 18:00:00.362  7191  7191 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 18:00:00.362  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:00:00.362  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:00.365  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:00:00.368  7261  7310 W FormManager: Network not available. Please check & try again.
08-16 18:00:00.370  4372  7312 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:00.370  4372  7309 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:00.370  4372  7312 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:00.372  7261  7311 V FormManager: Network unavailable.
08-16 18:00:00.376  7261  7311 V FormManager: Network unavailable.
08-16 18:00:00.381  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:00.391  1028  2007 I ActivityManager: Killing 6767:com.lge.bnr/1000 (adj 15): empty #17
,08-16 18:00:00.395  7285  7285 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d6fac44 Instance Count = 1
08-16 18:00:00.474  1028  1970 W libprocessgroup: failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
08-16 18:00:00.475  7285  7285 D BluetoothAdapterApp: onCreate
,08-16 18:00:00.507  7220  7220 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 18:00:00.512  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 18:00:00.512  7285  7285 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 18:00:00.512  7285  7285 D ProfileConfigQcom: Adding HeadsetService
08-16 18:00:00.512  7285  7285 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 18:00:00.512  7285  7285 D ProfileConfigQcom: Adding A2dpService
08-16 18:00:00.513  7220  7220 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 18:00:00.513  7285  7285 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 18:00:00.513  7285  7285 D ProfileConfigQcom: Adding HidService
08-16 18:00:00.513  7285  7285 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 18:00:00.513  7285  7285 D ProfileConfigQcom: Adding HealthService
08-16 18:00:00.514  7285  7285 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 18:00:00.515  7285  7285 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 18:00:00.515  7285  7285 D ProfileConfigQcom: Adding PanService
08-16 18:00:00.515  7285  7285 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 18:00:00.516  7285  7285 D ProfileConfigQcom: Adding GattService
08-16 18:00:00.516  7285  7285 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 18:00:00.516  7285  7285 D ProfileConfigQcom: Adding BluetoothMapService
08-16 18:00:00.516  7285  7285 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 18:00:00.518  7285  7285 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 18:00:00.525  7165  7165 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 18:00:00.525  7285  7285 V LGMDMManagerInternal: Create singleton instance
,08-16 18:00:00.554  7220  7220 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:00.554  7220  7220 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:00.563  7220  7220 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 18:00:00.564  7220  7220 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 18:00:00.564  7220  7220 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 18:00:00.564  7220  7220 V SoundPool: doLoad: loading sample sampleID=1
08-16 18:00:00.565  7220  7220 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 18:00:00.567  7220  7316 V SoundPool: Start decode
08-16 18:00:00.567  7220  7316 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 18:00:00.568   319  2183 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 18:00:00.568   319  2183 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 18:00:00.569   319  2183 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 18:00:00.569   319  2183 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 18:00:00.569   319  2183 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 18:00:00.569   319  2183 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 18:00:00.569   319  2183 V MediaPlayerService: player type = 3
08-16 18:00:00.569   319  2183 V AwesomePlayer: AwesomePlayer create()
08-16 18:00:00.570   319  2183 V AwesomePlayer: reset_l() 
08-16 18:00:00.570   319  2183 V AwesomePlayer: cancelPlayerEvents
08-16 18:00:00.570   319  2183 V AwesomePlayer: setAudioSink() 
08-16 18:00:00.570   319  2183 V AwesomePlayer: reset_l() 
08-16 18:00:00.570   319  2183 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-16 18:00:00.570   319  2183 V AudioCache: ignored
08-16 18:00:00.570   319  2183 V AwesomePlayer: cancelPlayerEvents
08-16 18:00:00.570   319  2183 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 18:00:00.570   319  2183 V AwesomePlayer: setDataSource_l dataSource
08-16 18:00:00.570   319  2183 V LGParserOSAL: SniffLGParser start
08-16 18:00:00.570   319  2183 V LGParserOSAL: MainType:5, SubType=0
08-16 18:00:00.570   319  2183 V LGParserOSAL: #### check Mime : application/ogg
08-16 18:00:00.570   319  2183 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,08-16 18:00:00.570   319  2183 E MediaExtractor: Use LGExtractor :application/ogg ,
,08-16 18:00:00.573  6869  6869 D UEI.SmartControl: QS Service created
08-16 18:00:00.585  7220  7220 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 18:00:00.587  7220  7220 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:00:00.587  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 18:00:00.599  7220  7220 V LGMDMManager: Create singleton instance
08-16 18:00:00.599  7285  7285 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:00.603  7285  7285 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:00.603  7285  7285 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:00.603  7285  7285 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:00.604  7285  7285 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:00.604  7285  7285 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 18:00:00.605  6869  6869 I UEI.SmartControl: Service initServices...
08-16 18:00:00.606  6869  6869 D UEI.SmartControl: QS start get config
08-16 18:00:00.615   319  2183 V LGParserOSAL: supported mime: application/ogg
08-16 18:00:00.615   319  2183 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 18:00:00.615   319  2183 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-16 18:00:00.615   319  2183 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 18:00:00.615   319  2183 V AwesomePlayer: AudioTrack Setting
08-16 18:00:00.615   319  2183 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 18:00:00.615   319  2183 V AwesomePlayer: setAudioSource() 
08-16 18:00:00.615   319  2183 V MediaPlayerService: prepare
08-16 18:00:00.615   319  2183 V AwesomePlayer: prepareAsync_l() 
08-16 18:00:00.615   319  2183 V MediaPlayerService: wait for prepare
08-16 18:00:00.615  7237  7237 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 18:00:00.615   319  7318 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 18:00:00.615   319  7318 V AwesomePlayer: initAudioDecoder() 
08-16 18:00:00.615   319  7318 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 18:00:00.615   319  7318 V AudioSystem: isOffloadSupported()
08-16 18:00:00.615   319  7318 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 18:00:00.616   319  7318 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 18:00:00.616   319  7318 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 18:00:00.616   319  7318 V AwesomePlayer: getUseOffload() = 0 
08-16 18:00:00.616   319  7318 V OMXCodec: OMXCodec::Create
08-16 18:00:00.616   319  7318 V OMXCodec: findMatchingCodecs()
08-16 18:00:00.616   319  7318 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 18:00:00.616   319  7318 V OMXCodec: matchingCodecs.size()=1
08-16 18:00:00.616   319  7318 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-16 18:00:00.620   319  7318 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 18:00:00.620   319  7318 V LGCodecAdapter: LG Codec Adapter start
08-16 18:00:00.620   319  7318 V OMXCodec: OMXCodec Createtor
08-16 18:00:00.620   319  7318 V OMXCodec: setComponentRole
08-16 18:00:00.620   319  7318 V OMXCodec: configureCodec protected=0
08-16 18:00:00.620   319  7318 V LGCodecAdapter: called getLGCodecSpecificData
08-16 18:00:00.621   319  7318 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 18:00:00.621   319  7318 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 18:00:00.621   319  7318 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 18:00:00.621   319  7318 V LGCodecOSAL: Not support LGCodec
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 18:00:00.621   319  7318 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 18:00:00.621   319  7318 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 18:00:00.621   319  7318 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 18:00:00.621   319  7318 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 18:00:00.621   319  7318 V AudioSystem: isOffloadSupported()
08-16 18:00:00.621   319  7318 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 18:00:00.621   319  7318 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 18:00:00.621   319  7318 V OMXCodec: init()
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 18:00:00.621   319  7318 V OMXCodec: allocateBuffers
08-16 18:00:00.621   319  7318 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 18:00:00.621   319  7318 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 18:00:00.621   319  7318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 18:00:00.621   319  7318 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 18:00:00.622   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 18:00:00.622   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 18:00:00.622   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 18:00:00.622   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 18:00:00.622   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 18:00:00.622   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-16 18:00:00.623   319  7318 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 18:00:00.623   319  7318 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 18:00:00.623   319  7318 V AudioCache: notify(0xb54745c0, 5, 0, 0)
08-16 18:00:00.623   319  7318 V AudioCache: ignored
08-16 18:00:00.623   319  7318 V AudioCache: notify(0xb54745c0, 1, 0, 0)
08-16 18:00:00.623   319  7318 V AudioCache: prepared
08-16 18:00:00.623   319  2183 V AudioCache: wait - success
08-16 18:00:00.623   319  2183 V MediaPlayerService: start
08-16 18:00:00.623   319  2183 V AwesomePlayer: play_l() 
08-16 18:00:00.623   319  2183 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 18:00:00.623   319  2183 V AwesomePlayer: createAudioPlayer_l
08-16 18:00:00.623   319  2183 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 18:00:00.623   319  2183 V AwesomePlayer: startAudioPlayer_l() 
08-16 18:00:00.623   319  2183 D AudioPlayer: start of Playback, useOffload 0
08-16 18:00:00.623   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 18:00:00.623   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 18:00:00.625   319  7320 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-16 18:00:00.625   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c7650 on output port
08-16 18:00:00.626   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 18:00:00.626   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 18:00:0,0.626   319  2183 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 18:00:00.627   319  2183 V AudioCache: notify(0xb54745c0, 6, 0, 0)
08-16 18:00:00.627   319  2183 V AudioCache: ignored
08-16 18:00:00.627   319  2183 V MediaPlayerService: wait for playback complete
08-16 18:00:00.628   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.628   319  7321 V AudioCache: memcpy(0xaf006000, 0xb16e3000, 4096)
08-16 18:00:00.632   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.632   319  7321 V AudioCache: memcpy(0xaf007000, 0xb16e3000, 4096)
08-16 18:00:00.633   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.633   319  7321 V AudioCache: memcpy(0xaf008000, 0xb16e3000, 4096)
08-16 18:00:00.634   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.634   319  7321 V AudioCache: memcpy(0xaf009000, 0xb16e3000, 4096)
08-16 18:00:00.634   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.634   319  7321 V AudioCache: memcpy(0xaf00a000, 0xb16e3000, 4096)
08-16 18:00:00.635   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.635   319  7321 V AudioCache: memcpy(0xaf00b000, 0xb16e3000, 4096)
08-16 18:00:00.636   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.636   319  7321 V AudioCache: memcpy(0xaf00c000, 0xb16e3000, 4096)
08-16 18:00:00.636   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.636   319  7321 V AudioCache: memcpy(0xaf00d000, 0xb16e3000, 4096)
08-16 18:00:00.637   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.637   319  7321 V AudioCache: memcpy(0xaf00e000, 0xb16e3000, 4096)
08-16 18:00:00.638   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.638   319  7321 V AudioCache: memcpy(0xaf00f000, 0xb16e3000, 4096)
08-16 18:00:00.638   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.638   319  7321 V AudioCache: memcpy(0xaf010000, 0xb16e3000, 4096)
08-16 18:00:00.639   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.639   319  7321 V AudioCache: memcpy(0xaf011000, 0xb16e3000, 4096)
08-16 18:00:00.640   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.640   319  7321 V AudioCache: memcpy(0xaf012000, 0xb16e3000, 4096)
08-16 18:00:00.641   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.641   319  7321 V AudioCache: memcpy(0xaf013000, 0xb16e3000, 4096)
08-16 18:00:00.642   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.642   319  7321 V AudioCache: memcpy(0xaf014000, 0xb16e3000, 4096)
08-16 18:00:00.643   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.643   319  7321 V AudioCache: memcpy(0xaf015000, 0xb16e3000, 4096)
08-16 18:00:00.644   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.644   319  7321 V AudioCache: memcpy(0xaf016000, 0xb16e3000, 4096)
08-16 18:00:00.644   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.645   319  7321 V AudioCache: memcpy(0xaf017000, 0xb16e3000, 4096)
08-16 18:00:00.645   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.645   319  7321 V AudioCache: memcpy(0xaf018000, 0xb16e3000, 4096)
08-16 18:00:00.646   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.646   319  7321 V AudioCache: memcpy(0xaf019000, 0xb16e3000, 4096)
08-16 18:00:00.647   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.647   319  7321 V AudioCache: memcpy(0xaf01a000, 0xb16e3000, 4096)
08-16 18:00:00.647   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.647   319  7321 V AudioCache: memcpy(0xaf01b000, 0xb16e3000, 4096)
08-16 18:00:00.648   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.648   319  7321 V AudioCache: memcpy(0xaf01c000, 0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: memcpy(0xaf01d000, 0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: memcpy(0xaf01e000, 0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: memcpy(0xaf01f000, 0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.649   319  7321 V AudioCache: memcpy(0xaf020000, 0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: memcpy(0xaf021000, 0xb16e3000, 4096)
08-16 18:00:00.652  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 18:00:00.652   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: memcpy(0xaf022000, 0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: memcpy(0xaf023000, 0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.652   319  7321 V AudioCache: memcpy(0xaf024000, 0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: memcpy(0xaf025000, 0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: memcpy(0xaf026000, 0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: memcpy(0xaf027000, 0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.653   319  7321 V AudioCache: memcpy(0xaf028000, 0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: memcpy(0xaf029000, 0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: memcpy(0xaf02a000, 0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: memcpy(0xaf02b000, 0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.654   319  7321 V AudioCache: memcpy(0xaf02c000, 0xb16e3000, 4096)
,08-16 18:00:00.655  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 18:00:00.655   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.655   319  7321 V AudioCache: memcpy(0xaf02d000, 0xb16e3000, 4096)
08-16 18:00:00.657  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6391
08-16 18:00:00.657   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.657   319  7321 V AudioCache: memcpy(0xaf02e000, 0xb16e3000, 4096)
08-16 18:00:00.657   319  7321 V AudioCache: write(0xb16e3000, 4096)
,08-16 18:00:00.657   319  7321 V AudioCache: memcpy(0xaf02f000, 0xb16e3000, 4096)
08-16 18:00:00.658   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.658   319  7321 V AudioCache: memcpy(0xaf030000, 0xb16e3000, 4096)
08-16 18:00:00.658   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.658   319  7321 V AudioCache: memcpy(0xaf031000, 0xb16e3000, 4096)
08-16 18:00:00.659   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.659   319  7321 V AudioCache: memcpy(0xaf032000, 0xb16e3000, 4096)
08-16 18:00:00.659   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.659   319  7321 V AudioCache: memcpy(0xaf033000, 0xb16e3000, 4096)
08-16 18:00:00.659   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.659   319  7321 V AudioCache: memcpy(0xaf034000, 0xb16e3000, 4096)
08-16 18:00:00.660   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 18:00:00.660   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.660   319  7321 V AudioCache: memcpy(0xaf035000, 0xb16e3000, 4096)
08-16 18:00:00.660   319  7321 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:00:00.660   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.660   319  7321 V AudioCache: memcpy(0xaf036000, 0xb16e3000, 4096)
08-16 18:00:00.660   319  7321 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:00:00.660   319  7321 V AudioCache: write(0xb16e3000, 4096)
08-16 18:00:00.660   319  7321 V AudioCache: memcpy(0xaf037000, 0xb16e3000, 4096)
08-16 18:00:00.660   319  7321 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:00:00.660   319  7321 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 18:00:00.660   319  7321 V AwesomePlayer: postAudioEOS() 
08-16 18:00:00.660   319  7321 V AudioCache: write(0xb16e3000, 280)
08-16 18:00:00.660   319  7321 V AudioCache: memcpy(0xaf038000, 0xb16e3000, 280)
08-16 18:00:00.662   319  7318 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 18:00:00.662   319  7318 V AwesomePlayer: onStreamDone
08-16 18:00:00.662   319  7318 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 18:00:00.662   319  7318 V AudioCache: notify(0xb54745c0, 2, 0, 0)
08-16 18:00:00.662   319  7318 V AudioCache: playback complete
08-16 18:00:00.662   319  7318 V AwesomePlayer: pause_l() 
08-16 18:00:00.662   319  7318 V AudioCache: notify(0xb54745c0, 7, 0, 0)
08-16 18:00:00.662   319  7318 V AudioCache: ignored
08-16 18:00:00.662   319  7318 V AwesomePlayer: cancelPlayerEvents
08-16 18:00:00.662   319  7318 D AudioPlayer: Pause Playback at 1068125
08-16 18:00:00.662   319  2183 V AudioCache: wait - success
08-16 18:00:00.662   319  2183 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 18:00:00.662   319  2183 V AwesomePlayer: reset_l() 
08-16 18:00:00.662   319  2183 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-16 18:00:00.662   319  2183 V AudioCache: ignored
08-16 18:00:00.662   319  2183 V AwesomePlayer: cancelPlayerEvents
08-16 18:00:00.663   319  2183 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 18:00:00.663   319  7320 V, OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c7650 on port 1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 18:00:00.663   319  7320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 18:00:00.663   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 18:00:00.664   319  2183 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 18:00:00.664   319  2183 D AudioPlayer: AudioPlayer releasing audio source
08-16 18:00:00.664   319  2183 D AudioPlayer: AudioPlayer done releasing audio source
08-16 18:00:00.664   319  2183 V AwesomePlayer: reset_l() 
,08-16 18:00:00.664   319  2183 V AwesomePlayer: cancelPlayerEvents
08-16 18:00:00.664   319  2183 V AwesomePlayer: ~AwesomePlayer call
08-16 18:00:00.664   319  2183 V AwesomePlayer: reset_l() 
08-16 18:00:00.664   319  2183 V AwesomePlayer: cancelPlayerEvents
08-16 18:00:00.665  7220  7316 V SoundPool: close(31)
08-16 18:00:00.665  7220  7316 V SoundPool: pointer = 0x9fff7000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 18:00:00.852  6869  6869 I UEI.SmartControl: Supports setup maps: true
,08-16 18:00:00.855  6869  6869 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 18:00:00.855  6869  6869 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 18:00:00.855  6869  6869 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 18:00:00.855  6869  6869 I UEI.SmartControl: ### init IR Blaster...
08-16 18:00:00.859  6869  6869 D serial_port: Configuring serial port
08-16 18:00:00.859  6869  6869 E UEI.SmartControl: UEIBLaster setting for 616
08-16 18:00:00.859  6869  6869 I UEI.SmartControl: Setting serial record hearder size = 2
,08-16 18:00:00.859  6869  6869 I UEI.SmartControl: configuring settings for MAXQ616
08-16 18:00:00.859  6869  6869 I UEI.SmartControl: Get version...
,08-16 18:00:00.876  6869  7322 D UEI.SmartControl: serial port data available: 21,
,08-16 18:00:00.903  6869  6869 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 18:00:00.904  6869  6869 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 18:00:00.904  6869  6869 I UEI.SmartControl: QS saving settings...
08-16 18:00:00.908  6869  6869 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 18:00:00.925  6869  7322 D UEI.SmartControl: serial port data available: 4
,08-16 18:00:00.957  6869  7328 I UEI.SmartControl: Device manager: loading config....
,08-16 18:00:00.962  6869  7328 D UEI.SmartControl: ----------- loading internal config...
08-16 18:00:00.967  6869  6869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 18:00:00.974  6869  6869 E UEI.SmartControl: Services init done
08-16 18:00:00.974  6869  6869 D UEI.SmartControl: QS Service init finished
08-16 18:00:00.978  6869  6869 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 18:00:00.978  6869  6869 D UEI.SmartControl: QS Service version code: 201091
08-16 18:00:00.981  6869  6869 D UEI.SmartControl: Service requested: Control
08-16 18:00:00.983  6869  7328 E UEI.SmartControl: Loading SETTINGS...
08-16 18:00:00.987  6869  6869 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 18:00:00.992  6869  6869 D UEI.SmartControl: Internal service binding...
08-16 18:00:00.993  7220  7220 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 18:00:00.994  6869  6883 I UEI.SmartControl: ------ IControl API: 11
08-16 18:00:00.994  6869  6883 D UEI.SmartControl: File observer start...
08-16 18:00:00.995  6869  6883 E UEI.SmartControl: IR Port is disabled: false
,08-16 18:00:00.995  6869  6883 D UEI.SmartControl: Starting file observer...
08-16 18:00:00.996  6869  6883 I UEI.SmartControl: Registering callback...
08-16 18:00:00.997  6869  7328 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 18:00:00.997  6869  6885 I UEI.SmartControl: ------ IControl API: 19
08-16 18:00:00.998  6869  6885 I UEI.SmartControl: Registering Services Ready callback...
,08-16 18:00:01.016  6869  7327 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 18:00:01.016  6869  7327 D UEI.SmartControl: -----service ready thread exits
08-16 18:00:01.017  7220  7236 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 18:00:01.018  7220  7314 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 18:00:01.019  7220  7314 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-16 18:00:01.020  7220  7220 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 18:00:01.021  7220  7220 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 18:00:01.021  6869  6883 I UEI.SmartControl: ------ IControl API: 8
08-16 18:00:01.022  1028  1416 D PowerManagerServiceEx: acquireWakeLockInternal: lock=685346902, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
08-16 18:00:01.025  7220  7220 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-16 18:00:01.025  7220  7220 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 18:00:01.026  7220  7220 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 18:00:01.026  7220  7220 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 18:00:01.028  7220  7220 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 18:00:01.029  7220  7220 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 18:00:01.062  1028  1103 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7333 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-16 18:00:01.073  7220  7220 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 18:00:01.077  7220  7220 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 18:00:01.079  1028  2043 I ActivityManager: Killing 6819:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 18:00:01.120  1028  2043 I ActivityManager: Killing 6905:com.google.android.setupwizard/u0a46 (adj 15): empty #18
,08-16 18:00:01.162  1028  1898 W libprocessgroup: failed to open /acct/uid_10005/pid_6819/cgroup.procs: No such file or directory
,08-16 18:00:01.173  1028  1970 W libprocessgroup: failed to open /acct/uid_10046/pid_6905/cgroup.procs: No such file or directory
,08-16 18:00:01.187  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 18:00:01.245  7333  7333 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-16 18:00:01.255  7333  7333 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:01.258  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=685346902 [*alarm*], flags=0x0
08-16 18:00:01.260  7220  7220 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 18:00:01.261  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 18:00:01.262  7220  7220 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:00:01.262  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 18:00:01.263  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 18:00:01.264  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 18:00:01.265  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-16 18:00:01.266  7220  7220 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471363201265]
,08-16 18:00:01.269  1028  2043 I ActivityManager: Killing 6948:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 18:00:01.290  7220  7355 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 18:00:01.333  1028  1640 W libprocessgroup: failed to open /acct/uid_10072/pid_6948/cgroup.procs: No such file or directory
,08-16 18:00:01.346  7220  7220 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 18:00:01.351  7220  7220 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 18:00:01.352  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 18:00:01.352  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-16 18:00:01.353  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-16 18:00:01.353  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 18:00:01.354  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 18:00:01.376  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 18:00:01.863  1028  2026 D WifiServiceImplEx: setWifiEnabled: true pid=7042, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 18:00:01.865  1028  2026 D WifiService: setWifiEnabled: true pid=7042, uid=10118
08-16 18:00:01.865  1028  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:00:01.885  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:00:01.885  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:00:01.885  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 18:00:01.888  1028  1534 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 18:00:01.888  1028  1534 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 18:00:01.891  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 18:00:01.891  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:00:01.891  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 18:00:01.891  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:00:01.891  1028  1534 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 18:00:01.891  1028  1534 E WifiHW  : unknown target_country: EU , set to default
08-16 18:00:01.891  1028  1534 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 18:00:01.891  1028  1534 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 18:00:01.891  1028  1534 I WifiUtil: gEnableBmps=1
08-16 18:00:01.947  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:01.958  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 18:00:01.962  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:01.970  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:00:01.974  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:01.975  1028  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:01.979  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 18:00:01.982  6385  7190 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 18:00:01.989  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 18:00:01.993  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:01.994  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:00:01.997  5820  5820 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 18:00:02.020  5820  5820 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:00:02.042  2151  2151 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:02.062  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:00:02.062  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:02.064  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:00:02.065  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 18:00:02.069  6479  6479 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:00:02.078  6479  6479 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:02.078  6479  6479 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:00:02.078  6479  6479 D AppUp4:CustFacade: isPhone : true
,08-16 18:00:02.080  6479  6479 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:00:02.080  6479  6479 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 18:00:02.081  6479  6479 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 18:00:02.082  6479  6994 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 18:00:02.082  6479  6994 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 18:00:02.082  6479  6994 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 18:00:02.087  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:02.087  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:02.088  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:02.092  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:02.122  1028  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:02.127  4372  7376 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:02.129  4372  7377 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:02.129  4372  7377 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:02.155  1028  1898 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7381 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 18:00:02.161  1028  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:02.161  1028  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:00:02.232  7381  7381 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:02.232  7381  7381 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:00:02.234  7381  7381 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 18:00:02.235  7381  7381 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 18:00:02.325  7381  7381 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 18:00:02.339  7381  7381 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 18:00:02.414  7381  7381 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 18:00:02.457  7381  7381 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:02.457  7381  7381 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:02.594   309   886 D SoftapController: Softap fwReload - Ok
,08-16 18:00:02.598  1028  1534 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (703ms)
08-16 18:00:02.602   309   886 D CommandListener: Setting iface cfg
08-16 18:00:02.602   309   886 D CommandListener: Trying to bring down wlan0
08-16 18:00:02.603   309   886 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:00:02.605  1028  1534 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 18:00:02.607  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:00:02.607  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:00:02.607  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:00:02.608  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:00:02.609  1028  1110 D Tethering: InitialState.processMessage what=4
08-16 18:00:02.613  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:02.613  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 18:00:02.608  7415  7415 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:02.608  7415  7415 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:02.620  1028  1534 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 18:00:02.620  1028  1534 D WifiMonitor: connecting to supplicant
,08-16 18:00:02.621  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:02.622  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:02.622  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 18:00:02.629  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:00:02.640  7415  7415 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 18:00:02.673  7381  7381 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:00:02.673  7415  7415 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 18:00:02.673  7415  7415 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 18:00:02.703  3419  3419 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:00:02.703  3419  3419 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:02.703  3419  3419 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 18:00:02.706  7381  7381 I HubEmail: JNI_OnLoad()
08-16 18:00:02.706  7381  7381 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 18:00:02.706  7381  7381 I HubEmail: registerNatives()
08-16 18:00:02.706  7381  7381 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 18:00:02.706  7381  7381 I HubEmail: registerNativeMethods()
08-16 18:00:02.706  7381  7381 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 18:00:02.706  7381  7381 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 18:00:02.743  7415  7415 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 18:00:02.752  1028  1935 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7426 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 18:00:02.757  7261  7423 W FormManager: Network not available. Please check & try again.
,08-16 18:00:02.763  7381  7422 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.767  7261  7424 V FormManager: Network unavailable.
08-16 18:00:02.771  7261  7424 V FormManager: Network unavailable.
,08-16 18:00:02.775  7415  7415 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 18:00:02.777  1028  1898 I ActivityManager: Killing 6497:com.android.contacts/u0a19 (adj 15): empty #17
08-16 18:00:02.786  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-16 18:00:02.786  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 18:00:02.787  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:00:02.787  1028  1534 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:00:02.788  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:02.788  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:02.789  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:02.790  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:02.790  1028  1534 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 18:00:02.790  1028  1534 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 18:00:02.791  7415  7415 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 18:00:02.792  1028  1534 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 18:00:02.792  1028  1534 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 18:00:02.792  1028  1534 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 18:00:02.792  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:00:02.792  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:00:02.792  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 18:00:02.792  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 18:00:02.793  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 18:00:02.793  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 18:00:02.820  1028  2007 W libprocessgroup: failed to open /acct/uid_10019/pid_6497/cgroup.procs: No such file or directory
,08-16 18:00:02.826  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:00:02.826  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:00:02.826  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:00:02.828  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.828  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.828  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.829  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.829  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:00:02.829  1028  1534 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 18:00:02.830  1028  1534 D WifiNative-wlan0: SET update_config 1: returned true
08-16 18:00:02.830  1028  1534 D WifiConfigStore: Loading config and enabling all networks 
08-16 18:00:02.830  1028  1534 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 18:00:02.831  1028  1534 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 18:00:02.831  1936  1936 D WfdService: Waiting for WifiP2p enabling
08-16 18:00:02.832  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:02.837  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 18:00:02.840  1028  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 18:00:02.840  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:02.840  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:00:02.840  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:02.840  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:02.841  1028  1534 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 18:00:02.841  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:02.842  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:02.842  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:02.842  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:02.854  1028  1534 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 18:00:02.855  1028  1534 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 18:00:02.855  1028  1534 D WifiStateMachine: enableVerboseLogging : level 2
08-16 18:00:02.856  1028  1534 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 18:00:02.856  1028  1534 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 18:00:02.856  1028  1534 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 18:00:02.856  1028  1534 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 18:00:02.856  1028  1534 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 18:00:02.857  1028  1534 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 18:00:02.857  1028  1534 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 18:00:02.857  1028  1534 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 18:00:02.857  1028  1534 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 18:00:02.858  1028  1534 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 18:00:02.858  1028  1534 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 18:00:02.858  1028  1534 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 18:00:02.858  1028  1534 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 18:00:02.859  1028  1534 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-16 18:00:02.860  1936  1936 D WfdsService: Supplicant Connection state is changed : true
08-16 18:00:02.860  1936  2289 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 18:00:02.860  1936  2289 D WfdsService: Set the WFDS Monitor: true
08-16 18:00:02.860  1028  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:00:02.860  1936  2289 D WfdsMonitor: WfdsMonitorThread create
08-16 18:00:02.860  1028  1534 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 18:00:02.860  1936  2289 D WfdsMonitor: WFDS Monitor is created and started
08-16 18:00:02.860  1936  2289 D WfdsService: WiFi: Supplicant connection re-established
08-16 18:00:02.861  1028  1534 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 18:00:02.861  1028  1534 D WifiNative-HAL: Setting external_sim to 1
08-16 18:00:02.861  1028  1534 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 18:00:02.861  1028  1534 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 18:00:02.861  1028  1534 I WifiNative-HAL: startHal
08-16 18:00:02.861  1028  1534 D wifi    : setting scan oui 0xaf5341a0
08-16 18:00:02.862  1028  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:00:02.862  1028  1534 I WifiNative-HAL: startHal
08-16 18:00:02.862  1028  1534 D wifi    : setting scan oui 0xaf5341a0
08-16 18:00:02.862  1936  7445 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 18:00:02.862  1028  1534 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 18:00:02.863  1936  7445 E CtrlSupplicant: Succeed to open control connection
08-16 18:00:02.863  1936  7445 E CtrlSupplicant: Succeed to open monitor connection
08-16 18:00:02.863  1936  7445 D WfdsMonitor: Supplicant connection established
08-16 18:00:02.863  1028  1534 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 18:00:02.863  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 18:00:02.863  1936  2289 D WfdsService: Connected to the supplicant for wfds
08-16 18:00:02.863  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 18:00:02.864  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 18:00:02.864  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:00:02.864  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:00:02.864  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:00:02.864  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 18:00:02.865  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 18:00:02.865  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 18:00:02.865  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:00:02.865  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:00:02.866  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:00:02.866  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:00:02.866  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:00:02.866  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:00:02.866  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 18:00:02.867  7415  7415 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 18:00:02.867  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 18:00:02.867  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:00:02.867  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:00:02.868  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:00:02.869  1028  1534 E WifiNative: : [219,976,214 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 18:00:02.869  1028  1534 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 18:00:02.869  1028  1534 D W,ifiNative-wlan0: RECONNECT: returned true
08-16 18:00:02.869  1028  1534 D WifiNative-wlan0: doString: [STATUS]
08-16 18:00:02.870  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:00:02.870  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:00:02.870  1028  1534 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:00:02.870  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:00:02.871  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:00:02.871  1028  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:00:02.872  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 18:00:02.872  1028  1028 D RttService: SCAN_AVAILABLE : 3
08-16 18:00:02.872  1028  1552 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.872  1028  1552 I WifiNative-HAL: startHal
08-16 18:00:02.872  1028  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf5341a0
08-16 18:00:02.872  1028  1552 D wifi    : failed to get capabilities : -3
08-16 18:00:02.872  1028  1552 E WifiScanningService: could not get scan capabilities
08-16 18:00:02.872  1028  1553 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.873   309   886 D CommandListener: Setting iface cfg
08-16 18:00:02.873  1028  1534 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:00:02.873   309   886 D CommandListener: Trying to bring up p2p0
08-16 18:00:02.873  1028  1532 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 18:00:02.873  1028  1532 D LGWifiP2pService: P2pEnablingState
08-16 18:00:02.873  1028  1532 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.873  1028  1534 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 18:00:02.873  1028  1532 D LGWifiP2pService: P2p socket connection successful
08-16 18:00:02.873  1028  1532 D LGWifiP2pService: P2pEnabledState
08-16 18:00:02.874  1028  1534 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 18:00:02.874  1028  1532 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 18:00:02.875  1028  1532 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 18:00:02.875  1028  1532 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 18:00:02.875  1028  1532 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 18:00:02.876  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 18:00:02.876  1936  1936 D WfdsService: WifiP2pState is changed : true
08-16 18:00:02.876  1936  2289 D WfdsService: Receive the WFDS_ENABLE Method
08-16 18:00:02.876  1936  2289 D WfdsService: Set the WFDS Monitor: true
08-16 18:00:02.876  1936  2289 D WfdsService: Connected to the supplicant for wfds
08-16 18:00:02.876  1936  2289 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 18:00:02.876  1028  1532 D WifiNative-p2p0: SET device_name G3: returned true
08-16 18:00:02.876  1028  1532 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 18:00:02.876  1028  1532 D LGWifiP2pService: before postfix = G3
08-16 18:00:02.876  1028  1532 D WifiServerServiceExt: postfix byte check : 2
08-16 18:00:02.876  7415  7415 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 18:00:02.876  1028  1532 D LGWifiP2pService: after postfix = G3
08-16 18:00:02.876  1028  1532 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 18:00:02.876  1936  2289 D WfdsService: selectPreferredScanChannel [36]
08-16 18:00:02.876  1936  2289 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 18:00:02.876  1028  1534 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 18:00:02.877  1936  1936 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 18:00:02.877  1936  1936 D WfdsService: isConnected: false
08-16 18:00:02.877  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=219985  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:02.878  1028  1532 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 18:00:02.878  1028  1532 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 18:00:02.878  1028  1532 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 18:00:02.878  1028  1532 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 18:00:02.,879  1028  1532 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 18:00:02.879  1028  1532 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 18:00:02.879  1028  1532 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 18:00:02.879  1028  1532 D WifiNative-HAL: p2pGetDeviceAddress
08-16 18:00:02.880  1028  1532 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 18:00:02.881  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:02.881  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:02.881  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=219989  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:02.881  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.881  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.882  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:00:02.882  1028  1534 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 18:00:02.882  1028  1532 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 18:00:02.882  1028  1532 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 18:00:02.882  1028  1534 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 18:00:02.882  1028  1532 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 18:00:02.882  1028  1534 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 18:00:02.882  1028  1532 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 18:00:02.883  1028  1534 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 18:00:02.883  7415  7415 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 18:00:02.883  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:02.884  1936  1936 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 18:00:02.884  1936  1936 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 18:00:02.884  1936  1936 D WfdsService: Update P2p Interface State: 3
08-16 18:00:02.884  1028  1532 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 18:00:02.884  1028  1532 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 18:00:02.885  1028  1532 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 18:00:02.885  1028  1532 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 18:00:02.885  1028  1534 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 18:00:02.885  1028  1534 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 18:00:02.886  1028  1534 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 18:00:02.886  1028  1534 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-16 18:00:02.894  7415  7415 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 18:00:02.895  1028  1532 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 18:00:02.895  1028  1532 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 18:00:02.895  1028  1534 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 18:00:02.895  1028  1532 D LGWifiP2pService: InactiveState
08-16 18:00:02.895  1028  1532 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.895  1028  1534 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 18:00:02.895  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.895  1028  1532 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 18:00:02.896  1028  1534 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 18:00:02.896  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 18:00:02.896  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:00:02.896  7415  7415 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.897  1936  7445 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:00:02.897  1028  7444 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:00:02.897  1028  7444 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.897  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.897  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.897  7415  7415 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:00:02.897  7415  7415 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.897  1936  7445 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 18:00:02.898  7415  7415 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.899  1028  1532 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-16 18:00:02.899  1028  1532 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.899  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.899  1028  1532 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.899  1028  1532 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.899  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.899  1028  1532 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.899  1028  1532 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.900  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.900  1028  1532 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.900  1936  7445 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.900  1028  1532 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.900  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.900  1028  1532 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.900  1028  1028 E WifiServerServiceExt: No p2p device connected
08-16 18:00:02.900  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:00:02.901  7415  7415 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.901  1936  2289 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 18:00:02.901  1028  7444 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.901  1028  7444 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.901  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.902  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.902  7415  7415 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:00:02.902  7415  7415 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.902  1028  7444 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.902  1028  7444 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.902  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.902  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.902  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:00:02.902  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.902  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.902  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:02.902  7415  7415 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRI,VER type=WORLD
08-16 18:00:02.902  1028  7444 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.902  1028  7444 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.903  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.903  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.903  1028  7444 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.903  1028  7444 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.903  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.903  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:02.903  1028  1534 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 18:00:02.903  1936  7445 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.903  1936  7445 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:02.903  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.903  1028  1534 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:00:02.903  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:02.904  1028  1534 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:00:02.904  1028  1534 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:00:02.904  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 18:00:02.904  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 18:00:02.904  7415  7415 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:02.905  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 18:00:02.905  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:02.905  1028  7444 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:02.905  1028  7444 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:02.905  1028  1534 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 18:00:02.905  1028  1534 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 18:00:02.906  1028  1534 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 18:00:02.906  1028  1534 D WifiNative-wlan0: doBoolean: SCAN
08-16 18:00:02.906  1028  1534 D WifiNative-wlan0: SCAN: returned false
08-16 18:00:02.906  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=220014  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:02.907  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=220015  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:02.908  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:02.908  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:02.909  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:02.909  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-,16 18:00:02.909  1028  1534 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:02.909  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:00:02.910  1028  1534 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:02.910  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:02.910  1028  1534 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:02.910  1028  1534 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:02.911  1028  1534 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:02.912  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:02.913  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:00:02.914  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:02.914  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:00:02.938  7426  7426 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:02.939  7426  7426 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:02.942  7426  7426 D PhoneMonitor: Register our PhoneStateListener
08-16 18:00:02.955  7426  7426 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 18:00:02.962  7426  7426 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 18:00:02.985  7426  7426 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 18:00:02.986  7426  7426 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 18:00:02.988  7426  7426 D TelephonyAutoProfiling: [parse] Load xml
,08-16 18:00:02.993  7426  7426 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 18:00:02.993  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 18:00:02.994  7426  7426 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 18:00:02.994  7426  7426 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-16 18:00:03.002  7426  7426 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 18:00:03.010  1028  2043 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7448 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:00:03.011  1028  2043 I ActivityManager: Killing 6552:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 18:00:03.102  1028  1641 W libprocessgroup: failed to open /acct/uid_10027/pid_6552/cgroup.procs: No such file or directory
,08-16 18:00:03.323  1028  2043 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7472 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 18:00:03.323  1028  2043 I ActivityManager: Killing 6664:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 18:00:03.371  1028  1641 W libprocessgroup: failed to open /acct/uid_10080/pid_6664/cgroup.procs: No such file or directory
,08-16 18:00:03.472  7415  7415 E wpa_supplicant: USIM:  scard_init function
08-16 18:00:03.472  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 18:00:03.472  7415  7415 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 18:00:03.472  1028  7444 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 18:00:03.473  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 18:00:03.473  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-16 18:00:03.473  1028  7444 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 18:00:03.474  1028  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 18:00:03.474  1028  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 18:00:03.474  1028  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 18:00:03.475  1028  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 18:00:03.475  1028  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-16 18:00:03.480  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:00:03.480  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 18:00:03.492  1028  1880 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7489 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:00:03.494  1028  1880 I ActivityManager: Killing 6702:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 18:00:03.587  7415  7415 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 18:00:03.590  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 18:00:03.590  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-16 18:00:03.590  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-16 18:00:03.590  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 18:00:03.590  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:03.590  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:03.601  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=220709  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 18:00:03.606  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:03.606  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:03.606  7415  7415 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:00:03.606  7415  7415 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:00:03.607  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:00:03.608  1028  1989 W libprocessgroup: failed to open /acct/uid_10097/pid_6702/cgroup.procs: No such file or directory
08-16 18:00:03.608  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 18:00:03.608  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:00:03.609  1028  7444 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:00:03.609  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 18:00:03.609  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:00:03.609  1028  7444 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:00:03.609  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:03.609  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 18:00:03.620  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=220727  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 18:00:03.622  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.622  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.623  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.623  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.623  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:00:03.623  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=220731  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:00:03.624  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.624  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=220732  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:00:03.625  1028  1534 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=220733
08-16 18:00:03.625  1028  1534 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=220733
08-16 18:00:03.625  1028  1534 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=220733
08-16 18:00:03.626  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=220734
08-16 18:00:03.626  1028  1534 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=220734
08-16 18:00:03.627  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=220735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-16 18:00:03.630  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.630  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.630  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 18:00:03.636  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=220743  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:00:03.637  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.637  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.637  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 18:00:03.637  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=220745  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:00:03.639  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=220747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:00:03.641  1028  1534 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=220749
08-16 18:00:03.642  1028  1534 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=220750
,08-16 18:00:03.643  1028  1534 D WifiNative-wlan0: doString: [STATUS]
08-16 18:00:03.643  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:03.643  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:03.644  1028  1534 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:00:03.644  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.644  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.645  1028  1534 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 18:00:03.645  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.647  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.647  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.648  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.652  1028  1534 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 18:00:03.652  1028  1534 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-16 18:00:03.657  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.657  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.657  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 18:00:03.660  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.660  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.660  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 18:00:03.666  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.666  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.666  7489  7489 I art     : Almond Protected OAT
08-16 18:00:03.667  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.669  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.669  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.671  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:03.673  1028  1534 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 18:00:03.673  1028  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:00:03.673  1028  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:00:03.673  1028  1540 D ConnectivityService: Got NetworkAgent Messenger
08-16 18:00:03.674  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 18:00:03.674  1028  1540 D ConnectivityService: NetworkAgent connected
08-16 18:00:03.674  1028  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:00:03.674  1028  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:00:03.678  1028  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:00:03.678  1028  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:00:03.678  1028  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:00:03.678  1028  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-16 18:00:03.678  1028  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:00:03.682  1028  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:00:03.684   309   886 D CommandListener: Setting iface cfg
,08-16 18:00:03.689  1028  1534 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 18:00:03.690  1028  7519 D DhcpStateMachine: StoppedState
08-16 18:00:03.690  1028  7519 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.690  1028  7519 D DhcpStateMachine: WaitBeforeStartState
08-16 18:00:03.690  1028  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=220798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:03.691  1028  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=220799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:03.691  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=220799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:03.692  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:03.692  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:03.692  1028  1534 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:03.693  1028  1534 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:03.693  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:03.693  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:03.694  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:03.695  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 18:00:03.695  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:03.696  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-16 18:00:03.696  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:03.697  1028  1028 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 18:00:03.697  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:03.697  1028  1028 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 18:00:03.698  1028  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=220806  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:03.698  1028  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=220806  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:03.699  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=220807  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 18:00:03.700  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:175102] from screen [on:0 period:-1810578828] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 18:00:03.701  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1810578827] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 18:00:03.701  1028  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 18:00:03.705  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.707  1028  1540 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 18:00:03.707  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.707  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.708  1028  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.708  1028  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 18:00:03.708  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.709  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.709  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 18:00:03.710  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-16 18:00:03.710  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-16 18:00:03.711  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 18:00:03.711  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 18:00:03.711  1028  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 18:00:03.711  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 18:00:03.711  1028  1534 D WifiNative-wlan0: SET ps 0: returned true
08-16 18:00:03.712  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 18:00:03.712  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 18:00:03.712  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 18:00:03.712  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2aecf0c0 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.712  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2aecf0c0 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.712  1028  1534 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 18:00:03.712  1028  1534 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:00:03.712  1028  7519 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.712  1028  7519 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 18:00:03.712  1028  1534 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:00:03.713   309   886 D CommandListener: Setting iface cfg
08-16 18:00:03.713   309   886 D CommandListener: Trying to bring up wlan0
08-16 18:00:03.714  1028  1534 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 18:00:03.715  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:03.715  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 18:00:03.715  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.716  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.716  1028  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.716  1028  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.717  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.717  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:03.718  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 18:00:03.718  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 18:00:03.719  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 18:00:03.719  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:00:03.719  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:00:03.719  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.719  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:00:03.719  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:00:03.719  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 18:00:03.720  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 18:00:03.720  1028  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 18:00:03.720  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:00:03.727  7489  7489 D WeatherApplication: removeAccount
08-16 18:00:03.728  7489  7489 D WeatherApplication: Account.length = 0
08-16 18:00:03.728  7489  7489 E WeatherApplication: OPERATOR:OPEN
08-16 18:00:03.732  7489  7489 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:3
,08-16 18:00:03.735  7489  7489 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:00:03.735  7489  7489 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:00:03.737  7489  7489 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:00:03.739  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:00:03.739  7489  7489 D WeatherAncestor: connectivity changed - connection : true
08-16 18:00:03.739  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 18:00:03.739  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:00:03.740  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:00:03.740  1028  1534 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 18:00:03.740  7489  7489 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 18:00:03.740  1028  1540 D ConnectivityService: ignoring duplicate network state non-change
08-16 18:00:03.743  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.743  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.744  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.744  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.745  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:00:03.745  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.746  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 18:00:03.747  1028  1534 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 18:00:03.748  1028  1540 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 18:00:03.753  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.754  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.754  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:00:03.756  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 18:00:03.761  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 18:00:03.762  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.762  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.763  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 18:00:03.764  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 18:00:03.766  7489  7489 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:00:03.766  7489  7489 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:00:03.767  7489  7489 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 18:00:03.768  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.769  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:03.769  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 18:00:03.769  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.769  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:03.771  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.771  1028  1540 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 18:00:03.772  1028  1540 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 18:00:03.773  1028  1540 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 18:00:03.773   309   886 E Netd    : netlink response contains error (File exists)
,08-16 18:00:03.774  1028  1540 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 18:00:03.774  1028  1540 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 18:00:03.774  1028  1540 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 18:00:03.775  1028  1540 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 18:00:03.775  1028  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 18:00:03.775  1028  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.775  1028  1540 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.775  1028  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.775  1028  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:03.775  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.775  1028  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:03.775  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 18:00:03.776  1028  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:00:03.776  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.776  1028  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.776  1028  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 18:00:03.776  1028  1540 D ConnectivityService: currentScore = 0, newScore = 20
08-16 18:00:03.776  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 18:00:03.776  1028  1540 D ConnectivityService:    accepting network in place of null
08-16 18:00:03.776  1028  1540 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.777  1028  1534 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.777  1028  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:03.777  1028  1540 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 18:00:03.777  1028  1540 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 18:00:03.777  1028  1540 D ConnectivityService: send,StickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:00:03.777  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.777  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:00:03.778   309  7524 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 18:00:03.778  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.778  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:00:03.779  1028  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:03.779  1028  1540 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 18:00:03.779  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.779  1028  1540 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 18:00:03.780  1028  1540 D ConnectivityService: validation of new default Network = false
08-16 18:00:03.780  1028  1540 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 18:00:03.780  1028  1540 D DSQN    : enableDataServiceNotify 
08-16 18:00:03.780  1028  1540 D DSQN    : start dsqn bin
08-16 18:00:03.780  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 18:00:03.781  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:00:03.781  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:00:03.781  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:00:03.785  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:03.785  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:00:03.785  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.789  1028  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.789  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.789  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:03.789  1028  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:03.790  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:00:03.788  7525  7525 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:03.788  7525  7525 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:03.795  1028  1531 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 18:00:03.800  7525  7525 E DSQN    : DSQN ssw
08-16 18:00:03.803  7489  7489 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:00:03.804  7489  7489 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:3
08-16 18:00:03.829   309  7524 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 18:00:03.841  1028  2007 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7530 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:00:03.842  1028  2007 I ActivityManager: Killing 6576:com.android.vending/u0a44 (adj 15): empty #17
08-16 18:00:03.862   309  7524 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 18:00:03.891  1810  7529 I CheckinService: active receiver: enabled
,08-16 18:00:03.891  1028  1970 W libprocessgroup: failed to open /acct/uid_10044/pid_6576/cgroup.procs: No such file or directory
08-16 18:00:03.893   309   885 D LGDataListener: argv[0]=dsqncommand
08-16 18:00:03.893   309   885 D LGDataListener: argv[1]=wlan0
,08-16 18:00:03.893   309   885 D LGDataListener: argv[2]=1
,08-16 18:00:03.893   309   885 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 18:00:03.893  1028  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 18:00:03.894  1028  1108 D DSQN    : start to monitor internet connection
08-16 18:00:03.905  1810  7529 I CheckinService: Preparing to send checkin request
08-16 18:00:03.905  1810  7529 I EventLogService: Accumulating logs since 1471363093565
,08-16 18:00:03.914  1028  7519 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 18:00:03.915  1028  7519 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 18:00:03.915  1028  7519 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 18:00:03.919  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:00:03.908  7550  7550 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:03.908  7550  7550 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:03.920  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.922  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.924  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:00:03 GMT], X-Android-Received-Millis=[1471363203923], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471363203892]}
08-16 18:00:03.924  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 18:00:03.924  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 18:00:03.924  1028  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.924  1028  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.924  1028  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:03.925  1028  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:03.925  1028  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:00:03.925  1028  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 18:00:03.925  1028  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 18:00:03.925  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.925  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:03.925  1028  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:03.926  1028  1540 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.926  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 18:00:03.926  7550  7550 I dhcpcd  : version 5.5.6 starting
08-16 18:00:03.926  1028  1534 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.926  1028  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:03.928  1846  1846 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:03.928  7550  7550 E dhcpcd  : get_duid: m
08-16 18:00:03.928  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:00:03.928  7550  7550 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 18:00:03.928  7550  7550 D, dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 18:00:03.930  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:00:03.949  1028  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.949  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:03.949  1028  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:00:03.957  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:00:03.958  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.959  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:03.963  1810  7529 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 18:00:03.965  1028  1534 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:00:03.965  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-16 18:00:03.965  1028  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:00:03.966  1028  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:00:03.966  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 18:00:03.967  1028  1534 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-16 18:00:03.986  7550  7550 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 18:00:03.986  7550  7550 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:00:03.986  7550  7550 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:00:03.986  7550  7550 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 18:00:03.986  7550  7550 D dhcpcd  : wlan0: sending REQUEST (xid 0x910c7d1a), next in 3.69 seconds
08-16 18:00:04.003   278   428 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:00:04.003   278   428 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 18:00:04.003   278   428 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:00:04.004  7530  7558 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 18:00:04.009  7550  7550 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 18:00:04.010   278   428 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:00:04.010   278   428 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 18:00:04.010   278   428 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:00:04.010  7530  7558 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 18:00:04.031   278   428 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 18:00:04.031   278   428 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 18:00:04.031   278   428 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:00:04.032  7530  7560 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 18:00:04.037   278   428 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 18:00:04.037   278   428 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 18:00:04.037   278   428 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:00:04.037  7530  7560 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 18:00:04.050  7550  7550 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 18:00:04.050  7550  7550 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 18:00:04.051  7550  7550 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 18:00:04.051  7550  7550 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 18:00:04.051  7550  7550 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:00:04.051  7550  7550 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 18:00:04.051  7550  7550 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:00:04.051  7550  7550 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 18:00:04.073  1028  2026 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7565 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 18:00:04.131  7565  7565 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 18:00:04.131  7565  7565 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 18:00:04.152  7565  7565 I MultiDex: VM with version 2.1.0 has multidex support
08-16 18:00:04.153  7565  7565 I MultiDex: install
08-16 18:00:04.153  7565  7565 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 18:00:04.168  7565  7565 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 18:00:04.318  1028  7519 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 18:00:04.320  1028  7519 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 18:00:04.320  1028  7519 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:00:04.321  1028  7519 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 18:00:04.321  1028  7519 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-16 18:00:04.321  1028  7519 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:00:04.321  1028  7519 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 18:00:04.321  1028  7519 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-16 18:00:04.324  1028  7519 D DhcpStateMachine: RunningState
08-16 18:00:04.354  1028  1640 I art     : Explicit concurrent mark sweep GC freed 105334(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.667ms total 113.928ms
,08-16 18:00:04.397  7616  7616 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 18:00:04.451  7616  7616 I dex2oat : dex2oat took 54.545ms (threads: 4)
,08-16 18:00:04.484  7565  7582 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:00:04.484  7565  7582 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:00:04.484  7565  7582 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:00:04.484  7565  7582 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:00:04.484  7565  7582 I Adreno-EGL: Remote Branch: 
08-16 18:00:04.484  7565  7582 I Adreno-EGL: Local Patches: 
08-16 18:00:04.484  7565  7582 I Adreno-EGL: Reconstruct Branch: 
,08-16 18:00:04.484  7530  7530 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 18:00:04.497  7530  7530 I LibraryLoader: Loading: webviewchromium
,08-16 18:00:04.501  7530  7530 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1616-1621)
08-16 18:00:04.502  7530  7530 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:00:04.511  7530  7530 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {18b9f1d1}
,08-16 18:00:04.513  7530  7530 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 18:00:04.513  7530  7530 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 18:00:04.526  7530  7530 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 18:00:04.527  7530  7530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:00:04.552   319  2186 V AudioPolicyService: registerClient() client 0xb1022ec0, uid 10093
,08-16 18:00:04.554  7530  7628 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 18:00:04.555  7530  7530 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 18:00:04.557  7530  7530 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-16 18:00:04.558  7530  7530 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 18:00:04.601  7530  7530 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:00:04.601  7530  7530 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:00:04.601  7530  7530 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:00:04.601  7530  7530 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:00:04.601  7530  7530 I Adreno-EGL: Remote Branch: 
08-16 18:00:04.601  7530  7530 I Adreno-EGL: Local Patches: 
08-16 18:00:04.601  7530  7530 I Adreno-EGL: Reconstruct Branch: 
,08-16 18:00:04.674  7530  7530 I NSApplication: Starting up...
,08-16 18:00:04.750  1028  1989 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7641 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 18:00:04.751  1028  1989 I ActivityManager: Killing 7145:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 18:00:04.771  7565  7582 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:04.771  7565  7582 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:04.790  1028  1540 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 18:00:04.845  1028  1043 W libprocessgroup: failed to open /acct/uid_10037/pid_7145/cgroup.procs: No such file or directory
,08-16 18:00:04.891  1028  1044 D WifiServiceImplEx: setWifiEnabled: false pid=7042, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 18:00:04.892  1028  1044 D WifiService: setWifiEnabled: false pid=7042, uid=10118
08-16 18:00:04.892  1028  1044 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:00:04.906  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:00:04.907  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:00:04.907  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 18:00:04.909  1028  1534 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 18:00:04.910  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 18:00:04.911  7565  7582 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:00:04.911  7565  7582 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:00:04.911  7565  7582 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:00:04.911  7565  7582 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:00:04.911  7565  7582 I Adreno-EGL: Remote Branch: 
08-16 18:00:04.911  7565  7582 I Adreno-EGL: Local Patches: 
08-16 18:00:04.911  7565  7582 I Adreno-EGL: Reconstruct Branch: 
08-16 18:00:04.912  1028  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-16 18:00:04.913  1028  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 18:00:04.915  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 18:00:04.915  1028  1534 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 18:00:04.915  1028  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:00:04.915  1028  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:00:04.917  1028  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:00:04.917  1028  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:00:04.919  7641  7641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:04.926  1028  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 18:00:04.926  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.926  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.926  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:00:04.927  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:00:04.927  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:00:04.927  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:00:04.928  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:00:04.928  1028  7519 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.930   309   886 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:00:04.960  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 18:00:04.960  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 18:00:04.962  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:04.963  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:04.963  1028  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.963  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:04.963  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.963  1028  1532 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2905b2fc
08-16 18:00:04.964  1028  1532 D LGWifiP2pService: P2pDisablingState
08-16 18:00:04.964  1028  1532 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.964  1028  1532 D LGWifiP2pService: p2p socket connection lost
08-16 18:00:04.964  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:04.964  1028  1532 D LGWifiP2pService: P2pDisabledState
08-16 18:00:04.966  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:04.966  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:04.967  1028  1534 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:00:04.968  1028  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 18:00:04.968  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-16 18:00:04.968  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:04.968  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:04.968  1028  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.968  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:00:04.968  1028  1532 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.968  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 18:00:04.969  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-16 18:00:04.969  7415  7415 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:00:04.970  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 18:00:04.970  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:00:04.971  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:00:04.977  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:04.977  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:04.977  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:00:04.977  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 18:00:04.977  1028  1028 D RttService: SCAN_AVAILABLE : 1
08-16 18:00:04.979  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:00:04.979  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:04.979  1028  1552 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.979  1028  1553 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:04.985  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 18:00:04.985  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 18:00:04.985  1936  1936 D WfdsService: WifiP2pState is changed : false
08-16 18:00:04.985  1936  2289 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 18:00:04.985  1936  2289 D WfdsService: Set the WFDS Monitor: false
08-16 18:00:04.986  1936  2289 D WfdsMonitor: WFDS Monitor is stopped
08-16 18:00:04.986  1936  2289 D WfdsService: STATE : WfdsDisabledState - enter
08-16 18:00:04.986  1936  7445 D CtrlSupplicant: Received on exit socket, terminate
08-16 18:00:04.986  1936  7445 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 18:00:04.986  1936  7445 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 18:00:04.986  1936  7445 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 18:00:04.987  1936  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 18:00:04.988  1936  2289 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 18:00:04.992  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:04.994  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:04.994  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:04.995  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:05.013  7565  7582 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 18:00:05.013  7565  7582 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 18:00:05.013  7565  7582 I Adreno-EGL: Build Date: 12/12/14 금
08-16 18:00:05.013  7565  7582 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 18:00:05.013  7565  7582 I Adreno-EGL: Remote Branch: 
08-16 18:00:05.013  7565  7582 I Adreno-EGL: Local Patches: 
08-16 18:00:05.013  7565  7582 I Adreno-EGL: Reconstruct Branch: 
,08-16 18:00:05.024   309   886 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:00:05.025  1028  1540 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 18:00:05.025  1028  1540 D DSQN    : disableDataServiceNotify
08-16 18:00:05.025  1028  1540 D DSQN    : stop dsqn bin
08-16 18:00:05.026  1028  1534 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 18:00:05.027  1028  1534 D WifiNative-p2p0: TERMINATE: returned true
08-16 18:00:05.027  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:00:05.027  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:00:05.027  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:00:05.027  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-16 18:00:05.029  1028  1540 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 18:00:05.029  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:05.029  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:05.029  1028  1540 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:05.029  1028  1540 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 18:00:05.029  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 18:00:05.029  1028  1540 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 18:00:05.030  1028  1540 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 18:00:05.030  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 18:00:05.030  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 18:00:05.030  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:05.030  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:05.030  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:05.030  1028  7518 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 18:00:05.030  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:05.030  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:05.030  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:00:05.031  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:05.033  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 18:00:05.034  1028  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:05.034  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:00:05.034  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 18:00:05.034  1028  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:05.034  1028  1540 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:05.034  1028  1540 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:05.034  1028  1540 D NetworkManagementService: Removing idletimer
08-16 18:00:05.034  1028  1534 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:05.034  1028  1540 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:05.034  1028  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:05.034  1028  1540 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 18:00:05.035  1846  1846 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:05.035  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:00:05.035  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:05.035  7042  7042 V io.jxcore.n,ode.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:05.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:00:05.035  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:05.035  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:05.035  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 18:00:05.036  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:00:05.036  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:00:05.036  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:00:05.036  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:05.036  1028  1028 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 18:00:05.037  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:05.037  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:05.037  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:05.037  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:05.037  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 18:00:05.037  1028  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 18:00:05.037  1028  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 18:00:05.037  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:00:05.037  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:00:05.037  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:00:05.050  1598  1598 D StatusBar.NetworkController: refresh,Views: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:05.071  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:00:05.072  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:05.072  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:05.085  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:00:05.086  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:05.086  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:05.106  7415  7415 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 18:00:05.106  7415  7415 I wpa_supplicant: monitor socket send errors count : 1
08-16 18:00:05.106  7415  7415 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1936-4\x00 that cannot receive messages
08-16 18:00:05.106  1028  7444 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 18:00:05.106  1028  7444 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-16 18:00:05.136  1028  7519 D DhcpStateMachine: StoppedState
08-16 18:00:05.136  1028  7519 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:05.138  1028  1534 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-16 18:00:05.138  1028  1534 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 18:00:05.144  7415  7415 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:00:05.145  7415  7415 W wpa_supplicant: USIM:  scard_deinit function
08-16 18:00:05.144  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 18:00:05.145  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:00:05.145  1028  1110 D Tethering: InitialState.processMessage what=4
08-16 18:00:05.145  1028  7444 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:00:05.145  1028  7444 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 18:00:05.145  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:05.145  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 18:00:05.146  1028  1534 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=222254
08-16 18:00:05.146  1028  1534 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=222254
08-16 18:00:05.147  1028  1534 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=222255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 18:00:05.147  1028  1534 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=222255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 18:00:05.149  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:00:05.150  1028  1534 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:05.150  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:05.154  2151  4251 I art     : Explicit concurrent mark sweep GC freed 5826(332KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.115ms total 38.166ms
,08-16 18:00:05.166   309  7669 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 18:00:05.166  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 18:00:05.167  1810  7529 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-16 18:00:05.176  1810  7529 I CheckinService: active receiver: disabled
08-16 18:00:05.214  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 18:00:05.221  6385  7190 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:00:05.230  2151  2151 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:05.241  7415  7415 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 18:00:05.241  1028  7444 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 18:00:05.241  1028  7444 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 18:00:05.241  1028  7444 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 18:00:05.242  1028  1534 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-16 18:00:05.242  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:00:05.242  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:05.242  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:00:05.242  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:00:05.244  6479  6479 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 18:00:05.251  6479  6479 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:05.251  6479  6479 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:00:05.251  6479  6479 D AppUp4:CustFacade: isPhone : true
08-16 18:00:05.251  6479  6479 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:00:05.252  6479  6479 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:00:05.255  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:05.256  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 18:00:05.258  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:05.260  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:05.266  4372  7675 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:05.268  7381  7381 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:00:05.269  4372  7676 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:05.269  4372  7676 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:05.292  7381  7678 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:00:05.300  3419  3419 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:00:05.300  3419  3419 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:05.300  3419  3419 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 18:00:05.305  7426  7426 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:00:05.306  7426  7426 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 18:00:05.306  7261  7681 W FormManager: Network not available. Please check & try again.
08-16 18:00:05.308  7261  7682 V FormManager: Network unavailable.
08-16 18:00:05.323  7489  7489 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:5
08-16 18:00:05.324  7261  7682 V FormManager: Network unavailable.
,08-16 18:00:05.328  7489  7489 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:00:05.328  7489  7489 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:00:05.328  7489  7489 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:00:05.329  7489  7489 D WeatherAncestor: connectivity changed - connection : true
08-16 18:00:05.329  7489  7489 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2463fdc
08-16 18:00:05.330  7489  7489 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:00:05.330  7489  7489 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:00:05.330  7489  7489 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-16 18:00:05.330  7489  7489 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:00:05.330  7489  7489 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:5
08-16 18:00:05.345  1028  1534 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 18:00:05.345  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:00:05.345  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:00:05.345  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:00:05.347  1936  1936 D WfdsService: Supplicant Connection state is changed : false
08-16 18:00:05.347  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 18:00:05.348  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-16 18:00:05.349  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:05.349  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:05.349  2466  2466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:05.349  1936  2289 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 18:00:05.349  1936  2289 D WfdsService: Set the WFDS Monitor: false
08-16 18:00:05.349  1936  2289 D WfdsMonitor: WFDS Monitor is stopped
08-16 18:00:05.349  1028  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 18:00:05.349  1028  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 18:00:05.350  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:05.350  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:05.369  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:00:05.369  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:00:05.369  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:00:05.369  7165  7165 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 18:00:05.369  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:00:05.370  7165  7165 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:00:05.370  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:00:05.370  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:00:05.370  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:00:05.370  7165  7165 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:00:05.371  7165  7165 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:00:05.381  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:05.385  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:00:05.388  7261  7686 W FormManager: Network not available. Please check & try again.
08-16 18:00:05.396  7261  7687 V FormManager: Network unavailable.
,08-16 18:00:05.396  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:05.404  7261  7687 V FormManager: Network unavailable.
08-16 18:00:05.419  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:00:05.422  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 18:00:05.424  7261  7689 W FormManager: Network not available. Please check & try again.
08-16 18:00:05.430  7261  7690 V FormManager: Network unavailable.
08-16 18:00:05.431  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:00:05.439  7261  7690 V FormManager: Network unavailable.
08-16 18:00:05.451  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:05.452  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 18:00:05.453  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:05.455  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:05.460  4372  7691 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:05.467  4372  7692 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:05.467  4372  7692 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:05.522  1028  1043 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7693 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 18:00:05.544   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 22.817ms
,08-16 18:00:05.580   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.334ms total 33.517ms
,08-16 18:00:05.602   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 20.938ms
,08-16 18:00:05.652  7693  7693 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 18:00:05.652  7693  7693 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 18:00:05.666  7693  7693 V [BNRBootReceiver]: Boot Receiver Return
08-16 18:00:05.667  7693  7693 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 18:00:05.673  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.685  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:05.701  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:05.726  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:05.727  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:05.730  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:00:05.737  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.751  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:05.766  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:00:05.782  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:05.783  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:05.786  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:00:05.794  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 18:00:05.801  7165  7165 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-16 18:00:05.808  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.828  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:05.844  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:05.853  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:05.854  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:00:05.855  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:00:05.861  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.878  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:05.889  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:05.904  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:05.905  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:05.906  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:05.910  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.919  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:05.926  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:05.935  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:05.935  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:05.936  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:05.941  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.954  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:05.959  6869  7329 D UEI.SmartControl: Internal timer expired: 4
08-16 18:00:05.959  6869  7329 D UEI.SmartControl: unbind internal service
08-16 18:00:05.964  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:05.975  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:05.976  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:05.977  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:05.985  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:05.997  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.010  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.019  6869  7326 D serial_port: close(fd = 24)
08-16 18:00:06.020  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:06.020  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:06.021  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:06.027  6869  7326 I UEI.SmartControl: Serial port is closed.
,08-16 18:00:06.033  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:06.062  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.075  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.084  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:06.085  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:00:06.090  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:06.099  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:00:06.118  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.133  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.154  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:06.155  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:06.157  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 18:00:06.176  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
,08-16 18:00:06.187  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 18:00:06.205  1028  1539 D WifiService: New client listening to asynchronous messages
,08-16 18:00:06.205  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:06.211  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.223  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.241  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:06.242  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:06.245  7220  7220 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 18:00:06.248  7220  7220 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-16 18:00:06.249  7220  7220 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 18:00:06.256  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:06.260  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 18:00:06.264  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:06.270  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.283  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.299  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:06.300  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:06.302  7220  7220 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 18:00:06.304  7220  7220 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:00:06.305  7220  7220 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 18:00:06.314  1028  2026 I ActivityManager: Killing 7237:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 18:00:06.376  1028  1899 W libprocessgroup: failed to open /acct/uid_1000/pid_7237/cgroup.procs: No such file or directory
,08-16 18:00:06.381  2151  2151 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 18:00:06.400  2151  2151 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 18:00:06.403  2151  2151 D c       : Getting all permits...
,08-16 18:00:06.403  2151  2151 D a       : Opening database...
08-16 18:00:06.412  2151  2151 D a       : Opening database auth.proximity.permit_store...
08-16 18:00:06.412  2151  2151 D a       : Closing database...
,08-16 18:00:06.427  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:00:06.431  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:00:06.431  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:00:06.431  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:06.434  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.441  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.449  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:06.449  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:06.451  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:00:06.456  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:06.460  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:00:06.460  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:00:06.460  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:06.465  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.474  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.484  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:06.485  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:06.487  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:00:06.491  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:06.496  7191  7191 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 18:00:06.496  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:00:06.496  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:00:06.503  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:06.514  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.524  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:06.525  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:00:06.527  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:00:06.538  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:00:06.546  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:00:06.553  7261  7718 W FormManager: Network not available. Please check & try again.
08-16 18:00:06.558  7261  7719 V FormManager: Network unavailable.
08-16 18:00:06.563  7261  7719 V FormManager: Network unavailable.
08-16 18:00:06.563  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:00:06.592  2151  2151 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 18:00:06.612  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:06.613  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:06.614  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:06.617  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:06.627  7191  7191 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 18:00:06.627  7191  7191 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 18:00:06.627  7191  7191 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:06.628  4372  7720 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:06.630  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:00:06.635  4372  7721 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:06.635  4372  7721 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:06.644  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:06.652  7261  7724 V FormManager: Network unavailable.
08-16 18:00:06.653  7261  7723 W FormManager: Network not available. Please check & try again.
08-16 18:00:06.656  7261  7724 V FormManager: Network unavailable.
,08-16 18:00:06.709  1028  1534 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1810575819] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 18:00:06.712  1028  1534 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1810575817] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 18:00:06.782  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:06.787  1028  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:06.790  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 18:00:06.803  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:06.804  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:06.807  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 18:00:06.809  6385  7190 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:00:06.810  5820  5820 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:00:06.812  1028  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:00:06.832  2151  2151 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:06.843  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:00:06.843  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:06.843  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:00:06.843  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:00:06.845  6479  6479 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:00:06.851  6479  6479 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:06.851  6479  6479 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:00:06.851  6479  6479 D AppUp4:CustFacade: isPhone : true
08-16 18:00:06.851  6479  6479 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:00:06.852  6479  6479 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-16 18:00:06.856  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:06.857  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:06.860  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:06.864  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:06.877  4372  7729 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:06.878  7381  7381 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:00:06.882  4372  7730 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:06.882  4372  7730 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:06.906  3419  3419 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:00:06.907  3419  3419 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:06.907  3419  3419 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 18:00:06.907  3419  3419 D PhoneState: setPdpRejectCasuse : false
08-16 18:00:06.910  7381  7732 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:06.913  7261  7734 W FormManager: Network not available. Please check & try again.
08-16 18:00:06.914  7426  7426 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:00:06.914  7426  7426 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:00:06.928  7261  7736 V FormManager: Network unavailable.
08-16 18:00:06.928  7489  7489 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:6
,08-16 18:00:06.932  7489  7489 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 18:00:06.932  7489  7489 D Weather.Utils: 2 : All the weather widget is gone.
,08-16 18:00:06.932  7261  7736 V FormManager: Network unavailable.
08-16 18:00:06.932  7489  7489 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:00:06.932  7489  7489 D WeatherAncestor: connectivity changed - connection : true
08-16 18:00:06.932  7489  7489 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2463fdc
08-16 18:00:06.934  7489  7489 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:00:06.934  7489  7489 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:00:06.934  7489  7489 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:00:06.934  7489  7489 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:00:06.934  7489  7489 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:6
08-16 18:00:07.908  1028  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:07.908  1028  2026 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 18:00:07.940  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:00:07.941  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:00:07.941  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 18:00:07.942  1028  1110 D BluetoothManagerService: Message: 1
08-16 18:00:07.942  1028  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 18:00:07.969  1028  1110 D BluetoothManagerService: Message: 20
08-16 18:00:07.969  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2571ffb9:true
,08-16 18:00:07.974  7285  7285 D BluetoothAdapterState: make
08-16 18:00:07.979  7285  7285 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 18:00:07.979  7285  7285 I bluedroid-qcom: init
08-16 18:00:07.980  7285  7748 I BluetoothAdapterState: Entering OffState
08-16 18:00:07.981  7285  7285 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 18:00:07.981  7285  7285 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 18:00:07.981  7285  7285 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 18:00:07.981  7285  7285 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 18:00:07.982  7285  7285 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 18:00:07.983  7285  7285 I bluedroid-qcom: get_profile_interface socket
08-16 18:00:07.984  7285  7285 I bluedroid-qcom: get_profile_interface map_client
,08-16 18:00:07.989  7285  7752 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 18:00:07.988  7751  7751 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:07.988  7751  7751 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:08.002  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-16 18:00:08.005  1028  1110 D BluetoothManagerService: Message: 40
08-16 18:00:08.005  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 18:00:08.006  7285  7303 I bluedroid-qcom: config_hci_snoop_log
08-16 18:00:08.008  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 18:00:08.008  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 18:00:08.013  7751  7751 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 18:00:08.013  7751  7751 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 18:00:08.013  7751  7751 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 18:00:08.014  7285  7748 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 18:00:08.015  7285  7748 D BluetoothAdapterProperties: Setting state to 11
08-16 18:00:08.015  7285  7748 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:00:08.017  7751  7751 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 18:00:08.022  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:08.022  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 18:00:08.022  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 18:00:08.025  7751  7751 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 18:00:08.025  7751  7751 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 18:00:08.027  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:08.027  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 18:00:08.035  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.039  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 18:00:08.041  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.045  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:08.054  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:00:08.064  1028  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:08.070  1028  1110 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:00:08.076  7285  7748 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 18:00:08.076  7285  7285 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:00:08.081  7285  7285 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:08.082  7285  7285 V BluetoothPbapReceiver: ***********state = 11
08-16 18:00:08.082  7285  7752 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 18:00:08.088  7285  7752 D BluetoothAdapterProperties: Name is: G3
08-16 18:00:08.090  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 18:00:08.090  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:00:08.090  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 18:00:08.091  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 18:00:08.092  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.094  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.094  6385  7190 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:00:08.094  7285  7748 D BluetoothBondStateMachine: make
08-16 18:00:08.095  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.097  7285  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.097  7285  7748 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 18:00:08.097  7285  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.098  7285  7748 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 18:00:08.098  7285  7748 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-16 18:00:08.099  7285  7770 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 18:00:08.100  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.101  1028  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.102  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:00:08.103  5820  5820 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:00:08.109  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:00:08.155  1028  1899 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7771 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 18:00:08.158  1028  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:08.158  5820  5820 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 18:00:08.159  1028  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:08.162  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:08.164  7285  7285 D HeadsetService: Received start request. Starting profile...
08-16 18:00:08.165  7285  7285 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:00:08.165  7285  7285 D LGBluetoothHfpAdapter: Version 1.6
,08-16 18:00:08.168  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:08.169  7285  7285 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:00:08.170  7285  7285 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:00:08.171  7285  7285 D HeadsetStateMachine: make
08-16 18:00:08.177  2151  2151 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.177  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:08.183  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:00:08.191  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:00:08.191  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.191  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:00:08.191  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:00:08.192  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:08.193  6479  6479 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:00:08.197  6479  6479 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:08.197  6479  6479 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:00:08.197  6479  6479 D AppUp4:CustFacade: isPhone : true
,08-16 18:00:08.197  6479  6479 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:00:08.197  6479  6479 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:00:08.199  7285  7748 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:08.205  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.205  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:08.206  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:08.210  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:08.218  7285  7285 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:08.218  7285  7285 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 18:00:08.220  7285  7748 V LGMDMManager: Create singleton instance
,08-16 18:00:08.223  7285  7748 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 18:00:08.223  7285  7285 D HeadsetStateMachine: max_hf_connections = 1
08-16 18:00:08.223  7285  7285 I bluedroid-qcom: get_profile_interface handsfree
08-16 18:00:08.224  4372  7790 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:08.225  7381  7381 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 18:00:08.226  7285  7285 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 18:00:08.226   319  2183 V AudioPolicyService: registerClient() client 0xb04105e0, uid 1002
08-16 18:00:08.226   319   319 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 18:00:08.226   319   319 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:00:08.226   319   319 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:00:08.227  7285  7285 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 18:00:08.227   319  2186 V AudioFlinger: registerClient() client 0xb55814f0, pid 7285
08-16 18:00:08.228   319  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:08.228   319  1371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:08.228  7285  7285 V ToneGenerator: Create Track: 0xb4928080
08-16 18:00:08.228  7285  7285 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 18:00:08.228  7285  7285 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 18:00:08.228  1028  1934 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:08.228  1028  1934 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:08.229   319  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:00:08.229   319  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,08-16 18:00:08.229   319  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:00:08.229   319  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:00:08.229  1846  2499 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:08.229  1846  2499 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:08.229  3419  3435 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:08.229  3419  3435 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:08.229  1598  2096 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:08.229  1598  2096 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:08.229  7285  7303 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:08.229  7285  7303 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 18:00:08.229   319  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:08.229   319  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:08.230  7285  7301 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:08.230  7285  7301 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 18:00:08.230  1028  1641 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:08.230  1028  1641 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:08.230  1846  1862 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:08.230  1846  1862 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:08.230  3419  3434 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:08.230  3419  3434 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:08.230   319   319 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 18:00:08.231   319  2186 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:00:08.231   319  2186 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 18:00:08.231   319  2186 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:00:08.231   319  2186 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:00:08.233  7285  7285 V AudioSystem: getLatency() output 2, latency 50
08-16 18:00:08.233  7285  7285 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 18:00:08.233  7285  7285 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 18:00:08.233   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:00:08.233   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-16 18:00:08.233   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:00:08.233   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 18:00:08.233   319  1375 V AudioFlinger: createTrack() lSessionId: 22
08-16 18:00:08.234  7285  7285 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 18:00:08.234   319  2183 V AudioFlinger: acquiring 22 from 7285, for 7285
08-16 18:00:08.234   319  2183 V AudioFlinger:  added new entry for 22
08-16 18:00:08.234  7285  7285 V ToneGenerator: ToneGenerator INIT OK, time: 225354
08-16 18:00:08.234  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.235  7285  7788 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 18:00:08.235  7285  7788 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:00:08.235  7285  7788 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:00:08.235  7285  7788 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 18:00:08.235   319   319 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7285
08-16 18:00:08.235  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.237  7285  7285 D A2dpService: Received start request. Starting profile...
08-16 18:00:08.237  7285  7285 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 18:00:08.238  7285  7285 V Avrcp   : make
08-16 18:00:08.238  7285  7285 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 18:00:08.238  7285  7285 I bluedroid-qcom: get_profile_interface avrcp
08-16 18:00:08.239  1598  2096 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-16 18:00:08.239  1598  2096 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:08.240  4372  7791 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.240  4372  7791 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:00:08.240   319   319 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 18:00:08.240   319   319 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 18:00:08.240   319   319 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 18:00:08.240   319   319 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 18:00:08.240   319   319 V voice   : voice_set_parameters: exit with code(0)
08-16 18:00:08.240   319   319 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 18:00:08.240   319   319 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 18:00:08.241   319   319 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 18:00:08.241   319   319 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 18:00:08.241   319   319 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 18:00:08.241   319   319 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 18:00:08.241  7285  7788 V ToneGenerator: ToneGenerator destructor
08-16 18:00:08.241  7285  7788 V ToneGenerator: stopTone
08-16 18:00:08.241  7285  7788 V ToneGenerator: Delete Track: 0xb4928080
08-16 18:00:08.241  7285  7788 V AudioTrack: ~AudioTrack, releasing session id from 7285 on behalf of 7285
08-16 18:00:08.241   319  2186 V AudioFlinger: releasing 22 from 7285 for 7285
08-16 18:00:08.241   319  2186 V AudioFlinger:  decremented refcount to 0
08-16 18:00:08.241   319  2186 V AudioFlinger: purging stale effects
08-16 18:00:08.241   319  2186 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 18:00:08.241   319  2186 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 18:00:08.241   319  2186 V AudioFlinger: PlaybackThread::Track destructor
08-16 18:00:08.242   319  2186 V AudioFlinger: removeClient_l() pid 7285, calling pid 319
08-16 18:00:08.243   319  1267 V AudioPolicyService: AudioCommandThread() waking up
08-16 18:00:08.243   319  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 18:00:08.243   319  1267 V AudioPolicyManager: releaseOutput() 2
,08-16 18:00:08.243   319  1267 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 18:00:08.247  7285  7285 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 18:00:08.248  7285  7285 E AudioManager: No RCC entry present to update
08-16 18:00:08.248  7285  7285 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 18:00:08.252  7285  7285 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 18:00:08.254  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 18:00:08.254  7285  7285 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 18:00:08.254  7771  7771 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 18:00:08.254  7771  7771 W LG Account v2.2: No ProfileInfo entries
08-16 18:00:08.254  7771  7771 I LG Account v2.2: isEnabled: false
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Country: EU
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Operator: OPEN
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Ranking support: false
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Comfort support: false
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Accessory: true
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Health device: true
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Extra Pedometer: false
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Blood glucose device: false
08-16 18:00:08.255  7771  7771 I Feature : [Lifetracker]Device Number: 3
08-16 18:00:08.260  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 18:00:08.267  7381  7794 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:00:08.313  3419  3419 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 18:00:08.313  3419  3419 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.313  3419  3419 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 18:00:08.316  7165  7165 D BluetoothPermissionRequest: onReceive
08-16 18:00:08.317  7261  7799 W FormManager: Network not available. Please check & try again.
08-16 18:00:08.318  7261  7800 V FormManager: Network unavailable.
08-16 18:00:08.320  7426  7426 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:00:08.321  7426  7426 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:00:08.321  7261  7800 V FormManager: Network unavailable.
08-16 18:00:08.327  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 18:00:08.337  7489  7489 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:8
08-16 18:00:08.338  7489  7489 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:00:08.338  7489  7489 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:00:08.338  7489  7489 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:00:08.338  7489  7489 D WeatherAncestor: connectivity changed - connection : true
08-16 18:00:08.338  7489  7489 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2463fdc
08-16 18:00:08.339  7489  7489 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:00:08.339  7489  7489 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:00:08.339  7489  7489 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:00:08.340  7489  7489 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 18:00:08.341  7489  7489 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:8
08-16 18:00:08.357  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 18:00:08.360  6385  7190 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 18:00:08.365  1028  1043 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:08.365  1028  1043 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:08.372  2151  2151 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:00:08.382  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 18:00:08.382  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.382  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 18:00:08.382  6479  6479 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 18:00:08.383  6479  6479 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 18:00:08.385  6479  6479 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:08.385  6479  6479 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-16 18:00:08.385  6479  6479 D AppUp4:CustFacade: isPhone : true
08-16 18:00:08.386  6479  6479 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:00:08.386  6479  6479 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 18:00:08.389  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.389  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:08.391  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:08.393  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 18:00:08.399  7381  7381 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 18:00:08.405  4372  7802 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 18:00:08.407  4372  7803 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.407  4372  7803 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 18:00:08.415  7381  7807 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:00:08.418  7261  7805 W FormManager: Network not available. Please check & try again.
08-16 18:00:08.418  3419  3419 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 18:00:08.418  3419  3419 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:08.418  3419  3419 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 18:00:08.424  7426  7426 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 18:00:08.425  7426  7426 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 18:00:08.433  7261  7806 V FormManager: Network unavailable.
,08-16 18:00:08.436  7489  7489 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:8
08-16 18:00:08.436  1028  1898 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 18:00:08.437  7489  7489 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 18:00:08.437  7261  7806 V FormManager: Network unavailable.
08-16 18:00:08.439  7489  7489 D Weather.Utils: 2 : All the weather widget is gone.
08-16 18:00:08.441  7489  7489 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 18:00:08.441  7489  7489 D WeatherAncestor: connectivity changed - connection : true
08-16 18:00:08.441  7489  7489 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2463fdc
08-16 18:00:08.441  7489  7489 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 18:00:08.442  7489  7489 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 18:00:08.442  7489  7489 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 18:00:08.442  7489  7489 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 18:00:08.442  7489  7489 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:0:8
08-16 18:00:08.443  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 18:00:08.447  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:00:08.448  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 18:00:08.449  7285  7285 I BluetoothA2dpServiceJni: classInitNative
08-16 18:00:08.449  7285  7285 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:00:08.449  7285  7285 D A2dpStateMachine: make
08-16 18:00:08.450  7285  7285 I bluedroid-qcom: get_profile_interface a2dp
08-16 18:00:08.450  7285  7810 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:00:08.452  7285  7285 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:00:08.452  7285  7285 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 18:00:08.453  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.453  7285  7809 D A2dpStateMachine: Enter Disconnected: -2
08-16 18:00:08.454  7285  7285 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 18:00:08.456  7285  7285 D HidService: Received start request. Starting profile...
08-16 18:00:08.456  7285  7285 I bluedroid-qcom: get_profile_interface hidhost
08-16 18:00:08.456  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.456  7285  7285 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 18:00:08.458  7285  7285 D HealthService: Received start request. Starting profile...
,08-16 18:00:08.459  7285  7285 I bluedroid-qcom: get_profile_interface health
08-16 18:00:08.460  7285  7285 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 18:00:08.460  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.461  7285  7285 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 18:00:08.462  7285  7285 D PanService: Received start request. Starting profile...
08-16 18:00:08.462  7285  7285 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:00:08.463  7285  7285 I bluedroid-qcom: get_profile_interface pan
08-16 18:00:08.467  7285  7285 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 18:00:08.467  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.468  7285  7285 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 18:00:08.472  7285  7285 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:00:08.472  7285  7285 D BtGatt.GattService: Received start request. Starting profile...
,08-16 18:00:08.472  7285  7285 D BtGatt.GattService: start()
08-16 18:00:08.472  7285  7285 I bluedroid-qcom: get_profile_interface gatt
08-16 18:00:08.473  7285  7285 D BtGatt.AdvertiseManager: advertise manager created
08-16 18:00:08.477  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
,08-16 18:00:08.478  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.478  7285  7285 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 18:00:08.479  7285  7285 V BluetoothMapService: BluetoothMapBinder()
08-16 18:00:08.479  7285  7285 D BluetoothMapService: Received start request. Starting profile...
08-16 18:00:08.479  7285  7285 D BluetoothMapService: start()
08-16 18:00:08.482  7285  7285 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 18:00:08.482  7285  7285 D BluetoothMapEmailAppObserver: createReceiver()
08-16 18:00:08.483  7285  7285 D BluetoothMapEmailAppObserver: initObservers()
08-16 18:00:08.483  7285  7285 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 18:00:08.489  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:08.489  7285  7285 D HeadsetStateMachine: Proxy object connected
08-16 18:00:08.489  7285  7285 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 18:00:08.489  7285  7285 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 18:00:08.493  7285  7285 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:08.493  7285  7788 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 18:00:08.494  7285  7788 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:00:08.494  7285  7788 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 18:00:08.495  7285  7285 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:08.497  7285  7285 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:08.499  7285  7285 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:08.500  7285  7285 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 18:00:08.502  7285  7285 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 18:00:08.504  7285  7285 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 18:00:08.504  7285  7285 V BluetoothMapService: Handler(): got msg=1
08-16 18:00:08.506  7285  7748 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 18:00:08.506  7285  7748 I bluedroid-qcom: enable
08-16 18:00:08.506  7285  7817 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 18:00:08.506  7285  7285 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:08.506  7285  7817 I bt-btu  : btu_task pending for preload complete event
08-16 18:00:08.506  7285  7748 I bt_hci_bdroid: init
08-16 18:00:08.508  7285  7285 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:08.508  7285  7285 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:08.508  7285  7285 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:08.508  7285  7285 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:08.508  7285  7285 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 18:00:08.509  7285  7748 I bt_vendor: bt-vendor : init
08-16 18:00:08.509  7285  7748 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 18:00:08.509  7285  7748 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 18:00:08.509  7285  7748 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 18:00:08.513  7285  7748 D bt_userial_mct: userial_init
08-16 18:00:08.513  7285  7748 D bt_hci_bdroid: set_power 1
08-16 18:00:08.513  7285  7748 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 18:00:08.513  7285  7748 I bt_vendor: Starting hciattach daemon
08-16 18:00:08.513  7285  7748 I bt_vendor: try to set true
08-16 18:00:08.508  7820  7820 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:08.508  7820  7820 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 18:00:08.528  7821  7821 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 18:00:08.545  1028  1898 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 18:00:08.581  7844  7844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-16 18:00:08.591  7845  7845 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:00:08.597  7824  7824 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:00:08.614  1028  1898 I ActivityManager: Killing 7333:com.lge.clock/u0a10 (adj 15): empty #17
,08-16 18:00:08.616  7847  7847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 18:00:08.627  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 18:00:08.639  7849  7849 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:00:08.650  7850  7850 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 18:00:08.674  7852  7852 I libmdmdetect: ESOC framework not supported
08-16 18:00:08.675  7852  7852 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 18:00:08.682  1028  1641 W libprocessgroup: failed to open /acct/uid_10010/pid_7333/cgroup.procs: No such file or directory
08-16 18:00:08.683  7852  7852 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 18:00:08.683  7852  7852 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 18:00:08.683  7852  7852 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 18:00:08.683  7852  7852 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 18:00:08.683  7852  7852 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 18:00:08.683  7852  7852 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 18:00:08.683  7852  7852 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 18:00:08.723  7852  7853 E QC-QMI  : qmi_client [7852] 14: failed to locate client data
08-16 18:00:08.723   463   463 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 18:00:08.723   463   463 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 18:00:08.776  7854  7854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 18:00:08.792  7855  7855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:00:08.866  7285  7748 I bt_vendor: bluetooth satus is on
08-16 18:00:08.866  7285  7748 D bt_hci_bdroid: preload
08-16 18:00:08.866  7285  7819 D bt_userial_mct: userial_open(port:0)
,08-16 18:00:08.866  7285  7819 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 18:00:08.870  7285  7819 I bt_vendor: Done intiailizing UART
08-16 18:00:08.873  7285  7819 I bt_vendor: Done intiailizing UART
08-16 18:00:08.873  7285  7819 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 18:00:08.873  7285  7819 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 18:00:08.874  7285  7860 D bt_userial_mct: Entering userial_read_thread()
08-16 18:00:08.874  7285  7817 I bt-btu  : btu_task received preload complete event
08-16 18:00:08.879  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 18:00:08.879  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-16 18:00:08.885  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 18:00:08.890  7285  7817 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 18:00:08.894  1028  1416 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e70da27 type 2 when 225996 android} when 225996
,08-16 18:00:08.899  7220  7220 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 18:00:08.901  7220  7220 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6391
08-16 18:00:08.914  1028  1416 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29aef4d4 type 2 when 226021 com.google.android.gms} when 226021
,08-16 18:00:08.921   309  7865 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 18:00:08.923  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 18:00:08.946  7285  7817 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 18:00:08.946  7285  7817 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0205061 
08-16 18:00:08.946  7285  7817 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0205061 
,08-16 18:00:08.971  7285  7752 E bt-btif : Calling BTA_HhEnable
08-16 18:00:08.971  7285  7752 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 18:00:08.972  7285  7752 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 18:00:08.973  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 18:00:08.973  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-16 18:00:08.973  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 18:00:08.973  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 18:00:08.973  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 18:00:08.975  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:00:08.975  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 18:00:08.975  7285  7752 D BluetoothAdapterProperties: Name is: G3
08-16 18:00:08.979  7285  7752 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:00:08.980  7285  7752 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:00:08.980  7285  7752 D bt_hci_bdroid: postload
08-16 18:00:08.980  7285  7819 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:08.981  7285  7817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 18:00:08.981  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.982  7285  7752 D bte_conf: Device ID record 1 : primary
08-16 18:00:08.982  7285  7752 D bte_conf:   vendorId            = 00c4
08-16 18:00:08.982  7285  7752 D bte_conf:   vendorIdSource      = 0001
08-16 18:00:08.982  7285  7752 D bte_conf:   product             = 13a1
08-16 18:00:08.982  7285  7752 D bte_conf:   version             = 1000
08-16 18:00:08.982  7285  7752 D bte_conf:   clientExecutableURL = 
08-16 18:00:08.982  7285  7752 D bte_conf:   serviceDescription  = 
08-16 18:00:08.982  7285  7752 D bte_conf:   documentationURL    = 
08-16 18:00:08.982  7285  7752 D bte_conf: bte_load_did_conf no section named DID2.
08-16 18:00:08.983  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:08.986  7285  7752 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 18:00:08.978  7867  7867 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:08.978  7867  7867 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:08.992  7285  7817 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:08.992  7285  7817 W bt-smp  : Plain text(LSB ~ MSB) = 5e a1 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:08.992  7285  7817 W bt-smp  : Encrypted text(LSB ~ MSB) = 10 43 f8 7a 27 9a cd ee 36 40 63 7c 01 99 d9 3f 
08-16 18:00:08.992  7285  7817 W bt-btm  : Stopping oneshot timer
08-16 18:00:08.992  7285  7819 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:08.993  7285  7748 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 18:00:08.994  7285  7748 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:00:08.994  7285  7748 D BluetoothAdapterProperties: State =  11
08-16 18:00:08.994  7285  7748 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 18:00:08.995  7285  7748 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 18:00:08.995  7285  7748 D BluetoothAdapterProperties: Setting state to 12
08-16 18:00:08.995  7285  7748 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 18:00:08.995  7285  7752 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:00:08.997  7285  7819 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:08.997  7285  7819 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:08.998  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:08.998  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 18:00:08.998  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 18:00:09.001  7285  7819 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 18:00:09.002  7285  7860 E bt_mct  : hci lib postload completed
08-16 18:00:09.005  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:09.005  7285  7748 I BluetoothAdapterState: Entering On State
08-16 18:00:09.008  7285  7748 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 18:00:09.008  7285  7748 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 18:00:09.008  7285  7748 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 18:00:09.009  7285  7748 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 18:00:09.013  7285  7752 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:00:09.013  7285  7752 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 18:00:09.019  7165  7187 D BluetoothPan: onBluetoothStateChange on: true
08-16 18:00:09.019  7165  7187 D BluetoothPan: onBluetoothStateChange call bindService
08-16 18:00:09.025  7165  7186 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:00:09.031  1846  1846 D BluetoothHeadset: Proxy object connected
,08-16 18:00:09.037  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:09.041  1846  1846 D BluetoothHeadset: Proxy object connected
08-16 18:00:09.041  7285  7817 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:09.042  7285  7817 W bt-smp  : Plain text(LSB ~ MSB) = a1 38 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:09.042  7285  7817 W bt-smp  : Encrypted text(LSB ~ MSB) = 62 ca fe 5d 3c 8b 26 9d 78 a6 3a 12 72 b8 b8 59 
08-16 18:00:09.042  7285  7817 W bt-btm  : Stopping oneshot timer
08-16 18:00:09.042  7165  7187 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 18:00:09.051  7165  7871 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 18:00:09.054  7285  7817 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:09.054  7285  7817 W bt-smp  : Plain text(LSB ~ MSB) = 21 5d 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:09.054  7285  7817 W bt-smp  : Encrypted text(LSB ~ MSB) = f5 0f 1b 85 ea 8d 6a 18 7a 64 f2 6c 59 46 53 40 
08-16 18:00:09.054  7285  7817 W bt-btm  : Stopping oneshot timer
,08-16 18:00:09.056  7285  7748 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 18:00:09.057  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:09.058  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:00:09.059  1028  1028 D BluetoothHeadset: Proxy object connected
08-16 18:00:09.060  7165  7165 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:00:09.060  7165  7165 D PanProfile: Bluetooth service connected
08-16 18:00:09.062  7873  7873 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 18:00:09.067  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 18:00:09.069  1028  1028 D BluetoothA2dp: Proxy object connected
08-16 18:00:09.070  1846  1846 D BluetoothHeadset: Proxy object connected
08-16 18:00:09.070  7285  7817 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:09.070  7285  7817 W bt-smp  : Plain text(LSB ~ MSB) = 56 fa 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:09.070  7285  7817 W bt-smp  : Encrypted text(LSB ~ MSB) = eb a1 db a0 e3 68 09 b8 3c ad 76 c0 4b af 84 fd 
08-16 18:00:09.070  7285  7817 W bt-btm  : Stopping oneshot timer
08-16 18:00:09.072  1028  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 18:00:09.072  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 18:00:09.074  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.075  1936  2094 D LGBluetoothAPIService: Message: 1
08-16 18:00:09.075  1936  2094 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 18:00:09.079  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 18:00:09.085  7285  7817 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:09.086  7285  7817 W bt-smp  : Plain text(LSB ~ MSB) = 3c 9e 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:09.086  7285  7817 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 90 13 5f 0d a1 99 c6 38 47 da 5a eb 92 1c b0 
08-16 18:00:09.086  7285  7817 W bt-btm  : Stopping oneshot timer
08-16 18:00:09.087  7042  7042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 18:00:09.089  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 18:00:09.089  1028  1110 D BluetoothManagerService: Message: 40
08-16 18:00:09.090  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 18:00:09.094  7165  7165 D BluetoothMap: Proxy object connected
08-16 18:00:09.094  7165  7165 D MapProfile: Bluetooth service connected
08-16 18:00:09.094  7165  7165 D BluetoothMap: getConnectedDevices()
,08-16 18:00:09.097  7285  7285 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.097  1936  2094 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 18:00:09.097  7285  7285 D BluetoothMapService: STATE_ON
08-16 18:00:09.098  7285  7875 V BluetoothMapService: getConnectedDevices()
08-16 18:00:09.099  7285  7285 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 18:00:09.099  7285  7285 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 18:00:09.100  7285  7285 V BluetoothMapService: Handler(): got msg=1
08-16 18:00:09.101  7530  7561 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 18:00:09.102  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 18:00:09.102  1936  2094 D LGBluetoothAPIService: Message: 100
08-16 18:00:09.102  1936  2094 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 18:00:09.102  7285  7285 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 18:00:09.102  7165  7165 D BluetoothInputDevice: Proxy object connected
08-16 18:00:09.102  7165  7165 D HidProfile: Bluetooth service connected
08-16 18:00:09.105  7285  7890 D BluetoothMapMasInstance: MAS initSocket()
08-16 18:00:09.105  7285  7890 D BluetoothMapMasInstance:   masId = 00
08-16 18:00:09.105  7285  7890 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 18:00:09.105  7285  7890 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 18:00:09.105  7285  7890 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 18:00:09.107  7165  7165 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 18:00:09.108  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:09.110  1028  1110 D BluetoothManagerService: Message: 30
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:09.114  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:09.115  7285  7890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:09.116  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:09.116  7285  7890 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 18:00:09.117  7285  7890 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 18:00:09.117  7285  7890 D BluetoothMapMasInstance: Accepting socket connection...
08-16 18:00:09.119  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:09.119  7285  7285 V BluetoothPbapService: Pbap Service onCreate
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:09.120  7042  7042 V io.jxcore.node.Connectivit,yMonitor:     - is Bluetooth enabled: true
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:09.120  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:09.120  7285  7285 V BluetoothPbapService: Starting PBAP service
08-16 18:00:09.120  7285  7752 D BluetoothAdapterProperties: Scan Mode:21
08-16 18:00:09.120  7285  7752 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 18:00:09.121  7285  7285 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 18:00:09.121  7285  7285 V BluetoothPbapService: Pbap Service onBind
08-16 18:00:09.123  7285  7285 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.123  7285  7285 V BluetoothPbapService: state: 12
08-16 18:00:09.123  7285  7285 V BluetoothPbapService: Handler(): got msg=1
08-16 18:00:09.124  7285  7285 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 18:00:09.125  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:09.126  7285  7891 V BluetoothPbapService: Pbap Service initSocket
08-16 18:00:09.126  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:09.126  1028  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:09.128  7285  7891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:09.130  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:09.131  7285  7891 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 18:00:09.131  7285  7891 V BluetoothPbapService: Succeed to create listening socket 
08-16 18:00:09.131  7285  7891 V BluetoothPbapService: Accepting socket connection...
08-16 18:00:09.133  7165  7165 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 18:00:09.136  1028  1110 D BluetoothManagerService: Message: 30
08-16 18:00:09.140  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 18:00:09.142  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 18:00:09.147  7285  7285 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:00:09.147  7285  7285 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.147  7285  7285 V BluetoothPbapReceiver: ***********state = 12
08-16 18:00:09.147  7165  7165 D BluetoothPbap: Proxy object connected
,08-16 18:00:09.150  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:00:09.150  7165  7165 D PbapServerProfile: Bluetooth service connected
08-16 18:00:09.151  2151  2151 D c       : Getting all permits...
08-16 18:00:09.151  2151  2151 D a       : Opening database...
08-16 18:00:09.154  7165  7165 D BluetoothA2dp: Proxy object connected
08-16 18:00:09.154  2151  2151 D a       : Opening database auth.proximity.permit_store...
,08-16 18:00:09.155  7165  7165 D A2dpProfile: Bluetooth service connected
08-16 18:00:09.155  2151  2151 D a       : Closing database...
08-16 18:00:09.161  7165  7165 D BluetoothHeadset: Proxy object connected
08-16 18:00:09.162  7165  7165 D HeadsetProfile: Bluetooth service connected
,08-16 18:00:09.169  7165  7165 D DockEventReceiver: finishStartingService: stopping service
08-16 18:00:09.175  7165  7165 D BluetoothPermissionRequest: onReceive
,08-16 18:00:09.177  7165  7165 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:00:09.179  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:00:09.183  7285  7285 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 18:00:09.185  7285  7285 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 18:00:09.193  7285  7285 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 18:00:09.222  7285  7285 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 18:00:09.223  7285  7285 V BtOppService: onCreate
08-16 18:00:09.227  7285  7285 V BluetoothOppNotification: send message
08-16 18:00:09.232  7285  7285 V BtOppService: Starting RfcommListener
08-16 18:00:09.241  7285  7285 D BluetoothOppPreference: Dumping Names:  
08-16 18:00:09.241  7285  7285 D BluetoothOppPreference: {}
,08-16 18:00:09.241  7285  7285 D BluetoothOppPreference: Dumping Channels:  
08-16 18:00:09.241  7285  7285 D BluetoothOppPreference: {}
08-16 18:00:09.242  7285  7285 V BtOppService: onStartCommand
,08-16 18:00:09.246  7285  7899 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:00:09.247  7285  7285 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.247  7285  7285 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:00:09.248  7285  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:00:09.248  7285  7896 V BtOppService: Deleted complete outbound shares, number =  0
08-16 18:00:09.250  7285  7285 V BluetoothOppNotification: new notify threadi!
08-16 18:00:09.251  7285  7285 V BluetoothOppNotification: send delay message
08-16 18:00:09.252  7285  7285 V BtOppService: start RfcommListener
08-16 18:00:09.255  7285  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 18:00:09.256  7285  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f50acb1 on behalf of 
08-16 18:00:09.257  7285  7285 V BtOppService: RfcommListener started
08-16 18:00:09.257  7285  7285 V BtOppService: ContentObserver received notification
,08-16 18:00:09.259  7285  7901 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 18:00:09.261  1028  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:09.261  7285  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bdda596 on behalf of 
08-16 18:00:09.263  7285  7900 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:00:09.264  7285  7901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:09.265  7285  7899 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:00:09.265  7285  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:00:09.266  7285  7896 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 18:00:09.267  7285  7896 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 18:00:09.269  7285  7901 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 18:00:09.269  7285  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dd76517 on behalf of 
08-16 18:00:09.270  7285  7901 V BtOppRfcommListener: Started RFCOMM listener....
08-16 18:00:09.270  7285  7896 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c4d3d04 on behalf of 
08-16 18:00:09.270  7285  7901 I BtOppRfcommListener: Accept thread started.
08-16 18:00:09.270  7285  7901 V BtOppRfcommListener: Accepting connection...
,08-16 18:00:09.274  7285  7899 V BluetoothOppNotification: update too frequent, put in queue
08-16 18:00:09.275  7285  7899 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:00:09.276  7285  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:09.281  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:09.281  7285  7285 V BluetoothFtpService: Ftp Service onCreate
08-16 18:00:09.281  7285  7285 I BluetoothFtpService: Ftp Service onCreate
08-16 18:00:09.281  7285  7285 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:00:09.281  7285  7285 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.282  7285  7285 V BluetoothFtpService: Starting Listening on sockets
08-16 18:00:09.282  7285  7285 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:09.282  7285  7285 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:09.282  7285  7285 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:09.282  7285  7285 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.282  7285  7285 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 18:00:09.282  7285  7285 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 18:00:09.460  1028  1989 I art     : Explicit concurrent mark sweep GC freed 95459(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.711ms total 181.023ms
,08-16 18:00:09.460  1028  1041 I art     : WaitForGcToComplete blocked for 106.580ms for cause HeapTrim
08-16 18:00:09.463  7285  7285 V BtOppService: ContentObserver received notification
08-16 18:00:09.465  7285  7285 V BluetoothFtpService: Handler(): got msg=1
08-16 18:00:09.466  7285  7285 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 18:00:09.467  7285  7285 V BluetoothFtpService: Ftp Service initSocket
08-16 18:00:09.469  7285  7902 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:00:09.469  7285  7902 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:00:09.470  1028  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:09.471  7285  7285 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:09.472  7285  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac68522 on behalf of 
08-16 18:00:09.473  7285  7900 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 18:00:09.473  7285  7902 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d633bb3 on behalf of 
,08-16 18:00:09.474  7285  7902 V BluetoothOppNotification: update too frequent, put in queue
08-16 18:00:09.478  7285  7902 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:00:09.480  7285  7285 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 18:00:09.481  7285  7285 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 18:00:09.481  7285  7900 V BluetoothOppNotification: outbound notification was removed.
08-16 18:00:09.481  7285  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:09.482  7285  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ee32570 on behalf of 
08-16 18:00:09.483  7285  7900 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:00:09.485  7285  7900 V BluetoothOppNotification: inbound notification was removed.
08-16 18:00:09.485  7285  7903 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 18:00:09.486  7285  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 18:00:09.488  7285  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bf40e9 on behalf of 
08-16 18:00:09.508  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:09.509  7285  7285 V BluetoothSapService: Sap Service onCreate
,08-16 18:00:09.511  7285  7285 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:09.511  7285  7285 V BluetoothSapService: state: 12
08-16 18:00:09.511  7285  7285 V BluetoothSapService: Starting SAP server process
08-16 18:00:09.513  7285  7285 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 18:00:09.508  7904  7904 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:09.514  7285  7905 V BluetoothSapService: Sap Service initRfcommSocket
08-16 18:00:09.508  7904  7904 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:09.515  1028  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:09.516  7285  7905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:09.517  7285  7905 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 18:00:09.517  7285  7905 V BluetoothSapService: Succeed to create listening socket 
08-16 18:00:09.517  7285  7905 V BluetoothSapService: Accepting socket connection...
08-16 18:00:09.526  7904  7904 V BT_SAP  : Event pipe created
08-16 18:00:09.526  7904  7904 V BT_SAP  : create_server_socket qcom.sap.server
08-16 18:00:09.526  7904  7904 V BT_SAP  : created socket fd 6
,08-16 18:00:09.972  1028  1532 D LGWifiP2pService: P2pDisabledState{ when=-9ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:00:09.972  1028  1532 D LGWifiP2pService: DefaultState{ when=-9ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:00:10.004  1028  1416 V AlarmManager: ELAPSED_WAKEUP set : Alarm{21e00e1b type 2 when 227109 com.google.android.gms} when 227109
,08-16 18:00:10.030  1028  1534 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 18:00:10.034  1028  1534 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 18:00:10.132  1028  1934 I ActivityManager: Killing 7693:com.lge.bnr/1000 (adj 15): empty #17
,08-16 18:00:10.171  1028  1571 W libprocessgroup: failed to open /acct/uid_1000/pid_7693/cgroup.procs: No such file or directory
,08-16 18:00:10.225  1028  1971 I ActivityManager: Killing 7191:com.lge.sync/1000 (adj 15): empty #17
,08-16 18:00:10.246  1028  1539 D WifiService: Client connection lost with reason: 4
,08-16 18:00:10.253  7285  7285 V BluetoothOppNotification: new notify threadi!
08-16 18:00:10.253  7285  7285 V BluetoothOppNotification: send delay message
08-16 18:00:10.254  7285  7916 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 18:00:10.256  7285  7916 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27c202a5 on behalf of 
08-16 18:00:10.256  7285  7916 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:00:10.258  7285  7916 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:10.260  7285  7916 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b07967a on behalf of 
08-16 18:00:10.260  7285  7916 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 18:00:10.264  7285  7916 V BluetoothOppNotification: outbound notification was removed.
,08-16 18:00:10.264  7285  7916 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 18:00:10.265  7285  7916 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e706e2b on behalf of 
,08-16 18:00:10.266  7285  7916 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:00:10.267  7285  7916 V BluetoothOppNotification: inbound notification was removed.
08-16 18:00:10.267  7285  7916 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 18:00:10.268  7285  7916 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7b23288 on behalf of 
08-16 18:00:10.271  1028  1899 W libprocessgroup: failed to open /acct/uid_1000/pid_7191/cgroup.procs: No such file or directory
08-16 18:00:10.964  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:10.964  1028  1043 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@34946bb8 mBinding = false
,08-16 18:00:11.004  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:00:11.005  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:00:11.005  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 18:00:11.006  1028  1110 D BluetoothManagerService: Message: 2
08-16 18:00:11.006  1028  1110 D BluetoothManagerService: Sending off request.
08-16 18:00:11.007  7285  7303 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 18:00:11.008  7285  7748 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 18:00:11.008  7285  7748 D BluetoothAdapterProperties: Setting state to 13
08-16 18:00:11.008  7285  7748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:00:11.009  7285  7748 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 18:00:11.009  7285  7748 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 18:00:11.011  7285  7752 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:00:11.013  7285  7748 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 18:00:11.018  7285  7748 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 18:00:11.021  7285  7890 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 18:00:11.021  7285  7891 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:00:11.022  7285  7901 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:00:11.022  7285  7905 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:00:11.022  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 18:00:11.022  7285  7817 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 18:00:11.027  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:00:11.027  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:00:11.027  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 18:00:11.028  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 18:00:11.028  7285  7817 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 18:00:11.035  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:11.035  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:11.037  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:11.037  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:11.039  7285  7903 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:00:11.047  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:11.047  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:00:11.051  7042  7042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:00:11.051  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:11.055  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:11.055  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 18:00:11.055  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 18:00:11.058  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:11.063  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:00:11.067  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:11.068  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:11.070  7285  7285 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:11.070  7285  7285 D BluetoothMapService: STATE_TURNING_OFF
08-16 18:00:11.070  7285  7285 V BluetoothMapService: Handler(): got msg=4
08-16 18:00:11.070  7285  7285 D BluetoothMapService: MAP Service closeService in
08-16 18:00:11.070  7285  7285 D BluetoothMapMasInstance: MAP Service shutdown
08-16 18:00:11.071  7285  7285 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:00:11.071  7285  7285 V BluetoothMapService: MAP Service closeService out
08-16 18:00:11.072  7285  7285 V BtOppService: Receiver DISABLED_ACTION 
08-16 18:00:11.072  7285  7285 I BtOppRfcommListener: stopping Accept Thread
08-16 18:00:11.072  7285  7285 V BtOppRfcommListener: close mBtServerSocket
,08-16 18:00:11.075  7285  7901 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 18:00:11.076  7285  7285 V BtOppRfcommListener: waiting for thread to terminate
08-16 18:00:11.076  7285  7285 V BtOppRfcommListener: done waiting for thread to terminate
08-16 18:00:11.079  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 18:00:11.089  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 18:00:11.093  7285  7285 V BtOppService: onDestroy
08-16 18:00:11.095  7285  7285 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 18:00:11.099  7285  7285 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:00:11.099  7285  7285 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:11.099  7285  7285 V BluetoothPbapReceiver: ***********state = 13
08-16 18:00:11.101  7285  7285 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 18:00:11.103  7285  7285 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:11.103  7285  7285 V BluetoothPbapService: state: 13
08-16 18:00:11.104  7285  7285 V BluetoothPbapService: Pbap Service closeService in
,08-16 18:00:11.109  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:00:11.114  7285  7285 V BluetoothPbapService: successfully stopped pbap service
08-16 18:00:11.114  7285  7285 V BluetoothPbapService: Pbap Service closeService out
08-16 18:00:11.115  7285  7285 V BluetoothPbapService: Pbap Service onDestroy
08-16 18:00:11.115  7285  7285 V BluetoothPbapService: Pbap Service closeService in
08-16 18:00:11.115  7285  7285 V BluetoothPbapService: Pbap Service closeService out
08-16 18:00:11.115  7285  7285 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 18:00:11.132  7165  7165 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:00:11.134  7165  7165 D BluetoothPbap: Proxy object disconnected
08-16 18:00:11.134  7165  7165 D PbapServerProfile: Bluetooth service disconnected
08-16 18:00:11.142  7165  7165 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 18:00:11.146  7165  7165 D BluetoothPermissionRequest: onReceive
08-16 18:00:11.146  7165  7165 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 18:00:11.153  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:00:11.157  7285  7285 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-16 18:00:11.157  7285  7285 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 18:00:11.158  7285  7285 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 18:00:11.163  7285  7285 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:11.163  7285  7285 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:00:11.164  7285  7285 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:00:11.164  7285  7285 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:11.165  7285  7285 V BluetoothFtpService: Ftp Service closeService
08-16 18:00:11.165  7285  7285 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 18:00:11.167  7285  7285 V BluetoothFtpService: successfully stopped ftp service
08-16 18:00:11.167  7285  7285 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:11.167  7285  7285 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:11.167  7285  7285 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:11.167  7285  7285 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:11.167  7285  7285 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 18:00:11.168  7285  7285 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 18:00:11.169  7285  7285 V BluetoothFtpService: Ftp Service onDestroy
08-16 18:00:11.169  7285  7285 V BluetoothFtpService: Ftp Service closeService
,08-16 18:00:11.174  7285  7285 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:11.174  7285  7285 V BluetoothSapService: state: 13
08-16 18:00:11.174  7285  7285 V BluetoothSapService: Stopping SAP server process
08-16 18:00:11.176  7285  7285 V BluetoothSapService: Sap Service closeSapService in
08-16 18:00:11.176  7285  7285 V BluetoothSapService: Close listen Socket : 
08-16 18:00:11.176  7285  7285 V BluetoothSapService: Close rfcomm Socket : 
08-16 18:00:11.177  7285  7285 V BluetoothSapService: Close sapd  Socket : 
08-16 18:00:11.178  7285  7285 V BluetoothSapService: Sap Service closeSapService out
,08-16 18:00:11.178  7285  7285 V BluetoothSapService: Sap Service onDestroy,
08-16 18:00:11.179  7285  7285 V BluetoothSapService: Sap Service closeSapService in
,08-16 18:00:11.179  7285  7285 V BluetoothSapService: Close listen Socket : 
,08-16 18:00:11.179  7285  7285 V BluetoothSapService: Close rfcomm Socket : ,
08-16 18:00:11.179  7285  7285 V BluetoothSapService: Close sapd  Socket : 
08-16 18:00:11.179  7285  7285 V BluetoothSapService: Sap Service closeSapService out
08-16 18:00:11.936  7285  7752 D bt_hci_bdroid: cleanup
,08-16 18:00:11.952  7285  7819 I bt_lpm  : LPM is already off!!!
08-16 18:00:11.952  7285  7860 I bt_userial_mct: exiting userial_read_thread
08-16 18:00:11.952  7285  7860 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 18:00:11.953  7285  7817 W bt-btif : ag scb idx 1 not allocated
08-16 18:00:11.953  7285  7817 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 18:00:11.953  7285  7817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:00:11.953  7285  7817 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 18:00:11.954  7285  7752 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 18:00:11.954  7285  7819 I bt_vendor: hw_epilog_process
08-16 18:00:11.955  7285  7752 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 18:00:11.955  7285  7752 D bt_userial_mct: userial_close
08-16 18:00:11.955  7285  7752 E bt_userial_mct: pthread_join() FAILED result:3
,08-16 18:00:11.955  7285  7752 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 18:00:11.961  7285  7752 D bt_hci_bdroid: set_power 0
08-16 18:00:11.961  7285  7752 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 18:00:11.961  7285  7752 I bt_vendor: bluetooth satus is on
08-16 18:00:11.961  7285  7752 I bt_vendor: bt-vendor : resetting BT status
08-16 18:00:11.961  7285  7752 I bt_vendor: Starting hciattach daemon
08-16 18:00:11.961  7285  7752 I bt_vendor: try to set false
,08-16 18:00:11.971  7285  7752 I bt_vendor: Starting hciattach daemon
08-16 18:00:11.971  7285  7752 I bt_vendor: try to set false
08-16 18:00:11.973  7285  7752 I bt_vendor: cleanup
08-16 18:00:11.974  7285  7817 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 18:00:11.974  7285  7752 I GKI_LINUX: GKI_exit_task 0 done
08-16 18:00:11.974  7285  7752 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 18:00:11.976  7285  7748 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 18:00:11.982  7285  7285 D HeadsetService: Received stop request...Stopping profile...
,08-16 18:00:11.988  7285  7285 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 18:00:11.988  7285  7285 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:00:11.988  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:11.989  7285  7788 D HeadsetStateMachine: Exit Disconnected: -1
08-16 18:00:11.993  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-16 18:00:11.994  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-16 18:00:11.994  1846  1846 D BluetoothHeadset: Proxy object disconnected
08-16 18:00:11.994  1028  1028 D BluetoothHeadset: Proxy object disconnected
08-16 18:00:11.994  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 18:00:11.995  7285  7285 D A2dpService: Received stop request...Stopping profile...
,08-16 18:00:11.998  7285  7809 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:00:12.001  7285  7748 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 18:00:12.002  7285  7285 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 18:00:12.004  7285  7285 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 18:00:12.004  7285  7285 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:00:12.004  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:12.005  1028  1028 D BluetoothA2dp: Proxy object disconnected
08-16 18:00:12.005  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 18:00:12.007  7285  7285 D HidService: Received stop request...Stopping profile...
08-16 18:00:12.007  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:12.009  7285  7285 D HealthService: Received stop request...Stopping profile...
08-16 18:00:12.009  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
,08-16 18:00:12.014  7285  7285 D PanService: Received stop request...Stopping profile...
08-16 18:00:12.015  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:12.016  7285  7285 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:00:12.017  7285  7285 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 18:00:12.017  7285  7285 D BtGatt.GattService: stop()
08-16 18:00:12.017  7285  7285 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 18:00:12.019  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:12.019  7285  7285 D HeadsetStateMachine: Unbinding service...
08-16 18:00:12.021  7285  7285 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:00:12.021  7285  7285 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:00:12.021  7285  7285 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:00:12.021  7285  7285 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:00:12.021  7285  7285 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 18:00:12.021  7285  7285 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:00:12.021  7285  7285 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 18:00:12.022  7285  7285 D BluetoothMapService: Received stop request...Stopping profile...
08-16 18:00:12.022  7285  7285 D BluetoothMapService: stop()
,08-16 18:00:12.025  7285  7285 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 18:00:12.025  7285  7285 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 18:00:12.027  7285  7285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2463fdc
08-16 18:00:12.028  7285  7285 I BluetoothA2dpServiceJni: cleanupNative
08-16 18:00:12.028  7285  7810 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:00:12.028  7285  7285 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:00:12.028  7285  7285 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:00:12.029  7285  7285 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:00:12.029  7285  7285 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:00:12.029  7285  7285 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:00:12.029  7285  7285 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:00:12.029  7285  7285 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:00:12.030  7285  7285 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:00:12.030  7285  7285 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 18:00:12.035  7285  7285 V BluetoothMapService: Handler(): got msg=4
08-16 18:00:12.035  7285  7285 D BluetoothMapService: MAP Service closeService in
08-16 18:00:12.035  7285  7285 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:00:12.035  7285  7285 V BluetoothMapService: MAP Service closeService out
,08-16 18:00:12.038  7285  7748 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:00:12.038  7285  7748 D BluetoothAdapterProperties: Setting state to 10
08-16 18:00:12.038  7285  7748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:00:12.040  7285  7285 D BluetoothMapService: cleanup()
08-16 18:00:12.040  7285  7285 D BluetoothMapService: MAP Service closeService in
08-16 18:00:12.040  7285  7285 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 18:00:12.040  7285  7285 V BluetoothMapService: MAP Service closeService out
08-16 18:00:12.041  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:12.041  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 18:00:12.041  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 18:00:12.042  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:12.042  7285  7748 I BluetoothAdapterState: Entering OffState
08-16 18:00:12.043  7165  7871 D BluetoothPan: onBluetoothStateChange on: false
08-16 18:00:12.043  7165  7871 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:00:12.044  7165  7871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:12.045  7165  7871 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:00:12.045  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:12.046  7165  7871 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 18:00:12.046  7165  7871 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:00:12.047  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:12.047  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:00:12.050  1846  2671 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:00:12.052  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 18:00:12.052  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 18:00:12.054  1028  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 18:00:12.054  1028  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 18:00:12.054  1028  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@34946bb8 mBinding = false
08-16 18:00:12.054  1028  1110 D BluetoothManagerService: Sending unbind request.
08-16 18:00:12.061  7285  7752 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 18:00:12.063  7285  7285 I GKI_LINUX: GKI_exit_task 1 done
08-16 18:00:12.063  7285  7285 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 18:00:12.063  7285  7285 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 18:00:12.065  7285  7285 I art     : --- WEIRD: removing null entry 248
08-16 18:00:12.065  7285  7285 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 18:00:12.065  7285  7285 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 18:00:12.065  7285  7285 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 18:00:12.067  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 18:00:12.069  7285  7285 I art     : System.exit called, status: 0
08-16 18:00:12.069  7285  7285 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 18:00:12.089   319   319 V AudioFlinger: 7285 died, releasing its sessions
08-16 18:00:12.089   319   319 V AudioFlinger:  pid 1846 @ 0
08-16 18:00:12.089   319   319 V AudioFlinger:  pid 3419 @ 1
08-16 18:00:12.089   319   319 V AudioFlinger:  pid 3419 @ 2
,08-16 18:00:12.093  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 18:00:12.094  1936  2094 D LGBluetoothAPIService: Message: 101
08-16 18:00:12.094  1936  2094 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 18:00:12.094  1936  2094 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 18:00:12.094  1936  2094 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 18:00:12.095  7165  7165 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 18:00:12.100  1028  1935 I ActivityManager: Process com.android.bluetooth (pid 7285) has died
08-16 18:00:12.100  1028  1935 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-16 18:00:12.100  1028  1935 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-16 18:00:12.107  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:12.110  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:00:12.110  1936  2094 D LGBluetoothAPIService: Message: 2
08-16 18:00:12.110  1936  2094 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 18:00:12.111  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:12.112  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:12.118  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 18:00:12.118  7165  7165 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 18:00:12.123  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 18:00:12.128  1598  1598 D BluetoothAdapter: 522976455: getState() :  mService = null. Returning STATE_OFF
08-16 18:00:12.128  1598  1598 D BluetoothAdapter: 522976455: getState() :  mService = null. Returning STATE_OFF
08-16 18:00:12.186  1028  2043 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7948 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 18:00:12.204  7165  7165 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:00:12.208  1028  1416 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2be770f7 type 2 when 229263 com.google.android.gms} when 229263
08-16 18:00:12.220   309  7973 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 18:00:12.220  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 18:00:12.273  7948  7948 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 18:00:12.274  7948  7948 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:00:12.274  7948  7948 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 18:00:12.275  7948  7948 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 18:00:12.293  7948  7948 D BluetoothAdapterApp: Loading JNI Library
,08-16 18:00:12.326  7948  7948 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d6fac44 Instance Count = 1
,08-16 18:00:12.333  7948  7948 D BluetoothAdapterApp: onCreate
08-16 18:00:12.356  7948  7948 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 18:00:12.357  7948  7948 D ProfileConfigQcom: Adding HeadsetService
,08-16 18:00:12.357  7948  7948 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-16 18:00:12.357  7948  7948 D ProfileConfigQcom: Adding A2dpService
08-16 18:00:12.357  7948  7948 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 18:00:12.357  7948  7948 D ProfileConfigQcom: Adding HidService
08-16 18:00:12.358  7948  7948 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-16 18:00:12.358  7948  7948 D ProfileConfigQcom: Adding HealthService
08-16 18:00:12.358  7948  7948 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 18:00:12.359  7948  7948 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 18:00:12.360  7948  7948 D ProfileConfigQcom: Adding PanService
08-16 18:00:12.360  7948  7948 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 18:00:12.360  7948  7948 D ProfileConfigQcom: Adding GattService
08-16 18:00:12.361  7948  7948 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 18:00:12.361  7948  7948 D ProfileConfigQcom: Adding BluetoothMapService
08-16 18:00:12.361  7948  7948 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 18:00:12.362  7948  7948 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:00:12.364  7948  7948 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:12.364  7948  7948 V BluetoothPbapReceiver: ***********state = 10
08-16 18:00:12.366  7948  7948 V LGMDMManagerInternal: Create singleton instance
,08-16 18:00:12.446  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:00:12.450  7165  7165 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 18:00:12.450  7948  7948 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 18:00:12.451  7948  7948 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 18:00:12.458  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 18:00:12.459  1936  2094 D LGBluetoothAPIService: Message: 100
08-16 18:00:12.459  1936  2094 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 18:00:12.474  7165  7165 D BluetoothPermissionRequest: onReceive
,08-16 18:00:12.477  7165  7165 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:00:12.477  7165  7165 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 18:00:12.480  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:00:12.487  7948  7948 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 18:00:12.500  7948  7948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:12.504  7948  7948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:12.505  7948  7948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:12.505  7948  7948 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:12.507  7948  7948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:12.507  7948  7948 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 18:00:12.516  7824  7824 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 18:00:13.965  1598  1598 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 18:00:13.992  1028  1468 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 18:00:14.007  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 18:00:14.074  1028  1028 D administrator: Handling package changes for user 0
,08-16 18:00:14.094  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:00:14.094  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:00:14.098  1028  1103 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7996 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-16 18:00:14.102  1598  1598 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 18:00:14.103  1598  1598 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 18:00:14.158  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 18:00:14.194  7996  7996 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 18:00:14.258  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 18:00:14.258  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 18:00:14.293  7996  7996 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:14.293  7996  7996 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:14.319  1028  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:00:14.327  1028  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 18:00:14.335  2466  2466 V GmsNetworkLocationProvi: DISABLE
08-16 18:00:14.335  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 18:00:14.370  1028  1101 D LocationProviderProxy: applying state to connected service
08-16 18:00:14.370  2466  2466 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 18:00:14.436  7996  8040 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 18:00:14.436  7996  8040 I Babel   : MmsConfig.loadMmsSettings
08-16 18:00:14.441  7996  8040 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 18:00:14.443  7996  8040 I Babel   : MmsConfig.loadFromDatabase
,08-16 18:00:14.472  7996  7996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:14.473  7996  8040 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 18:00:14.473  7996  8040 I Babel   : MmsConfig.loadFromResources
08-16 18:00:14.479  7996  8040 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 18:00:14.481  7996  8040 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 18:00:14.483  7996  8038 W AudioCapabilities: Unsupported mime audio/evrc
08-16 18:00:14.485  7996  8038 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 18:00:14.489  7996  8038 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 18:00:14.502  1810  8042 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 18:00:14.502  1810  8042 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 18:00:14.503  6479  6479 I AppUp4:CustModeStarterReceiver: onReceive
08-16 18:00:14.506  7996  8038 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 18:00:14.512  6479  6479 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@6aee3f3
08-16 18:00:14.513  6479  6479 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 18:00:14.513  6479  6479 D AppUp4:CustFacade: isPhone : true
08-16 18:00:14.513  6479  6479 D AppUp4:CustModeStarterReceiver: begin check event
08-16 18:00:14.513  6479  6479 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 18:00:14.514  7996  8038 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 18:00:14.514  1810  4818 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 18:00:14.518  7996  8038 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 18:00:14.538  7996  8038 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 18:00:14.546  7996  8038 W VideoCapabilities: Unsupported mime video/divx
08-16 18:00:14.548  7996  8038 W VideoCapabilities: Unsupported mime video/divx311
08-16 18:00:14.552  7996  8038 W VideoCapabilities: Unsupported mime video/divx4
08-16 18:00:14.553  1028  1934 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8045 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 18:00:14.557  1028  1934 I ActivityManager: Killing 7381:com.lge.email/u0a23 (adj 15): empty #17
08-16 18:00:14.578  7996  8038 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 18:00:14.594  7996  8038 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 18:00:14.598  7996  8038 W AudioCapabilities: Unsupported mime audio/eac3
08-16 18:00:14.599  7996  8038 W AudioCapabilities: Unsupported mime audio/ac3
08-16 18:00:14.600  7996  8038 W AudioCapabilities: Unsupported mime audio/g726
08-16 18:00:14.601  7996  8038 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 18:00:14.602  7996  8038 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 18:00:14.603  7996  8038 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 18:00:14.604  7996  8038 W VideoCapabilities: Unsupported mime video/theora
08-16 18:00:14.606  7996  8038 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 18:00:14.631  1028  1970 W libprocessgroup: failed to open /acct/uid_10023/pid_7381/cgroup.procs: No such file or directory
,08-16 18:00:14.660  8045  8045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:14.660  8045  8045 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 18:00:14.660  8045  8045 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 18:00:14.662  8045  8045 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 18:00:14.662  8045  8045 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 18:00:14.728  8045  8045 I SystemConfig: BUILD Country: EU
08-16 18:00:14.729  8045  8045 I SystemConfig: BUILD Operator: OPEN
,08-16 18:00:14.776  1028  1898 I ActivityManager: Killing 7261:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 18:00:14.903  1028  1571 W libprocessgroup: failed to open /acct/uid_10026/pid_7261/cgroup.procs: No such file or directory
,08-16 18:00:14.974  1028  1880 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8070 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 18:00:14.982  8045  8065 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 18:00:14.982  8045  8065 I SystemConfig: existFile = false
08-16 18:00:14.982  8045  8065 I SystemConfig: canReadFile = false
08-16 18:00:14.982  8045  8065 I SystemConfig: systemFeature RCS result false
08-16 18:00:14.982  8045  8065 D SystemConfig: refreshRcsSupport() :false
,08-16 18:00:15.040  1028  1540 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-16 18:00:15.045  8070  8070 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:15.046  8070  8070 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 18:00:15.046  8070  8070 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 18:00:15.046  8070  8070 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 18:00:15.156  8070  8070 I AppConfig: Total System Memory = 2995761152
,08-16 18:00:15.168  8070  8070 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 18:00:15.266  1028  1044 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8089 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:00:15.267  1028  1044 I ActivityManager: Killing 6385:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-16 18:00:15.374  1028  1935 W libprocessgroup: failed to open /acct/uid_1000/pid_6385/cgroup.procs: No such file or directory
,08-16 18:00:15.628  8089  8089 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 18:00:15.758  8089  8089 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 18:00:15.758  8089  8089 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:15.811  8089  8089 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 18:00:15.833  8089  8089 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 18:00:15.834  8089  8089 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 18:00:15.854  8089  8089 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 18:00:15.854  8089  8089 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 18:00:15.875  1028  1898 I ActivityManager: Killing 7426:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 18:00:15.977  1028  2007 W libprocessgroup: failed to open /acct/uid_10046/pid_7426/cgroup.procs: No such file or directory
,08-16 18:00:15.986  3497  4536 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 18:00:15.991  3497  4536 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3863dbc3 on behalf of 8089
08-16 18:00:15.997  4651  8129 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 18:00:16.038  1028  1971 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8130 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 18:00:16.062  8089  8089 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 18:00:16.084  8089  8089 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 18:00:16.111  8130  8130 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 18:00:16.132  8130  8130 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-16 18:00:16.132  8130  8130 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 18:00:16.132  8130  8130 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 18:00:16.132  8130  8130 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 18:00:16.132  8130  8130 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 18:00:16.132  8130  8130 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 18:00:16.149  1028  1898 I ActivityManager: Killing 7448:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 18:00:16.177  1028  1641 W libprocessgroup: failed to open /acct/uid_10057/pid_7448/cgroup.procs: No such file or directory
,08-16 18:00:16.449  1028  1880 V SIM_STK : Menu title from STK is T-Mobile
,08-16 18:00:16.464  4651  8129 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 467 ms] updated apps [took 467 ms] 
,08-16 18:00:16.507  1028  1416 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d62a87f type 2 when 233611 com.google.android.gms} when 233611
,08-16 18:00:16.513   309  8169 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 18:00:16.514  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 18:00:17.108  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:17.108  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18ea736 added. We now have 6 listener(s)
08-16 18:00:17.108  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:00:17.122  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:17.122  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a73d637 added. We now have 7 listener(s)
08-16 18:00:17.122  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:17.123  7042  7121 I System.out: IsBluetoothEnabled
08-16 18:00:17.125  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:17.125  1028  1043 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-16 18:00:17.126  1028  1110 D BluetoothManagerService: Message: 2
08-16 18:00:17.129  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:00:17.132  1028  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:17.132  1028  1970 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 18:00:17.150  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:00:17.151  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:00:17.151  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 18:00:17.152  1028  1110 D BluetoothManagerService: Message: 1
08-16 18:00:17.152  1028  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 18:00:17.177  1028  1110 D BluetoothManagerService: Message: 20
08-16 18:00:17.177  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a6f7538:true
,08-16 18:00:17.181  7948  7948 D BluetoothAdapterState: make
08-16 18:00:17.186  7948  7948 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 18:00:17.186  7948  7948 I bluedroid-qcom: init
08-16 18:00:17.187  7948  8176 I BluetoothAdapterState: Entering OffState
08-16 18:00:17.187  7948  7948 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 18:00:17.188  7948  7948 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 18:00:17.188  7948  7948 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 18:00:17.188  7948  7948 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 18:00:17.188  7948  7948 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 18:00:17.190  7948  7948 I bluedroid-qcom: get_profile_interface socket
08-16 18:00:17.190  7948  7948 I bluedroid-qcom: get_profile_interface map_client
,08-16 18:00:17.194  7948  8180 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 18:00:17.188  8179  8179 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:17.198  8179  8179 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:17.208  8179  8179 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 18:00:17.208  8179  8179 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 18:00:17.208  8179  8179 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 18:00:17.213  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 18:00:17.214  1028  1110 D BluetoothManagerService: Message: 40
08-16 18:00:17.214  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 18:00:17.215  7948  7975 I bluedroid-qcom: config_hci_snoop_log
08-16 18:00:17.216  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 18:00:17.216  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 18:00:17.217  7948  8180 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 18:00:17.218  8179  8179 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 18:00:17.220  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:00:17.221  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 18:00:17.222  7948  8180 D BluetoothAdapterProperties: Name is: G3
,08-16 18:00:17.228  8179  8179 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 18:00:17.228  8179  8179 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 18:00:17.232  7948  8176 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 18:00:17.232  7948  8176 D BluetoothAdapterProperties: Setting state to 11
08-16 18:00:17.232  7948  8176 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:00:17.233  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:17.233  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 18:00:17.233  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 18:00:17.253  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:17.256  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:00:17.261  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:17.269  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 18:00:17.276  7948  8176 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 18:00:17.282  7948  7948 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:00:17.283  7948  7948 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:17.283  7948  7948 V BluetoothPbapReceiver: ***********state = 11
08-16 18:00:17.285  7948  8176 D BluetoothBondStateMachine: make
,08-16 18:00:17.287  7948  8176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.287  7948  8176 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 18:00:17.287  7948  8176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.287  7948  8176 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 18:00:17.288  7948  8176 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 18:00:17.289  7948  8196 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 18:00:17.290  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:00:17.293  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:17.304  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:00:17.308  7948  7948 D HeadsetService: Received start request. Starting profile...
08-16 18:00:17.308  7948  7948 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:00:17.308  7948  7948 D LGBluetoothHfpAdapter: Version 1.6
08-16 18:00:17.309  7165  7165 D BluetoothPermissionRequest: onReceive
08-16 18:00:17.312  7948  7948 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:00:17.313  7948  7948 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:00:17.313  7948  7948 D HeadsetStateMachine: make
08-16 18:00:17.316  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:00:17.317  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:00:17.326  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:17.331  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 18:00:17.337  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:17.342  7948  8176 E BluetoothAdapterService: File transfer profiles supported!!
08-16 18:00:17.350  7948  7948 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:17.350  7948  7948 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:17.355  7948  7948 D HeadsetStateMachine: max_hf_connections = 1
08-16 18:00:17.355  7948  7948 I bluedroid-qcom: get_profile_interface handsfree
08-16 18:00:17.357  7948  7948 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 18:00:17.358   319  1375 V AudioPolicyService: registerClient() client 0xb1022da0, uid 1002
08-16 18:00:17.358   319  2183 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-16 18:00:17.358   319  2183 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:00:17.358   319  2183 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:00:17.359  7948  8176 V LGMDMManager: Create singleton instance
08-16 18:00:17.359  7948  7948 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 18:00:17.359   319   319 V AudioFlinger: registerClient() client 0xb14330e8, pid 7948
08-16 18:00:17.360   319  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:17.360   319  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:17.360  1028  1880 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:17.360  1028  1880 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:17.360  1598  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:17.360  1598  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:17.360  3419  3435 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:17.360  3419  3435 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:17.360  1846  2499 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:17.360  1846  2499 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 18:00:17.360  7948  7976 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 18:00:17.360  7948  7976 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 18:00:17.361  7948  7948 V ToneGenerator: Create Track: 0xb4928a80
08-16 18:00:17.361  7948  7948 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 18:00:17.361  7948  7948 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 18:00:17.361   319  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:17.361   319  1371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:17.361  1598  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:17.361  7948  7975 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:17.361  1598  1615 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:17.361  7948  7975 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 18:00:17.361  1846  1862 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:17.361  1846  1862 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:17.361   319  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:00:17.361   319  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 18:00:17.361   319  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:00:17.361  3419  3434 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:17.361   319  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 18:00:17.361  3419  3434 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:17.361  1028  1935 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 18:00:17.361  1028  1935 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 18:00:17.361   319  1376 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 18:00:17.362   319  2186 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 18:00:17.362   319  2186 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 18:00:17.362   319  2186 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 18:00:17.362   319  2186 V AudioPolicyManagerEx: getOutput() returns output 2
0,8-16 18:00:17.362  7948  8176 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 18:00:17.362  7948  7948 V AudioSystem: getLatency() output 2, latency 50
08-16 18:00:17.362  7948  7948 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 18:00:17.362  7948  7948 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 18:00:17.363   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:00:17.363   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 18:00:17.363   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 18:00:17.363   319  1375 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 18:00:17.363   319  1375 V AudioFlinger: createTrack() lSessionId: 23
08-16 18:00:17.364  7948  7948 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 18:00:17.365   319  1375 V AudioFlinger: acquiring 23 from 7948, for 7948
08-16 18:00:17.365   319  1375 V AudioFlinger:  added new entry for 23
08-16 18:00:17.365  7948  7948 V ToneGenerator: ToneGenerator INIT OK, time: 234485
08-16 18:00:17.365  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.366  7948  8198 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 18:00:17.366  7948  8198 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 18:00:17.366  7948  8198 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 18:00:17.366  7948  8198 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 18:00:17.367  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.367   319  2183 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7948
08-16 18:00:17.367   319  2183 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 18:00:17.367   319  2183 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 18:00:17.367   319  2183 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 18:00:17.367   319  2183 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 18:00:17.367   319  2183 V voice   : voice_set_parameters: exit with code(0)
08-16 18:00:17.367   319  2183 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 18:00:17.367   319  2183 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 18:00:17.368   319  2183 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 18:00:17.368   319  2183 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 18:00:17.368   319  2183 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 18:00:17.368   319  2183 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 18:00:17.368  7948  8198 V ToneGenerator: ToneGenerator destructor
08-16 18:00:17.368  7948  8198 V ToneGenerator: stopTone
08-16 18:00:17.368  7948  8198 V ToneGenerator: Delete Track: 0xb4928a80
08-16 18:00:17.368  7948  8198 V AudioTrack: ~AudioTrack, releasing session id from 7948 on behalf of 7948
08-16 18:00:17.368   319  1376 V AudioFlinger: releasing 23 from 7948 for 7948
08-16 18:00:17.368   319  1376 V AudioFlinger:  decremented refcount to 0
08-16 18:00:17.368   319  1376 V AudioFlinger: purging stale effects
08-16 18:00:17.368   319  1376 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 18:00:17.368   319  1376 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 18:00:17.368  7948  7948 D A2dpService: Received start request. Starting profile...
08-16 18:00:17.369   319  1267 V AudioPolicyService: AudioCommandThread() waking up
08-16 18:00:17.369   319  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 18:00:17.369   319  1267 V AudioPolicyManager: releaseOutput() 2
08-16 18:00:17.369   319  1267 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 18:00:17.369   319  1376 V AudioFlinger: PlaybackThread::Track destructor
08-16 18:00:17.369   319  1376 V AudioFlinger: removeClient_l() pid 7948, calling pid 319
08-16 18:00:17.369  7948  7948 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 18:00:17.370  7948  7948 V Avrcp   : make
08-16 18:00:17.371  7948  7948 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 18:00:17.371  7948  7948 I bluedroid-qcom: get_profile_interface avrcp
08-16 18:00:17.381  7948  7948 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 18:00:17.383  7948  7948 E AudioManager: No RCC entry present to update
08-16 18:00:17.383  7948  7948 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 18:00:17.388  7948  7948 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 18:00:17.390  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 18:00:17.390  7948  7948 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 18:00:17.395  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 18:00:17.536  1028  2026 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:17.536  1028  2026 V SIM_STK : Menu title from STK is T-Mobile
,08-16 18:00:17.645  1028  1989 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 18:00:17.656  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 18:00:17.662  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 18:00:17.662  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 18:00:17.662  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 18:00:17.662  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-16 18:00:17.663  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:00:17.663  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 18:00:17.663  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 18:00:17.663  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 18:00:17.663  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:00:17.663  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 18:00:17.663  7948  7948 I BluetoothA2dpServiceJni: classInitNative
08-16 18:00:17.663  7948  7948 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:00:17.663  7948  7948 D A2dpStateMachine: make
08-16 18:00:17.665  7948  7948 I bluedroid-qcom: get_profile_interface a2dp
08-16 18:00:17.665  7948  8208 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 18:00:17.668  7948  7948 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:00:17.668  7948  7948 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 18:00:17.669  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.669  7948  8207 D A2dpStateMachine: Enter Disconnected: -2
08-16 18:00:17.670  7948  7948 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 18:00:17.672  7948  7948 D HidService: Received start request. Starting profile...
08-16 18:00:17.672  7948  7948 I bluedroid-qcom: get_profile_interface hidhost
08-16 18:00:17.672  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.672  7948  7948 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 18:00:17.673  7948  7948 D HealthService: Received start request. Starting profile...
08-16 18:00:17.676  7948  7948 I bluedroid-qcom: get_profile_interface health
08-16 18:00:17.677  7948  7948 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 18:00:17.677  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.678  7948  7948 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 18:00:17.679  7948  7948 D PanService: Received start request. Starting profile...
08-16 18:00:17.679  7948  7948 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:00:17.679  7948  7948 I bluedroid-qcom: get_profile_interface pan
,08-16 18:00:17.685  7948  7948 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 18:00:17.685  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.686  7948  7948 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 18:00:17.689  7948  7948 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:00:17.690  7948  7948 D BtGatt.GattService: Received start request. Starting profile...
08-16 18:00:17.690  7948  7948 D BtGatt.GattService: start()
08-16 18:00:17.690  7948  7948 I bluedroid-qcom: get_profile_interface gatt
08-16 18:00:17.690  7948  7948 D BtGatt.AdvertiseManager: advertise manager created
,08-16 18:00:17.699  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.700  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:17.700  7948  7948 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 18:00:17.701  7948  7948 V BluetoothMapService: BluetoothMapBinder()
08-16 18:00:17.701  7948  7948 D BluetoothMapService: Received start request. Starting profile...
08-16 18:00:17.701  7948  7948 D BluetoothMapService: start()
08-16 18:00:17.704  7948  7948 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 18:00:17.704  7948  7948 D BluetoothMapEmailAppObserver: createReceiver()
08-16 18:00:17.705  7948  7948 D BluetoothMapEmailAppObserver: initObservers()
08-16 18:00:17.705  7948  7948 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 18:00:17.711  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
,08-16 18:00:17.711  7948  7948 D HeadsetStateMachine: Proxy object connected
08-16 18:00:17.712  7948  7948 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 18:00:17.712  7948  7948 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 18:00:17.718  7948  7948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:17.719  7948  8198 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 18:00:17.720  7948  8198 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:00:17.721  7948  7948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:17.721  7948  8198 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 18:00:17.724  7948  7948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 18:00:17.725  7948  7948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:17.732  7948  7948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:17.732  7948  7948 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 18:00:17.734  7948  7948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 18:00:17.736  7948  7948 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 18:00:17.736  7948  7948 V BluetoothMapService: Handler(): got msg=1
,08-16 18:00:17.737  7948  8176 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 18:00:17.737  7948  8176 I bluedroid-qcom: enable
08-16 18:00:17.738  7948  8176 I bt_hci_bdroid: init
08-16 18:00:17.738  7948  7948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:17.738  7948  7948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:17.738  7948  7948 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:17.738  7948  7948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:17.738  7948  7948 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-16 18:00:17.740  7948  8215 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 18:00:17.741  7948  8176 I bt_vendor: bt-vendor : init
08-16 18:00:17.741  7948  8176 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 18:00:17.741  7948  8176 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 18:00:17.741  7948  8176 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 18:00:17.741  7948  8176 D bt_userial_mct: userial_init
08-16 18:00:17.741  7948  8215 I bt-btu  : btu_task pending for preload complete event
08-16 18:00:17.742  7948  8176 D bt_hci_bdroid: set_power 1
08-16 18:00:17.742  7948  8176 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 18:00:17.742  7948  8176 I bt_vendor: Starting hciattach daemon
08-16 18:00:17.742  7948  8176 I bt_vendor: try to set true
08-16 18:00:17.738  8218  8218 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:17.738  8218  8218 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:17.783  8219  8219 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 18:00:17.873  8225  8225 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 18:00:17.896  8226  8226 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:00:17.948  8228  8228 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:00:17.963  8229  8229 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 18:00:17.976  8230  8230 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 18:00:17.987  8231  8231 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 18:00:18.011  8233  8233 I libmdmdetect: ESOC framework not supported
,08-16 18:00:18.013  8233  8233 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-16 18:00:18.024  8233  8233 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 18:00:18.025  8233  8233 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-16 18:00:18.025  8233  8233 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-16 18:00:18.025  8233  8233 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 18:00:18.025  8233  8233 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-16 18:00:18.025  8233  8233 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 18:00:18.025  8233  8233 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 18:00:18.077  8233  8234 E QC-QMI  : qmi_client [8233] 15: failed to locate client data
08-16 18:00:18.078   463   463 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 18:00:18.078   463   463 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 18:00:18.142  8235  8235 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 18:00:18.179  8239  8239 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:00:18.251  7948  8176 I bt_vendor: bluetooth satus is on
,08-16 18:00:18.251  7948  8176 D bt_hci_bdroid: preload
,08-16 18:00:18.258  7948  8217 D bt_userial_mct: userial_open(port:0)
,08-16 18:00:18.258  7948  8217 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 18:00:18.263  7948  8217 I bt_vendor: Done intiailizing UART
08-16 18:00:18.268  7948  8217 I bt_vendor: Done intiailizing UART
08-16 18:00:18.268  7948  8217 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 18:00:18.269  7948  8217 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-16 18:00:18.277  7948  8215 I bt-btu  : btu_task received preload complete event
,08-16 18:00:18.278  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-16 18:00:18.278  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 18:00:18.282  7948  8244 D bt_userial_mct: Entering userial_read_thread()
08-16 18:00:18.291  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 18:00:18.305  7948  8215 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 18:00:18.416  7948  8215 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 18:00:18.416  7948  8215 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0205061 
08-16 18:00:18.416  7948  8215 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0205061 
,08-16 18:00:18.472  7948  8180 E bt-btif : Calling BTA_HhEnable
,08-16 18:00:18.472  7948  8180 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 18:00:18.473  7948  8180 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 18:00:18.485  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-16 18:00:18.485  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-16 18:00:18.485  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 18:00:18.486  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 18:00:18.486  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 18:00:18.489  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 18:00:18.489  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 18:00:18.494  7948  8180 D BluetoothAdapterProperties: Name is: G3
,08-16 18:00:18.503  7948  8180 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:00:18.503  7948  8180 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:00:18.503  7948  8180 D bt_hci_bdroid: postload
08-16 18:00:18.504  7948  8217 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:18.505  7948  8180 D bte_conf: Device ID record 1 : primary
08-16 18:00:18.505  7948  8180 D bte_conf:   vendorId            = 00c4
08-16 18:00:18.505  7948  8180 D bte_conf:   vendorIdSource      = 0001
08-16 18:00:18.505  7948  8180 D bte_conf:   product             = 13a1
08-16 18:00:18.505  7948  8180 D bte_conf:   version             = 1000
08-16 18:00:18.505  7948  8180 D bte_conf:   clientExecutableURL = 
08-16 18:00:18.505  7948  8180 D bte_conf:   serviceDescription  = 
08-16 18:00:18.505  7948  8180 D bte_conf:   documentationURL    = 
08-16 18:00:18.506  7948  8180 D bte_conf: bte_load_did_conf no section named DID2.
08-16 18:00:18.506  7948  8215 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 18:00:18.507  7948  8217 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:18.510  7948  8176 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 18:00:18.511  7948  8176 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:00:18.511  7948  8176 D BluetoothAdapterProperties: State =  11
08-16 18:00:18.511  7948  8176 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 18:00:18.511  7948  8176 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 18:00:18.512  7948  8176 D BluetoothAdapterProperties: Setting state to 12
08-16 18:00:18.512  7948  8176 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 18:00:18.512  7948  8180 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 18:00:18.512  7948  8180 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 18:00:18.508  8246  8246 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:18.518  8246  8246 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:18.524  1028  1110 D BluetoothManagerService: Message: 60
08-16 18:00:18.524  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 18:00:18.524  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 18:00:18.525  7948  8217 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 18:00:18.538  7948  8215 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:18.538  7948  8215 W bt-smp  : Plain text(LSB ~ MSB) = 76 b1 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:18.538  7948  8215 W bt-smp  : Encrypted text(LSB ~ MSB) = bc f5 5c f4 15 e6 5e d9 65 9f 2f c1 91 57 04 be 
,08-16 18:00:18.542  7948  8217 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 18:00:18.542  7948  8215 W bt-btm  : Stopping oneshot timer
08-16 18:00:18.542  7948  8244 E bt_mct  : hci lib postload completed
08-16 18:00:18.549  7948  8176 I BluetoothAdapterState: Entering On State
08-16 18:00:18.556  7948  8180 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:00:18.556  7948  8180 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 18:00:18.563  1846  2671 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:18.569  7948  8176 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 18:00:18.569  7948  8176 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 18:00:18.569  7948  8176 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 18:00:18.572  7948  8176 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 18:00:18.585  7948  8215 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:18.585  7948  8215 W bt-smp  : Plain text(LSB ~ MSB) = 2d da 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:18.585  7948  8215 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b 9b 3c 49 c3 a1 46 aa 11 94 17 d6 b9 23 1e f6 
,08-16 18:00:18.588  7948  8215 W bt-btm  : Stopping oneshot timer
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:18.590  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:18.600  7948  8176 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 18:00:18.610  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:18.611  7948  8215 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:18.612  7948  8215 W bt-smp  : Plain text(LSB ~ MSB) = db fe 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:18.612  7948  8215 W bt-smp  : Encrypted text(LSB ~ MSB) = 73 a4 b7 84 50 06 75 47 46 07 24 88 7c 37 0b 52 
08-16 18:00:18.612  7948  8215 W bt-btm  : Stopping oneshot timer
08-16 18:00:18.615  1846  1846 D BluetoothHeadset: Proxy object connected
,08-16 18:00:18.622  7165  7871 D BluetoothPan: onBluetoothStateChange on: true
08-16 18:00:18.622  7165  7871 D BluetoothPan: onBluetoothStateChange call bindService
08-16 18:00:18.646  7948  8215 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 18:00:18.646  7948  8215 W bt-smp  : Plain text(LSB ~ MSB) = f2 af 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:18.646  7948  8215 W bt-smp  : Encrypted text(LSB ~ MSB) = e7 44 42 c8 5e 8a c6 7f 28 5c 26 ec 70 34 91 9d 
08-16 18:00:18.646  7948  8215 W bt-btm  : Stopping oneshot timer
,08-16 18:00:18.652  7165  7871 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:00:18.657  7165  7187 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:18.659  7165  7187 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:00:18.661  8263  8263 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 18:00:18.663  7948  8215 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-16 18:00:18.663  7948  8215 W bt-smp  : Plain text(LSB ~ MSB) = 58 27 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 18:00:18.663  7948  8215 W bt-smp  : Encrypted text(LSB ~ MSB) = fa c5 de c3 54 99 67 8d da f2 90 8c 72 30 a4 12 
08-16 18:00:18.663  7948  8215 W bt-btm  : Stopping oneshot timer
08-16 18:00:18.664  7165  7165 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:00:18.664  7165  7165 D PanProfile: Bluetooth service connected
08-16 18:00:18.669  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:18.669  7165  7165 D BluetoothMap: Proxy object connected
08-16 18:00:18.669  7165  7165 D MapProfile: Bluetooth service connected
08-16 18:00:18.669  7165  7165 D BluetoothMap: getConnectedDevices()
08-16 18:00:18.670  7948  8266 V BluetoothMapService: getConnectedDevices()
08-16 18:00:18.672  7165  7165 D BluetoothHeadset: Proxy object connected
08-16 18:00:18.672  7165  7165 D HeadsetProfile: Bluetooth service connected
,08-16 18:00:18.675  1846  1846 D BluetoothHeadset: Proxy object connected
08-16 18:00:18.676  7165  7186 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:00:18.678  7165  7165 D BluetoothA2dp: Proxy object connected
08-16 18:00:18.678  7165  7165 D A2dpProfile: Bluetooth service connected
08-16 18:00:18.679  7165  7187 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 18:00:18.682  7165  7165 D BluetoothInputDevice: Proxy object connected
08-16 18:00:18.682  7165  7165 D HidProfile: Bluetooth service connected
08-16 18:00:18.683  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:18.684  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:00:18.684  1028  1028 D BluetoothHeadset: Proxy object connected
08-16 18:00:18.684  1846  2499 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:00:18.686  1846  1846 D BluetoothHeadset: Proxy object connected
,08-16 18:00:18.687  1028  1028 D BluetoothA2dp: Proxy object connected
08-16 18:00:18.689  1028  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 18:00:18.689  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 18:00:18.691  1598  1598 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 18:00:18.694  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:18.694  1936  2094 D LGBluetoothAPIService: Message: 1
08-16 18:00:18.694  1936  2094 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 18:00:18.694  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:18.694  1936  2094 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 18:00:18.695  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 18:00:18.695  1936  2094 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 18:00:18.695  1028  1110 D BluetoothManagerService: Message: 40
08-16 18:00:18.695  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 18:00:18.698  7948  7948 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:18.698  7948  7948 D BluetoothMapService: STATE_ON
08-16 18:00:18.701  7165  7165 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 18:00:18.702  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 18:00:18.715  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:18.716  7948  7948 V BluetoothPbapService: Pbap Service onCreate
08-16 18:00:18.716  7948  7948 V BluetoothPbapService: Starting PBAP service
08-16 18:00:18.717  7948  7948 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 18:00:18.717  7948  7948 V BluetoothMapService: Handler(): got msg=1
08-16 18:00:18.718  7948  7948 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 18:00:18.718  7948  7948 V BluetoothPbapService: Pbap Service onBind
08-16 18:00:18.719  7948  8272 D BluetoothMapMasInstance: MAS initSocket()
08-16 18:00:18.720  7948  8272 D BluetoothMapMasInstance:   masId = 00
08-16 18:00:18.720  7948  8272 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 18:00:18.720  7948  8272 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 18:00:18.720  7948  8272 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-16 18:00:18.843  1028  1934 I art     : Explicit concurrent mark sweep GC freed 27805(1354KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.890ms total 139.810ms
,08-16 18:00:18.845  1028  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:18.846  7948  7948 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:18.846  7948  7948 V BluetoothPbapService: state: 12
08-16 18:00:18.846  7948  7948 V BluetoothPbapService: Handler(): got msg=1
08-16 18:00:18.849  7948  7948 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 18:00:18.850  7948  7948 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 18:00:18.850  7948  7948 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:18.850  7948  7948 V BluetoothPbapReceiver: ***********state = 12
08-16 18:00:18.856  2151  2151 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:00:18.857  2151  2151 D c       : Getting all permits...
08-16 18:00:18.857  2151  2151 D a       : Opening database...
08-16 18:00:18.858  7165  7165 D BluetoothPbap: Proxy object connected
08-16 18:00:18.858  7165  7165 D PbapServerProfile: Bluetooth service connected
,08-16 18:00:18.859  7948  8274 V BluetoothPbapService: Pbap Service initSocket
08-16 18:00:18.860  7948  8272 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:18.862  2151  2151 D a       : Opening database auth.proximity.permit_store...
08-16 18:00:18.863  2151  2151 D a       : Closing database...
08-16 18:00:18.864  1028  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:18.865  7165  7165 D DockEventReceiver: finishStartingService: stopping service
08-16 18:00:18.867  7948  8272 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 18:00:18.868  7948  8272 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 18:00:18.868  7948  8272 D BluetoothMapMasInstance: Accepting socket connection...
08-16 18:00:18.869  7948  8180 D BluetoothAdapterProperties: Scan Mode:21
08-16 18:00:18.870  7948  8180 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 18:00:18.870  7948  8274 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:18.873  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:00:18.876  7948  8274 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 18:00:18.877  7948  8274 V BluetoothPbapService: Succeed to create listening socket 
08-16 18:00:18.877  7948  8274 V BluetoothPbapService: Accepting socket connection...
08-16 18:00:18.906  7165  7165 D BluetoothPermissionRequest: onReceive
,08-16 18:00:18.916  7165  7165 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 18:00:18.919  7165  7165 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 18:00:18.924  7948  7948 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-16 18:00:18.927  7948  7948 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 18:00:18.938  7948  7948 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 18:00:18.970  7948  7948 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 18:00:18.971  7948  7948 V BtOppService: onCreate
,08-16 18:00:18.976  7948  7948 V BluetoothOppNotification: send message
08-16 18:00:18.981  7948  7948 V BtOppService: Starting RfcommListener
08-16 18:00:18.992  7948  7948 D BluetoothOppPreference: Dumping Names:  
08-16 18:00:18.993  7948  7948 D BluetoothOppPreference: {}
08-16 18:00:18.993  7948  7948 D BluetoothOppPreference: Dumping Channels:  
08-16 18:00:18.993  7948  7948 D BluetoothOppPreference: {}
,08-16 18:00:18.997  7948  7948 V BtOppService: onStartCommand
08-16 18:00:19.005  7948  7948 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:00:19.006  7948  7948 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 18:00:19.008  7948  8281 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:00:19.012  7948  7948 V BluetoothOppNotification: new notify threadi!
08-16 18:00:19.014  7948  7948 V BluetoothOppNotification: send delay message
08-16 18:00:19.014  7948  8278 V BtOppService: Deleted complete outbound shares, number =  0
08-16 18:00:19.015  7948  7948 V BtOppService: start RfcommListener
08-16 18:00:19.018  7948  8282 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 18:00:19.018  7948  8278 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 18:00:19.019  7948  8278 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 18:00:19.020  7948  8281 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-16 18:00:19.025  7948  7948 V BtOppService: RfcommListener started
08-16 18:00:19.027  7948  8278 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f50acb1 on behalf of 
08-16 18:00:19.027  7948  8282 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bdda596 on behalf of 
08-16 18:00:19.031  7948  8283 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 18:00:19.032  1028  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:19.033  7948  8281 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dd76517 on behalf of 
08-16 18:00:19.033  7948  8282 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:00:19.035  7948  8283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:00:19.036  7948  8281 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:00:19.037  7948  8283 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 18:00:19.037  7948  8283 V BtOppRfcommListener: Started RFCOMM listener....
08-16 18:00:19.038  7948  8283 I BtOppRfcommListener: Accept thread started.
08-16 18:00:19.038  7948  8283 V BtOppRfcommListener: Accepting connection...
08-16 18:00:19.039  7948  8282 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:19.042  7948  8282 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c4d3d04 on behalf of 
08-16 18:00:19.043  7948  8282 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 18:00:19.046  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:19.046  7948  8282 V BluetoothOppNotification: outbound notification was removed.
08-16 18:00:19.046  7948  8282 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:19.046  7948  7948 V BluetoothFtpService: Ftp Service onCreate
08-16 18:00:19.046  7948  7948 I BluetoothFtpService: Ftp Service onCreate
08-16 18:00:19.046  7948  7948 V BluetoothFtpService: Ftp Service onStartCommand
08-16 18:00:19.046  7948  7948 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:19.046  7948  7948 V BluetoothFtpService: Starting Listening on sockets
08-16 18:00:19.047  7948  7948 V BtOppService: ContentObserver received notification
08-16 18:00:19.047  7948  7948 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 18:00:19.047  7948  7948 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 18:00:19.047  7948  7948 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 18:00:19.047  7948  7948 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:19.048  7948  7948 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 18:00:19.048  7948  7948 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 18:00:19.049  7948  8284 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:00:19.050  7948  8284 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:00:19.050  7948  8282 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac68522 on behalf of 
08-16 18:00:19.051  7948  7948 V BtOppService: ContentObserver received notification
08-16 18:00:19.051  7948  7948 V BluetoothFtpService: Handler(): got msg=1
08-16 18:00:19.053  7948  7948 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 18:00:19.053  7948  8282 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:00:19.053  7948  7948 V BluetoothFtpService: Ftp Service initSocket
08-16 18:00:19.055  7948  8284 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d633bb3 on behalf of 
08-16 18:00:19.056  7948  8284 V BluetoothOppNotification: update too frequent, put in queue
08-16 18:00:19.059  7948  8284 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 18:00:19.059  7948  8284 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 18:00:19.059  7948  8282 V BluetoothOppNotification: inbound notification was removed.
08-16 18:00:19.060  7948  8282 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 18:00:19.063  7948  8284 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ee32570 on behalf of 
08-16 18:00:19.064  7948  8284 V BluetoothOppNotification: update too frequent, put in queue
,08-16 18:00:19.065  7948  8282 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bf40e9 on behalf of 
08-16 18:00:19.065  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:19.065  7948  8284 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 18:00:19.067  7948  7948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:19.069  7948  7948 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 18:00:19.070  7948  7948 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 18:00:19.072  7948  8285 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 18:00:19.106  7948  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f8668e5
08-16 18:00:19.106  7948  7948 V BluetoothSapService: Sap Service onCreate
,08-16 18:00:19.108  7948  7948 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:00:19.108  7948  7948 V BluetoothSapService: state: 12
08-16 18:00:19.108  7948  7948 V BluetoothSapService: Starting SAP server process
08-16 18:00:19.111  7948  7948 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 18:00:19.108  8286  8286 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:19.108  8286  8286 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:19.114  7948  8287 V BluetoothSapService: Sap Service initRfcommSocket
08-16 18:00:19.115  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:19.117  7948  8287 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:00:19.120  7948  8287 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 18:00:19.120  7948  8287 V BluetoothSapService: Succeed to create listening socket 
08-16 18:00:19.121  7948  8287 V BluetoothSapService: Accepting socket connection...
,08-16 18:00:19.142  8286  8286 V BT_SAP  : Event pipe created
,08-16 18:00:19.143  8286  8286 V BT_SAP  : create_server_socket qcom.sap.server
08-16 18:00:19.143  8286  8286 V BT_SAP  : created socket fd 6
,08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:19.197  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:00:19.199  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:00:19.202  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:19.202  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42127a4 added. We now have 8 listener(s)
,08-16 18:00:19.202  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:19.207  1028  1043 D WifiServiceImplEx: setWifiEnabled: false pid=7042, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 18:00:19.208  1028  1043 D WifiService: setWifiEnabled: false pid=7042, uid=10118
08-16 18:00:19.208  1028  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 18:00:19.221  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:19.224  1028  1898 D WifiServiceImplEx: setWifiEnabled: true pid=7042, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 18:00:19.225  1028  1898 D WifiService: setWifiEnabled: true pid=7042, uid=10118
08-16 18:00:19.225  1028  1898 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:00:19.242  1028  1534 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 18:00:19.242  1028  1534 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 18:00:19.243  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 18:00:19.243  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:00:19.243  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 18:00:19.243  1028  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 18:00:19.243  1028  1534 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 18:00:19.244  1028  1534 E WifiHW  : unknown target_country: EU , set to default
08-16 18:00:19.244  1028  1534 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 18:00:19.244  1028  1534 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 18:00:19.244  1028  1534 I WifiUtil: gEnableBmps=1
08-16 18:00:19.244  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 18:00:19.245  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 18:00:19.245  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-16 18:00:19.928   309   886 D SoftapController: Softap fwReload - Ok
,08-16 18:00:19.937  1028  1534 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (689ms)
08-16 18:00:19.945   309   886 D CommandListener: Setting iface cfg
08-16 18:00:19.945   309   886 D CommandListener: Trying to bring down wlan0
,08-16 18:00:19.960  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 18:00:19.979   309   886 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:00:19.982  1028  1110 D Tethering: InitialState.processMessage what=4
08-16 18:00:19.999  1028  1534 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 18:00:20.001  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:00:19.998  8307  8307 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 18:00:20.008  8307  8307 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:20.039  7948  7948 V BluetoothOppNotification: new notify threadi!
,08-16 18:00:20.046  7948  7948 V BluetoothOppNotification: send delay message
,08-16 18:00:20.049  7948  8321 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 18:00:20.049  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:00:20.049  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:00:20.049  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:00:20.049  7165  7165 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:00:20.051  7948  8321 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27c202a5 on behalf of 
08-16 18:00:20.052  7948  8321 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 18:00:20.054  7948  8321 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:20.055  7948  8321 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b07967a on behalf of 
08-16 18:00:20.055  7948  8321 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 18:00:20.056  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:00:20.056  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:00:20.056  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:00:20.060  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 18:00:20.064  8307  8307 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 18:00:20.070  1028  1534 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 18:00:20.070  1028  1534 D WifiMonitor: connecting to supplicant
08-16 18:00:20.084  7165  7165 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:00:20.084  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 18:00:20.084  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:00:20.084  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:00:20.084  7165  7165 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:00:20.084  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 18:00:20.084  7165  7165 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 18:00:20.090  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 18:00:20.093  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:20.094  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:20.095  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 18:00:20.096  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:00:20.096  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:00:20.096  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:00:20.096  7165  7165 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 18:00:20.097  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:00:20.097  7165  7165 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:00:20.097  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 18:00:20.097  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:00:20.097  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:00:20.097  7165  7165 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:00:20.098  7165  7165 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:00:20.099  7948  8321 V BluetoothOppNotification: outbound notification was removed.
08-16 18:00:20.099  7948  8321 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 18:00:20.099  8307  8307 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:00:20.100  7948  8321 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e706e2b on behalf of 
08-16 18:00:20.101  7948  8321 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 18:00:20.103  7948  8321 V BluetoothOppNotification: inbound notification was removed.
08-16 18:00:20.103  7948  8321 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 18:00:20.104  7948  8321 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7b23288 on behalf of 
08-16 18:00:20.107  8307  8307 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 18:00:20.146  1028  1935 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8325 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 18:00:20.178  8307  8307 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:00:20.204  8307  8307 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 18:00:20.212  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 18:00:20.215  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:00:20.216  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 18:00:20.217  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:00:20.218  1028  1534 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 18:00:20.218  1028  8343 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 18:00:20.218  1028  8343 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 18:00:20.219  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-16 18:00:20.220  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:20.221  1028  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:20.222  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:20.223  1028  1534 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 18:00:20.224  1028  1534 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 18:00:20.225  1028  1534 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 18:00:20.226  1028  1534 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 18:00:20.226  1028  1534 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 18:00:20.241  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:00:20.241  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 18:00:20.241  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:00:20.242  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 18:00:20.242  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 18:00:20.242  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 18:00:20.242  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:20.257  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:00:20.260  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:20.260  1028  1640 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 18:00:20.263  1028  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 18:00:20.263  1028  1534 E WifiStateMachine: useWiFiOffloading() : false
08-16 18:00:20.263  1028  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 18:00:20.264  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.264  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.264  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.264  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.264  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 18:00:20.265  1028  1534 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 18:00:20.266  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 18:00:20.266  1028  1534 D WifiNative-wlan0: SET update_config 1: returned true
08-16 18:00:20.266  1028  1534 D WifiConfigStore: Loading config and enabling all networks 
08-16 18:00:20.266  1028  1534 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 18:00:20.267  1028  1534 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 18:00:20.267  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 18:00:20.269  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1dec3de0 Bundle[{}]
08-16 18:00:20.270  7042  7121 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 18:00:20.270  7042  7121 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 18:00:20.271  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 18:00:20.271  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:20.271  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 18:00:20.272  1936  1936 D WfdService: Waiting for WifiP2p enabling
,08-16 18:00:20.272  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 18:00:20.273  7042  7121 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 18:00:20.273  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 18:00:20.273  1028  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 18:00:20.274  1028  1534 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:20.278  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:00:20.278  7042  7121 I System.out: Running OutgoingSocketThread
08-16 18:00:20.282  7042  8359 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 911)
08-16 18:00:20.282  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:20.285  1028  1534 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 18:00:20.286  1028  1534 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 18:00:20.288  8325  8346 W FormManager: Network not available. Please check & try again.
08-16 18:00:20.288  1028  1534 D WifiStateMachine: enableVerboseLogging : level 2
08-16 18:00:20.288  1028  1534 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 18:00:20.288  1028  1534 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 18:00:20.288  1028  1534 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 18:00:20.288  1028  1534 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 18:00:20.288  1028  1534 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 18:00:20.289  7042  8359 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45362
08-16 18:00:20.289  7042  8359 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 18:00:20.289  1028  1534 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 18:00:20.289  1028  1534 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 18:00:20.289  1028  1534 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 18:00:20.290  1028  1534 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 18:00:20.290  8325  8347 V FormManager: Network unavailable.
08-16 18:00:20.290  1028  1534 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 18:00:20.290  1028  1534 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 18:00:20.291  1028  1534 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 18:00:20.291  1028  1534 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 18:00:20.291  1028  1534 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 18:00:20.292  1028  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:00:20.292  1028  1534 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 18:00:20.292  1028  1534 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 18:00:20.292  1028  1534 D WifiNative-HAL: Setting external_sim to 1
08-16 18:00:20.292  1028  1534 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 18:00:20.293  1028  1534 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 18:00:20.293  1028  1534 I WifiNative-HAL: startHal
08-16 18:00:20.293  1028  1534 D wifi    : setting scan oui 0xaf5341a0
08-16 18:00:20.293  1028  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:00:20.293  1028  1534 I WifiNative-HAL: startHal
08-16 18:00:20.293  1028  1534 D wifi    : setting scan oui 0xaf5341a0
08-16 18:00:20.293  1936  1936 D WfdsService: Supplicant Connection state is changed : true
08-16 18:00:20.293  1936  2289 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 18:00:20.293  1936  2289 D WfdsService: Set the WFDS Monitor: true
08-16 18:00:20.293  1936  2289 D WfdsMonitor: WfdsMonitorThread create
08-16 18:00:20.293  1028  1534 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 18:00:20.293  1936  2289 D WfdsMonitor: WFDS Monitor is created and started
08-16 18:00:20.293  7996  7996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.293  1936  2289 D WfdsService: WiFi: Supplicant connection re-established
08-16 18:00:20.294  1028  1534 D WifiNative-wlan0: STA_AUTOCONNECT 1: re,turned true
08-16 18:00:20.294  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 18:00:20.294  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 18:00:20.294  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 18:00:20.295  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:00:20.295  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:00:20.295  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:00:20.295  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 18:00:20.295  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 18:00:20.295  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 18:00:20.295  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:00:20.296  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:00:20.296  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:00:20.296  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 18:00:20.296  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 18:00:20.296  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 18:00:20.296  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 18:00:20.296  8307  8307 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 18:00:20.296  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 18:00:20.296  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 18:00:20.297  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 18:00:20.297  1028  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 18:00:20.297  1028  1534 E WifiNative: : [237,405,272 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 18:00:20.297  1028  1534 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 18:00:20.298  1028  1534 D WifiNative-wlan0: RECONNECT: returned true
08-16 18:00:20.298  1028  1534 D WifiNative-wlan0: doString: [STATUS]
08-16 18:00:20.298  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:00:20.298  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 18:00:20.298  1028  1534 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:00:20.298  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 18:00:20.299  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
08-16 18:00:20.299  1028  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.300  1936  8366 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 18:00:20.300  1936  8366 E CtrlSupplicant: Succeed to open control connection
,08-16 18:00:20.300  1936  8366 E CtrlSupplicant: Succeed to open monitor connection
08-16 18:00:20.301  1936  8366 D WfdsMonitor: Supplicant connection established
08-16 18:00:20.301  1936  2289 D WfdsService: Connected to the supplicant for wfds
08-16 18:00:20.301   309   886 D CommandListener: Setting iface cfg
08-16 18:00:20.301   309   886 D CommandListener: Trying to bring up p2p0
08-16 18:00:20.302  1028  1532 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 18:00:20.302  1028  1532 D LGWifiP2pService: P2pEnablingState
08-16 18:00:20.302  1028  1532 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.302  1028  1532 D LGWifiP2pService: P2p socket connection successful
08-16 18:00:20.302  1028  1532 D LGWifiP2pService: P2pEnabledState
08-16 18:00:20.302  1028  1532 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 18:00:20.303  1028  1532 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 18:00:20.304  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 18:00:20.304  1936  1936 D WfdsService: WifiP2pState is changed : true
08-16 18:00:20.304  1936  2289 D WfdsService: Receive the WFDS_ENABLE Method
08-16 18:00:20.304  1936  2289 D WfdsService: Set the WFDS Monitor: true
08-16 18:00:20.304  1936  2289 D WfdsService: Connected to the supplicant for wfds
08-16 18:00:20.304  1936  2289 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 18:00:20.304  8307  8307 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 18:00:20.304  1936  2289 D WfdsService: selectPreferredScanChannel [36]
08-16 18:00:20.304  1936  2289 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 18:00:20.306  1936  1936 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 18:00:20.306  1028  1532 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 18:00:20.306  1936  1936 D WfdsService: isConnected: false
08-16 18:00:20.307  1028  1532 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 18:00:20.308  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 18:00:20.308  1028  1028 D RttService: SCAN_AVAILABLE : 3
08-16 18:00:20.308  1028  1532 D WifiNative-p2p0: SET device_name G3: returned true
08-16 18:00:20.308  1028  1532 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 18:00:20.308  1028  1532 D LGWifiP2pService: before postfix = G3
08-16 18:00:20.308  1028  1532 D WifiServerServiceExt: postfix byte check : 2
08-16 18:00:20.308  1028  1532 D LGWifiP2pService: after postfix = G3
08-16 18:00:20.308  1028  1532 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 18:00:20.308  1028  1552 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.308  1028  1552 I WifiNative-HAL: startHal
08-16 18:00:20.308  1028  1532 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 18:00:20.308  1028  1532 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 18:00:20.308  1028  1553 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.308  1028  1534 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 18:00:20.309  8325  8347 V FormManager: Network unavailable.
08-16 18:00:20.309  1028  1532 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 18:00:20.309  1028  1534 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 18:00:20.309  1028  1532 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 18:00:20.309  1028  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf5341a0
08-16 18:00:20.309  1028  1552 D wifi    : failed to get capabilities : -3
08-16 18:00:20.309  1028  1552 E WifiScanningService: could not get scan capabilities
08-16 18:00:20.309  1028  1534 E WifiStateMachine:  Co,nnectModeState CMD_START_DRIVER 0 0
08-16 18:00:20.309  1028  1532 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 18:00:20.309  1028  1532 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 18:00:20.310  1028  1534 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 18:00:20.310  1028  1532 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 18:00:20.310  1028  1532 D WifiNative-HAL: p2pGetDeviceAddress
08-16 18:00:20.310  1028  1532 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 18:00:20.310  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=237418  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:20.311  1028  1532 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 18:00:20.311  1028  1532 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 18:00:20.311  1028  1532 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 18:00:20.311  1028  1532 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 18:00:20.311  1028  1532 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 18:00:20.311  1028  1532 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 18:00:20.312  1028  1532 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 18:00:20.312  1028  1532 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-16 18:00:20.314  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:20.314  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:20.315  1936  1936 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 18:00:20.315  1936  1936 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 18:00:20.315  1936  1936 D WfdsService: Update P2p Interface State: 3
08-16 18:00:20.316  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.316  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.316  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:00:20.316  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:20.317  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=237425  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:20.317  1028  1534 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 18:00:20.317  1028  1534 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 18:00:20.318  1028  1534 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 18:00:20.318  1028  1534 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 18:00:20.324  8307  8307 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 18:00:20.324  1028  1534 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 18:00:20.324  1028  1534 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 18:00:20.325  1028  1534 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 18:00:20.325  1028  1534 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 18:00:20.325  8307  8307 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 18:00:20.325  1028  1532 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 18:00:20.325  1028  1532 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 18:00:20.325  1028  1532 D LGWifiP2pService: InactiveState
08-16 18:00:20.325  1028  1532 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.325  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.325  1028  1532 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 18:00:20.326  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:00:20.326  1028  1532 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 18:00:20.326  1028  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.326  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.326  8307  8307 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:00:20.326  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.327  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.328  1936  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:00:20.328  1936  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.328  1936  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.328  1028  8343 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:00:20.328  1028  8343 E Wif,iMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.328  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.328  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.328  1028  8343 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.328  1028  8343 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.328  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.328  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.328  1028  8343 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.328  1028  8343 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.328  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.328  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.329  1028  1532 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.330  1028  2026 I ActivityManager: Killing 7472:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-16 18:00:20.331  1936  2289 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 18:00:20.331  1028  1028 E WifiServerServiceExt: No p2p device connected
08-16 18:00:20.332  1028  1534 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 18:00:20.332  1028  1534 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 18:00:20.333  1028  1534 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 18:00:20.333  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 18:00:20.333  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 18:00:20.334  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.334  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 18:00:20.334  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.334  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.334  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 18:00:20.334  8307  8307 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 18:00:20.334  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.334  1936  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.335  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.335  1936  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.335  1028  8343 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.335  1028  8343 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.336  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.336  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.336  1028  8343 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 18:00:20.336  1028  8343 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.336  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.336  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 18:00:20.336  1028  1534 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 18:00:20.336  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.336  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:20.337  1028  1534 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:00:20.337  1028  1534 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:00:20.337  1028  1534 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 18:00:20.337  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 18:00:20.337  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 18:00:20.337  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:20.338  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 18:00:20.338  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:20.338  1028  8343 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18,:00:20.338  1028  8343 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 18:00:20.338  1028  1534 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 18:00:20.338  1028  1534 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 18:00:20.338  1028  1534 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 18:00:20.338  1028  1534 D WifiNative-wlan0: doBoolean: SCAN
08-16 18:00:20.339  1028  1534 D WifiNative-wlan0: SCAN: returned false
08-16 18:00:20.339  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=237447  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-16 18:00:20.383  1028  1898 W libprocessgroup: failed to open /acct/uid_10062/pid_7472/cgroup.procs: No such file or directory
08-16 18:00:20.384  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=237492  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 18:00:20.386  1028  1534 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:20.388  1028  1534 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:20.389  1028  1534 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:20.391  1028  1534 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:20.391  1028  1534 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 18:00:20.394  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:20.394  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:00:20.397  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:20.400  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.400  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:20.400  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 18:00:20.402  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:20.402  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:00:20.404  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:20.404  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 18:00:20.441  8348  8348 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:20.444  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:00:20.450  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:20.452  1028  1899 I ActivityManager: Killing 7489:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 18:00:20.494  1028  1934 W libprocessgroup: failed to open /acct/uid_10085/pid_7489/cgroup.procs: No such file or directory
,08-16 18:00:20.525  8348  8348 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 18:00:20.532  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:00:20.542  8325  8372 W FormManager: Network not available. Please check & try again.
08-16 18:00:20.551  8325  8373 V FormManager: Network unavailable.
,08-16 18:00:20.555  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:00:20.557  8325  8373 V FormManager: Network unavailable.
,08-16 18:00:20.590  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:20.590  4372  4372 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 18:00:20.592  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:20.595  4372  4372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 18:00:20.601  4372  8374 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 18:00:20.606  4372  8375 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 18:00:20.606  4372  8375 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 18:00:20.666  1028  2007 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8376 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 18:00:20.699   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 35.355ms
,08-16 18:00:20.722   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.640ms
08-16 18:00:20.743   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 20.236ms
,08-16 18:00:20.773  8376  8376 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 18:00:20.773  8376  8376 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 18:00:20.779  8376  8376 V [BNRBootReceiver]: Boot Receiver Return
08-16 18:00:20.783  8376  8376 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 18:00:20.815  8307  8307 E wpa_supplicant: USIM:  scard_init function
08-16 18:00:20.815  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 18:00:20.816  8307  8307 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 18:00:20.816  1028  8343 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-16 18:00:20.816  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-16 18:00:20.816  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-16 18:00:20.816  1028  8343 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 18:00:20.816  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 18:00:20.816  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 18:00:20.822  1028  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:00:20.823  1028  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:00:20.824  1028  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:00:20.825  1028  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 18:00:20.825  1028  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 18:00:20.841  1028  2026 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8397 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 18:00:20.842  1028  2026 I ActivityManager: Killing 7530:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 18:00:20.934  8307  8307 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 18:00:20.934  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 18:00:20.935  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 18:00:20.936  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 18:00:20.936  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 18:00:20.936  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:20.937  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:20.961  8307  8307 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:00:20.962  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:00:20.962  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:20.963  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:20.963  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 18:00:20.963  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:00:20.964  1028  8343 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:00:20.964  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 18:00:20.964  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-16 18:00:20.971  1028  8343 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 18:00:20.972  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:20.972  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:21.059  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=238166  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 18:00:21.074  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:00:21.075  1028  1934 W libprocessgroup: failed to open /acct/uid_10093/pid_7530/cgroup.procs: No such file or directory
,08-16 18:00:21.087  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=238194  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 18:00:21.089  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.089  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.089  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=238197  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:00:21.089  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:00:21.094  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=238202  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 18:00:21.094  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.094  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:21.095  1028  1534 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=238203
,08-16 18:00:21.095  1028  1534 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=238203
08-16 18:00:21.096  1028  1534 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=238204
08-16 18:00:21.096  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=238204
08-16 18:00:21.096  1028  1534 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=238204
08-16 18:00:21.097  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=238205  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:00:21.097  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:21.102  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.102  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.103  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 18:00:21.103  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=238211  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 18:00:21.105  1028  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=238213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-16 18:00:21.108  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=238215  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 18:00:21.109  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.109  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.109  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 18:00:21.110  1028  1534 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=238218
08-16 18:00:21.112  1028  1534 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=238220
08-16 18:00:21.113  1028  1534 D WifiNative-wlan0: doString: [STATUS]
08-16 18:00:21.114  1028  8343 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 18:00:21.114  1028  8343 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 18:00:21.114  1028  1534 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 18:00:21.116  1028  1534 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 18:00:21.118  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.118  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:21.119  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.122  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.122  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:00:21.123  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.129  1028  1534 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 18:00:21.129  1028  1534 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 18:00:21.135  8397  8397 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:00:21.136  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.136  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.136  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 18:00:21.140  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.140  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:21.142  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.147  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.148  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.148  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 18:00:21.150  1028  1534 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 18:00:21.150  1028  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:00:21.150  1028  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:00:21.151  1028  1540 D ConnectivityService: Got NetworkAgent Messenger
,08-16 18:00:21.151  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 18:00:21.151  1028  1540 D ConnectivityService: NetworkAgent connected
08-16 18:00:21.151  1028  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:00:21.151  1028  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:00:21.162  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.163  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:21.164  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.170  8397  8397 D PluginManager: init()
,08-16 18:00:21.176  1028  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 18:00:21.176  1028  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:00:21.176  1028  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 18:00:21.176  1028  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 18:00:21.176  1028  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 18:00:21.188  1028  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 18:00:21.190   309   886 D CommandListener: Setting iface cfg
08-16 18:00:21.195  1028  1534 E WifiStateMachine: Start Dhcp Watchdog 3
,08-16 18:00:21.195  1028  8420 D DhcpStateMachine: StoppedState
,08-16 18:00:21.195  1028  8420 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.195  1028  8420 D DhcpStateMachine: WaitBeforeStartState
08-16 18:00:21.195  1028  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=238303  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:21.196  1028  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=238304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:21.196  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=238304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:21.198  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:21.198  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 18:00:21.198  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:21.198  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:21.199  1028  1534 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:21.199  1028  1534 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:21.200  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:21.200  1028  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 18:00:21.201  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:21.202  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-16 18:00:21.204  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:21.204  1028  1028 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 18:00:21.207  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:21.207  1028  1028 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 18:00:21.208  1028  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=238316  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:21.209  1028  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=238316  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:21.209  1028  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=238317  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 18:00:21.211  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14497] from screen [on:0 period:-1810561318] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 18:00:21.212  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1810561317] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 18:00:21.212  1028  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 18:00:21.215  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 18:00:21.217  1028  1540 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 18:00:21.219  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.219  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.220  1028  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.220  1028  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.221  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.221  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.222  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 18:00:21.222  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=148,0,0
08-16 18:00:21.222  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=148,0,0
08-16 18:00:21.222  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 18:00:21.223  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 18:00:21.223  1028  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 18:00:21.223  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 18:00:21.224  1028  1534 D WifiNative-wlan0: SET ps 0: returned true
08-16 18:00:21.224  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 18:00:21.224  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 18:00:21.224  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 18:00:21.224  1028  1534 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 18:00:21.224  1028  1534 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-16 18:00:21.225  1028  1534 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-16 18:00:21.225  1028  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d377359 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.225  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d377359 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.225  1028  8420 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:00:21.225  1028  8420 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 18:00:21.225   309   886 D CommandListener: Setting iface cfg
08-16 18:00:21.226   309   886 D CommandListener: Trying to bring up wlan0
08-16 18:00:21.227  1028  1534 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-16 18:00:21.228  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.228  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.229  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 18:00:21.229  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-16 18:00:21.229  1028  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.230  1028  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.230  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.231  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 18:00:21.231  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-16 18:00:21.232  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 18:00:21.232  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 18:00:21.233  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-16 18:00:21.233  1028  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.233  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 18:00:21.233  1028  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.234  1028  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-16 18:00:21.234  1028  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 18:00:21.234  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 18:00:21.234  1028  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 18:00:21.234  1028  1534 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 18:00:21.252  1028  1534 D WifiNative-wlan0: SET ps 1: returned true
,08-16 18:00:21.253  1028  1534 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 18:00:21.254  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-16 18:00:21.254  1028  1534 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 18:00:21.255  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 18:00:21.255  1028  1540 D ConnectivityService: ignoring duplicate network state non-change
08-16 18:00:21.257  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.257  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 18:00:21.259  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.261  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.261  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.261  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:00:21.265  1028  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 18:00:21.266  1028  1540 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 18:00:21.272  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.272  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.272  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 18:00:21.279  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 18:00:21.281  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.281  1598  1598 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 18:00:21.282  7042  7121 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 912)
08-16 18:00:21.282  7042  7121 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 912)
,08-16 18:00:21.285  7042  7121 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 917)
08-16 18:00:21.286  7042  7121 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 18:00:21.286  7042  7121 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 918)
08-16 18:00:21.287  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 18:00:21.288  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.290  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.290  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:00:21.291  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.291  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@290a090d added. We now have 2 listener(s)
08-16 18:00:21.291  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.291  1028  1534 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 18:00:21.292  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.292  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.292  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 18:00:21.292  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 18:00:21.294  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.295  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:00:21.295  1028  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.295  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 18:00:21.298  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.298  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.298  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.298  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.298  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151600c2 added. We now have 9 listener(s)
08-16 18:00:21.298  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.298  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:00:21.299  1028  1540 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 18:00:21.299  1028  1540 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 18:00:21.300  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.300  1028  1540 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 18:00:21.301   309   886 E Netd    : netlink response contains error (File exists)
08-16 18:00:21.301  1028  1540 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 18:00:21.302  1028  1540 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 18:00:21.302  1028  1540 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:00:21.302  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:00:21.302  1028  1540 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 18:00:21.303  1028  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 18:00:21.303  1028  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.303  1028  1540 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.303  1028  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.303  1028  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:21.303  1028  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:21.303  1028  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:00:21.303  1028  8414 D NetworkMonit,or NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.303  1028  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.303  1028  8414 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 18:00:21.303  1028  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 18:00:21.304  1028  1540 D ConnectivityService: currentScore = 0, newScore = 20
08-16 18:00:21.304  1028  8414 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:00:21.304  1028  1540 D ConnectivityService:    accepting network in place of null
08-16 18:00:21.304  1028  1540 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.304  1028  8414 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 18:00:21.304  1028  1534 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.304  1028  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:21.307  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 18:00:21.307  1028  1540 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 18:00:21.307  1028  1540 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 18:00:21.309  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:00:21.310  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:00:21.310   309  8424 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 18:00:21.310  1028  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 18:00:21.310  1028  1540 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 18:00:21.311  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 18:00:21.311  1028  1540 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 18:00:21.311  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 18:00:21.312  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 18:00:21.312  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 18:00:21.312  1028  1540 D ConnectivityService: validation of new default Network = false
08-16 18:00:21.312  1028  1540 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 18:00:21.312  1028  1540 D DSQN    : enableDataServiceNotify 
08-16 18:00:21.312  1028  1540 D DSQN    : start dsqn bin
08-16 18:00:21.312  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:00:21.312  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:00:21.312  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.312  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351b1a10 added. We now have 3 listener(s)
08-16 18:00:21.313  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:, updateConnectivityInfo: State changed:
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:00:21.316  7042  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:00:21.318  7042  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.320  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:00:21.320  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.321  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.321  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.321  1028  1531 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 18:00:21.321  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.321  1598  1598 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:00:21.321  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16db2909 added. We now have 10 listener(s)
08-16 18:00:21.321  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.321  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:00:21.321  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.321  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:00:21.321  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.321  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.321  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.321  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.321  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@290a090d removed from the list
08-16 18:00:21.321  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.321  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151600c2 removed from the list
08-16 18:00:21.321  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:00:21.321  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.323  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.323  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.323  1028  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.323  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.323  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:21.324  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:,21.324  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.324  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.324  1028  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:21.324  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151600c2 not in the list
08-16 18:00:21.324  1598  1598 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 18:00:21.324  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:00:21.324  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.324  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.325  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.318  8425  8425 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:21.318  8425  8425 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:21.327  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.327  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.327  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.327  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16db2909 removed from the list
08-16 18:00:21.327  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.327  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.327  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.327  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.327  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351b1a10 removed from the list
08-16 18:00:21.328  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.328  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c7670e added. We now have 2 listener(s)
08-16 18:00:21.328  1028  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.330  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.330  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.330  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.330  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18,:00:21.331  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1421552f added. We now have 9 listener(s)
08-16 18:00:21.331  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.331  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:00:21.333  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.337  8425  8425 E DSQN    : DSQN ssw
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:00:21.340  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:00:21.342  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.342  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:00:21.342  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.342  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28844cc5 added. We now have 3 listener(s)
08-16 18:00:21.342  1028  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.344  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.346  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.348  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.349  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.349  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.349  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.349  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3516e61a added. We now have 10 listener(s)
08-16 18:00:21.349  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.349  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:00:21.349  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:00:21.349  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:00:21.349  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.349  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:00:21.351  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:00:21.351  1028  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.352  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:00:21.353  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.353  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.355  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:00:21.355  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:00:21.356  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:00:21.356  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.358  7042  7121 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:00:21.358  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.358  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:00:21.359   309  8424 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 18:00:21.360  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:00:21.360  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.360  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:00:21.361  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.361  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.361  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.361  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.361  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c7670e removed from the list
08-16 18:00:21.361  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.361  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1421552f removed from the list
08-16 18:00:21.361  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:00:21.361  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.361  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.361  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.362  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.362  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.362  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.362  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1421552f not in the list
08-16 18:00:21.362  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.362  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.363  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.363  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 18:00:21.363  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:00:21.363  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.363  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.363  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3516e61a removed from the list
08-16 18:00:21.363  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.363  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.363  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.363  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.363  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28844cc5 removed from the list
08-16 18:00:21.364  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.364  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1be1f041 added. We now have 2 listener(s)
08-16 18:00:21.364  1028  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.366  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.366  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.366  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.366  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.366  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad49e6 added. We now have 9 listener(s)
08-16 18:00:21.366  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.367  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:00:21.368  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:00:21.371  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:00:21.372  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:00:21.374  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:00:21.374  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.374  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19efc1d4 added. We now have 3 listener(s)
08-16 18:00:21.374  1028  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.375  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.376  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.376  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.376  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.376  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.376  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161c4f7d added. We now have 10 listener(s)
08-16 18:00:21.376  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.376  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:00:21.376  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:00:21.376  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:00:21.376  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:00:21.377  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.377  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:00:21.377  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.379  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:00:21.379  1028  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.383  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:00:21.384  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:00:21.385  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:00:21.386  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.387  7042  7121 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:00:21.387  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:00:21.387  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.387  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:00:21.387  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.387  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.387  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.388  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.388  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1be1f041 removed from the list
08-16 18:00:21.388  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.388  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad49e6 removed from the list
08-16 18:00:21.388  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:00:21.388  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.388  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.388  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.389  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.389  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.389  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.389  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad49e6 not in the list
08-16 18:00:21.389  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.389  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.389  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.390  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 18:00:21.390  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:00:21.390  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.390  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.390  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161c4f7d removed from the list
08-16 18:00:21.390  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.390  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.390  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.390  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.390  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19efc1d4 removed from the list
08-16 18:00:21.391  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.391  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23712740 added. We now have 2 listener(s)
08-16 18:00:21.391  1028  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.393   309  8424 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 18:00:21.393  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.394  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.394  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.394  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.394  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca36679 added. We now have 9 listener(s)
08-16 18:00:21.394  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.395  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:00:21.398  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:00:21.400  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:00:21.401  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.401  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:00:21.401  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.401  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3917e81f added. We now have 3 listener(s)
08-16 18:00:21.401  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.403  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.404  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.404  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.404  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.404  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.404  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.404  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee1776c added. We now have 10 listener(s)
08-16 18:00:21.404  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.405  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:00:21.405  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:00:21.405  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:00:21.405  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.405  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:00:21.406  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:00:21.407  1028  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 18:00:21.410  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:00:21.411  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:00:21.412  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:00:21.413  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.414  7042  7121 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 18:00:21.416  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:00:21.416  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.416  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:00:21.416  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.416  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.416  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.416  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.416  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23712740 removed from the list
08-16 18:00:21.416  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.416  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca36679 removed from the list
08-16 18:00:21.416  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:00:21.416  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.416  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.416  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.417  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.417  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.417  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.417  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca36679 not in the list
08-16 18:00:21.417  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.417  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.418  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.418  7042  7121 D BluetoothLeScanner: could not find callback wrapper
08-16 18:00:21.418  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:00:21.418  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.418  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.418  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee1776c removed from the list
08-16 18:00:21.418  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.418  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.418  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.418  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.418  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3917e81f removed from the list
08-16 18:00:21.419  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.419  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fdce73b added. We now have 2 listener(s)
08-16 18:00:21.419  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.420  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.421  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.421  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.421  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.421  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12249e58 added. We now have 9 listener(s)
08-16 18:00:21.421  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.421  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:00:21.423  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:00:21.426   309   885 D LGDataListener: argv[0]=dsqncommand
08-16 18:00:21.426   309   885 D LGDataListener: argv[1]=wlan0
08-16 18:00:21.426   309   885 D LGDataListener: argv[2]=1
08-16 18:00:21.427   309   885 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 18:00:21.427  1028  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 18:00:21.427  1028  1108 D DSQN    : start to monitor internet connection
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:00:21.427  7042  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:00:21.427  1028  8420 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 18:00:21.428  1028  8420 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 18:00:21.428  1028  8420 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 18:00:21.430  7042  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:00:21.430  7042  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:00:21.430  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:00:21.430  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fd1f896 added. We now have 3 listener(s)
08-16 18:00:21.431  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 18:00:21.428  8432  8432 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:21.432  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 18:00:21.432  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:00:21.432  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:00:21.432  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:00:21.432  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028bc17 added. We now have 10 listener(s)
08-16 18:00:21.432  7042  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:00:21.432  7042  7121 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:00:21.432  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.432  7042  7121 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:00:21.432  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.432  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.432  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:00:21.432  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.433  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fdce73b removed from the list
08-16 18:00:21.433  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.433  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12249e58 removed from the list
08-16 18:00:21.433  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.435  7042  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:00:21.435  7042  7121 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:00:21.435  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.435  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.435  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.436  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.436  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.436  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.436  7042  7121 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12249e58 not in the list
08-16 18:00:21.436  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.436  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.428  8432  8432 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 18:00:21.437  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:00:21.437  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:00:21.437  7042  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:00:21.437  7042  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028bc17 removed from the list
08-16 18:00:21.437  7042  7121 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:00:21.437  7042  7121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:00:21.437  7042  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:00:21.437  7042  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:00:21.437  7042  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fd1f896 removed from the list
08-16 18:00:21.438  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 18:00:21.438  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 18:00:21.438  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 18:00:21.438  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:00:21.438  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 18:00:21.438  7042  7121 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:00:21.443  8432  8432 I dhcpcd  : version 5.5.6 starting
08-16 18:00:21.445  8432  8432 E dhcpcd  : get_duid: m
08-16 18:00:21.445  8432  8432 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 18:00:21.445  8432  8432 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 18:00:21.445  7042  8433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 925, name: My test thread name)
08-16 18:00:21.445  7042  8433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 925, thread name: My test thread name)
08-16 18:00:21.446  7042  8433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 925, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 18:00:21.450  7042  8435 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 927, name: My test thread name)
08-16 18:00:21.450  7042  8435 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 927, thread name: My test thread name)
08-16 18:00:21.450  7042  8435 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 927, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:00:21.453  7042  7121 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 18:00:21.453  7042  7121 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 18:00:21.453  7042  7121 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 18:00:21.453  7042  7121 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 18:00:21.453  7042  7121 D com.test.thalitest.ThaliTestRunner: Total duration: 22830 ms
08-16 18:00:21.455  7042  7121 I jxcore-log: Total number of executed tests:  80
08-16 18:00:21.455  7042  7121 I jxcore-log: 
08-16 18:00:21.455  7042  7121 I jxcore-log: Number of passed tests:  80
08-16 18:00:21.455  7042  7121 I jxcore-log: 
08-16 18:00:21.455  7042  7121 I jxcore-log: Number of failed tests:  0
08-16 18:00:21.455  7042  7121 I jxcore-log: 
08-16 18:00:21.456  7042  7121 I jxcore-log: Number of ignored tests:  0
08-16 18:00:21.456  7042  7121 I jxcore-log: 
08-16 18:00:21.456  7042  7121 I jxcore-log: Total duration:  22830
08-16 18:00:21.456  7042  7121 I jxcore-log: 
08-16 18:00:21.457  7042  7121 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 18:00:21.457  7042  7121 I jxcore-log: 
08-16 18:00:21.461  1028  8414 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:00:21 GMT], X-Android-Received-Millis=[1471363221460], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471363221426]}
08-16 18:00:21.461  1028  8414 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 18:00:21.461  1028  8414 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 18:00:21.461  1028  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.461  1028  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.462  1028  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:21.462  1028  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:21.462  1028  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 18:00:21.462  1028  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 18:00:21.462  1028  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 18:00:21.462  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.462  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:21.462  1028  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:21.462  1028  1540 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.462  1028  1534 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.462  1028  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:00:21.462  1028  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 18:00:21.463  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:00:21.464  1846  1846 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:21.464  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 18:00:21.473  7042  7042 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 18:00:21.475  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.475  7042  7121 I jxcore-log: 
08-16 18:00:21.482  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.482  7042  7121 I jxcore-log: 
08-16 18:00:21.482  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.482  7042  7121 I jxcore-log: 
08-16 18:00:21.483  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.483  7042  7121 I jxcore-log: 
08-16 18:00:21.484  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.484  7042  7121 I jxcore-log: 
08-16 18:00:21.485  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.485  7042  7121 I jxcore-log: 
08-16 18:00:21.485  1598  1598 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 18:00:21.486  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.486  7042  7121 I jxcore-log: 
08-16 18:00:21.486  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.487  1598  1598 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 18:00:21.487  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.487  7042  7121 I jxcore-log: 
08-16 18:00:21.488  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.488  7042  7121 I jxcore-log: 
08-16 18:00:21.488  8432  8432 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 18:00:21.488  8432  8432 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:00:21.488  8432  8432 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:00:21.488  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.488  7042  7121 I jxcore-log: 
08-16 18:00:21.488  8432  8432 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 18:00:21.488  8432  8432 D dhcpcd  : wlan0: sending REQUEST (xid 0x91b14c8c), next in 3.65 seconds
08-16 18:00:21.489  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:00:21.489  7042  7121 I jxcore-log: 
,08-16 18:00:21.490  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.490  7042  7121 I jxcore-log: 
,08-16 18:00:21.491  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.491  7042  7121 I jxcore-log: 
08-16 18:00:21.491  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.491  7042  7121 I jxcore-log: 
08-16 18:00:21.491  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.491  7042  7121 I jxcore-log: 
08-16 18:00:21.492  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.492  7042  7121 I jxcore-log: 
08-16 18:00:21.492  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.492  7042  7121 I jxcore-log: 
08-16 18:00:21.493  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.493  7042  7121 I jxcore-log: 
08-16 18:00:21.494  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.494  7042  7121 I jxcore-log: 
08-16 18:00:21.494  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.494  7042  7121 I jxcore-log: 
08-16 18:00:21.494  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:00:21.494  7042  7121 I jxcore-log: 
08-16 18:00:21.495  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.495  7042  7121 I jxcore-log: 
08-16 18:00:21.495  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.495  7042  7121 I jxcore-log: 
08-16 18:00:21.496  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.496  7042  7121 I jxcore-log: 
08-16 18:00:21.496  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:00:21.496  7042  7121 I jxcore-log: 
08-16 18:00:21.497  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.497  7042  7121 I jxcore-log: 
08-16 18:00:21.497  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.497  7042  7121 I jxcore-log: 
08-16 18:00:21.498  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.498  7042  7121 I jxcore-log: 
08-16 18:00:21.498  7042  7121 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:00:21.498  7042  7121 I jxcore-log: 
08-16 18:00:21.519  8432  8432 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from, 192.168.1.1
,08-16 18:00:21.560  8432  8432 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-16 18:00:21.560  8432  8432 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 18:00:21.561  8432  8432 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 18:00:21.561  8432  8432 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 18:00:21.562  8432  8432 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 18:00:21.562  8432  8432 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 18:00:21.563  8432  8432 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 18:00:21.563  8432  8432 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 18:00:21.640  8397  8397 W ExternalStrings: load override strings
08-16 18:00:21.640  8397  8397 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:00:21.640  8397  8397 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 18:00:21.642  8397  8397 D StatusProvider: onCreate
,08-16 18:00:21.711  8397  8397 V Signer  : override build config not found
08-16 18:00:21.711  8397  8397 D Signer  : value of property debug is false
,08-16 18:00:21.753  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 18:00:21.753  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 18:00:21.753  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 18:00:21.754  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 18:00:21.754  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 18:00:21.754  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 18:00:21.754  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 18:00:21.755  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 18:00:21.755  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,08-16 18:00:21.755  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 18:00:21.755  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 18:00:21.755  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 18:00:21.756  8397  8397 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 18:00:21.768  8442  8442 D AndroidRuntime: 
08-16 18:00:21.768  8442  8442 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 18:00:21.771  8397  8397 V LGMDMManager: Create singleton instance
08-16 18:00:21.771  8442  8442 D AndroidRuntime: CheckJNI is OFF
08-16 18:00:21.831  1028  8420 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 18:00:21.834  1028  8420 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 18:00:21.834  1028  8420 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 18:00:21.835  1028  8420 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 18:00:21.835  1028  8420 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 18:00:21.835  1028  8420 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 18:00:21.835  1028  8420 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 18:00:21.835  1028  8420 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 18:00:21.836  1028  8420 D DhcpStateMachine: RunningState
08-16 18:00:21.846  8397  8397 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 18:00:21.933  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:21.934  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:00:21.935  8442  8442 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 18:00:21.947  1028  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 18:00:21.948  1028  1103 I ActivityManager: Killing 7042:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 18:00:21.950  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:00:21.955  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:21.992  1028  1571 I WindowState: WIN DEATH: Window{34a170e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 18:00:21.993  1028  1539 D WifiService: Client connection lost with reason: 4
08-16 18:00:22.000  1028  1571 D InputDispatcher: Window went away: Window{34a170e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 18:00:22.075  8397  8474 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 18:00:22.182  1028  1103 I ActivityManager:   Force finishing activity ActivityRecord{134f756b u0 com.test.thalitest/.MainActivity t6}
,08-16 18:00:22.213  1028  1534 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:00:22.214  1028  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:00:22.215  1028  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:00:22.216  1028  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 18:00:22.218  1028  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:00:22.219  1028  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 18:00:22.221   342   352 E GBMv2   : DFP En is all cleared set to be enabled
08-16 18:00:22.222  1028  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 18:00:22.222  1028  1540 D ConnectivityService: identical MTU - not setting
08-16 18:00:22.223  1028  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 18:00:22.223  1028  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 18:00:22.223  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:00:22.223  1028  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:22.225  1028  1540 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 18:00:22.227  1598  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 18:00:22.247  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.247  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.248  1028  1934 W ActivityManager: Spurious death for ProcessRecord{3938b332 7042:com.test.thalitest/u0a118}, curProc for 7042: null
08-16 18:00:22.249  2027  2027 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 18:00:22.251  2027  2027 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 18:00:22.254  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 18:00:22.258  2027  2095 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-16 18:00:22.260  1900  1900 D ActionManagerService: notifyUserLog: 1000003
08-16 18:00:22.261  3806  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 18:00:22.262  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 18:00:22.263  2027  2027 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 18:00:22.263  1936  3965 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 18:00:22.264  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 18:00:22.264  1028  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 18:00:22.264  1936  3965 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3910dffb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 18:00:22.265  1936  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 18:00:22.266  1936  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{27900818 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 18:00:22.266  1028  1116 I ActivityManager:   Force finishing activity ActivityRecord{134f756b u0 com.test.thalitest/.MainActivity t6 f}
08-16 18:00:22.266  1028  1116 W ActivityManager: Duplicate finish request for ActivityRecord{134f756b u0 com.test.thalitest/.MainActivity t6 f}
,08-16 18:00:22.282  1598  1598 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 18:00:22.286  1990  1990 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 18:00:22.286  2027  2027 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-16 18:00:22.289  3806  3806 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 18:00:22.290  7948  7948 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 18:00:22.291  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 18:00:22.300  2466  2604 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 18:00:22.308  1028  1468 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 18:00:22.339  4651  4651 I art     : Explicit concurrent mark sweep GC freed 15403(882KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 747us total 65.689ms
,08-16 18:00:22.372  4541  4541 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 18:00:22.372  4541  4541 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 18:00:22.372  4541  4541 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 18:00:22.372  4541  4541 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 18:00:22.372  4541  4541 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:00:22.372  4541  4541 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:00:22.372  4541  4541 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:22.372  4541  4541 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:00:22.372  4541  4541 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:00:22.373  4541  4541 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:00:22.373  4541  4541 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:00:22.373  4541  4541 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 18:00:22.381  1028  1028 D administrator: Handling package changes for user 0
08-16 18:00:22.389  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.389  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.413  1598  1598 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-16 18:00:22.419  2027  2027 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 18:00:22.425  1598  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 18:00:22.425  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.425  1900  1900 D ActionManagerService: notifyUserLog: 1000004
08-16 18:00:22.426  3806  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-16 18:00:22.430  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 18:00:22.432  3806  4533 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:00:22.437  1598  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-16 18:00:22.437  1598  1655 D KeyguardModel: createShortcutInfo...
,08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , expire_time: 0
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , display: false
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , animation: false }
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , expire_time: 0
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , display: false
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , animation: false }
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , expire_time: 0
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , display: false
08-16 18:00:22.451  2027  2027 I GBoardWebViewUtils: , animation: false }
08-16 18:00:22.452  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:22.464  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 18:00:22.464  1598  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:22.464  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 18:00:22.466  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 18:00:22.467  1598  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:00:22.467  1598  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 18:00:22.468  1598  1598 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,08-16 18:00:22.472  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.478  1028  1641 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:22.478  1028  1641 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:22.482  1598  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 18:00:22.482  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.484  1598  1598 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 18:00:22.487  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 18:00:22.487  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 18:00:22.488  1598  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:00:22.488  1598  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-16 18:00:22.497  1598  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 18:00:22.497  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.498  1028  1641 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:22.505  2027  8495 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-16 18:00:22.507  1598  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:22.507  1598  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 18:00:22.507  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 18:00:22.507  1598  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 18:00:22.508  1598  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:00:22.508  1598  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 18:00:22.509  1598  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 18:00:22.509  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.513  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.513  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.523  1028  1101 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 18:00:22.524  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 18:00:22.544  7220  7220 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 18:00:22.546  1598  1598 D KeyguardModel: handleShortcutListChanged...
08-16 18:00:22.546  1598  1598 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 18:00:22.547  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 18:00:22.553  1028  1880 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 18:00:22.553  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 18:00:22.553  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 18:00:22.553  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 18:00:22.553  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 18:00:22.554  7948  7948 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 18:00:22.555  1598  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 18:00:22.555  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.555  1863  1863 D SplitUIManager: split_name #11 / not available #0
08-16 18:00:22.556  1863  1863 D SplitUIService: removed split : 
08-16 18:00:22.559  1598  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 18:00:22.559  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.560  1598  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:00:22.560  1598  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 18:00:22.562  1598  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 18:00:22.562  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.563  1598  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:00:22.563  1598  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 18:00:22.563  1598  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 18:00:22.563  1598  1655 D KeyguardModel: createShortcutInfo...
08-16 18:00:22.564  1598  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 18:00:22.564  1598  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 18:00:22.566  1598  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 18:00:22.566  1598  1655 D KeyguardModel: createShortcutInfo...
,08-16 18:00:22.586  1863  1863 D SplitUIManager: split_name #11 / not available #0
08-16 18:00:22.586  1863  1863 I SplitUIService: split app #11
08-16 18:00:22.591  1028  1989 V SIM_STK : Menu title from STK is T-Mobile
08-16 18:00:22.599  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 18:00:22.603  7165  7165 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 18:00:22.603  2027  2027 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 18:00:22.605  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 18:00:22.605  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 18:00:22.605  7165  7165 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 18:00:22.605  7165  7165 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 18:00:22.605  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 18:00:22.606  7165  7165 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 18:00:22.606  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 18:00:22.606  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 18:00:22.606  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 18:00:22.606  7165  7165 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 18:00:22.606  7165  7165 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 18:00:22.606  7165  7165 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 18:00:22.611  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 18:00:22.611  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.620  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:00:22.620  1598  1598 D KeyguardModel: handleShortcutListChanged...
08-16 18:00:22.621  1598  1598 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 18:00:22.624  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.632  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.632  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.632  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.635  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.635  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.646  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:22.649  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.653  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 18:00:22.653  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 18:00:22.654  1028  1028 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 18:00:22.655  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.655  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.655  1028  1573 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 18:00:22.655  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.657  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.659  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 18:00:22.662  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:00:22.667  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.668  8397  8474 D LgDataFeature: LgDataFeature() Constructor: none
08-16 18:00:22.668  8397  8474 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 18:00:22.673  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.673  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.673  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.678  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.678  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.681  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:00:22.689  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 18:00:22.699  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.699  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.700  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.704  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 18:00:22.706  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.706  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 18:00:22.706  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:00:22.708  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 18:00:22.709  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 18:00:22.711   329   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 18:00:22.711  3245  8501 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 18:00:22.711  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 18:00:22.712  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 18:00:22.718  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:22.730  1028  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{71a3c30 u0 com.lge.launcher2/.Launcher t5} time:239850
08-16 18:00:22.730  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.740  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 18:00:22.740  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:00:22.745  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.745  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.745  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.747  1028  1116 I art     : Explicit concurrent mark sweep GC freed 84960(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.645ms total 239.226ms
,08-16 18:00:22.752  2027  2150 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 18:00:22.753  2027  2150 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 18:00:22.754  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.754  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.757  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 18:00:22.758  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 18:00:22.758  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:00:22.767  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:22.768  2027  2027 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 18:00:22.770  2595  2595 D [Concierge]Service: onStartCommand(). Type : 8
08-16 18:00:22.770  2595  2595 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 18:00:22.771  2595  2595 D [Concierge]Service: Update widget ID : 11
08-16 18:00:22.772  2027  2027 D [Concierge]WidgetView: change position of spinner
08-16 18:00:22.772  8397  8474 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 18:00:22.773  2027  2027 I [Concierge]WidgetView: initWebView(). Time : 1471363222773
08-16 18:00:22.773  2595  2595 D [Concierge]Service: onStartCommand(). Type : 0
08-16 18:00:22.775  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.802  8442  8442 D AndroidRuntime: Shutting down VM
,08-16 18:00:22.807  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.807  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.807  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.808  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 18:00:22.818  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-16 18:00:22.818  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 18:00:22.819  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 18:00:22.819  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 18:00:22.819  8397  8474 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 18:00:22.821  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 18:00:22.823  8397  8474 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 18:00:22.829  1028  1116 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8506 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 18:00:22.834  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.834  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.838  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 18:00:22.841  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.846  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.846  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 18:00:22.847  7220  7220 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 18:00:22.849  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.850  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.852  2027  2027 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 192170029
08-16 18:00:22.852  8348  8348 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 18:00:22.853  2027  2027 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 18:00:22.853  2027  2027 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 18:00:22.857  2027  2027 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3aec4bad
08-16 18:00:22.857  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 18:00:22.858  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 18:00:22.858  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:00:22.860  8348  8348 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:22.862  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:00:22.865  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 18:00:22.866  2027  2027 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 18:00:22.866  2027  2027 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 18:00:22.867  2027  2027 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471363010344, New one : 1471363222773
08-16 18:00:22.867  2027  2027 D [Concierge]WidgetView: Unregister all receivers
08-16 18:00:22.867  2027  2027 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-16 18:00:22.868  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:00:22.870  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 18:00:22.872  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 18:00:22.873  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 18:00:22.874  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 18:00:22.874  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.875  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 18:00:22.876  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 18:00:22.876  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 18:00:22.881  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 18:00:22.881  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.882  7220  7220 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 18:00:22.882  7220  7220 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:00:22.883  7220  7220 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 18:00:22.889  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 18:00:22.889  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.889  1028  1935 I ActivityManager: Killing 7565:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 18:00:22.928  2027  2027 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 18:00:22.938  2027  2027 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 18:00:22.938  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 18:00:22.940  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 18:00:22.951  1028  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:00:22.955  1028  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 18:00:22.960  2027  2027 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ca5721e time:240080
08-16 18:00:22.972  8348  8348 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 18:00:22.973  8348  8348 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 18:00:22.976  1028  1899 W libprocessgroup: failed to open /acct/uid_10005/pid_7565/cgroup.procs: No such file or directory
08-16 18:00:22.977  7165  7165 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 18:00:22.978  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 18:00:22.983  7165  7165 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 18:00:22.988  7220  7220 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 18:00:22.988  7220  7220 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 18:00:22.989  7220  7220 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 18:00:22.989  7220  7220 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 18:00:22.990  7220  7220 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 18:00:22.994  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 18:00:22.995  8397  8397 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 18:00:22.995  8397  8475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 18:00:22.996  1028  1971 I ActivityManager: Killing 7996:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 18:00:23.071  2027  2027 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 18:00:23.082  1810  1810 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-16 18:00:23.084  1028  1641 W libprocessgroup: failed to open /acct/uid_10072/pid_7996/cgroup.procs: No such file or directory
08-16 18:00:23.095  2151  2151 I ConfigService: onCreate
,08-16 18:00:23.096  2151  2151 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 18:00:23.100  1810  1810 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 18:00:23.102  2151  2151 I ConfigService: onBind returning update interface
08-16 18:00:23.103  2151  2151 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 18:00:23.103  2151  2151 I ConfigService: onBind returning config service
08-16 18:00:23.116  2027  2874 I GBoardtInterface: onReloaded()
,08-16 18:00:23.117  2151  2151 I ConfigService: onDestroy
08-16 18:00:23.118  2027  2027 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 18:00:23.118  1810  8529 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 18:00:23.119  3806  4533 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:00:23.126  3806  3825 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:00:23.132  1900  1900 D ActionManagerService: notifyUserLog: 1000001
08-16 18:00:23.133  3806  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 18:00:23.133  3806  4540 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-16 18:00:23.137  1900  1900 D ActionManagerService: notifyUserLog: 1000001
08-16 18:00:23.138  3806  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 18:00:23.138  3806  4540 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 18:00:23.138  3806  4540 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 18:00:23.138  3806  4540 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 18:00:23.139  3806  4533 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 18:00:23.141  2027  2027 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 18:00:23.141  2027  2027 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 18:00:23.145  2027  2027 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 18:00:23.145  2027  2027 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-16 18:00:23.147  2027  2027 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 18:00:23.147  2027  2027 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 18:00:23.151  6167  8535 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-16 18:00:23.153  1810  8537 I PeopleContactsSync: CP2 sync disabled
08-16 18:00:23.157  1810  4818 I Icing   : doRemovePackageData com.test.thalitest
,08-16 18:00:23.170  1810  8534 W GmsApplication: Using Auth Proxy for data requests.
,08-16 18:00:23.175  1810  8534 W GmsApplication: Using Auth Proxy for data requests.
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 18:00:23.226  6479  6479 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 18:00:23.236  2373  2528 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:23.237  2373  2528 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 18:00:23.240  2373  8540 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 18:00:23.246  2373  8540 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-16 18:00:23.247  2373  8540 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 18:00:23.247  2373  8540 E AndroidRuntime: Process: android.process.acore, PID: 2373
08-16 18:00:23.247  2373  8540 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:23.247  2373  8540 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 18:00:23.267  1028  1571 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8541 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 18:00:23.273  2373  8540 I Process : Sending signal. PID: 2373 SIG: 9
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:00:23.278  1028  8550 E DropBoxManagerService: 	... 5 more
08-16 18:00:23.279  1810  8531 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-16 18:00:23.280  1810  8531 E DriveAsyncService: disk I/O error (code 3850)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:23.280  1810  8531 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:00:23.291  4541  4592 E SQLiteDatabase: Error inserting f004=13 f005=8541 f002=1471363223270 f003=com.lge.email f006=10023
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 18:00:23.291  4541  4592 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
