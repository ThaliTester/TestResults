#### Test 81418577ad1885e_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-02 12:08:23.249  2119  2119 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
09-02 12:08:23.255  2119  2119 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,09-02 12:08:48.293  6969  6969 D AndroidRuntime: 
09-02 12:08:48.293  6969  6969 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 12:08:48.297  6969  6969 D AndroidRuntime: CheckJNI is OFF
09-02 12:08:48.504  6969  6969 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-02 12:08:48.514  1037  1919 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 12:08:48.530  1928  1944 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-02 12:08:48.536  1037  1919 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-02 12:08:48.537  1037  1919 D ActivityManager: setTaskToReturnTo : TaskRecord{20e0026e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 12:08:48.538  1037  1919 D ActivityManager: setTaskToReturnTo : TaskRecord{20e0026e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 12:08:48.539  1037  1919 D WindowStateEx: AppWindowTokenEx init.. 
09-02 12:08:48.540   327   360 E GBMv2   : DFP En is all cleared set to be enabled
09-02 12:08:48.567  1037  1919 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6984 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 12:08:48.569  6969  6969 D AndroidRuntime: Shutting down VM
09-02 12:08:48.621  1928  2775 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-02 12:08:48.621  1928  2775 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ed60ee0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 12:08:48.622  1928  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-02 12:08:48.622  1928  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3aecc599 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 12:08:48.698  6984  6984 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-02 12:08:48.798  6984  6984 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 12:08:48.807  6984  6984 I LibraryLoader: Loading: webviewchromium
09-02 12:08:48.811  6984  6984 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 109-113)
,09-02 12:08:48.811  6984  6984 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:08:48.826  6984  6984 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13cb978e}
09-02 12:08:48.827  6984  6984 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:08:48.827  6984  6984 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:08:48.836  6984  6984 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 12:08:48.837  6984  6984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 12:08:48.847  6984  6984 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-02 12:08:48.851  6984  6984 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-02 12:08:48.851   311  1535 V AudioPolicyService: registerClient() client 0xb1427160, uid 10118
09-02 12:08:48.852  6984  6984 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-02 12:08:48.857  1037  1119 D BluetoothManagerService: Message: 20
09-02 12:08:48.857  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d5cdb88:true
09-02 12:08:48.870  6984  6984 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:08:48.870  6984  6984 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:08:48.870  6984  6984 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:08:48.870  6984  6984 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:08:48.870  6984  6984 I Adreno-EGL: Remote Branch: 
09-02 12:08:48.870  6984  6984 I Adreno-EGL: Local Patches: 
09-02 12:08:48.870  6984  6984 I Adreno-EGL: Reconstruct Branch: 
,09-02 12:08:48.943  6984  7019 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-02 12:08:48.949  6984  6984 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-02 12:08:48.965  6984  6984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:08:48.970  6984  6984 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-02 12:08:48.973  6984  6984 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-02 12:08:48.975  6984  6984 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-02 12:08:48.976  6984  6984 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-02 12:08:48.989  6984  6984 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-02 12:08:48.995  6984  6984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 12:08:48.995  6984  6984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:08:49.039  6984  7031 D OpenGLRenderer: Render dirty regions requested: true
09-02 12:08:49.039  6984  7031 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 12:08:49.048  6984  7031 D OpenGLRenderer: Enabling debug mode 0
09-02 12:08:49.055  6984  6984 D Atlas   : Validating map...
09-02 12:08:49.062  1037  1886 D SplitWindow: check instance of lgWin Window{fbedd82 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 12:08:49.131  6984  7029 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:08:49.131  6984  7029 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:08:49.201  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +581ms (total +660ms)
09-02 12:08:49.202  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f32bd0f u0 com.test.thalitest/.MainActivity t6} time:170504
,09-02 12:08:49.208  6984  6984 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17e6dbb5 time:170510
09-02 12:08:49.314  6984  6984 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 12:08:49.346  6984  6984 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-02 12:08:49.346  6984  6984 I chromium: 
,09-02 12:08:49.444  6984  7042 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435168256
,09-02 12:08:49.457  6984  7042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 12:08:49.457  6984  7042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 12:08:49.457  6984  7042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 12:08:49.457  6984  7042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 12:08:49.457  6984  7042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-02 12:08:49.458  6984  7042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331dc269 added. We now have 1 listener(s)
09-02 12:08:49.462  1037  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:08:49.467  6984  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-02 12:08:49.471  6984  7042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:08:49.473  6984  7042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:49.473  6984  7042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 12:08:49.482  6984  7042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1318b81c added. We now have 1 listener(s)
09-02 12:08:49.482  6984  7042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:49.488  1037  1437 D WifiService: New client listening to asynchronous messages
,09-02 12:08:49.494  6984  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:08:49.494  6984  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 12:08:49.496  6984  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 12:08:49.496  6984  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 12:08:49.496  6984  7042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-02 12:08:49.505  6984  7042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:49.506  1037  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:08:49.509  6984  7042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-02 12:08:49.522  6984  7042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:49.522  6984  7042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:49.522  6984  7042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 12:08:49.522  6984  7042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:49.526  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:49.526  6984  7042 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 12:08:49.528  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:49.570  6984  7029 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-02 12:08:49.570  6984  7029 I chromium: 
,09-02 12:08:49.648  6984  6984 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 12:08:50.491   327   362 E GBMv2   : DFP En is all cleared set to be enabled
09-02 12:08:50.491   327   362 E GBMv2   : Set value is all cleared set the max
09-02 12:08:50.491   327   362 I GBMv2   : DFP Enabled. Ignore VFP set
,09-02 12:08:50.740  6984  7045 W jxcore-log: Initializing JXcore engine
09-02 12:08:50.740  6984  7045 W jxcore-log: JXcore engine is ready
,09-02 12:08:50.779  7045  7045 W Thread-827: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8526]" dev="sockfs" ino=8526 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 12:08:50.779  7045  7045 W Thread-827: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-02 12:08:50.779  7045  7045 W Thread-827: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9730]" dev="sockfs" ino=9730 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 12:08:50.779  7045  7045 W Thread-827: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-02 12:08:50.779  7045  7045 W Thread-827: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33819]" dev="sockfs" ino=33819 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-02 12:08:50.798  6984  7045 W jxcore-log: Starting JXcore engine
,09-02 12:08:50.878  6984  7045 W jxcore-log: Platform android
09-02 12:08:50.878  6984  7045 W jxcore-log: 
09-02 12:08:50.878  6984  7045 W jxcore-log: Process ARCH arm
09-02 12:08:50.878  6984  7045 W jxcore-log: 
,09-02 12:08:51.063  6984  7045 I jxcore-log: JXcore Cordova bridge is ready!
09-02 12:08:51.063  6984  7045 I jxcore-log: 
09-02 12:08:51.063  6984  7045 W jxcore-log: JXcore engine is started
,09-02 12:08:51.074  6984  7042 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-02 12:08:51.082  6984  6984 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 12:09:00.057  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-02 12:09:00.058  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
09-02 12:09:00.058  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-02 12:09:00.058  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
,09-02 12:09:00.063  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
,09-02 12:09:00.063  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
09-02 12:09:00.064  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
09-02 12:09:00.065  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
09-02 12:09:04.947  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 12:09:04.947  6984  7045 I jxcore-log: 
09-02 12:09:04.950  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 12:09:04.950  6984  7045 I jxcore-log: 
,09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:04.953  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:09:04.955  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-02 12:09:04.958  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 12:09:04.958  6984  7045 I jxcore-log: ,
09-02 12:09:04.959  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,09-02 12:09:04.959  6984  7045 I jxcore-log: 
09-02 12:09:05.459  6984  7045 D executeNativeTests: Running unit tests,
,09-02 12:09:05.541  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-02 12:09:05.541  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 added. We now have 2 listener(s)
,09-02 12:09:05.542  1037  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:09:05.543  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
09-02 12:09:05.543  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:05.543  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:05.543  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:05.543  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e added. We now have 2 listener(s)
09-02 12:09:05.543  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:05.544  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:09:05.546  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:05.548  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:05.549  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.549  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:05.550  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.551  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.554  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:09:05.554  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:09:05.554  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:09:05.556  6984  7045 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 12:09:05.566  6984  7045 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:09:05.566  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:09:05.566  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:09:05.567  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:09:05.570  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:09:05.574  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.574  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.576  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.576  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.576  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.577  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:05.577  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 removed from the list
09-02 12:09:05.577  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.578  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e removed from the list
09-02 12:09:05.578  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.578  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.578  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.578  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.579  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.579  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.579  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.580  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.582  6984  7045 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 12:09:05.582  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.582  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.582  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:09:05.583  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.583  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.583  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.583  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.583  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.583  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.583  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.583  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.584  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.584  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.584  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.584  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.584  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.584  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.584  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09,-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:09:05.589  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:09:05.589  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.589  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.589  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.590  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.590  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.590  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.590  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.590  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.590  6984  7045 E org.thaliproject.p2p.bt,connectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.590  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.590  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.590  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.590  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.590  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.591  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.591  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.591  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.591  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.592  6984  7045 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:09:05.593  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:05.598  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:05.599  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.599  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:05.600  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.600  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:05.601  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:09:05.601  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:09:05.601  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.601  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:09:05.602  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.604  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:09:05.604  1037  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:05.608  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:09:05.613  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:09:05.614  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 12:09:05.616  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:09:05.616  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.617  6984  7045 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:09:05.617  6984  7045 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:09:05.620  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.620  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.620  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.620  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.620  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.620  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.620  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.620  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.620  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.620  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.620  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.620  6984  7045 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:09:05.622  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:05.626  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:05.627  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.627  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:05.628  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.629  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.629  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:05.629  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:09:05.629  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:09:05.629  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.629  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:09:05.631  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:09:05.632  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.632  6984  7045 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:09:05.633  6984  7045 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:09:05.634  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.634  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.634  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:09:05.635  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.635  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.635  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.635  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.635  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.635  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.635  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.635  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.635  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.635  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.636  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.636  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.637  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.637  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.637  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.637  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.638  6984  7045 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:09:05.639  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:05.641  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:05.642  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:05.642  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:05.643  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:05.643  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:09:05.643  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: D,iscovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:09:05.643  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.643  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:09:05.644  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.648  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.649  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:09:05.649  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.650  6984  7045 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:09:05.651  6984  7045 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:09:05.651  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.651  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.651  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.651  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.651  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.651  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.652  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.652  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.652  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:05.652  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.652  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.652  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.652  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.652  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.652  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.652  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.653  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.653  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.653  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.653  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.653  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.653  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.654  6984  7045 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 12:09:05.654  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.654  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.654  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.654  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.654  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.654  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.654  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.654  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.654  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.654  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.654  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.654  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.654  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.654  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.655  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.655  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.659  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.659  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.659  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.659  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.661  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:09:05.661  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.661  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.661  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.661  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.661  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.661  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.661  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.661  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.661  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.661  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.661  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.662  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.662  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.662  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.662  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.662  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.663  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.663  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.663  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.663  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.663  6984  7045 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 12:09:05.663  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.663  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.663  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.663  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.663  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.664  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.664  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.664  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.664  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.664  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.664  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.664  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.664  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.664  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.664  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.664  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.664  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.664  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.664  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.664  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.665  6984  7045 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 12:09:05.665  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.665  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.665  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.665  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.665  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.665  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.665  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.665  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.665  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.665  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.665  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.665  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.665  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.665  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.666  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.666  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.666  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.666  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.666  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.666  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.667  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:09:05.668  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:09:05.668  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:09:05.669  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:09:05.669  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:09:05.669  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:09:05.669  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.669  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.669  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.669  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.669  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.669  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.669  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
,09-02 12:09:05.669  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.669  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.669  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.669  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.669  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.669  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.669  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.670  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.670  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.670  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.670  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.670  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.670  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.671  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:09:05.671  6984  7045 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:09:05.672  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:09:05.674  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:09:05.675  6984  7045 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:09:05.675  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:09:05.675  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 12:09:05.675  6984  7045 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:09:05.676  6984  7045 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 12:09:05.676  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:09:05.676  6984  7045 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:09:05.676  6984  7045 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 12:09:05.676  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:09:05.676  6984  7045 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:09:05.676  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 12:09:05.679  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 12:09:05.681  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 12:09:05.681  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 12:09:05.682  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 12:09:05.682  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 12:09:05.682  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 12:09:05.682  6984  7045 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:09:05.682  6984  7045 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 12:09:05.683  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.683  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.683  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.683  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.683  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.683  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.683  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 12:09:05.683  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.684  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.684  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.684  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.684  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.684  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.684  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.684  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.684  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.684  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.685  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.685  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.685  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.685  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.685  6984  7073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 891
09-02 12:09:05.685  6984  7045 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 12:09:05.686  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.686  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.686  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.686  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.686  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.686  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.686  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.686  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.686  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.686  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.686  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.686  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.686  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.686  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.687  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.687  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.687  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.687  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.687  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.687  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.688  6984  7045 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 12:09:05.688  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.688  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.688  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.689  6984  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 891)
09-02 12:09:05.689  6984  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 891)
09-02 12:09:05.690  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.690  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.690  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.690  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.690  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.690  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.690  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.690  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.690  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.690  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.690  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.691  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.691  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.692  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.692  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.692  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.692  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.693  6984  7045 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 12:09:05.693  6984  7045 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 12:09:05.693  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:09:05.693  6984  7045 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 12:09:05.693  6984  7045 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:09:05.693  6984  7045 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 12:09:05.693  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:09:05.693  6984  7045 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 12:09:05.693  6984  7045 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:09:05.693  6984  7045 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:09:05.693  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:09:05.693  6984  7045 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 12:09:05.693  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.694  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.694  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.694  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.694  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.694  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.694  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.694  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.694  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.694  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.694  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.694  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.694  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.694  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.695  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.695  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.695  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.695  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.695  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.695  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.696  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.696  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.696  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.696  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.696  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.696  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.696  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.696  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.696  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.696  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.696  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.696  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.696  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.696  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.696  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.696  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-02 12:09:05.696  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.696  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.697  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.697  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.697  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.697  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.697  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.697  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.697  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.697  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.697  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.697  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.697  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.698  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.698  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.698  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.698  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.698  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.698  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.699  6984  7045 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 12:09:05.699  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.700  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 12:09:05.700  6984  7045 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 12:09:05.700  6984  7045 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 12:09:05.701  6984  6984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 12:09:05.701  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 12:09:05.701  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:09:05.702  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.702  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 12:09:05.702  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 12:09:05.702  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 12:09:05.702  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.702  6984  7045 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 12:09:05.702  6984  6984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 12:09:05.703  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.703  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.703  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:09:05.704  6984  7045 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:09:05.704  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:09:05.704  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:09:05.705  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:05.705  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:05.705  6984  7045 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:09:05.705  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.705  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.705  6984  7045 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:09:05.706  6984  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:09:05.706  6984  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:09:05.706  6984  6984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:09:05.706  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.706  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.706  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.706  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.706  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.706  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.706  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.706  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.706  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.706  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.706  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.706  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.706  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.706  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.706  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.707  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.707  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.707  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.707  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.708  6984  7045 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 12:09:05.708  6984  7045 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:09:05.708  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:09:05.709  6984  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:09:05.710  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.710  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.710  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.710  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.710  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.710  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.710  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.710  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.710  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.710  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.710  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.710  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.710  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.710  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.711  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.711  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.711  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.711  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.712  1037  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:05.713  1037  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:05.715  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:05.716  1037  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:05.717  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.717  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.717  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.717  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.717  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.717  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.718  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.718  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.718  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.718  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.718  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.718  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.718  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.718  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.719  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.719  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.719  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.719  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.719  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:05.719  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:05.720  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:05.720  6984  7074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:05.720  4309  4325 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-02 12:09:05.721  6984  7074 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 12:09:05.721  6984  7074 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 12:09:05.721  6984  7074 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 12:09:05.722  6984  6984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 12:09:05.722  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:05.722  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.722  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.722  6984  7045 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab5acf9 not in the list
09-02 12:09:05.722  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.722  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.722  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:05.722  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.722  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.722  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:05.722  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:05.723  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:05.723  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:05.723  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:05.723  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba4b43e not in the list
09-02 12:09:05.724  6984  7045 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 12:09:05.724  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:09:05.724  6984  7045 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 12:09:05.724  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:09:05.724  6984  7045 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 12:09:05.724  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:09:05.725  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:09:05.726  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 12:09:05.726  6984  7045 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 12:09:05.726  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:09:05.726  6984  7045 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 12:09:05.726  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:09:05.726  6984  7045 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 12:09:05.726  6984  7045 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 12:09:05.727  6984  7045 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 12:09:05.727  6984  7045 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 12:09:05.728  6984  7045 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 12:09:05.728  6984  7045 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 12:09:05.728  6984  7045 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 12:09:05.728  6984  7045 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 12:09:05.729  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:05.729  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13d37697 added. We now have 2 listener(s)
09-02 12:09:05.729  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:05.731  6984  7045 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 12:09:05.732  1037  1962 D WifiServiceImplEx: setWifiEnabled: true pid=6984, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:09:05.732  1037  1962 D WifiService: setWifiEnabled: true pid=6984, uid=10118
09-02 12:09:05.732  1037  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:09:05.733  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:05.733  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ef5b084 added. We now have 3 listener(s)
09-02 12:09:05.733  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:05.735  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:05.735  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@247c906d added. We now have 4 listener(s)
09-02 12:09:05.735  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:05.737  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:05.737  6984  7045 V org.thaliproject.p2p.btconnecto,rlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e58e4a2 added. We now have 5 listener(s)
09-02 12:09:05.737  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:05.738  1037  1981 D WifiServiceImplEx: setWifiEnabled: false pid=6984, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:09:05.738  1037  1981 D WifiService: setWifiEnabled: false pid=6984, uid=10118
09-02 12:09:05.738  1037  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:09:05.750  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network],
09-02 12:09:05.750  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:05.750  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:05.751  1037  1379 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:05.751  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:05.751  1037  1379 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:05.751  1037  1379 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0,
09-02 12:09:05.751  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:05.752  1037  1379 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 12:09:05.752  1037  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:09:05.752  1037  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:09:05.752  1037  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:09:05.752  1037  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG,
09-02 12:09:05.752  1037  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:05.752  1037  1999 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14f49ad mBinding = false
09-02 12:09:05.770  1037  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:09:05.770  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:09:05.770  2674  2674 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:09:05.771  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.771  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.771  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:09:05.771  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
,09-02 12:09:05.772  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:05.772  1037  2823 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.775   307   895 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:09:05.779  1037  1119 D BluetoothManagerService: Message: 2
09-02 12:09:05.780  1037  1119 D BluetoothManagerService: Sending off request.
09-02 12:09:05.782  4309  4326 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 12:09:05.784  4309  4406 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 12:09:05.784  4309  4406 D BluetoothAdapterProperties: Setting state to 13
09-02 12:09:05.784  4309  4406 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:09:05.785  4309  4406 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:09:05.785  4309  4406 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 12:09:05.788  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:09:05.788  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:05.788  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:05.789  4309  4409 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:09:05.791  4309  4406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 12:09:05.791  4309  4406 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 12:09:05.793  4309  4679 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 12:09:05.793  4309  4742 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:05.794  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 12:09:05.794  4309  4680 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:05.795  4309  4531 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 12:09:05.795  4309  4722 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:05.795  4309  4736 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:05.799  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 12:09:05.799  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 12:09:05.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 12:09:05.802  4309  4531 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 12:09:05.807  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:05.807  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:05.808  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.808  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:09:05.825  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:05.825  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 12:09:05.825  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 12:09:05.839  1037  1873 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-02 12:09:05.840  1037  1111 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7087 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-02 12:09:05.842  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.842  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.842  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 12:09:05.842  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.842  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-02 12:09:05.844  1037  1455 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 12:09:05.844  1037  1455 D DSQN    : disableDataServiceNotify
09-02 12:09:05.844  1037  1455 D DSQN    : stop dsqn bin
09-02 12:09:05.846  1037  1379 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:09:05.846  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.846  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.846  1037  1377 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@33c16edc
09-02 12:09:05.847  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.847  1037  1377 D LGWifiP2pService: P2pDisablingState
09-02 12:09:05.847  1037  1377 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.847  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.847  1037  1377 D LGWifiP2pService: p2p socket connection lost
09-02 12:09:05.847  1037  1377 D LGWifiP2pService: P2pDisabledState
09-02 12:09:05.848  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-02 12:09:05.848  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.849  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.849  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.849  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.850  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.850  1037  1455 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 12:09:05.850  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:05.850  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:05.851  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.851  1037  1455 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:05.851  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:05.851  1037  1455 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 12:09:05.851  1037  1037 D WifiHS20: hidePasspointNotification off =f,alse
,09-02 12:09:05.852  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 12:09:05.852  1590  2037 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 12:09:05.853  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:05.853  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:05.853  1037  1455 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 12:09:05.853  1037  1455 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 12:09:05.853  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:09:05.854  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.854  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.855  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:05.855  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.855  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.855  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:05.855  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:05.855  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 12:09:05.856   307  7098 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 12:09:05.857  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 12:09:05.857  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-02 12:09:05.857  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 12:09:05.857  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-02 12:09:05.857  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.857  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:05.857  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:05.857  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.857  1037  2821 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 12:09:05.857,  1037  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.858  1037  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.859  1037  1377 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.859  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:05.859  1037  1377 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.859  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:09:05.859  2674  2674 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:09:05.859  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:09:05.859  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:09:05.859  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:05.860  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:05.860   307   895 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:09:05.860  1037  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:05.860  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:09:05.860  1928  1928 D WfdsService: WifiP2pState is changed : false
09-02 12:09:05.860  1037  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:05.860  1928  2282 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 12:09:05.860  1928  2282 D WfdsService: Set the WFDS Monitor: false
09-02 12:09:05.861  1037  1455 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:05.861  1037  1455 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:05.861  1037  1455 D NetworkManagementService: Removing idletimer
09-02 12:09:05.861  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:05.862  1928  2728 D CtrlSupplicant: Received on exit socket, terminate
09-02 12:09:05.862  1928  2728 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 12:09:05.862  1928  2728 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
,09-02 12:09:05.863  1037  1455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.863  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:05.864  1037  1455 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 12:09:05.864  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-02 12:09:05.866  1037  1379 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 12:09:05.867  1037  1379 D WifiNative-p2p0: TERMINATE: returned true
09-02 12:09:05.868  1928  2728 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 12:09:05.868  1928  2282 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:09:05.868  1928  2282 D WfdsService: STATE : WfdsDisabledState - enter
09-02 12:09:05.869  1928  2284 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 12:09:05.869  1928  2282 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 12:09:05.869  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:05.870  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:05.870  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:05.871  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.871  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:05.871  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:05.872  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:05.872  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:05.872  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:05.872  4309  4309 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:05.872  4309  4309 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:09:05.873  4309  4309 V BluetoothMapService: Handler(): got msg=4
09-02 12:09:05.873  4309  4309 D BluetoothMapService: MAP Service closeService in
09-02 12:09:05.873  4309  4309 D BluetoothMapMasInstance: MAP Service shutdown
09-02 12:09:05.873  4309  4309 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:09:05.873  4309  4309 V BluetoothMapService: MAP Service closeService out
09-02 12:09:05.874  4309  4309 V BtOppService: Receiver DISABLED_ACTION 
09-02 12:09:05.874  4309  4309 I BtOppRfcommListener: stopping Accept Thread
09-02 12:09:05.874  4309  4309 V BtOppRfcommListener: close mBtServerSocket
09-02 12:09:05.874  4309  4309 V BtOppRfcommListener: waiting for thread to terminate
09-02 12:09:05.874  4309  4722 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:09:05.875  4309  4309 V BtOppRfcommListener: done waiting for thread to terminate
,09-02 12:09:05.876  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:05.877  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:05.877  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:05.878  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.878  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:05.879  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:05.879  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:05.880  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:05.880  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:05.919  1037  1111 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7112 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 12:09:05.920  1037  1379 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:05.920  1037  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 12:09:05.923  4309  4309 V BtOppService: onDestroy
09-02 12:09:05.925  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:09:05.925  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:09:05.927  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 12:09:05.927  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,09-02 12:09:05.927  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:09:05.927  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:09:05.927  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:09:05.927  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:09:05.928  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:09:05.928  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:09:05.928  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.929  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.929  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-02 12:09:05.930  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.930  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:05.930  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-02 12:09:05.934  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 12:09:05.936  4309  4309 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 12:09:05.936  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 12:09:05.937  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:05.937  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 12:09:05.937  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:05.938  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:05.966  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:09:05.967  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:05.969  2674  2674 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 12:09:05.969  2674  2674 I wpa_supplicant: monitor socket send errors count : 1
09-02 12:09:05.969  2674  2674 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
09-02 12:09:05.970  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:05.970  1037  2719 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 12:09:05.970  1037  2719 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 12:09:05.974  7112  7112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:05.974  7112  7112 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-02 12:09:05.974  7112  7112 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:05.974  7112  7112 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-02 12:09:05.975  7112  7112 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 12:09:05.976  7112  7112 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 12:09:05.979  1037  2823 D DhcpStateMachine: StoppedState
09-02 12:09:05.979  1037  2823 D DhcpStateMachine: StoppedState{ when=-119ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:05.980  1037  1379 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 12:09:05.980  1037  1379 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-02 12:09:05.984  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:09:05.985  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:05.985  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:05.986  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 12:09:05.986  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:05.987  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:06.007  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:06.016  2674  2674 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:09:06.016  2674  2674 W wpa_supplicant: USIM:  scard_deinit function
09-02 12:09:06.017  1037  2719 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 12:09:06.018  1037  2719 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:09:06.018  1037  2719 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:09:06.018  1037  1119 D Tethering: InitialState.processMessage what=4
09-02 12:09:06.018  1037  2719 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 12:09:06.018  1037  2719 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:06.018  1037  2719 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:06.018  1037  1379 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=187307
09-02 12:09:06.019  1037  1379 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=187308
,09-02 12:09:06.019  1037  1379 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=187308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:09:06.019  1037  1379 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=187308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:09:06.019  7087  7087 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 12:09:06.019  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:09:06.020  7087  7087 W LG Account v2.2: No ProfileInfo entries
09-02 12:09:06.020  7087  7087 I LG Account v2.2: isEnabled: false
09-02 12:09:06.020  7087  7087 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 12:09:06.020  1037  1379 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:06.021  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:06.027  7087  7087 I Feature : [Lifetracker]Country: EU
09-02 12:09:06.027  7087  7087 I Feature : [Lifetracker]Operator: OPEN
09-02 12:09:06.027  7087  7087 I Feature : [Lifetracker]Ranking support: false
,09-02 12:09:06.027  7087  7087 I Feature : [Lifetracker]Comfort support: false
09-02 12:09:06.028  7087  7087 I Feature : [Lifetracker]Accessory: true
09-02 12:09:06.028  7087  7087 I Feature : [Lifetracker]Health device: true
09-02 12:09:06.028  7087  7087 I Feature : [Lifetracker]Extra Pedometer: false
09-02 12:09:06.028  7087  7087 I Feature : [Lifetracker]Blood glucose device: false
09-02 12:09:06.028  7087  7087 I Feature : [Lifetracker]Device Number: 3
09-02 12:09:06.036  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:06.054  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 12:09:06.074  1037  1962 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:09:06.076  1037  1962 I ActivityManager: Killing 6460:com.android.defcontainer/u0a4 (adj 15): empty #17
09-02 12:09:06.109  2674  2674 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 12:09:06.113  1037  2719 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 12:09:06.113  1037  2719 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 12:09:06.113  1037  2719 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 12:09:06.114  1037  1379 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-02 12:09:06.118  1037  1981 W libprocessgroup: failed to open /acct/uid_10004/pid_6460/cgroup.procs: No such file or directory
09-02 12:09:06.128  4309  4309 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 12:09:06.128  4309  4309 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:06.128  4309  4309 V BluetoothPbapReceiver: ***********state = 13
09-02 12:09:06.130  4309  4309 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-02 12:09:06.131  1037  1119 D BluetoothManagerService: Message: 20
09-02 12:09:06.132  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39edea5c:true
09-02 12:09:06.132  4309  4309 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:06.132  4309  4309 V BluetoothPbapService: state: 13
09-02 12:09:06.132  4309  4309 V BluetoothPbapService: Pbap Service closeService in
09-02 12:09:06.134  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:09:06.134  4309  4309 V BluetoothPbapService: successfully stopped pbap service
09-02 12:09:06.134  4309  4309 V BluetoothPbapService: Pbap Service closeService out
09-02 12:09:06.135  4309  4309 V BluetoothPbapService: Pbap Service onDestroy
09-02 12:09:06.135  4309  4309 V BluetoothPbapService: Pbap Service closeService in
,09-02 12:09:06.135  4309  4309 V BluetoothPbapService: Pbap Service closeService out
09-02 12:09:06.135  4309  4309 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 12:09:06.153  1037  1119 D BluetoothManagerService: Message: 30
,09-02 12:09:06.158  1037  1119 D BluetoothManagerService: Message: 30
09-02 12:09:06.161  7112  7112 D LocalBluetoothProfileManager: Adding local MAP profile
09-02 12:09:06.163  7112  7112 D BluetoothMap: Create BluetoothMap proxy object
09-02 12:09:06.163  1037  1119 D BluetoothManagerService: Message: 30
09-02 12:09:06.168  1037  1119 D BluetoothManagerService: Message: 30
,09-02 12:09:06.169  7112  7112 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-02 12:09:06.170  7112  7112 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-02 12:09:06.183  7112  7112 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-02 12:09:06.187  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-02 12:09:06.195  7112  7112 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:09:06.203  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:09:06.206  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:06.206  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:06.207  6984  6984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:09:06.209  1037  2018 I ActivityManager: Killing 6618:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-02 12:09:06.212  7112  7112 D BluetoothInputDevice: Proxy object connected
09-02 12:09:06.213  7112  7112 D HidProfile: Bluetooth service connected
09-02 12:09:06.214  7112  7112 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:09:06.216  7112  7112 D PanProfile: Bluetooth service connected
09-02 12:09:06.216  7112  7112 D BluetoothMap: Proxy object connected
09-02 12:09:06.218  7112  7112 D MapProfile: Bluetooth service connected
09-02 12:09:06.218  7112  7112 D BluetoothMap: getConnectedDevices()
09-02 12:09:06.219  7112  7112 D BluetoothMap: Bluetooth is Not enabled
09-02 12:09:06.219  7112  7112 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-02 12:09:06.269  1037  1962 W libprocessgroup: failed to open /acct/uid_10008/pid_6618/cgroup.procs: No such file or directory
,09-02 12:09:06.280  1928  1928 D WfdsService: Supplicant Connection state is changed : false
09-02 12:09:06.280  1037  1379 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 12:09:06.280  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:06.280  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:06.280  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:06.281  1928  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 12:09:06.281  1928  2282 D WfdsService: Set the WFDS Monitor: false
09-02 12:09:06.281  1928  2282 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:09:06.286  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:06.288  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:09:06.289  2495  2495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:06.290  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 12:09:06.291  1037  1429 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 12:09:06.291  1037  1429 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 12:09:06.293  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:06.295  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:06.302  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:06.360  7112  7112 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:09:06.360  7112  7112 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:06.379  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:06.381  7112  7112 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 12:09:06.387  7112  7112 D BluetoothPermissionRequest: onReceive
,09-02 12:09:06.391  7112  7112 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 12:09:06.401  1037  1687 I ActivityManager: Killing 6666:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-02 12:09:06.404  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:09:06.493  4309  4309 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-02 12:09:06.493  4309  4309 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 12:09:06.494  1037  1945 W libprocessgroup: failed to open /acct/uid_10011/pid_6666/cgroup.procs: No such file or directory
09-02 12:09:06.495  4309  4309 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 12:09:06.532  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:06.534  4309  4309 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:06.535  4309  4309 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 12:09:06.539  4309  4309 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:09:06.539  4309  4309 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:06.540  4309  4309 V BluetoothFtpService: Ftp Service closeService
09-02 12:09:06.540  4309  4309 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 12:09:06.541  4309  4309 V BluetoothFtpService: successfully stopped ftp service
09-02 12:09:06.542  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:06.542  4309  4309 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:09:06.542  4309  4309 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:06.542  4309  4309 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:06.543  4309  4309 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:06.543  4309  4309 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 12:09:06.543  4309  4309 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:09:06.546  4309  4309 V BluetoothFtpService: Ftp Service onDestroy
09-02 12:09:06.546  4309  4309 V BluetoothFtpService: Ftp Service closeService
,09-02 12:09:06.631  1037  1908 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:09:06.632  4309  4309 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:06.632  4309  4309 V BluetoothSapService: state: 13
09-02 12:09:06.632  4309  4309 V BluetoothSapService: Stopping SAP server process
,09-02 12:09:06.633  4309  4309 V BluetoothSapService: Sap Service closeSapService in
09-02 12:09:06.634  4309  4309 V BluetoothSapService: Close listen Socket : 
09-02 12:09:06.634  4309  4309 V BluetoothSapService: Close rfcomm Socket : 
09-02 12:09:06.634  4309  4309 V BluetoothSapService: Close sapd  Socket : 
09-02 12:09:06.637  4309  4309 V BluetoothSapService: Sap Service closeSapService out
09-02 12:09:06.638  4309  4309 V BluetoothSapService: Sap Service onDestroy
09-02 12:09:06.638  4309  4309 V BluetoothSapService: Sap Service closeSapService in
09-02 12:09:06.638  4309  4309 V BluetoothSapService: Close listen Socket : 
09-02 12:09:06.638  4309  4309 V BluetoothSapService: Close rfcomm Socket : 
09-02 12:09:06.638  4309  4309 V BluetoothSapService: Close sapd  Socket : 
09-02 12:09:06.638  4309  4309 V BluetoothSapService: Sap Service closeSapService out
09-02 12:09:06.639  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:09:06.645  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:06.649  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:09:06.650  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:06.650  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:06.655  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:06.655   331   331 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 24.482ms
09-02 12:09:06.661  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:06.667  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:06.668  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:09:06.669  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:09:06.673  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:06.677  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:09:06.677  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:06.677  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:06.682  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:06.688  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:06.689   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 33.131ms
09-02 12:09:06.701  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:06.701  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:06.703  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:09:06.710  7164  7164 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:06.710   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 19.903ms
09-02 12:09:06.762  1037  1981 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7181 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 12:09:06.765  1037  1981 I ActivityManager: Killing 6693:com.android.contacts/u0a19 (adj 15): empty #17
09-02 12:09:06.801  4309  4409 D bt_hci_bdroid: cleanup
09-02 12:09:06.801  4309  4536 I bt_lpm  : LPM is already off!!!
,09-02 12:09:06.801  4309  4646 I bt_userial_mct: exiting userial_read_thread
09-02 12:09:06.801  4309  4646 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 12:09:06.801  4309  4531 W bt-btif : ag scb idx 1 not allocated
09-02 12:09:06.801  4309  4531 E bt-btif : BTA AG is already disabled, ignoring ...
,09-02 12:09:06.801  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:06.801  4309  4409 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 12:09:06.801  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:06.801  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:06.802  4309  4536 I bt_vendor: hw_epilog_process
09-02 12:09:06.802  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:06.803  4309  4409 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 12:09:06.803  4309  4409 D bt_userial_mct: userial_close
09-02 12:09:06.803  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:06.803  4309  4409 E bt_userial_mct: pthread_join() FAILED result:3
09-02 12:09:06.803  4309  4409 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 12:09:06.803  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:06.803  4309  4531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:06.803  4309  4531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:06.803  4309  4531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:06.803  4309  4531 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 12:09:06.820  1037  2018 W libprocessgroup: failed to open /acct/uid_10019/pid_6693/cgroup.procs: No such file or directory
,09-02 12:09:06.857  4309  4409 D bt_hci_bdroid: set_power 0
09-02 12:09:06.857  4309  4409 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 12:09:06.857  4309  4409 I bt_vendor: bluetooth satus is on
,09-02 12:09:06.858  4309  4409 I bt_vendor: bt-vendor : resetting BT status
09-02 12:09:06.858  4309  4409 I bt_vendor: Starting hciattach daemon
09-02 12:09:06.858  4309  4409 I bt_vendor: try to set false
09-02 12:09:06.859  4309  4409 I bt_vendor: Starting hciattach daemon
09-02 12:09:06.859  4309  4409 I bt_vendor: try to set false
09-02 12:09:06.860  4309  4409 I bt_vendor: cleanup
,09-02 12:09:06.861  4309  4531 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 12:09:06.861  4309  4409 I GKI_LINUX: GKI_exit_task 0 done
09-02 12:09:06.861  4309  4409 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 12:09:06.862  4309  4406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 12:09:06.865  4309  4309 D HeadsetService: Received stop request...Stopping profile...
09-02 12:09:06.867  4309  4309 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:09:06.867  4309  4309 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:09:06.867  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
09-02 12:09:06.867  4309  4482 D HeadsetStateMachine: Exit Disconnected: -1
09-02 12:09:06.868  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:06.869  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 12:09:06.869  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:06.869  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:06.869  1839  1839 D BluetoothHeadset: Proxy object disconnected
,09-02 12:09:06.872  4309  4309 D A2dpService: Received stop request...Stopping profile...
09-02 12:09:06.872  4309  4514 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:09:06.874  4309  4309 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 12:09:06.880  4309  4406 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 12:09:06.881  4309  4309 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 12:09:06.881  4309  4309 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:09:06.881  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
09-02 12:09:06.882  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-02 12:09:06.882  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 12:09:06.883  4309  4309 D HeadsetStateMachine: Unbinding service...
,09-02 12:09:06.886  4309  4309 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:09:06.886  4309  4309 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:09:06.886  4309  4309 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:09:06.886  4309  4309 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:09:06.886  4309  4309 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:09:06.886  4309  4309 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:09:06.886  4309  4309 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:09:06.887  4309  4309 D HidService: Received stop request...Stopping profile...
09-02 12:09:06.887  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
09-02 12:09:06.888  4309  4309 D HealthService: Received stop request...Stopping profile...
09-02 12:09:06.888  7112  7112 D BluetoothInputDevice: Proxy object disconnected
09-02 12:09:06.888  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
09-02 12:09:06.888  7112  7112 D HidProfile: Bluetooth service disconnected
09-02 12:09:06.890  4309  4309 D PanService: Received stop request...Stopping profile...
09-02 12:09:06.890  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
09-02 12:09:06.891  4309  4309 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:09:06.891  7112  7112 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:09:06.891  7112  7112 D PanProfile: Bluetooth service disconnected
09-02 12:09:06.892  4309  4309 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:09:06.892  4309  4309 D BtGatt.GattService: stop()
09-02 12:09:06.892  4309  4309 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 12:09:06.893  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
09-02 12:09:06.894  4309  4309 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:09:06.894  4309  4309 D BluetoothMapService: stop()
09-02 12:09:06.895  4309  4309 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 12:09:06.895  4309  4309 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 12:09:06.895  4309  4309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bb0fbaf
,09-02 12:09:06.898  7112  7112 D BluetoothMap: Proxy object disconnected
09-02 12:09:06.898  7112  7112 D MapProfile: Bluetooth service disconnected
09-02 12:09:06.899  4309  4309 I BluetoothA2dpServiceJni: cleanupNative
09-02 12:09:06.899  4309  4515 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 12:09:06.903  4309  4309 I GKI_LINUX: GKI_exit_task 2 done
09-02 12:09:06.903  4309  4309 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 12:09:06.904  4309  4309 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:09:06.904  4309  4309 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:09:06.905  4309  4309 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:09:06.905  4309  4309 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:09:06.905  4309  4309 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:09:06.907  4309  4309 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:09:06.907  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:06.907  4309  4309 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 12:09:06.908  4309  4309 V BluetoothMapService: Handler(): got msg=4
09-02 12:09:06.908  4309  4309 D BluetoothMapService: MAP Service closeService in
09-02 12:09:06.908  4309  4309 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:09:06.908  4309  4309 V BluetoothMapService: MAP Service closeService out
09-02 12:09:06.909  4309  4406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 12:09:06.909  4309  4406 D BluetoothAdapterProperties: Setting state to 10
09-02 12:09:06.909  4309  4406 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 12:09:06.909  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:06.909  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 12:09:06.910  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-02 12:09:06.910  4309  4309 D BluetoothMapService: cleanup()
09-02 12:09:06.910  4309  4309 D BluetoothMapService: MAP Service closeService in
09-02 12:09:06.910  4309  4309 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:09:06.910  4309  4309 V BluetoothMapService: MAP Service closeService out
09-02 12:09:06.910  4309  4406 I BluetoothAdapterState: Entering OffState
09-02 12:09:06.910  1839  3484 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:06.911  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:06.912  7112  7128 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:09:06.913  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:06.913  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:09:06.914  7112  7129 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:09:06.914  1839  2440 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:06.915  7112  7128 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:09:06.923  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:09:06.926  7112  7129 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:09:06.928  7181  7201 W FormManager: Network not available. Please check & try again.
09-02 12:09:06.929  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 12:09:06.929  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 12:09:06.932  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 12:09:06.932  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 12:09:06.932  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@14f49ad mBinding = false
09-02 12:09:06.933  1037  1119 D BluetoothManagerService: Sending unbind request.
09-02 12:09:06.933  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:06.934  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 12:09:06.938  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:06.941  1928  2109 D LGBluetoothAPIService: Message: 2
09-02 12:09:06.941  1928  2109 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@285af05e mBinding = false
09-02 12:09:06.941  1928  2109 D LGBluetoothAPIService: Sending unbind request.
09-02 12:09:06.941  7112  7112 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 12:09:06.942  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:06.942  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 12:09:06.942  4309  4409 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-02 12:09:06.943  7112  7112 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 12:09:06.943  4309  4309 I GKI_LINUX: GKI_exit_task 1 done
09-02 12:09:06.943  4309  4309 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 12:09:06.943  4309  4309 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 12:09:06.945  4309  4309 I art     : --- WEIRD: removing null entry 246
09-02 12:09:06.945  4309  4309 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-02 12:09:06.945  4309  4309 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 12:09:06.947  4309  4309 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 12:09:06.948  1590  1590 D BluetoothAdapter: 943413990: getState() :  mService = null. Returning STATE_OFF
09-02 12:09:06.948  1590  1590 D BluetoothAdapter: 943413990: getState() :  mService = null. Returning STATE_OFF
09-02 12:09:06.949  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:09:06.949  4309  4309 I art     : System.exit called, status: 0
09-02 12:09:06.950  4309  4309 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:09:06.958  7112  7112 D DockEventReceiver: finishStartingService: stopping service
09-02 12:09:06.964  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:06.964  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:06.968   311  1385 V AudioFlinger: 4309 died, releasing its sessions
09-02 12:09:06.968   311  1385 V AudioFlinger:  pid 1839 @ 0
09-02 12:09:06.968   311  1385 V AudioFlinger:  pid 3310 @ 1
09-02 12:09:06.968   311  1385 V AudioFlinger:  pid 3310 @ 2
09-02 12:09:06.970  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:09:06.970  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:09:06.970  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:09:06.971  7112  7112 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:09:06.987  1037  1886 I ActivityManager: Process com.android.bluetooth (pid 4309) has died
09-02 12:09:06.988  1037  1886 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-02 12:09:06.991  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:09:06.992  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:09:06.995  7181  7203 V FormManager: Network unavailable.
09-02 12:09:07.002  7181  7203 V FormManager: Network unavailable.
,09-02 12:09:07.009  7112  7112 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:09:07.010  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 12:09:07.010  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:09:07.010  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:09:07.010  7112  7112 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:09:07.010  7112  7112 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:09:07.013  7112  7112 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 12:09:07.017  7112  7112 D BluetoothPermissionRequest: onReceive
,09-02 12:09:07.018  7112  7112 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 12:09:07.019  7112  7112 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 12:09:07.020  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:09:07.080  1037  1999 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7208 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 12:09:07.081  1037  1999 I ActivityManager: Killing 6721:com.lge.email/u0a23 (adj 15): empty #17
09-02 12:09:07.129  1037  2019 W libprocessgroup: failed to open /acct/uid_10023/pid_6721/cgroup.procs: No such file or directory
,09-02 12:09:07.137  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:07.138  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:09:07.149  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:09:07.153  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:07.164  7208  7208 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-02 12:09:07.165  7208  7208 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:07.165  7208  7208 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-02 12:09:07.167  7208  7208 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 12:09:07.168  7134  7134 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 12:09:07.168  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:07.168  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:07.174  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:09:07.174  4801  7225 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:09:07.176  7181  7229 W FormManager: Network not available. Please check & try again.
,09-02 12:09:07.182  4801  7227 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:07.182  4801  7227 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:07.184  7181  7230 V FormManager: Network unavailable.
09-02 12:09:07.184  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:07.192  7208  7208 D BluetoothAdapterApp: Loading JNI Library
09-02 12:09:07.196  7181  7230 V FormManager: Network unavailable.
,09-02 12:09:07.227  7208  7208 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1c8ffc24 Instance Count = 1
,09-02 12:09:07.233  7208  7208 D BluetoothAdapterApp: onCreate
,09-02 12:09:07.257  7208  7208 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 12:09:07.257  7208  7208 D ProfileConfigQcom: Adding HeadsetService
09-02 12:09:07.257  7208  7208 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-02 12:09:07.257  7208  7208 D ProfileConfigQcom: Adding A2dpService
09-02 12:09:07.258  7208  7208 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 12:09:07.258  7208  7208 D ProfileConfigQcom: Adding HidService
09-02 12:09:07.258  7208  7208 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 12:09:07.258  7208  7208 D ProfileConfigQcom: Adding HealthService
09-02 12:09:07.258  7208  7208 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 12:09:07.259  7208  7208 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 12:09:07.259  7208  7208 D ProfileConfigQcom: Adding PanService
09-02 12:09:07.259  7208  7208 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 12:09:07.260  7208  7208 D ProfileConfigQcom: Adding GattService
09-02 12:09:07.260  7208  7208 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 12:09:07.260  7208  7208 D ProfileConfigQcom: Adding BluetoothMapService
09-02 12:09:07.260  7208  7208 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 12:09:07.262  7208  7208 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 12:09:07.269  7112  7112 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 12:09:07.271  7208  7208 V LGMDMManagerInternal: Create singleton instance
,09-02 12:09:07.336  7208  7208 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:07.341  7208  7208 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:09:07.341  7208  7208 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:07.341  7208  7208 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:07.342  7208  7208 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:07.342  7208  7208 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 12:09:07.354  7164  7164 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-02 12:09:07.359  1037  1060 I ActivityManager: Killing 6745:com.android.gallery3d/u0a27 (adj 15): empty #17
09-02 12:09:07.434  1037  1886 W libprocessgroup: failed to open /acct/uid_10027/pid_6745/cgroup.procs: No such file or directory
,09-02 12:09:08.864  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:08.880  1037  1764 D WifiServiceImplEx: setWifiEnabled: true pid=6984, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:09:08.880  1037  1764 D WifiService: setWifiEnabled: true pid=6984, uid=10118
09-02 12:09:08.880  1037  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:09:08.885  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:08.889  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 12:09:08.895  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:08.897  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:08.902  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:08.907  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 12:09:08.912  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-02 12:09:08.915  1037  1379 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 12:09:08.915  1037  1379 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 12:09:08.916  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:08.916  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:08.917  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 12:09:08.918  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 12:09:08.918  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:09:08.918  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 12:09:08.918  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:09:08.918  1037  1379 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 12:09:08.918  1037  1379 E WifiHW  : unknown target_country: EU , set to default
09-02 12:09:08.918  1037  1379 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 12:09:08.918  1037  1379 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 12:09:08.918  1037  1379 I WifiUtil: gEnableBmps=1
09-02 12:09:08.932  6570  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-02 12:09:08.943  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:08.944  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:08.947  5874  5874 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 12:09:08.955  5874  5874 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 12:09:08.985  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:09.033  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:09.059  1037  1060 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7259 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-02 12:09:09.062  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:09.062  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 12:09:09.155  7259  7259 I AppUp4:AppBoxCP: onCreate
09-02 12:09:09.156  7259  7259 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-02 12:09:09.167  7259  7259 I AppUp4:DB:  setFingerPrint start
,09-02 12:09:09.168  7259  7259 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-02 12:09:09.177  7259  7259 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-02 12:09:09.177  7259  7259 I AppUp4:DB:  SDK version = 21
09-02 12:09:09.177  7259  7259 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-02 12:09:09.180  7259  7259 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-02 12:09:09.182  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:09:09.182  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:09.185  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:09:09.185  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:09:09.193  7259  7259 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 12:09:09.239  7259  7259 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:09.239  7259  7259 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:09.248  7259  7259 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13cb978e
,09-02 12:09:09.248  7259  7259 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:09:09.248  7259  7259 D AppUp4:CustFacade: isPhone : true
09-02 12:09:09.249  7259  7259 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:09:09.250  7259  7259 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-02 12:09:09.250  7259  7259 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-02 12:09:09.251  7259  7276 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-02 12:09:09.251  7259  7276 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-02 12:09:09.251  7259  7276 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-02 12:09:09.255  1037  1886 I ActivityManager: Killing 6766:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-02 12:09:09.316  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:09.316  1037  2018 W libprocessgroup: failed to open /acct/uid_10061/pid_6766/cgroup.procs: No such file or directory
09-02 12:09:09.316  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-02 12:09:09.328  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:09.333  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:09.342  4801  7282 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:09:09.346  4801  7283 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:09.346  4801  7283 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 12:09:09.416  1037  1981 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7284 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 12:09:09.497  7284  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:09:09.498  7284  7284 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:09.499  7284  7284 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-02 12:09:09.500  7284  7284 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:09:09.594  7284  7284 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-02 12:09:09.612  7284  7284 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-02 12:09:09.653  7284  7284 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 12:09:09.686  7284  7284 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:09.687  7284  7284 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:09.799  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:09:09.799  1037  1119 D Tethering: InitialState.processMessage what=4
09-02 12:09:09.803  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 12:09:09.810   307   895 D SoftapController: Softap fwReload - Ok
09-02 12:09:09.813  1037  1379 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (884ms)
09-02 12:09:09.815   307   895 D CommandListener: Setting iface cfg
09-02 12:09:09.815   307   895 D CommandListener: Trying to bring down wlan0
09-02 12:09:09.815   307   895 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:09:09.817  1037  1379 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 12:09:09.822  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:09.822  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:09.822  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:09.826  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:09.828  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 12:09:09.819  7312  7312 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:09.819  7312  7312 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:09.830  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:09.830  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-02 12:09:09.831  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:09.833  1037  1379 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 12:09:09.833  1037  1379 D WifiMonitor: connecting to supplicant
,09-02 12:09:09.853  7312  7312 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 12:09:09.860  7284  7284 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:09:09.890  3310  3310 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:09:09.890  3310  3310 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:09.890  3310  3310 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-02 12:09:09.900  7312  7312 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 12:09:09.900  7312  7312 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 12:09:09.929  1037  2018 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7322 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-02 12:09:09.935  7181  7319 W FormManager: Network not available. Please check & try again.
09-02 12:09:09.937  7181  7320 V FormManager: Network unavailable.
09-02 12:09:09.939  7181  7320 V FormManager: Network unavailable.
09-02 12:09:09.948  7284  7284 I HubEmail: JNI_OnLoad()
09-02 12:09:09.948  7284  7284 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 12:09:09.948  7284  7284 I HubEmail: registerNatives()
09-02 12:09:09.948  7284  7284 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 12:09:09.948  7284  7284 I HubEmail: registerNativeMethods()
09-02 12:09:09.948  7284  7284 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,09-02 12:09:09.949  7284  7284 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-02 12:09:09.953  1037  1945 I ActivityManager: Killing 6793:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-02 12:09:09.963  7312  7312 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 12:09:09.979  7284  7339 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:09.979  7312  7312 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-02 12:09:09.982  1037  1873 W libprocessgroup: failed to open /acct/uid_10080/pid_6793/cgroup.procs: No such file or directory
09-02 12:09:09.983  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:09:09.983  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 12:09:09.984  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:09:09.984  1037  1379 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:09:09.984  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:09.984  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:09.984  1037  1379 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 12:09:09.984  1037  1379 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 12:09:09.985  1037  1379 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 12:09:09.985  1037  1379 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 12:09:09.985  1037  1379 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 12:09:09.985  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:09.985  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:09.985  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:09.986  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:09.986  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:09.986  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:09.986  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:09.986  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:09.987  1037  1379 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 12:09:09.987  1928  1928 D WfdService: Waiting for WifiP2p enabling
09-02 12:09:09.988  1037  1379 D WifiNative-wlan0: SET update_config 1: returned true
09-02 12:09:09.988  1037  1379 D WifiConfigStore: Loading config and enabling all networks 
09-02 12:09:09.988  1037  1379 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 12:09:09.988  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:09.989  1037  1379 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 12:09:09.989  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 12:09:09.989  1037  1429 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 12:09:09.989  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:09.989  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:09.989  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:09.990  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:09.990  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:09.990  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:09.991  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:09.991  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:09:10.000  1037  1379 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 12:09:10.004  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-02 12:09:10.004  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-02 12:09:10.004  1037  7340 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 12:09:10.009  1037  1379 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 12:09:10.009  1037  1379 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-02 12:09:10.011  1037  1379 D WifiStateMachine: enableVerboseLogging : level 2
09-02 12:09:10.011  1037  1379 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-02 12:09:10.011  1037  1379 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,09-02 12:09:10.011  1037  1379 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 12:09:10.012  1037  1379 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 12:09:10.012  1037  1379 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 12:09:10.012  1037  1379 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 12:09:10.012  1037  1379 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 12:09:10.012  1037  1379 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 12:09:10.012  1037  1379 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 12:09:10.013  1037  1379 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 12:09:10.013  1037  1379 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 12:09:10.013  1037  1379 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 12:09:10.013  1037  1379 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 12:09:10.013  1037  1379 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 12:09:10.015  1928  1928 D WfdsService: Supplicant Connection state is changed : true
09-02 12:09:10.015  1928  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 12:09:10.015  1928  2282 D WfdsService: Set the WFDS Monitor: true
09-02 12:09:10.015  1928  2282 D WfdsMonitor: WfdsMonitorThread create
09-02 12:09:10.015  1037  1379 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:09:10.015  1037  1379 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 12:09:10.015  1928  2282 D WfdsMonitor: WFDS Monitor is created and started
09-02 12:09:10.015  1928  2282 D WfdsService: WiFi: Supplicant connection re-established
09-02 12:09:10.016  1037  1379 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 12:09:10.016  1037  1379 D WifiNative-HAL: Setting external_sim to 1
09-02 12:09:10.016  1037  1379 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 12:09:10.016  1928  7341 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 12:09:10.016  1037  1379 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 12:09:10.016  1037  1379 I WifiNative-HAL: startHal
09-02 12:09:10.016  1037  1379 D wifi    : setting scan oui 0xaf765440
09-02 12:09:10.016  1928  7341 E CtrlSupplicant: Succeed to open control connection
09-02 12:09:10.016  1037  1379 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:09:10.016  1037  1379 I WifiNative-HAL: startHal
09-02 12:09:10.016  1037  1379 D wifi    : setting scan oui 0xaf765440
09-02 12:09:10.017  1928  7341 E CtrlSupplicant: Succeed to open monitor connection
09-02 12:09:10.017  1037  1379 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 12:09:10.017  1928  7341 D WfdsMonitor: Supplicant connection established
09-02 12:09:10.017  1928  2282 D WfdsService: Connected to the supplicant for wfds
09-02 12:09:10.018  1037  1379 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 12:09:10.018  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 12:09:10.018  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 12:09:10.018  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 12:09:10.018  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:09:10.018  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:09:10.019  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:09:10.019  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 12:09:10.019  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 12:09:10.019  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 12:09:10.019  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:09:10.019  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:09:10.019  10,37  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:09:10.019  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:09:10.019  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:09:10.020  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:09:10.020  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 12:09:10.020  7312  7312 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 12:09:10.020  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 12:09:10.020  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:09:10.020  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:09:10.021  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:09:10.021  1037  1379 E WifiNative: : [191,310,289 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 12:09:10.021  1037  1379 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 12:09:10.022  1037  1379 D WifiNative-wlan0: RECONNECT: returned true
09-02 12:09:10.022  1037  1379 D WifiNative-wlan0: doString: [STATUS]
09-02 12:09:10.022  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:09:10.022  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
09-02 12:09:10.022  1037  1379 D WifiNative-wlan0:    returned wpa_state=DISCONNECTED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:09:10.022  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:10.023  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:10.023  1037  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.024  1037  1379 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:09:10.024  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
,09-02 12:09:10.024  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-02 12:09:10.024  1037  1379 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 12:09:10.024  1037  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.025  1037  1379 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 12:09:10.025  1037  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.024  1037  1543 I WifiNative-HAL: startHal
09-02 12:09:10.025  1037  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf765440
09-02 12:09:10.025  1037  1543 D wifi    : failed to get capabilities : -3
09-02 12:09:10.025  1037  1543 E WifiScanningService: could not get scan capabilities
09-02 12:09:10.025  1037  1379 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 12:09:10.026  1037  1379 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 12:09:10.026   307   895 D CommandListener: Setting iface cfg
09-02 12:09:10.026   307   895 D CommandListener: Trying to bring up p2p0
09-02 12:09:10.026  1037  1379 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 12:09:10.026  1037  1377 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:09:10.026  1037  1377 D LGWifiP2pService: P2pEnablingState
09-02 12:09:10.026  1037  1377 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.026  1037  1377 D LGWifiP2pService: P2p socket connection successful
09-02 12:09:10.026  1037  1377 D LGWifiP2pService: P2pEnabledState
09-02 12:09:10.026  1037  1379 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 12:09:10.026  1037  1379 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 12:09:10.027  7312  7312 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 12:09:10.027  1037  1379 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 12:09:10.027  1037  1379 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 12:09:10.028  1037  1379 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 12:09:10.028  1037  1379 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 12:09:10.028  7312  7312 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 12:09:10.029  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 12:09:10.030  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 12:09:10.030  1928  1928 D WfdsService: WifiP2pState is changed : true
09-02 12:09:10.030  1928  2282 D WfdsService: Receive the WFDS_ENABLE Method
09-02 12:09:10.030  1928  2282 D WfdsService: Set the WFDS Monitor: true
09-02 12:09:10.030  1928  2282 D WfdsService: Connected to the supplicant for wfds
09-02 12:09:10.030  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:09:10.030  1928  2282 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 12:09:10.030  7312  7312 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 12:09:10.030  1928  2282 D WfdsService: selectPreferredScanChannel [36]
09-02 12:09:10.030  1928  2282 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 12:09:10.030  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 12:09:10.030  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 12:09:10.030  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 12:09:10.030  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:09:10.030  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:09:10.031  1037  1379 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 12:09:10.031  1037  1379 E, WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 12:09:10.032  1037  1379 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 12:09:10.032  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 12:09:10.032  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 12:09:10.033  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.033  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:09:10.033  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.033  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.033  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.033  7312  7312 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:09:10.034  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.034  1928  7341 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.034  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.034  1037  7340 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.034  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.034  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.034  1037  1377 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 12:09:10.034  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.034  1928  7341 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.034  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.034  1037  1377 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 12:09:10.035  1037  7340 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.035  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.035  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.035  1037  1379 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 12:09:10.035  1037  1379 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:09:10.036  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 12:09:10.036  1037  1379 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:09:10.036  1928  1928 D WfdsService: isConnected: false
09-02 12:09:10.036  1037  1379 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:09:10.036  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 12:09:10.036  1037  1377 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,09-02 12:09:10.036  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 12:09:10.036  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:10.037  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 12:09:10.037  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:10.037  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:10.037  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:10.037  1037  1377 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 12:09:10.038  1037  1379 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 12:09:10.038  1037  1379 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-02 12:09:10.038  1037  1379 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 12:09:10.039  1037  1379 D WifiNative-wlan0: doBoolean: SCAN
09-02 12:09:10.039  1037  1377 D WifiNative-p2p0: SET device_name G3: returned true
09-02 12:09:10.039  1037  1377 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 12:09:10.039  1037  1377 D LGWifiP2pService: before postfix = G3
09-02 12:09:10.039  1037  1377 D WifiServerServiceExt: postfix byte check : 2
09-02 12:09:10.039  1037  1377 D LGWifiP2pService: after postfix = G3
09-02 12:09:10.039  1037  1377 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3,
,09-02 12:09:10.039  1037  1379 D WifiNative-wlan0: SCAN: returned false,
09-02 12:09:10.040  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=191329  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
09-02 12:09:10.040  1037  1377 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 12:09:10.040  1037  1377 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 12:09:10.041  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=191330  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,09-02 12:09:10.041  1037  1377 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 12:09:10.041  1037  1377 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 12:09:10.041  1037  1377 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 12:09:10.041  1037  1377 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 12:09:10.041  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=191330  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:09:10.041  1037  1377 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true,
09-02 12:09:10.041  1037  1377 D WifiNative-HAL: p2pGetDeviceAddress
09-02 12:09:10.042  1037  1377 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-02 12:09:10.043  7322  7322 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:10.044  7322  7322 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:09:10.045  7322  7322 D PhoneMonitor: Register our PhoneStateListener
09-02 12:09:10.050  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:10.050  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:10.051  1037  1037 D WifiHS20: hidePasspointNotification off =false
,09-02 12:09:10.051  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.051  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.051  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:10.051  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:10.051  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.051  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.052  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:09:10.052  1037  1377 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-02 12:09:10.052  1037  1377 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 12:09:10.052  1037  1377 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 12:09:10.052  1037  1377 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 12:09:10.052  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:10.052  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=191341  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:09:10.052  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:10.053  1037  1377 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 12:09:10.053  1037  1377 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 12:09:10.053  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:10.053  1037  1377 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 12:09:10.053  1037  1379 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:10.053  1037  1377 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 12:09:10.054  1037  1379 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:10.054  1037  1379 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:10.055  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 12:09:10.055  1037  1379 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:10.055  1037  1379 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:10.055  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 12:09:10.055  1928  1928 D WfdsService: Update P2p Interface State: 3
09-02 12:09:10.057  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:10.057  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 12:09:10.057  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:10.057  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 12:09:10.060  7322  7322 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:09:10.061  7322  7322 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:09:10.062  1037  1377 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 12:09:10.062  1037  1377 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-02 12:09:10.068  7322  7322 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-02 12:09:10.069  7322  7322 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-02 12:09:10.069  7322  7322 D TelephonyAutoProfiling: [parse] Load xml
09-02 12:09:10.072  7322  7322 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-02 12:09:10.072  7322  7322 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-02 12:09:10.072  7322  7322 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-02 12:09:10.075  7322  7322 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-02 12:09:10.108  1037  1060 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7345 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:09:10.110  1037  1060 I ActivityManager: Killing 6826:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-02 12:09:10.169  1037  1377 D LGWifiP2pService: InactiveState
09-02 12:09:10.169  1037  1377 D LGWifiP2pService: InactiveState{ when=-134ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.169  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-134ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:09:10.169  1037  1908 W libprocessgroup: failed to open /acct/uid_10097/pid_6826/cgroup.procs: No such file or directory
09-02 12:09:10.169  1037  1377 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 12:09:10.171  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 12:09:10.172  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.173  7312  7312 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:09:10.173  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.174  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-02 12:09:10.176  1928  7341 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:09:10.176  1928  7341 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.176  1928  7341 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.177  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:09:10.177  1037  7340 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.177  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.177  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:10.177  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.177  1037  7340 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.178  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.178  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.178  1037  1377 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 12:09:10.178  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:10.178  1037  7340 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.178  1037  1377 D LGWifiP2pService: InactiveState{ when=-125ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.178  1037  7340 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.178  1037  7340 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:10.178  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-125ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.178  1037  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.178  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.178  1037  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.179  1037  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.179  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.179  1037  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.182  1037  1377 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.183  1928  2282 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 12:09:10.183  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.183  1037  1377 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.183  1037  1377 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.183  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.184  1037  1377 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.andr,oid.internal.util.StateMachine$SmHandler }
09-02 12:09:10.184  1037  1037 E WifiServerServiceExt: No p2p device connected
09-02 12:09:10.373  1037  1908 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7366 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-02 12:09:10.374  1037  1908 I ActivityManager: Killing 6858:com.lge.eula/1000 (adj 15): empty #17
,09-02 12:09:10.428  1037  1999 W libprocessgroup: failed to open /acct/uid_1000/pid_6858/cgroup.procs: No such file or directory
,09-02 12:09:10.504  1037  1687 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7383 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:09:10.505  1037  1687 I ActivityManager: Killing 5700:com.lge.bnr/1000 (adj 15): empty #17
,09-02 12:09:10.522  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 12:09:10.522  1037  7340 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 12:09:10.522  7312  7312 E wpa_supplicant: USIM:  scard_init function
09-02 12:09:10.522  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 12:09:10.522  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-02 12:09:10.522  1037  7340 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 12:09:10.522  1037  1379 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,09-02 12:09:10.523  7312  7312 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-02 12:09:10.523  1037  1379 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 12:09:10.523  1037  1379 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 12:09:10.524  1037  1379 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 12:09:10.524  1037  1379 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 12:09:10.525  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:09:10.525  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 12:09:10.570  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=191859  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 12:09:10.570  1037  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_5700/cgroup.procs: No such file or directory
,09-02 12:09:10.575  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=191864  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 12:09:10.576  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:10.576  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:10.576  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.577  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.577  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:09:10.583  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:10.587  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-02 12:09:10.588  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 12:09:10.616  7383  7383 I art     : Almond Protected OAT
,09-02 12:09:10.805  1037  1060 I art     : Explicit concurrent mark sweep GC freed 79589(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.848ms total 135.610ms
,09-02 12:09:10.807  7383  7383 D WeatherApplication: removeAccount
09-02 12:09:10.808  7383  7383 D WeatherApplication: Account.length = 0
09-02 12:09:10.808  7383  7383 E WeatherApplication: OPERATOR:OPEN
09-02 12:09:10.811  7383  7383 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:10
09-02 12:09:10.814  7383  7383 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:09:10.814  7383  7383 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:09:10.815  7383  7383 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:09:10.817  7383  7383 D WeatherAncestor: connectivity changed - connection : true
09-02 12:09:10.818  7383  7383 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-02 12:09:10.824  7383  7383 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:09:10.824  7383  7383 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-02 12:09:10.824  7383  7383 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-02 12:09:10.847  1037  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.847  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:10.847  1037  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:09:10.851  7383  7383 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:09:10.851  7383  7383 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:10
09-02 12:09:10.867  1037  1379 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:09:10.868  1037  1379 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:09:10.868  1037  1379 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:09:10.869  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 12:09:10.869  1037  1379 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-02 12:09:10.886  1037  1919 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7401 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:09:10.888  1037  1919 I ActivityManager: Killing 2119:com.lge.music/u0a34 (adj 15): empty #17
09-02 12:09:10.908   311   311 V AudioFlinger: 2119 died, releasing its sessions
09-02 12:09:10.908   311   311 V AudioFlinger:  pid 1839 @ 0
,09-02 12:09:10.908   311   311 V AudioFlinger:  pid 3310 @ 1
09-02 12:09:10.908   311   311 V AudioFlinger:  pid 3310 @ 2
09-02 12:09:10.933  7312  7312 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:09:10.934  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 12:09:10.935  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 12:09:10.935  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 12:09:10.935  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 12:09:10.935  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:10.935  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:10.935  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=192224  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:09:10.936  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=192225  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:09:10.936  1037  1379 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192225
09-02 12:09:10.936  1037  1379 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192226
09-02 12:09:10.937  1037  1379 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192226
09-02 12:09:10.937  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192226
09-02 12:09:10.937  1037  1379 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192226
09-02 12:09:10.938  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=192227  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:09:10.946  7312  7312 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:09:10.946  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:09:10.947  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:10.947  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:10.948  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 12:09:10.948  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:09:10.948  1037  7340 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:09:10.948  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 12:09:10.948  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-02 12:09:10.948  1037  7340 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-02 12:09:10.948  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:10.948  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:10.969  1037  1873 W libprocessgroup: failed to open /acct/uid_10034/pid_2119/cgroup.procs: No such file or directory
,09-02 12:09:10.978  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:09:10.981  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:10.981  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:09:10.981  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.981  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.981  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:09:10.983  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:10.985  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=192274  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:09:10.987  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.987  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:10.987  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 12:09:10.988  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:10.988  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 12:09:10.989  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=192278  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:09:10.990  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=192279  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:09:10.990  1037  1379 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=192279
09-02 12:09:10.991  1037  1379 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=192280
09-02 12:09:10.991  1037  1379 D WifiNative-wlan0: doString: [STATUS]
09-02 12:09:10.992  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:10.992  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:10.998  1037  1379 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:09:11.000  1037  1379 I WifiServiceExtension: setVHTCapabilityType  : false
,09-02 12:09:11.008  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.008  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:11.009  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.009  1037  1379 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 12:09:11.009  1037  1379 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-02 12:09:11.017  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.017  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.017  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:09:11.021  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.021  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.021  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:09:11.023  1037  1379 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 12:09:11.023  1037  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:09:11.023  1037  1455 D ConnectivityService: Got NetworkAgent Messenger
09-02 12:09:11.023  1037  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:09:11.023  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 12:09:11.023  1037  1455 D ConnectivityService: NetworkAgent connected
09-02 12:09:11.023  1037  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:09:11.023  1037  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:09:11.029  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.029  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:09:11.031  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.032  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.032  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:11.034  1037  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:09:11.034  1037  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:09:11.034  1037  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:09:11.034  1037  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:09:11.034  1037  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:09:11.035  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.042  1037  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:09:11.043   307   895 D CommandListener: Setting iface cfg
09-02 12:09:11.047  1037  1379 E WifiStateMachine: Start Dhcp Watchdog 2
09-02 12:09:11.047  1037  7423 D DhcpStateMachine: StoppedState
09-02 12:09:11.047  1037  7423 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.047  1037  7423 D DhcpStateMachine: WaitBeforeStartState
09-02 12:09:11.048  1037  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-02 12:09:11.049  1037  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192338  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:11.049  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192338  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:11.050  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:11.050  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:11.051  1037  1379 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:11.051  1037  1379 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:11.051  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:11.052  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:11.053  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:11.053  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-02 12:09:11.054  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:11.054  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 12:09:11.055  1037  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=192344  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:11.056  1037  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=192345  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:11.056  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=192345  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:11.057  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:145831] from screen [on:0 period:-362831471] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:09:11.059  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-362831470] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:09:11.059  1037  1379 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-02 12:09:11.062  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.063  1037  1455 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-02 12:09:11.064  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.064  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.065  1037  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.065  1037  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.066  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.066  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.066  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 12:09:11.067  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=138,0,0
09-02 12:09:11.067  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=138,0,0
09-02 12:09:11.067  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 12:09:11.068  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 12:09:11.068  1037  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 12:09:11.068  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 12:09:11.068  1037  1379 D WifiNative-wlan0: SET ps 0: returned true
09-02 12:09:11.068  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 12:09:11.069  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 12:09:11.069  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 12:09:11.069  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b9e8f7c target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.069  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b9e8f7c target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.069  1037  7423 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.069  1037  7423 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-02 12:09:11.070  1037  1379 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 12:09:11.070  1037  1379 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:09:11.070  1037  1379 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:09:11.071   307   895 D CommandListener: Setting iface cfg
,09-02 12:09:11.071   307   895 D CommandListener: Trying to bring up wlan0
09-02 12:09:11.072  1037  1379 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 12:09:11.073  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:11.073  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:09:11.074  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:11.074  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:09:11.075  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.075  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.076  1037  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.076  1037  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.077  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.077  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:11.077  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 12:09:11.078  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 12:09:11.078  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 12:09:11.078  1037  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.078  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.078  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:09:11.079  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:09:11.079  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:09:11.079  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 12:09:11.079  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 12:09:11.079  1037  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 12:09:11.080  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:11.086   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:09:11.086   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 12:09:11.086   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:09:11.087  7401  7426 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-02 12:09:11.091   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:09:11.091   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 12:09:11.091   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:09:11.092  7401  7426 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 12:09:11.096  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:11.096  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 12:09:11.097  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:09:11.097  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:09:11.097  1037  1379 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 12:09:11.097   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:09:11.097   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 12:09:11.097   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:09:11.098  1037  1455 D ConnectivityService: ignoring duplicate network state non-change
09-02 12:09:11.098  7401  7430 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-02 12:09:11.100   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 12:09:11.100   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 12:09:11.100   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:09:11.100  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.100  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:11.100  7401  7430 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 12:09:11.101  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.101  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.101  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-02 12:09:11.102  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:11.104  1037  1379 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 12:09:11.105  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 12:09:11.107  1037  1455 D ConnectivityService: Adding iface wlan0 to network 101
09-02 12:09:11.109  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.109  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.109  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:09:11.111  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:09:11.114  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-02 12:09:11.118  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.118  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.118  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:09:11.118  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:09:11.124  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.124  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:11.126  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.126  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.126  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:09:11.126  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:11.130  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.132  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:09:11.132  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.132  1037  1455 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 12:09:11.133  1037  1455 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 12:09:11.136  1037  1455 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-02 12:09:11.136   307   895 E Netd    : netlink response contains error (File exists)
09-02 12:09:11.137  1037  1455 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-02 12:09:11.138  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:11.138  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:09:11.138  1037  1455 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 12:09:11.138  1037  1455 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-02 12:09:11.138  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.138  1037  1455 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-02 12:09:11.142  1037  1455 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 12:09:11.143  1037  1455 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 12:09:11.143  1037  1455 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 12:09:11.143  1037  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 12:09:11.143  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.143  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 12:09:11.143  1037  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:09:11.143  1037  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:11.144  1037  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 12:09:11.144  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.144  1037  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:11.144  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 12:09:11.144  1037  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 12:09:11.144  1037  1455 D ConnectivityService: currentScore = 0, newScore = 20
09-02 12:09:11.144  1037  1455 D ConnectivityService:    accepting network in place of null
09-02 12:09:11.144  1037  1455 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:11.144  1037  1379 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:11.145  1037  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:09:11.145  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:11.145  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:09:11.146  1037  1455 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 12:09:11.147  1037  1455 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 12:09:11.147  1037  1455 D ConnectivityService: sendStickyBroadcast: ,action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:09:11.147  1037  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.147  1037  1455 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 12:09:11.148   307  7436 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 12:09:11.148  1037  1455 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 12:09:11.149  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 12:09:11.151  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:09:11.151  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:09:11.151  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:09:11.152  1037  1455 D ConnectivityService: validation of new default Network = false
09-02 12:09:11.152  1037  1455 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 12:09:11.152  1037  1455 D DSQN    : enableDataServiceNotify 
09-02 12:09:11.152  1037  1455 D DSQN    : start dsqn bin
,09-02 12:09:11.162  1037  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 12:09:11.162  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:11.162  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:11.162  1037  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:11.163  1590  2037 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 12:09:11.149  7437  7437 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:09:11.149  7437  7437 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:11.176  7437  7437 E DSQN    : DSQN ssw
09-02 12:09:11.180  1037  1375 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 12:09:11.181  1804  7438 I CheckinService: active receiver: enabled
,09-02 12:09:11.195  1804  7438 I CheckinService: Preparing to send checkin request
09-02 12:09:11.195  1804  7438 I EventLogService: Accumulating logs since 1472810804602
09-02 12:09:11.203  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:09:11.204  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.204  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:11.243  1804  7438 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-02 12:09:11.271  1037  7423 D DhcpStateMachine: DHCPV4 request on wlan0
,09-02 12:09:11.272  1037  7423 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 12:09:11.272  1037  7423 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 12:09:11.259  7456  7456 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:11.259  7456  7456 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:11.283  7456  7456 I dhcpcd  : version 5.5.6 starting
09-02 12:09:11.286  7456  7456 E dhcpcd  : get_duid: m
09-02 12:09:11.286  7456  7456 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 12:09:11.286  7456  7456 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-02 12:09:11.325  7401  7401 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 12:09:11.343  7456  7456 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:09:11.344  7456  7456 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-02 12:09:11.344  7456  7456 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:09:11.344  7456  7456 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 12:09:11.344  7456  7456 D dhcpcd  : wlan0: sending REQUEST (xid 0x4b765134), next in 4.76 seconds
09-02 12:09:11.360  1037  1999 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7463 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-02 12:09:11.368  7401  7401 I LibraryLoader: Loading: webviewchromium
09-02 12:09:11.372  7401  7401 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2669-2674)
,09-02 12:09:11.372  7401  7401 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:09:11.373  7456  7456 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-02 12:09:11.381  7401  7401 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ff67e31}
09-02 12:09:11.383  7401  7401 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 12:09:11.384  7401  7401 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:09:11.407  7456  7456 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 12:09:11.407  7456  7456 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 12:09:11.408  7456  7456 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 12:09:11.408  7456  7456 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 12:09:11.408  7456  7456 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:09:11.408  7401  7401 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 12:09:11.409  7456  7456 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:09:11.409  7456  7456 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 12:09:11.409  7456  7456 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 12:09:11.418  7401  7401 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:09:11.426  7463  7463 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-02 12:09:11.426  7463  7463 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-02 12:09:11.435  7401  7401 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-02 12:09:11.435  7401  7401 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,09-02 12:09:11.436  7401  7401 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-02 12:09:11.442   311  1384 V AudioPolicyService: registerClient() client 0xb558a400, uid 10093
09-02 12:09:11.445  7401  7487 W AudioManagerAndroid: Requires BLUETOOTH permission
09-02 12:09:11.458  7401  7401 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:09:11.458  7401  7401 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:09:11.458  7401  7401 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:09:11.458  7401  7401 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:09:11.458  7401  7401 I Adreno-EGL: Remote Branch: 
09-02 12:09:11.458  7401  7401 I Adreno-EGL: Local Patches: 
09-02 12:09:11.458  7401  7401 I Adreno-EGL: Reconstruct Branch: 
09-02 12:09:11.460  7463  7463 I MultiDex: VM with version 2.1.0 has multidex support
09-02 12:09:11.460  7463  7463 I MultiDex: install
09-02 12:09:11.461  7463  7463 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-02 12:09:11.476  7463  7463 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-02 12:09:11.512   307  7436 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 12:09:11.537  7401  7401 I NSApplication: Starting up...
,09-02 12:09:11.574  1037  1886 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7516 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-02 12:09:11.575  1037  1886 I ActivityManager: Killing 6157:com.android.vending/u0a44 (adj 15): empty #17
09-02 12:09:11.591   331   331 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 14.702ms
,09-02 12:09:11.603   331   331 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 11.848ms
09-02 12:09:11.614   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.206ms
,09-02 12:09:11.649  1037  1687 W libprocessgroup: failed to open /acct/uid_10044/pid_6157/cgroup.procs: No such file or directory
,09-02 12:09:11.675  1037  7423 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-02 12:09:11.676  1037  7423 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 12:09:11.676  1037  7423 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:09:11.677  1037  7423 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,09-02 12:09:11.677  1037  7423 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 12:09:11.677  1037  7423 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:09:11.677  1037  7423 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 12:09:11.677  1037  7423 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 12:09:11.677  1037  7423 D DhcpStateMachine: RunningState
,09-02 12:09:11.684  7516  7516 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:11.778  7463  7478 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:11.778  7463  7478 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:11.902  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 12:09:11.907  6570  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:09:11.925  7543  7543 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-02 12:09:11.925  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.936   307  7548 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-02 12:09:11.936  1037  1999 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-02 12:09:11.936   307  7548 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-02 12:09:11.937  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:09:11.937  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.937  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:09:11.937  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-02 12:09:11.939  7259  7259 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:09:11.945  1037  1999 D WifiServiceImplEx: setWifiEnabled: false pid=6984, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:09:11.945  1037  1999 D WifiService: setWifiEnabled: false pid=6984, uid=10118
09-02 12:09:11.945  1037  1999 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:09:11.946  7259  7259 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13cb978e
09-02 12:09:11.946  7259  7259 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:09:11.946  7259  7259 D AppUp4:CustFacade: isPhone : true
09-02 12:09:11.947  7259  7259 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:09:11.952  7259  7259 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:09:11.953  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.954  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-02 12:09:11.954  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:11.956  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:11.959  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:09:11.959  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:11.959  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:11.960  1037  1379 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:11.960  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:11.960  1037  1379 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0,
09-02 12:09:11.960  1037  1379 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:11.961  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 12:09:11.961  4801  7553 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:09:11.961  1037  1379 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 12:09:11.961  1037  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:09:11.961  1037  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:09:11.961  1037  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:09:11.961  1037  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:09:11.962  3432  3432 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.963  3432  3432 V DownloadManager: DownloadService onCreate
09-02 12:09:11.964  4801  7554 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.964  4801  7554 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 12:09:11.964  3432  7557 I DownloadManager: in removeSpuriousFiles
09-02 12:09:11.965  4801  7553 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-02 12:09:11.965  3432  7557 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-02 12:09:11.966  3432  7557 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@33bf4652 on behalf of 3432
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-02 12:09:11.966  7284  7284 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-02 12:09:11.966  3432  7557 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-02 12:09:11.967  3432  7557 I DownloadManager: in trimDatabase
09-02 12:09:11.967  3432  7557 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,09-02 12:09:11.968  3432  7557 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@54a1d23 on behalf of 3432
09-02 12:09:11.969  7543  7543 I dex2oat : dex2oat took 44.052ms (threads: 4)
09-02 12:09:11.973  1037  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:09:11.973  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:09:11.974  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:09:11.974  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.974  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.975  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:09:11.975  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:11.975  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:11.975   307   895 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:09:11.975  1037  7423 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:11.981  7463  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:09:11.981  7463  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:09:11.981  7463  7478 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:09:11.981  7463  7478 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:09:11.981  7463  7478 I Adreno-EGL: Remote Branch: 
09-02 12:09:11.981  7463  7478 I Adreno-EGL: Local Patches: 
09-02 12:09:11.981  7463  7478 I Adreno-EGL: Reconstruct Branch: 
09-02 12:09:11.985  3432  3432 V DownloadManager: DownloadService onStartCommand
,09-02 12:09:11.990  3310  3310 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:09:11.990  3310  3310 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:11.990  3310  3310 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:09:11.990  7284  7562 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:11.991  4801  7553 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-02 12:09:11.992  7322  7322 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:09:11.992  7322  7322 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:09:11.993  3432  7558 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-02 12:09:11.995  4801  4801 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-02 12:09:11.995  4801  4801 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-02 12:09:11.995  4801  4801 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-02 12:09:11.996  3432  7558 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@be7759e on behalf of 3432
09-02 12:09:11.997  4801  4801 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-02 12:09:11.998  3432  7558 V DownloadManager: processing inserted download 1
,09-02 12:09:11.999  3432  7558 V DownloadManager: processing inserted download 4
09-02 12:09:12.000  3432  7558 V DownloadManager: processing inserted download 7
09-02 12:09:12.000  3432  7558 V DownloadManager: processing inserted download 8
09-02 12:09:12.000  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 12:09:12.000  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-02 12:09:12.001  3432  7558 V DownloadManager: processing inserted download 9
09-02 12:09:12.001  3432  7558 V DownloadManager: processing inserted download 10
09-02 12:09:12.002  3432  7558 V DownloadManager: processing inserted download 11
09-02 12:09:12.003  3432  7558 V DownloadManager: processing inserted download 12
09-02 12:09:12.003  3432  7558 V DownloadManager: processing inserted download 13
09-02 12:09:12.004  3432  7558 V DownloadManager: processing inserted download 14
09-02 12:09:12.004  3432  7558 V DownloadManager: processing inserted download 16
09-02 12:09:12.005  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 12:09:12.005  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:12.006  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:12.006  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:12.007  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:12.007  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:12.007  1037  1379 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:09:12.008  1037  1377 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.009  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.009  1037  1377 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@33c16edc
09-02 12:09:12.009  1037  1377 D LGWifiP2pService: P2pDisablingState
09-02 12:09:12.009  1037  1377 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.009  1037  1377 D LGWifiP2pService: p2p socket connection lost
09-02 12:09:12.009  1037  1377 D LGWifiP2pService: P2pDisabledState
09-02 12:09:12.014  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-02 12:09:12.014  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.015  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.015  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:12.015  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-02 12:09:12.016  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:12.016  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:09:12.017  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.020  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 12:09:12.022  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.022  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.022  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:12.022  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 12:09:12.023  1037  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.023  1037  1037 D RttService: SCAN_AVAILABLE : 1
09-02 12:09:12.023  1037  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.024  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:09:12.024  1928  1928 D WfdsService: WifiP2pState is changed : false
09-02 12:09:12.024  1928  2282 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 12:09:12.024  1928  2282 D WfdsService: Set the WFDS Monitor: false
09-02 12:09:12.025  1928  2282 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:09:12.025  1928  7341 D CtrlSupplicant: Received on exit socket, terminate
09-02 12:09:12.025  1928  2282 D WfdsService: STATE : WfdsDisabledState - enter
09-02 12:09:12.025  1928  7341 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 12:09:12.025  1928  7341 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 12:09:12.025  1928  7341 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 12:09:12.025  1928  2284 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 12:09:12.025  1037  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 12:09:12.026  1928  2282 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 12:09:12.026  1037  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.026  1037  1377 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:12.026  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:09:12.026  7312  7312 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:09:12.026  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:09:12.026  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:12.027  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
,09-02 12:09:12.034  7383  7383 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:12
09-02 12:09:12.036  4801  4801 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-02 12:09:12.036  3432  3432 V DownloadManager: DownloadService onDestroy
09-02 12:09:12.036   307   895 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:09:12.037  1037  1455 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 12:09:12.037  1037  1455 D DSQN    : disableDataServiceNotify
09-02 12:09:12.037  1037  1455 D DSQN    : stop dsqn bin
09-02 12:09:12.038  7383  7383 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:09:12.038  7383  7383 D Weather.Utils: 2 : All the weather widget is gone.
,09-02 12:09:12.039  7383  7383 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:09:12.039  7383  7383 D WeatherAncestor: connectivity changed - connection : true
,09-02 12:09:12.039  7383  7383 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f64abbc
09-02 12:09:12.040  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:12.040  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:12.040  7181  7563 W FormManager: Network not available. Please check & try again.
09-02 12:09:12.040  7383  7383 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:09:12.041  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.041  1037  1379 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 12:09:12.041  1037  1379 D WifiNative-p2p0: TERMINATE: returned true
09-02 12:09:12.041  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:12.041  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:12.041  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:12.041  1037  1037 D WifiHS20: hidePasspointNotification off =false
09-02 12:09:12.042  7383  7383 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:09:12.042  7383  7383 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:09:12.042  7383  7383 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:09:12.042  7383  7383 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:12
09-02 12:09:12.043  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.043  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.043  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:12.045  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 12:09:12.046  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 12:09:12.047  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:12.047  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 12:09:12.047  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:12.047  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:12.047  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:12.047  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
0,9-02 12:09:12.049  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:12.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:12.049  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:12.049  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:12.049  7181  7564 V FormManager: Network unavailable.
,09-02 12:09:12.053  1037  1455 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-02 12:09:12.053  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:12.053  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:12.053  7181  7564 V FormManager: Network unavailable.
09-02 12:09:12.053  1037  1455 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:12.056  1037  1455 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 12:09:12.056  1590  2037 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 12:09:12.056  1037  1455 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 12:09:12.056  1037  1455 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-02 12:09:12.057  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:09:12.057  1037  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:12.057  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:09:12.058  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:09:12.058  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 12:09:12.058  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:09:12.058  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:09:12.058  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:09:12.059  1037  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:12.059  1037  1455 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:12.059  1037  1455 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:12.060  1037  1455 D NetworkManagementService: Removing idletimer
09-02 12:09:12.060  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 12:09:12.060  1037  1455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.060  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:12.060  1037  1455 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 12:09:12.060  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 12:09:12.060  1037  1379 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:12.060  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:12.060  1037  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:09:12.060  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 12:09:12.060  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:09:12.061  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:09:12.061  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:09:12.061  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-02 12:09:12.062  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.066  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.072  7463  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:09:12.072  7463  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:09:12.072  7463  7478 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:09:12.072  7463  7478 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:09:12.072  7463  7478 I Adreno-EGL: Remote Branch: 
09-02 12:09:12.072  7463  7478 I Adreno-EGL: Local Patches: 
09-02 12:09:12.072  7463  7478 I Adreno-EGL: Reconstruct Branch: 
,09-02 12:09:12.082  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:09:12.083  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:09:12.083  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:09:12.083  7112  7112 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-02 12:09:12.085  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:09:12.086  7112  7112 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:09:12.086  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 12:09:12.086  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:09:12.087  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:09:12.087  7112  7112 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:09:12.087  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 12:09:12.087  7112  7112 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:09:12.091  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:09:12.092  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.092  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.095  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:09:12.099  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:09:12.108  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 12:09:12.108  7312  7312 I wpa_supplicant: monitor socket send errors count : 1
09-02 12:09:12.108  7312  7312 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
,09-02 12:09:12.109  1037  7340 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 12:09:12.109  1037  7340 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 12:09:12.110  7181  7576 W FormManager: Network not available. Please check & try again.
09-02 12:09:12.111  7181  7577 V FormManager: Network unavailable.
09-02 12:09:12.114  7181  7577 V FormManager: Network unavailable.
,09-02 12:09:12.121  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:09:12.121  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.122  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.122  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.134  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:09:12.136  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:09:12.137  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:09:12.138  7312  7312 W wpa_supplicant: USIM:  scard_deinit function
09-02 12:09:12.138  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 12:09:12.138  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:09:12.138  1037  7340 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:09:12.138  1037  7340 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 12:09:12.138  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:12.138  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:12.139  1037  1119 D Tethering: InitialState.processMessage what=4
09-02 12:09:12.139  1037  1379 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193428
,09-02 12:09:12.139  1037  1379 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193428
09-02 12:09:12.139  1037  1379 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=193428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:09:12.139  1037  1379 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=193429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 12:09:12.140  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:09:12.140  1037  1379 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:12.140  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:12.142  7181  7580 V FormManager: Network unavailable.
09-02 12:09:12.144  7181  7579 W FormManager: Network not available. Please check & try again.
09-02 12:09:12.144  7181  7580 V FormManager: Network unavailable.
09-02 12:09:12.145  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.155  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:12.155  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:09:12.156  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:12.158  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:09:12.161  4801  7583 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:09:12.163  1037  1455 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-02 12:09:12.164  4801  7584 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:12.164  4801  7584 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:12.179  1037  7423 D DhcpStateMachine: StoppedState
09-02 12:09:12.179  1037  7423 D DhcpStateMachine: StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:09:12.183  1037  1059 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7585 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-02 12:09:12.185  1037  1379 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 12:09:12.185  1037  1379 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-02 12:09:12.238  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 12:09:12.240  1037  7340 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 12:09:12.240  1037  7340 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 12:09:12.240  1037  7340 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 12:09:12.240  1037  1379 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,09-02 12:09:12.245  7585  7585 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 12:09:12.245  7585  7585 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-02 12:09:12.250  7585  7585 V [BNRBootReceiver]: Boot Receiver Return
09-02 12:09:12.250  7585  7585 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 12:09:12.252  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:12.256  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:09:12.256  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:12.256  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:12.258  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:12.262  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.269  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.269  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.270  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:09:12.273  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.277  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:12.282  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:12.288  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.288  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.289  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:09:12.290  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-02 12:09:12.293  7112  7112 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 12:09:12.295  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.303  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.307  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.313  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.313  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.314  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:12.317  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.324  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.328  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.334  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.334  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.334  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:09:12.339  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.345  1037  1379 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 12:09:12.345  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:12.345  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:12.345  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:12.345  1928  1928 D WfdsService: Supplicant Connection state is changed : false
09-02 12:09:12.345  1928  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 12:09:12.345  1928  2282 D WfdsService: Set the WFDS Monitor: false
09-02 12:09:12.345  1928  2282 D WfdsMonitor: WFDS Monitor is stopped
09-02 12:09:12.347  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:12.347  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 12:09:12.350  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:12.350  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:09:12.352  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:12.352  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:12.352  2495  2495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:12.354  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:12.358  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 12:09:12.358  1037  1429 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 12:09:12.358  1037  1429 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 12:09:12.361  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:12.369  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.369  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.369  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:12.374  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:12.381  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.388  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.393  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.394  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.395  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:12.400  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:12.407  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.412  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.418  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.418  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.419  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:12.426  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:12.438  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.445  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.446  7463  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 12:09:12.446  7463  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 12:09:12.446  7463  7478 I Adreno-EGL: Build Date: 12/12/14 금
09-02 12:09:12.446  7463  7478 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 12:09:12.446  7463  7478 I Adreno-EGL: Remote Branch: 
09-02 12:09:12.446  7463  7478 I Adreno-EGL: Local Patches: 
09-02 12:09:12.446  7463  7478 I Adreno-EGL: Reconstruct Branch: 
09-02 12:09:12.453  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.454  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:09:12.460  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:09:12.465  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.481  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.487  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.494  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.495  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.495  5814  5814 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:09:12.500  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.505  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 12:09:12.514  1037  1437 D WifiService: New client listening to asynchronous messages
,09-02 12:09:12.514  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:09:12.520  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.532  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.539  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.540  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.541  5814  5814 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 12:09:12.543  5814  5814 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:09:12.544  5814  5814 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-02 12:09:12.552  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.560  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 12:09:12.564  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:12.572  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.588  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.599  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.599  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:09:12.600   307  7605 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 12:09:12.600  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 12:09:12.601  5814  5814 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 12:09:12.602  1804  7438 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-02 12:09:12.602  5814  5814 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:09:12.603  5814  5814 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:09:12.607  1037  1908 I ActivityManager: Killing 7087:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-02 12:09:12.640  1804  7438 I CheckinService: active receiver: disabled
,09-02 12:09:12.643  1037  2019 W libprocessgroup: failed to open /acct/uid_10037/pid_7087/cgroup.procs: No such file or directory
,09-02 12:09:12.667  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-02 12:09:12.684  2214  2214 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-02 12:09:12.685  2214  2214 D c       : Getting all permits...
09-02 12:09:12.685  2214  2214 D a       : Opening database...
09-02 12:09:12.692  2214  2214 D a       : Opening database auth.proximity.permit_store...
09-02 12:09:12.693  2214  2214 D a       : Closing database...
09-02 12:09:12.708  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:12.712  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 12:09:12.712  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:12.712  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:09:12.716  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.724  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:12.737  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.738  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.740  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:09:12.746  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.753  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:09:12.753  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:12.753  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:12.763  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.772  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:12.782  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:12.783  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:09:12.786  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:09:12.792  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:12.797  7134  7134 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 12:09:12.797  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:12.797  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:12.803  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:12.811  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.822  5814  5814 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:09:12.822  5814  5814 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:12.825  5814  5814 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:09:12.841  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:12.846  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:09:12.852  7181  7609 W FormManager: Network not available. Please check & try again.
09-02 12:09:12.861  7181  7610 V FormManager: Network unavailable.
,09-02 12:09:12.867  7181  7610 V FormManager: Network unavailable.
09-02 12:09:12.868  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:12.898  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:09:12.898  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:09:12.898  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:09:12.898  7112  7112 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:09:12.899  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-02 12:09:12.900  7112  7112 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:09:12.900  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-02 12:09:12.900  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:09:12.900  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:09:12.900  7112  7112 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:09:12.900  7112  7112 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:09:12.911  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:12.912  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-02 12:09:12.916  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:12.924  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:12.932  4801  7614 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:09:12.939  4801  7615 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:12.940  4801  7615 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:12.940  7134  7134 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 12:09:12.941  7134  7134 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 12:09:12.941  7134  7134 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:12.946  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:09:12.956  7181  7617 W FormManager: Network not available. Please check & try again.
09-02 12:09:12.959  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:12.961  7181  7618 V FormManager: Network unavailable.
09-02 12:09:12.970  7181  7618 V FormManager: Network unavailable.
,09-02 12:09:12.982  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-02 12:09:14.068  1037  1379 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-362828461] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:09:14.070  1037  1379 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-362828458] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-02 12:09:14.150  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:14.162  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 12:09:14.172  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:14.177  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:14.180  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:14.182  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 12:09:14.184  6570  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:09:14.195  5874  5874 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 12:09:14.221  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:14.251  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:09:14.251  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:14.251  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:09:14.252  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-02 12:09:14.259  7259  7259 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:09:14.263  7259  7259 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13cb978e
09-02 12:09:14.263  7259  7259 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:09:14.263  7259  7259 D AppUp4:CustFacade: isPhone : true
09-02 12:09:14.263  7259  7259 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:09:14.263  7259  7259 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:09:14.270  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:14.270  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:09:14.271  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:09:14.279  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:14.291  7284  7284 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 12:09:14.338  3310  3310 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:09:14.338  3310  3310 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:14.338  3310  3310 I LgeMiscReceiver: networkInfo.isConnected() = true
09-02 12:09:14.338  3310  3310 D PhoneState: setPdpRejectCasuse : false
09-02 12:09:14.342  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:14.346  4801  7640 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:09:14.349  7284  7641 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:09:14.349  7322  7322 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:09:14.350  7322  7322 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:09:14.353  4801  7645 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:14.353  4801  7645 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:14.355  7181  7639 W FormManager: Network not available. Please check & try again.
,09-02 12:09:14.356  7181  7642 V FormManager: Network unavailable.
09-02 12:09:14.366  7181  7642 V FormManager: Network unavailable.
,09-02 12:09:14.370  7383  7383 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:14
,09-02 12:09:14.373  7383  7383 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-02 12:09:14.374  7383  7383 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:09:14.374  7383  7383 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:09:14.374  7383  7383 D WeatherAncestor: connectivity changed - connection : true
09-02 12:09:14.374  7383  7383 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f64abbc
09-02 12:09:14.375  7383  7383 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:09:14.375  7383  7383 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:09:14.375  7383  7383 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:09:14.375  7383  7383 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:09:14.375  7383  7383 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:14
,09-02 12:09:14.962  1037  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:14.963  1037  1945 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 12:09:15.000  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:09:15.001  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:15.001  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,09-02 12:09:15.005  1037  1119 D BluetoothManagerService: Message: 1
09-02 12:09:15.006  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 12:09:15.038  1037  1119 D BluetoothManagerService: Message: 20
09-02 12:09:15.038  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f7732d4:true
,09-02 12:09:15.043  7208  7208 D BluetoothAdapterState: make
09-02 12:09:15.048  7208  7208 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 12:09:15.048  7208  7208 I bluedroid-qcom: init
09-02 12:09:15.049  7208  7658 I BluetoothAdapterState: Entering OffState
09-02 12:09:15.049  7208  7208 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 12:09:15.050  7208  7208 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 12:09:15.050  7208  7208 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:09:15.050  7208  7208 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 12:09:15.050  7208  7208 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 12:09:15.052  7208  7208 I bluedroid-qcom: get_profile_interface socket
09-02 12:09:15.052  7208  7208 I bluedroid-qcom: get_profile_interface map_client
,09-02 12:09:15.058  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.049  7661  7661 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:15.049  7661  7661 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:15.068  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:15.071  1037  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 12:09:15.072  7208  7662 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 12:09:15.078  7661  7661 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 12:09:15.078  7661  7661 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 12:09:15.078  7661  7661 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 12:09:15.079  7661  7661 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 12:09:15.080  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:15.082  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:15.087  7661  7661 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 12:09:15.087  7661  7661 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 12:09:15.095  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:09:15.106  7208  7662 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 12:09:15.110  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:15.114  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:15.117  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 12:09:15.117  1037  1119 D BluetoothManagerService: Message: 40
09-02 12:09:15.117  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,09-02 12:09:15.120  7208  7662 D BluetoothAdapterProperties: Name is: G3
,09-02 12:09:15.122  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 12:09:15.125  6570  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:09:15.128  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:09:15.129  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:09:15.132  7208  7223 I bluedroid-qcom: config_hci_snoop_log
09-02 12:09:15.133  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.134  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 12:09:15.134  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-02 12:09:15.145  7208  7658 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 12:09:15.145  7208  7658 D BluetoothAdapterProperties: Setting state to 11
,09-02 12:09:15.145  7208  7658 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 12:09:15.146  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:15.146  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 12:09:15.146  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 12:09:15.147  7208  7658 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 12:09:15.153  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.154  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:15.156  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-02 12:09:15.156  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:15.161  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:15.161  5874  5874 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 12:09:15.162  7208  7658 D BluetoothBondStateMachine: make
,09-02 12:09:15.164  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:15.165  7208  7658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.165  7208  7658 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 12:09:15.165  7208  7658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.165  7208  7658 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 12:09:15.165  7208  7658 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 12:09:15.167  7208  7681 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 12:09:15.167  7208  7208 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:09:15.167  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:15.168  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:15.168  7208  7208 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:15.168  7208  7208 V BluetoothPbapReceiver: ***********state = 11
09-02 12:09:15.173  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:09:15.173  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:09:15.215  1037  1687 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7683 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 12:09:15.220  5874  5874 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 12:09:15.224  7208  7208 D HeadsetService: Received start request. Starting profile...
09-02 12:09:15.225  7208  7208 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:09:15.225  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:15.225  7208  7208 D LGBluetoothHfpAdapter: Version 1.6
,09-02 12:09:15.228  7208  7208 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 12:09:15.229  7208  7208 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:09:15.230  7208  7208 D HeadsetStateMachine: make
09-02 12:09:15.231  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:15.234  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.243  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:09:15.244  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:09:15.244  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.244  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:09:15.244  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:09:15.245  7259  7259 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:09:15.248  7259  7259 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13cb978e
09-02 12:09:15.248  7259  7259 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:09:15.248  7259  7259 D AppUp4:CustFacade: isPhone : true
09-02 12:09:15.249  7259  7259 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:09:15.249  7259  7259 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:09:15.250  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:15.251  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:15.251  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:09:15.254  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:15.254  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:15.256  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 12:09:15.258  7208  7658 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:15.262  7208  7208 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:15.262  7208  7208 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:09:15.264  4801  7701 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 12:09:15.266  7208  7208 D HeadsetStateMachine: max_hf_connections = 1
09-02 12:09:15.266  7208  7208 I bluedroid-qcom: get_profile_interface handsfree
09-02 12:09:15.268  7208  7208 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 12:09:15.268   311   311 V AudioPolicyService: registerClient() client 0xb57f66a0, uid 1002
09-02 12:09:15.268   311  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:09:15.268   311  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:09:15.268   311  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:09:15.269  7208  7208 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:09:15.269   311  1535 V AudioFlinger: registerClient() client 0xb1433148, pid 7208
09-02 12:09:15.269   311  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:15.269  7208  7208 V ToneGenerator: Create Track: 0xb4928080
,09-02 12:09:15.269   311  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:15.269  7208  7208 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 12:09:15.269  7208  7208 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 12:09:15.270  1037  1962 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:15.270  1037  1962 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-02 12:09:15.270  1590  3178 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:15.270  1590  3178 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:15.270  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:15.270  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:15.270   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:09:15.270   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:09:15.270   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:09:15.270   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:09:15.270  3310  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:15.270  3310  3327 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:15.270  7208  7208 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:09:15.270  7208  7224 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:15.270  7208  7224 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 12:09:15.270   311  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:15.270   311  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:15.270   311   311 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 12:09:15.270  1037  1919 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:15.270  1037  1919 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:15.270   311  1535 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:09:15.270   311  1535 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 12:09:15.270   311  1535 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:09:15.270   311  1535 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:09:15.270  7208  7208 V AudioSystem: getLatency() output 2, latency 50
09-02 12:09:15.270  7208  7208 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 12:09:15.270  7208  7208 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 12:09:15.270  1590  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:15.270  1590  2084 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:15.270  7208  7679 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:15.271  7208  7679 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 12:09:15.271  1839  2440 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:15.271  1839  2440 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:15.271  3310  3326 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:15.271  3310  3326 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:15.271   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:09:15.271   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:09:15.271   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:09:15.271   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:09:15.271   311   311 V AudioFlinger: createTrack() lSessionId: 20
09-02 12:09:15.272  7208  7208 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 12:09:15.272   311  1535 V AudioFlinger: acquiring 20 from 7208, for 7208
09-02 12:09:15.272   311  1535 V AudioFlinger:  added new entry for 20
09-02 12:09:15.272  7208  7208 V ToneGenerator: ToneGenera,tor INIT OK, time: 196574
09-02 12:09:15.272  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.273  7208  7698 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 12:09:15.273  4801  7702 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.273  7208  7698 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:09:15.273  4801  7702 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:15.273  7208  7698 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:09:15.273  7208  7698 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 12:09:15.274   311  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7208
09-02 12:09:15.274   311  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 12:09:15.274   311  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 12:09:15.274   311  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 12:09:15.274   311  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 12:09:15.274   311  1384 V voice   : voice_set_parameters: exit with code(0)
09-02 12:09:15.274   311  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 12:09:15.274   311  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 12:09:15.274   311  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 12:09:15.274   311  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 12:09:15.274   311  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 12:09:15.274   311  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 12:09:15.274  7208  7698 V ToneGenerator: ToneGenerator destructor
09-02 12:09:15.274  7208  7698 V ToneGenerator: stopTone
09-02 12:09:15.274  7208  7698 V ToneGenerator: Delete Track: 0xb4928080
09-02 12:09:15.276  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.277  7208  7208 D A2dpService: Received start request. Starting profile...
09-02 12:09:15.278  7208  7208 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 12:09:15.279  7208  7208 V Avrcp   : make
09-02 12:09:15.279  7208  7208 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 12:09:15.279  7208  7208 I bluedroid-qcom: get_profile_interface avrcp
09-02 12:09:15.279  7284  7284 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:09:15.279  7208  7658 V LGMDMManager: Create singleton instance
09-02 12:09:15.281  7208  7698 V AudioTrack: ~AudioTrack, releasing session id from 7208 on behalf of 7208
09-02 12:09:15.281   311  1385 V AudioFlinger: releasing 20 from 7208 for 7208
09-02 12:09:15.281   311  1385 V AudioFlinger:  decremented refcount to 0
09-02 12:09:15.281   311  1385 V AudioFlinger: purging stale effects
09-02 12:09:15.282   311  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 12:09:15.282   311  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 12:09:15.282   311  1385 V AudioFlinger: PlaybackThread::Track destructor
09-02 12:09:15.282   311  1274 V AudioPolicyService: AudioCommandThread() waking up
09-02 12:09:15.282   311  1385 V AudioFlinger: removeClient_l() pid 7208, calling pid 311
09-02 12:09:15.282   311  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 12:09:15.282   311  1274 V AudioPolicyManager: releaseOutput() 2
09-02 12:09:15.282   311  1274 V AudioPolicyService: AudioCommandThread() going to sleep
,09-02 12:09:15.289  7208  7658 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 12:09:15.290  7208  7208 V AudioManager: registerRemoteController: size of Media player list: 0
09-02 12:09:15.292  7208  7208 E AudioManager: No RCC entry present to update
09-02 12:09:15.292  7208  7208 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 12:09:15.295  7208  7208 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 12:09:15.296  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 12:09:15.296  7208  7208 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-02 12:09:15.300  3310  3310 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-02 12:09:15.300  3310  3310 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.300  3310  3310 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:09:15.302  7322  7322 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:09:15.303  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 12:09:15.303  7284  7706 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:15.303  7322  7322 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:09:15.345  7181  7710 W FormManager: Network not available. Please check & try again.
09-02 12:09:15.346  7683  7683 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 12:09:15.346  7683  7683 W LG Account v2.2: No ProfileInfo entries
09-02 12:09:15.346  7683  7683 I LG Account v2.2: isEnabled: false
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Country: EU
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Operator: OPEN
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Ranking support: false
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Comfort support: false
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Accessory: true
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Health device: true
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Extra Pedometer: false
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Blood glucose device: false
09-02 12:09:15.347  7683  7683 I Feature : [Lifetracker]Device Number: 3
09-02 12:09:15.349  7181  7711 V FormManager: Network unavailable.
,09-02 12:09:15.351  7383  7383 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:15
09-02 12:09:15.353  7383  7383 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:09:15.353  7383  7383 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:09:15.353  7383  7383 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:09:15.355  7112  7112 D BluetoothPermissionRequest: onReceive
09-02 12:09:15.356  7383  7383 D WeatherAncestor: connectivity changed - connection : true
09-02 12:09:15.356  7383  7383 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f64abbc
09-02 12:09:15.356  7383  7383 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-02 12:09:15.356  7383  7383 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:09:15.356  7383  7383 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:09:15.356  7383  7383 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:09:15.357  7383  7383 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:15
09-02 12:09:15.362  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 12:09:15.364  7181  7711 V FormManager: Network unavailable.
09-02 12:09:15.384  6570  6570 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 12:09:15.389  6570  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 12:09:15.390  1037  1981 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:09:15.390  1037  1981 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:09:15.399  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:15.406  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 12:09:15.406  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:09:15.407  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 12:09:15.407  7259  7259 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 12:09:15.408  7259  7259 I AppUp4:CustModeStarterReceiver: onReceive
09-02 12:09:15.412  7259  7259 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13cb978e
09-02 12:09:15.412  7259  7259 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-02 12:09:15.412  7259  7259 D AppUp4:CustFacade: isPhone : true
09-02 12:09:15.412  7259  7259 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:09:15.412  7259  7259 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 12:09:15.414  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.414  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:09:15.415  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:15.417  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:15.420  4801  7715 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.421  4801  7715 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:15.422  7284  7284 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 12:09:15.422  4801  7714 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:09:15.509  1037  1962 I art     : Explicit concurrent mark sweep GC freed 114029(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.370ms total 82.110ms
,09-02 12:09:15.510  1037  1764 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 12:09:15.516  3310  3310 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 12:09:15.516  3310  3310 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:15.516  3310  3310 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 12:09:15.518  7322  7322 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 12:09:15.518  7322  7322 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 12:09:15.520  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 12:09:15.524  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-02 12:09:15.525  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 12:09:15.525  7208  7208 I BluetoothA2dpServiceJni: classInitNative
09-02 12:09:15.525  7208  7208 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:09:15.525  7208  7208 D A2dpStateMachine: make
09-02 12:09:15.527  7208  7208 I bluedroid-qcom: get_profile_interface a2dp
09-02 12:09:15.527  7208  7722 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 12:09:15.529  7208  7208 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:09:15.529  7208  7208 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 12:09:15.531  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.532  7208  7208 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 12:09:15.532  7208  7721 D A2dpStateMachine: Enter Disconnected: -2
09-02 12:09:15.533  7181  7719 W FormManager: Network not available. Please check & try again.
09-02 12:09:15.533  7208  7208 D HidService: Received start request. Starting profile...
09-02 12:09:15.533  7208  7208 I bluedroid-qcom: get_profile_interface hidhost
09-02 12:09:15.534  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.534  7208  7208 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:09:15.536  7208  7208 D HealthService: Received start request. Starting profile...
09-02 12:09:15.537  7208  7208 I bluedroid-qcom: get_profile_interface health
09-02 12:09:15.537  7208  7208 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:09:15.537  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
,09-02 12:09:15.537  7284  7718 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:15.538  7208  7208 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 12:09:15.539  7208  7208 D PanService: Received start request. Starting profile...
,09-02 12:09:15.540  7208  7208 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:09:15.540  7208  7208 I bluedroid-qcom: get_profile_interface pan
09-02 12:09:15.541  7383  7383 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:15
09-02 12:09:15.542  7383  7383 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 12:09:15.542  7383  7383 D Weather.Utils: 2 : All the weather widget is gone.
09-02 12:09:15.542  7383  7383 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 12:09:15.543  7383  7383 D WeatherAncestor: connectivity changed - connection : true
09-02 12:09:15.543  7383  7383 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f64abbc
09-02 12:09:15.543  7181  7720 V FormManager: Network unavailable.
09-02 12:09:15.543  7383  7383 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 12:09:15.543  7383  7383 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 12:09:15.543  7383  7383 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 12:09:15.543  7383  7383 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 12:09:15.543  7383  7383 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:9:15
09-02 12:09:15.547  7208  7208 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 12:09:15.547  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.548  7208  7208 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-02 12:09:15.553  7208  7208 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:09:15.554  7208  7208 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:09:15.554  7208  7208 D BtGatt.GattService: start()
09-02 12:09:15.554  7208  7208 I bluedroid-qcom: get_profile_interface gatt
09-02 12:09:15.555  7208  7208 D BtGatt.AdvertiseManager: advertise manager created
09-02 12:09:15.556  7181  7720 V FormManager: Network unavailable.
09-02 12:09:15.562  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.562  7208  7208 D HeadsetStateMachine: Proxy object connected
09-02 12:09:15.563  7208  7208 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 12:09:15.563  7208  7208 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 12:09:15.564  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:15.565  7208  7208 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 12:09:15.566  7208  7208 V BluetoothMapService: BluetoothMapBinder()
,09-02 12:09:15.566  7208  7208 D BluetoothMapService: Received start request. Starting profile...
,09-02 12:09:15.566  7208  7208 D BluetoothMapService: start()
09-02 12:09:15.569  7208  7208 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 12:09:15.569  7208  7208 D BluetoothMapEmailAppObserver: createReceiver()
09-02 12:09:15.570  7208  7208 D BluetoothMapEmailAppObserver: initObservers()
09-02 12:09:15.570  7208  7208 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-02 12:09:15.578  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
,09-02 12:09:15.582  7208  7208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 12:09:15.584  7208  7698 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 12:09:15.585  7208  7698 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 12:09:15.585  7208  7698 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 12:09:15.586  7208  7208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:15.589  7208  7208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:15.591  7208  7208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:15.593  7208  7208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:15.593  7208  7208 V PanService: [BTUI] SIM Extra State :ABSENT
,09-02 12:09:15.597  7208  7208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 12:09:15.597  7208  7208 V BluetoothMapService: Handler(): got msg=1
09-02 12:09:15.598  7208  7658 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 12:09:15.599  7208  7658 I bluedroid-qcom: enable
09-02 12:09:15.599  7208  7658 I bt_hci_bdroid: init
09-02 12:09:15.599  7208  7729 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 12:09:15.599  7208  7729 I bt-btu  : btu_task pending for preload complete event
09-02 12:09:15.600  7208  7208 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:15.600  7208  7658 I bt_vendor: bt-vendor : init
09-02 12:09:15.600  7208  7658 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 12:09:15.600  7208  7658 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 12:09:15.600  7208  7658 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 12:09:15.600  7208  7658 D bt_userial_mct: userial_init
09-02 12:09:15.600  7208  7658 D bt_hci_bdroid: set_power 1
09-02 12:09:15.600  7208  7658 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 12:09:15.600  7208  7658 I bt_vendor: Starting hciattach daemon
09-02 12:09:15.600  7208  7658 I bt_vendor: try to set true
09-02 12:09:15.601  7208  7208 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:09:15.601  7208  7208 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:15.601  7208  7208 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:15.601  7208  7208 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:15.602  7208  7208 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 12:09:15.589  7732  7732 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:15.589  7732  7732 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:15.633  7733  7733 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 12:09:15.730  7739  7739 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 12:09:15.744  7740  7740 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:09:15.784  7742  7742 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:09:15.801  7743  7743 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 12:09:15.825  7744  7744 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:09:15.839  7748  7748 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-02 12:09:15.863  7750  7750 I libmdmdetect: ESOC framework not supported
09-02 12:09:15.864  7750  7750 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 12:09:15.876  7750  7750 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 12:09:15.876  7750  7750 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 12:09:15.876  7750  7750 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 12:09:15.876  7750  7750 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 12:09:15.877  7750  7750 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 12:09:15.877  7750  7750 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 12:09:15.877  7750  7750 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 12:09:15.914  7750  7751 E QC-QMI  : qmi_client [7750] 14: failed to locate client data
,09-02 12:09:15.918   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-02 12:09:15.918   469   469 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-02 12:09:15.949  7755  7755 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 12:09:15.964  7756  7756 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:09:16.004  7208  7658 I bt_vendor: bluetooth satus is on
09-02 12:09:16.004  7208  7658 D bt_hci_bdroid: preload
09-02 12:09:16.004  7208  7731 D bt_userial_mct: userial_open(port:0)
09-02 12:09:16.004  7208  7731 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-02 12:09:16.008  7208  7731 I bt_vendor: Done intiailizing UART,
,09-02 12:09:16.009  7208  7731 I bt_vendor: Done intiailizing UART
09-02 12:09:16.009  7208  7731 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-02 12:09:16.009  7208  7731 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 12:09:16.009  7208  7729 I bt-btu  : btu_task received preload complete event
09-02 12:09:16.010  7208  7758 D bt_userial_mct: Entering userial_read_thread()
09-02 12:09:16.010  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 12:09:16.010  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 12:09:16.012  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 12:09:16.018  7208  7729 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:09:16.019  7208  7729 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:09:16.019  7208  7729 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:09:16.019  7208  7729 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 12:09:16.019  7208  7729 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:09:16.019  7208  7729 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 12:09:16.086  7208  7729 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 12:09:16.087  7208  7729 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021d061 
09-02 12:09:16.087  7208  7729 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021d061 
,09-02 12:09:16.111  7401  7428 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-02 12:09:16.126  7208  7662 E bt-btif : Calling BTA_HhEnable
09-02 12:09:16.126  7208  7662 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 12:09:16.126  7208  7662 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 12:09:16.127  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 12:09:16.127  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 12:09:16.127  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 12:09:16.127  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,09-02 12:09:16.127  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 12:09:16.129  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:09:16.129  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:09:16.130  7208  7662 D BluetoothAdapterProperties: Name is: G3
09-02 12:09:16.135  7208  7662 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:09:16.135  7208  7662 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:09:16.136  7208  7662 D bt_hci_bdroid: postload
09-02 12:09:16.136  7208  7731 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 12:09:16.136  7208  7729 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 12:09:16.137  7208  7662 D bte_conf: Device ID record 1 : primary
09-02 12:09:16.137  7208  7662 D bte_conf:   vendorId            = 00c4
09-02 12:09:16.137  7208  7662 D bte_conf:   vendorIdSource      = 0001
09-02 12:09:16.137  7208  7662 D bte_conf:   product             = 13a1
09-02 12:09:16.137  7208  7662 D bte_conf:   version             = 1000
09-02 12:09:16.137  7208  7662 D bte_conf:   clientExecutableURL = 
09-02 12:09:16.137  7208  7662 D bte_conf:   serviceDescription  = 
09-02 12:09:16.137  7208  7662 D bte_conf:   documentationURL    = 
09-02 12:09:16.137  7208  7662 D bte_conf: bte_load_did_conf no section named DID2.
09-02 12:09:16.138  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:16.139  7208  7729 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:16.139  7208  7729 W bt-smp  : Plain text(LSB ~ MSB) = bd 15 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:16.139  7208  7729 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 d6 2a d9 e8 5b 2b 8a f0 7a cd df a0 f8 7d 61 
09-02 12:09:16.139  7208  7729 W bt-btm  : Stopping oneshot timer
09-02 12:09:16.140  7208  7731 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:09:16.140  7208  7731 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:09:16.141  7208  7658 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 12:09:16.142  7208  7658 D BluetoothAdapterProperties: ScanMode =  20
09-02 12:09:16.142  7208  7658 D BluetoothAdapterProperties: State =  11
09-02 12:09:16.143  7208  7658 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 12:09:16.143  7208  7658 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 12:09:16.143  7208  7658 D BluetoothAdapterProperties: Setting state to 12
09-02 12:09:16.143  7208  7658 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:09:16.144  7208  7662 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 12:09:16.145  7208  7662 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:09:16.148  7208  7731 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:09:16.148  7208  7731 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 12:09:16.139  7762  7762 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:16.139  7762  7762 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:16.154  7208  7731 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:09:16.158  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:16.158  7208  7758 E bt_mct  : hci lib postload completed
09-02 12:09:16.158  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 12:09:16.158  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:16.161  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:09:16.167  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:16.170  7208  7658 I BluetoothAdapterState: Entering On State
09-02 12:09:16.171  1839  3484 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:09:16.174  7208  7658 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 12:09:16.174  7208  7658 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,09-02 12:09:16.174  7208  7658 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 12:09:16.177  7208  7658 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-02 12:09:16.181  1839  1839 D BluetoothHeadset: Proxy object connected
09-02 12:09:16.181  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:09:16.183  1037  1037 D BluetoothHeadset: Proxy object connected
09-02 12:09:16.186  7112  7129 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:09:16.188  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:09:16.190  7208  7662 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:09:16.190  7208  7662 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 12:09:16.191  7208  7729 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:16.191  7208  7729 W bt-smp  : Plain text(LSB ~ MSB) = 56 a3 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:16.191  7208  7729 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 c0 a4 48 e6 33 bf 53 26 6d 30 9c 2b 49 b8 10 
09-02 12:09:16.191  7208  7729 W bt-btm  : Stopping oneshot timer
09-02 12:09:16.191  1839  1839 D BluetoothHeadset: Proxy object connected
09-02 12:09:16.192  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:09:16.193  7112  7202 D BluetoothMap: onBluetoothStateChange: up=true
09-02 12:09:16.200  1037  1037 D BluetoothA2dp: Proxy object connected
,09-02 12:09:16.202  1839  2440 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:09:16.206  1839  1839 D BluetoothHeadset: Proxy object connected
09-02 12:09:16.206  7112  7129 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:09:16.206  7112  7129 D BluetoothPan: onBluetoothStateChange call bindService
09-02 12:09:16.207  7208  7729 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:16.207  7208  7729 W bt-smp  : Plain text(LSB ~ MSB) = 89 ce 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:16.207  7208  7729 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 02 85 1a 52 2a ae 0f e2 8a 84 46 14 ab 27 22 
09-02 12:09:16.207  7208  7729 W bt-btm  : Stopping oneshot timer
09-02 12:09:16.211  7112  7128 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:09:16.216  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-02 12:09:16.217  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 12:09:16.218  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-02 12:09:16.218  7112  7112 D BluetoothMap: Proxy object connected
09-02 12:09:16.218  7112  7112 D MapProfile: Bluetooth service connected
09-02 12:09:16.218  7112  7112 D BluetoothMap: getConnectedDevices()
09-02 12:09:16.218  1037  1119 D BluetoothManagerService: Message: 40
09-02 12:09:16.218  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 12:09:16.220  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.220  7208  7658 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 12:09:16.220  1928  2109 D LGBluetoothAPIService: Message: 1
09-02 12:09:16.220  7208  7729 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:16.220  1928  2109 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 12:09:16.220  7208  7729 W bt-smp  : Plain text(LSB ~ MSB) = 8c b4 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:16.220  7208  7729 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f e7 5a 73 86 26 7f 4b dd 3b 04 fc 39 90 02 66 
09-02 12:09:16.220  7208  7729 W bt-btm  : Stopping oneshot timer
09-02 12:09:16.221  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:16.228  7778  7778 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-02 12:09:16.233  7208  7729 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:16.233  7208  7729 W bt-smp  : Plain text(LSB ~ MSB) = 94 69 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:16.233  7208  7729 W bt-smp  : Encrypted text(LSB ~ MSB) = b1 2f 02 86 b3 36 9f 55 db 2c f5 28 fe c0 03 df 
09-02 12:09:16.233  7208  7729 W bt-btm  : Stopping oneshot timer
09-02 12:09:16.234  1928  2109 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-02 12:09:16.236  7208  7208 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.236  7208  7208 D BluetoothMapService: STATE_ON
09-02 12:09:16.237  6984  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 12:09:16.237  7208  7224 V BluetoothMapService: getConnectedDevices()
09-02 12:09:16.238  7208  7208 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 12:09:16.238  7208  7208 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 12:09:16.239  7112  7112 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:09:16.239  7112  7112 D PanProfile: Bluetooth service connected
09-02 12:09:16.239  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 12:09:16.239  1928  2109 D LGBluetoothAPIService: Message: 100
09-02 12:09:16.239  1928  2109 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:16.242  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:16.243  7112  7112 D BluetoothInputDevice: Proxy object connected
09-02 12:09:16.243  7112  7112 D HidProfile: Bluetooth service connected
09-02 12:09:16.245  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:16.246  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:16.246  7112  7112 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 12:09:16.249  1037  1119 D BluetoothManagerService: Message: 30
,09-02 12:09:16.251  7112  7112 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 12:09:16.254  1037  1119 D BluetoothManagerService: Message: 30
09-02 12:09:16.256  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:16.256  7208  7208 V BluetoothPbapService: Pbap Service onCreate
09-02 12:09:16.256  7208  7208 V BluetoothPbapService: Starting PBAP service
09-02 12:09:16.257  7208  7208 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 12:09:16.258  7208  7208 V BluetoothPbapService: Pbap Service onBind
09-02 12:09:16.259  7208  7208 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.259  7208  7208 V BluetoothPbapService: state: 12
09-02 12:09:16.259  7208  7208 V BluetoothMapService: Handler(): got msg=1
,09-02 12:09:16.259  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 12:09:16.260  7208  7208 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 12:09:16.260  7208  7208 V BluetoothPbapService: Handler(): got msg=1
09-02 12:09:16.261  7208  7208 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 12:09:16.261  7208  7779 D BluetoothMapMasInstance: MAS initSocket()
09-02 12:09:16.262  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:09:16.262  7208  7779 D BluetoothMapMasInstance:   masId = 00
09-02 12:09:16.262  7208  7779 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 12:09:16.262  7208  7779 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 12:09:16.262  7208  7779 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 12:09:16.262  7208  7780 V BluetoothPbapService: Pbap Service initSocket
,09-02 12:09:16.263  1037  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:16.264  1037  1687 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:16.265  7208  7779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:16.265  7208  7780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:16.266  7208  7779 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 12:09:16.266  7208  7780 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 12:09:16.266  7208  7779 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 12:09:16.266  7208  7780 V BluetoothPbapService: Succeed to create listening socket 
09-02 12:09:16.266  7208  7779 D BluetoothMapMasInstance: Accepting socket connection...
09-02 12:09:16.267  7208  7780 V BluetoothPbapService: Accepting socket connection...
09-02 12:09:16.267  7112  7112 D BluetoothA2dp: Proxy object connected
09-02 12:09:16.268  7208  7662 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:09:16.268  7208  7662 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 12:09:16.269  7112  7112 D A2dpProfile: Bluetooth service connected
09-02 12:09:16.270  7208  7208 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:09:16.270  7208  7208 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.270  7208  7208 V BluetoothPbapReceiver: ***********state = 12
09-02 12:09:16.274  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:09:16.275  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:16.275  2214  2214 D c       : Getting all permits...
09-02 12:09:16.275  2214  2214 D a       : Opening database...
09-02 12:09:16.278  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:16.280  2214  2214 D a       : Opening database auth.proximity.permit_store...
09-02 12:09:16.280  2214  2214 D a       : Closing database...
09-02 12:09:16.283  7112  7112 D BluetoothHeadset: Proxy object connected
09-02 12:09:16.284  7112  7112 D HeadsetProfile: Bluetooth service connected
09-02 12:09:16.287  7112  7112 D BluetoothPbap: Proxy object connected
,09-02 12:09:16.289  7112  7112 D PbapServerProfile: Bluetooth service connected
09-02 12:09:16.292  7112  7112 D DockEventReceiver: finishStartingService: stopping service
09-02 12:09:16.296  7112  7112 D BluetoothPermissionRequest: onReceive
09-02 12:09:16.298  7112  7112 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 12:09:16.299  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 12:09:16.301  7208  7208 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 12:09:16.302  7208  7208 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 12:09:16.307  7208  7208 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-02 12:09:16.324  7208  7208 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 12:09:16.324  7208  7208 V BtOppService: onCreate
,09-02 12:09:16.327  7208  7208 V BluetoothOppNotification: send message
09-02 12:09:16.330  7208  7208 V BtOppService: Starting RfcommListener
09-02 12:09:16.333  7208  7208 D BluetoothOppPreference: Dumping Names:  
09-02 12:09:16.333  7208  7208 D BluetoothOppPreference: {}
09-02 12:09:16.333  7208  7208 D BluetoothOppPreference: Dumping Channels:  
,09-02 12:09:16.333  7208  7208 D BluetoothOppPreference: {}
09-02 12:09:16.333  7208  7208 V BtOppService: onStartCommand
09-02 12:09:16.335  7208  7788 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:16.336  7208  7208 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.336  7208  7208 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 12:09:16.337  7208  7788 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-02 12:09:16.338  7208  7785 V BtOppService: Deleted complete outbound shares, number =  0
09-02 12:09:16.338  7208  7208 V BluetoothOppNotification: new notify threadi!
09-02 12:09:16.339  7208  7208 V BluetoothOppNotification: send delay message
09-02 12:09:16.340  7208  7208 V BtOppService: start RfcommListener
09-02 12:09:16.340  7208  7788 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@90ae911 on behalf of 
09-02 12:09:16.341  7208  7785 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 12:09:16.342  7208  7785 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 12:09:16.342  7208  7788 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:09:16.343  7208  7788 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:16.343  7208  7785 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ce9a76 on behalf of 
09-02 12:09:16.343  7208  7788 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:09:16.344  7208  7788 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@384be877 on behalf of 
09-02 12:09:16.344  7208  7208 V BtOppService: RfcommListener started
09-02 12:09:16.345  7208  7788 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:09:16.346  7208  7788 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:09:16.346  7208  7790 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 12:09:16.346  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:16.347  7208  7790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:16.347  7208  7790 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-02 12:09:16.348  7208  7789 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:09:16.349  7208  7790 V BtOppRfcommListener: Started RFCOMM listener....
09-02 12:09:16.349  7208  7789 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c306ce4 on behalf of 
,09-02 12:09:16.349  7208  7790 I BtOppRfcommListener: Accept thread started.
09-02 12:09:16.349  7208  7790 V BtOppRfcommListener: Accepting connection...
09-02 12:09:16.350  7208  7789 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 12:09:16.351  7208  7789 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:16.352  7208  7789 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e24054d on behalf of 
09-02 12:09:16.353  7208  7789 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 12:09:16.354  7208  7789 V BluetoothOppNotification: outbound notification was removed.
09-02 12:09:16.354  7208  7789 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:16.355  7208  7789 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3581e802 on behalf of 
09-02 12:09:16.356  7208  7789 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 12:09:16.357  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:16.357  7208  7208 V BluetoothFtpService: Ftp Service onCreate
09-02 12:09:16.357  7208  7208 I BluetoothFtpService: Ftp Service onCreate
09-02 12:09:16.357  7208  7208 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:09:16.357  7208  7208 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.357  7208  7208 V BluetoothFtpService: Starting Listening on sockets
09-02 12:09:16.358  7208  7208 V BtOppService: ContentObserver received notification
09-02 12:09:16.358  7208  7208 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:09:16.358  7208  7789 V BluetoothOppNotification: inbound notification was removed.
09-02 12:09:16.358  7208  7208 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:16.358  7208  7208 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:16.358  7208  7208 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.358  7208  7208 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 12:09:16.358  7208  7789 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:09:16.358  7208  7208 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:09:16.360  7208  7791 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:16.360  7208  7791 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-02 12:09:16.361  7208  7208 V BtOppService: ContentObserver received notification
09-02 12:09:16.361  7208  7208 V BluetoothFtpService: Handler(): got msg=1
09-02 12:09:16.362  7208  7208 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 12:09:16.362  7208  7208 V BluetoothFtpService: Ftp Service initSocket
09-02 12:09:16.367  1037  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:16.368  7208  7208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:16.368  7208  7789 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f97350 on behalf of 
09-02 12:09:16.369  7208  7791 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b38a949 on behalf of 
09-02 12:09:16.369  7208  7208 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-02 12:09:16.369  7208  7208 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 12:09:16.371  7208  7791 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:16.371  7208  7791 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:09:16.371  7208  7792 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-02 12:09:16.372  7208  7791 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@222a824e on behalf of 
,09-02 12:09:16.373  7208  7791 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:09:16.374  7208  7791 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:09:16.382  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:16.382  7208  7208 V BluetoothSapService: Sap Service onCreate
09-02 12:09:16.384  7208  7208 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:16.384  7208  7208 V BluetoothSapService: state: 12
09-02 12:09:16.384  7208  7208 V BluetoothSapService: Starting SAP server process
,09-02 12:09:16.385  7208  7208 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 12:09:16.369  7793  7793 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:16.369  7793  7793 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:16.387  7208  7794 V BluetoothSapService: Sap Service initRfcommSocket
09-02 12:09:16.388  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:16.388  7208  7794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:16.389  7208  7794 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-02 12:09:16.389  7208  7794 V BluetoothSapService: Succeed to create listening socket 
09-02 12:09:16.389  7208  7794 V BluetoothSapService: Accepting socket connection...
09-02 12:09:16.398  7793  7793 V BT_SAP  : Event pipe created
09-02 12:09:16.398  7793  7793 V BT_SAP  : create_server_socket qcom.sap.server
09-02 12:09:16.398  7793  7793 V BT_SAP  : created socket fd 6
,09-02 12:09:16.518   307  7436 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 12:09:16.520  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
09-02 12:09:16.520  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s584ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:16.520  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s465ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:16.520  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s465ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:16.520  1037  7422 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 12:09:16.920  1037  1919 I ActivityManager: Killing 7585:com.lge.bnr/1000 (adj 15): empty #17
,09-02 12:09:16.938   307  7548 D libc-netbsd: res_queryN name = mtalk.google.com., class = 1, type = 1
,09-02 12:09:16.942  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 12:09:16.958  1037  1945 W libprocessgroup: failed to open /acct/uid_1000/pid_7585/cgroup.procs: No such file or directory
,09-02 12:09:17.014  1037  1377 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:09:17.014  1037  1377 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:09:17.044  1037  1379 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 12:09:17.046  1037  1379 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 12:09:17.341  7208  7208 V BluetoothOppNotification: new notify threadi!
,09-02 12:09:17.341  7208  7208 V BluetoothOppNotification: send delay message
,09-02 12:09:17.353  7208  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:09:17.357  7208  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b0755a on behalf of 
,09-02 12:09:17.363  7208  7804 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 12:09:17.364  7208  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:17.365  7208  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337f938b on behalf of 
09-02 12:09:17.366  7208  7804 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 12:09:17.367  7208  7804 V BluetoothOppNotification: outbound notification was removed.
09-02 12:09:17.367  7208  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:17.368  7208  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34c85c68 on behalf of 
09-02 12:09:17.369  7208  7804 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 12:09:17.370  7208  7804 V BluetoothOppNotification: inbound notification was removed.
09-02 12:09:17.371  7208  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:09:17.372  7208  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25e73881 on behalf of 
,09-02 12:09:17.596  1037  1919 I ActivityManager: Killing 6892:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-02 12:09:17.620  5814  5814 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-02 12:09:17.620  5814  5814 W System.err: android.os.DeadObjectException
09-02 12:09:17.621  5814  5814 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 12:09:17.621  5814  5814 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-02 12:09:17.621  5814  5814 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:09:17.621  5814  5814 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:09:17.621  5814  5814 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:09:17.621  5814  5814 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:09:17.621  5814  5814 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:09:17.621  5814  5814 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:09:17.621  5814  5814 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-02 12:09:17.621  5814  5814 W System.err: android.os.DeadObjectException
09-02 12:09:17.622  5814  5814 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 12:09:17.622  5814  5814 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-02 12:09:17.622  5814  5814 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:09:17.622  5814  5814 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:09:17.622  5814  5814 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:09:17.622  5814  5814 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:09:17.622  5814  5814 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:09:17.622  5814  5814 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:09:17.622  5814  5814 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-02 12:09:17.623  5814  5814 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-02 12:09:17.656  1037  1945 W libprocessgroup: failed to open /acct/uid_1000/pid_6892/cgroup.procs: No such file or directory
,09-02 12:09:17.656  1037  1945 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-02 12:09:17.676  5814  5814 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-02 12:09:17.677  5814  5814 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-02 12:09:17.733  1037  2019 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:09:17.784  5814  5814 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-02 12:09:17.813  7805  7805 D UEI.SmartControl: Quickset Services start...
09-02 12:09:17.815  7805  7805 I UEI.SmartControl: Manufacture = LGE
09-02 12:09:17.815  7805  7805 D UEI.SmartControl: Id = LGNevo
09-02 12:09:17.817  7805  7805 D UEI.SmartControl: File observer start...
,09-02 12:09:17.821  7805  7805 E UEI.SmartControl: IR Port is disabled: false
09-02 12:09:17.821  7805  7805 D UEI.SmartControl: Starting file observer...
09-02 12:09:17.822  7805  7805 D UEI.SmartControl: Extracting JNI libs...
09-02 12:09:17.822  7805  7805 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-02 12:09:17.930  7805  7805 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-02 12:09:17.930  7805  7805 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-02 12:09:17.930  7805  7805 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-02 12:09:17.970  7805  7805 I UEI.SmartControl: --- Selecting new region: 6
09-02 12:09:17.972  7805  7805 I UEI.SmartControl: Model = LG-D855
09-02 12:09:17.975  7805  7805 D UEI.SmartControl: QS Service created
,09-02 12:09:17.992  7805  7805 I UEI.SmartControl: Service initServices...
,09-02 12:09:17.997  7805  7805 D UEI.SmartControl: QS start get config
09-02 12:09:18.010  1037  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:18.010  1037  1981 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2d96dabf mBinding = false
,09-02 12:09:18.026  1037  1119 D BluetoothManagerService: Message: 2
09-02 12:09:18.026  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:09:18.026  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:18.026  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:18.028  1037  1119 D BluetoothManagerService: Sending off request.
,09-02 12:09:18.032  7208  7679 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,09-02 12:09:18.032  7208  7658 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 12:09:18.033  7208  7658 D BluetoothAdapterProperties: Setting state to 13
09-02 12:09:18.033  7208  7658 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:09:18.035  7208  7658 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:09:18.035  7208  7658 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 12:09:18.039  7208  7662 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:09:18.040  7208  7658 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 12:09:18.041  7208  7792 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 12:09:18.042  7208  7779 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 12:09:18.043  7208  7780 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 12:09:18.045  7208  7790 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:18.045  7208  7794 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:09:18.046  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 12:09:18.046  7208  7729 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 12:09:18.047  7208  7658 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 12:09:18.048  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 12:09:18.048  7208  7729 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 12:09:18.049  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:18.049  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:18.050  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:18.050  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:18.051  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:09:18.051  6984  ,6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:18.051  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:18.052  6984  6984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:09:18.052  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:18.071  7805  7805 D UEI.SmartControl: Loading JNI Libs...
,09-02 12:09:18.083  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:18.083  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 12:09:18.083  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-02 12:09:18.086  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:18.088  7208  7208 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.088  7208  7208 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:09:18.088  7208  7208 V BluetoothMapService: Handler(): got msg=4
09-02 12:09:18.088  7208  7208 D BluetoothMapService: MAP Service closeService in
09-02 12:09:18.088  7208  7208 D BluetoothMapMasInstance: MAP Service shutdown
09-02 12:09:18.088  7208  7208 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:09:18.088  7208  7208 V BluetoothMapService: MAP Service closeService out
09-02 12:09:18.089  7208  7208 V BtOppService: Receiver DISABLED_ACTION 
09-02 12:09:18.089  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.089  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-02 12:09:18.090  7208  7208 I BtOppRfcommListener: stopping Accept Thread
09-02 12:09:18.090  7208  7208 V BtOppRfcommListener: close mBtServerSocket
09-02 12:09:18.090  7208  7208 V BtOppRfcommListener: waiting for thread to terminate
09-02 12:09:18.091  7208  7790 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:09:18.091  7208  7208 V BtOppRfcommListener: done waiting for thread to terminate
09-02 12:09:18.092  7208  7208 V BtOppService: onDestroy
09-02 12:09:18.092  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:09:18.094  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:18.095  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:18.101  7208  7208 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-02 12:09:18.105  7208  7208 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:09:18.106  7208  7208 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.106  7208  7208 V BluetoothPbapReceiver: ***********state = 13
09-02 12:09:18.107  7208  7208 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-02 12:09:18.109  7112  7112 D DockEventReceiver: finishStartingService: stopping service
09-02 12:09:18.109  7208  7208 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.109  7208  7208 V BluetoothPbapService: state: 13
09-02 12:09:18.109  7208  7208 V BluetoothPbapService: Pbap Service closeService in
09-02 12:09:18.110  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:09:18.111  7112  7112 D BluetoothPbap: Proxy object disconnected
09-02 12:09:18.111  7112  7112 D PbapServerProfile: Bluetooth service disconnected
09-02 12:09:18.112  7208  7208 V BluetoothPbapService: successfully stopped pbap service
09-02 12:09:18.112  7208  7208 V BluetoothPbapService: Pbap Service closeService out
09-02 12:09:18.112  7208  7208 V BluetoothPbapService: Pbap Service onDestroy
09-02 12:09:18.112  7208  7208 V BluetoothPbapService: Pbap Service closeService in
09-02 12:09:18.112  7208  7208 V BluetoothPbapService: Pbap Service closeService out
09-02 12:09:18.112  7208  7208 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-02 12:09:18.124  7112  7112 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 12:09:18.128  7112  7112 D BluetoothPermissionRequest: onReceive
09-02 12:09:18.129  7112  7112 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 12:09:18.133  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:09:18.136  7208  7208 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 12:09:18.136  7208  7208 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-02 12:09:18.137  7208  7208 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 12:09:18.140  7208  7208 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.140  7208  7208 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 12:09:18.141  7208  7208 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:09:18.141  7208  7208 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.141  7208  7208 V BluetoothFtpService: Ftp Service closeService
09-02 12:09:18.141  7208  7208 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 12:09:18.143  7208  7208 V BluetoothFtpService: successfully stopped ftp service
09-02 12:09:18.143  7208  7208 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:09:18.143  7208  7208 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:18.143  7208  7208 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:18.144  7208  7208 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.144  7208  7208 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 12:09:18.144  7208  7208 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:09:18.144  7208  7208 V BluetoothFtpService: Ftp Service onDestroy
09-02 12:09:18.144  7208  7208 V BluetoothFtpService: Ftp Service closeService
09-02 12:09:18.148  7208  7208 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:18.148  7208  7208 V BluetoothSapService: state: 13
09-02 12:09:18.148  7208  7208 V BluetoothSapService: Stopping SAP server process
,09-02 12:09:18.150  7208  7208 V BluetoothSapService: Sap Service closeSapService in
09-02 12:09:18.150  7208  7208 V BluetoothSapService: Close listen Socket : 
09-02 12:09:18.150  7208  7208 V BluetoothSapService: Close rfcomm Socket : 
09-02 12:09:18.151  7208  7208 V BluetoothSapService: Close sapd  Socket : 
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Sap Service closeSapService out
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Sap Service onDestroy
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Sap Service closeSapService in
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Close listen Socket : 
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Close rfcomm Socket : 
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Close sapd  Socket : 
09-02 12:09:18.152  7208  7208 V BluetoothSapService: Sap Service closeSapService out
09-02 12:09:18.382  7805  7805 I UEI.SmartControl: Supports setup maps: true
,09-02 12:09:18.385  7805  7805 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 12:09:18.385  7805  7805 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 12:09:18.385  7805  7805 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 12:09:18.385  7805  7805 I UEI.SmartControl: ### init IR Blaster...
09-02 12:09:18.391  7805  7805 D serial_port: Configuring serial port
09-02 12:09:18.394  7805  7805 E UEI.SmartControl: UEIBLaster setting for 616
09-02 12:09:18.395  7805  7805 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 12:09:18.395  7805  7805 I UEI.SmartControl: configuring settings for MAXQ616
09-02 12:09:18.395  7805  7805 I UEI.SmartControl: Get version...
09-02 12:09:18.413  7805  7843 D UEI.SmartControl: serial port data available: 21
,09-02 12:09:18.443  7805  7805 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-02 12:09:18.443  7805  7805 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 12:09:18.443  7805  7805 I UEI.SmartControl: QS saving settings...
09-02 12:09:18.446  7805  7805 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 12:09:18.463  7805  7843 D UEI.SmartControl: serial port data available: 4
,09-02 12:09:18.505  7805  7852 I UEI.SmartControl: Device manager: loading config....
,09-02 12:09:18.512  7805  7852 D UEI.SmartControl: ----------- loading internal config...
09-02 12:09:18.513  7805  7805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-02 12:09:18.515  7805  7805 E UEI.SmartControl: Services init done
09-02 12:09:18.516  7805  7805 D UEI.SmartControl: QS Service init finished
09-02 12:09:18.518  7805  7805 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 12:09:18.518  7805  7805 D UEI.SmartControl: QS Service version code: 201091
09-02 12:09:18.521  7805  7805 D UEI.SmartControl: Service requested: Control
,09-02 12:09:18.536  7805  7852 E UEI.SmartControl: Loading SETTINGS...
,09-02 12:09:18.539  7805  7805 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 12:09:18.543  1037  1873 I ActivityManager: Killing 5814:com.lge.qremote/u0a112 (adj 15): empty #17
09-02 12:09:18.551  7805  7852 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-02 12:09:18.565  7805  7851 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 12:09:18.565  7805  7851 D UEI.SmartControl: -----service ready thread exits
09-02 12:09:18.599  1037  1945 W libprocessgroup: failed to open /acct/uid_10112/pid_5814/cgroup.procs: No such file or directory
,09-02 12:09:18.608  7805  7805 D UEI.SmartControl: Internal service binding...
,09-02 12:09:19.026  7208  7662 D bt_hci_bdroid: cleanup
,09-02 12:09:19.033  7208  7731 I bt_lpm  : LPM is already off!!!
09-02 12:09:19.034  7208  7758 I bt_userial_mct: exiting userial_read_thread
09-02 12:09:19.034  7208  7758 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 12:09:19.037  7208  7729 W bt-btif : ag scb idx 1 not allocated
09-02 12:09:19.037  7208  7729 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:19.037  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:19.039  7208  7662 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 12:09:19.041  7208  7729 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:09:19.041  7208  7729 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-02 12:09:19.041  7208  7731 I bt_vendor: hw_epilog_process
09-02 12:09:19.042  7208  7662 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 12:09:19.042  7208  7662 D bt_userial_mct: userial_close
09-02 12:09:19.042  7208  7662 E bt_userial_mct: pthread_join() FAILED result:3
09-02 12:09:19.042  7208  7662 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 12:09:19.048  7208  7662 D bt_hci_bdroid: set_power 0
09-02 12:09:19.048  7208  7662 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 12:09:19.048  7208  7662 I bt_vendor: bluetooth satus is on
,09-02 12:09:19.048  7208  7662 I bt_vendor: bt-vendor : resetting BT status
09-02 12:09:19.048  7208  7662 I bt_vendor: Starting hciattach daemon
09-02 12:09:19.048  7208  7662 I bt_vendor: try to set false
,09-02 12:09:19.054  7208  7662 I bt_vendor: Starting hciattach daemon
09-02 12:09:19.054  7208  7662 I bt_vendor: try to set false
09-02 12:09:19.056  7208  7662 I bt_vendor: cleanup
09-02 12:09:19.057  7208  7729 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 12:09:19.057  7208  7662 I GKI_LINUX: GKI_exit_task 0 done
09-02 12:09:19.057  7208  7662 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 12:09:19.059  7208  7658 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 12:09:19.066  7208  7208 D HeadsetService: Received stop request...Stopping profile...
,09-02 12:09:19.070  7208  7208 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:09:19.070  7208  7208 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:09:19.070  7208  7698 D HeadsetStateMachine: Exit Disconnected: -1
09-02 12:09:19.072  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.074  7208  7658 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 12:09:19.074  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:19.074  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:19.075  1839  1839 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:19.076  1037  1037 D BluetoothHeadset: Proxy object disconnected
09-02 12:09:19.076  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 12:09:19.076  7208  7208 D A2dpService: Received stop request...Stopping profile...
09-02 12:09:19.077  7208  7721 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:09:19.079  7208  7208 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-02 12:09:19.084  7208  7208 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 12:09:19.084  7208  7208 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:09:19.084  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.085  1037  1037 D BluetoothA2dp: Proxy object disconnected
09-02 12:09:19.085  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 12:09:19.086  7208  7208 D HidService: Received stop request...Stopping profile...
09-02 12:09:19.086  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.088  7208  7208 D HealthService: Received stop request...Stopping profile...
09-02 12:09:19.088  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.090  7208  7208 D PanService: Received stop request...Stopping profile...
09-02 12:09:19.091  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.093  7208  7208 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:09:19.095  7208  7208 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:09:19.095  7208  7208 D BtGatt.GattService: stop()
09-02 12:09:19.096  7208  7208 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 12:09:19.097  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.098  7208  7208 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:09:19.098  7208  7208 D BluetoothMapService: stop()
09-02 12:09:19.100  7208  7208 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 12:09:19.100  7208  7208 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 12:09:19.101  7208  7208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f64abbc
09-02 12:09:19.108  7208  7208 D HeadsetStateMachine: Unbinding service...
,09-02 12:09:19.112  7208  7208 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:09:19.112  7208  7208 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:09:19.113  7208  7208 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:09:19.113  7208  7208 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:09:19.113  7208  7208 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:09:19.113  7208  7208 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:09:19.113  7208  7208 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 12:09:19.113  7208  7208 I BluetoothA2dpServiceJni: cleanupNative
09-02 12:09:19.113  7208  7722 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 12:09:19.114  7208  7208 I GKI_LINUX: GKI_exit_task 2 done
09-02 12:09:19.114  7208  7208 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 12:09:19.114  7208  7208 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:09:19.114  7208  7208 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:09:19.115  7208  7208 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:09:19.115  7208  7208 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:09:19.115  7208  7208 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:09:19.115  7208  7208 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:09:19.115  7208  7208 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 12:09:19.118  7208  7208 V BluetoothMapService: Handler(): got msg=4
09-02 12:09:19.118  7208  7208 D BluetoothMapService: MAP Service closeService in
09-02 12:09:19.118  7208  7208 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:09:19.118  7208  7208 V BluetoothMapService: MAP Service closeService out
09-02 12:09:19.119  7208  7658 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 12:09:19.119  7208  7658 D BluetoothAdapterProperties: Setting state to 10
09-02 12:09:19.119  7208  7658 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 12:09:19.119  7208  7208 D BluetoothMapService: cleanup()
09-02 12:09:19.120  7208  7208 D BluetoothMapService: MAP Service closeService in
09-02 12:09:19.120  7208  7208 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 12:09:19.120  7208  7208 V BluetoothMapService: MAP Service closeService out
09-02 12:09:19.121  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:19.121  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 12:09:19.121  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,09-02 12:09:19.126  1839  3484 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:19.127  7208  7658 I BluetoothAdapterState: Entering OffState
09-02 12:09:19.128  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:19.129  7112  7129 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:09:19.129  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:19.130  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:09:19.130  7112  7129 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:09:19.135  7112  7129 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 12:09:19.138  1839  3485 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:19.139  7112  7129 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:09:19.140  7112  7129 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:09:19.140  7112  7129 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:09:19.141  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 12:09:19.141  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 12:09:19.143  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 12:09:19.143  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 12:09:19.144  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2d96dabf mBinding = false
09-02 12:09:19.144  1037  1119 D BluetoothManagerService: Sending unbind request.
09-02 12:09:19.149  7208  7662 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 12:09:19.152  7208  7208 I GKI_LINUX: GKI_exit_task 1 done
09-02 12:09:19.152  7208  7208 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 12:09:19.153  7208  7208 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 12:09:19.153  7208  7208 I art     : --- WEIRD: removing null entry 248
09-02 12:09:19.153  7208  7208 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-02 12:09:19.153  7208  7208 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 12:09:19.154  7208  7208 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 12:09:19.155  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 12:09:19.157  7208  7208 I art     : System.exit called, status: 0
09-02 12:09:19.157  7208  7208 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 12:09:19.177   311   311 V AudioFlinger: 7208 died, releasing its sessions
09-02 12:09:19.177   311   311 V AudioFlinger:  pid 1839 @ 0
09-02 12:09:19.177   311   311 V AudioFlinger:  pid 3310 @ 1
09-02 12:09:19.177   311   311 V AudioFlinger:  pid 3310 @ 2
,09-02 12:09:19.187  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-02 12:09:19.187  1928  2109 D LGBluetoothAPIService: Message: 101
09-02 12:09:19.188  1928  2109 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-02 12:09:19.188  1928  2109 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-02 12:09:19.189  1928  2109 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-02 12:09:19.190  7112  7112 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-02 12:09:19.228  1037  1764 I ActivityManager: Process com.android.bluetooth (pid 7208) has died
,09-02 12:09:19.229  1037  1764 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-02 12:09:19.229  1037  1764 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-02 12:09:19.238  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:19.239  1928  2109 D LGBluetoothAPIService: Message: 2
09-02 12:09:19.239  1928  2109 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-02 12:09:19.241  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:19.243  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:19.245  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-02 12:09:19.247  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 12:09:19.247  7112  7112 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 12:09:19.259  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:09:19.266  1590  1590 D BluetoothAdapter: 943413990: getState() :  mService = null. Returning STATE_OFF
09-02 12:09:19.266  1590  1590 D BluetoothAdapter: 943413990: getState() :  mService = null. Returning STATE_OFF
,09-02 12:09:19.305  1037  1060 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7877 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 12:09:19.307  7112  7112 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:09:19.361  7877  7877 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 12:09:19.362  7877  7877 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:19.362  7877  7877 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 12:09:19.363  7877  7877 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 12:09:19.383  7877  7877 D BluetoothAdapterApp: Loading JNI Library
,09-02 12:09:19.416  7877  7877 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1c8ffc24 Instance Count = 1
,09-02 12:09:19.422  7877  7877 D BluetoothAdapterApp: onCreate
09-02 12:09:19.446  7877  7877 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 12:09:19.446  7877  7877 D ProfileConfigQcom: Adding HeadsetService
09-02 12:09:19.446  7877  7877 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 12:09:19.446  7877  7877 D ProfileConfigQcom: Adding A2dpService
09-02 12:09:19.446  7877  7877 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 12:09:19.447  7877  7877 D ProfileConfigQcom: Adding HidService
09-02 12:09:19.447  7877  7877 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-02 12:09:19.447  7877  7877 D ProfileConfigQcom: Adding HealthService
,09-02 12:09:19.447  7877  7877 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 12:09:19.448  7877  7877 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 12:09:19.448  7877  7877 D ProfileConfigQcom: Adding PanService
,09-02 12:09:19.449  7877  7877 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 12:09:19.449  7877  7877 D ProfileConfigQcom: Adding GattService
09-02 12:09:19.449  7877  7877 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 12:09:19.449  7877  7877 D ProfileConfigQcom: Adding BluetoothMapService
09-02 12:09:19.450  7877  7877 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 12:09:19.451  7877  7877 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:09:19.452  7877  7877 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:19.452  7877  7877 V BluetoothPbapReceiver: ***********state = 10
09-02 12:09:19.454  7877  7877 V LGMDMManagerInternal: Create singleton instance
09-02 12:09:19.561  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:09:19.567  7877  7877 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 12:09:19.568  7877  7877 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 12:09:19.569  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 12:09:19.569  1928  2109 D LGBluetoothAPIService: Message: 100
09-02 12:09:19.570  1928  2109 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 12:09:19.574  7112  7112 D BluetoothPermissionRequest: onReceive
09-02 12:09:19.575  7112  7112 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-02 12:09:19.576  7112  7112 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 12:09:19.576  7112  7112 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-02 12:09:19.579  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:09:19.584  7877  7877 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 12:09:19.590  7877  7877 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:19.594  7877  7877 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-02 12:09:19.594  7877  7877 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:19.594  7877  7877 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:19.596  7877  7877 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:19.596  7877  7877 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 12:09:19.600  7164  7164 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-02 12:09:21.027  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:21.027  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:09:21.244  1590  1590 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-02 12:09:21.278  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 12:09:21.305  1037  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 12:09:21.320   331   331 I art     : Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 20.482ms total 51.110ms
,09-02 12:09:21.347  1037  1111 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7905 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-02 12:09:21.353  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-02 12:09:21.354  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-02 12:09:21.391  1037  1037 D administrator: Handling package changes for user 0
,09-02 12:09:21.415  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 12:09:21.440  7905  7905 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 12:09:21.505  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-02 12:09:21.505  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 12:09:21.519  7905  7905 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:21.519  7905  7905 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:21.575  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:09:21.581  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-02 12:09:21.588  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 12:09:21.589  2495  2495 V GmsNetworkLocationProvi: DISABLE
,09-02 12:09:21.611  1037  1109 D LocationProviderProxy: applying state to connected service
09-02 12:09:21.612  2495  2495 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-02 12:09:21.627  7905  7949 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-02 12:09:21.627  7905  7949 I Babel   : MmsConfig.loadMmsSettings
09-02 12:09:21.631  7905  7949 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 12:09:21.632  7905  7949 I Babel   : MmsConfig.loadFromDatabase
,09-02 12:09:21.653  7905  7949 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-02 12:09:21.653  7905  7949 I Babel   : MmsConfig.loadFromResources
,09-02 12:09:21.654  7905  7949 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-02 12:09:21.655  7905  7949 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 12:09:21.658  7905  7905 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:09:21.674  7905  7948 W AudioCapabilities: Unsupported mime audio/evrc
09-02 12:09:21.675  7905  7948 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 12:09:21.677  7905  7948 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-02 12:09:21.679  1804  7952 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-02 12:09:21.679  1804  7952 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-02 12:09:21.683  7259  7259 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 12:09:21.689  7259  7259 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@13cb978e
09-02 12:09:21.689  7259  7259 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 12:09:21.689  7259  7259 D AppUp4:CustFacade: isPhone : true
09-02 12:09:21.690  7259  7259 D AppUp4:CustModeStarterReceiver: begin check event
09-02 12:09:21.690  7259  7259 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-02 12:09:21.690  1804  5287 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-02 12:09:21.701  7905  7948 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-02 12:09:21.702  7905  7948 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 12:09:21.706  7905  7948 W AudioCapabilities: Unsupported mime audio/evrc
09-02 12:09:21.712  7905  7948 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-02 12:09:21.713  7905  7948 W VideoCapabilities: Unsupported mime video/divx
09-02 12:09:21.715  7905  7948 W VideoCapabilities: Unsupported mime video/divx311
,09-02 12:09:21.717  7905  7948 W VideoCapabilities: Unsupported mime video/divx4
09-02 12:09:21.720  7905  7948 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-02 12:09:21.725  1037  1764 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7956 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-02 12:09:21.728  1037  1886 I ActivityManager: Killing 7134:com.lge.sync/1000 (adj 15): empty #17
,09-02 12:09:21.740  1037  1437 D WifiService: Client connection lost with reason: 4
,09-02 12:09:21.742  7905  7948 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 12:09:21.745  7905  7948 W AudioCapabilities: Unsupported mime audio/eac3
09-02 12:09:21.745  7905  7948 W AudioCapabilities: Unsupported mime audio/ac3
09-02 12:09:21.746  7905  7948 W AudioCapabilities: Unsupported mime audio/g726
09-02 12:09:21.747  7905  7948 W AudioCapabilities: Unsupported mime audio/wma-voice
09-02 12:09:21.747  7905  7948 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-02 12:09:21.748  7905  7948 W AudioCapabilities: Unsupported mime audio/adpcm
09-02 12:09:21.749  7905  7948 W VideoCapabilities: Unsupported mime video/theora
09-02 12:09:21.750  7905  7948 W VideoCapabilities: Unsupported mime video/mjpg
09-02 12:09:21.819  1037  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_7134/cgroup.procs: No such file or directory
,09-02 12:09:21.871  7956  7956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:21.872  7956  7956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:21.872  7956  7956 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 12:09:21.873  7956  7956 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-02 12:09:21.873  7956  7956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-02 12:09:21.953  7956  7956 I SystemConfig: BUILD Country: EU
09-02 12:09:21.953  7956  7956 I SystemConfig: BUILD Operator: OPEN
,09-02 12:09:21.999  1037  1060 I ActivityManager: Killing 7284:com.lge.email/u0a23 (adj 15): empty #17
,09-02 12:09:22.259  1037  1060 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7982 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-02 12:09:22.263  1037  2018 W libprocessgroup: failed to open /acct/uid_10023/pid_7284/cgroup.procs: No such file or directory
09-02 12:09:22.274  7956  7974 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-02 12:09:22.274  7956  7974 I SystemConfig: existFile = false
09-02 12:09:22.274  7956  7974 I SystemConfig: canReadFile = false
09-02 12:09:22.274  7956  7974 I SystemConfig: systemFeature RCS result false
09-02 12:09:22.275  7956  7974 D SystemConfig: refreshRcsSupport() :false
,09-02 12:09:22.331  7982  7982 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:22.331  7982  7982 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 12:09:22.331  7982  7982 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 12:09:22.332  7982  7982 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 12:09:22.448  7982  7982 I AppConfig: Total System Memory = 2995761152
,09-02 12:09:22.461  7982  7982 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-02 12:09:22.557  1037  1962 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8001 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:09:22.559  1037  1962 I ActivityManager: Killing 7181:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-02 12:09:22.649  1037  1764 W libprocessgroup: failed to open /acct/uid_10026/pid_7181/cgroup.procs: No such file or directory
,09-02 12:09:22.810  8001  8001 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-02 12:09:22.881  8001  8001 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:22.882  8001  8001 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:22.947  8001  8001 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-02 12:09:22.969  8001  8001 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 12:09:22.971  8001  8001 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-02 12:09:22.990  8001  8001 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-02 12:09:22.990  8001  8001 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-02 12:09:23.012  1037  2019 I ActivityManager: Killing 6570:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-02 12:09:23.050  1037  2018 W libprocessgroup: failed to open /acct/uid_1000/pid_6570/cgroup.procs: No such file or directory
,09-02 12:09:23.057  3432  6288 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-02 12:09:23.061  3432  6288 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c88604c on behalf of 8001
09-02 12:09:23.065  5114  8038 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-02 12:09:23.107  1037  1764 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8039 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-02 12:09:23.152  8001  8001 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-02 12:09:23.178  8001  8001 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-02 12:09:23.209  8039  8039 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-02 12:09:23.247  8039  8039 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-02 12:09:23.248  8039  8039 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,09-02 12:09:23.248  8039  8039 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-02 12:09:23.248  8039  8039 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-02 12:09:23.248  8039  8039 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-02 12:09:23.248  8039  8039 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-02 12:09:23.264  1037  1919 I ActivityManager: Killing 7322:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-02 12:09:23.280  1037  1687 W libprocessgroup: failed to open /acct/uid_10046/pid_7322/cgroup.procs: No such file or directory
,09-02 12:09:23.455  1037  1919 I art     : Explicit concurrent mark sweep GC freed 35441(1654KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.441ms total 136.297ms
,09-02 12:09:23.504  7805  7853 D UEI.SmartControl: Internal timer expired: 1
09-02 12:09:23.504  7805  7853 D UEI.SmartControl: unbind internal service
,09-02 12:09:23.518  7805  7805 D UEI.SmartControl: Service.onUnbind: IControl
,09-02 12:09:23.520  7805  7805 D UEI.SmartControl: Service.onDestroy
09-02 12:09:23.520  7805  7805 D UEI.SmartControl: Lock is in USE false
09-02 12:09:23.520  7805  7805 D UEI.SmartControl: unbind internal service
09-02 12:09:23.529  7805  7805 D serial_port: close(fd = 25)
09-02 12:09:23.532  7805  7805 I UEI.SmartControl: Serial port is closed.
09-02 12:09:23.532  7805  7805 I UEI.SmartControl: Serial port is closed.
09-02 12:09:23.532  7805  7805 D UEI.SmartControl: Blaster closed
09-02 12:09:23.533  7805  7805 D UEI.SmartControl: Shut down QS...
09-02 12:09:23.533  7805  7805 D UEI.SmartControl: Stopping QS lib
09-02 12:09:23.533  7805  7805 D UEI.SmartControl: QS lib stop result = true
09-02 12:09:23.533  7805  7805 D UEI.SmartControl: Stopped QS lib
09-02 12:09:23.534  7805  7805 D UEI.SmartControl: Stopped file observer...
09-02 12:09:23.534  7805  7805 D UEI.SmartControl: QS shutdown complete
,09-02 12:09:23.616  1037  2019 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:09:23.642  5114  8038 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 577 ms] updated apps [took 577 ms] 
,09-02 12:09:24.045  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:09:24.045  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@325f50f0 added. We now have 6 listener(s)
09-02 12:09:24.046  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:09:24.060  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:24.060  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dec669 added. We now have 7 listener(s)
09-02 12:09:24.060  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:24.061  6984  7045 I System.out: IsBluetoothEnabled
09-02 12:09:24.063  1037  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:24.063  1037  1962 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-02 12:09:24.063  1037  1119 D BluetoothManagerService: Message: 2
,09-02 12:09:24.069  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:24.069  1037  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:24.069  1037  1060 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 12:09:24.091  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:09:24.091  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:24.091  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:24.092  1037  1119 D BluetoothManagerService: Message: 1
09-02 12:09:24.092  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 12:09:24.117  1037  1119 D BluetoothManagerService: Message: 20
09-02 12:09:24.117  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aba770c:true
,09-02 12:09:24.121  7877  7877 D BluetoothAdapterState: make
09-02 12:09:24.126  7877  7877 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 12:09:24.126  7877  7877 I bluedroid-qcom: init
09-02 12:09:24.127  7877  8084 I BluetoothAdapterState: Entering OffState
09-02 12:09:24.128  7877  7877 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 12:09:24.128  7877  7877 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 12:09:24.128  7877  7877 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:09:24.128  7877  7877 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 12:09:24.128  7877  7877 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 12:09:24.130  7877  7877 I bluedroid-qcom: get_profile_interface socket
09-02 12:09:24.130  7877  7877 I bluedroid-qcom: get_profile_interface map_client
,09-02 12:09:24.134  7877  8088 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 12:09:24.119  8087  8087 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:24.140  7877  8088 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 12:09:24.129  8087  8087 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:24.150  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-02 12:09:24.152  1037  1119 D BluetoothManagerService: Message: 40
09-02 12:09:24.152  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 12:09:24.153  7877  7892 I bluedroid-qcom: config_hci_snoop_log
09-02 12:09:24.155  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 12:09:24.155  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 12:09:24.157  8087  8087 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 12:09:24.157  8087  8087 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 12:09:24.157  8087  8087 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 12:09:24.160  8087  8087 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 12:09:24.164  8087  8087 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 12:09:24.164  8087  8087 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-02 12:09:24.169  7877  8084 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 12:09:24.171  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:09:24.171  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:09:24.171  7877  8088 D BluetoothAdapterProperties: Name is: G3
09-02 12:09:24.172  7877  8084 D BluetoothAdapterProperties: Setting state to 11
09-02 12:09:24.172  7877  8084 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 12:09:24.173  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:24.173  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 12:09:24.173  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 12:09:24.174  7877  8084 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 12:09:24.181  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:24.184  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:24.186  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:24.190  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-02 12:09:24.196  7877  7877 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:09:24.196  7877  7877 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:24.196  7877  7877 V BluetoothPbapReceiver: ***********state = 11
,09-02 12:09:24.214  7877  8084 D BluetoothBondStateMachine: make
,09-02 12:09:24.218  7877  8084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.218  7877  8084 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 12:09:24.218  7877  8084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.218  7877  8084 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 12:09:24.219  7877  8084 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 12:09:24.219  7877  8101 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 12:09:24.220  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:09:24.222  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:24.227  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:09:24.228  7877  7877 D HeadsetService: Received start request. Starting profile...
09-02 12:09:24.229  7877  7877 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:09:24.229  7877  7877 D LGBluetoothHfpAdapter: Version 1.6
09-02 12:09:24.232  7877  7877 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 12:09:24.233  7877  7877 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:09:24.234  7877  7877 D HeadsetStateMachine: make
09-02 12:09:24.237  7112  7112 D BluetoothPermissionRequest: onReceive
09-02 12:09:24.239  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:24.242  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 12:09:24.249  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:24.253  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 12:09:24.256  7877  7877 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:24.256  7877  7877 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:09:24.259  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:24.259  7877  7877 D HeadsetStateMachine: max_hf_connections = 1
09-02 12:09:24.259  7877  7877 I bluedroid-qcom: get_profile_interface handsfree
09-02 12:09:24.260  7877  7877 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 12:09:24.261   311  1384 V AudioPolicyService: registerClient() client 0xb14271e0, uid 1002
09-02 12:09:24.261   311   311 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:09:24.261   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:09:24.261   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:09:24.261  7877  7877 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:09:24.261   311  1535 V AudioFlinger: registerClient() client 0xb5581628, pid 7877
09-02 12:09:24.262   311  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:24.262   311  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:24.262  7877  7877 V ToneGenerator: Create Track: 0xb4928080
09-02 12:09:24.262  7877  7877 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 12:09:24.262  7877  7877 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 12:09:24.262  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:24.262  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:24.262   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:09:24.262   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 12:09:24.262   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:09:24.262   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:09:24.262  7877  7877 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 12:09:24.262  1590  1611 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:24.262  1590  1611 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:24.262   311   311 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 12:09:24.263   311  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 12:09:24.263   311  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 12:09:24.263   311  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 12:09:24.263   311  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 12:09:24.263  1037  1764 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:24.263  1037  1764 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:24.263   311  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:24.263   311  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:24.263  1839  3485 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:24.263  1839  3485 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:24.263  3310  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:24.263  3310  3327 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 12:09:24.263  3310  3327 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:24.263  3310  3327 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:24.263  1590  1609 V ,AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:24.263  1590  1609 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:24.263  7877  7893 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 12:09:24.263  7877  7893 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 12:09:24.264  7877  7893 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:24.264  1037  2019 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 12:09:24.264  7877  7893 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 12:09:24.264  1037  2019 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 12:09:24.264  7877  7877 V AudioSystem: getLatency() output 2, latency 50
09-02 12:09:24.264  7877  7877 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 12:09:24.264  7877  7877 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 12:09:24.264   311  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,09-02 12:09:24.264   311  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:09:24.264   311  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 12:09:24.264   311  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 12:09:24.264   311  1384 V AudioFlinger: createTrack() lSessionId: 21
09-02 12:09:24.265  7877  7877 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 12:09:24.266   311   311 V AudioFlinger: acquiring 21 from 7877, for 7877
09-02 12:09:24.266   311   311 V AudioFlinger:  added new entry for 21
09-02 12:09:24.266  7877  7877 V ToneGenerator: ToneGenerator INIT OK, time: 205568
,09-02 12:09:24.266  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.266  7877  8105 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 12:09:24.266  7877  8105 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 12:09:24.267  7877  8105 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 12:09:24.267  7877  8105 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 12:09:24.267   311   311 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7877
09-02 12:09:24.267  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
,09-02 12:09:24.268   311   311 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 12:09:24.268   311   311 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 12:09:24.268   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 12:09:24.268   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 12:09:24.268   311   311 V voice   : voice_set_parameters: exit with code(0)
09-02 12:09:24.268   311   311 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 12:09:24.268   311   311 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 12:09:24.268   311   311 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 12:09:24.268   311   311 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,09-02 12:09:24.268   311   311 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 12:09:24.268   311   311 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 12:09:24.268  7877  8105 V ToneGenerator: ToneGenerator destructor
09-02 12:09:24.268  7877  8105 V ToneGenerator: stopTone
09-02 12:09:24.268  7877  8105 V ToneGenerator: Delete Track: 0xb4928080
,09-02 12:09:24.270  7877  7877 D A2dpService: Received start request. Starting profile...
09-02 12:09:24.271  7877  8105 V AudioTrack: ~AudioTrack, releasing session id from 7877 on behalf of 7877
09-02 12:09:24.271  7877  7877 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 12:09:24.271   311  1535 V AudioFlinger: releasing 21 from 7877 for 7877
09-02 12:09:24.271   311  1535 V AudioFlinger:  decremented refcount to 0
09-02 12:09:24.271   311  1535 V AudioFlinger: purging stale effects
09-02 12:09:24.271   311  1535 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 12:09:24.271   311  1535 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 12:09:24.271   311  1274 V AudioPolicyService: AudioCommandThread() waking up
09-02 12:09:24.271   311  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 12:09:24.271   311  1274 V AudioPolicyManager: releaseOutput() 2
09-02 12:09:24.271   311  1274 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 12:09:24.271   311  1535 V AudioFlinger: PlaybackThread::Track destructor
09-02 12:09:24.271   311  1535 V AudioFlinger: removeClient_l() pid 7877, calling pid 311
09-02 12:09:24.271  7877  7877 V Avrcp   : make
09-02 12:09:24.272  7877  7877 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 12:09:24.272  7877  7877 I bluedroid-qcom: get_profile_interface avrcp
09-02 12:09:24.274  7877  8084 E BluetoothAdapterService: File transfer profiles supported!!
09-02 12:09:24.280  7877  7877 V AudioManager: registerRemoteController: size of Media player list: 0
,09-02 12:09:24.281  7877  7877 E AudioManager: No RCC entry present to update
09-02 12:09:24.281  7877  7877 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 12:09:24.285  7877  7877 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 12:09:24.287  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 12:09:24.287  7877  7877 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 12:09:24.289  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 12:09:24.293  7877  8084 V LGMDMManager: Create singleton instance
09-02 12:09:24.294  7877  8084 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 12:09:24.389  1037  1962 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:09:24.390  1037  1962 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:09:24.521  1037  1687 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 12:09:24.532  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 12:09:24.536  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-02 12:09:24.537  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 12:09:24.537  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 12:09:24.537  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 12:09:24.538  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:09:24.538  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 12:09:24.538  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 12:09:24.538  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 12:09:24.538  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:09:24.538  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 12:09:24.539  7877  7877 I BluetoothA2dpServiceJni: classInitNative
09-02 12:09:24.539  7877  7877 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:09:24.539  7877  7877 D A2dpStateMachine: make
09-02 12:09:24.543  7877  7877 I bluedroid-qcom: get_profile_interface a2dp
,09-02 12:09:24.543  7877  8112 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 12:09:24.548  7877  7877 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:09:24.548  7877  7877 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 12:09:24.552  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.554  7877  8111 D A2dpStateMachine: Enter Disconnected: -2
,09-02 12:09:24.560  7877  7877 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 12:09:24.562  7877  7877 D HidService: Received start request. Starting profile...
09-02 12:09:24.562  7877  7877 I bluedroid-qcom: get_profile_interface hidhost
09-02 12:09:24.562  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.563  7877  7877 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:09:24.565  7877  7877 D HealthService: Received start request. Starting profile...
09-02 12:09:24.569  7877  7877 I bluedroid-qcom: get_profile_interface health
09-02 12:09:24.569  7877  7877 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:09:24.569  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.571  7877  7877 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 12:09:24.573  7877  7877 D PanService: Received start request. Starting profile...
09-02 12:09:24.573  7877  7877 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:09:24.573  7877  7877 I bluedroid-qcom: get_profile_interface pan
,09-02 12:09:24.582  7877  7877 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 12:09:24.582  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.582  7877  7877 D HeadsetStateMachine: Proxy object connected
09-02 12:09:24.583  7877  7877 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 12:09:24.583  7877  7877 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 12:09:24.586  7877  7877 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-02 12:09:24.593  7877  7877 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:09:24.593  7877  7877 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:09:24.593  7877  7877 D BtGatt.GattService: start()
09-02 12:09:24.593  7877  7877 I bluedroid-qcom: get_profile_interface gatt
09-02 12:09:24.594  7877  7877 D BtGatt.AdvertiseManager: advertise manager created
09-02 12:09:24.605  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
,09-02 12:09:24.615  7877  7877 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 12:09:24.616  7877  8105 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 12:09:24.618  7877  8105 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 12:09:24.619  7877  8105 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 12:09:24.619  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:24.620  7877  7877 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 12:09:24.623  7877  7877 V BluetoothMapService: BluetoothMapBinder()
09-02 12:09:24.624  7877  7877 D BluetoothMapService: Received start request. Starting profile...
09-02 12:09:24.624  7877  7877 D BluetoothMapService: start()
,09-02 12:09:24.634  7877  7877 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-02 12:09:24.634  7877  7877 D BluetoothMapEmailAppObserver: createReceiver()
,09-02 12:09:24.637  7877  7877 D BluetoothMapEmailAppObserver: initObservers()
09-02 12:09:24.637  7877  7877 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-02 12:09:24.660  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
,09-02 12:09:24.665  7877  7877 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:24.667  7877  7877 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:24.671  7877  7877 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:24.676  7877  7877 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 12:09:24.681  7877  7877 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 12:09:24.681  7877  7877 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 12:09:24.685  7877  7877 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 12:09:24.685  7877  7877 V BluetoothMapService: Handler(): got msg=1
09-02 12:09:24.689  7877  7877 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-02 12:09:24.689  7877  7877 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-02 12:09:24.689  7877  7877 V BluetoothSapReceiver: SapReceiver onReceive 
,09-02 12:09:24.692  7877  7877 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:24.692  7877  7877 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-02 12:09:24.693  7877  8084 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,09-02 12:09:24.693  7877  8084 I bluedroid-qcom: enable
09-02 12:09:24.694  7877  8084 I bt_hci_bdroid: init
09-02 12:09:24.697  7877  8125 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-02 12:09:24.697  7877  8125 I bt-btu  : btu_task pending for preload complete event
09-02 12:09:24.698  7877  8084 I bt_vendor: bt-vendor : init
09-02 12:09:24.698  7877  8084 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 12:09:24.698  7877  8084 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 12:09:24.698  7877  8084 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 12:09:24.698  7877  8084 D bt_userial_mct: userial_init
09-02 12:09:24.699  7877  8084 D bt_hci_bdroid: set_power 1
09-02 12:09:24.699  7877  8084 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 12:09:24.699  7877  8084 I bt_vendor: Starting hciattach daemon
09-02 12:09:24.699  7877  8084 I bt_vendor: try to set true
09-02 12:09:24.689  8128  8128 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:24.689  8128  8128 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:09:24.727  8133  8133 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-02 12:09:24.812  8141  8141 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 12:09:24.825  8142  8142 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:09:24.851  8144  8144 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:09:24.865  8145  8145 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-02 12:09:24.879  8146  8146 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:09:24.904  8147  8147 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-02 12:09:24.933  8149  8149 I libmdmdetect: ESOC framework not supported
09-02 12:09:24.936  8149  8149 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 12:09:24.947  8149  8149 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-02 12:09:24.947  8149  8149 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 12:09:24.948  8149  8149 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 12:09:24.948  8149  8149 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 12:09:24.948  8149  8149 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-02 12:09:24.948  8149  8149 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,09-02 12:09:24.948  8149  8149 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 12:09:24.994  8149  8150 E QC-QMI  : qmi_client [8149] 15: failed to locate client data
,09-02 12:09:24.995   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 12:09:24.996   469   469 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-02 12:09:25.046  8154  8154 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 12:09:25.070  8155  8155 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 12:09:25.103  7877  8084 I bt_vendor: bluetooth satus is on
09-02 12:09:25.103  7877  8084 D bt_hci_bdroid: preload
09-02 12:09:25.103  7877  8127 D bt_userial_mct: userial_open(port:0)
09-02 12:09:25.103  7877  8127 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 12:09:25.107  7877  8127 I bt_vendor: Done intiailizing UART
09-02 12:09:25.108  7877  8127 I bt_vendor: Done intiailizing UART
09-02 12:09:25.108  7877  8127 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 12:09:25.109  7877  8127 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 12:09:25.109  7877  8125 I bt-btu  : btu_task received preload complete event
09-02 12:09:25.109  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 12:09:25.109  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 12:09:25.112  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 12:09:25.112  7877  8157 D bt_userial_mct: Entering userial_read_thread()
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_GAP
,09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:09:25.118  7877  8125 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 12:09:25.193  7877  8125 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 12:09:25.193  7877  8125 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021d061 
09-02 12:09:25.193  7877  8125 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021d061 
,09-02 12:09:25.210  7877  8088 E bt-btif : Calling BTA_HhEnable
09-02 12:09:25.210  7877  8088 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 12:09:25.210  7877  8088 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 12:09:25.214  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 12:09:25.214  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 12:09:25.214  7877  8088 D BluetoothAdapterProperties: Name is: G3
09-02 12:09:25.216  7877  8088 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:09:25.216  7877  8088 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:09:25.216  7877  8088 D bt_hci_bdroid: postload
09-02 12:09:25.217  7877  8088 D bte_conf: Device ID record 1 : primary
09-02 12:09:25.217  7877  8088 D bte_conf:   vendorId            = 00c4
09-02 12:09:25.217  7877  8088 D bte_conf:   vendorIdSource      = 0001
09-02 12:09:25.217  7877  8088 D bte_conf:   product             = 13a1
09-02 12:09:25.217  7877  8088 D bte_conf:   version             = 1000
09-02 12:09:25.217  7877  8088 D bte_conf:   clientExecutableURL = 
09-02 12:09:25.217  7877  8088 D bte_conf:   serviceDescription  = 
09-02 12:09:25.217  7877  8088 D bte_conf:   documentationURL    = 
09-02 12:09:25.218  7877  8088 D bte_conf: bte_load_did_conf no section named DID2.
09-02 12:09:25.224  7877  8084 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 12:09:25.224  7877  8084 D BluetoothAdapterProperties: ScanMode =  20
,09-02 12:09:25.229  7877  8084 D BluetoothAdapterProperties: State =  11
09-02 12:09:25.230  7877  8084 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 12:09:25.230  7877  8084 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 12:09:25.230  7877  8084 D BluetoothAdapterProperties: Setting state to 12
09-02 12:09:25.230  7877  8084 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:09:25.231  7877  8088 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 12:09:25.219  8162  8162 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:25.219  8162  8162 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:25.240  1037  1119 D BluetoothManagerService: Message: 60
09-02 12:09:25.240  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 12:09:25.240  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-02 12:09:25.245  7877  8084 I BluetoothAdapterState: Entering On State
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:25.268  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:09:25.272  1839  2440 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:09:25.274  7877  8084 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 12:09:25.274  7877  8084 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 12:09:25.274  7877  8084 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 12:09:25.278  7877  8084 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 12:09:25.279  7877  8088 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:09:25.279  7877  8088 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 12:09:25.283  7877  8127 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 12:09:25.283  7877  8127 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 12:09:25.291  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:25.297  7877  8084 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-02 12:09:25.300  7877  8157 E bt_mct  : hci lib postload completed
09-02 12:09:25.302  1839  1839 D BluetoothHeadset: Proxy object connected
09-02 12:09:25.303  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:09:25.308  1037  1037 D BluetoothHeadset: Proxy object connected
09-02 12:09:25.311  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 12:09:25.311  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 12:09:25.311  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,09-02 12:09:25.314  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 12:09:25.314  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 12:09:25.314  7877  8125 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 12:09:25.317  7877  8088 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 12:09:25.346  7877  8125 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:25.346  7877  8125 W bt-smp  : Plain text(LSB ~ MSB) = 55 ed 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:25.346  7877  8125 W bt-smp  : Encrypted text(LSB ~ MSB) = c2 30 7c 70 2c fb 4f b9 b2 3c 8f a2 c7 5f 52 b2 
09-02 12:09:25.346  7877  8125 W bt-btm  : Stopping oneshot timer
,09-02 12:09:25.350  8167  8167 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-02 12:09:25.356  7112  7128 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:09:25.359  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:09:25.363  1839  1839 D BluetoothHeadset: Proxy object connected
,09-02 12:09:25.364  7877  8125 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:25.364  7877  8125 W bt-smp  : Plain text(LSB ~ MSB) = 0f e5 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:25.364  7877  8125 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 c8 d6 63 e2 15 2d d5 a6 cb 20 5b 15 68 7e e3 
09-02 12:09:25.364  7877  8125 W bt-btm  : Stopping oneshot timer
09-02 12:09:25.365  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:09:25.367  1037  1037 D BluetoothA2dp: Proxy object connected
09-02 12:09:25.373  7112  7202 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:09:25.384  7112  7112 D BluetoothA2dp: Proxy object connected
09-02 12:09:25.384  7112  7112 D A2dpProfile: Bluetooth service connected
09-02 12:09:25.384  7112  7128 D BluetoothMap: onBluetoothStateChange: up=true
09-02 12:09:25.388  1839  3484 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:09:25.391  1839  1839 D BluetoothHeadset: Proxy object connected
09-02 12:09:25.392  7112  7112 D BluetoothMap: Proxy object connected
09-02 12:09:25.392  7112  7112 D MapProfile: Bluetooth service connected
09-02 12:09:25.392  7112  7112 D BluetoothMap: getConnectedDevices()
09-02 12:09:25.392  7877  8125 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:25.392  7877  8125 W bt-smp  : Plain text(LSB ~ MSB) = 27 f1 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:25.392  7877  8125 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b a6 83 2e e9 0a 4e 82 3c e9 fd f1 84 7d 50 a7 
09-02 12:09:25.392  7877  8125 W bt-btm  : Stopping oneshot timer
09-02 12:09:25.393  7112  7128 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:09:25.394  7877  7892 V BluetoothMapService: getConnectedDevices()
09-02 12:09:25.396  7112  7112 D BluetoothHeadset: Proxy object connected
09-02 12:09:25.396  7112  7112 D HeadsetProfile: Bluetooth service connected
09-02 12:09:25.396  7112  7202 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:09:25.396  7112  7202 D BluetoothPan: onBluetoothStateChange call bindService
09-02 12:09:25.402  7112  7129 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 12:09:25.404  7112  7112 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:09:25.404  7112  7112 D PanProfile: Bluetooth service connected
09-02 12:09:25.405  7877  8125 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:25.405  7877  8125 W bt-smp  : Plain text(LSB ~ MSB) = 17 70 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:25.405  7877  8125 W bt-smp  : Encrypted text(LSB ~ MSB) = c9 9d f9 c9 7b 5e a3 b5 43 0c 94 c4 6c 3d 0e 4b 
09-02 12:09:25.405  7877  8125 W bt-btm  : Stopping oneshot timer
09-02 12:09:25.409  7112  7112 D BluetoothInputDevice: Proxy object connected
09-02 12:09:25.409  7112  7112 D HidProfile: Bluetooth service connected
09-02 12:09:25.412  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 12:09:25.412  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 12:09:25.412  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 12:09:25.414  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 12:09:25.417  7877  8125 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 12:09:25.417  7877  8125 W bt-smp  : Plain text(LSB ~ MSB) = 5d ab 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 12:09:25.417  7877  8125 W bt-smp  : Encrypted text(LSB ~ MSB) = c5 ea c9 62 aa c6 8a 3d 78 42 be 49 13 e8 ff 9e 
09-02 12:09:25.417  7877  8125 W bt-btm  : Stopping oneshot timer
09-02 12:09:25.418  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:09:25.422  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:25.422  1928  2109 D LGBluetoothAPIService: Message: 1
09-02 12:09:25.422  1928  2109 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 12:09:25.422  1928  2109 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-02 12:09:25.422  1928  2109 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 12:09:25.423  1037  1119 D BluetoothManagerService: Message: 40
09-02 12:09:25.423  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 12:09:25.425  7877  7877 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.425  7877  7877 D BluetoothMapService: STATE_ON
09-02 12:09:25.426  7112  7112 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 12:09:25.428  7112  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 12:09:25.435  7112  7112 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:09:25.444  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:25.444  7877  7877 V BluetoothPbapService: Pbap Service onCreate
09-02 12:09:25.444  7877  7877 V BluetoothPbapService: Starting PBAP service
09-02 12:09:25.445  7877  7877 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 12:09:25.445  7877  7877 V BluetoothPbapService: Pbap Service onBind
09-02 12:09:25.446  7877  7877 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.446  7877  7877 V BluetoothPbapService: state: 12
09-02 12:09:25.446  7877  7877 V BluetoothMapService: Handler(): got msg=1
09-02 12:09:25.447  7112  7112 D BluetoothPbap: Proxy object connected
09-02 12:09:25.447  7112  7112 D PbapServerProfile: Bluetooth service connected
09-02 12:09:25.447  7877  7877 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 12:09:25.447  7877  7877 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 12:09:25.447  7877  7877 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.447  7877  7877 V BluetoothPbapReceiver: ***********state = 12
,09-02 12:09:25.448  7877  8185 D BluetoothMapMasInstance: MAS initSocket()
09-02 12:09:25.448  7877  8185 D BluetoothMapMasInstance:   masId = 00
09-02 12:09:25.448  7877  8185 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 12:09:25.448  7877  8185 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 12:09:25.448  7877  8185 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 12:09:25.450  1037  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:25.450  7877  7877 V BluetoothPbapService: Handler(): got msg=1
09-02 12:09:25.451  7877  7877 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 12:09:25.451  7877  8185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:25.452  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:09:25.452  2214  2214 D c       : Getting all permits...
09-02 12:09:25.452  2214  2214 D a       : Opening database...
09-02 12:09:25.452  7877  8186 V BluetoothPbapService: Pbap Service initSocket
09-02 12:09:25.453  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:25.453  7877  8186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:25.454  2214  2214 D a       : Opening database auth.proximity.permit_store...
09-02 12:09:25.455  7877  8088 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:09:25.455  2214  2214 D a       : Closing database...
09-02 12:09:25.455  7877  8088 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 12:09:25.456  7877  8186 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 12:09:25.456  7877  8186 V BluetoothPbapService: Succeed to create listening socket 
09-02 12:09:25.456  7877  8186 V BluetoothPbapService: Accepting socket connection...
09-02 12:09:25.456  7877  8185 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 12:09:25.456  7877  8185 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 12:09:25.456  7877  8185 D BluetoothMapMasInstance: Accepting socket connection...
09-02 12:09:25.457  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:25.466  7112  7112 D BluetoothPermissionRequest: onReceive
,09-02 12:09:25.468  7112  7112 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 12:09:25.470  7112  7112 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 12:09:25.473  7877  7877 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 12:09:25.474  7877  7877 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 12:09:25.479  7877  7877 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 12:09:25.501  7877  7877 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 12:09:25.501  7877  7877 V BtOppService: onCreate
09-02 12:09:25.505  7877  7877 V BluetoothOppNotification: send message
09-02 12:09:25.509  7877  7877 V BtOppService: Starting RfcommListener
09-02 12:09:25.516  7877  7877 D BluetoothOppPreference: Dumping Names:  
09-02 12:09:25.516  7877  7877 D BluetoothOppPreference: {}
09-02 12:09:25.516  7877  7877 D BluetoothOppPreference: Dumping Channels:  
09-02 12:09:25.516  7877  7877 D BluetoothOppPreference: {}
09-02 12:09:25.518  7877  7877 V BtOppService: onStartCommand
,09-02 12:09:25.526  7877  7877 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.526  7877  8194 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:25.527  7877  7877 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 12:09:25.529  7877  8194 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:09:25.529  7877  8191 V BtOppService: Deleted complete outbound shares, number =  0
09-02 12:09:25.531  7877  8194 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@90ae911 on behalf of 
09-02 12:09:25.533  7877  8191 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 12:09:25.533  7877  8191 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,09-02 12:09:25.535  7877  7877 V BluetoothOppNotification: new notify threadi!
09-02 12:09:25.537  7877  7877 V BluetoothOppNotification: send delay message
09-02 12:09:25.538  7877  8191 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ce9a76 on behalf of 
09-02 12:09:25.538  7877  8194 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:09:25.539  7877  7877 V BtOppService: start RfcommListener
09-02 12:09:25.540  7877  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:09:25.544  7877  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@384be877 on behalf of 
09-02 12:09:25.545  7877  8194 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-02 12:09:25.545  7877  8196 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 12:09:25.547  7877  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:25.548  7877  7877 V BtOppService: RfcommListener started
09-02 12:09:25.548  7877  7877 V BtOppService: ContentObserver received notification
09-02 12:09:25.549  7877  8197 V BtOppRfcommListener: Starting RFCOMM listener....
,09-02 12:09:25.550  1037  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:25.551  7877  8198 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:25.551  7877  8198 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:09:25.552  7877  8197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:25.552  7877  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c306ce4 on behalf of 
09-02 12:09:25.553  7877  8198 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e24054d on behalf of 
09-02 12:09:25.553  7877  8197 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-02 12:09:25.554  7877  8197 V BtOppRfcommListener: Started RFCOMM listener....
09-02 12:09:25.554  7877  8197 I BtOppRfcommListener: Accept thread started.
09-02 12:09:25.554  7877  8197 V BtOppRfcommListener: Accepting connection...
09-02 12:09:25.555  7877  8196 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 12:09:25.559  7877  8196 V BluetoothOppNotification: outbound notification was removed.
,09-02 12:09:25.559  7877  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:25.559  7877  8198 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:09:25.561  7877  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3581e802 on behalf of 
,09-02 12:09:25.562  7877  8196 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-02 12:09:25.566  7877  8196 V BluetoothOppNotification: inbound notification was removed.
,09-02 12:09:25.566  7877  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:09:25.568  7877  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@108c9513 on behalf of 
09-02 12:09:25.577  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
09-02 12:09:25.577  7877  7877 V BluetoothFtpService: Ftp Service onCreate
09-02 12:09:25.577  7877  7877 I BluetoothFtpService: Ftp Service onCreate
,09-02 12:09:25.577  7877  7877 V BluetoothFtpService: Ftp Service onStartCommand
09-02 12:09:25.577  7877  7877 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.577  7877  7877 V BluetoothFtpService: Starting Listening on sockets
09-02 12:09:25.577  7877  7877 V BtOppService: ContentObserver received notification
09-02 12:09:25.578  7877  7877 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 12:09:25.578  7877  7877 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 12:09:25.578  7877  7877 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 12:09:25.578  7877  7877 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.578  7877  7877 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 12:09:25.578  7877  7877 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 12:09:25.579  7877  8199 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 12:09:25.579  7877  8199 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 12:09:25.580  7877  8199 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b38a949 on behalf of 
09-02 12:09:25.581  7877  7877 V BluetoothFtpService: Handler(): got msg=1
09-02 12:09:25.581  7877  7877 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 12:09:25.581  7877  7877 V BluetoothFtpService: Ftp Service initSocket
09-02 12:09:25.584  1037  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:25.585  7877  8199 V BluetoothOppNotification: update too frequent, put in queue
09-02 12:09:25.586  7877  7877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:25.587  7877  8199 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 12:09:25.588  7877  7877 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 12:09:25.590  7877  8200 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-02 12:09:25.619  7877  7877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29989745
,09-02 12:09:25.620  7877  7877 V BluetoothSapService: Sap Service onCreate
,09-02 12:09:25.622  7877  7877 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:09:25.622  7877  7877 V BluetoothSapService: state: 12
09-02 12:09:25.622  7877  7877 V BluetoothSapService: Starting SAP server process
09-02 12:09:25.625  7877  7877 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 12:09:25.609  8201  8201 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:25.609  8201  8201 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:25.627  7877  8202 V BluetoothSapService: Sap Service initRfcommSocket
09-02 12:09:25.628  1037  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:25.629  7877  8202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:09:25.631  7877  8202 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-02 12:09:25.631  7877  8202 V BluetoothSapService: Succeed to create listening socket 
09-02 12:09:25.631  7877  8202 V BluetoothSapService: Accepting socket connection...
09-02 12:09:25.656  8201  8201 V BT_SAP  : Event pipe created
09-02 12:09:25.656  8201  8201 V BT_SAP  : create_server_socket qcom.sap.server
09-02 12:09:25.656  8201  8201 V BT_SAP  : created socket fd 6
,09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:26.130  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:09:26.141  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:26.143  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:26.143  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b84a8ee added. We now have 8 listener(s)
09-02 12:09:26.143  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:26.146  1037  2019 D WifiServiceImplEx: setWifiEnabled: false pid=6984, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:09:26.146  1037  2019 D WifiService: setWifiEnabled: false pid=6984, uid=10118
09-02 12:09:26.146  1037  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:09:26.153  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:26.157  1037  1873 D WifiServiceImplEx: setWifiEnabled: true pid=6984, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 12:09:26.158  1037  1873 D WifiService: setWifiEnabled: true pid=6984, uid=10118
09-02 12:09:26.159  1037  1873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:09:26.177  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 12:09:26.177  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 12:09:26.178  1037  1037 D Ulp_jni : JNI:system_update. Event-4
09-02 12:09:26.179  1037  1379 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 12:09:26.179  1037  1379 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 12:09:26.182  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 12:09:26.182  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:09:26.182  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 12:09:26.182  1037  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 12:09:26.182  1037  1379 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 12:09:26.182  1037  1379 E WifiHW  : unknown target_country: EU , set to default
09-02 12:09:26.182  1037  1379 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 12:09:26.182  1037  1379 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 12:09:26.182  1037  1379 I WifiUtil: gEnableBmps=1
09-02 12:09:26.539  7877  7877 V BluetoothOppNotification: new notify threadi!
,09-02 12:09:26.542  7877  7877 V BluetoothOppNotification: send delay message
09-02 12:09:26.544  7877  8215 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 12:09:26.581  7877  8215 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26d99105 on behalf of 
09-02 12:09:26.582  7877  8215 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-02 12:09:26.593  7877  8215 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:26.608  7877  8215 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b0755a on behalf of 
09-02 12:09:26.609  7877  8215 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-02 12:09:26.651  7877  8215 V BluetoothOppNotification: outbound notification was removed.
09-02 12:09:26.651  7877  8215 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 12:09:26.652  7877  8215 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337f938b on behalf of 
09-02 12:09:26.653  7877  8215 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 12:09:26.654  7877  8215 V BluetoothOppNotification: inbound notification was removed.
09-02 12:09:26.655  7877  8215 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 12:09:26.655  7877  8215 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34c85c68 on behalf of 
09-02 12:09:26.757   307   895 D SoftapController: Softap fwReload - Ok
,09-02 12:09:26.768  1037  1379 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (582ms)
09-02 12:09:26.778   307   895 D CommandListener: Setting iface cfg
09-02 12:09:26.778   307   895 D CommandListener: Trying to bring down wlan0
,09-02 12:09:26.782  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:09:26.791   307   895 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:09:26.808  1037  1379 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-02 12:09:26.799  8223  8223 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:26.819  8223  8223 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:09:26.833  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:26.833  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:26.833  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:26.840  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-02 12:09:26.849  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:26.850  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 12:09:26.861  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:26.872  1037  1379 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 12:09:26.873  1037  1379 D WifiMonitor: connecting to supplicant
,09-02 12:09:26.880  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:09:26.880  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:09:26.880  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:09:26.880  7112  7112 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:09:26.882  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:09:26.884  7112  7112 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:09:26.884  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 12:09:26.884  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:09:26.884  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:09:26.884  7112  7112 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:09:26.884  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 12:09:26.885  7112  7112 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:09:26.901  8223  8223 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 12:09:26.935  1037  1945 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8241 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 12:09:26.943  8223  8223 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 12:09:26.943  8223  8223 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 12:09:26.945  1037  1119 D Tethering: InitialState.processMessage what=4
09-02 12:09:26.946  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 12:09:27.006  8223  8223 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 12:09:27.047  1037  1981 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8262 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:09:27.051  8241  8260 W FormManager: Network not available. Please check & try again.
09-02 12:09:27.058  8241  8261 V FormManager: Network unavailable.
09-02 12:09:27.063  8241  8261 V FormManager: Network unavailable.
09-02 12:09:27.063   331   331 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 17.071ms
,09-02 12:09:27.078   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 14.053ms
,09-02 12:09:27.091   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 13.171ms
09-02 12:09:27.092  8223  8223 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-02 12:09:27.093  1037  1764 I ActivityManager: Killing 7345:com.android.chrome/u0a57 (adj 15): empty #17
09-02 12:09:27.097  8262  8262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:27.100  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-02 12:09:27.102  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:09:27.102  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 12:09:27.102  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 12:09:27.102  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:09:27.102  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 12:09:27.102  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 12:09:27.102  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:09:27.103  1037  1379 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 12:09:27.103  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.104  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.104  1037  1379 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.104  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.105  1037  1379 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 12:09:27.105  1037  1379 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 12:09:27.105  1037  1379 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 12:09:27.106  1037  1379 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 12:09:27.106  1037  1379 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 12:09:27.165  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:09:27.170  1037  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 12:09:27.170  1037  1379 E WifiStateMachine: useWiFiOffloading() : false
09-02 12:09:27.170  1037  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 12:09:27.172  1037  1379 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 12:09:27.173  1037  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_7345/cgroup.procs: No such file or directory
09-02 12:09:27.174  1037  1379 D WifiNative-wlan0: SET update_config 1: returned true
09-02 12:09:27.176  1037  1379 D WifiConfigStore: Loading config and enabling all networks 
09-02 12:09:27.176  1037  1379 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 12:09:27.178  1037  1379 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-02 12:09:27.182  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.182  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.183  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.183  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.183  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 12:09:27.183  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 12:09:27.186  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.187  1928  1928 D WfdService: Waiting for WifiP2p enabling
09-02 12:09:27.187  1037  1429 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 12:09:27.191  1037  1379 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 12:09:27.192  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:27.198  6984  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:27.201  6984  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:09:27.201  1037  1059 I ActivityManager: Killing 7366:com.lge.drmservice/u0a62 (adj 15): empty #17
09-02 12:09:27.202  1037  1379 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 12:09:27.202  1037  1379 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:09:27.203  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:09:27.206  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:09:27.217  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 12:09:27.218  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 12:09:27.222  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3298e3c0 Bundle[{}]
09-02 12:09:27.223  6984  7045 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 12:09:27.224  6984  7045 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 12:09:27.225  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-02 12:09:27.226  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 12:09:27.228  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 12:09:27.229  6984  7045 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-02 12:09:27.235  6984  7045 I System.out: Running OutgoingSocketThread
,09-02 12:09:27.237  6984  8284 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 921)
09-02 12:09:27.238  6984  8284 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43276
09-02 12:09:27.238  6984  8284 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-02 12:09:27.250  1037  1379 D WifiStateMachine: enableVerboseLogging : level 2
09-02 12:09:27.250  1037  1379 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-02 12:09:27.251  1037  2018 W libprocessgroup: failed to open /acct/uid_10062/pid_7366/cgroup.procs: No such file or directory
,09-02 12:09:27.252  1037  1379 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 12:09:27.252  1037  1379 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 12:09:27.252  1037  1379 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 12:09:27.253  1037  1379 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 12:09:27.253  1037  1379 D WifiNative-wlan0: SET model_name LG-D855: returned true
,09-02 12:09:27.253  1037  1379 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 12:09:27.254  1037  1379 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 12:09:27.254  1037  1379 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 12:09:27.254  1037  1379 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 12:09:27.254  1037  1379 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-02 12:09:27.255  1037  1379 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 12:09:27.255  1037  1379 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 12:09:27.255  1037  1379 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 12:09:27.256  1037  1379 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:09:27.256  1037  1379 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 12:09:27.257  1037  1379 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 12:09:27.257  1037  1379 D WifiNative-HAL: Setting external_sim to 1
09-02 12:09:27.257  1037  1379 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 12:09:27.257  7905  7905 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.257  1928  1928 D WfdsService: Supplicant Connection state is changed : true
09-02 12:09:27.258  1037  1379 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 12:09:27.258  1037  1379 I WifiNative-HAL: startHal
09-02 12:09:27.258  1037  1379 D wifi    : setting scan oui 0xaf765440
09-02 12:09:27.258  1928  2282 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 12:09:27.259  1928  2282 D WfdsService: Set the WFDS Monitor: true
09-02 12:09:27.259  1928  2282 D WfdsMonitor: WfdsMonitorThread create
09-02 12:09:27.259  1037  1379 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:09:27.259  1037  1379 I WifiNative-HAL: startHal
09-02 12:09:27.259  1037  1379 D wifi    : setting scan oui 0xaf765440
09-02 12:09:27.259  1928  2282 D WfdsMonitor: WFDS Monitor is created and started
09-02 12:09:27.259  1928  2282 D WfdsService: WiFi: Supplicant connection re-established
09-02 12:09:27.259  1037  1379 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 12:09:27.260  1037  1379 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 12:09:27.260  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 12:09:27.260  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 12:09:27.260  1928  8285 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 12:09:27.260  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 12:09:27.261  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:09:27.261  1928  8285 E CtrlSupplicant: Succeed to open control connection
09-02 12:09:27.261  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:09:27.261  1928  8285 E CtrlSupplicant: Succeed to open monitor connection
09-02 12:09:27.261  1928  8285 D WfdsMonitor: Supplicant connection established
09-02 12:09:27.261  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:09:27.261  1928  2282 D WfdsService: Connected to the supplicant for wfds
09-02 12:09:27.261  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 12:09:27.262  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 12:09:27.262  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 12:09:27.262  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:09:27.262  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:09:27.262  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:09:27.262  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 12:09:27.263  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 12:09:27.263  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 12:09:27.263  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 12:09:27.263  8223  8223 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 12:09:27.264  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 12:09:27.264  1037  1379 D Wifi,Native-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 12:09:27.264  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 12:09:27.264  1037  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 12:09:27.265  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:09:27.265  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:09:27.265  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:09:27.265  7112  7112 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:09:27.265  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:09:27.265  1037  1379 E WifiNative: : [208,553,914 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 12:09:27.265  1037  1379 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 12:09:27.266  7112  7112 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:09:27.266  1037  1379 D WifiNative-wlan0: RECONNECT: returned true
09-02 12:09:27.266  1037  1379 D WifiNative-wlan0: doString: [STATUS]
09-02 12:09:27.266  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 12:09:27.266  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:09:27.266  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:09:27.266  7112  7112 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:09:27.266  7112  7112 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:09:27.267  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:09:27.267  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 12:09:27.267  1037  1379 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:09:27.267  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:27.268  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:27.268  1037  1377 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.271   307   895 D CommandListener: Setting iface cfg
09-02 12:09:27.271   307   895 D CommandListener: Trying to bring up p2p0
,09-02 12:09:27.274  1037  1379 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 12:09:27.274  1037  1377 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:09:27.274  1037  1377 D LGWifiP2pService: P2pEnablingState
09-02 12:09:27.274  1037  1379 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 12:09:27.274  1037  1377 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.275  1037  1377 D LGWifiP2pService: P2p socket connection successful
09-02 12:09:27.275  1037  1377 D LGWifiP2pService: P2pEnabledState
09-02 12:09:27.276  1037  1379 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 12:09:27.276  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 12:09:27.276  1037  1037 D RttService: SCAN_AVAILABLE : 3
09-02 12:09:27.277  1037  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.277  1037  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.277  1037  1543 I WifiNative-HAL: startHal
09-02 12:09:27.277  1037  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf765440
09-02 12:09:27.277  1037  1543 D wifi    : failed to get capabilities : -3
09-02 12:09:27.277  1037  1543 E WifiScanningService: could not get scan capabilities
09-02 12:09:27.277  1037  1377 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 12:09:27.277  8262  8262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:27.280  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 12:09:27.280  1037  1379 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 12:09:27.280  1928  1928 D WfdsService: WifiP2pState is changed : true
09-02 12:09:27.280  1928  2282 D WfdsService: Receive the WFDS_ENABLE Method
09-02 12:09:27.280  1928  2282 D WfdsService: Set the WFDS Monitor: true
09-02 12:09:27.280  1928  2282 D WfdsService: Connected to the supplicant for wfds
09-02 12:09:27.280  1037  1379 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 12:09:27.280  1928  2282 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 12:09:27.281  8223  8223 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 12:09:27.281  1037  1377 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 12:09:27.281  1037  1379 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 12:09:27.281  1928  2282 D WfdsService: selectPreferredScanChannel [36]
09-02 12:09:27.281  1928  2282 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 12:09:27.281  1037  1377 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 12:09:27.281  1037  1379 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 12:09:27.281  1037  1379 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 12:09:27.281  8223  8223 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 12:09:27.282  1037  1377 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 12:09:27.282  1037  1377 D WifiNative-p2p0: SET device_name G3: returned true
09-02 12:09:27.282  1037  1377 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 12:09:27.282  1037  1377 D LGWifiP2pService: before postfix = G3
09-02 12:09:27.282  1037  1377 D WifiServerServiceExt: postfix byte check : 2
09-02 12:09:27.282  1037  1377 D LGWifiP2pService: after postfix = G3
09-02 12:09:27.282  1037  1377 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 12:09:27.283  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 12:09:27.283  1037  1379 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 12:09:27.283  1928  1928 D WfdsService: isConnected: false
09-02 12:09:27.284  1037  1379 E WifiStateMachine:  ConnectModeState wha,t:132096 -100 0
09-02 12:09:27.284  1037  1379 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 12:09:27.284  1037  1377 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 12:09:27.284  1037  1379 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 12:09:27.284  1037  1377 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 12:09:27.284  8223  8223 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 12:09:27.285  1037  1377 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 12:09:27.285  1037  1377 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 12:09:27.285  1037  1377 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 12:09:27.285  1037  1377 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 12:09:27.285  1037  1377 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 12:09:27.285  1037  1377 D WifiNative-HAL: p2pGetDeviceAddress
09-02 12:09:27.285  1037  1377 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-02 12:09:27.286  1037  1377 D LGWifiP2pService: DeviceAddress: 
09-02 12:09:27.286  1037  1377 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 12:09:27.286  1037  1377 D WifiNative-p2p0: P2P_FLUSH: returned false
09-02 12:09:27.286  1037  1377 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 12:09:27.286  1037  1377 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 12:09:27.286  1037  1377 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 12:09:27.287  1037  1377 D WifiNative-p2p0:    returned OK
09-02 12:09:27.287  1037  1377 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 12:09:27.288  1037  1377 D WifiNative-p2p0: SAVE_CONFIG: returned false
09-02 12:09:27.288  1037  1377 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-02 12:09:27.288  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 12:09:27.290  1037  1377 D LGWifiP2pService: InactiveState
09-02 12:09:27.290  1037  1377 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.290  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.290  1037  1377 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 12:09:27.291  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 12:09:27.291  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 12:09:27.291  1928  1928 D WfdsService: Update P2p Interface State: 3
,09-02 12:09:27.297  1037  1377 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 12:09:27.297  1037  1377 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.297  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 12:09:27.297  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.298  1037  1377 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.298  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-02 12:09:27.299  8223  8223 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:09:27.299  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.299  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.300  1928  8285 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:09:27.300  1928  8285 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.300  1928  8285 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.300  1037  8283 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:09:27.300  1037  8283 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.301  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.301  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.301  1037  8283 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.301  1037  8283 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.301  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.301  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.301  1037  8283 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.301  1037  8283 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.301  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.301  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: InactiveState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: DefaultState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1928  2282 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1377 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.302  1037  1037 E WifiServerServiceExt: No p2p device connected
09-02 12:09:27.303  1037  1379 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 12:09:27.303  1037  1379 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 12:09:27.304  1037  1379 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 12:09:27.304  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 12:09:27.304  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_c,md COUNTRY CZ
09-02 12:09:27.305  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.306  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 12:09:27.306  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.306  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.306  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 12:09:27.306  8223  8223 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 12:09:27.307  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.308  1928  8285 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.308  1037  1379 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 12:09:27.308  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.308  1928  8285 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.308  1037  1379 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:09:27.308  1037  1379 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:09:27.309  1037  8283 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.309  1037  8283 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.309  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.309  1037  1379 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 12:09:27.309  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.309  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 12:09:27.309  1037  8283 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 12:09:27.309  1037  8283 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.309  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.309  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 12:09:27.309  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:27.309  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 12:09:27.309  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:27.310  1037  1377 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.310  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.310  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 12:09:27.310  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:27.310  1037  8283 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:27.310  1037  8283 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 12:09:27.310  1037  1379 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 12:09:27.310  1037  1379 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-02 12:09:27.311  1037  1379 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 12:09:27.311  1037  1379 D WifiNative-wlan0: doBoolean: SCAN
09-02 12:09:27.311  1037  1379 D WifiNative-wlan0: SCAN: returned false
09-02 12:09:27.312  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=208601  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:09:27.315  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=208604  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 12:09:27.315  1037  1379 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:27.316  1037  1379 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:27.316  1037  1379 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:27.316  1037  1379 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:27.317  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.317  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.317  1037  1379 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 12:09:27.317  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.317  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.317  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:09:27.319  8241  8287 W FormManager: Network not available. Please check & try again.
09-02 12:09:27.319  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:27.324  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.324  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 12:09:27.326  8241  8288 V FormManager: Network unavailable.
09-02 12:09:27.326  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:27.326  4801  4801 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 12:09:27.328  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:27.328  8241  8288 V FormManager: Network unavailable.
09-02 12:09:27.330  4801  4801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 12:09:27.335  4801  8289 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 12:09:27.336  4801  8290 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 12:09:27.336  4801  8290 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 12:09:27.366  1037  1919 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8291 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 12:09:27.476  8291  8291 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 12:09:27.477  8291  8291 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 12:09:27.490  8291  8291 V [BNRBootReceiver]: Boot Receiver Return
,09-02 12:09:27.492  8291  8291 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 12:09:27.550  1037  1873 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8309 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 12:09:27.552  1037  1873 I ActivityManager: Killing 7383:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-02 12:09:27.598  1037  1687 W libprocessgroup: failed to open /acct/uid_10085/pid_7383/cgroup.procs: No such file or directory
,09-02 12:09:27.625  8309  8309 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 12:09:27.650  8223  8223 E wpa_supplicant: USIM:  scard_init function
09-02 12:09:27.650  8223  8223 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-02 12:09:27.652  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 12:09:27.652  1037  8283 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 12:09:27.652  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 12:09:27.652  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-02 12:09:27.653  1037  8283 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 12:09:27.653  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 12:09:27.653  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 12:09:27.653  1037  1379 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
09-02 12:09:27.654  1037  1379 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
09-02 12:09:27.654  1037  1379 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
09-02 12:09:27.654  1037  1379 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
09-02 12:09:27.655  1037  1379 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 12:09:27.660  8309  8309 D PluginManager: init()
09-02 12:09:27.660  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=208949  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 12:09:27.667  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.667  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.668  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.668  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.668  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 12:09:27.668  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.668  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.669  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:09:27.670  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=208959  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 12:09:27.671  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.671  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.671  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 12:09:27.674  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.674  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.676  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:27.776  8223  8223 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:09:27.779  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 12:09:27.780  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 12:09:27.782  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 12:09:27.782  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 12:09:27.783  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:27.783  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 12:09:27.785  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=209074  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:09:27.787  8223  8223 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:09:27.787  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:09:27.788  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:27.788  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:27.789  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 12:09:27.789  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:09:27.789  1037  8283 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:09:27.789  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 12:09:27.789  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:09:27.789  1037  8283 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 12:09:27.790  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:27.790  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=209076  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 12:09:27.790  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:27.792  1037  1379 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209081
09-02 12:09:27.793  1037  1379 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209082
09-02 12:09:27.794  1037  1379 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209083
09-02 12:09:27.796  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 12:09:27.799  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209088
09-02 12:09:27.799  1037  1379 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209088
09-02 12:09:27.800  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=209089  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:09:27.803  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.803  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.807  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.807  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.807  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 12:09:27.807  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.809  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=209098  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 12:09:27.810  1037  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=209099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:09:27.810  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=209099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 12:09:27.811  1037  1379 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=209100
09-02 12:09:27.811  1037  1379 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=209101
09-02 12:09:27.812  1037  1379 D WifiNative-wlan0: doString: [STATUS]
09-02 12:09:27.813  1037  8283 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 12:09:27.813  1037  8283 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 12:09:27.813  1037  1379 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 12:09:27.814  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.814  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.814  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 12:09:27.815  1037  1379 I WifiServiceExtension: setVHTCapabilityType  : false
,09-02 12:09:27.827  1037  1379 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 12:09:27.827  1037  1379 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-02 12:09:27.830  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.830  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 12:09:27.832  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.832  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.833  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 12:09:27.833  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.834  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.834  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.835  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.842  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.842  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.842  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-02 12:09:27.844  1037  1379 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 12:09:27.845  1037  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:09:27.845  1037  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:09:27.845  1037  1455 D ConnectivityService: Got NetworkAgent Messenger
09-02 12:09:27.845  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 12:09:27.845  1037  1455 D ConnectivityService: NetworkAgent connected
09-02 12:09:27.845  1037  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:09:27.846  1037  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:09:27.859  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.859  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.860  1037  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-02 12:09:27.860  1037  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:09:27.860  1037  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 12:09:27.861  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.862  1037  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 12:09:27.862  1037  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 12:09:27.868  1037  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 12:09:27.869   307   895 D CommandListener: Setting iface cfg
09-02 12:09:27.872  1037  1379 E WifiStateMachine: Start Dhcp Watchdog 3
09-02 12:09:27.872  1037  8335 D DhcpStateMachine: StoppedState
09-02 12:09:27.872  1037  8335 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.872  1037  8335 D DhcpStateMachine: WaitBeforeStartState
,09-02 12:09:27.873  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.873  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 12:09:27.873  1037  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=209162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:27.874  1037  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=209163  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:27.875  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=209164  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:27.875  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.876  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.876  1037  1379 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.876  1037  1379 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.877  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.877  1037  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 12:09:27.878  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.878  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-02 12:09:27.879  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.879  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 12:09:27.880  1037  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=209169  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:27.880  1037  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=209170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:27.881  1037  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=209170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 12:09:27.882  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13811] from screen [on:0 period:-362814646] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:09:27.883  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-362814645] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 12:09:27.883  1037  1379 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-02 12:09:27.887  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.888  1037  1455 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-02 12:09:27.889  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:27.889  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:27.889  1037  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:27.890  1037  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:27.890  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:27.891  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 12:09:27.891  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 12:09:27.891  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
09-02 12:09:27.892  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
09-02 12:09:27.892  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 12:09:27.892  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 12:09:27.892  1037  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 12:09:27.892  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 12:09:27.893  1037  1379 D WifiNative-wlan0: SET ps 0: returned true
09-02 12:09:27.893  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 12:09:27.893  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 12:09:27.893  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 12:09:27.894  1037  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32a8861d target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.894  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32a8861d target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.894  1037  8335 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.894  1037  8335 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 12:09:27.894  1037  1379 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 12:09:27.894  1037  1379 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 12:09:27.894  1037  1379 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-02 12:09:27.895   307   895 D CommandListener: Setting iface cfg
09-02 12:09:27.895   307   895 D CommandListener: Trying to bring up wlan0
09-02 12:09:27.897  1037  1379 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 12:09:27.898  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.898  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:09:27.899  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 12:09:27.899  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 12:09:27.900  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-02 12:09:27.900  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-02 12:09:27.900  1037  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.901  1037  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.901  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 12:09:27.901  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 12:09:27.901  1037  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 12:09:27.901  1037  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 12:09:27.902  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 12:09:27.902  1037  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 12:09:27.902  1037  1379 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 12:09:27.920  1037  1379 D WifiNative-wlan0: SET ps 1: returned true
09-02 12:09:27.920  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 12:09:27.920  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:27.921  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 12:09:27.921  1037  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:27.922  1037  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:27.922  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:27.922  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:27.923  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 12:09:27.923  1037  1379 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:09:27.924  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 12:09:27.924  1037  1379 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 12:09:27.924  1037  1455 D ConnectivityService: ignoring duplicate network state non-change
09-02 12:09:27.928  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.928  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.928  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.928  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.928  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:09:27.929  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:27.934  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.934  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.934  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 12:09:27.934  1037  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 12:09:27.935  1037  1455 D ConnectivityService: Adding iface wlan0 to network 102
09-02 12:09:27.938  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 12:09:27.941  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 12:09:27.944  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.944  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.944  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:09:27.948  1037  1379 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 12:09:27.949  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-02 12:09:27.953  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.954  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 12:09:27.954  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.954  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:09:27.954  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 12:09:27.955  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.958  1037  1455 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 12:09:27.958  1037  1455 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-02 12:09:27.959  1037  1455 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-02 12:09:27.960   307   895 E Netd    : netlink response contains error (File exists)
,09-02 12:09:27.960  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.960  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:09:27.960  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.962  1037  1455 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-02 12:09:27.963  1037  1455 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 12:09:27.963  1037  1455 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-02 12:09:27.963  1037  1455 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-02 12:09:27.964  1037  1455 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 12:09:27.964  1037  1455 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 12:09:27.964  1037  1455 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-02 12:09:27.964  1037  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 12:09:27.964  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:09:27.964  1037  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:09:27.964  1037  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:27.964  1037  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 12:09:27.964  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 12:09:27.964  1037  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:27.964  1037  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 12:09:27.964  1037  1455 D ConnectivityService: currentScore = 0, newScore = 20
09-02 12:09:27.964  1037  1455 D ConnectivityService:    accepting network in place of null
09-02 12:09:27.964  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:27.964  1037  1455 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:27.965  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.965  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 12:09:27.965  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:09:27.965  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 12:09:27.966  1037  1455 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 12:09:27.966  1037  1455 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 12:09:27.966  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 12:09:27.966  1037  1379 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:27.966  1037  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:09:27.968  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:27.968  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:09:27.968   307  8340 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 12:09:27.971  1037  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 12:09:27.971  1037  1455 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 12:09:27.971  1037  1455 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-02 12:09:27.974  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 12:09:27.974  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 12:09:27.975  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 12:09:27.975  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 12:09:27.976  1037  1455 D ConnectivityService: validation of new default Network = false
09-02 12:09:27.976  1037  1455 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 12:09:27.976  1037  1455 D DSQN    : enableDataServiceNotify 
09-02 12:09:27.976  1037  1455 D DSQN    : start dsqn bin
09-02 12:09:27.982  1037  1375 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 12:09:27.969  8341  8341 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:27.983  1037  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 12:09:27.983  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:27.984  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:27.969  8341  8341 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:27.984  1037  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:27.984  1590  2037 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 12:09:27.994  8341  8341 E DSQN    : DSQN ssw
,09-02 12:09:28.001  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 12:09:28.001  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:28.002  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:28.029   307  8340 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 12:09:28.063   307  8340 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 12:09:28.096   307   894 D LGDataListener: argv[0]=dsqncommand
09-02 12:09:28.096   307   894 D LGDataListener: argv[1]=wlan0
09-02 12:09:28.097   307   894 D LGDataListener: argv[2]=1
09-02 12:09:28.097   307   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 12:09:28.098  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 12:09:28.098  1037  1117 D DSQN    : start to monitor internet connection
09-02 12:09:28.098  1037  8335 D DhcpStateMachine: DHCPV4 request on wlan0
09-02 12:09:28.100  1037  8335 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 12:09:28.100  1037  8335 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 12:09:28.089  8347  8347 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 12:09:28.089  8347  8347 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 12:09:28.129  8347  8347 I dhcpcd  : version 5.5.6 starting
09-02 12:09:28.130  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 10:09:28 GMT], X-Android-Received-Millis=[1472810968129], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472810968095]}
09-02 12:09:28.130  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 12:09:28.130  1037  8334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 12:09:28.131  1037  1455 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-02 12:09:28.131  1037  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 12:09:28.131  1037  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 12:09:28.131  1037  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:28.132  1037  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 12:09:28.132  1037  1455 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-02 12:09:28.132  1037  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 12:09:28.132  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:28.132  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:28.133  1037  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:28.135  1590  2037 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 12:09:28.135  8347  8347 E dhcpcd  : get_duid: m
09-02 12:09:28.135  1037  1455 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:28.135  8347  8347 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 12:09:28.135  8347  8347 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 12:09:28.138  1037  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 12:09:28.138  1037  1379 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:28.138  1037  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:09:28.138  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:28.139  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 12:09:28.161  8309  8309 W ExternalStrings: load override strings
09-02 12:09:28.161  8309  8309 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 12:09:28.161  8309  8309 W ExternalStr,ings: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:09:28.161  8309  8309 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:09:28.165  8309  8309 D StatusProvider: onCreate
,09-02 12:09:28.181  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-02 12:09:28.182  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 12:09:28.183  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 12:09:28.212  8347  8347 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:09:28.212  8347  8347 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-02 12:09:28.212  8347  8347 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:09:28.212  8347  8347 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 12:09:28.213  8347  8347 D dhcpcd  : wlan0: sending REQUEST (xid 0x63e0abed), next in 3.10 seconds
,09-02 12:09:28.218  8309  8309 V Signer  : override build config not found
,09-02 12:09:28.218  8309  8309 D Signer  : value of property debug is false
09-02 12:09:28.236  6984  7045 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 922)
09-02 12:09:28.237  6984  7045 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 922)
,09-02 12:09:28.241  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-02 12:09:28.241  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-02 12:09:28.242  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-02 12:09:28.242  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-02 12:09:28.242  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
,09-02 12:09:28.242  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-02 12:09:28.242  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-02 12:09:28.242  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,09-02 12:09:28.243  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-02 12:09:28.243  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-02 12:09:28.243  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-02 12:09:28.243  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-02 12:09:28.243  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-02 12:09:28.247  6984  7045 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 927)
09-02 12:09:28.249  6984  7045 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 12:09:28.249  6984  7045 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 928)
09-02 12:09:28.250  8309  8309 V LGMDMManager: Create singleton instance
,09-02 12:09:28.259  8347  8347 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-02 12:09:28.259  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.259  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@908a18f added. We now have 2 listener(s)
09-02 12:09:28.260  1037  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.262  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.262  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.262  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.262  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.262  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d808c1c added. We now have 9 listener(s)
09-02 12:09:28.262  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.263  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:09:28.267  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:28.274  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:28.276  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.276  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:28.277  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.278  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39665fa added. We now have 3 listener(s)
09-02 12:09:28.279  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.279  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.281  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:09:28.286  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.286  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.286  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.286  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.286  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3377c7ab added. We now have 10 listener(s)
09-02 12:09:28.286  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.287  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:28.287  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:28.287  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:28.287  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.287  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.287  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.288  8347  8347 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 12:09:28.288  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.288  8347  8347 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 12:09:28.288  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@908a18f removed from the list
09-02 12:09:28.288  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.288  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d808c1c removed from the list
09-02 12:09:28.288  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:28.288  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.288  8347  8347 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 12:09:28.289  8347  8347 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 12:09:28.289  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.289  8347  8347 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 12:09:28.289  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.289  8347  8347 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 12:09:28.290  8309  8309 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-02 12:09:28.290  8347  8347 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 12:09:28.290  8347  8347 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-02 12:09:28.292  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.292  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.292  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.292  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d808c1c not in the list
09-02 12:09:28.292  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.292  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.293  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:09:28.293  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.293  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.293  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3377c7ab removed from the list
09-02 12:09:28.293  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:09:28.293  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.293  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.293  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.293  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39665fa removed from the list
09-02 12:09:28.294  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.294  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2184e08 added. We now have 2 listener(s)
09-02 12:09:28.294  1037  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.297  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.297  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.297  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.297  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.297  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4fd9a1 added. We now have 9 listener(s)
09-02 12:09:28.297  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.298  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:09:28.300  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:28.305  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:09:28.309  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.310  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:28.314  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.318  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.318  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.318  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15693387 added. We now have 3 listener(s)
09-02 12:09:28.318  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:09:28.320  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.320  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.320  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.320  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.320  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce842b4 added. We now have 10 listener(s)
09-02 12:09:28.320  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.320  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:28.320  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:09:28.320  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:09:28.320  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:28.320  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:09:28.322  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:09:28.322  1037  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.325  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:09:28.327  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:09:28.328  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:09:28.329  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.330  6984  7045 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 12:09:28.333  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:28.333  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:28.337  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:28.337  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:28.337  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:28.337  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.337  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.337  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.337  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.337  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2184e08 removed from the list
09-02 12:09:28.337  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.337  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4fd9a1 removed from the list
09-02 12:09:28.337  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:28.337  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.338  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.338  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.339  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.339  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.339  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.339  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4fd9a1 not in the list
09-02 12:09:28.339  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.339  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.340  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.340  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:28.340  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:28.340  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.340  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.340  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce842b4 removed from the list
09-02 12:09:28.3,40  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.341  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.341  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.341  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.341  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15693387 removed from the list
09-02 12:09:28.341  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.341  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a1b8123 added. We now have 2 listener(s)
09-02 12:09:28.342  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.344  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-02 12:09:28.344  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.344  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.345  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.345  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1320d620 added. We now have 9 listener(s)
09-02 12:09:28.345  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.345  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:09:28.350  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:28.360  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:09:28.363  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.363  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:28.363  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.363  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d63299e added. We now have 3 listener(s)
09-02 12:09:28.365  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.366  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.368  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.368  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.368  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.368  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.368  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.368  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181b0c7f added. We now have 10 listener(s)
09-02 12:09:28.368  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.368  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:28.369  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:28.369  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:09:28.369  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:09:28.369  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:28.369  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:09:28.371  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:09:28.371  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.375  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:09:28.378  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:09:28.380  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:09:28.380  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.382  6984  7045 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 12:09:28.382  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:28.382  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:28.382  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:28.382  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.382  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.382  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.382  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.382  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a1b8123 removed from the list
09-02 12:09:28.382  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.382  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1320d620 removed from the list
09-02 12:09:28.382  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:28.382  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.383  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.383  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.384  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.384  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.384  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.384  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1320d620 not in the list
09-02 12:09:28.384  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.384  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.385  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.385  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:28.385  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:28.385  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.386  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.386  698,4  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181b0c7f removed from the list
09-02 12:09:28.386  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.386  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.386  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.386  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.386  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d63299e removed from the list
09-02 12:09:28.387  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.387  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@295441aa added. We now have 2 listener(s)
09-02 12:09:28.387  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:09:28.391  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.391  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.391  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.391  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.391  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385df19b added. We now have 9 listener(s)
09-02 12:09:28.391  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.392  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:09:28.395  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:28.395  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:28.395  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:28.400  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:09:28.401  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.401  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:28.401  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.401  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd16d11 added. We now have 3 listener(s)
09-02 12:09:28.402  1037  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.405  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.405  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.405  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09,:28.405  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.405  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@378cce76 added. We now have 10 listener(s)
09-02 12:09:28.405  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.405  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:28.405  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:09:28.405  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:09:28.405  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:09:28.405  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:09:28.407  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.408  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:09:28.409  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.409  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.413  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:28.413  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:09:28.414  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:09:28.415  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:09:28.416  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.418  6984  7045 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 12:09:28.419  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:28.420  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:28.420  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:28.420  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:28.420  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.420  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.420  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.420  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.421  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@295441aa removed from the list
09-02 12:09:28.421  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.421  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385df19b removed from the list
09-02 12:09:28.421  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:28.421  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.422  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.422  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.423  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.423  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.423  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.423  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385df19b not in the list
09-02 12:09:28.423  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.423  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.424  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.426  6984  7045 D BluetoothLeScanner: could not find callback wrapper
09-02 12:09:28.426  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:09:28.426  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.426  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.426  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@378cce76 removed from the list
09-02 12:09:28.426  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.426  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.426  6984  7045 D org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.426  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.426  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd16d11 removed from the list
09-02 12:09:28.427  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.427  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24cec94d added. We now have 2 listener(s)
09-02 12:09:28.477  1037  1981 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8379 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-02 12:09:28.480  1037  1981 I ActivityManager: Killing 7401:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-02 12:09:28.505  1037  8335 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-02 12:09:28.506  1037  8335 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 12:09:28.506  1037  8335 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 12:09:28.506  1037  8335 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 12:09:28.506  1037  8335 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 12:09:28.506  1037  8335 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,09-02 12:09:28.506  1037  8335 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 12:09:28.506  1037  8335 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 12:09:28.506  1037  8335 D DhcpStateMachine: RunningState
,09-02 12:09:28.550  8309  8366 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 12:09:28.688  1037  1981 E libprocessgroup: failed to kill 1 processes for processgroup 7401
09-02 12:09:28.689  1037  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 12:09:28.697  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.698  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:09:28.698  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.699  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.699  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bef5c02 added. We now have 9 listener(s)
09-02 12:09:28.699  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.700  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:09:28.746  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:09:28.763  6984  7045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:09:28.768  6984  7045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:09:28.768  6984  7045 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:09:28.768  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:09:28.769  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a60750 added. We now have 3 listener(s)
09-02 12:09:28.769  1037  1687 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 12:09:28.771  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.774  6984  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:09:28.774  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 12:09:28.774  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:09:28.774  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:09:28.775  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:09:28.775  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bcbad49 added. We now have 10 listener(s)
09-02 12:09:28.775  6984  7045 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:09:28.775  6984  7045 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:09:28.775  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:09:28.775  6984  7045 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:09:28.776  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.776  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.776  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:09:28.776  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.776  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24cec94d removed from the list
09-02 12:09:28.776  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.776  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bef5c02 removed from the list
09-02 12:09:28.776  6984  7045 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:09:28.776  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.779  8379  8379 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:28.781  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.781  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.782  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.782  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.782  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.782  6984  7045 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bef5c02 not in the list
09-02 12:09:28.782  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.782  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.784  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:09:28.784  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:09:28.784  6984  7045 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:09:28.784  6984  7045 V org.thaliproject.p2p.btconnectorlib.DiscoveryMana,gerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bcbad49 removed from the list
09-02 12:09:28.784  6984  7045 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:09:28.784  6984  7045 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:09:28.784  6984  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:09:28.784  6984  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:09:28.784  6984  7045 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a60750 removed from the list
09-02 12:09:28.786  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 12:09:28.786  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 12:09:28.786  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 12:09:28.786  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:09:28.787  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 12:09:28.787  6984  7045 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:09:28.799  6984  8404 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 935, name: My test thread name)
09-02 12:09:28.799  6984  8404 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 935, thread name: My test thread name)
09-02 12:09:28.800  6984  8404 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 935, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 12:09:28.802  6984  8405 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 937, name: My test thread name)
09-02 12:09:28.803  6984  8405 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 937, thread name: My test thread name)
09-02 12:09:28.803  6984  8405 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 937, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 12:09:28.805  6984  7045 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 12:09:28.805  6984  7045 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 12:09:28.805  6984  7045 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 12:09:28.805  6984  7045 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 12:09:28.805  6984  7045 D com.test.thalitest.ThaliTestRunner: Total duration: 23267 ms
09-02 12:09:28.807  6984  7045 I jxcore-log: *Native tests were executed*
09-02 12:09:28.807  6984  7045 I jxcore-log: 
09-02 12:09:28.807  6984  7045 I jxcore-log: Total number of executed tests:  80
09-02 12:09:28.807  6984  7045 I jxcore-log: 
09-02 12:09:28.807  6984  7045 I jxcore-log: Number of passed tests:  80
09-02 12:09:28.807  6984  7045 I jxcore-log: 
09-02 12:09:28.808  6984  7045 I jxcore-log: Number of failed tests:  0
09-02 12:09:28.808  6984  7045 I jxcore-log: 
09-02 12:09:28.808  6984  7045 I jxcore-log: Number of ignored tests:  0
09-02 12:09:28.808  6984  7045 I jxcore-log: 
09-02 12:09:28.809  6984  7045 I jxcore-log: Total duration:  23267
09-02 12:09:28.809  6984  7045 I jxcore-log: 
09-02 12:09:28.809  6984  7045 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 12:09:28.809  6984  7045 I jxcore-log: 
09-02 12:09:28.812  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.812  6984  7045 I jxcore-log: 
09-02 12:09:28.815  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.815  6984  7045 I jxcore-log: 
09-02 12:09:28.817  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.817  6984  7045 I jxcore-log: 
,09-02 12:09:28.818  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.818  6984  7045 I jxcore-log: 
09-02 12:09:28.820  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.820  6984  7045 I jxcore-log: 
09-02 12:09:28.822  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:09:28.822  6984  7045 I jxcore-log: 
09-02 12:09:28.824  6984  6984 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 12:09:28.826  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:09:28.826  6984  7045 I jxcore-log: 
09-02 12:09:28.829  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.829  6984  7045 I jxcore-log: 
09-02 12:09:28.830  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.830  6984  7045 I jxcore-log: 
09-02 12:09:28.831  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:09:28.831  6984  7045 I jxcore-log: 
09-02 12:09:28.832  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:09:28.832  6984  7045 I jxcore-log: 
09-02 12:09:28.833  8379  8379 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-02 12:09:28.834  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:09:28.834  6984  7045 I jxcore-log: 
,09-02 12:09:28.835  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.835  6984  7045 I jxcore-log: 
09-02 12:09:28.836  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.836  6984  7045 I jxcore-log: 
09-02 12:09:28.840  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.840  6984  7045 I jxcore-log: 
09-02 12:09:28.841  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.841  6984  7045 I jxcore-log: 
09-02 12:09:28.841  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.841  6984  7045 I jxcore-log: 
09-02 12:09:28.842  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.842  6984  7045 I jxcore-log: 
09-02 12:09:28.846  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.846  6984  7045 I jxcore-log: 
,09-02 12:09:28.849  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:09:28.849  6984  7045 I jxcore-log: 
09-02 12:09:28.851  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:09:28.851  6984  7045 I jxcore-log: 
09-02 12:09:28.853  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:09:28.853  6984  7045 I jxcore-log: 
09-02 12:09:28.855  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.855  6984  7045 I jxcore-log: 
09-02 12:09:28.857  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.857  6984  7045 I jxcore-log: 
09-02 12:09:28.859  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.859  6984  7045 I jxcore-log: 
09-02 12:09:28.859  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.859  6984  7045 I jxcore-log: 
09-02 12:09:28.860  6984  7045 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:09:28.860  6984  7045 I jxcore-log: 
,09-02 12:09:28.866  8379  8379 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-02 12:09:28.866  8379  8379 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 12:09:28.866  8379  8379 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 12:09:28.867  8379  8379 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-02 12:09:28.867  8379  8379 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 12:09:28.869  8379  8379 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-02 12:09:28.876  8379  8379 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-02 12:09:28.889  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:09:28.891  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:28.904  8379  8379 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 12:09:28.907  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 12:09:28.910  7112  7112 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 12:09:28.911  8379  8379 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-02 12:09:28.912  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:28.913  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:28.915  8309  8366 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:28.915  8309  8366 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 12:09:28.920  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:28.921  8379  8379 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-02 12:09:28.928  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:28.938  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:28.938  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:28.939  8379  8379 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 12:09:28.941  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:28.942  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:28.948  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:28.955  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:28.961  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:09:28.961  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:28.961  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:28.965  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 12:09:28.965  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 12:09:28.965  7112  7112 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 12:09:28.965  7112  7112 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 12:09:28.966  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 12:09:28.966  7112  7112 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 12:09:28.966  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 12:09:28.966  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 12:09:28.966  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 12:09:28.966  7112  7112 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 12:09:28.966  7112  7112 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 12:09:28.967  7112  7112 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 12:09:28.973  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:28.974  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-02 12:09:28.983  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:28.988  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:28.994  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:28.994  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:28.994  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:28.997  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:28.997  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.004  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:29.011  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:29.017  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 12:09:29.018  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:29.018  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:29.020  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.020  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.028  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:29.034  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:29.039  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:29.039  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:29.039  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:29.042  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.042  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.048  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:29.052  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:29.058  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:29.058  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:29.058  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:29.062  8309  8366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-02 12:09:29.066  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.067  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.079  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:29.081  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-02 12:09:29.088  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:29.089  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-02 12:09:29.089  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 12:09:29.090  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 12:09:29.091  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-02 12:09:29.091  8309  8366 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,09-02 12:09:29.096  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:29.096  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:29.097  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-02 12:09:29.098  8414  8414 D AndroidRuntime: 
09-02 12:09:29.098  8414  8414 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 12:09:29.099  8309  8366 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-02 12:09:29.100  8414  8414 D AndroidRuntime: CheckJNI is OFF
09-02 12:09:29.101  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 12:09:29.104  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.104  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.110  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:29.117  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:29.124  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:29.125  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:29.126  8379  8379 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 12:09:29.129  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.130  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.132  8262  8262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 12:09:29.135  8262  8262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 12:09:29.139  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 12:09:29.145  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 12:09:29.152  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:29.152  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 12:09:29.153  8379  8379 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-02 12:09:29.153  8379  8379 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:09:29.154  8379  8379 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:09:29.159  8309  8367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 12:09:29.160  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.163  8262  8262 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 12:09:29.164  8262  8262 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 12:09:29.167  7112  7112 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 12:09:29.174  7112  7112 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 12:09:29.181  8379  8379 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 12:09:29.182  8379  8379 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 12:09:29.182  8379  8379 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 12:09:29.183  8379  8379 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 12:09:29.183  8379  8379 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 12:09:29.186  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-02 12:09:29.191  8379  8379 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-02 12:09:29.193  8379  8379 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 12:09:29.193  8379  8379 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-02 12:09:29.203  8414  8414 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 12:09:29.215  1037  1111 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-02 12:09:29.215  1037  1111 I ActivityManager: Killing 6984:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-02 12:09:29.233  8379  8379 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 12:09:29.233  8379  8379 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:29.271  8379  8379 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-02 12:09:29.272  8379  8379 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-02 12:09:29.272  8379  8379 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-02 12:09:29.272  8379  8379 V SoundPool: doLoad: loading sample sampleID=1
09-02 12:09:29.273  8379  8379 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 12:09:29.275  8379  8438 V SoundPool: Start decode
09-02 12:09:29.275  8379  8438 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-02 12:09:29.275   311  1384 V MediaPlayerService: decode(22, 10857164, 17813)
,09-02 12:09:29.275   311  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-02 12:09:29.275   311  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-02 12:09:29.275   311  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-02 12:09:29.275   311  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-02 12:09:29.275   311  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-02 12:09:29.275   311  1384 V MediaPlayerService: player type = 3
09-02 12:09:29.275   311  1384 V AwesomePlayer: AwesomePlayer create()
09-02 12:09:29.276   311  1384 V AwesomePlayer: reset_l() 
09-02 12:09:29.276   311  1384 V AwesomePlayer: cancelPlayerEvents
09-02 12:09:29.276   311  1384 V AwesomePlayer: setAudioSink() 
09-02 12:09:29.276   311  1384 V AwesomePlayer: reset_l() 
09-02 12:09:29.276   311  1384 V AudioCache: notify(0xb54746c0, 8, 0, 0)
09-02 12:09:29.276   311  1384 V AudioCache: ignored
09-02 12:09:29.276   311  1384 V AwesomePlayer: cancelPlayerEvents
09-02 12:09:29.276   311  1384 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-02 12:09:29.276   311  1384 V AwesomePlayer: setDataSource_l dataSource
09-02 12:09:29.276   311  1384 V LGParserOSAL: SniffLGParser start
09-02 12:09:29.276   311  1384 V LGParserOSAL: MainType:5, SubType=0
09-02 12:09:29.276   311  1384 V LGParserOSAL: #### check Mime : application/ogg
09-02 12:09:29.276   311  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-02 12:09:29.276   311  1384 E MediaExtractor: Use LGExtractor :application/ogg 
09-02 12:09:29.286  1037  2018 I WindowState: WIN DEATH: Window{fbedd82 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 12:09:29.287  1037  1437 D WifiService: Client connection lost with reason: 4
09-02 12:09:29.294  1037  2018 D InputDispatcher: Window went away: Window{fbedd82 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 12:09:29.325   311  1384 V LGParserOSAL: supported mime: application/ogg
09-02 12:09:29.325   311  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-02 12:09:29.325   311  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-02 12:09:29.325   311  1384 V AwesomePlayer: mBitrate = -1 bits/sec
09-02 12:09:29.325   311  1384 V AwesomePlayer: AudioTrack Setting
09-02 12:09:29.325   311  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-02 12:09:29.325   311  1384 V AwesomePlayer: setAudioSource() 
09-02 12:09:29.325   311  1384 V MediaPlayerService: prepare
09-02 12:09:29.325   311  1384 V AwesomePlayer: prepareAsync_l() 
09-02 12:09:29.325   311  1384 V MediaPlayerService: wait for prepare
09-02 12:09:29.326   311  8439 V AwesomePlayer: onPrepareAsyncEvent() 
09-02 12:09:29.326   311  8439 V AwesomePlayer: initAudioDecoder() 
09-02 12:09:29.326   311  8439 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 12:09:29.326   311  8439 V AudioSystem: isOffloadSupported()
09-02 12:09:29.326   311  8439 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 12:09:29.326   311  8439 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 12:09:29.326   311  8439 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 12:09:29.326   311  8439 V AwesomePlayer: getUseOffload() = 0 
09-02 12:09:29.326   311  8439 V OMXCodec: OMXCodec::Create
09-02 12:09:29.326   311  8439 V OMXCodec: findMatchingCodecs()
09-02 12:09:29.326   311  8439 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-02 12:09:29.326   311  8439 V OMXCodec: matchingCodecs.size()=1
09-02 12:09:29.326   311  8439 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-02 12:09:29.328   311  8439 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-02 12:09:29.328   311  8439 V LGCodecAdapter: LG Codec Adapter start
09-02 12:09:29.328   311  8439 V OMXCodec: OMXCodec Createtor
09-02 12:09:29.328   311  8439 V OMXCodec: setComponentRole
09-02 12:09:29.328   311  8439 V OMXCodec: configureCodec protected=0
09-02 12:09:29.328   311  8439 V LGCodecAdapter: called getLGCodecSpecificData
09-02 12:09:29.329   311  8439 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-02 12:09:29.329   311  8439 V LGCodecOSAL: Called LGconfigureCodecMETA
09-02 12:09:29.329   311  8439 V LGCodecOSAL: Called LGconfigureCodecMSG
09-02 12:09:29.329   311  8439 V LGCodecOSAL: Not support LGCodec
09-02 12:09:29.329   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 12:09:29.329   311  8439 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-02 12:09:29.329   311  8439 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-02 12:09:29.329   311  8439 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-02 12:09:29.329   311  8439 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 12:09:29.329   311  8439 V AudioSystem: isOffloadSupported()
09-02 12:09:29.329   311  8439 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 12:09:29.329   311  8439 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 12:09:29.329   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-02 12:09:29.329   311  8439 V OMXCodec: init()
09-02 12:09:29.329   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-02 12:09:29.329   311  8439 V OMXCodec: allocateBuffers
09-02 12:09:29.329   311  8439 V OMXCodec: allocateBuffersOnPort portIndex=0
09-0,2 12:09:29.329   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c01f0 on input port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0240 on input port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on input port
09-02 12:09:29.330   311  8439 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0b00 on output port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0b50 on output port
09-02 12:09:29.330   311  8439 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0ba0 on output port
09-02 12:09:29.330   311  8439 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 12:09:29.330   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 12:09:29.330   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 12:09:29.330   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-02 12:09:29.330   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-02 12:09:29.330   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-02 12:09:29.330   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,09-02 12:09:29.330   311  8439 V OMXCodec: init() mAsyncCompletion wait free! 
09-02 12:09:29.330   311  8439 V AwesomePlayer: finishAsyncPrepare_l() 
09-02 12:09:29.330   311  8439 V AudioCache: notify(0xb54746c0, 5, 0, 0)
09-02 12:09:29.330   311  8439 V AudioCache: ignored
09-02 12:09:29.330   311  8439 V AudioCache: notify(0xb54746c0, 1, 0, 0)
09-02 12:09:29.330   311  8439 V AudioCache: prepared
09-02 12:09:29.330   311  1384 V AudioCache: wait - success
09-02 12:09:29.330   311  1384 V MediaPlayerService: start
09-02 12:09:29.331   311  1384 V AwesomePlayer: play_l() 
,09-02 12:09:29.331   311  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-02 12:09:29.331   311  1384 V AwesomePlayer: createAudioPlayer_l
09-02 12:09:29.331   311  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
09-02 12:09:29.331   311  1384 V AwesomePlayer: startAudioPlayer_l() ,
09-02 12:09:29.331   311  1384 D AudioPlayer: start of Playback, useOffload 0
09-02 12:09:29.331   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 12:09:29.331   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data,
09-02 12:09:29.332   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-02 12:09:29.332   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,09-02 12:09:29.332   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-02 12:09:29.332   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-02 12:09:29.332   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
,09-02 12:09:29.332   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550304
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550784
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550864
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974550944
,09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat(),
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-02 12:09:29.333   311  8441 V OMXCodec: allocateBuffersOnPort portIndex=1
,09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0b50 on output port
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0b00 on output port
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0920 on output port
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17e5060 on output port
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-02 12:09:29.333   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,09-02 12:09:29.334   311  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-02 12:09:29.335   311  1384 V AudioCache: notify(0xb54746c0, 6, 0, 0)
09-02 12:09:29.335   311  1384 V AudioCache: ignored
09-02 12:09:29.335   311  1384 V MediaPlayerService: wait for playback complete
09-02 12:09:29.335   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.335   311  8442 V AudioCache: memcpy(0xaecfd000, 0xb57d5000, 4096)
09-02 12:09:29.336   311  8442 V AudioCache: write(0xb57d5000, 4096)
,09-02 12:09:29.336   311  8442 V AudioCache: memcpy(0xaecfe000, 0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: memcpy(0xaecff000, 0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: memcpy(0xaed00000, 0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: memcpy(0xaed01000, 0xb57d5000, 4096)
09-02 12:09:29.347   311  8442 V AudioCache: write(0xb57d5000, 4096)
,09-02 12:09:29.347   311  8442 V AudioCache: memcpy(0xaed02000, 0xb57d5000, 4096)
09-02 12:09:29.348   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.348   311  8442 V AudioCache: memcpy(0xaed03000, 0xb57d5000, 4096)
09-02 12:09:29.348   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.348   311  8442 V AudioCache: memcpy(0xaed04000, 0xb57d5000, 4096)
09-02 12:09:29.348   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.348   311  8442 V AudioCache: memcpy(0xaed05000, 0xb57d5000, 4096)
09-02 12:09:29.350   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.350   311  8442 V AudioCache: memcpy(0xaed06000, 0xb57d5000, 4096)
,09-02 12:09:29.350   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.350   311  8442 V AudioCache: memcpy(0xaed07000, 0xb57d5000, 4096)
09-02 12:09:29.350   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.350   311  8442 V AudioCache: memcpy(0xaed08000, 0xb57d5000, 4096)
09-02 12:09:29.351   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.351   311  8442 V AudioCache: memcpy(0xaed09000, 0xb57d5000, 4096)
09-02 12:09:29.351   311  8442 V AudioCache: write(0xb57d5000, 4096)
,09-02 12:09:29.351   311  8442 V AudioCache: memcpy(0xaed0a000, 0xb57d5000, 4096)
09-02 12:09:29.351   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.351   311  8442 V AudioCache: memcpy(0xaed0b000, 0xb57d5000, 4096)
09-02 12:09:29.352   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.352   311  8442 V AudioCache: memcpy(0xaed0c000, 0xb57d5000, 4096)
09-02 12:09:29.353   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.353   311  8442 V AudioCache: memcpy(0xaed0d000, 0xb57d5000, 4096)
09-02 12:09:29.353   311  8442 V AudioCache: write(0xb57d5000, 4096)
,09-02 12:09:29.353   311  8442 V AudioCache: memcpy(0xaed0e000, 0xb57d5000, 4096)
09-02 12:09:29.353   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.353   311  8442 V AudioCache: memcpy(0xaed0f000, 0xb57d5000, 4096)
09-02 12:09:29.354   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.354   311  8442 V AudioCache: memcpy(0xaed10000, 0xb57d5000, 4096)
09-02 12:09:29.354   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.354   311  8442 V AudioCache: memcpy(0xaed11000, 0xb57d5000, 4096)
,09-02 12:09:29.355   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.355   311  8442 V AudioCache: memcpy(0xaed12000, 0xb57d5000, 4096)
09-02 12:09:29.356   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.356   311  8442 V AudioCache: memcpy(0xaed13000, 0xb57d5000, 4096)
09-02 12:09:29.356   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.356   311  8442 V AudioCache: memcpy(0xaed14000, 0xb57d5000, 4096)
09-02 12:09:29.357   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.357   311  8442 V AudioCache: memcpy(0xaed15000, 0xb57d5000, 4096)
,09-02 12:09:29.357   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.357   311  8442 V AudioCache: memcpy(0xaed16000, 0xb57d5000, 4096)
09-02 12:09:29.360   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.360   311  8442 V AudioCache: memcpy(0xaed17000, 0xb57d5000, 4096)
09-02 12:09:29.360   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.360   311  8442 V AudioCache: memcpy(0xaed18000, 0xb57d5000, 4096)
09-02 12:09:29.361   311  8442 V AudioCache: write(0xb57d5000, 4096)
,09-02 12:09:29.361   311  8442 V AudioCache: memcpy(0xaed19000, 0xb57d5000, 4096)
09-02 12:09:29.361   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.361   311  8442 V AudioCache: memcpy(0xaed1a000, 0xb57d5000, 4096)
,09-02 12:09:29.363   311  8442 V AudioCache: write(0xb57d5000, 4096),
09-02 12:09:29.363   311  8442 V AudioCache: memcpy(0xaed1b000, 0xb57d5000, 4096)
09-02 12:09:29.364   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.364   311  8442 V AudioCache: memcpy(0xaed1c000, 0xb57d5000, 4096)
09-02 12:09:29.365   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.365   311  8442 V AudioCache: memcpy(0xaed1d000, 0xb57d5000, 4096)
,09-02 12:09:29.366   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.366   311  8442 V AudioCache: memcpy(0xaed1e000, 0xb57d5000, 4096)
09-02 12:09:29.367   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.367   311  8442 V AudioCache: memcpy(0xaed1f000, 0xb57d5000, 4096)
09-02 12:09:29.368   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.368   311  8442 V AudioCache: memcpy(0xaed20000, 0xb57d5000, 4096)
09-02 12:09:29.369   311  8442 V AudioCache: write(0xb57d5000, 4096),
09-02 12:09:29.369   311  8442 V AudioCache: memcpy(0xaed21000, 0xb57d5000, 4096)
09-02 12:09:29.370   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.370   311  8442 V AudioCache: memcpy(0xaed22000, 0xb57d5000, 4096)
09-02 12:09:29.371   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.371   311  8442 V AudioCache: memcpy(0xaed23000, 0xb57d5000, 4096)
,09-02 12:09:29.372   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.372   311  8442 V AudioCache: memcpy(0xaed24000, 0xb57d5000, 4096)
,09-02 12:09:29.373   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.373   311  8442 V AudioCache: memcpy(0xaed25000, 0xb57d5000, 4096)
09-02 12:09:29.374   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.374   311  8442 V AudioCache: memcpy(0xaed26000, 0xb57d5000, 4096)
09-02 12:09:29.375   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.375   311  8442 V AudioCache: memcpy(0xaed27000, 0xb57d5000, 4096)
09-02 12:09:29.375   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.375   311  8442 V AudioCache: memcpy(0xaed28000, 0xb57d5000, 4096)
,09-02 12:09:29.375   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.375   311  8442 V AudioCache: memcpy(0xaed29000, 0xb57d5000, 4096)
09-02 12:09:29.376   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.376   311  8442 V AudioCache: memcpy(0xaed2a000, 0xb57d5000, 4096)
09-02 12:09:29.377   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.377   311  8442 V AudioCache: memcpy(0xaed2b000, 0xb57d5000, 4096)
09-02 12:09:29.378   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.378   311  8442 V AudioCache: memcpy(0xaed2c000, 0xb57d5000, 4096)
09-02 12:09:29.378   311  8442 V AudioCache: write(0xb57d5000, 4096)
,09-02 12:09:29.378   311  8442 V AudioCache: memcpy(0xaed2d000, 0xb57d5000, 4096)
09-02 12:09:29.378   311  8442 V AudioCache: write(0xb57d5000, 4096)
09-02 12:09:29.378   311  8442 V AudioCache: memcpy(0xaed2e000, 0xb57d5000, 4096)
09-02 12:09:29.379   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-02 12:09:29.379   311  8442 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-02 12:09:29.379   311  8442 V AwesomePlayer: postAudioEOS() 
09-02 12:09:29.379   311  8442 V AudioCache: write(0xb57d5000, 280)
09-02 12:09:29.379   311  8442 V AudioCache: memcpy(0xaed2f000, 0xb57d5000, 280)
09-02 12:09:29.380   311  8439 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-02 12:09:29.381   311  8439 V AwesomePlayer: onStreamDone
09-02 12:09:29.381   311  8439 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-02 12:09:29.381   311  8439 V AudioCache: notify(0xb54746c0, 2, 0, 0)
09-02 12:09:29.381   311  8439 V AudioCache: playback complete
09-02 12:09:29.381   311  8439 V AwesomePlayer: pause_l() 
09-02 12:09:29.381   311  1384 V AudioCache: wait - success
09-02 12:09:29.381   311  8439 V AudioCache: notify(0xb54746c0, 7, 0, 0)
09-02 12:09:29.381   311  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-02 12:09:29.381   311  8439 V AudioCache: ignored
09-02 12:09:29.381   311  8439 V AwesomePlayer: cancelPlayerEvents
09-02 12:09:29.381   311  8439 D AudioPlayer: Pause Playback at 1068125
09-02 12:09:29.383   311  1384 V AwesomePlayer: reset_l() 
09-02 12:09:29.383   311  1384 V AudioCache: notify(0xb54746c0, 8, 0, 0)
09-02 12:09:29.383   311  1384 V AudioCache: ignored
09-02 12:09:29.383   311  1384 V AwesomePlayer: cancelPlayerEvents
09-02 12:09:29.383   311  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-02 12:09:29.383   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-02 12:09:29.383   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-02 12:09:29.383   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-02 12:09:29.383   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c08d0 on port 0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0240 on port 0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c01f0 on port 0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb17e5060 on port 1
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0920 on port 1
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0b00 on port 1
09-02 12:09:29.384   311  8441 V, OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0b50 on port 1
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 12:09:29.384   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-02 12:09:29.384   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 12:09:29.384   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 12:09:29.385   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-02 12:09:29.385   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-02 12:09:29.385   311  8441 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-02 12:09:29.385   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 12:09:29.385   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-02 12:09:29.385   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-02 12:09:29.386   311  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-02 12:09:29.386   311  1384 D AudioPlayer: AudioPlayer releasing audio source
09-02 12:09:29.386   311  1384 D AudioPlayer: AudioPlayer done releasing audio source
09-02 12:09:29.386   311  1384 V AwesomePlayer: reset_l() 
09-02 12:09:29.386   311  1384 V AwesomePlayer: cancelPlayerEvents
09-02 12:09:29.386   311  1384 V AwesomePlayer: ~AwesomePlayer call
09-02 12:09:29.387   311  1384 V AwesomePlayer: reset_l() 
09-02 12:09:29.387   311  1384 V AwesomePlayer: cancelPlayerEvents
09-02 12:09:29.387  8379  8438 V SoundPool: close(31)
09-02 12:09:29.387  8379  8438 V SoundPool: pointer = 0xa000f000, size = 205080, sampleRate = 48000, numChannels = 2
,09-02 12:09:29.410  1037  1379 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 12:09:29.411  1037  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 12:09:29.412  1037  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 12:09:29.416  1037  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:29.422  1037  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:29.426  1037  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 12:09:29.428  1037  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-02 12:09:29.428  1037  1455 D ConnectivityService: identical MTU - not setting
09-02 12:09:29.428  1037  1455 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-02 12:09:29.428  1037  1455 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 12:09:29.428  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 12:09:29.429  1037  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:29.430  1037  1455 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 12:09:29.431  1590  2037 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-02 12:09:29.471  1037  1111 I ActivityManager:   Force finishing activity ActivityRecord{f32bd0f u0 com.test.thalitest/.MainActivity t6}
,09-02 12:09:29.509   327   360 E GBMv2   : DFP En is all cleared set to be enabled
,09-02 12:09:29.514  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-02 12:09:29.521  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{f32bd0f u0 com.test.thalitest/.MainActivity t6 f}
09-02 12:09:29.522  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{f32bd0f u0 com.test.thalitest/.MainActivity t6 f}
,09-02 12:09:29.561  7805  7805 D UEI.SmartControl: QS Service created
09-02 12:09:29.563  8379  8379 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-02 12:09:29.565  8379  8379 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 12:09:29.565  8379  8379 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 12:09:29.567  1037  1764 W ActivityManager: Spurious death for ProcessRecord{1cad7797 6984:com.test.thalitest/u0a118}, curProc for 6984: null
09-02 12:09:29.570  1928  2775 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,09-02 12:09:29.571  1928  2775 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15bb2255 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-02 12:09:29.572  2020  2020 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-02 12:09:29.574  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-02 12:09:29.574  2020  2020 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-02 12:09:29.574  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{27e1b46a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-02 12:09:29.580  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,09-02 12:09:29.581  2020  2113 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-02 12:09:29.583  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-02 12:09:29.590  8379  8379 V LGMDMManager: Create singleton instance
09-02 12:09:29.596  3797  3797 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-02 12:09:29.596  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-02 12:09:29.597  2495  2685 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-02 12:09:29.599  7877  7877 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-02 12:09:29.599  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-02 12:09:29.619  1037  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-02 12:09:29.623  5114  5114 I art     : Explicit concurrent mark sweep GC freed 8260(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 712us total 85.797ms
09-02 12:09:29.628  7805  7805 I UEI.SmartControl: Service initServices...
09-02 12:09:29.628  7805  7805 D UEI.SmartControl: QS start get config
09-02 12:09:29.635  1037  1109 W InputMethodInfo: Duplicated subtype definition found: , voice
09-02 12:09:29.664  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-02 12:09:29.664  1892  1892 D ActionManagerService: notifyUserLog: 1000003
,09-02 12:09:29.665  3797  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-02 12:09:29.667  2020  2020 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-02 12:09:29.668  2020  2020 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-02 12:09:29.669  2020  2020 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-02 12:09:29.672  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-02 12:09:29.673  1892  1892 D ActionManagerService: notifyUserLog: 1000004
09-02 12:09:29.673  3797  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-02 12:09:29.674  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-02 12:09:29.674  3797  3812 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 12:09:29.675  1590  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 12:09:29.675  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262123
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , display: false
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , animation: false }
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262287
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , display: false
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , animation: false }
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , create_time: 1472216588858
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , display: false
09-02 12:09:29.677  2020  2020 I GBoardWebViewUtils: , animation: false }
09-02 12:09:29.680  5024  5024 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-02 12:09:29.680  5024  5024 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-02 12:09:29.681  5024  5024 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-02 12:09:29.681  5024  5024 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-02 12:09:29.681  5024  5024 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:09:29.681  5024  5024 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:09:29.681  5024  5024 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 12:09:29.681  5024  5024 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,09-02 12:09:29.681  5024  5024 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:09:29.682  5024  5024 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:09:29.682  5024  5024 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 12:09:29.682  5024  5024 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 12:09:29.705  2020  8444 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-02 12:09:29.706  1590  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 12:09:29.706  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.711  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 12:09:29.711  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-02 12:09:29.717  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-02 12:09:29.717  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-02 12:09:29.724  1037  1562 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:09:29.727  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 12:09:29.727  1590  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:29.732  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 12:09:29.732  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:09:29.749  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:09:29.749  1590  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-02 12:09:29.751  1590  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 12:09:29.751  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.751  1856  1856 D SplitUIManager: split_name #11 / not available #0
09-02 12:09:29.752  1856  1856 D SplitUIService: removed split : 
09-02 12:09:29.756  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 12:09:29.756  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:29.757  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:09:29.757  1590  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 12:09:29.761  1590  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 12:09:29.761  1590  1646 D KeyguardModel: createShortcutInfo...
,09-02 12:09:29.769  1590  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:29.769  1590  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 12:09:29.769  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 12:09:29.770  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:09:29.774  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:09:29.774  1590  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 12:09:29.775  1037  1037 I art     : Explicit concurrent mark sweep GC freed 82509(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.418ms total 224.920ms
09-02 12:09:29.777  1037  1125 I art     : WaitForGcToComplete blocked for 204.758ms for cause Explicit
09-02 12:09:29.781  1856  1856 D SplitUIManager: split_name #11 / not available #0
09-02 12:09:29.781  1856  1856 I SplitUIService: split app #11
,09-02 12:09:29.782  1590  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 12:09:29.782  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.785  1590  1590 D KeyguardModel: handleShortcutListChanged...
09-02 12:09:29.785  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 12:09:29.790  1590  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 12:09:29.790  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.791  1590  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 12:09:29.791  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.792  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:09:29.792  1590  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-02 12:09:29.794  1590  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 12:09:29.794  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.796  1037  1873 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:09:29.796  1037  1873 V SIM_STK : Menu title from STK is T-Mobile
09-02 12:09:29.799  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:09:29.799  1590  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 12:09:29.800  1590  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 12:09:29.800  1590  1646 D KeyguardModel: createShortcutInfo...
09-02 12:09:29.808  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 12:09:29.808  1590  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 12:09:29.809  1590  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 12:09:29.809  1590  1646 D KeyguardModel: createShortcutInfo...
,09-02 12:09:29.820  8379  8379 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 12:09:29.821  8379  8379 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-02 12:09:29.822  8379  8379 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6670
09-02 12:09:29.839  1590  1590 D KeyguardModel: handleShortcutListChanged...
09-02 12:09:29.839  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-02 12:09:29.869  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:29.885  1037  1037 D administrator: Handling package changes for user 0
09-02 12:09:29.885  1037  2019 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 12:09:29.886  7877  7877 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 12:09:29.890  1037  1919 V SIM_STK : Menu title from STK is T-Mobile
,09-02 12:09:29.904  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:29.910  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.912  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.914  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.916  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.918  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:29.921  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.923  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 12:09:29.947  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 12:09:29.954  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-02 12:09:29.956  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-02 12:09:29.958  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-02 12:09:29.958  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:29.960  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-02 12:09:29.962  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-02 12:09:29.963  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-02 12:09:29.964  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-02 12:09:29.969  2214  2214 I ConfigService: onCreate
09-02 12:09:29.971  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-02 12:09:29.974  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-02 12:09:29.978  2214  2214 I ConfigService: onBind returning update interface
,09-02 12:09:29.994  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-02 12:09:29.994  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-02 12:09:29.994  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 12:09:29.996  1037  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-02 12:09:29.997  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-02 12:09:29.997  2214  2214 I ConfigService: onBind returning config service
09-02 12:09:29.998  2020  2020 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-02 12:09:29.999  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-02 12:09:29.999  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.001  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{353e11d4 u0 com.lge.launcher2/.Launcher t5} time:211303
09-02 12:09:30.001  2214  2214 I ConfigService: onDestroy
09-02 12:09:30.003  1037  1125 I art     : Explicit concurrent mark sweep GC freed 8175(466KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 9.027ms total 208.354ms
09-02 12:09:30.007  2020  2172 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-02 12:09:30.008  2020  2172 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-02 12:09:30.011  1804  8450 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-02 12:09:30.024  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-02 12:09:30.026  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 12:09:30.026  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.033  2020  2020 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-02 12:09:30.035  2561  2561 D [Concierge]Service: onStartCommand(). Type : 8
09-02 12:09:30.036  2561  2561 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-02 12:09:30.036  2561  2561 D [Concierge]Service: Update widget ID : 11
09-02 12:09:30.038  2020  2020 D [Concierge]WidgetView: change position of spinner
,09-02 12:09:30.041  2020  2020 I [Concierge]WidgetView: initWebView(). Time : 1472810970041
09-02 12:09:30.041  2561  2561 D [Concierge]Service: onStartCommand(). Type : 0
09-02 12:09:30.041  5912  8456 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-02 12:09:30.058  1804  8458 I PeopleContactsSync: CP2 sync disabled
,09-02 12:09:30.062  2020  2020 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 988940941
09-02 12:09:30.062  2020  2020 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-02 12:09:30.062  1804  5287 I Icing   : doRemovePackageData com.test.thalitest
09-02 12:09:30.062  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-02 12:09:30.063  7259  7259 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-02 12:09:30.065  2020  2020 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@6067836
09-02 12:09:30.065  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-02 12:09:30.066  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 12:09:30.066  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.070  1804  8457 W GmsApplication: Using Auth Proxy for data requests.
09-02 12:09:30.072  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-02 12:09:30.073  2020  2020 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-02 12:09:30.073  2020  2020 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 12:09:30.073  2020  2020 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472810786205, New one : 1472810970041
09-02 12:09:30.073  2020  2020 D [Concierge]WidgetView: Unregister all receivers
,09-02 12:09:30.073  2020  2020 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 12:09:30.074  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.076  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-02 12:09:30.077  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-02 12:09:30.079  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-02 12:09:30.081  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-02 12:09:30.082  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-02 12:09:30.083  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.083  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.095  2214  2238 I art     : Explicit concurrent mark sweep GC freed 6442(370KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 788us total 21.475ms
,09-02 12:09:30.108  1037  1059 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8461 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-02 12:09:30.112  2357  8460 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-02 12:09:30.132  1804  8457 W GmsApplication: Using Auth Proxy for data requests.
,09-02 12:09:30.151  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-02 12:09:30.159  2020  2020 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-02 12:09:30.160  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-02 12:09:30.161  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 12:09:30.194  7805  7805 I UEI.SmartControl: Supports setup maps: true
09-02 12:09:30.197  7805  7805 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 12:09:30.197  7805  7805 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 12:09:30.197  7805  7805 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 12:09:30.197  7805  7805 I UEI.SmartControl: ### init IR Blaster...
,09-02 12:09:30.200  8414  8414 D AndroidRuntime: Shutting down VM
09-02 12:09:30.202  8461  8461 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:30.202  8461  8461 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 12:09:30.203  2020  2020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25621afe time:211505
09-02 12:09:30.204  7805  7805 D serial_port: Configuring serial port
09-02 12:09:30.204  7805  7805 E UEI.SmartControl: UEIBLaster setting for 616
09-02 12:09:30.204  7805  7805 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 12:09:30.204  7805  7805 I UEI.SmartControl: configuring settings for MAXQ616
09-02 12:09:30.204  7805  7805 I UEI.SmartControl: Get version...
09-02 12:09:30.208  8461  8461 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 12:09:30.208  8461  8461 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 12:09:30.220  7805  8480 D UEI.SmartControl: serial port data available: 21
,09-02 12:09:30.246  7805  7805 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 12:09:30.246  7805  7805 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 12:09:30.246  7805  7805 I UEI.SmartControl: QS saving settings...
09-02 12:09:30.246  7805  7805 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 12:09:30.258  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:09:30.259  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8482 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-02 12:09:30.262  8461  8461 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-02 12:09:30.263  7805  8480 D UEI.SmartControl: serial port data available: 4
09-02 12:09:30.271  8461  8461 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-02 12:09:30.289  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 12:09:30.290  7805  8501 I UEI.SmartControl: Device manager: loading config....
09-02 12:09:30.290  7805  8501 D UEI.SmartControl: ----------- loading internal config...
09-02 12:09:30.291  7805  7805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-02 12:09:30.291  7805  7805 E UEI.SmartControl: Services init done
09-02 12:09:30.291  7805  7805 D UEI.SmartControl: QS Service init finished
09-02 12:09:30.292  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 12:09:30.293  7805  7805 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 12:09:30.293  7805  7805 D UEI.SmartControl: QS Service version code: 201091
09-02 12:09:30.293  7805  7805 D UEI.SmartControl: Service requested: Control
09-02 12:09:30.299  7805  8501 E UEI.SmartControl: Loading SETTINGS...
,09-02 12:09:30.302  7805  8501 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 12:09:30.303  8461  8461 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 12:09:30.304  7805  7805 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 12:09:30.305  8379  8379 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-02 12:09:30.305  7805  7821 I UEI.SmartControl: ------ IControl API: 11
09-02 12:09:30.305  7805  7821 D UEI.SmartControl: File observer start...
09-02 12:09:30.305  7805  7821 E UEI.SmartControl: IR Port is disabled: false
09-02 12:09:30.305  7805  7821 D UEI.SmartControl: Starting file observer...
09-02 12:09:30.306  7805  7805 D UEI.SmartControl: Internal service binding...
09-02 12:09:30.306  7805  7821 I UEI.SmartControl: Registering callback...
09-02 12:09:30.307  7805  7820 I UEI.SmartControl: ------ IControl API: 19
09-02 12:09:30.307  7805  7820 I UEI.SmartControl: Registering Services Ready callback...
09-02 12:09:30.307  7805  7820 I UEI.SmartControl: Notify client services are ready...
09-02 12:09:30.308  8379  8394 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-02 12:09:30.311  7805  8500 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 12:09:30.312  7805  8500 D UEI.SmartControl: -----service ready thread exits
09-02 12:09:30.312  8379  8395 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-02 12:09:30.312  8379  8436 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-02 12:09:30.312  8379  8436 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-02 12:09:30.312  8379  8379 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-02 12:09:30.313  8379  8379 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-02 12:09:30.313  7805  7821 I UEI.SmartControl: ------ IControl API: 8
,09-02 12:09:30.314  8379  8379 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-02 12:09:30.314  8379  8379 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-02 12:09:30.314  8379  8379 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-02 12:09:30.314  8379  8379 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-02 12:09:30.315  8379  8379 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-02 12:09:30.315  8379  8379 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-02 12:09:30.316  8379  8379 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-02 12:09:30.319  8379  8379 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-02 12:09:30.320  1037  1962 I ActivityManager: Killing 7905:com.google.android.talk/u0a72 (adj 15): empty #17
09-02 12:09:30.337  8461  8461 D LgDataFeature: LgDataFeature() Constructor: none
09-02 12:09:30.337  8461  8461 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 12:09:30.352  2020  2020 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-02 12:09:30.387  2020  2856 I GBoardtInterface: onReloaded()
,09-02 12:09:30.389  1037  1962 I ActivityManager: Killing 7463:com.google.android.gms.unstable/u0a5 (adj 15): empty #18
09-02 12:09:30.392  2020  2020 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-02 12:09:30.445  1037  1764 W libprocessgroup: failed to open /acct/uid_10072/pid_7905/cgroup.procs: No such file or directory
,09-02 12:09:30.451  1037  2019 W libprocessgroup: failed to open /acct/uid_10005/pid_7463/cgroup.procs: No such file or directory
09-02 12:09:30.452  3797  3812 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 12:09:30.463  3797  4918 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-02 12:09:30.486  1892  1892 D ActionManagerService: notifyUserLog: 1000001
09-02 12:09:30.488  3797  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 12:09:30.489  3797  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-02 12:09:30.498  1892  1892 D ActionManagerService: notifyUserLog: 1000001
09-02 12:09:30.500  3797  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 12:09:30.500  3797  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 12:09:30.500  3797  4922 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-02 12:09:30.500  3797  4922 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-02 12:09:30.504  3797  3812 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-02 12:09:30.509  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-02 12:09:30.509  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-02 12:09:30.513  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-02 12:09:30.513  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,09-02 12:09:30.516  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-02 12:09:30.517  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 12:09:30.550  8461  8461 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-02 12:09:30.558  7982  7982 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
09-02 12:09:30.559  1037  1687 I ActivityManager: Killing 8001:com.android.vending/u0a44 (adj 15): empty #17
09-02 12:09:30.619  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-02 12:09:30.619  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-02 12:09:30.619  1037  1059 W libprocessgroup: failed to open /acct/uid_10044/pid_8001/cgroup.procs: No such file or directory

```
